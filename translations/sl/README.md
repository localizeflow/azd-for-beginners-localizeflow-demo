<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T14:44:29+00:00",
  "source_file": "README.md",
  "language_code": "sl"
}
-->
> Opomba: Ta dokumentacija se nenehno posodablja, da odraža najnovejše spremembe.

> ⚠️ Ta repozitorij je demo, ustvarjen za prikaz avtomatizirane lokalizacije dokumentacije z uporabo Localizeflow.
>
> Izvirna vsebina temelji na
> Microsoftovem projektu "AZD za začetnike".


# AZD za začetnike: Strukturirano učna pot

![AZD-for-beginners](../../translated_images/azdbeginners.5527441dd9f74068.sl.png) 

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## Začetek s tem tečajem

Sledite tem korakom, da začnete svojo učno pot za AZD:

1. **Razvejite repozitorij**: Kliknite [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)
2. **Klonirajte repozitorij**: `git clone https://github.com/microsoft/azd-for-beginners.git`
3. **Pridružite se skupnosti**: [Azure Discord skupnosti](https://discord.com/invite/ByRwuEEgH4) za strokovno podporo
4. **Izberite svojo učno pot**: Izberite poglavje spodaj, ki ustreza vaši ravni izkušenj

### Podpora za več jezikov

#### Avtomatizirani prevodi (vedno posodobljeni)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabščina](../ar/README.md) | [Bengalščina](../bn/README.md) | [Bolgarščina](../bg/README.md) | [Burmanski (Myanmar)](../my/README.md) | [Kitajščina (poenostavljena)](../zh/README.md) | [Kitajščina (tradicionalna, Hong Kong)](../hk/README.md) | [Kitajščina (tradicionalna, Macau)](../mo/README.md) | [Kitajščina (tradicionalna, Tajvan)](../tw/README.md) | [Hrvaščina](../hr/README.md) | [Češčina](../cs/README.md) | [Danska](../da/README.md) | [Nizozemščina](../nl/README.md) | [Estonščina](../et/README.md) | [Finščina](../fi/README.md) | [Francoščina](../fr/README.md) | [Nemščina](../de/README.md) | [Grščina](../el/README.md) | [Hebrejščina](../he/README.md) | [Hindi](../hi/README.md) | [Madžarščina](../hu/README.md) | [Indonezijščina](../id/README.md) | [Italijanščina](../it/README.md) | [Japonščina](../ja/README.md) | [Kannada](../kn/README.md) | [Korejščina](../ko/README.md) | [Litovščina](../lt/README.md) | [Malajščina](../ms/README.md) | [Malajalščina](../ml/README.md) | [Maratščina](../mr/README.md) | [Nepalščina](../ne/README.md) | [Nigerijski pidžin](../pcm/README.md) | [Norveščina](../no/README.md) | [Perzijsko (Farsi)](../fa/README.md) | [Poljščina](../pl/README.md) | [Portugalski (Brazilija)](../br/README.md) | [Portugalski (Portugalska)](../pt/README.md) | [Pandžabski (Gurmukhi)](../pa/README.md) | [Romunščina](../ro/README.md) | [Ruščina](../ru/README.md) | [Srbski (cirilica)](../sr/README.md) | [Slovaščina](../sk/README.md) | [Slovenščina](./README.md) | [Španščina](../es/README.md) | [Svahili](../sw/README.md) | [Švedščina](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Tajščina](../th/README.md) | [Turščina](../tr/README.md) | [Ukrajinščina](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamščina](../vi/README.md)

> **Raje klonirate lokalno?**

> Ta repozitorij vključuje prevode v več kot 50 jezikov, kar znatno poveča velikost prenosa. Če želite klonirati brez prevodov, uporabite sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Tako boste imeli vse, kar potrebujete za dokončanje tečaja, s precej hitrejšim prenosom.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## Pregled tečaja

Obvladujte Azure Developer CLI (azd) skozi strukturirana poglavja, zasnovana za postopno učenje. **Poseben poudarek na uvajanju AI aplikacij z integracijo Microsoft Foundry.**

### Zakaj je ta tečaj bistven za sodobne razvijalce

Na podlagi vpogledov skupnosti Microsoft Foundry Discord, **45 % razvijalcev želi uporabljati AZD za AI delovne obremenitve**, vendar se soočajo z izzivi pri:
- Kompleksnih večstoritevnih AI arhitekturah
- Najboljših praksah uvajanja AI v produkcijo  
- Integraciji in konfiguraciji Azure AI storitev
- Optimizaciji stroškov za AI delovne obremenitve
- Odpravljanju težav specifičnih za uvajanje AI

### Cilji učenja

Z dokončanjem tega strukturiranega tečaja boste:
- **Obvladali osnove AZD**: Temeljni pojmi, namestitev in konfiguracija
- **Uvajali AI aplikacije**: Uporaba AZD z Microsoft Foundry storitvami
- **Implementirali infrastrukturo kot kodo**: Upravljanje Azure virov z Bicep predlogami
- **Reševali težave pri uvajanju**: Odpravljanje pogostih napak in razhroščevanje
- **Optimizirali za produkcijo**: Varnost, prilagajanje, spremljanje in upravljanje stroškov
- **Gradili rešitve z več agenti**: Uvajanje kompleksnih AI arhitektur

## 📚 Učna poglavja

*Izberite svojo učno pot glede na raven izkušenj in cilje*

### 🚀 Poglavje 1: Osnove in hiter začetek
**Zahteve**: Azure naročnina, osnovno znanje ukazne vrstice  
**Trajanje**: 30-45 minut  
**Kompleksnost**: ⭐

#### Kaj se boste naučili
- Razumevanje osnov Azure Developer CLI
- Namestitev AZD na vašo platformo
- Vaša prva uspešna namestitev

#### Učni viri
- **🎯 Začnite tukaj**: [Kaj je Azure Developer CLI?](../..)
- **📖 Teorija**: [AZD osnove](docs/getting-started/azd-basics.md) - Temeljni pojmi in terminologija
- **⚙️ Namestitev**: [Namestitev in nastavitev](docs/getting-started/installation.md) - Vodniki za posamezne platforme
- **🛠️ Praktično**: [Vaš prvi projekt](docs/getting-started/first-project.md) - Navodila po korakih
- **📋 Hiter pregled**: [Komandni spisek](resources/cheat-sheet.md)

#### Praktični vajeni
```bash
# Hitri pregled namestitve
azd version

# Namestite svojo prvo aplikacijo
azd init --template todo-nodejs-mongo
azd up
```

**💡 Izhodna točka poglavja**: Uspešno namestite preprosto spletno aplikacijo v Azure z uporabo AZD

**✅ Preverjanje uspešnosti:**
```bash
# Po zaključku Poglavja 1 morate biti sposobni:
azd version              # Prikaže nameščeno različico
azd init --template todo-nodejs-mongo  # Inicializira projekt
azd up                  # Izvede namestitev v Azure
azd show                # Prikaže URL delujoče aplikacije
# Aplikacija se odpre v brskalniku in deluje
azd down --force --purge  # Očisti vire
```

**📊 Časovna vložek:** 30-45 minut  
**📈 Stopnja znanja po tem:** Samostojno uvajanje osnovnih aplikacij

**✅ Preverjanje uspešnosti:**
```bash
# Po zaključku poglavja 1 bi morali biti sposobni:
azd version              # Prikaže nameščeno različico
azd init --template todo-nodejs-mongo  # Inicializira projekt
azd up                  # Namesti v Azure
azd show                # Prikaže URL delujoče aplikacije
# Aplikacija se odpre v brskalniku in deluje
azd down --force --purge  # Počisti vire
```

**📊 Časovna vložek:** 30-45 minut  
**📈 Stopnja znanja po tem:** Samostojno uvajanje osnovnih aplikacij

---

### 🤖 Poglavje 2: AI-prvi razvoj (priporočeno za AI razvijalce)
**Zahteve**: Poglavje 1 dokončano  
**Trajanje**: 1-2 uri  
**Kompleksnost**: ⭐⭐

#### Kaj se boste naučili
- Integracija Microsoft Foundry z AZD
- Uvajanje AI-podprtih aplikacij
- Razumevanje konfiguracij AI storitev

#### Učni viri
- **🎯 Začnite tukaj**: [Integracija Microsoft Foundry](docs/microsoft-foundry/microsoft-foundry-integration.md)
- **📖 Vzorci**: [Uvajanje AI modelov](docs/microsoft-foundry/ai-model-deployment.md) - Uvajanje in upravljanje AI modelov
- **🛠️ Delavnica**: [AI delavnica laboratorij](docs/microsoft-foundry/ai-workshop-lab.md) - Pripravite AI rešitve za AZD
- **🎥 Interaktivni vodič**: [Delavnični materiali](workshop/README.md) - Učenje preko brskalnika z MkDocs * DevContainer okolje
- **📋 Predloge**: [Microsoft Foundry predloge](../..)
- **📝 Primeri**: [Primeri uvajanja AZD](examples/README.md)

#### Praktični vajeni
```bash
# Namestite svojo prvo AI aplikacijo
azd init --template azure-search-openai-demo
azd up

# Preizkusite dodatne AI predloge
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```

**💡 Izhodna točka poglavja**: Uvajanje in konfiguracija AI-podprte klepetalne aplikacije z RAG zmožnostmi

**✅ Preverjanje uspešnosti:**
```bash
# Po 2. poglavju bi morali biti sposobni:
azd init --template azure-search-openai-demo
azd up
# Preizkusiti AI klepetalni vmesnik
# Postavljati vprašanja in dobiti odgovore, podprte z AI, z viri
# Preveriti, ali integracija iskanja deluje
azd monitor  # Preveriti, da Application Insights prikazuje telemetrijo
azd down --force --purge
```

**📊 Časovna vložek:** 1-2 uri  
**📈 Stopnja znanja po tem:** Sposobnost uvajanja in konfiguriranja produkcijsko pripravljenih AI aplikacij  
**💰 Zavedanje stroškov:** Razumevanje stroškov razvoja 80-150 $/mesec, produkcija 300-3500 $/mesec

#### 💰 Stroški za uvajanje AI aplikacij

**Razvojno okolje (ocenjeno 80-150 $/mesec):**
- Azure OpenAI (Plačilo glede na porabo): 0-50 $/mesec (glede na uporabo tokenov)
- AI Search (osnovna raven): 75 $/mesec
- Container Apps (porabniški način): 0-20 $/mesec
- Shranjevanje (standardno): 1-5 $/mesec

**Produkcijsko okolje (ocenjeno 300-3.500+ $/mesec):**
- Azure OpenAI (PTU za konsistentno zmogljivost): 3.000+ $/mesec ALI plačilo glede na porabo pri velikem obsegu
- AI Search (standardna raven): 250 $/mesec
- Container Apps (namenski način): 50-100 $/mesec
- Application Insights: 5-50 $/mesec
- Shranjevanje (premium): 10-50 $/mesec

**💡 Nasveti za optimizacijo stroškov:**
- Uporabljajte **Brezplačni nivo** Azure OpenAI za učenje (vključenih 50.000 tokenov/mesec)
- Za začasno neaktivnost zaženite `azd down`, da sprostite vire
- Začnite z obračunom po porabi, PTU nadgradite le za produkcijo
- Uporabite `azd provision --preview` za oceno stroškov pred uvajanjem
- Omogočite samodejno prilagajanje: plačajte samo za dejansko uporabo

**Nadzor stroškov:**
```bash
# Preveri ocenjene mesečne stroške
azd provision --preview

# Spremljaj dejanske stroške v Azure portalu
az consumption budget list --resource-group <your-rg>
```

---

### ⚙️ Poglavje 3: Konfiguracija in avtentikacija
**Zahteve**: Poglavje 1 dokončano  
**Trajanje**: 45-60 minut  
**Kompleksnost**: ⭐⭐

#### Kaj se boste naučili
- Konfiguracija in upravljanje okolij
- Avtentikacija in najboljše varnostne prakse
- Poimenovanje in organizacija virov

#### Učni viri
- **📖 Konfiguracija**: [Vodnik za konfiguracijo](docs/getting-started/configuration.md) - Nastavitev okolja
- **🔐 Varnost**: [Vzorce avtentikacije in upravljane identitete](docs/getting-started/authsecurity.md) - Vzorce avtentikacije
- **📝 Primeri**: [Primer aplikacije za bazo podatkov](examples/database-app/README.md) - AZD primerek baze podatkov

#### Praktični vajeni
- Konfigurirajte več okolij (dev, staging, prod)
- Nastavite avtentikacijo z upravljano identiteto
- Izvedite konfiguracije, specifične za okolje

**💡 Izhodna točka poglavja**: Upravljajte več okolij z ustrezno avtentikacijo in varnostjo

---

### 🏗️ Poglavje 4: Infrastruktura kot koda in uvajanje
**Zahteve**: Poglavja 1-3 dokončana  
**Trajanje**: 1-1.5 ure  
**Kompleksnost**: ⭐⭐⭐

#### Kaj se boste naučili
- Napredni vzorci uvajanja
- Infrastruktura kot koda s pomočjo Bicep
- Strategije zagotavljanja virov

#### Učni viri
- **📖 Uvajanje**: [Vodnik za uvajanje](docs/deployment/deployment-guide.md) - Celotni delovni tokovi
- **🏗️ Zagotavljanje virov**: [Zagotavljanje virov](docs/deployment/provisioning.md) - Upravljanje Azure virov
- **📝 Primeri**: [Primer Container App](../../examples/container-app) - Uvajanje v vsebnikih

#### Praktični vajeni
- Ustvarite prilagojene Bicep predloge
- Uvajajte večstoritevne aplikacije
- Izvedite strategije uvajanja blue-green

**💡 Izhodna točka poglavja**: Uvajajte kompleksne večstoritevne aplikacije z uporabo prilagojenih infrastrukturnih predlog

### 🎯 Poglavje 5: Rešitve z več agenti (napredno)  
**Pogoj za začetek**: Poglavji 1-2 dokončani  
**Trajanje**: 2-3 ure  
**Zahtevnost**: ⭐⭐⭐⭐

#### Kaj se boste naučili  
- Vzorce večagentne arhitekture  
- Orkestracijo in koordinacijo agentov  
- Postavitve umetne inteligence pripravljenih za produkcijo

#### Viri za učenje  
- **🤖 Izpostavljen projekt**: [Rešitev z več agenti za trgovino](examples/retail-scenario.md) - Popolna implementacija  
- **🛠️ ARM predloge**: [Pakiranje ARM predlog](../../examples/retail-multiagent-arm-template) - Namestitev z enim klikom  
- **📖 Arhitektura**: [Vzorce koordinacije več agentov](/docs/pre-deployment/coordination-patterns.md) - Vzorce

#### Praktične vaje  
```bash
# Namestite popolno maloprodajno rešitev z več agenti
cd examples/retail-multiagent-arm-template
./deploy.sh

# Raziščite konfiguracije agentov
az deployment group show --resource-group <rg-name> --name <deployment-name>
```
  
**💡 Rezultat poglavja**: Postavite in upravljajte produkcijsko rešitev z več agenti z agenti za stranke in zaloge  

---

### 🔍 Poglavje 6: Preverjanje in načrtovanje pred postavitvijo  
**Pogoj za začetek**: Poglavje 4 dokončano  
**Trajanje**: 1 ura  
**Zahtevnost**: ⭐⭐

#### Kaj se boste naučili  
- Načrtovanje zmogljivosti in preverjanje virov  
- Strategije izbire SKU  
- Predpripravljalni pregledi in avtomatizacija

#### Viri za učenje  
- **📊 Načrtovanje**: [Načrtovanje zmogljivosti](docs/pre-deployment/capacity-planning.md) - Preverjanje virov  
- **💰 Izbira**: [Izbira SKU](docs/pre-deployment/sku-selection.md) - Stroškovno učinkovite izbire  
- **✅ Validacija**: [Predpripravljalni pregledi](docs/pre-deployment/preflight-checks.md) - Avtomatizirani skripti

#### Praktične vaje  
- Zaženite skripte za preverjanje zmogljivosti  
- Optimizirajte izbiro SKU za stroške  
- Uvedite avtomatizirane preglede pred postavitvijo

**💡 Rezultat poglavja**: Preverite in optimizirajte postavitve pred zagonom  

---

### 🚨 Poglavje 7: Odpravljanje težav in razhroščevanje  
**Pogoj za začetek**: Vsaj eno poglavje o postavitvi zaključeno  
**Trajanje**: 1-1.5 ure  
**Zahtevnost**: ⭐⭐

#### Kaj se boste naučili  
- Sistematične metode razhroščevanja  
- Pogoste težave in rešitve  
- Odpravljanje težav, specifičnih za umetno inteligenco

#### Viri za učenje  
- **🔧 Pogoste težave**: [Pogoste težave](docs/troubleshooting/common-issues.md) - Pogosta vprašanja in rešitve  
- **🕵️ Razhroščevanje**: [Vodnik za razhroščevanje](docs/troubleshooting/debugging.md) - Strategije korak za korakom  
- **🤖 Težave AI**: [Odpravljanje težav AI](docs/troubleshooting/ai-troubleshooting.md) - Težave storitev AI

#### Praktične vaje  
- Diagnostika neuspehov postavitve  
- Reševanje težav z avtentikacijo  
- Razhroščevanje povezljivosti AI storitev

**💡 Rezultat poglavja**: Samostojno diagnosticirajte in rešite pogoste težave pri postavitvah  

---

### 🏢 Poglavje 8: Produkcijski in podjetniški vzorci  
**Pogoj za začetek**: Poglavji 1-4 dokončani  
**Trajanje**: 2-3 ure  
**Zahtevnost**: ⭐⭐⭐⭐

#### Kaj se boste naučili  
- Strategije za produkcijske postavitve  
- Podjetniški varnostni vzorci  
- Nadzor in optimizacija stroškov

#### Viri za učenje  
- **🏭 Produkcija**: [Najboljše prakse za produkcijsko AI](docs/microsoft-foundry/production-ai-practices.md) - Podjetniški vzorci  
- **📝 Primeri**: [Primer mikrostoritev](../../examples/microservices) - Kompleksne arhitekture  
- **📊 Nadzor**: [Integracija Application Insights](docs/pre-deployment/application-insights.md) - Spremljanje

#### Praktične vaje  
- Uvedite varnostne vzorce za podjetja  
- Nastavite celovit nadzor  
- Izvedite postavitev v produkcijsko okolje s pravilnim upravljanjem

**💡 Rezultat poglavja**: Postavite aplikacije pripravljene za podjetje s polno produkcijsko funkcionalnostjo  

---

## 🎓 Pregled delavnice: Izkušnja praktičnega učenja

> **⚠️ STANJE DELAVNICE: Aktivni razvoj**  
> Materiali delavnice so trenutno v postopku razvoja in izpopolnjevanja. Osnovni moduli so funkcionalni, a nekateri naprednejši deli še manjkajo. Aktivno delamo na dokončanju vsebine. [Spremljajte napredek →](workshop/README.md)

### Interaktivni materiali delavnice  
**Celovito praktično učenje z orodji v brskalniku in vodenimi vajami**

Naši materiali delavnice zagotavljajo strukturirano, interaktivno učno izkušnjo, ki dopolnjuje zgornji učni načrt po poglavjih. Delavnica je zasnovana tako za samostojno učenje kot za voden učni proces.

#### 🛠️ Značilnosti delavnice  
- **Vmesnik v brskalniku**: Popolna delavnica na osnovi MkDocs z iskanjem, kopiranjem in temami  
- **Integracija GitHub Codespaces**: Postavitev razvojnega okolja z enim klikom  
- **Strukturirana učna pot**: 7-stopenjske vodene vaje (skupno 3,5 ure)  
- **Odkritje → Postavitev → Prilagoditev**: Postopna metodologija  
- **Interaktivno razvojno okolje DevContainer**: Vnaprej konfigurirana orodja in odvisnosti

#### 📚 Struktura delavnice  
Delavnica sledi metodologiji **Odkritje → Postavitev → Prilagoditev**:

1. **Faza odkritja** (45 minut)  
   - Spoznajte Microsoft Foundry predloge in storitve  
   - Razumite vzorce večagentne arhitekture  
   - Preglejte zahteve za postavitev in pogoje

2. **Faza postavitve** (2 uri)  
   - Praktična postavitev AI aplikacij z AZD  
   - Konfiguracija Azure AI storitev in končnih točk  
   - Uvedba varnostnih in avtentikacijskih vzorcev

3. **Faza prilagoditve** (45 minut)  
   - Prilagodite aplikacije za specifične primere uporabe  
   - Optimizirajte za produkcijsko postavitev  
   - Izvedba nadzora in upravljanja stroškov

#### 🚀 Začetek z delavnico  
```bash
# Možnost 1: GitHub Codespaces (Priporočeno)
# Kliknite "Code" → "Ustvari codespace na main" v repozitoriju

# Možnost 2: Lokalni razvoj
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# Sledite navodilom za nastavitev v workshop/README.md
```
  
#### 🎯 Učni cilji delavnice  
Z dokončanjem delavnice bodo udeleženci:  
- **Postavili produkcijske AI aplikacije**: Uporaba AZD s storitvami Microsoft Foundry  
- **Obvladali večagentne arhitekture**: Uvedba usklajenih AI agentskih rešitev  
- **Uvedli najboljše varnostne prakse**: Konfiguracija avtentikacije in nadzora dostopa  
- **Optimizirali rast**: Oblikovanje stroškovno učinkovitih, zmogljivih postavitev  
- **Odpravljali težave pri postavitvah**: Samostojno reševanje pogostih težav

#### 📖 Viri delavnice  
- **🎥 Interaktivni vodič**: [Materiali delavnice](workshop/README.md) - Učno okolje v brskalniku  
- **📋 Navodila korak za korakom**: [Vodene vaje](../../workshop/docs/instructions) - Podrobni postopki  
- **🛠️ AI delavnica lab**: [AI delavnica lab](docs/microsoft-foundry/ai-workshop-lab.md) - AI osredotočene vaje  
- **💡 Hitri začetek**: [Vodnik za nastavitev delavnice](workshop/README.md#quick-start) - Konfiguracija okolja

**Odlično za**: usposabljanje v podjetjih, univerzitetne tečaje, samostojno učenje in razvojne bootcampe.

---

## 📖 Kaj je Azure Developer CLI?

Azure Developer CLI (azd) je ukazna vrstica, osredotočena na razvijalce, ki pospešuje postopek razvoja in postavitve aplikacij v Azure. Ponuja:

- **Postavitve na osnovi predlog** - Uporaba vnaprej izdelanih predlog za običajne aplikacijske vzorce  
- **Infrastruktura kot koda** - Upravljanje Azure virov z Bicep ali Terraform  
- **Integrirane delovne tokove** - Brezhibna postavitev, upravljanje in nadzor aplikacij  
- **Prijazno za razvijalce** - Optimizirano za produktivnost in uporabniško izkušnjo razvijalcev

### **AZD + Microsoft Foundry: popolno za AI postavitve**

**Zakaj AZD za AI rešitve?** AZD rešuje glavne izzive, s katerimi se srečujejo razvijalci AI:

- **Predloge pripravljene za AI** - Vnaprej konfigurirane predloge za Azure OpenAI, Kognitivne storitve in ML delovne obremenitve  
- **Varne AI postavitve** - Vgrajeni varnostni vzorci za AI storitve, API ključev in končnih točk modelov  
- **Produkcijski AI vzorci** - Najboljše prakse za skalabilne in stroškovno učinkovite AI aplikacije  
- **Celoviti AI delovni tokovi** - Od razvoja modela do produkcijske postavitve z ustreznim nadzorom  
- **Optimizacija stroškov** - Pametno upravljanje virov in strategije skaliranja za AI delovne obremenitve  
- **Integracija Microsoft Foundry** - Neprekinjena povezava s katalogom modelov Microsoft Foundry in končnimi točkami  

---

## 🎯 Knjižnica predlog in primerov

### Izpostavljeno: Microsoft Foundry predloge  
**Začnite tukaj, če uvajate AI aplikacije!**

> **Opomba:** Te predloge prikazujejo različne AI vzorce. Nekatere so zunanje Azure Samples, druge lokalne implementacije.

| Predloga | Poglavje | Zahtevnost | Storitve | Vrsta |
|----------|----------|------------|----------|-------|
| [**Začetek s AI klepetom**](https://github.com/Azure-Samples/get-started-with-ai-chat) | Poglavje 2 | ⭐⭐ | AzureOpenAI + Azure AI Model Inference API + Azure AI Search + Azure Container Apps + Application Insights | Zunanja |
| [**Začetek z AI agenti**](https://github.com/Azure-Samples/get-started-with-ai-agents) | Poglavje 2 | ⭐⭐ | Azure AI Agent Service + AzureOpenAI + Azure AI Search + Azure Container Apps + Application Insights | Zunanja |
| [**Azure Search + OpenAI Demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Poglavje 2 | ⭐⭐ | AzureOpenAI + Azure AI Search + App Service + Storage | Zunanja |
| [**OpenAI Chat App Quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Poglavje 2 | ⭐ | AzureOpenAI + Container Apps + Application Insights | Zunanja |
| [**Agent OpenAI Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Poglavje 5 | ⭐⭐⭐ | AzureOpenAI + Azure Functions + Prompty | Zunanja |
| [**Contoso Chat RAG**](https://github.com/Azure-Samples/contoso-chat) | Poglavje 8 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Cosmos DB + Container Apps | Zunanja |
| [**Rešitev z več agenti za trgovino**](examples/retail-scenario.md) | Poglavje 5 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Storage + Container Apps + Cosmos DB | **Lokalna** |

### Izpostavljeno: Popolni učni scenariji  
**Predloge aplikacij, pripravljene za produkcijo, povezane z učnimi poglavji**

| Predloga | Učno poglavje | Zahtevnost | Ključni nauk |
|----------|---------------|------------|--------------|
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Poglavje 2 | ⭐ | Osnovni vzorci AI postavitve |
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Poglavje 2 | ⭐⭐ | RAG implementacija z Azure AI Search |
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | Poglavje 4 | ⭐⭐ | Integracija inteligence dokumentov |
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Poglavje 5 | ⭐⭐⭐ | Okvir agentov in klicanje funkcij |
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | Poglavje 8 | ⭐⭐⭐ | Orkestracija AI za podjetja |
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | Poglavje 5 | ⭐⭐⭐⭐ | Večagentna arhitektura z agenti za stranke in zaloge |

### Učenje po tipu primerov

> **📌 Lokalni proti zunanjim primerom:**  
> **Lokalni primeri** (v tem repozitoriju) = takoj pripravljeni za uporabo  
> **Zunanji primeri** (Azure Samples) = klonirajte iz povezanih repozitorijev

#### Lokalni primeri (pripravljeni za uporabo)  
- [**Rešitev z več agenti za trgovino**](examples/retail-scenario.md) - Popolna produkcijska implementacija z ARM predlogami  
  - Večagentna arhitektura (agent za stranke + agent za zalogo)  
  - Celovito spremljanje in ocenjevanje  
  - Namestitev z enim klikom prek ARM predloge

#### Lokalni primeri - aplikacije v vsebnikih (poglavja 2-5)  
**Celoviti primeri postavitve vsebnikov v tem repozitoriju:**  
- [**Primeri aplikacij v vsebnikih**](examples/container-app/README.md) - Popoln vodič po postavitvah z vsebniki  
  - [Preprost Flask API](../../examples/container-app/simple-flask-api) - Osnovni REST API s skaliranjem na nič  
  - [Microservices Architecture](../../examples/container-app/microservices) - Produkcijska večstoritevna postavitev  
  - Hitri začetek, produkcija in napredni vzorci postavitve  
  - Navodila za nadzor, varnost in optimizacijo stroškov  

#### Zunanji primeri - enostavne aplikacije (poglavji 1-2)  
**Klonirajte te Azure Samples repozitorije za začetek:**  
- [Simple Web App - Node.js + MongoDB](https://github.com/Azure-Samples/todo-nodejs-mongo) - Osnovni vzorci postavitve  
- [Static Website - React SPA](https://github.com/Azure-Samples/todo-csharp-sql-swa-func) - Postavitev statičnih vsebin  
- [Container App - Python Flask](https://github.com/Azure-Samples/container-apps-store-api-microservice) - Postavitev REST API

#### Zunanji primeri - integracija podatkovnih baz (poglavji 3-4)  
- [Database App - C# + SQL](https://github.com/Azure-Samples/todo-csharp-sql) - Vzorci povezljivosti podatkovnih baz  
- [Functions + Cosmos DB](https://github.com/Azure-Samples/todo-python-mongo-swa-func) - Brezstrežni podatkovni delovni tok

#### Zunanji primeri - napredni vzorci (poglavja 4-8)  
- [Java mikrostoritev](https://github.com/Azure-Samples/java-microservices-aca-lab) - Večstoritevne arhitekture  
- [Container Apps jobs](https://github.com/Azure-Samples/container-apps-jobs) - Ozadinsko procesiranje  
- [Enterprise ML Pipeline](https://github.com/Azure-Samples/mlops-v2) - Produkcijski vzorci ML

### Zunanje zbirke predlog  

- [**Uradna galerija predlog AZD**](https://azure.github.io/awesome-azd/) - Izbrana zbirka uradnih in skupnostnih predlog
- [**Predloge Azure Developer CLI**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - Dokumentacija Microsoft Learn predlog
- [**Mapa primerov**](examples/README.md) - Lokalni učni primeri z podrobnimi razlagami

---

## 📚 Učne vsebine in reference

### Hitre reference
- [**Povzetek ukazov**](resources/cheat-sheet.md) - Bistveni ukazi za azd, organizirani po poglavjih
- [**Slovar izrazov**](resources/glossary.md) - Terminologija Azure in azd  
- [** pogosta vprašanja (FAQ)**](resources/faq.md) - Pogosta vprašanja, organizirana po učnih poglavjih
- [**Studijski vodič**](resources/study-guide.md) - Obsežne vaje za prakso

### Delavnice z vajo v praksi
- [**Delavnica AI**](docs/microsoft-foundry/ai-workshop-lab.md) - Naredite svoje AI rešitve pripravne za AZD-razmestitev (2-3 ure)
- [**Vodnik interaktivne delavnice**](workshop/README.md) - Delavnica v brskalniku z MkDocs in DevContainer okoljem
- [**Strukturirana učna pot**](../../workshop/docs/instructions) - 7 korakov vodene vaje (Odkritje → Razmestitev → Prilagoditev)
- [**Delavnica AZD za začetnike**](workshop/README.md) - Celotne praktične delavnice z GitHub Codespaces integracijo

### Zunanji učni viri
- Dokumentacija Azure Developer CLI (https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)
- Azure Architecture Center (https://learn.microsoft.com/en-us/azure/architecture/)
- Azure cenovni kalkulator (https://azure.microsoft.com/pricing/calculator/)
- Azure Status (https://status.azure.com/)

---

## 🔧 Hiter vodnik za odpravljanje težav

**Pogoste težave, s katerimi se srečujejo začetniki, in takojšnje rešitve:**

### ❌ "azd: ukaz ni najden"

```bash
# Najprej namestite AZD
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Preverite namestitev
azd version
```

### ❌ "Ni najdene naročnine" ali "Naročnina ni nastavljena"

```bash
# Prikaži razpoložljive naročnine
az account list --output table

# Nastavi privzeto naročnino
az account set --subscription "<subscription-id-or-name>"

# Nastavi za okolje AZD
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Preveri
az account show
```

### ❌ "InsufficientQuota" ali "Kvota presežena"

```bash
# Poskusite z drugo Azure regijo
azd env set AZURE_LOCATION "westus2"
azd up

# Ali uporabite manjše SKU-je v razvoju
# Uredite infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```

### ❌ "azd up" ne uspe na polovici poti

```bash
# Možnost 1: Počisti in poskusi znova
azd down --force --purge
azd up

# Možnost 2: Samo popravi infrastrukturo
azd provision

# Možnost 3: Preveri podrobne dnevnike
azd show
azd logs
```

### ❌ "Avtentikacija ni uspela" ali "Potekel žeton"

```bash
# Ponovno se prijavite
az logout
az login

azd auth logout
azd auth login

# Preverite pristnost
az account show
```

### ❌ "Vir že obstaja" ali konflikt imen

```bash
# AZD generira edinstvena imena, vendar če pride do konflikta:
azd down --force --purge

# Potem poskusi znova z novim okoljem
azd env new dev-v2
azd up
```

### ❌ Razmestitev predloge traja predolgo

**Normalni časi čakanja:**
- Preprosta spletna aplikacija: 5-10 minut
- Aplikacija z bazo podatkov: 10-15 minut
- AI aplikacije: 15-25 minut (OpenAI zagotavljanje je počasno)

```bash
# Preveri napredek
azd show

# Če si zataknjen več kot 30 minut, preveri Azure Portal:
azd monitor
# Poišči neuspele namestitve
```

### ❌ "Dostop zavrnjen" ali "Prepovedano"

```bash
# Preverite svojo Azure vlogo
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Potrebujete vsaj vlogo "Contributor"
# Prosite svojega Azure skrbnika, da vam podeli:
# - Contributor (za vire)
# - Administrator dostopa uporabnika (za dodelitve vlog)
```

### ❌ Ne najdem URL-ja razmestitve aplikacije

```bash
# Prikaži vse končne točke storitve
azd show

# Ali odpri Azure Portal
azd monitor

# Preveri določeno storitev
azd env get-values
# Poišči spremenljivke *_URL
```

### 📚 Celotni viri za odpravljanje težav

- **Vodnik za pogoste težave:** [Podrobne rešitve](docs/troubleshooting/common-issues.md)
- **Težave specifične za AI:** [AI odpravljanje težav](docs/troubleshooting/ai-troubleshooting.md)
- **Vodnik za odpravljanje napak:** [Korak za korakom](docs/troubleshooting/debugging.md)
- **Pomoč:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🔧 Hiter vodnik za odpravljanje težav

**Pogoste težave, s katerimi se srečujejo začetniki, in takojšnje rešitve:**

<details>
<summary><strong>❌ "azd: ukaz ni najden"</strong></summary>

```bash
# Najprej namestite AZD
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Preverite namestitev
azd version
```
</details>

<details>
<summary><strong>❌ "Ni najdene naročnine" ali "Naročnina ni nastavljena"</strong></summary>

```bash
# Prikaži razpoložljive naročnine
az account list --output table

# Nastavi privzeto naročnino
az account set --subscription "<subscription-id-or-name>"

# Nastavi za AZD okolje
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Preveri
az account show
```
</details>

<details>
<summary><strong>❌ "InsufficientQuota" ali "Kvota presežena"</strong></summary>

```bash
# Poskusite z drugo regijo Azure
azd env set AZURE_LOCATION "westus2"
azd up

# Ali uporabite manjše SKU-je v razvoju
# Uredite infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>

<details>
<summary><strong>❌ "azd up" ne uspe na polovici poti</strong></summary>

```bash
# Možnost 1: Očisti in poskusi znova
azd down --force --purge
azd up

# Možnost 2: Popravi samo infrastrukturo
azd provision

# Možnost 3: Preveri podrobne dnevnike
azd show
azd logs
```
</details>

<details>
<summary><strong>❌ "Avtentikacija ni uspela" ali "Potekel žeton"</strong></summary>

```bash
# Ponovno se avtentificirajte
az logout
az login

azd auth logout
azd auth login

# Preverite avtentikacijo
az account show
```
</details>

<details>
<summary><strong>❌ "Vir že obstaja" ali konflikt imen</strong></summary>

```bash
# AZD generira edinstvena imena, vendar če pride do konflikta:
azd down --force --purge

# Nato poskusi znova z novim okoljem
azd env new dev-v2
azd up
```
</details>

<details>
<summary><strong>❌ Razmestitev predloge traja predolgo</strong></summary>

**Normalni časi čakanja:**
- Preprosta spletna aplikacija: 5-10 minut
- Aplikacija z bazo podatkov: 10-15 minut
- AI aplikacije: 15-25 minut (OpenAI zagotavljanje je počasno)

```bash
# Preveri napredek
azd show

# Če si zataknjen več kot 30 minut, preveri Azure Portal:
azd monitor
# Poišči neuspešne namestitve
```
</details>

<details>
<summary><strong>❌ "Dostop zavrnjen" ali "Prepovedano"</strong></summary>

```bash
# Preverite svojo Azure vlogo
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Potrebujete vsaj vlogo "Contributor"
# Prosite svojega Azure skrbnika, da podeli:
# - Contributor (za vire)
# - Uporabniški skrbnik dostopa (za dodelitve vlog)
```
</details>

<details>
<summary><strong>❌ Ne najdem URL-ja razmestitve aplikacije</strong></summary>

```bash
# Prikaži vse končne točke storitev
azd show

# Ali odpri Azure Portal
azd monitor

# Preveri določeno storitev
azd env get-values
# Poišči spremenljivke *_URL
```
</details>

### 📚 Celotni viri za odpravljanje težav

- **Vodnik za pogoste težave:** [Podrobne rešitve](docs/troubleshooting/common-issues.md)
- **Težave specifične za AI:** [AI odpravljanje težav](docs/troubleshooting/ai-troubleshooting.md)
- **Vodnik za odpravljanje napak:** [Korak za korakom](docs/troubleshooting/debugging.md)
- **Pomoč:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🎓 Zaključek tečaja in potrdilo

### Spremljanje napredka
Spremljajte svoj napredek učenja skozi vsako poglavje:

- [ ] **Poglavje 1**: Osnove in hiter začetek ✅
- [ ] **Poglavje 2**: Razvoj AI na prvem mestu ✅  
- [ ] **Poglavje 3**: Konfiguracija in avtentikacija ✅
- [ ] **Poglavje 4**: Infrastruktura kot koda in razmestitev ✅
- [ ] **Poglavje 5**: Večagentne AI rešitve ✅
- [ ] **Poglavje 6**: Preverjanje in načrtovanje pred razmestitvijo ✅
- [ ] **Poglavje 7**: Odpravljanje težav in razhroščevanje ✅
- [ ] **Poglavje 8**: Vzpostavitev in vzorci za podjetja ✅

### Preverjanje znanja
Po zaključku vsakega poglavja preverite svoje znanje z:
1. **Praktična vaja**: Zaključite praktično razmestitev poglavja
2. **Preverjanje znanja**: Preglejte del s pogostimi vprašanji za svoje poglavje
3. **Skupnostna razprava**: Delite svoje izkušnje v Azure Discord
4. **Naslednje poglavje**: Nadaljujte na naslednjo stopnjo zahtevnosti

### Prednosti zaključka tečaja
Po zaključku vseh poglavij boste imeli:
- **Proizvodne izkušnje**: Razmestili ste resnične AI aplikacije v Azure
- **Poklicne veščine**: Sposobnosti razmestitve za podjetja  
- **Priznanje v skupnosti**: Aktivni član Azure razvijalske skupnosti
- **Napredovanje v karieri**: Zaželeno znanje za AZD in AI razmestitev

---

## 🤝 Skupnost in podpora

### Pomoč in podpora
- **Tehnične težave**: [Prijava napak in zahteve za funkcije](https://github.com/microsoft/azd-for-beginners/issues)
- **Vprašanja o učenju**: [Microsoft Azure Discord skupnost](https://discord.gg/microsoft-azure) in [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **Pomoč specifična za AI**: Pridružite se [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **Dokumentacija**: [Uradna dokumentacija Azure Developer CLI](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)

### Vpogledi skupnosti iz Microsoft Foundry Discord

**Nedavni rezultati ankete na kanalu #Azure:**
- **45 %** razvijalcev želi uporabljati AZD za AI naloge
- **Glavni izzivi**: Razmestitve več storitev, upravljanje poverilnic, pripravljenost za proizvodnjo  
- **Najbolj zahtevano**: Predloge specifične za AI, vodiči za odpravljanje težav, najboljše prakse

**Pridružite se naši skupnosti za:**
- Delitev vaših AZD + AI izkušenj in iskanje pomoči
- Dostop do zgodnjih predogledov novih AI predlog
- Prispevanje k najboljšim praksam za razmestitev AI
- Vplivanje na prihodnji razvoj AI + AZD funkcij

### Prispevek k tečaju
Prispevke so dobrodošle! Preberite naš [Vodnik za prispevke](CONTRIBUTING.md) za podrobnosti o:
- **Izboljšavah vsebine**: Izboljšajte obstoječa poglavja in primere
- **Novi primeri**: Dodajte scenarije iz resničnega sveta in predloge  
- **Prevajanju**: Pomagajte vzdrževati večjezično podporo
- **Poročilih o napakah**: Izboljšajte natančnost in jasnost
- **Standardih skupnosti**: Upoštevajte vključujoča pravila skupnosti

---

## 📄 Informacije o tečaju

### Licenca
Ta projekt je licenciran pod licenco MIT - za podrobnosti glejte datoteko [LICENSE](../../LICENSE).

### Sorodni učni viri Microsoft Learn

Naša ekipa pripravlja tudi druge obsežne učne tečaje:

<!-- CO-OP TRANSLATOR OTHER COURSES START -->
### LangChain
[![LangChain4j za začetnike](https://img.shields.io/badge/LangChain4j%20for%20Beginners-22C55E?style=for-the-badge&&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchain4j-for-beginners)
[![LangChain.js za začetnike](https://img.shields.io/badge/LangChain.js%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchainjs-for-beginners?WT.mc_id=m365-94501-dwahlin)

---

### Azure / Edge / MCP / Agentje
[![AZD za začetnike](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Edge AI za začetnike](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![MCP za začetnike](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)
[![AI agentje za začetnike](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Serija Generativne AI
[![Generativna AI za začetnike](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Generativna AI (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
[![Generativna AI (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)
[![Generativna AI (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---
 
### Osnovno učenje
[![Strojno učenje za začetnike](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![Podatkovna znanost za začetnike](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![AI za začetnike](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Kibernetska varnost za začetnike](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Spletni razvoj za začetnike](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![IoT za začetnike](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![XR razvoj za začetnike](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Serija Copilot
[![Copilot za AI partnersko programiranje](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![Copilot za C#/.NET](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Copilot Avantura](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ Navigacija po tečaju

**🚀 Pripravljeni na začetek učenja?**

**Začetniki**: Začnite s [Poglavje 1: Osnove in hiter začetek](../..)  
**AI razvijalci**: Preskočite na [Poglavje 2: AI-prvi razvoj](../..)  
**Izkušeni razvijalci**: Začnite s [Poglavje 3: Konfiguracija in avtentikacija](../..)

**Naslednji koraki**: [Začni poglavje 1 - Osnove AZD](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Izjava o omejitvi odgovornosti**:
Ta dokument je bil preveden z uporabo storitve za avtomatski prevod AI [Co-op Translator](https://github.com/Azure/co-op-translator). Čeprav si prizadevamo za natančnost, upoštevajte, da lahko avtomatizirani prevodi vsebujejo napake ali netočnosti. Izvirni dokument v njegovem maternem jeziku velja za avtoritativni vir. Za ključne informacije priporočamo strokovni prevod, opravljen s strani usposobljenega prevajalca. Ne odgovarjamo za kakršne koli nesporazume ali napačne interpretacije, ki izhajajo iz uporabe tega prevoda.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->