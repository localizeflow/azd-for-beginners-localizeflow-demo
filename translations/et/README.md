<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T15:07:36+00:00",
  "source_file": "README.md",
  "language_code": "et"
}
-->
> Märkus: See dokumentatsioon uuendatakse pidevalt, et kajastada viimaseid muudatusi.

> ⚠️ See hoidla on demo, mis on loodud Localizeflow abil automatiseeritud dokumentatsiooni lokaliseerimise tutvustamiseks.
>
> Originaalsisu põhineb Microsofti projektidel „AZD algajatele“.


# AZD algajatele: Struktureeritud õpiteekond

![AZD-for-beginners](../../translated_images/azdbeginners.5527441dd9f74068.et.png) 

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## Selle kursuse alustamine

Järgige järgmisi samme, et alustada oma AZD õpiteekonda:

1. **Haru hoidla**: Klõpsake [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)
2. **Kloonige hoidla**: `git clone https://github.com/microsoft/azd-for-beginners.git`
3. **Liituge kogukonnaga**: [Azure Discord kogukonnad](https://discord.com/invite/ByRwuEEgH4) eksperttoega
4. **Valige oma õpiteekond**: Valige allpool peatükk, mis vastab teie kogemustasemele

### Mitmekeelne tugi

#### Automatiseeritud tõlked (Alati ajakohased)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](./README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Eelistate kohalikku kloonimist?**

> See hoidla sisaldab 50+ keele tõlget, mis suurendab oluliselt allalaadimise mahtu. Kui soovite kloonida ilma tõlgeteta, kasutage harva kloonimist (sparse checkout):
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> See annab teile kõik vajaliku kursuse läbimiseks palju kiiremalt.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## Kursuse ülevaade

Meisterdage Azure Developer CLI (azd) struktureeritud peatükkide kaudu, mis on mõeldud järkjärguliseks õppimiseks. **Eriline rõhk AI rakenduste juurutamisel Microsoft Foundry integreerimisega.**

### Miks see kursus on tänapäeva arendajatele oluline

Põhinedes Microsoft Foundry Discord kogukonna teadmistele, soovib **45% arendajatest kasutada AZD-d AI töökoormuste jaoks**, kuid nad kogevad raskusi:
- Komplekssed mitme teenuse AI arhitektuurid
- Tootmises AI juurutamise parimad tavad  
- Azure AI teenuste integratsioon ja seadistamine
- AI töökoormuste kulude optimeerimine
- AI spetsiifiliste juurutusprobleemide tõrkeotsing

### Õpieesmärgid

Selle struktureeritud kursuse läbimisel:
- **Siirdute AZD põhiteadmised**: põhikontseptsioonid, paigaldus ja seadistus
- **Juurutate AI rakendusi**: kasutades AZD-d Microsoft Foundry teenustega
- **Rakendate infrastruktuuri koodina**: haldate Azure ressursse Bicep mallidega
- **Lahendate juurutusprobleeme**: lahendate tavalisi probleeme ja silute tõrkeid
- **Optimeerite tootmiseks**: turvalisus, skaleerimine, jälgimine ja kulude juhtimine
- **Ehitate mitme agendi lahendusi**: juurutate keerukaid AI arhitektuure

## 📚 Õppepeatükid

*Valige oma õpitee vastavalt kogemustasemele ja eesmärkidele*

### 🚀 1. peatükk: Alus ja kiire algus
**Eeltingimused**: Azure tellimus, põhilised käsurea teadmised  
**Kestus**: 30–45 minutit  
**Tasemekomplekssus**: ⭐

#### Mida õpite
- Azure Developer CLI põhialused
- AZD paigaldamine teie platvormile
- Teie esimene õnnestunud juurutus

#### Õppematerjalid
- **🎯 Alustage siit**: [Mis on Azure Developer CLI?](../..)
- **📖 Teooria**: [AZD põhialused](docs/getting-started/azd-basics.md) - põhimõisted ja terminoloogia
- **⚙️ Paigaldus**: [Paigaldus ja seadistamine](docs/getting-started/installation.md) - platvormispetsiifilised juhised
- **🛠️ Praktika**: [Teie esimene projekt](docs/getting-started/first-project.md) - samm-sammult juhend
- **📋 Kiire viide**: [Käsukäivitustabel](resources/cheat-sheet.md)

#### Praktilised harjutused
```bash
# Kiire paigalduskontroll
azd version

# Paigalda oma esimene rakendus
azd init --template todo-nodejs-mongo
azd up
```

**💡 Peatüki tulemus**: Edukas lihtsa veebirakenduse juurutamine Azure’i kasutades AZD-d

**✅ Edu kinnitamine:**
```bash
# Pärast 1. peatüki lõpetamist peaksid sa oskama:
azd version              # Kuvab paigaldatud versiooni
azd init --template todo-nodejs-mongo  # Algatab projekti
azd up                  # Paigaldab Azure'i
azd show                # Kuvab töötava rakenduse URL-i
# Rakendus avaneb brauseris ja töötab
azd down --force --purge  # Koristab ressursid
```

**📊 Ajakulu:** 30–45 minutit  
**📈 Oskustase pärast lõpetamist:** Suudab iseseisvalt lihtsaid rakendusi juurutada

**✅ Edu kinnitamine:**
```bash
# Pärast esimest peatükki peaksite olema suuteline:
azd version              # Kuvab paigaldatud versiooni
azd init --template todo-nodejs-mongo  # Projekti initsialiseerib
azd up                  # Rakendab Azure'i
azd show                # Kuvab töötava rakenduse URL-i
# Rakendus avaneb brauseris ja töötab
azd down --force --purge  # Resursid puhastatakse üles
```

**📊 Ajakulu:** 30–45 minutit  
**📈 Oskustase pärast lõpetamist:** Suudab iseseisvalt lihtsaid rakendusi juurutada

---

### 🤖 2. peatükk: AI-esimene arendus (Soovitatav AI arendajatele)
**Eeltingimused**: 1. peatükk lõpetatud  
**Kestus**: 1–2 tundi  
**Tasemekomplekssus**: ⭐⭐

#### Mida õpite
- Microsoft Foundry integreerimine AZD-ga
- AI-põhiste rakenduste juurutamine
- AI teenuste seadistuste mõistmine

#### Õppematerjalid
- **🎯 Alustage siit**: [Microsoft Foundry integratsioon](docs/microsoft-foundry/microsoft-foundry-integration.md)
- **📖 Mustrid**: [AI mudelite juurutus](docs/microsoft-foundry/ai-model-deployment.md) - AI mudelite juurutamine ja haldamine
- **🛠️ Töökoht**: [AI töötoa labor](docs/microsoft-foundry/ai-workshop-lab.md) - Tehke oma AI lahendused AZD-valmis
- **🎥 Interaktiivne juhend**: [Töötoa materjalid](workshop/README.md) - Brauseripõhine õppimine MkDocsi ja DevContainer keskkonnaga
- **📋 Mallid**: [Microsoft Foundry mallid](../..)
- **📝 Näited**: [AZD juurutuse näited](examples/README.md)

#### Praktilised harjutused
```bash
# Käivitage oma esimene tehisintellekti rakendus
azd init --template azure-search-openai-demo
azd up

# Proovige täiendavaid tehisintellekti malle
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```

**💡 Peatüki tulemus**: AI-põhise vestlusrakenduse juurutamine ja seadistamine RAG võimekusega

**✅ Edu kinnitamine:**
```bash
# Pärast peatükki 2 peaksite olema võimeline:
azd init --template azure-search-openai-demo
azd up
# Testima tehisintellekti vestlusliidest
# Esitama küsimusi ja saama tehisintellekti jõul põhinevaid vastuseid koos allikatega
# Kontrollima, et otsingute integreerimine töötab
azd monitor  # Kontrollima, kas Application Insights kuvab telemeetriat
azd down --force --purge
```

**📊 Ajakulu:** 1–2 tundi  
**📈 Oskustase pärast lõpetamist:** Suudab juurutada ja seadistada tootmisvalmis AI rakendusi  
**💰 Kulu teadlikkus:** Mõistab $80–150/kuu arenduskulusid, $300–3500/kuu tootmiskulusid

#### 💰 Kulude kaalutlused AI juurutusteks

**Arenduskeskkond (Hinnanguliselt $80–150/kuu):**
- Azure OpenAI (tasu vastavalt kasutusele): $0–50/kuu (sõltuvalt tokenite kasutusest)
- AI otsing (Põhitase): $75/kuu
- Container Apps (Tarbitav): $0–20/kuu
- Salvestus (Standard): $1–5/kuu

**Tootmiskeskkond (Hinnanguliselt $300–3500+/kuu):**
- Azure OpenAI (PTU ühtlaseks jõudluseks): $3000+/kuu VÕI tasu vastavalt kasutusele, kuid suures mahus
- AI otsing (Standardtase): $250/kuu
- Container Apps (Pühendatud): $50–100/kuu
- Application Insights: $5–50/kuu
- Salvestus (Premium): $10–50/kuu

**💡 Kuluoptimeerimise nõuanded:**
- Kasutage õppimiseks **Tasuta taset** Azure OpenAI jaoks (kaasas 50 000 tokenit kuus)
- Käivitage `azd down`, et deaktiveerida ressursid, kui mitte aktiivselt arendamas
- Alustage tarbimispõhisest arveldusest, PTU suurendage ainult tootmiseks
- Kasutage `azd provision --preview` kulude hindamiseks enne juurutamist
- Lubage automaatskaalumine: maksate ainult tegeliku kasutuse eest

**Kulu jälgimine:**
```bash
# Kontrolli hinnangulisi igakuiseid kulusid
azd provision --preview

# Jälgi tegelikke kulusid Azurei portaalis
az consumption budget list --resource-group <your-rg>
```

---

### ⚙️ 3. peatükk: Seadistamine ja autentimine
**Eeltingimused**: 1. peatükk lõpetatud  
**Kestus**: 45–60 minutit  
**Tasemekomplekssus**: ⭐⭐

#### Mida õpite
- Keskkonna seadistus ja haldamine
- Autentimise ja turvalisuse parimad tavad
- Ressursside nimetamine ja organiseerimine

#### Õppematerjalid
- **📖 Seadistamine**: [Seadistamise juhend](docs/getting-started/configuration.md) - Keskkonna seadistamine
- **🔐 Turvalisus**: [Autentimis- ja haldusidentiteedi mustrid](docs/getting-started/authsecurity.md) - Autentimismustrid
- **📝 Näited**: [Andmebaasi rakenduse näide](examples/database-app/README.md) - AZD andmebaasi näited

#### Praktilised harjutused
- Mitme keskkonna seadistamine (arendus, testimine, tootmine)
- Halduse identiteedi autentimise seadistamine
- Keskkonnapõhiste seadistuste rakendamine

**💡 Peatüki tulemus**: Halda mitut keskkonda asjakohase autentimise ja turvalisusega

---

### 🏗️ 4. peatükk: Infrastruktuur koodina ja juurutus
**Eeltingimused**: Peatükid 1–3 lõpetatud  
**Kestus**: 1–1,5 tundi  
**Tasemekomplekssus**: ⭐⭐⭐

#### Mida õpite
- Täiustatud juurutusmustrid
- Infrastruktuur kui kood Bicepiga
- Ressursside provisjonimise strateegiad

#### Õppematerjalid
- **📖 Juurutus**: [Juurutuse juhend](docs/deployment/deployment-guide.md) - Täielikud töövood
- **🏗️ Provisjonimine**: [Ressursside provisjonimine](docs/deployment/provisioning.md) - Azure ressursihaldus
- **📝 Näited**: [Container App näide](../../examples/container-app) - Konteineripõhised juurutused

#### Praktilised harjutused
- Kohandatud Bicep mallide loomine
- Mitme teenuse rakenduste juurutamine
- Sinine-roheline juurutusstrateegiate rakendamine

**💡 Peatüki tulemus**: Juurutage keerukaid mitmete teenustega rakendusi kohandatud infrastruktuurimallidega

---
### 🎯 5. peatükk: Mitme agendi tehisintellekti lahendused (edasijõudnutele)  
**Eeldused**: Peatükid 1-2 lõppenud  
**Kestus**: 2-3 tundi  
**Kompleksus**: ⭐⭐⭐⭐

#### Mida sa õpid  
- Mitme agendi arhitektuuri mustrid  
- Agendi orkestreerimine ja koordineerimine  
- Tootmiskõlblikud tehisintellekti lahendused

#### Õppematerjalid  
- **🤖 Esiletõstetud projekt**: [Jaekaubanduse mitme agendi lahendus](examples/retail-scenario.md) – Täielik rakendus  
- **🛠️ ARM mallid**: [ARM malli pakk](../../examples/retail-multiagent-arm-template) – Ühe klõpsuga juurutus  
- **📖 Arhitektuur**: [Mitme agendi koordineerimise mustrid](/docs/pre-deployment/coordination-patterns.md) – Mustrid

#### Praktilised harjutused  
```bash
# Paigalda täielik jaekaubanduse mitme agendi lahendus
cd examples/retail-multiagent-arm-template
./deploy.sh

# Uuri agendi konfiguratsioone
az deployment group show --resource-group <rg-name> --name <deployment-name>
```
  
**💡 Peatüki tulemus**: Juurutada ja hallata tootmiskõlblikku mitme agendi AI lahendust koos kliendi ja laovarude agentidega

---

### 🔍 6. peatükk: Eeljuurutuse valideerimine ja planeerimine  
**Eeldused**: 4. peatükk lõpetatud  
**Kestus**: 1 tund  
**Kompleksus**: ⭐⭐

#### Mida sa õpid  
- Võimsuse planeerimine ja ressursside valideerimine  
- SKU valimise strateegiad  
- Kontrollid enne käivitust ja automatiseerimine

#### Õppematerjalid  
- **📊 Planeerimine**: [Võimsuse planeerimine](docs/pre-deployment/capacity-planning.md) – Ressursside valideerimine  
- **💰 Valik**: [SKU valimine](docs/pre-deployment/sku-selection.md) – Kulutõhusad valikud  
- **✅ Valideerimine**: [Pre-flight kontrollid](docs/pre-deployment/preflight-checks.md) – Automatiseeritud skriptid

#### Praktilised harjutused  
- Käivita võimsuse valideerimise skripte  
- Optimeeri SKU valikud kulude tarbeks  
- Rakenda automatiseeritud eeljuurutuse kontrollid

**💡 Peatüki tulemus**: Valideerida ja optimeerida juurutusi enne nende tegemist

---

### 🚨 7. peatükk: Tõrkeotsing ja silumine  
**Eeldused**: Suvaline juurutamise peatükk lõpetatud  
**Kestus**: 1-1,5 tundi  
**Kompleksus**: ⭐⭐

#### Mida sa õpid  
- Süstemaatilised silumise lähenemised  
- Levinumad probleemid ja lahendused  
- Tehisintellektile spetsiifiline tõrkeotsing

#### Õppematerjalid  
- **🔧 Levinumad probleemid**: [Levinud probleemid](docs/troubleshooting/common-issues.md) – KKK ja lahendused  
- **🕵️ Silumine**: [Silumise juhend](docs/troubleshooting/debugging.md) – Samm-sammult strateegiad  
- **🤖 AI probleemid**: [Tehisintellekti tõrkeotsing](docs/troubleshooting/ai-troubleshooting.md) – AI teenuste probleemid

#### Praktilised harjutused  
- Diagnostika juurutamise ebaõnnestumiste puhul  
- Autentimisküsimuste lahendamine  
- AI teenuse ühenduvuse silumine

**💡 Peatüki tulemus**: Ise sõltumatult diagnoosida ja lahendada levinud juurutamise probleeme

---

### 🏢 8. peatükk: Tootmise ja ettevõtte mustrid  
**Eeldused**: Peatükid 1-4 lõpetatud  
**Kestus**: 2-3 tundi  
**Kompleksus**: ⭐⭐⭐⭐

#### Mida sa õpid  
- Tootmiskeskkonna juurutusstrateegiad  
- Ettevõtte turvalisuse mustrid  
- Jälgimine ja kulude optimeerimine

#### Õppematerjalid  
- **🏭 Tootmine**: [Tootmise AI parimad praktikad](docs/microsoft-foundry/production-ai-practices.md) – Ettevõtte mustrid  
- **📝 Näited**: [Mikroteenuste näide](../../examples/microservices) – Komplekssed arhitektuurid  
- **📊 Jälgimine**: [Application Insights integreerimine](docs/pre-deployment/application-insights.md) – Jälgimine

#### Praktilised harjutused  
- Rakenda ettevõtte turvalisuse mustrid  
- Loo põhjalik jälgimine  
- Juuruta tootmises koos sobiva valitsemisega

**💡 Peatüki tulemus**: Juuruta tootmisele valmis ettevõtte rakendusi täisvõimalustega

---

## 🎓 Töötuba ülevaade: Käed-külge õpikogemus

> **⚠️ TÖÖTOA STAATUS: Arendamisel**  
> Töötuba materjalid on hetkel arendamisel ja täiendamisel. Põhimoodulid töötavad, kuid mõned edasijõudnud jaotised on veel puudulikud. Töötame aktiivselt kogu sisu valmimiseks. [Jälgi edenemist →](workshop/README.md)

### Interaktiivsed töötuba materjalid  
**Kattuv ja praktiline õpe brauseripõhiste tööriistade ja juhendatud harjutustega**

Meie töötuba materjalid pakuvad struktureeritud, interaktiivset õppimiskogemust, mis täiendavad ülaltoodud peatükkidel põhinevat õppekava. Töötuba on loodud nii iseseisvaks õppimiseks kui ka juhendajaga sessioonideks.

#### 🛠️ Töötuba funktsioonid  
- **Brauseripõhine kasutajaliides**: Täielik MkDocs’i toetusega töötuba koos otsingu, kopeerimise ja teemade valikutega  
- **GitHub Codespaces integratsioon**: Arenduskeskkonna ühe klõpsuga seadistus  
- **Struktureeritud õpiteekond**: 7 sammu juhendatud harjutust (kokku 3,5 tundi)  
- **Avastus → Juurutus → Kohandamine**: Astmeline metoodika  
- **Interaktiivne DevContainer keskkond**: Eelseadistatud tööriistad ja sõltuvused

#### 📚 Töötuba struktuur  
Töötuba järgib **avastamise → juurutamise → kohandamise** metoodikat:

1. **Avastusfaas** (45 minutit)  
   - Tutvu Microsoft Foundry mallide ja teenustega  
   - Mõista mitme agendi arhitektuuri mustreid  
   - Vaata juurutamise nõudeid ja eeldusi

2. **Juurutusfaas** (2 tundi)  
   - Praktiline AI rakenduste juurutamine AZD-ga  
   - Azure AI teenuste ja lõpupunktide konfigureerimine  
   - Turvalisuse ja autentimise mustrite implementeerimine

3. **Kohandamisfaas** (45 minutit)  
   - Rakenduste muutmine spetsiifilisteks juhtumiteks  
   - Optimeerimine tootmiskeskkonna juurutuseks  
   - Jälgimise ja kuluhalduse rakendamine

#### 🚀 Töötuba alustamine  
```bash
# Valik 1: GitHub Codespaces (Soovitatav)
# Klõpsake "Code" → "Create codespace on main" hoidlas

# Valik 2: Kohalik arendus
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# Järgige seadistamisjuhiseid workshop/README.md failis
```
  
#### 🎯 Töötuba õpitulemused  
Töötuba lõpetades osalejad:  
- **Juurutavad tootmise AI rakendusi**: Kasutades AZD-d Microsoft Foundry teenustega  
- **Valdavad mitme agendi arhitektuurid**: Rakendavad koordineeritud AI agendi lahendusi  
- **Rakendavad turvalisuse parimaid praktikaid**: Konfigureerivad autentimist ja juurdepääsukontrolli  
- **Optimeerivad skaleerumist**: Kujundavad kulutõhusaid ja jõudlusrikkaid juurutusi  
- **Tõrkeotsing juurutamisel**: Lahendavad levinud probleeme iseseisvalt

#### 📖 Töötuba ressursid  
- **🎥 Interaktiivne juhend**: [Töötuba materjalid](workshop/README.md) – Brauseripõhine õppimiskeskkond  
- **📋 Samm-sammuline juhis**: [Juhendatud harjutused](../../workshop/docs/instructions) – Detailne õpetus  
- **🛠️ AI töötuba labor**: [AI töötuba labor](docs/microsoft-foundry/ai-workshop-lab.md) – AI-spetsiifilised harjutused  
- **💡 Kiirstart**: [Töötuba seadistusjuhend](workshop/README.md#quick-start) – Keskkonna seadistamine

**Sobib ideaalselt**: Ettevõttekoolituseks, ülikoolikursusteks, iseseisvaks õppimiseks ja arendajate bootcamp’ideks.

---

## 📖 Mis on Azure Developer CLI?

Azure Developer CLI (azd) on arendajale suunatud käsurealiides, mis kiirendab rakenduste loomist ja juurutamist Azure’i platvormile. Pakub:

- **Malli-põhised juurutused** – Kasuta eelvalmiskandjad enamlevinud rakendusmustrite jaoks  
- **Infrastruktuur kui kood** – Halda Azure ressursse Bicep või Terraform abil  
- **Integreeritud töövood** – Provisioneerimine, juurutamine ja jälgimine ühe sujuva protsessina  
- **Arendajasõbralik** – Optimeeritud arendaja tootlikkuse ja kogemuse parandamiseks

### **AZD + Microsoft Foundry: Perfektne AI lahenduste jaoks**

**Miks valida AZD AI lahenduste jaoks?** AZD lahendab AI arendajate suurimad väljakutsed:

- **AI-valmis mallid** – Eelseadistatud mallid Azure OpenAI, Cognitive Services’i ja ML töökoormuste jaoks  
- **Turvalised AI juurutused** – Sisseehitatud turvamustrid AI teenustele, API võtmetele ja mudelilõpp-punktidele  
- **Tootmise AI mustrid** – Parimad praktikad skaleeritavate, kuluefektiivsete AI rakenduste jaoks  
- **Lõplik AI töövoog** – Mudeliarendusest kuni tootmise juurutuseni koos nõuetekohase jälgimisega  
- **Kuluoptimeerimine** – Tark ressursside jaotus ning skaleerimisstrateegiad AI töökoormuste jaoks  
- **Microsoft Foundry integratsioon** – Sujuv ühendus Microsoft Foundry mudelikataloogi ja lõpp-punktidega

---

## 🎯 Mallide ja näidiste kogu

### Esiletõstetud: Microsoft Foundry mallid  
**Alusta siit, kui juurutad AI rakendusi!**

> **Märkus:** Need mallid demonstreerivad erinevaid AI mustreid. Mõned on Azure näited, teised lokaalsed rakendused.

| Mall | Peatükk | Kompleksus | Teenused | Tüüp |
|------|---------|------------|----------|------|
| [**Alusta AI vestlusega**](https://github.com/Azure-Samples/get-started-with-ai-chat) | Peatükk 2 | ⭐⭐ | AzureOpenAI + Azure AI mudeli järeldus API + Azure AI otsing + Azure konteiner-rakendused + Application Insights | Väline |
| [**Alusta AI agentidega**](https://github.com/Azure-Samples/get-started-with-ai-agents) | Peatükk 2 | ⭐⭐ | Azure AI agendi teenus + AzureOpenAI + Azure AI otsing + Azure konteiner-rakendused + Application Insights | Väline |
| [**Azure Search + OpenAI demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Peatükk 2 | ⭐⭐ | AzureOpenAI + Azure AI otsing + App Service + Storage | Väline |
| [**OpenAI Chat App Quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Peatükk 2 | ⭐ | AzureOpenAI + konteiner-rakendused + Application Insights | Väline |
| [**Agent OpenAI Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Peatükk 5 | ⭐⭐⭐ | AzureOpenAI + Azure funktsioonid + Prompty | Väline |
| [**Contoso Chat RAG**](https://github.com/Azure-Samples/contoso-chat) | Peatükk 8 | ⭐⭐⭐⭐ | AzureOpenAI + AI otsing + Cosmos DB + konteiner-rakendused | Väline |
| [**Jaemüügi mitme agendi lahendus**](examples/retail-scenario.md) | Peatükk 5 | ⭐⭐⭐⭐ | AzureOpenAI + AI otsing + Storage + konteiner-rakendused + Cosmos DB | **Lokaalne** |

### Esiletõstetud: Täielikud õpistsenaariumid  
**Tootmiskõlblikud rakenduse mallid, mis vastavad õppepeatükkidele**

| Mall | Õppepeatükk | Kompleksus | Peamine õpe |
|------|-------------|------------|-------------|
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Peatükk 2 | ⭐ | Põhilised AI juurutusmustrid |
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Peatükk 2 | ⭐⭐ | RAG rakendus Azure AI otsinguga |
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | Peatükk 4 | ⭐⭐ | Dokumendi intelligentsuse integreerimine |
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Peatükk 5 | ⭐⭐⭐ | Agendiraamistiku ja funktsioonide kutsumine |
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | Peatükk 8 | ⭐⭐⭐ | Ettevõtte AI orkestreerimine |
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | Peatükk 5 | ⭐⭐⭐⭐ | Mitme agendi arhitektuur koos kliendi ja laovarude agentidega |

### Õppimine näidiste kaudu

> **📌 Kohalikud vs. välimised näited:**  
> **Kohalikud näited** (selles repos) = Koheselt kasutusvalmis  
> **Väline näited** (Azure näited) = Kloneeri seotud repodest

#### Kohalikud näited (kasutamiseks valmis)  
- [**Jaemüügi mitme agendi lahendus**](examples/retail-scenario.md) – Täielik tootmiskõlblik rakendus ARM mallidega  
  - Mitme agendi arhitektuur (klient + laovarud)  
  - Ulatuslik jälgimine ja hindamine  
  - Ühe klõpsuga juurutamine ARM malli kaudu

#### Kohalikud näited – konteinerirakendused (peatükid 2-5)  
**Konteineripõhised juurutusnäited selles repositooriumis:**  
- [**Konteinerirakenduste näited**](examples/container-app/README.md) – Täielik juhend konteinerjuurutustele  
  - [Lihtne Flask API](../../examples/container-app/simple-flask-api) – Põhiline REST API koos scale-to-zero funktsiooniga  
  - [Mikroteenuste arhitektuur](../../examples/container-app/microservices) – Tootmiskõlblik mitme-teenuse juurutus  
  - Kiirstart, tootmine ja edasijõudnud juurutusmustrid  
  - Jälgimine, turvalisus ja kulude optimeerimise juhised  

#### Välimised näited – lihtsad rakendused (peatükid 1-2)  
**Kloneeri Azure näidiste repositooriumid alustamiseks:**  
- [Lihtne veebirakendus - Node.js + MongoDB](https://github.com/Azure-Samples/todo-nodejs-mongo) – Põhilised juurutusmustrid  
- [Staatiline veebisait - React SPA](https://github.com/Azure-Samples/todo-csharp-sql-swa-func) – Staatiline sisujurutus  
- [Konteinerirakendus - Python Flask](https://github.com/Azure-Samples/container-apps-store-api-microservice) – REST API juurutamine

#### Välimised näited – andmebaasi integratsioon (peatükid 3-4)  
- [Andmebaasirakendus - C# + SQL](https://github.com/Azure-Samples/todo-csharp-sql) – Andmebaasi ühendumise mustrid  
- [Funktsioonid + Cosmos DB](https://github.com/Azure-Samples/todo-python-mongo-swa-func) – Serverivaba andmevoog

#### Välimised näited – edasijõudnud mustrid (peatükid 4-8)  
- [Java mikroteenused](https://github.com/Azure-Samples/java-microservices-aca-lab) – Mitme teenuse arhitektuur  
- [Konteiner-rakenduste taustatööd](https://github.com/Azure-Samples/container-apps-jobs) – Taustaprotsessid  
- [Ettevõtte ML torujuhe](https://github.com/Azure-Samples/mlops-v2) – Tootmiskõlblikud ML mustrid

### Välimised mallide kogu  

- [**Ametlik AZD malligalerii**](https://azure.github.io/awesome-azd/) - kureeritud ametlike ja kogukonna mallide kogu
- [**Azure arendaja CLI mallid**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - Microsoft Learn mallide dokumentatsioon
- [**Näidiste kataloog**](examples/README.md) - kohalikud õppenäited koos üksikasjalike selgitustega

---

## 📚 Õppevahendid ja viited

### Kiirviited
- [**Käskude petutahvel**](resources/cheat-sheet.md) - Olulised azd käsud peatükkide kaupa korraldatud
- [**Glosaar**](resources/glossary.md) - Azure’i ja azd terminoloogia
- [**KKK**](resources/faq.md) - Üldised küsimused õppepeatükkide kaupa korraldatud
- [**Õppejuhend**](resources/study-guide.md) - Kattuvad praktikaülesanded

### Praktilised töötoad
- [**Tehisintellekti töötoa labor**](docs/microsoft-foundry/ai-workshop-lab.md) - Tee oma tehisintellekti lahendused AZD-le juurutatavateks (2–3 tundi)
- [**Interaktiivne töötoa juhend**](workshop/README.md) - Veebipõhine töötuba MkDocsi ja DevContainer keskkonnaga
- [**Struktureeritud õppeteekond**](../../workshop/docs/instructions) - 7-sammulised juhendatud harjutused (Avastamine → Juurutamine → Kohandamine)
- [**AZD algajatele töötuba**](workshop/README.md) - Täielik praktiline töötoa materjal GitHub Codespaces integratsiooniga

### Välised õppeallikad
- [Azure arendaja CLI dokumentatsioon](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)
- [Azure arhitektuuri keskus](https://learn.microsoft.com/en-us/azure/architecture/)
- [Azure hinnakalkulaator](https://azure.microsoft.com/pricing/calculator/)
- [Azure olekuportaal](https://status.azure.com/)

---

## 🔧 Kiire tõrkeotsingu juhend

**Algajate sagedasemad probleemid ja kohesed lahendused:**

### ❌ "azd: käsku ei leitud"

```bash
# Paigalda esmalt AZD
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Kontrolli paigaldust
azd version
```

### ❌ "Liitumist ei leitud" või "Liitumist ei ole seatud"

```bash
# Kuvada saadaolevad tellimused
az account list --output table

# Määra vaikimisi tellimus
az account set --subscription "<subscription-id-or-name>"

# Määra AZD keskkonnale
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Kinnita
az account show
```

### ❌ "InsufficientQuota" või "Kvoot ületatud"

```bash
# Proovi erinevat Azure'i regioonis
azd env set AZURE_LOCATION "westus2"
azd up

# Või kasuta arenduses väiksemaid SKU-sid
# Muuda infra/main.parameters.json faili:
{
  "sku": "B1"  // Instead of "P1V2"
}
```

### ❌ "azd up" ebaõnnestub poole peal

```bash
# Võimalus 1: Puhasta ja proovi uuesti
azd down --force --purge
azd up

# Võimalus 2: Paranda ainult infrastruktuur
azd provision

# Võimalus 3: Kontrolli üksikasjalikke logisid
azd show
azd logs
```

### ❌ "Autentimine ebaõnnestus" või "Token aegunud"

```bash
# Autentige uuesti
az logout
az login

azd auth logout
azd auth login

# Kontrollige autentimist
az account show
```

### ❌ "Resurss juba olemas" või nimeriigi konfliktid

```bash
# AZD genereerib unikaalseid nimesid, kuid kui tekib konflikt:
azd down --force --purge

# Siis proovi uuesti uue keskkonnaga
azd env new dev-v2
azd up
```

### ❌ Malli juurutamine võtab liiga kaua aega

**Tavalised ooteajad:**
- Lihtne veebirakendus: 5–10 minutit
- Rakendus andmebaasiga: 10–15 minutit
- Tehisintellekti rakendused: 15–25 minutit (OpenAI varustamine on aeglane)

```bash
# Kontrolli edenemist
azd show

# Kui kinni >30 minutit, kontrolli Azure portaalis:
azd monitor
# Otsi ebaõnnestunud juurutusi
```

### ❌ "Luba keelatud" või "Keelatud"

```bash
# Kontrolli oma Azure'i rolli
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Sul peab olema vähemalt "Contributor" roll
# Palu oma Azure'i administraatoril anda järgmised õigused:
# - Contributor (ressursside jaoks)
# - User Access Administrator (rolli määramiste jaoks)
```

### ❌ Juurutatud rakenduse URL-i ei leita

```bash
# Näita kõiki teenuse otspunktid
azd show

# Või avage Azure'i portaal
azd monitor

# Kontrolli kindlat teenust
azd env get-values
# Otsi *_URL muutujaid
```

### 📚 Täielikud tõrkeotsingu ressursid

- **Sagedaste probleemide juhend:** [Üksikasjalikud lahendused](docs/troubleshooting/common-issues.md)
- **Tehisintellektispetsiifilised probleemid:** [Tehisintellekti tõrkeotsing](docs/troubleshooting/ai-troubleshooting.md)
- **Silumine:** [Järkjärguline silumine](docs/troubleshooting/debugging.md)
- **Abi saamine:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🔧 Kiire tõrkeotsingu juhend

**Algajate sagedasemad probleemid ja kohesed lahendused:**

<details>
<summary><strong>❌ "azd: käsku ei leitud"</strong></summary>

```bash
# Installige esmalt AZD
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Kontrolli paigaldust
azd version
```
</details>

<details>
<summary><strong>❌ "Liitumist ei leitud" või "Liitumist ei ole seatud"</strong></summary>

```bash
# Loetle saadaolevad tellimused
az account list --output table

# Määra vaikimisi tellimus
az account set --subscription "<subscription-id-or-name>"

# Sea AZD keskkonnaks
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Kontrolli
az account show
```
</details>

<details>
<summary><strong>❌ "InsufficientQuota" või "Kvoot ületatud"</strong></summary>

```bash
# Proovi erinevat Azure'i regioon
azd env set AZURE_LOCATION "westus2"
azd up

# Või kasuta arenduses väiksemaid SKU-sid
# Muuda infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>

<details>
<summary><strong>❌ "azd up" ebaõnnestub poole peal</strong></summary>

```bash
# Valik 1: Puhasta ja proovi uuesti
azd down --force --purge
azd up

# Valik 2: Paranda lihtsalt infrastruktuur
azd provision

# Valik 3: Kontrolli üksikasjalikke logisid
azd show
azd logs
```
</details>

<details>
<summary><strong>❌ "Autentimine ebaõnnestus" või "Token aegunud"</strong></summary>

```bash
# Autendi uuesti
az logout
az login

azd auth logout
azd auth login

# Kontrolli autentimist
az account show
```
</details>

<details>
<summary><strong>❌ "Resurss juba olemas" või nimeriigi konfliktid</strong></summary>

```bash
# AZD genereerib unikaalseid nimesid, kuid kui tekib konflikt:
azd down --force --purge

# Siis proovige uuesti puhta keskkonnaga
azd env new dev-v2
azd up
```
</details>

<details>
<summary><strong>❌ Malli juurutamine võtab liiga kaua aega</strong></summary>

**Tavalised ooteajad:**
- Lihtne veebirakendus: 5–10 minutit
- Rakendus andmebaasiga: 10–15 minutit
- Tehisintellekti rakendused: 15–25 minutit (OpenAI varustamine on aeglane)

```bash
# Kontrolli edenemist
azd show

# Kui kinni >30 minutit, kontrolli Azure portaalis:
azd monitor
# Otsi ebaõnnestunud juurutusi
```
</details>

<details>
<summary><strong>❌ "Luba keelatud" või "Keelatud"</strong></summary>

```bash
# Kontrolli oma Azure rolli
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Sul peab olema vähemalt "Panustaja" roll
# Palu oma Azure administraatoril anda:
# - Panustaja (ressursside jaoks)
# - Kasutaja juurdepääsu administraator (rolli määrangute jaoks)
```
</details>

<details>
<summary><strong>❌ Juurutatud rakenduse URL-i ei leita</strong></summary>

```bash
# Näita kõiki teenuse lõpp-punkte
azd show

# Või ava Azure'i portaal
azd monitor

# Kontrolli konkreetset teenust
azd env get-values
# Otsi *_URL muutujad
```
</details>

### 📚 Täielikud tõrkeotsingu ressursid

- **Sagedaste probleemide juhend:** [Üksikasjalikud lahendused](docs/troubleshooting/common-issues.md)
- **Tehisintellektispetsiifilised probleemid:** [Tehisintellekti tõrkeotsing](docs/troubleshooting/ai-troubleshooting.md)
- **Silumine:** [Järkjärguline silumine](docs/troubleshooting/debugging.md)
- **Abi saamine:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🎓 Kursuse lõpetamine ja sertifitseerimine

### Edusammude jälgimine
Jälgi oma õppe edenemist iga peatüki kaupa:

- [ ] **1. peatükk**: Põhitõed ja kiire algus ✅
- [ ] **2. peatükk**: Tehisintellekt esimesena ✅  
- [ ] **3. peatükk**: Konfiguratsioon ja autentimine ✅
- [ ] **4. peatükk**: Infrastruktuur koodina ja juurutamine ✅
- [ ] **5. peatükk**: Mitmeagendilised tehisintellekti lahendused ✅
- [ ] **6. peatükk**: Eeljuurutamise valideerimine ja planeerimine ✅
- [ ] **7. peatükk**: Tõrkeotsing ja silumine ✅
- [ ] **8. peatükk**: Tootmine ja ettevõtte mustrid ✅

### Õppimise kontroll
Pärast iga peatüki lõpetamist kontrolli oma teadmisi:
1. **Praktiline ülesanne**: Täida peatüki praktiline juurutamine
2. **Teadmiste kontroll**: Vaata oma peatüki KKK osakond läbi
3. **Kogukonna arutelu**: Jaga oma kogemust Azure Discordis
4. **Järgmine peatükk**: Liigu järgmisele keerukuse tasemele

### Kursus lõpetamise eelised
Kõigi peatükkide lõpetamisel on sul:
- **Tootmiskogemus**: Tõeliste AI rakenduste juurutamine Azure’isse
- **Professionaalsed oskused**: Ettevõttesisesteks juurutusteks valmis olemine  
- **Kogukonna tunnustus**: Aktiivne liige Azure arendajakogukonnas
- **Karjääri edenemine**: Nõutud AZD ja AI juurutamise ekspertteadmised

---

## 🤝 Kogukond ja tugi

### Abi ja tugi
- **Tehnilised probleemid**: [Tõrgete teatamine ja funktsioonisoovid](https://github.com/microsoft/azd-for-beginners/issues)
- **Õppeküsimused**: [Microsoft Azure Discord kogukond](https://discord.gg/microsoft-azure) ja [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **AI-spetsiifiline abi**: Liitu [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **Dokumentatsioon**: [Ametlik Azure arendaja CLI dokumentatsioon](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)

### Kogukonna vaated Microsoft Foundry Discordist

**Viimased küsitluse tulemused #Azure kanalist:**
- **45%** arendajatest soovib kasutada AZD-d tehisintellekti töökoormuste jaoks
- **Peamised väljakutsed**: Mitmeteenuste juurutamine, mandaatide haldamine, tootmisvalmidus  
- **Kõige enam soovitud**: AI-spetsiifilised mallid, tõrkeotsingu juhendid, parimad praktikad

**Liitu meie kogukonnaga, et:**
- Jagada oma AZD + AI kogemusi ja saada abi
- Juurdepääs varajastele eelvaadetele uute AI mallide kohta
- Panustada AI juurutamise parimatesse praktikatesse
- Mõjutada tulevasi AI + AZD funktsioonide arenguid

### Kursusele panustamine
Ootame panuseid! Palun loe meie [Panustamise juhendit](CONTRIBUTING.md), mis käsitleb:
- **Sisute parandamine**: Värskenda olemasolevaid peatükke ja näiteid
- **Uued näited**: Lisa reaalse maailma stsenaariume ja malle  
- **Tõlkimine**: Aita säilitada mitmekeelset tuge
- **Vigade teatamine**: Paranda täpsust ja arusaadavust
- **Kogukonna standardid**: Järgi kaasava kogukonna juhiseid

---

## 📄 Kursuse info

### Litsents
See projekt on litsentseeritud MIT litsentsi alusel - vaata üksikasju [LICENSE](../../LICENSE) failist.

### Seotud Microsofti õppeallikad

Meie meeskond toodab teisi põhjalikke õppekoole:

<!-- CO-OP TRANSLATOR OTHER COURSES START -->
### LangChain
[![LangChain4j algajatele](https://img.shields.io/badge/LangChain4j%20for%20Beginners-22C55E?style=for-the-badge&&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchain4j-for-beginners)
[![LangChain.js algajatele](https://img.shields.io/badge/LangChain.js%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchainjs-for-beginners?WT.mc_id=m365-94501-dwahlin)

---

### Azure / Edge / MCP / Agendid
[![AZD algajatele](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Edge AI algajatele](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![MCP algajatele](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)
[![AI agendid algajatele](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Generatiivse tehisintellekti sari
[![Generatiivne AI algajatele](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Generatiivne AI (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
[![Generatiivne AI (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)
[![Generatiivne AI (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---
 
### Põhiõpe
[![ML algajatele](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![Andmeteadus algajatele](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![Tehisintellekt algajatele](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Küberjulgeolek algajatele](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Veebiarendus algajatele](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![Asjade internet algajatele](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![XR arendus algajatele](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### CoPilot seeria
[![CoPilot AI paarisprogrammeerimiseks](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![CoPilot C#/.NET jaoks](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![CoPilot seiklus](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ Kursuse navigatsioon

**🚀 Valmis õppima hakkama?**

**Algajad**: Alustage jaotisest [1. peatükk: Alused ja kiire algus](../..)  
**Tehisintellekti arendajad**: Minge jaotisse [2. peatükk: Tehisintellekt esmane arendus](../..)  
**Kogenud arendajad**: Alustage jaotisest [3. peatükk: Konfiguratsioon ja autentimine](../..)

**Järgmised sammud**: [Alustage 1. peatükiga - AZD põhialused](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Tähelepanek**:
See dokument on tõlgitud kasutades tehisintellekti tõlketeenust [Co-op Translator](https://github.com/Azure/co-op-translator). Kuigi püüdleme täpsuse poole, tuleb arvestada, et automaatsed tõlked võivad sisaldada vigu või ebatäpsusi. Originaaldokument oma emakeeles tuleks pidada autoriteetseks allikaks. Olulise info puhul soovitatakse professionaalset inimtõlget. Me ei vastuta selle tõlkega seotud arusaamatuste või valesti mõistmiste eest.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->