<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T14:55:57+00:00",
  "source_file": "README.md",
  "language_code": "lt"
}
-->
> Pastaba: Ši dokumentacija nuolat atnaujinama, kad atspindėtų naujausius pokyčius.

> ⚠️ Šis saugyklos pavyzdys sukurtas siekiant parodyti
> automatizuotą dokumentacijos lokalizaciją naudojant Localizeflow.
>
> Originalus turinys paremtas
> Microsoft „AZD for Beginners“ projektu.


# AZD Pradedantiesiems: Struktūruota mokymosi kelionė

![AZD-for-beginners](../../translated_images/azdbeginners.5527441dd9f74068.lt.png) 

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## Pradžia su šiuo kursu

Sekite šiuos žingsnius, kad pradėtumėte savo AZD mokymosi kelionę:

1. **Sukurti šaką (Fork) saugykloje**: Spauskite [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)
2. **Klonuoti saugyklą**: `git clone https://github.com/microsoft/azd-for-beginners.git`
3. **Prisijungti prie bendruomenės**: [Azure Discord Communities](https://discord.com/invite/ByRwuEEgH4) – ekspertų pagalbai
4. **Pasirinkti mokymosi kelią**: Pasirinkite žemiau esantį skyrių, atitinkantį jūsų patirties lygį

### Daugiakalbė palaikymas

#### Automatizuoti vertimai (visada atnaujinti)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](./README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Norite klonuoti vietoje?**

> Šioje saugykloje yra daugiau nei 50 kalbų vertimų, kurie žymiai padidina atsisiuntimo dydį. Norėdami klonuoti be vertimų, naudokite branduolio atsisiuntimą (sparse checkout):
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Tai suteikia viską, ko reikia kursui užbaigti, su daug greitesniu atsisiuntimu.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## Kurso apžvalga

Įvaldykite Azure Developer CLI (azd) per struktūruotus skyrius, skirtus palaipsniui mokytis. **Dėmesys skiriamas AI taikomųjų programų diegimui su Microsoft Foundry integracija.**

### Kodėl šis kursas yra būtinas šiuolaikiniams kūrėjams

Remiantis Microsoft Foundry Discord bendruomenės įžvalgomis, **45% kūrėjų nori naudoti AZD AI užduotims**, tačiau susiduria su iššūkiais, tokiais kaip:
- Sudėtingos daugelio paslaugų AI architektūros
- Geriausios praktikos AI gamybos diegimui  
- Azure AI paslaugų integracija ir konfigūracija
- AI darbo krūvių kainų optimizavimas
- AI diegimo problemų sprendimas

### Mokymosi tikslai

Baigę šį struktūruotą kursą, jūs:
- **Įvaldysite AZD pagrindus**: svarbiausios sąvokos, diegimas ir konfigūracija
- **Diegsite AI taikomąsias programas**: naudodami AZD ir Microsoft Foundry paslaugas
- **Įgyvendinsite infrastruktūrą kaip kodą**: valdykite Azure išteklius su Bicep šablonais
- **Spręsite diegimo problemas**: diagnozuokite ir taisykite problemas
- **Optimizuosite gamybai**: saugumas, mastelio keitimas, stebėjimas ir išlaidų valdymas
- **Kursite daugiaagentinius sprendimus**: diegsite sudėtingas AI architektūras

## 📚 Mokymosi skyriai

*Pasirinkite mokymosi kelią pagal savo patirties lygį ir tikslus*

### 🚀 1 skyrius: Pagrindai ir greitas startas
**Reikalavimai:** Azure prenumerata, pagrindinės komandų eilutės žinios  
**Trukmė:** 30-45 minučių  
**Sudėtingumas:** ⭐

#### Ką išmoksite
- Azure Developer CLI pagrindai
- AZD diegimas jūsų platformoje
- Pirmasis sėkmingas diegimas

#### Mokymosi šaltiniai
- **🎯 Pradėkite čia**: [Kas yra Azure Developer CLI?](../..)
- **📖 Teorija**: [AZD pagrindai](docs/getting-started/azd-basics.md) – pagrindinės sąvokos ir terminai
- **⚙️ Diegimas**: [Diegimas ir nustatymas](docs/getting-started/installation.md) – platformai pritaikyti gidai
- **🛠️ Praktika**: [Jūsų pirmasis projektas](docs/getting-started/first-project.md) – žingsnis po žingsnio vadovas
- **📋 Greita nuoroda**: [Komandų atmintinė](resources/cheat-sheet.md)

#### Praktinės užduotys
```bash
# Greitas diegimo patikrinimas
azd version

# Diegkite savo pirmąją programą
azd init --template todo-nodejs-mongo
azd up
```

**💡 Skyrius baigtas:** Sėkmingai įdiegti paprastą žiniatinklio programą į Azure naudojant AZD

**✅ Sėkmės patvirtinimas:**
```bash
# Baigus 1 skyrių, turėtumėte sugebėti:
azd version              # Rodo įdiegtą versiją
azd init --template todo-nodejs-mongo  # Inicijuoja projektą
azd up                  # Diegia į Azure
azd show                # Rodo veikiančios programos URL
# Programa atsidaro naršyklėje ir veikia
azd down --force --purge  # Išvalo resursus
```

**📊 Laiko sąnaudos:** 30-45 min  
**📈 Įgūdžių lygis po:** Gali savarankiškai diegti pagrindines programas

**✅ Sėkmės patvirtinimas:**
```bash
# Baigus 1 skyrių, turėtumėte gebėti:
azd version              # Rodo įdiegtą versiją
azd init --template todo-nodejs-mongo  # Inicializuoja projektą
azd up                  # Diegia į Azure
azd show                # Rodo veikiančios programos URL
# Programa atsidaro naršyklėje ir veikia
azd down --force --purge  # Pašalina resursus
```

**📊 Laiko sąnaudos:** 30-45 min  
**📈 Įgūdžių lygis po:** Gali savarankiškai diegti pagrindines programas

---

### 🤖 2 skyrius: AI pirma kūrimas (Rekomenduojama AI kūrėjams)
**Reikalavimai:** 1 skyrius įveiktas  
**Trukmė:** 1-2 valandos  
**Sudėtingumas:** ⭐⭐

#### Ką išmoksite
- Microsoft Foundry integracija su AZD
- AI varomų taikomųjų programų diegimas
- AI paslaugų konfigūracijų supratimas

#### Mokymosi šaltiniai
- **🎯 Pradėkite čia**: [Microsoft Foundry integracija](docs/microsoft-foundry/microsoft-foundry-integration.md)
- **📖 Modelių diegimas**: [AI modelių diegimas](docs/microsoft-foundry/ai-model-deployment.md) – diekite ir valdykite AI modelius
- **🛠️ Dirbtuvės**: [AI dirbtuvių laboratorija](docs/microsoft-foundry/ai-workshop-lab.md) – paruoškite AI sprendimus AZD naudojimui
- **🎥 Interaktyvus vadovas**: [Dirbtuvių medžiaga](workshop/README.md) – mokymasis per naršyklę su MkDocs * DevContainer aplinka
- **📋 Šablonai**: [Microsoft Foundry šablonai](../..)
- **📝 Pavyzdžiai**: [AZD diegimo pavyzdžiai](examples/README.md)

#### Praktinės užduotys
```bash
# Diegti savo pirmąją DI programą
azd init --template azure-search-openai-demo
azd up

# Išbandykite papildomas DI šablonus
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```

**💡 Skyrius baigtas:** Diegti ir konfigūruoti AI varomą pokalbių programą su RAG galimybėmis

**✅ Sėkmės patvirtinimas:**
```bash
# Po 2 skyriaus turėtumėte gebėti:
azd init --template azure-search-openai-demo
azd up
# Išbandyti dirbtinio intelekto pokalbių sąsają
# Užduoti klausimus ir gauti dirbtinio intelekto atsakymus su šaltiniais
# Patikrinti, ar veikia paieškos integracija
azd monitor  # Patikrinti, ar Application Insights rodo telemetriją
azd down --force --purge
```

**📊 Laiko sąnaudos:** 1-2 valandos  
**📈 Įgūdžių lygis po:** Gali diegti ir konfigūruoti gamybai paruoštas AI programas  
**💰 Kainų supratimas:** Supranta apie 80-150 $/mėn kūrimo išlaidas, 300-3500 $/mėn gamybos išlaidas

#### 💰 AI diegimų kaštų svarstymai

**Kūrimo aplinka (maždaug 80-150 $ per mėn):**
- Azure OpenAI (mokestis už naudojimąsi): 0-50 $/mėn (pagal tokenų suvartojimą)
- AI paieška (pagrindinis lygis): 75 $/mėn
- Konteinerių programos (naudojimo pagrindu): 0-20 $/mėn
- Saugykla (standartinė): 1-5 $/mėn

**Gamybos aplinka (maždaug 300-3500+ $ per mėn):**
- Azure OpenAI (PTU stabiliai veiklai): 3000+ $/mėn ARBA mokestis už naudojimąsi su aukštu tūriu
- AI paieška (standartinis lygis): 250 $/mėn
- Konteinerių programos (dedikuota): 50-100 $/mėn
- Application Insights: 5-50 $/mėn
- Saugykla (premium): 10-50 $/mėn

**💡 Kaštų optimizavimo patarimai:**
- Mokymuisi naudokite **nemokamą Azure OpenAI lygį** (įskaičiuota 50 000 tokenų per mėn)
- Naudokite `azd down`, kad atjungtumėte išteklius, kai nevystote aktyviai
- Pradėkite nuo mokėjimo pagal naudojimąsi, PTU imkite tik gamybai
- Naudokite `azd provision --preview`, kad įvertintumėte išlaidas prieš diegimą
- Įjunkite auto-mastelio keitimą: mokėkite tik už faktinį naudojimą

**Kaštų stebėjimas:**
```bash
# Patikrinkite numatomas mėnesines išlaidas
azd provision --preview

# Stebėkite faktines išlaidas Azure portale
az consumption budget list --resource-group <your-rg>
```

---

### ⚙️ 3 skyrius: Konfigūracija ir autentifikacija
**Reikalavimai:** 1 skyrius baigtas  
**Trukmė:** 45-60 minučių  
**Sudėtingumas:** ⭐⭐

#### Ką išmoksite
- Aplinkos konfigūracija ir valdymas
- Autentifikacijos ir saugumo geriausios praktikos
- Išteklių pavadinimų suteikimas ir organizavimas

#### Mokymosi šaltiniai
- **📖 Konfigūracija**: [Konfigūracijos vadovas](docs/getting-started/configuration.md) – aplinkos nustatymas
- **🔐 Saugumas**: [Autentifikacijos šablonai ir valdomos tapatybės](docs/getting-started/authsecurity.md) – autentifikacijos šablonai
- **📝 Pavyzdžiai**: [Duomenų bazės programos pavyzdys](examples/database-app/README.md) – AZD duomenų bazės pavyzdžiai

#### Praktinės užduotys
- Konfigūruoti kelias aplinkas (dev, staging, prod)
- Nustatyti valdomą tapatybę autentifikacijai
- Įgyvendinti aplinkai pritaikytas konfigūracijas

**💡 Skyrius baigtas:** Valdyti kelias aplinkas su tinkama autentifikacija ir saugumu

---

### 🏗️ 4 skyrius: Infrastruktūra kaip kodas ir diegimas
**Reikalavimai:** Baigti 1-3 skyrius  
**Trukmė:** 1-1.5 valandos  
**Sudėtingumas:** ⭐⭐⭐

#### Ką išmoksite
- Pažangūs diegimo šablonai
- Infrastruktūra kaip kodas su Bicep
- Išteklių paruošimo strategijos

#### Mokymosi šaltiniai
- **📖 Diegimas**: [Diegimo vadovas](docs/deployment/deployment-guide.md) – pilni darbo procesai
- **🏗️ Paruošimas**: [Išteklių paruošimas](docs/deployment/provisioning.md) – Azure išteklių valdymas
- **📝 Pavyzdžiai**: [Konteinerių programos pavyzdys](../../examples/container-app) – konteinerizuoti diegimai

#### Praktinės užduotys
- Kurti pasirinktinius Bicep šablonus
- Diegti daugiapaslapių paslaugų programas
- Įgyvendinti mėlyno-žalio (blue-green) diegimo strategijas

**💡 Skyrius baigtas:** Sėkmingai diegti sudėtingas daugiaservisines programas naudodami pasirinktinius infrastruktūros šablonus

---
### 🎯 5 skyrius: Daugiaveiksnių dirbtinio intelekto sprendimai (Išplėstinė dalis)
**Pranešimas**: 1-2 skyrius baigti  
**Trukmė**: 2-3 valandos  
**Sudėtingumas**: ⭐⭐⭐⭐

#### Ko išmoksite
- Daugiaveiksnių architektūros modeliai
- Agentų koordinavimas ir valdymas
- Produkcijai pasiruošę DI diegimai

#### Mokymosi ištekliai
- **🤖 Rekomenduojamas projektas**: [Daugiaveiksnių sprendimas mažmeninei prekybai](examples/retail-scenario.md) – Pilnas įgyvendinimas
- **🛠️ ARM šablonai**: [ARM šablonų paketas](../../examples/retail-multiagent-arm-template) – Vieno mygtuko diegimas
- **📖 Architektūra**: [Daugiaveiksnių koordinavimo modeliai](/docs/pre-deployment/coordination-patterns.md) – Modeliai

#### Praktinės užduotys
```bash
# Įdiekite visą mažmeninės prekybos daugialypės agentų sprendimą
cd examples/retail-multiagent-arm-template
./deploy.sh

# Ištirkite agentų konfigūracijas
az deployment group show --resource-group <rg-name> --name <deployment-name>
```

**💡 Skyriaus tikslas**: Įdiegti ir valdyti produkcijai pasiruošusią daugiaveiksnių DI sprendimą su Klientų ir Inventoriaus agentais

---

### 🔍 6 skyrius: Priešdiegiminė validacija ir planavimas
**Pranešimas**: 4 skyrius baigtas  
**Trukmė**: 1 valanda  
**Sudėtingumas**: ⭐⭐

#### Ko išmoksite
- Talpos planavimas ir resursų validacija
- SKU atrankos strategijos
- Priešdiegiminiai patikrinimai ir automatizacija

#### Mokymosi ištekliai
- **📊 Planavimas**: [Talpos planavimas](docs/pre-deployment/capacity-planning.md) – Resursų validacija
- **💰 Atranka**: [SKU atranka](docs/pre-deployment/sku-selection.md) – Ekonomiški sprendimai
- **✅ Validacija**: [Priešdiegiminiai patikrinimai](docs/pre-deployment/preflight-checks.md) – Automatizuoti skriptai

#### Praktinės užduotys
- Paleisti talpos validacijos skriptus  
- Optimizuoti SKU atrankas pagal kainą  
- Įgyvendinti automatizuotus priešdiegiminius patikrinimus

**💡 Skyriaus tikslas**: Validuoti ir optimizuoti diegimus prieš jų vykdymą

---

### 🚨 7 skyrius: Gedimų paieška ir derinimas
**Pranešimas**: Bet kuris diegimo skyrius baigtas  
**Trukmė**: 1-1,5 valandos  
**Sudėtingumas**: ⭐⭐

#### Ko išmoksite
- Sistemingos derinimo metodikos  
- Dažniausios problemos ir sprendimai  
- DI specifinės gedimų paieškos

#### Mokymosi ištekliai
- **🔧 Dažnos problemos**: [Dažnos problemos](docs/troubleshooting/common-issues.md) – DUK ir sprendimai  
- **🕵️ Derinimas**: [Derinimo gidas](docs/troubleshooting/debugging.md) – Žingsnis po žingsnio strategijos  
- **🤖 DI problemos**: [DI gedimų paieška](docs/troubleshooting/ai-troubleshooting.md) – DI paslaugų problemos  

#### Praktinės užduotys
- Nustatyti diegimo klaidas  
- Išspręsti autentifikacijos problemas  
- Derinti DI paslaugų jungtis

**💡 Skyriaus tikslas**: Nepriklausomai diagnozuoti ir spręsti dažniausias diegimo problemas

---

### 🏢 8 skyrius: Produkcijos ir įmonių modeliai
**Pranešimas**: 1-4 skyrius baigti  
**Trukmė**: 2-3 valandos  
**Sudėtingumas**: ⭐⭐⭐⭐

#### Ko išmoksite
- Produkcijos diegimo strategijos  
- Įmonių saugumo modeliai  
- Stebėjimas ir kaštų optimizavimas

#### Mokymosi ištekliai
- **🏭 Produkcija**: [DI produkcijos geriausios praktikos](docs/microsoft-foundry/production-ai-practices.md) – Įmonių modeliai  
- **📝 Pavyzdžiai**: [Mikropaslaugų pavyzdys](../../examples/microservices) – Sudėtingos architektūros  
- **📊 Stebėjimas**: [Application Insights integracija](docs/pre-deployment/application-insights.md) – Stebėsena

#### Praktinės užduotys
- Įgyvendinti įmonių saugumo modelius  
- Nustatyti išsamų stebėjimą  
- Įdiegti gamyboje su tinkama valdymo sistema

**💡 Skyriaus tikslas**: Įdiegti įmonėms skirtas programas su pilnomis gamybos galimybėmis

---

## 🎓 Darbo grupės apžvalga: Praktinis mokymasis

> **⚠️ DARBO GRUPĖS STATUSAS: Aktyvus vystymas**  
> Mokymo medžiaga šiuo metu ruošiama ir tobulinama. Pagrindiniai moduliai veikia, bet kai kurios išplėstinės dalys dar nebaigtos. Aktyviai dirbame, kad užbaigtume visą turinį. [Sekite pažangą →](workshop/README.md)

### Interaktyvios darbo grupės medžiagos
**Išsamus praktinis mokymasis su naršyklės aplinkos įrankiais ir vedamomis užduotimis**

Mūsų darbo grupės medžiaga suteikia struktūruotą, interaktyvų mokymosi patyrimą, papildantį aukščiau pateiktą skyrių programą. Darbo grupė skirta tiek savarankiškam mokymuisi, tiek vedamiems užsiėmimams.

#### 🛠️ Darbo grupės ypatybės
- **Naršyklės sąsaja**: Pilnas MkDocs pagrindu veikiantis kursas su paieška, kopijavimo ir temos funkcijomis  
- **GitHub Codespaces integracija**: Vieno mygtuko kūrimo aplinkos nustatymas  
- **Struktūrinis mokymosi kelias**: 7 žingsnių vedamos užduotys (iš viso 3,5 val.)  
- **Atrask → Įdiek → Priderink**: Progresinė metodika  
- **Interaktyvi DevContainer aplinka**: Iš anksto sukonfigūruoti įrankiai ir priklausomybės

#### 📚 Darbo grupės struktūra
Darbo grupės metodika seką **Atrask → Įdiek → Priderink** modelį:

1. **Atrankos etapas** (45 min.)  
   - Susipažinimas su Microsoft Foundry šablonais ir paslaugomis  
   - Daugiaveiksnių architektūros modelių peržiūra  
   - Diegimo reikalavimų ir prielaidų peržiūra  

2. **Diegimo etapas** (2 val.)  
   - Praktinis DI programų diegimas naudojant AZD  
   - Azure DI paslaugų ir galinių taškų konfigūracija  
   - Saugumo ir autentifikacijos modelių įgyvendinimas  

3. **Priderinimo etapas** (45 min.)  
   - Programų modifikavimas specifiniams atvejams  
   - Produkcijai tinkamo diegimo optimizavimas  
   - Stebėjimo ir kaštų valdymo įgyvendinimas

#### 🚀 Pradėkite nuo darbo grupės
```bash
# 1 variantas: GitHub Codespaces (rekomenduojama)
# Spustelėkite "Code" → "Create codespace on main" įrašų saugykloje

# 2 variantas: Vietinė plėtra
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# Vykdykite nustatymo instrukcijas workshop/README.md faile
```

#### 🎯 Darbo grupės mokymosi tikslai
Užbaigus darbo grupę, dalyviai sugebės:  
- **Diegti produkcines DI programas**: Naudojant AZD ir Microsoft Foundry paslaugas  
- **Valdyti daugiaveiksnius architektūros sprendimus**: Įgyvendinti koordinuotus DI agentų sprendimus  
- **Taikyti saugumo geriausias praktikas**: Konfigūruoti autentifikaciją ir prieigos kontrolę  
- **Optimizuoti mastelį**: Projektuoti ekonomiškus ir našius diegimus  
- **Spręsti diegimo problemas**: Nepriklausomai šalinant dažnas problemas  

#### 📖 Darbo grupės ištekliai
- **🎥 Interaktyvus gidas**: [Darbo grupės medžiaga](workshop/README.md) – Naršyklėje veikianti mokymosi aplinka  
- **📋 Žingsnis po žingsnio instrukcijos**: [Vedamos užduotys](../../workshop/docs/instructions) – Išsamios gairės  
- **🛠️ DI darbo grupės laboratorija**: [DI laboratorija](docs/microsoft-foundry/ai-workshop-lab.md) – DI orientuotos užduotys  
- **💡 Greitas startas**: [Darbo grupės nustatymo gidas](workshop/README.md#quick-start) – Aplinkos konfigūracija

**Puikiai tinka**: Įmonių mokymams, universitetų kursams, savarankiškam mokymuisi ir programuotojų stovykloms.

---

## 📖 Kas yra Azure Developer CLI?

Azure Developer CLI (azd) – tai programuotojams skirtas komandų eilutės įrankis, kuris spartina programų kūrimo ir diegimo Azure procesą. Jis suteikia:

- **Šablonais pagrįsti diegimai** – Naudokite iš anksto sukurtus šablonus dažnai pasitaikantiems programų modeliams  
- **Infrastruktūros kaip kodo valdymas** – Valdykite Azure resursus naudodami Bicep ar Terraform  
- **Integruoti darbo procesai** – Sklandžiai teikite, diegkite ir stebėkite programas  
- **Draugiškas programuotojui** – Optimizuotas produktyvumui ir patirčiai

### **AZD + Microsoft Foundry: Idealu DI diegimams**

**Kodėl rinktis AZD DI sprendimams?** AZD sprendžia pagrindines DI kūrėjų problemas:

- **Pasiruošę DI šablonai** – Iš anksto sukonfigūruoti Azure OpenAI, Cognitive Services ir ML veiklos šablonai  
- **Saugūs DI diegimai** – Integruoti saugumo modeliai DI paslaugoms, API raktams ir modelių galiniams taškams  
- **Produkcinio DI modeliai** – Geriausios praktikos skaliabiliems, ekonomiškiems DI programų diegimams  
- **Pilnai integruoti DI procesai** – Nuo modelio kūrimo iki produkcinio diegimo su tinkama stebėsena  
- **Kaštų optimizavimas** – Išmanūs išteklių paskirstymo ir mastelio keitimo sprendimai DI veiklai  
- **Microsoft Foundry integracija** – Sklandi MS Foundry modelių katalogo ir galinių taškų integracija

---

## 🎯 Šablonų ir pavyzdžių biblioteka

### Rekomenduojama: Microsoft Foundry šablonai
**Pradėkite čia, jei diegiate DI programas!**

> **Pastaba:** Šie šablonai atspindi įvairius DI modelius. Kai kurie yra išoriniai Azure pavyzdžiai, kiti – vietiniai įgyvendinimai.

| Šablonas | Skyrius | Sudėtingumas | Paslaugos | Tipas |
|----------|---------|--------------|-----------|-------|
| [**Pradėkite su DI pokalbiais**](https://github.com/Azure-Samples/get-started-with-ai-chat) | 2 skyrius | ⭐⭐ | AzureOpenAI + Azure AI Model Inference API + Azure AI Search + Azure Container Apps + Application Insights | Išorinis |
| [**Pradėkite su DI agentais**](https://github.com/Azure-Samples/get-started-with-ai-agents) | 2 skyrius | ⭐⭐ | Azure AI Agent Service + AzureOpenAI + Azure AI Search + Azure Container Apps + Application Insights | Išorinis |
| [**Azure Search + OpenAI demonstracija**](https://github.com/Azure-Samples/azure-search-openai-demo) | 2 skyrius | ⭐⭐ | AzureOpenAI + Azure AI Search + App Service + Storage | Išorinis |
| [**AtidarykiteAI pokalbių programėlės spartusis startas**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | 2 skyrius | ⭐ | AzureOpenAI + Container Apps + Application Insights | Išorinis |
| [**Agent OpenAI Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | 5 skyrius | ⭐⭐⭐ | AzureOpenAI + Azure Functions + Prompty | Išorinis |
| [**Contoso Chat RAG**](https://github.com/Azure-Samples/contoso-chat) | 8 skyrius | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Cosmos DB + Container Apps | Išorinis |
| [**Daugiaveiksnių sprendimas mažmeninei prekybai**](examples/retail-scenario.md) | 5 skyrius | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Storage + Container Apps + Cosmos DB | **Vietinis** |

### Rekomenduojama: Visapusiški mokymosi scenarijai
**Produkcinio lygio programų šablonai susieti su mokymosi skyriais**

| Šablonas | Mokymosi skyrius | Sudėtingumas | Svarbiausia išmokti |
|----------|------------------|--------------|---------------------|
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | 2 skyrius | ⭐ | Pagrindinės DI diegimo schemos |
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | 2 skyrius | ⭐⭐ | RAG diegimas su Azure AI Search |
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | 4 skyrius | ⭐⭐ | Dokumentų intelektas integracija |
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | 5 skyrius | ⭐⭐⭐ | Agentų karkasas ir funkcijų kvietimas |
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | 8 skyrius | ⭐⭐⭐ | Įmonių DI koordinavimas |
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | 5 skyrius | ⭐⭐⭐⭐ | Daugiaveiksnių architektūra su Klientų ir Inventoriaus agentais |

### Mokymasis pagal pavyzdžių tipą

> **📌 Vietiniai vs Išoriniai pavyzdžiai:**  
> **Vietiniai pavyzdžiai** (šioje saugykloje) = Iš karto paruošti naudoti  
> **Išoriniai pavyzdžiai** (Azure pavyzdžiai) = Kopijuojami iš nurodytų saugyklų

#### Vietiniai pavyzdžiai (paruošti naudoti)
- [**Daugiaveiksnių sprendimas mažmeninei prekybai**](examples/retail-scenario.md) – Pilnai paruoštas produkcinis įgyvendinimas su ARM šablonais
  - Daugiaveiksnių architektūra (Klientų + Inventoriaus agentai)  
  - Išsamus stebėjimas ir vertinimas  
  - Vieno paspaudimo diegimas per ARM šabloną

#### Vietiniai pavyzdžiai – Konteinerių programos (2-5 skyriai)
**Išsamūs konteinerių diegimo pavyzdžiai šiame repo:**
- [**Konteinerių programų pavyzdžiai**](examples/container-app/README.md) – Pilnas konteinerizuotų diegimų vadovas  
  - [Paprastas Flask API](../../examples/container-app/simple-flask-api) – Pagrindinis REST API su scale-to-zero  
  - [Mikropaslaugų architektūra](../../examples/container-app/microservices) – Produkcijai paruoštas daugiapaslaugis diegimas  
  - Greito starto, produkcijos ir pažangaus diegimo modeliai  
  - Stebėjimo, saugumo ir kaštų optimizavimo gairės

#### Išoriniai pavyzdžiai – Paprastos programos (1-2 skyriai)
**Klonuokite šias Azure pavyzdžių saugyklas pradžiai:**
- [Paprasta žiniatinklio programa - Node.js + MongoDB](https://github.com/Azure-Samples/todo-nodejs-mongo) – Pagrindinių diegimo modelių pavyzdys  
- [Statinis svetainės tinklas - React SPA](https://github.com/Azure-Samples/todo-csharp-sql-swa-func) – Statinės turinio diegimas  
- [Konteinerių programa - Python Flask](https://github.com/Azure-Samples/container-apps-store-api-microservice) – REST API diegimas

#### Išoriniai pavyzdžiai – Duomenų bazės integracija (3-4 skyriai)  
- [Duomenų bazės programa - C# + SQL](https://github.com/Azure-Samples/todo-csharp-sql) – Duomenų bazės jungčių modeliai  
- [Funkcijos + Cosmos DB](https://github.com/Azure-Samples/todo-python-mongo-swa-func) – Serverless duomenų srautas

#### Išoriniai pavyzdžiai – Išplėstiniai modeliai (4-8 skyriai)
- [Java mikropaslaugos](https://github.com/Azure-Samples/java-microservices-aca-lab) – Daugiapaslaugės architektūros  
- [Konteinerių programų darbai](https://github.com/Azure-Samples/container-apps-jobs) – Fono apdorojimas  
- [Įmonių ML pipeline](https://github.com/Azure-Samples/mlops-v2) – Produkcijai paruošti ML modeliai

### Išorinės šablonų kolekcijos
- [**Oficiali AZD šablonų galerija**](https://azure.github.io/awesome-azd/) - Atrinkti oficialių ir bendruomenės šablonų rinkiniai  
- [**Azure Developer CLI šablonai**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - Microsoft Learn šablonų dokumentacija  
- [**Pavyzdžių katalogas**](examples/README.md) - Vietiniai mokymosi pavyzdžiai su išsamiais paaiškinimais

---

## 📚 Mokymosi ištekliai ir nuorodos

### Greitos nuorodos
- [**Komandų dažniausiai naudojamų sąrašas**](resources/cheat-sheet.md) - Esminės azd komandos sugrupuotos pagal skyrių  
- [**Sąvokų žodynas**](resources/glossary.md) - Azure ir azd terminologija  
- [**DUK**](resources/faq.md) - Dažniausiai užduodami klausimai sugrupuoti pagal mokymosi skyrių  
- [**Mokymosi vadovas**](resources/study-guide.md) - Išsamūs praktikos pratimai

### Praktiniai užsiėmimai
- [**DI dirbtuvės laboratorija**](docs/microsoft-foundry/ai-workshop-lab.md) - Padarykite savo DI sprendimus diegiamus naudojant AZD (2–3 valandos)  
- [**Interaktyvus darbo vadovas**](workshop/README.md) - Naršyklėje veikianti dirbtuvė su MkDocs ir DevContainer aplinka  
- [**Struktūruotas mokymosi kelias**](../../workshop/docs/instructions) - 7 žingsnių vadovaujami pratimai (Atranka → Diegimas → Pritaikymas)  
- [**AZD pradedantiesiems dirbtuvės**](workshop/README.md) - Pilni praktinės dirbtuvės medžiaga su GitHub Codespaces integracija

### Išoriniai mokymosi ištekliai
- Azure Developer CLI dokumentacija: https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/  
- Azure architektūros centras: https://learn.microsoft.com/en-us/azure/architecture/  
- Azure kainų skaičiuoklė: https://azure.microsoft.com/pricing/calculator/  
- Azure būsenos puslapis: https://status.azure.com/

---

## 🔧 Greitos būdų sprendimo gairės

**Dažniausios problemos, su kuriomis susiduria pradedantieji, ir greiti sprendimai:**

### ❌ „azd: komanda nerasta“

```bash
# Pirmiausia įdiekite AZD
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Patikrinkite diegimą
azd version
```

### ❌ „Nerasta prenumeratos“ arba „Prenumerata nepriskirta“

```bash
# Išvardinti galimus paskyrimus
az account list --output table

# Nustatyti numatytąjį paskyrimą
az account set --subscription "<subscription-id-or-name>"

# Nustatyti AZD aplinkai
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Patikrinti
az account show
```

### ❌ „Nepakanka kvotos“ arba „Kvota viršyta“

```bash
# Išbandykite kitą Azure regioną
azd env set AZURE_LOCATION "westus2"
azd up

# Arba naudokite mažesnius SKU kūrimo metu
# Redaguokite infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```

### ❌ „azd up“ nepavyksta pusė kelio

```bash
# Parinktis 1: Išvalyti ir bandyti dar kartą
azd down --force --purge
azd up

# Parinktis 2: Tiesiog sutvarkyti infrastruktūrą
azd provision

# Parinktis 3: Patikrinti išsamius žurnalus
azd show
azd logs
```

### ❌ „Autentifikavimas nepavyko“ arba „Žetonas pasibaigęs“

```bash
# Pakartotinai autentifikuoti
az logout
az login

azd auth logout
azd auth login

# Patvirtinkite autentifikavimą
az account show
```

### ❌ „Išteklius jau egzistuoja“ arba pavadinimų konfliktai

```bash
# AZD sugeneruoja unikalius pavadinimus, bet jei kyla konfliktas:
azd down --force --purge

# Tada bandykite dar kartą su švaria aplinka
azd env new dev-v2
azd up
```

### ❌ Šablono diegimas užtrunka per ilgai

**Įprasti laukimo laikai:**  
- Paprasta interneto programa: 5–10 minučių  
- Programa su duomenų baze: 10–15 minučių  
- DI taikomosios programos: 15–25 minutės (OpenAI teikimas vyksta lėtai)

```bash
# Patikrinkite pažangą
azd show

# Jei užstrigote daugiau nei 30 minučių, patikrinkite Azure Portal:
azd monitor
# Ieškokite nepavykusių diegimų
```

### ❌ „Leidimas uždraustas“ arba „Draudžiama“

```bash
# Patikrinkite savo Azure vaidmenį
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Jums reikia bent „Contributor“ vaidmens
# Paprašykite savo Azure administratoriaus suteikti:
# - Contributor (resursams)
# - User Access Administrator (vaidmenų paskyrimams)
```

### ❌ Negaliu rasti įdiegto programos URL

```bash
# Rodyti visus paslaugų galinius taškus
azd show

# Arba atidarykite Azure portalą
azd monitor

# Patikrinti konkrečią paslaugą
azd env get-values
# Ieškoti *_URL kintamųjų
```

### 📚 Išsamūs trikčių šalinimo ištekliai

- **Dažnų problemų vadovas:** [Išsamūs sprendimai](docs/troubleshooting/common-issues.md)  
- **DI specifinės problemos:** [DI trikčių šalinimas](docs/troubleshooting/ai-troubleshooting.md)  
- **Derinimo vadovas:** [Žingsnis po žingsnio derinimas](docs/troubleshooting/debugging.md)  
- **Kreipkitės pagalbos:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🔧 Greitos būdų sprendimo gairės

**Dažniausios problemos, su kuriomis susiduria pradedantieji, ir greiti sprendimai:**

<details>
<summary><strong>❌ „azd: komanda nerasta“</strong></summary>

```bash
# Pirmiausia įdiekite AZD
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Patikrinkite diegimą
azd version
```
</details>

<details>
<summary><strong>❌ „Nerasta prenumeratos“ arba „Prenumerata nepriskirta“</strong></summary>

```bash
# Išvardinti galimus prenumeratas
az account list --output table

# Nustatyti numatytąją prenumeratą
az account set --subscription "<subscription-id-or-name>"

# Nustatyti AZD aplinkai
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Patikrinti
az account show
```
</details>

<details>
<summary><strong>❌ „Nepakanka kvotos“ arba „Kvota viršyta“</strong></summary>

```bash
# Išbandykite kitą Azure regioną
azd env set AZURE_LOCATION "westus2"
azd up

# Arba naudokite mažesnius SKU kūrimo metu
# Redaguokite infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>

<details>
<summary><strong>❌ „azd up“ nepavyksta pusė kelio</strong></summary>

```bash
# Parinktis 1: Išvalyti ir bandyti dar kartą
azd down --force --purge
azd up

# Parinktis 2: Tiesiog taisyti infrastruktūrą
azd provision

# Parinktis 3: Patikrinti detalius žurnalus
azd show
azd logs
```
</details>

<details>
<summary><strong>❌ „Autentifikavimas nepavyko“ arba „Žetonas pasibaigęs“</strong></summary>

```bash
# Pakartotinai autentifikuoti
az logout
az login

azd auth logout
azd auth login

# Patvirtinti autentifikaciją
az account show
```
</details>

<details>
<summary><strong>❌ „Išteklius jau egzistuoja“ arba pavadinimų konfliktai</strong></summary>

```bash
# AZD generuoja unikalius pavadinimus, bet jei kyla konfliktas:
azd down --force --purge

# Tada pabandykite dar kartą su nauja aplinka
azd env new dev-v2
azd up
```
</details>

<details>
<summary><strong>❌ Šablono diegimas užtrunka per ilgai</strong></summary>

**Įprasti laukimo laikai:**  
- Paprasta interneto programa: 5–10 minučių  
- Programa su duomenų baze: 10–15 minučių  
- DI taikomosios programos: 15–25 minutės (OpenAI teikimas vyksta lėtai)

```bash
# Patikrinkite pažangą
azd show

# Jei užstrigote >30 minučių, patikrinkite Azure portalą:
azd monitor
# Ieškokite nepavykusių diegimų
```
</details>

<details>
<summary><strong>❌ „Leidimas uždraustas“ arba „Draudžiama“</strong></summary>

```bash
# Patikrinkite savo Azure vaidmenį
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Jums reikia bent "Contributor" vaidmens
# Paprašykite savo Azure administratoriaus suteikti:
# - Contributor (ištekliams)
# - User Access Administrator (vaidmenų priskyrimams)
```
</details>

<details>
<summary><strong>❌ Negaliu rasti įdiegto programos URL</strong></summary>

```bash
# Rodyti visus paslaugų galinius taškus
azd show

# Arba atidaryti Azure portalą
azd monitor

# Patikrinti konkrečią paslaugą
azd env get-values
# Ieškoti *_URL kintamųjų
```
</details>

### 📚 Išsamūs trikčių šalinimo ištekliai

- **Dažnų problemų vadovas:** [Išsamūs sprendimai](docs/troubleshooting/common-issues.md)  
- **DI specifinės problemos:** [DI trikčių šalinimas](docs/troubleshooting/ai-troubleshooting.md)  
- **Derinimo vadovas:** [Žingsnis po žingsnio derinimas](docs/troubleshooting/debugging.md)  
- **Kreipkitės pagalbos:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🎓 Kurso baigimas ir sertifikavimas

### Pažangos stebėjimas  
Stebėkite savo mokymosi pažangą kiekviename skyriuje:

- [ ] **1 skyrius**: Pamatai ir greitas pradėjimas ✅  
- [ ] **2 skyrius**: DI pirmenybės vystymas ✅  
- [ ] **3 skyrius**: Konfigūravimas ir autentifikavimas ✅  
- [ ] **4 skyrius**: Infrastruktūra kaip kodas ir diegimas ✅  
- [ ] **5 skyrius**: Daugiaveikslių DI sprendimai ✅  
- [ ] **6 skyrius**: Pre-diegimo patikra ir planavimas ✅  
- [ ] **7 skyrius**: Trikčių šalinimas ir derinimas ✅  
- [ ] **8 skyrius**: Produkcijos ir įmonių modeliai ✅

### Mokymosi patvirtinimas  
Baigus kiekvieną skyrių, patvirtinkite savo žinias:  
1. **Praktinis užduotis**: Baigti praktinį diegimą skyriuje  
2. **Žinių patikra**: Peržiūrėti DUK skyrių  
3. **Bendruomenės diskusija**: Dalintis patirtimi Azure Discord  
4. **Kitas skyrius**: Eiti prie kito sudėtingumo lygio

### Kurso baigimo naudos  
Baigus visus skyrius, turėsite:  
- **Produkcinę patirtį**: Įdiegėte realias DI programas Azure  
- **Profesinius įgūdžius**: Įmonių lygio diegimo gebėjimus  
- **Bendruomenės pripažinimą**: Aktyvus Azure kūrėjų bendruomenės narys  
- **Karjeros iššūkį**: Paklausi AZD ir DI diegimo ekspertizė

---

## 🤝 Bendruomenė ir palaikymas

### Pagalba ir palaikymas  
- **Techninės problemos**: [Praneškite apie klaidas ir prašykite funkcijų](https://github.com/microsoft/azd-for-beginners/issues)  
- **Mokymosi klausimai**: [Microsoft Azure Discord bendruomenė](https://discord.gg/microsoft-azure) ir [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)  
- **DI specifinė pagalba**: Prisijunkite prie [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)  
- **Dokumentacija**: [Oficiali Azure Developer CLI dokumentacija](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)

### Bendruomenės įžvalgos iš Microsoft Foundry Discord

**Naujausios apklausos #Azure kanale rezultatai:**  
- **45%** kūrėjų nori naudoti AZD DI darbams  
- **Pagrindinės problemos:** Daugiapakopė paslaugų diegimas, kredencialų valdymas, produkcijos paruošimas  
- **Dažniausiai prašomi dalykai:** DI specifiniai šablonai, trikčių šalinimo vadovai, geriausios praktikos

**Prisijunkite prie mūsų bendruomenės norėdami:**  
- Dalintis savo AZD + DI patirtimi ir gauti pagalbą  
- Gauti ankstyvas naujų DI šablonų peržiūras  
- Prisidėti prie DI diegimo geriausių praktikų  
- Daryti įtaką būsimoms DI + AZD funkcijoms

### Kviečiame prisidėti prie kurso
Laukiame jūsų indėlio! Prašome perskaityti mūsų [Prisidėjimo vadovą](CONTRIBUTING.md) dėl detalių apie:  
- **Turinio patobulinimus**: Tobulinti esamus skyrius ir pavyzdžius  
- **Naujus pavyzdžius**: Pridėti realaus pasaulio scenarijus ir šablonus  
- **Vertimus**: Padėti palaikyti daugiakalbį palaikymą  
- **Klaidų pranešimus**: Tobulinti tikslumą ir aiškumą  
- **Bendruomenės standartus**: Laikytis mūsų įtraukių bendruomenės taisyklių

---

## 📄 Kurso informacija

### Licencija  
Šis projektas licencijuojamas pagal MIT licenciją - žr. [LICENSE](../../LICENSE) failą dėl detalių.

### Susiję Microsoft mokymosi ištekliai

Mūsų komanda kuria kitus išsamius mokymosi kursus:

<!-- CO-OP TRANSLATOR OTHER COURSES START -->
### LangChain  
[![LangChain4j pradedantiesiems](https://img.shields.io/badge/LangChain4j%20for%20Beginners-22C55E?style=for-the-badge&&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchain4j-for-beginners)  
[![LangChain.js pradedantiesiems](https://img.shields.io/badge/LangChain.js%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchainjs-for-beginners?WT.mc_id=m365-94501-dwahlin)

---

### Azure / Edge / MCP / Agentai  
[![AZD pradedantiesiems](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)  
[![Edge DI pradedantiesiems](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)  
[![MCP pradedantiesiems](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)  
[![DI agentai pradedantiesiems](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Generatyvinis DI serijos  
[![Generatyvinis DI pradedantiesiems](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)  
[![Generatyvinis DI (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)  
[![Generatyvinis DI (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)  
[![Generatyvinis DI (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---
 
### Pagrindinis mokymasis  
[![ML pradedantiesiems](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![Duomenų mokslas pradedantiesiems](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![DI pradedantiesiems](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Kibernetinis saugumas pradedantiesiems](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Žiniatinklio kūrimas pradedantiesiems](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![Daiktų internetas pradedantiesiems](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![XR kūrimas pradedantiesiems](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### „Copilot“ serija
[![Copilot DI poriniam programavimui](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![Copilot C#/.NET platformai](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Copilot nuotykiai](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ Kurso navigacija

**🚀 Pasiruošę pradėti mokytis?**

**Pradedantieji**: Pradėkite nuo [1 skyriaus: pagrindai ir greitas startas](../..)  
**DI kūrėjai**: Pereikite į [2 skyrių: DI-pirmasis kūrimas](../..)  
**Patyrę kūrėjai**: Pradėkite nuo [3 skyriaus: konfigūracija ir autentifikacija](../..)

**Tolimesni žingsniai**: [Pradėkite 1 skyrių – AZD pagrindai](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Atsakomybės apribojimas**:  
Šis dokumentas buvo išverstas naudojant dirbtinio intelekto vertimo paslaugą [Co-op Translator](https://github.com/Azure/co-op-translator). Nors stengiamės užtikrinti tikslumą, atkreipkite dėmesį, kad automatizuoti vertimai gali turėti klaidų ar netikslumų. Pirminė dokumento versija gimtąja kalba laikoma autoritetingu šaltiniu. Svarbiai informacijai rekomenduojama kreiptis į profesionalius vertėjus. Mes neatsakome už bet kokius nesusipratimus ar neteisingus aiškinimus, kilusius naudojant šį vertimą.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->