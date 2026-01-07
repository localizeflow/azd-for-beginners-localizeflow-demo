<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T14:41:10+00:00",
  "source_file": "README.md",
  "language_code": "hr"
}
-->
> Napomena: Ova dokumentacija se kontinuirano ažurira kako bi odražavala najnovije promjene.

> ⚠️ Ovaj repozitorij je demo kreiran za prikaz
> automatizirane lokalizacije dokumentacije pomoću Localizeflow.
>
> Izvorni sadržaj temelji se na
> Microsoftovom projektu "AZD za početnike".


# AZD za početnike: Strukturirano učenje

![AZD-for-beginners](../../translated_images/azdbeginners.5527441dd9f74068.hr.png) 

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## Početak s ovim tečajem

Slijedite ove korake da započnete svoju AZD putanju učenja:

1. **Forkajte repozitorij**: Kliknite [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)
2. **Klonirajte repozitorij**: `git clone https://github.com/microsoft/azd-for-beginners.git`
3. **Pridružite se zajednici**: [Azure Discord zajednice](https://discord.com/invite/ByRwuEEgH4) za stručnu podršku
4. **Odaberite svoj put učenja**: Izaberite poglavlje ispod koje odgovara vašoj razini iskustva

### Podrška za više jezika

#### Automatski prijevodi (UVIJEK ažurno)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](./README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Preferirate li klonirati lokalno?**

> Ovaj repozitorij uključuje prijevode na preko 50 jezika što značajno povećava veličinu preuzimanja. Za kloniranje bez prijevoda koristite sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> To vam daje sve što vam treba da završite tečaj s mnogo bržim preuzimanjem.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## Pregled tečaja

Savladajte Azure Developer CLI (azd) kroz strukturirane cjeline osmišljene za postupno učenje. **Poseban fokus na implementaciji AI aplikacija s integracijom Microsoft Foundry.**

### Zašto je ovaj tečaj bitan za moderne programere

Na temelju uvida iz Microsoft Foundry Discord zajednice, **45% programera želi koristiti AZD za AI radne procese** ali nailaze na izazove s:
- Složenim AI arhitekturama s više usluga
- Najboljim praksama za produkcijsku AI implementaciju  
- Integracijom i konfiguracijom Azure AI servisa
- Optimizacijom troškova za AI zadatke
- Rješavanjem problema specifičnih za AI implementacije

### Ciljevi učenja

Završetkom ovog strukturiranog tečaja ćete:
- **Ovladati AZD osnovama**: Ključni koncepti, instalacija i konfiguracija
- **Implementirati AI aplikacije**: Koristiti AZD sa Microsoft Foundry servisima
- **Implementirati Infrastructure as Code**: Upravljati Azure resursima pomoću Bicep predložaka
- **Otklanjati poteškoće kod implementacija**: Rješavati uobičajene probleme i debugirati
- **Optimizirati za produkciju**: Sigurnost, skaliranje, nadzor i upravljanje troškovima
- **Izgraditi višestruke AI agent rješenja**: Implementirati složene AI arhitekture

## 📚 Poglavlja za učenje

*Odaberite svoj put učenja na temelju razine iskustva i ciljeva*

### 🚀 Poglavlje 1: Osnove i Brzi Početak
**Preduvjeti**: Azure pretplata, osnovno znanje komandne linije  
**Trajanje**: 30-45 minuta  
**Kompleksnost**: ⭐

#### Što ćete naučiti
- Razumijevanje osnova Azure Developer CLI
- Instalacija AZD na vašu platformu
- Prva uspješna implementacija

#### Resursi za učenje
- **🎯 Počnite ovdje**: [Što je Azure Developer CLI?](../..)
- **📖 Teorija**: [AZD osnove](docs/getting-started/azd-basics.md) - Ključni koncepti i terminologija
- **⚙️ Postavljanje**: [Instalacija i postavljanje](docs/getting-started/installation.md) - Vodiči za platformu
- **🛠️ Praktično**: [Vaš prvi projekt](docs/getting-started/first-project.md) - Korak-po-korak tutorial
- **📋 Brzi referentni vodič**: [Spisak komandi](resources/cheat-sheet.md)

#### Praktične vježbe
```bash
# Brza provjera instalacije
azd version

# Postavite svoju prvu aplikaciju
azd init --template todo-nodejs-mongo
azd up
```

**💡 Ishod poglavlja**: Uspješno implementirati jednostavnu web aplikaciju na Azure pomoću AZD

**✅ Validacija uspjeha:**
```bash
# Nakon dovršetka Poglavlja 1, trebali biste moći:
azd version              # Prikazuje instaliranu verziju
azd init --template todo-nodejs-mongo  # Inicijalizira projekt
azd up                  # Raspoređuje na Azure
azd show                # Prikazuje URL pokrenute aplikacije
# Aplikacija se otvara u pregledniku i radi
azd down --force --purge  # Čisti resurse
```

**📊 Uloženo vrijeme:** 30-45 minuta  
**📈 Razina znanja nakon:** Može samostalno implementirati osnovne aplikacije

**✅ Validacija uspjeha:**
```bash
# Nakon dovršetka Poglavlja 1, trebali biste moći:
azd version              # Prikazuje instaliranu verziju
azd init --template todo-nodejs-mongo  # Inicijalizira projekt
azd up                  # Implementira na Azure
azd show                # Prikazuje URL aktivne aplikacije
# Aplikacija se otvara u pregledniku i radi
azd down --force --purge  # Čisti resurse
```

**📊 Uloženo vrijeme:** 30-45 minuta  
**📈 Razina znanja nakon:** Može samostalno implementirati osnovne aplikacije

---

### 🤖 Poglavlje 2: AI-prvo razvoja (Preporučeno za AI programere)
**Preduvjeti**: Završeno poglavlje 1  
**Trajanje**: 1-2 sata  
**Kompleksnost**: ⭐⭐

#### Što ćete naučiti
- Integracija Microsoft Foundry s AZD
- Primjena AI-powered aplikacija
- Razumijevanje konfiguracija AI servisa

#### Resursi za učenje
- **🎯 Počnite ovdje**: [Integracija Microsoft Foundry](docs/microsoft-foundry/microsoft-foundry-integration.md)
- **📖 Uzorci**: [Implementacija AI modela](docs/microsoft-foundry/ai-model-deployment.md) - Implementacija i upravljanje AI modelima
- **🛠️ Radionica**: [AI radionica](docs/microsoft-foundry/ai-workshop-lab.md) - Priprema AI rješenja za AZD
- **🎥 Interaktivni vodič**: [Materijali radionice](workshop/README.md) - Učenje putem preglednika s MkDocs * DevContainer okruženjem
- **📋 Predlošci**: [Microsoft Foundry predlošci](../..)
- **📝 Primjeri**: [Primjeri AZD implementacija](examples/README.md)

#### Praktične vježbe
```bash
# Postavite svoju prvu AI aplikaciju
azd init --template azure-search-openai-demo
azd up

# Isprobajte dodatne AI predloške
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```

**💡 Ishod poglavlja**: Implementirati i konfigurirati AI-chat aplikaciju s RAG mogućnostima

**✅ Validacija uspjeha:**
```bash
# Nakon Poglavlja 2, trebali biste moći:
azd init --template azure-search-openai-demo
azd up
# Testirati AI chat sučelje
# Postavljati pitanja i dobivati AI-pokretane odgovore s izvorima
# Provjeriti radi li integracija pretraživanja
azd monitor  # Provjeriti prikazuje li Application Insights telemetriju
azd down --force --purge
```

**📊 Uloženo vrijeme:** 1-2 sata  
**📈 Razina znanja nakon:** Može implementirati i konfigurirati AI aplikacije spremne za produkciju  
**💰 Svijest o troškovima:** Razumijevanje troškova razvoja od 80-150 USD/mj i produkcijskih 300-3500 USD/mj

#### 💰 Troškovi AI implementacija

**Razvojno okruženje (Procijenjeno 80-150 USD/mj):**
- Azure OpenAI (pay-as-you-go): 0-50 USD/mj (ovisno o korištenju tokena)
- AI Search (osnovna razina): 75 USD/mj
- Container Apps (potrošnja): 0-20 USD/mj
- Pohrana (standard): 1-5 USD/mj

**Produkcijsko okruženje (Procijenjeno 300-3.500+ USD/mj):**
- Azure OpenAI (PTU za dosljedne performanse): 3.000+ USD/mj ILI plaćanje po potrošnji kod velikih volumena
- AI Search (standardna razina): 250 USD/mj
- Container Apps (dedikirano): 50-100 USD/mj
- Application Insights: 5-50 USD/mj
- Pohrana (premium): 10-50 USD/mj

**💡 Savjeti za optimizaciju troškova:**
- Koristite **Besplatnu razinu** Azure OpenAI za učenje (50.000 tokena/mj uključeno)
- Pokrenite `azd down` za oslobađanje resursa kad ne radite aktivno razvoj
- Počnite s naplatom po potrošnji, PTU koristite samo za produkciju
- Koristite `azd provision --preview` za procjenu troškova prije implementacije
- Omogućite automatsko skaliranje: plaćate samo stvarnu potrošnju

**Nadzor troškova:**
```bash
# Provjerite procijenjene mjesečne troškove
azd provision --preview

# Pratite stvarne troškove u Azure Portalu
az consumption budget list --resource-group <your-rg>
```

---

### ⚙️ Poglavlje 3: Konfiguracija i autentifikacija
**Preduvjeti**: Završeno poglavlje 1  
**Trajanje**: 45-60 minuta  
**Kompleksnost**: ⭐⭐

#### Što ćete naučiti
- Konfiguracija i upravljanje okruženjem
- Najbolje prakse autentifikacije i sigurnosti
- Imenovanje i organizacija resursa

#### Resursi za učenje
- **📖 Konfiguracija**: [Vodič za konfiguraciju](docs/getting-started/configuration.md) - Postavljanje okruženja
- **🔐 Sigurnost**: [Autentifikacijski obrasci i upravljani identitet](docs/getting-started/authsecurity.md) - Obrasci autentifikacije
- **📝 Primjeri**: [Primjer baze podataka](examples/database-app/README.md) - Primjeri baza s AZD

#### Praktične vježbe
- Konfigurirajte više okruženja (dev, staging, prod)
- Postavite autentifikaciju putem managed identity
- Implementirajte konfiguracije specifične za okruženje

**💡 Ishod poglavlja**: Upravljajte više okruženja s ispravnom autentifikacijom i sigurnošću

---

### 🏗️ Poglavlje 4: Infrastructure as Code i implementacija
**Preduvjeti**: Završena poglavlja 1-3  
**Trajanje**: 1-1.5 sati  
**Kompleksnost**: ⭐⭐⭐

#### Što ćete naučiti
- Napredni obrasci implementacije
- Infrastructure as Code pomoću Bicep-a
- Strategije za provisioniranje resursa

#### Resursi za učenje
- **📖 Implementacija**: [Vodič za implementaciju](docs/deployment/deployment-guide.md) - Kompletnu workflow-e
- **🏗️ Provisioniranje**: [Provisioniranje resursa](docs/deployment/provisioning.md) - Upravljanje Azure resursima
- **📝 Primjeri**: [Primjer Container app](../../examples/container-app) - Containerizirane implementacije

#### Praktične vježbe
- Kreirajte vlastite Bicep predloške
- Implementirajte aplikacije s više servisa
- Implementirajte strategije blue-green deploymenta

**💡 Ishod poglavlja**: Implementirajte složene višeservisne aplikacije koristeći prilagođene predloške infrastrukture

---
### 🎯 Poglavlje 5: Višeagentska AI rješenja (Napredno)
**Preduvjeti**: Poglavlja 1-2 završena  
**Trajanje**: 2-3 sata  
**Složenost**: ⭐⭐⭐⭐

#### Što ćete naučiti
- Obrasci višeagentske arhitekture
- Orkestracija i koordinacija agenata
- AI implementacije spremne za produkciju

#### Izvori za učenje
- **🤖 Istaknuti projekt**: [Višeagentsko rješenje za maloprodaju](examples/retail-scenario.md) - Potpuna implementacija
- **🛠️ ARM predlošci**: [ARM paket predložaka](../../examples/retail-multiagent-arm-template) - Jednim klikom za implementaciju
- **📖 Arhitektura**: [Obrasci koordinacije više agenata](/docs/pre-deployment/coordination-patterns.md) - Obrasci

#### Praktične vježbe
```bash
# Postavite kompletnu maloprodajnu višeslojnu agentsku soluciju
cd examples/retail-multiagent-arm-template
./deploy.sh

# Istražite konfiguracije agenata
az deployment group show --resource-group <rg-name> --name <deployment-name>
```

**💡 Ishod poglavlja**: Implementirajte i upravljajte višeagentskim AI rješenjem spremnim za produkciju s agentima za korisnike i inventar

---

### 🔍 Poglavlje 6: Validacija i planiranje prije implementacije
**Preduvjeti**: Poglavlje 4 završeno  
**Trajanje**: 1 sat  
**Složenost**: ⭐⭐

#### Što ćete naučiti
- Planiranje kapaciteta i validacija resursa
- Strategije odabira SKU-a
- Provjere prije pokretanja i automatizacija

#### Izvori za učenje
- **📊 Planiranje**: [Planiranje kapaciteta](docs/pre-deployment/capacity-planning.md) - Validacija resursa
- **💰 Odabir**: [Odabir SKU](docs/pre-deployment/sku-selection.md) - Izbor povoljan za troškove
- **✅ Validacija**: [Provjere prije pokretanja](docs/pre-deployment/preflight-checks.md) - Automatizirani skripti

#### Praktične vježbe
- Pokrenite skripte za validaciju kapaciteta
- Optimizirajte odabir SKU za troškove
- Implementirajte automatizirane provjere prije implementacije

**💡 Ishod poglavlja**: Validirajte i optimizirajte implementacije prije izvršavanja

---

### 🚨 Poglavlje 7: Otklanjanje problema i ispravljanje grešaka
**Preduvjeti**: Neko poglavlje o implementaciji završeno  
**Trajanje**: 1-1.5 sati  
**Složenost**: ⭐⭐

#### Što ćete naučiti
- Sistematski pristupi ispravljanju grešaka
- Uobičajeni problemi i rješenja
- Otklanjanje problema specifičnih za AI

#### Izvori za učenje
- **🔧 Uobičajeni problemi**: [Česti problemi](docs/troubleshooting/common-issues.md) - Često postavljana pitanja i rješenja
- **🕵️ Ispravljanje grešaka**: [Vodič za ispravljanje grešaka](docs/troubleshooting/debugging.md) - Korak-po-korak strategije
- **🤖 AI problemi**: [Otklanjanje problema vezanih uz AI](docs/troubleshooting/ai-troubleshooting.md) - Problemi s AI uslugama

#### Praktične vježbe
- Dijagnosticirajte neuspjehe implementacije
- Riješite probleme s autentifikacijom
- Ispravite greške pri povezivanju s AI uslugama

**💡 Ishod poglavlja**: Samostalno dijagnosticirati i riješiti uobičajene probleme prilikom implementacije

---

### 🏢 Poglavlje 8: Obrasci za produkciju i poduzeća
**Preduvjeti**: Poglavlja 1-4 završena  
**Trajanje**: 2-3 sata  
**Složenost**: ⭐⭐⭐⭐

#### Što ćete naučiti
- Strategije produkcijske implementacije
- Sigurnosni obrasci za poduzeća
- Praćenje i optimizacija troškova

#### Izvori za učenje
- **🏭 Produkcija**: [Najbolje prakse AI produkcije](docs/microsoft-foundry/production-ai-practices.md) - Obrasci za poduzeća
- **📝 Primjeri**: [Microservices primjer](../../examples/microservices) - Kompleksne arhitekture
- **📊 Praćenje**: [Integracija Application Insights](docs/pre-deployment/application-insights.md) - Praćenje

#### Praktične vježbe
- Implementirajte sigurnosne obrasce za poduzeća
- Postavite sveobuhvatno praćenje
- Implementirajte u produkciju s odgovarajućim upravljanjem

**💡 Ishod poglavlja**: Implementirajte aplikacije spremne za poduzeća s punim produkcijskim mogućnostima

---

## 🎓 Pregled radionice: Praktično učenje

> **⚠️ STATUS RADIONICE: Aktivni razvoj**  
> Materijali radionice su trenutno u izradi i doradi. Glavni moduli su funkcionalni, ali neki napredni odjeli nisu dovršeni. Aktivno radimo na dovršetku sadržaja. [Pratite napredak →](workshop/README.md)

### Interaktivni materijali radionice
**Sveobuhvatno praktično učenje s alatima u pregledniku i vođenim vježbama**

Naši materijali radionice pružaju strukturirano, interaktivno iskustvo učenja koje nadopunjuje gore navedeni plan poglavlja. Radionica je dizajnirana za samostalno učenje i vođene instruktorske sesije.

#### 🛠️ Značajke radionice
- **Sučelje u pregledniku**: Potpuna radionica vođena MkDocs-om s pretraživanjem, kopiranjem i temama
- **Integracija GitHub Codespaces**: Postavljanje razvojnih okruženja jednim klikom
- **Strukturirani put učenja**: 7 koraka vođenih vježbi (ukupno 3,5 sati)
- **Otkriće → Implementacija → Prilagodba**: Progresivna metodologija
- **Interaktivno DevContainer okruženje**: Prekonfigurirani alati i ovisnosti

#### 📚 Struktura radionice
Radionica slijedi metodologiju **Otkriće → Implementacija → Prilagodba**:

1. **Faza otkrića** (45 min)
   - Istražite Microsoft Foundry predloške i usluge
   - Razumite obrasce višeagentske arhitekture
   - Pregledajte zahtjeve i preduvjete za implementaciju

2. **Faza implementacije** (2 sata)
   - Praktična implementacija AI aplikacija pomoću AZD-a
   - Konfigurirajte Azure AI usluge i endpointove
   - Implementirajte sigurnosne i autentifikacijske obrasce

3. **Faza prilagodbe** (45 min)
   - Prilagodite aplikacije za specifične primjene
   - Optimizirajte za produkcijsku implementaciju
   - Implementirajte praćenje i upravljanje troškovima

#### 🚀 Početak rada s radionicom
```bash
# Opcija 1: GitHub Codespaces (Preporučeno)
# Kliknite "Code" → "Create codespace on main" u spremištu

# Opcija 2: Lokalni razvoj
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# Slijedite upute za postavljanje u workshop/README.md
```

#### 🎯 Ishodi učenja radionice
Nakon završetka radionice sudionici će:
- **Implementirati AI aplikacije za produkciju**: Koristeći AZD i Microsoft Foundry usluge
- **Naučiti višagentske arhitekture**: Implementirati koordinirana rješenja s AI agentima
- **Primijeniti najbolje sigurnosne prakse**: Konfigurirati autentifikaciju i kontrolu pristupa
- **Optimizirati za skaliranje**: Dizajnirati isplative i učinkovite implementacije
- **Otklanjati probleme implementacija**: Samostalno rješavati uobičajene probleme

#### 📖 Resursi radionice
- **🎥 Interaktivni vodič**: [Materijali radionice](workshop/README.md) - Učenje u pregledniku
- **📋 Upute korak-po-korak**: [Vođene vježbe](../../workshop/docs/instructions) - Detaljni vodiči
- **🛠️ AI laboratorij radionice**: [AI radionica laboratorij](docs/microsoft-foundry/ai-workshop-lab.md) - Vježbe usmjerene na AI
- **💡 Brzi početak**: [Vodič za postavljanje radionice](workshop/README.md#quick-start) - Konfiguracija okruženja

**Izvrsno za**: Korporativne treninge, sveučilišne tečajeve, samostalno učenje i bootcampove za developere.

---

## 📖 Što je Azure Developer CLI?

Azure Developer CLI (azd) je naredbeni alat usmjeren prema developerima koji ubrzava proces izgradnje i implementacije aplikacija na Azure. Pruža:

- **Implementacije temeljene na predlošcima** - Koristite unaprijed izrađene predloške za uobičajene obrasce aplikacija
- **Infrastruktura kao kod** - Upravljajte Azure resursima koristeći Bicep ili Terraform  
- **Integrirane radne procedure** - Bez problema pruža, implementira i prati aplikacije
- **Prilagođeno razvojnim inženjerima** - Optimizirano za produktivnost i iskustvo developera

### **AZD + Microsoft Foundry: Savršeno za AI implementacije**

**Zašto izabrati AZD za AI rješenja?** AZD rješava glavne izazove s kojima se suočavaju AI developeri:

- **Predlošci spremni za AI** - Predkonfigurirani predlošci za Azure OpenAI, Cognitive Services i ML zadatke
- **Sigurne AI implementacije** - Ugrađeni sigurnosni obrasci za AI usluge, API ključeve i modele endpointa  
- **Produkcijski AI obrasci** - Najbolje prakse za skalabilne i isplative AI aplikacije
- **Sveobuhvatni AI radni tijekovi** - Od razvoja modela do produkcijske implementacije s ispravnim praćenjem
- **Optimizacija troškova** - Pametno raspoređivanje resursa i strategije skaliranja za AI radne zadatke
- **Integracija Microsoft Foundry** - Besprijekorna veza s katalogom modela i endpointima Microsoft Foundry

---

## 🎯 Predlošci i biblioteka primjera

### Istaknuto: Microsoft Foundry predlošci
**Počnite ovdje ako implementirate AI aplikacije!**

> **Napomena:** Ovi predlošci prikazuju različite AI obrasce. Neki su vanjski Azure primjeri, dok su drugi lokalne implementacije.

| Predložak | Poglavlje | Složenost | Usluge | Vrsta |
|----------|-----------|-----------|--------|-------|
| [**Početak s AI chatom**](https://github.com/Azure-Samples/get-started-with-ai-chat) | Poglavlje 2 | ⭐⭐ | AzureOpenAI + Azure AI Model Inference API + Azure AI Search + Azure Container Apps + Application Insights | Vanjski |
| [**Početak s AI agentima**](https://github.com/Azure-Samples/get-started-with-ai-agents) | Poglavlje 2 | ⭐⭐ | Azure AI Agent Service + AzureOpenAI + Azure AI Search + Azure Container Apps + Application Insights| Vanjski |
| [**Azure Search + OpenAI demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Poglavlje 2 | ⭐⭐ | AzureOpenAI + Azure AI Search + App Service + Storage | Vanjski |
| [**OpenAI Chat App Quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Poglavlje 2 | ⭐ | AzureOpenAI + Container Apps + Application Insights | Vanjski |
| [**Agent OpenAI Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Poglavlje 5 | ⭐⭐⭐ | AzureOpenAI + Azure Functions + Prompty | Vanjski |
| [**Contoso Chat RAG**](https://github.com/Azure-Samples/contoso-chat) | Poglavlje 8 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Cosmos DB + Container Apps | Vanjski |
| [**Višeagentsko rješenje za maloprodaju**](examples/retail-scenario.md) | Poglavlje 5 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Storage + Container Apps + Cosmos DB | **Lokalno** |

### Istaknuto: Potpuni scenariji učenja
**Predlošci aplikacija spremnih za produkciju povezani s poglavljima za učenje**

| Predložak | Poglavlje za učenje | Složenost | Ključna tema učenja |
|----------|---------------------|-----------|---------------------|
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Poglavlje 2 | ⭐ | Osnovni obrasci AI implementacije |
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Poglavlje 2 | ⭐⭐ | RAG implementacija sa Azure AI Search |
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | Poglavlje 4 | ⭐⭐ | Integracija inteligencije dokumenata |
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Poglavlje 5 | ⭐⭐⭐ | Okviri agenata i pozivanje funkcija |
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | Poglavlje 8 | ⭐⭐⭐ | Orkestracija AI za poduzeća |
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | Poglavlje 5 | ⭐⭐⭐⭐ | Višeagentska arhitektura s agentima za korisnike i inventar |

### Učenje po vrsti primjera

> **📌 Lokalni vs. Vanjski primjeri:**  
> **Lokalni primjeri** (u ovom repozitoriju) = Spremni za odmah korištenje  
> **Vanjski primjeri** (Azure primjeri) = Klonirajte iz povezanih repozitorija

#### Lokalni primjeri (spremni za korištenje)
- [**Višeagentsko rješenje za maloprodaju**](examples/retail-scenario.md) - Potpuna implementacija spremna za produkciju s ARM predlošcima
  - Višeagentska arhitektura (agenti za kupce i inventar)
  - Sveobuhvatno praćenje i evaluacija
  - Implementacija jednim klikom preko ARM predloška

#### Lokalni primjeri - aplikacije u kontejnerima (Poglavlja 2-5)
**Sveobuhvatni primjeri implementacije kontejnera u ovom repozitoriju:**
- [**Primjeri Container aplikacija**](examples/container-app/README.md) - Potpuni vodič za kontejnere
  - [Jednostavan Flask API](../../examples/container-app/simple-flask-api) - Osnovni REST API sa skaliranjem do nule
  - [Arhitektura mikroservisa](../../examples/container-app/microservices) - Produkcijska višeuslužna implementacija
  - Obrasci brzog početka, produkcije i napredne implementacije
  - Upute za praćenje, sigurnost i optimizaciju troškova

#### Vanjski primjeri - Jednostavne aplikacije (Poglavlja 1-2)
**Klonirajte ove Azure primjere za početak:**
- Jednostavna web aplikacija - Node.js + MongoDB ([repo](https://github.com/Azure-Samples/todo-nodejs-mongo)) - Osnovni obrasci implementacije
- Statička web stranica - React SPA ([repo](https://github.com/Azure-Samples/todo-csharp-sql-swa-func)) - Implementacija statičkog sadržaja
- Container App - Python Flask ([repo](https://github.com/Azure-Samples/container-apps-store-api-microservice)) - Implementacija REST API-ja

#### Vanjski primjeri - Integracija baza podataka (Poglavlja 3-4)  
- Aplikacija s bazom podataka - C# + SQL ([repo](https://github.com/Azure-Samples/todo-csharp-sql)) - Obrasci povezivanja s bazama
- Functions + Cosmos DB ([repo](https://github.com/Azure-Samples/todo-python-mongo-swa-func)) - Serverless podatkovni tok

#### Vanjski primjeri - Napredni obrasci (Poglavlja 4-8)
- Java mikroservisi ([repo](https://github.com/Azure-Samples/java-microservices-aca-lab)) - Višeslužne arhitekture
- Container Apps poslovi ([repo](https://github.com/Azure-Samples/container-apps-jobs)) - Obrada u pozadini  
- Enterprise ML pipeline ([repo](https://github.com/Azure-Samples/mlops-v2)) - Producentne ML prakse

### Vanjske kolekcije predložaka
- [**Službena galerija predložaka AZD**](https://azure.github.io/awesome-azd/) - Kurirana kolekcija službenih i zajedničkih predložaka
- [**Azure Developer CLI predlošci**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - Dokumentacija Microsoft Learn predložaka
- [**Direktorij primjera**](examples/README.md) - Lokalni primjeri za učenje s detaljnim objašnjenjima

---

## 📚 Resursi za učenje i reference

### Brze reference
- [**Komandna prečica**](resources/cheat-sheet.md) - Osnovne azd naredbe organizirane po poglavljima
- [**Rječnik pojmova**](resources/glossary.md) - Terminologija Azure i azd  
- [**Često postavljana pitanja**](resources/faq.md) - Česta pitanja organizirana po poglavljima
- [**Vodič za učenje**](resources/study-guide.md) - Sveobuhvatne vježbe za praksu

### Radionice s praksom
- [**AI radionica**](docs/microsoft-foundry/ai-workshop-lab.md) - Pripremite svoje AI rješenja za AZD implementaciju (2-3 sata)
- [**Interaktivni vodič radionice**](workshop/README.md) - Radionica u pregledniku s MkDocs i DevContainer okruženjem
- [**Strukturirani put učenja**](../../workshop/docs/instructions) - 7-koraka vođene vježbe (Otkriće → Implementacija → Prilagodba)
- [**AZD radionica za početnike**](workshop/README.md) - Potpuni materijali radionice s integracijom GitHub Codespaces

### Vanjski resursi za učenje
- Dokumentacija Azure Developer CLI-ja (https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)
- Azure Architecture Center (https://learn.microsoft.com/en-us/azure/architecture/)
- Kalkulator cijena Azure (https://azure.microsoft.com/pricing/calculator/)
- Status Azure (https://status.azure.com/)

---

## 🔧 Brzi vodič za rješavanje problema

**Česti problemi koje početnici susreću i trenutna rješenja:**

### ❌ "azd: naredba nije pronađena"

```bash
# Prvo instalirajte AZD
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Provjerite instalaciju
azd version
```

### ❌ "Pretplata nije pronađena" ili "Pretplata nije postavljena"

```bash
# Popis dostupnih pretplata
az account list --output table

# Postavi zadanu pretplatu
az account set --subscription "<subscription-id-or-name>"

# Postavi za AZD okruženje
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Provjeri
az account show
```

### ❌ "Nedovoljna kvota" ili "Kvota premašena"

```bash
# Isprobajte drugu Azure regiju
azd env set AZURE_LOCATION "westus2"
azd up

# Ili koristite manje SKU-ove u razvoju
# Uredite infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```

### ❌ "azd up" ne uspijeva na pola puta

```bash
# Opcija 1: Očistite i pokušajte ponovo
azd down --force --purge
azd up

# Opcija 2: Samo popravite infrastrukturu
azd provision

# Opcija 3: Provjerite detaljne zapise
azd show
azd logs
```

### ❌ "Autentikacija nije uspjela" ili "Token je istekao"

```bash
# Ponovno provjerite autentičnost
az logout
az login

azd auth logout
azd auth login

# Provjerite autentifikaciju
az account show
```

### ❌ "Resurs već postoji" ili sukobi u imenima

```bash
# AZD generira jedinstvena imena, ali ako dođe do sukoba:
azd down --force --purge

# Onda pokušajte ponovno s novim okruženjem
azd env new dev-v2
azd up
```

### ❌ Deploy predloška traje predugo

**Normalna vremena čekanja:**
- Jednostavna web aplikacija: 5-10 minuta
- Aplikacija s bazom podataka: 10-15 minuta
- AI aplikacije: 15-25 minuta (provisioniranje OpenAI-a je sporo)

```bash
# Provjeri napredak
azd show

# Ako zapneš više od 30 minuta, provjeri Azure Portal:
azd monitor
# Potraži neuspjele implementacije
```

### ❌ "Dozvola odbijena" ili "Zabranjeno"

```bash
# Provjerite svoju Azure ulogu
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Trebate barem ulogu "Contributor"
# Zatražite od vašeg Azure administratora da omogući:
# - Contributor (za resurse)
# - User Access Administrator (za dodjelu uloga)
```

### ❌ Ne mogu pronaći URL implementirane aplikacije

```bash
# Prikaži sve krajnje točke usluge
azd show

# Ili otvori Azure portal
azd monitor

# Provjeri određenu uslugu
azd env get-values
# Potraži *_URL varijable
```

### 📚 Kompletni resursi za rješavanje problema

- **Vodič za česte probleme:** [Detaljna rješenja](docs/troubleshooting/common-issues.md)
- **Problemi specifični za AI:** [Rješavanje problema s AI](docs/troubleshooting/ai-troubleshooting.md)
- **Vodič za otklanjanje pogrešaka:** [Korak-po-korak otklanjanje pogrešaka](docs/troubleshooting/debugging.md)
- **Potražite pomoć:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🔧 Brzi vodič za rješavanje problema

**Česti problemi koje početnici susreću i trenutna rješenja:**

<details>
<summary><strong>❌ "azd: naredba nije pronađena"</strong></summary>

```bash
# Prvo instalirajte AZD
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Provjerite instalaciju
azd version
```
</details>

<details>
<summary><strong>❌ "Pretplata nije pronađena" ili "Pretplata nije postavljena"</strong></summary>

```bash
# Prikaži dostupne pretplate
az account list --output table

# Postavi zadanu pretplatu
az account set --subscription "<subscription-id-or-name>"

# Postavi za AZD okruženje
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Provjeri
az account show
```
</details>

<details>
<summary><strong>❌ "Nedovoljna kvota" ili "Kvota premašena"</strong></summary>

```bash
# Pokušajte drugačiju Azure regiju
azd env set AZURE_LOCATION "westus2"
azd up

# Ili koristite manje SKU-ove u razvoju
# Uredite infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>

<details>
<summary><strong>❌ "azd up" ne uspijeva na pola puta</strong></summary>

```bash
# Opcija 1: Očisti i pokušaj ponovo
azd down --force --purge
azd up

# Opcija 2: Samo popravi infrastrukturu
azd provision

# Opcija 3: Provjeri detaljne zapise
azd show
azd logs
```
</details>

<details>
<summary><strong>❌ "Autentikacija nije uspjela" ili "Token je istekao"</strong></summary>

```bash
# Ponovno se autentificirajte
az logout
az login

azd auth logout
azd auth login

# Provjerite autentifikaciju
az account show
```
</details>

<details>
<summary><strong>❌ "Resurs već postoji" ili sukobi u imenima</strong></summary>

```bash
# AZD generira jedinstvena imena, ali ako dođe do sukoba:
azd down --force --purge

# Zatim pokušajte ponovno s novim okruženjem
azd env new dev-v2
azd up
```
</details>

<details>
<summary><strong>❌ Deploy predloška traje predugo</strong></summary>

**Normalna vremena čekanja:**
- Jednostavna web aplikacija: 5-10 minuta
- Aplikacija s bazom podataka: 10-15 minuta
- AI aplikacije: 15-25 minuta (provisioniranje OpenAI-a je sporo)

```bash
# Provjerite napredak
azd show

# Ako ste zaglavljeni >30 minuta, provjerite Azure Portal:
azd monitor
# Potražite neuspjele implementacije
```
</details>

<details>
<summary><strong>❌ "Dozvola odbijena" ili "Zabranjeno"</strong></summary>

```bash
# Provjerite svoju Azure ulogu
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Potreban vam je barem "Contributor" uloga
# Zamolite svog Azure administratora da dodijeli:
# - Contributor (za resurse)
# - User Access Administrator (za dodjelu uloga)
```
</details>

<details>
<summary><strong>❌ Ne mogu pronaći URL implementirane aplikacije</strong></summary>

```bash
# Prikaži sve krajnje točke usluga
azd show

# Ili otvorite Azure portal
azd monitor

# Provjerite određenu uslugu
azd env get-values
# Potražite *_URL varijable
```
</details>

### 📚 Kompletni resursi za rješavanje problema

- **Vodič za česte probleme:** [Detaljna rješenja](docs/troubleshooting/common-issues.md)
- **Problemi specifični za AI:** [Rješavanje problema s AI](docs/troubleshooting/ai-troubleshooting.md)
- **Vodič za otklanjanje pogrešaka:** [Korak-po-korak otklanjanje pogrešaka](docs/troubleshooting/debugging.md)
- **Potražite pomoć:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🎓 Završetak tečaja i certifikacija

### Praćenje napretka
Pratite svoj napredak u učenju kroz svako poglavlje:

- [ ] **Poglavlje 1**: Osnove i Brzi početak ✅
- [ ] **Poglavlje 2**: AI-prvo razvoj ✅  
- [ ] **Poglavlje 3**: Konfiguracija i autentikacija ✅
- [ ] **Poglavlje 4**: Infrastruktura kao kod & implementacija ✅
- [ ] **Poglavlje 5**: Više-agentna AI rješenja ✅
- [ ] **Poglavlje 6**: Provjera i planiranje prije implementacije ✅
- [ ] **Poglavlje 7**: Rješavanje problema i otklanjanje pogrešaka ✅
- [ ] **Poglavlje 8**: Produkcijski i enterprise obrasci ✅

### Provjera učenja
Nakon završetka svakog poglavlja, potvrdite svoje znanje:
1. **Praktična vježba**: Završite praktičnu implementaciju poglavlja
2. **Provjera znanja**: Pregledajte sekciju FAQ za svoje poglavlje
3. **Diskusija u zajednici**: Podijelite svoje iskustvo u Azure Discordu
4. **Dalje poglavlje**: Pređite na sljedeću razinu složenosti

### Prednosti završetka tečaja
Po završetku svih poglavlja imat ćete:
- **Iskustvo iz proizvodnje**: Implementirali stvarne AI aplikacije na Azure
- **Profesionalne vještine**: Sposobnost za enterprise implementacije  
- **Priznanje u zajednici**: Aktivni član Azure developer zajednice
- **Napredak u karijeri**: Tražene AZD i AI implementacijske vještine

---

## 🤝 Zajednica i podrška

### Dobivanje pomoći i podrške
- **Tehnički problemi**: [Prijavi greške i zatraži značajke](https://github.com/microsoft/azd-for-beginners/issues)
- **Pitanja o učenju**: [Microsoft Azure Discord zajednica](https://discord.gg/microsoft-azure) i [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **Pomoć specifična za AI**: Pridruži se [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **Dokumentacija**: [Službena dokumentacija Azure Developer CLI-ja](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)

### Utisci zajednice iz Microsoft Foundry Discorda

**Nedavni rezultati ankete s kanala #Azure:**
- **45%** developera želi koristiti AZD za AI radne procese
- **Glavni izazovi**: implementacije više servisa, upravljanje vjerodajnicama, spremnost za produkciju  
- **Najtraženije**: AI-specifični predlošci, vodiči za rješavanje problema, najbolje prakse

**Pridružite se zajednici i:**
- Dijelite svoja AZD + AI iskustva i dobijte pomoć
- Pristupite ranim pregledima novih AI predložaka
- Doprinesite najboljim praksama implementacije AI
- Utječite na budući razvoj AI + AZD značajki

### Doprinose tečaju
Dobrodošle su vaše doprinose! Molimo pročitajte naš [Vodič za doprinos](CONTRIBUTING.md) za detalje o:
- **Poboljšanjima sadržaja**: Unaprijedite postojeća poglavlja i primjere
- **Novim primjerima**: Dodajte stvarne primjere i predloške  
- **Prijevodu**: Pomozite održati podršku za više jezika
- **Prijavi grešaka**: Poboljšajte točnost i jasnoću
- **Standardi zajednice**: Slijedite smjernice uključive zajednice

---

## 📄 Informacije o tečaju

### Licenca
Ovaj projekt je licenciran pod MIT licencom - pogledajte datoteku [LICENSE](../../LICENSE) za detalje.

### Povezani Microsoft Learning resursi

Naš tim producira i druge sveobuhvatne kurseve za učenje:

<!-- CO-OP TRANSLATOR OTHER COURSES START -->
### LangChain
[![LangChain4j za početnike](https://img.shields.io/badge/LangChain4j%20for%20Beginners-22C55E?style=for-the-badge&&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchain4j-for-beginners)
[![LangChain.js za početnike](https://img.shields.io/badge/LangChain.js%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchainjs-for-beginners?WT.mc_id=m365-94501-dwahlin)

---

### Azure / Edge / MCP / AgentI
[![AZD za početnike](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Edge AI za početnike](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![MCP za početnike](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)
[![AI agenti za početnike](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Serija generativne AI
[![Generative AI za početnike](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Generative AI (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
[![Generative AI (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)
[![Generative AI (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---
 
### Osnovno učenje
[![ML za početnike](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![Data Science for Beginners](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![AI for Beginners](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Cybersecurity for Beginners](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Web Dev for Beginners](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![IoT for Beginners](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![XR Development for Beginners](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Copilot serija
[![Copilot for AI Paired Programming](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![Copilot for C#/.NET](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Copilot Adventure](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ Navigacija tečajem

**🚀 Spremni za početak učenja?**

**Početnici**: Počnite s [Poglavlje 1: Osnove i brzo pokretanje](../..)  
**AI razvojni programeri**: Preskočite na [Poglavlje 2: AI-prvo razvijanje](../..)  
**Iskusni programeri**: Počnite s [Poglavlje 3: Konfiguracija i autentikacija](../..)

**Sljedeći koraci**: [Započni Poglavlje 1 - Osnove AZD](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Odricanje od odgovornosti**:  
Ovaj je dokument preveden pomoću AI usluge za prijevod [Co-op Translator](https://github.com/Azure/co-op-translator). Iako se trudimo biti točni, imajte na umu da automatski prijevodi mogu sadržavati pogreške ili netočnosti. Izvorni dokument na izvornom jeziku treba smatrati autoritativnim izvorom. Za važne informacije preporučuje se profesionalni ljudski prijevod. Nismo odgovorni za bilo kakve nesporazume ili pogrešna tumačenja nastala korištenjem ovog prijevoda.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->