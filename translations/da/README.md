<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T13:44:45+00:00",
  "source_file": "README.md",
  "language_code": "da"
}
-->
> Note: Denne dokumentation opdateres løbende for at afspejle de nyeste ændringer.

> ⚠️ Dette repository er en demo oprettet for at vise
> automatiseret dokumentationslokalisering ved hjælp af Localizeflow.
>
> Det oprindelige indhold er baseret på
> Microsofts projekt "AZD for Beginners".


# AZD for Begyndere: En Struktureret Læringsrejse

![AZD-for-beginners](../../translated_images/azdbeginners.5527441dd9f74068.da.png) 

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## Kom i gang med dette kursus

Følg disse trin for at begynde din AZD-læringsrejse:

1. **Fork repositoryet**: Klik [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)
2. **Clone repositoryet**: `git clone https://github.com/microsoft/azd-for-beginners.git`
3. **Deltag i fællesskabet**: [Azure Discord Communities](https://discord.com/invite/ByRwuEEgH4) for ekspertstøtte
4. **Vælg din læringssti**: Vælg et kapitel nedenfor, der matcher dit erfaringsniveau

### Understøttelse af flere sprog

#### Automatiserede oversættelser (altid opdaterede)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabisk](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarsk](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Kinesisk (Forenklet)](../zh/README.md) | [Kinesisk (Traditionelt, Hong Kong)](../hk/README.md) | [Kinesisk (Traditionelt, Macau)](../mo/README.md) | [Kinesisk (Traditionelt, Taiwan)](../tw/README.md) | [Kroatisk](../hr/README.md) | [Tjekkisk](../cs/README.md) | [Dansk](./README.md) | [Hollandsk](../nl/README.md) | [Estisk](../et/README.md) | [Finsk](../fi/README.md) | [Fransk](../fr/README.md) | [Tysk](../de/README.md) | [Græsk](../el/README.md) | [Hebraisk](../he/README.md) | [Hindi](../hi/README.md) | [Ungarsk](../hu/README.md) | [Indonesisk](../id/README.md) | [Italiensk](../it/README.md) | [Japansk](../ja/README.md) | [Kannada](../kn/README.md) | [Koreansk](../ko/README.md) | [Litauisk](../lt/README.md) | [Malayisk](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepalesisk](../ne/README.md) | [Nigeriansk Pidgin](../pcm/README.md) | [Norsk](../no/README.md) | [Persisk (Farsi)](../fa/README.md) | [Polsk](../pl/README.md) | [Portugisisk (Brasilien)](../br/README.md) | [Portugisisk (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Rumænsk](../ro/README.md) | [Russisk](../ru/README.md) | [Serbisk (Kyrillisk)](../sr/README.md) | [Slovakisk](../sk/README.md) | [Slovensk](../sl/README.md) | [Spansk](../es/README.md) | [Swahili](../sw/README.md) | [Svensk](../sv/README.md) | [Tagalog (Filippinsk)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Tyrkisk](../tr/README.md) | [Ukrainsk](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamesisk](../vi/README.md)

> **Foretrækker du at clone lokalt?**

> Dette repository indeholder over 50 sprogoversættelser, hvilket betydeligt øger downloadstørrelsen. For at clone uden oversættelser, brug sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Dette giver dig alt, hvad du behøver for at gennemføre kurset med en meget hurtigere download.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## Kursusoversigt

Bliv mester i Azure Developer CLI (azd) gennem strukturerede kapitler designet til progressiv læring. **Særligt fokus på AI-applikationsudrulning med Microsoft Foundry-integration.**

### Hvorfor dette kursus er essentielt for moderne udviklere

Baseret på Microsoft Foundry Discord-fællesskabets indsigt ønsker **45% af udviklerne at bruge AZD til AI-arbejdsbelastninger** men støder på udfordringer med:
- Komplekse AI-arkitekturer med flere services
- Bedste praksis for produktionsudrulning af AI  
- Integration og konfiguration af Azure AI-tjenester
- Omkostningsoptimering for AI-arbejdsbelastninger
- Fejlfinding af AI-specifikke udrulningsproblemer

### Læringsmål

Ved at fuldføre dette strukturerede kursus vil du:
- **Mestre AZD Grundlæggende**: Kernebegreber, installation og konfiguration
- **Udrulle AI-applikationer**: Brug AZD med Microsoft Foundry-tjenester
- **Implementere Infrastructure as Code**: Administrer Azure-ressourcer med Bicep-skabeloner
- **Fejlfinding af Udrulninger**: Løs almindelige problemer og fejlret
- **Optimere til Produktion**: Sikkerhed, skalering, overvågning og omkostningsstyring
- **Bygge Multi-Agent-løsninger**: Udrul komplekse AI-arkitekturer

## 📚 Læringskapitler

*Vælg din læringssti baseret på erfaring og mål*

### 🚀 Kapitel 1: Grundlag & Hurtig start  
**Forudsætninger**: Azure-abonnement, grundlæggende kommandolinjekendskab  
**Varighed**: 30-45 minutter  
**Kompleksitet**: ⭐

#### Hvad du lærer
- Forståelse af Azure Developer CLI grundlæggende
- Installation af AZD på din platform
- Din første succesfulde udrulning

#### Læringsressourcer
- **🎯 Start her**: [Hvad er Azure Developer CLI?](../..)
- **📖 Teori**: [AZD Basics](docs/getting-started/azd-basics.md) - Kernebegreber og terminologi
- **⚙️ Opsætning**: [Installation & opsætning](docs/getting-started/installation.md) - Platformsspecifikke guides
- **🛠️ Praktisk**: [Dit første projekt](docs/getting-started/first-project.md) - Trin-for-trin vejledning
- **📋 Hurtig reference**: [Kommando oversigt](resources/cheat-sheet.md)

#### Praktiske øvelser
```bash
# Hurtig installationskontrol
azd version

# Udrul din første applikation
azd init --template todo-nodejs-mongo
azd up
```

**💡 Kapitelresultat**: Udrul en simpel webapplikation til Azure ved brug af AZD med success

**✅ Validering af succes:**  
```bash
# Efter at have gennemført Kapitel 1, bør du kunne:
azd version              # Viser installeret version
azd init --template todo-nodejs-mongo  # Initialiserer projekt
azd up                  # Udruller til Azure
azd show                # Viser kørende app URL
# Applikationen åbner i browseren og virker
azd down --force --purge  # Rydder op i ressourcer
```

**📊 Tidsforbrug:** 30-45 minutter  
**📈 Færdighedsniveau efter:** Kan udrulle basisapplikationer selvstændigt

**✅ Validering af succes:**  
```bash
# Efter at have gennemført Kapitel 1 bør du kunne:
azd version              # Viser installeret version
azd init --template todo-nodejs-mongo  # Initialiserer projekt
azd up                  # Udruller til Azure
azd show                # Viser kørende app URL
# Applikationen åbner i browseren og fungerer
azd down --force --purge  # Rydder op i ressourcer
```

**📊 Tidsforbrug:** 30-45 minutter  
**📈 Færdighedsniveau efter:** Kan udrulle basisapplikationer selvstændigt

---

### 🤖 Kapitel 2: AI-First udvikling (Anbefalet til AI-udviklere)  
**Forudsætninger**: Kapitel 1 gennemført  
**Varighed**: 1-2 timer  
**Kompleksitet**: ⭐⭐

#### Hvad du lærer
- Microsoft Foundry integration med AZD
- Udrulning af AI-drevne applikationer
- Forståelse af AI-tjenestekonfigurationer

#### Læringsressourcer
- **🎯 Start her**: [Microsoft Foundry Integration](docs/microsoft-foundry/microsoft-foundry-integration.md)
- **📖 Mønstre**: [AI Model Deployment](docs/microsoft-foundry/ai-model-deployment.md) - Udrul og administrer AI-modeller
- **🛠️ Workshop**: [AI Workshop Lab](docs/microsoft-foundry/ai-workshop-lab.md) - Gør dine AI-løsninger AZD-klare
- **🎥 Interaktiv guide**: [Workshop-materialer](workshop/README.md) - Browserbaseret læring med MkDocs * DevContainer-miljø
- **📋 Skabeloner**: [Microsoft Foundry skabeloner](../..)
- **📝 Eksempler**: [AZD udrulningseksempler](examples/README.md)

#### Praktiske øvelser
```bash
# Udrul din første AI-applikation
azd init --template azure-search-openai-demo
azd up

# Prøv yderligere AI-skabeloner
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```

**💡 Kapitelresultat**: Udrul og konfigurer en AI-drevet chatapplikation med RAG-funktioner

**✅ Validering af succes:**  
```bash
# Efter Kapitel 2 bør du kunne:
azd init --template azure-search-openai-demo
azd up
# Teste AI-chatgrænsefladen
# Stille spørgsmål og få AI-drevne svar med kilder
# Bekræfte at søgeintegration fungerer
azd monitor  # Kontrollere at Application Insights viser telemetri
azd down --force --purge
```

**📊 Tidsforbrug:** 1-2 timer  
**📈 Færdighedsniveau efter:** Kan udrulle og konfigurere produktionsklare AI-applikationer  
**💰 Omkostningsbevidsthed:** Forstå udviklingsomkostninger på $80-150/måned, produktionsomkostninger $300-3500/måned

#### 💰 Omkostningsovervejelser for AI-udrulninger

**Udviklingsmiljø (estimeret $80-150/måned):**
- Azure OpenAI (Betal efter forbrug): $0-50/måned (baseret på tokenforbrug)
- AI Search (Basisniveau): $75/måned
- Container Apps (Forbrug): $0-20/måned
- Storage (Standard): $1-5/måned

**Produktionsmiljø (estimeret $300-3.500+/måned):**
- Azure OpenAI (PTU for konsistent ydeevne): $3.000+/måned ELLER pay-as-you-go ved højt forbrug
- AI Search (Standardniveau): $250/måned
- Container Apps (Dedikeret): $50-100/måned
- Application Insights: $5-50/måned
- Storage (Premium): $10-50/måned

**💡 Omkostningsoptimeringstips:**
- Brug **Free Tier** Azure OpenAI til læring (50.000 tokens/måned inkluderet)
- Kør `azd down` for at deallokere ressourcer, når du ikke udvikler aktivt
- Start med forbrugsbaseret fakturering, opgrader til PTU kun i produktion
- Brug `azd provision --preview` for at estimere omkostninger før udrulning
- Aktiver autoskalering: betal kun for faktisk forbrug

**Omkostningsovervågning:**
```bash
# Tjek anslåede månedlige omkostninger
azd provision --preview

# Overvåg faktiske omkostninger i Azure Portal
az consumption budget list --resource-group <your-rg>
```

---

### ⚙️ Kapitel 3: Konfiguration & Autentificering  
**Forudsætninger**: Kapitel 1 gennemført  
**Varighed**: 45-60 minutter  
**Kompleksitet**: ⭐⭐

#### Hvad du lærer
- Konfiguration og håndtering af miljøer
- Autentificering og sikkerhedsbest practices
- Navngivning og organisering af ressourcer

#### Læringsressourcer
- **📖 Konfiguration**: [Konfigurationsvejledning](docs/getting-started/configuration.md) - Opsætning af miljø
- **🔐 Sikkerhed**: [Autentificeringsmønstre og managed identity](docs/getting-started/authsecurity.md) - Autentificeringsmønstre
- **📝 Eksempler**: [Database-applikationseksempel](examples/database-app/README.md) - AZD Database-eksempler

#### Praktiske øvelser
- Konfigurer flere miljøer (dev, staging, prod)
- Sæt managed identity-autentificering op
- Implementer miljøspecifikke konfigurationer

**💡 Kapitelresultat**: Håndter flere miljøer med korrekt autentificering og sikkerhed

---

### 🏗️ Kapitel 4: Infrastructure as Code & Udrulning  
**Forudsætninger**: Kapitel 1-3 gennemført  
**Varighed**: 1-1.5 timer  
**Kompleksitet**: ⭐⭐⭐

#### Hvad du lærer
- Avancerede udrulningsmønstre
- Infrastructure as Code med Bicep
- Strategier for ressourcestyring

#### Læringsressourcer
- **📖 Udrulning**: [Udrulningsguide](docs/deployment/deployment-guide.md) - Fulde arbejdsgange
- **🏗️ Ressourceprovisionering**: [Provisionering af ressourcer](docs/deployment/provisioning.md) - Azure ressourcestyring
- **📝 Eksempler**: [Container app-eksempel](../../examples/container-app) - Containerbaserede udrulninger

#### Praktiske øvelser
- Opret brugerdefinerede Bicep-skabeloner
- Udrul multi-service applikationer
- Implementer blue-green udrulningsstrategier

**💡 Kapitelresultat**: Udrul komplekse multi-service applikationer med brugerdefinerede infrastrukturskabeloner

---
### 🎯 Kapitel 5: Multi-Agent AI-løsninger (Avanceret)
**Forudsætninger**: Kapitel 1-2 gennemført  
**Varighed**: 2-3 timer  
**Kompleksitet**: ⭐⭐⭐⭐

#### Hvad du vil lære
- Multi-agent arkitektur mønstre
- Agent orkestrering og koordinering
- Produktionsklare AI-udrulninger

#### Læringsressourcer
- **🤖 Fokuseret projekt**: [Retail Multi-Agent Solution](examples/retail-scenario.md) - Komplett implementering
- **🛠️ ARM Skabeloner**: [ARM Template Package](../../examples/retail-multiagent-arm-template) - Ét-klik udrulning
- **📖 Arkitektur**: [Multi-agent koordinationsmønstre](/docs/pre-deployment/coordination-patterns.md) - Mønstre

#### Praktiske øvelser
```bash
# Implementer den komplette detailmulti-agent-løsning
cd examples/retail-multiagent-arm-template
./deploy.sh

# Udforsk agentkonfigurationer
az deployment group show --resource-group <rg-name> --name <deployment-name>
```

**💡 Kapitel Resultat**: Implementer og administrer en produktionsklar multi-agent AI-løsning med Kunde- og Lager-agenter

---

### 🔍 Kapitel 6: Forudgående validering & planlægning
**Forudsætninger**: Kapitel 4 gennemført  
**Varighed**: 1 time  
**Kompleksitet**: ⭐⭐

#### Hvad du vil lære
- Kapacitetsplanlægning og ressourcer validering
- SKU valgsstrategier
- For-flight checks og automatisering

#### Læringsressourcer
- **📊 Planlægning**: [Kapacitetsplanlægning](docs/pre-deployment/capacity-planning.md) - Ressourcevalidering
- **💰 Udvælgelse**: [SKU Udvælgelse](docs/pre-deployment/sku-selection.md) - Omkostningseffektive valg
- **✅ Validering**: [Pre-flight Checks](docs/pre-deployment/preflight-checks.md) - Automatiserede scripts

#### Praktiske øvelser
- Kør kapacitetsvalideringsscripts
- Optimer SKU valg for omkostninger
- Implementer automatiserede pre-udrulningskontroller

**💡 Kapitel Resultat**: Valider og optimer udrulninger før eksekvering

---

### 🚨 Kapitel 7: Fejlfinding & Debugging
**Forudsætninger**: Ethvert udrulningskapitel gennemført  
**Varighed**: 1-1.5 timer  
**Kompleksitet**: ⭐⭐

#### Hvad du vil lære
- Systematiske debugging metoder
- Almindelige problemer og løsninger
- AI-specifik fejlfinding

#### Læringsressourcer
- **🔧 Almindelige problemer**: [Almindelige problemer](docs/troubleshooting/common-issues.md) - FAQ og løsninger
- **🕵️ Debugging**: [Debugging Guide](docs/troubleshooting/debugging.md) - Trin-for-trin strategier
- **🤖 AI-problemer**: [AI-specifik fejlfinding](docs/troubleshooting/ai-troubleshooting.md) - AI service problemer

#### Praktiske øvelser
- Diagnosticer udrulningsfejl
- Løs autentifikationsproblemer
- Debug AI service forbindelser

**💡 Kapitel Resultat**: Diagnostiser og løs almindelige udrulningsproblemer selvstændigt

---

### 🏢 Kapitel 8: Produktions- & Enterprise-mønstre
**Forudsætninger**: Kapitel 1-4 gennemført  
**Varighed**: 2-3 timer  
**Kompleksitet**: ⭐⭐⭐⭐

#### Hvad du vil lære
- Produktionsudrulningsstrategier
- Enterprise sikkerhedsmønstre
- Overvågning og omkostningsoptimering

#### Læringsressourcer
- **🏭 Produktion**: [Produktions AI Best Practices](docs/microsoft-foundry/production-ai-practices.md) - Enterprise mønstre
- **📝 Eksempler**: [Microservices Eksempel](../../examples/microservices) - Kompleks arkitektur
- **📊 Overvågning**: [Application Insights integration](docs/pre-deployment/application-insights.md) - Overvågning

#### Praktiske øvelser
- Implementer enterprise sikkerhedsmønstre
- Opsæt omfattende overvågning
- Udrul til produktion med korrekt governance

**💡 Kapitel Resultat**: Udrul enterprise-klar applikationer med fuld produktionskapacitet

---

## 🎓 Workshop Oversigt: Hands-On Læringsoplevelse

> **⚠️ WORKSHOP STATUS: Aktiv Udvikling**  
> Workshop-materialerne udvikles og forbedres løbende. Kernemodulerne fungerer, men nogle avancerede sektioner mangler stadig. Vi arbejder aktivt på at færdiggøre alt indhold. [Følg fremskridt →](workshop/README.md)

### Interaktive Workshop Materialer
**Omfattende hands-on læring med browser-baserede værktøjer og guidede øvelser**

Vores workshop-materialer giver en struktureret, interaktiv læring, som supplerer ovenstående kapitelbaserede pensum. Workshoppen er designet til både selvstyret læring og instruktørledte sessioner.

#### 🛠️ Workshop Funktioner
- **Browser-baseret interface**: Fuldt MkDocs-styret workshop med søgning, kopiering og tema-funktioner
- **GitHub Codespaces Integration**: Ét-klik udviklingsmiljøopsætning
- **Struktureret læringssti**: 7-trins guidede øvelser (3.5 timer samlet)
- **Discovery → Deployment → Customization**: Progressiv metodologi
- **Interaktiv DevContainer-miljø**: Forkonfigurerede værktøjer og dependencies

#### 📚 Workshop Struktur
Workshoppen følger en **Discovery → Deployment → Customization** metodologi:

1. **Discovery-fase** (45 min)
   - Udforsk Microsoft Foundry skabeloner og services
   - Forstå multi-agent arkitektur mønstre
   - Gennemgå udrulningskrav og forudsætninger

2. **Deployment-fase** (2 timer)
   - Hands-on udrulning af AI applikationer med AZD
   - Konfigurér Azure AI services og endpoints
   - Implementer sikkerheds- og autentifikationsmønstre

3. **Customization-fase** (45 min)
   - Tilpas applikationer til specifikke brugsscenarier
   - Optimer til produktionsudrulning
   - Implementer overvågning og omkostningsstyring

#### 🚀 Kom i gang med workshoppen
```bash
# Mulighed 1: GitHub Codespaces (Anbefalet)
# Klik "Code" → "Create codespace on main" i lageret

# Mulighed 2: Lokal udvikling
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# Følg opsætningsvejledningen i workshop/README.md
```

#### 🎯 Workshop Læringsmål
Ved afslutning af workshoppen vil deltagerne:
- **Udrulle produktionsklare AI-applikationer**: Brug AZD med Microsoft Foundry services
- **Beherske Multi-Agent Arkitekturer**: Implementere koordinerede AI agent løsninger
- **Implementere Sikkerhedsbest Practices**: Konfigurér autentifikation og adgangskontrol
- **Optimere til Skala**: Designe omkostningseffektive, højtydende udrulninger
- **Fejlsøge Udrulninger**: Selvstændigt løse almindelige problemer

#### 📖 Workshop Ressourcer
- **🎥 Interaktiv Guide**: [Workshop Materialer](workshop/README.md) - Browser-baseret læringsmiljø
- **📋 Trin-for-trin Instruktioner**: [Guidede Øvelser](../../workshop/docs/instructions) - Detaljerede gennemgange
- **🛠️ AI Workshop Lab**: [AI Workshop Lab](docs/microsoft-foundry/ai-workshop-lab.md) - AI-fokuserede øvelser
- **💡 Hurtig Start**: [Workshop Opsætningsguide](workshop/README.md#quick-start) - Miljøkonfiguration

**Perfekt til**: Virksomhedstræning, universitetskurser, selvstudier og udviklerbootcamps.

---

## 📖 Hvad er Azure Developer CLI?

Azure Developer CLI (azd) er en udviklercentreret kommandolinjegrænseflade, der fremskynder processen med at bygge og udrulle applikationer til Azure. Den tilbyder:

- **Skabelon-baserede udrulninger** - Brug færdigbyggede skabeloner til almindelige applikationsmønstre
- **Infrastructure as Code** - Administrer Azure-ressourcer med Bicep eller Terraform  
- **Integrerede arbejdsgange** - Problemfri provisioning, udrulning og overvågning af applikationer
- **Udviklervenlig** - Optimeret til udviklerproduktivitet og oplevelse

### **AZD + Microsoft Foundry: Perfekt til AI-udrulninger**

**Hvorfor AZD til AI-løsninger?** AZD håndterer de største udfordringer AI-udviklere møder:

- **AI-Klare Skabeloner** - For-konfigurerede skabeloner til Azure OpenAI, Cognitive Services og ML workloads
- **Sikre AI Udrulninger** - Indbyggede sikkerhedsmønstre for AI-tjenester, API-nøgler og model endpoints  
- **Produktionsklare AI Mønstre** - Bedste praksis for skalerbare, omkostningseffektive AI applikationsudrulninger
- **End-to-End AI Arbejdsgange** - Fra modeludvikling til produktionsudrulning med korrekt overvågning
- **Omkostningsoptimering** - Smarte ressourcetildeling og skaleringsstrategier for AI workloads
- **Microsoft Foundry Integration** - Problemfri forbindelse til Microsoft Foundry modelkatalog og endpoints

---

## 🎯 Skabeloner & Eksempelsamling

### Fremhævet: Microsoft Foundry Skabeloner
**Start her, hvis du udruller AI-applikationer!**

> **Bemærk:** Disse skabeloner demonstrerer forskellige AI-mønstre. Nogle er eksterne Azure Samples, andre er lokale implementeringer.

| Skabelon | Kapitel | Kompleksitet | Services | Type |
|----------|---------|--------------|----------|------|
| [**Get started with AI chat**](https://github.com/Azure-Samples/get-started-with-ai-chat) | Kapitel 2 | ⭐⭐ | AzureOpenAI + Azure AI Model Inference API + Azure AI Search + Azure Container Apps + Application Insights | Ekstern |
| [**Get started with AI agents**](https://github.com/Azure-Samples/get-started-with-ai-agents) | Kapitel 2 | ⭐⭐ | Azure AI Agent Service + AzureOpenAI + Azure AI Search + Azure Container Apps + Application Insights| Ekstern |
| [**Azure Search + OpenAI Demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Kapitel 2 | ⭐⭐ | AzureOpenAI + Azure AI Search + App Service + Storage | Ekstern |
| [**OpenAI Chat App Quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Kapitel 2 | ⭐ | AzureOpenAI + Container Apps + Application Insights | Ekstern |
| [**Agent OpenAI Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Kapitel 5 | ⭐⭐⭐ | AzureOpenAI + Azure Functions + Prompty | Ekstern |
| [**Contoso Chat RAG**](https://github.com/Azure-Samples/contoso-chat) | Kapitel 8 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Cosmos DB + Container Apps | Ekstern |
| [**Retail Multi-Agent Solution**](examples/retail-scenario.md) | Kapitel 5 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Storage + Container Apps + Cosmos DB | **Lokal** |

### Fremhævet: Komplette læringsscenarier
**Produktionsklare applikationsskabeloner knyttet til læringskapitler**

| Skabelon | Læringskapitel | Kompleksitet | Nøglelæring |
|----------|----------------|--------------|-------------|
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Kapitel 2 | ⭐ | Grundlæggende AI-udrulningsmønstre |
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Kapitel 2 | ⭐⭐ | RAG-implementering med Azure AI Search |
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | Kapitel 4 | ⭐⭐ | Document Intelligence integration |
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Kapitel 5 | ⭐⭐⭐ | Agentframework og funktionskald |
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | Kapitel 8 | ⭐⭐⭐ | Enterprise AI orkestrering |
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | Kapitel 5 | ⭐⭐⭐⭐ | Multi-agent arkitektur med Kunde- og Lager-agenter |

### Læring efter eksempeltype

> **📌 Lokale vs. Eksterne Eksempler:**  
> **Lokale Eksempler** (i dette repo) = Klar til brug med det samme  
> **Eksterne Eksempler** (Azure Samples) = Klon fra linkede repositories

#### Lokale Eksempler (Klar til brug)
- [**Retail Multi-Agent Solution**](examples/retail-scenario.md) - Komplett produktionsklar implementering med ARM skabeloner
  - Multi-agent arkitektur (Kunde + Lager agenter)
  - Omfattende overvågning og evaluering
  - Ét-klik udrulning via ARM skabelon

#### Lokale Eksempler - Container Applikationer (Kapitel 2-5)
**Omfattende containerudrulnings-eksempler i dette repository:**
- [**Container App Examples**](examples/container-app/README.md) - Komplett guide til containerbaserede udrulninger
  - [Simple Flask API](../../examples/container-app/simple-flask-api) - Basis REST API med scale-to-zero
  - [Microservices Arkitektur](../../examples/container-app/microservices) - Produktionsklar multi-service udrulning
  - Hurtig start, produktion og avancerede udrulningsmønstre
  - Overvågning, sikkerhed og omkostningsoptimering vejledning

#### Eksterne Eksempler - Simple Applikationer (Kapitel 1-2)
**Klon disse Azure Samples repositories for at komme i gang:**
- [Simple Web App - Node.js + MongoDB](https://github.com/Azure-Samples/todo-nodejs-mongo) - Grundlæggende udrulningsmønstre
- [Static Website - React SPA](https://github.com/Azure-Samples/todo-csharp-sql-swa-func) - Statisk indholdsudrulning
- [Container App - Python Flask](https://github.com/Azure-Samples/container-apps-store-api-microservice) - REST API udrulning

#### Eksterne Eksempler - Databaseintegration (Kapitel 3-4)  
- [Database App - C# + SQL](https://github.com/Azure-Samples/todo-csharp-sql) - Databaseforbindelsesmønstre
- [Functions + Cosmos DB](https://github.com/Azure-Samples/todo-python-mongo-swa-func) - Serverløs dataprocesstyring

#### Eksterne Eksempler - Avancerede Mønstre (Kapitel 4-8)
- [Java Microservices](https://github.com/Azure-Samples/java-microservices-aca-lab) - Multi-service arkitekturer
- [Container Apps Jobs](https://github.com/Azure-Samples/container-apps-jobs) - Baggrundsbehandling  
- [Enterprise ML Pipeline](https://github.com/Azure-Samples/mlops-v2) - Produktionsklare ML-mønstre

### Eksterne Skabelonsamlinger
- [**Officiel AZD Skabelongalleri**](https://azure.github.io/awesome-azd/) - Kurateret samling af officielle og community-skabeloner  
- [**Azure Developer CLI Skabeloner**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - Microsoft Learn skabelondokumentation  
- [**Eksempelmappen**](examples/README.md) - Lokale læringseksempler med detaljerede forklaringer

---

## 📚 Læringsressourcer & Referencer

### Hurtige Referencer
- [**Kommando-oversigt**](resources/cheat-sheet.md) - Væsentlige azd-kommandoer organiseret efter kapitel  
- [**Ordliste**](resources/glossary.md) - Azure og azd terminologi  
- [**FAQ**](resources/faq.md) - Almindelige spørgsmål organiseret efter læringskapitel  
- [**Studieguide**](resources/study-guide.md) - Omfattende øvelser til praksis

### Praktiske Workshops
- [**AI Workshop Lab**](docs/microsoft-foundry/ai-workshop-lab.md) - Gør dine AI-løsninger deployerbare med AZD (2-3 timer)  
- [**Interaktiv Workshopguide**](workshop/README.md) - Browserbaseret workshop med MkDocs og DevContainer-miljø  
- [**Struktureret Læringssti**](../../workshop/docs/instructions) - 7-trins guidede øvelser (Opdagelse → Deployment → Tilpasning)  
- [**AZD For Begyndere Workshop**](workshop/README.md) - Fuldstændige hands-on workshopmaterialer med GitHub Codespaces-integration

### Eksterne Læringsressourcer
- [Azure Developer CLI Dokumentation](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)  
- [Azure Arkitekturcenter](https://learn.microsoft.com/en-us/azure/architecture/)  
- [Azure Prisberegner](https://azure.microsoft.com/pricing/calculator/)  
- [Azure Status](https://status.azure.com/)

---

## 🔧 Hurtig Fejlfinding Guide

**Almindelige problemer som begyndere støder på og hurtige løsninger:**

### ❌ "azd: kommando ikke fundet"

```bash
# Installer AZD først
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Bekræft installation
azd version
```
  
### ❌ "Ingen abonnement fundet" eller "Abonnement ikke sat"

```bash
# Liste tilgængelige abonnementer
az account list --output table

# Indstil standardabonnement
az account set --subscription "<subscription-id-or-name>"

# Indstil til AZD-miljø
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Bekræft
az account show
```
  
### ❌ "Utilstrækkelig Kvote" eller "Kvote overskredet"

```bash
# Prøv en anden Azure-region
azd env set AZURE_LOCATION "westus2"
azd up

# Eller brug mindre SKU'er i udvikling
# Rediger infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
  
### ❌ "azd up" fejler midt i processen

```bash
# Mulighed 1: Rens og prøv igen
azd down --force --purge
azd up

# Mulighed 2: Fiks kun infrastrukturen
azd provision

# Mulighed 3: Tjek detaljerede logfiler
azd show
azd logs
```
  
### ❌ "Godkendelse fejlede" eller "Token udløbet"

```bash
# Genautentificer
az logout
az login

azd auth logout
azd auth login

# Bekræft godkendelse
az account show
```
  
### ❌ "Ressource findes allerede" eller navnekonflikter

```bash
# AZD genererer unikke navne, men hvis der opstår konflikt:
azd down --force --purge

# Så prøv igen med et nyt miljø
azd env new dev-v2
azd up
```
  
### ❌ Skabelonudrulning tager for lang tid

**Normale ventetider:**  
- Simpel webapp: 5-10 minutter  
- App med database: 10-15 minutter  
- AI-applikationer: 15-25 minutter (OpenAI-provisionering er langsom)

```bash
# Tjek fremskridt
azd show

# Hvis fastlåst >30 minutter, tjek Azure Portal:
azd monitor
# Kig efter mislykkede implementeringer
```
  
### ❌ "Adgang nægtet" eller "Forbudt"

```bash
# Tjek din Azure-rolle
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Du skal have mindst "Bidragyder" rolle
# Bed din Azure-administrator om at give:
# - Bidragyder (for ressourcer)
# - Brugeradgangsadministrator (for rollefordelinger)
```
  
### ❌ Kan ikke finde URL til deployeret applikation

```bash
# Vis alle tjenesteendepunkter
azd show

# Eller åbn Azure Portal
azd monitor

# Tjek specifik tjeneste
azd env get-values
# Kig efter *_URL variabler
```
  
### 📚 Fuldstændige fejlfinding ressourcer

- **Guide til almindelige problemer:** [Detaljerede løsninger](docs/troubleshooting/common-issues.md)  
- **AI-specifikke problemer:** [AI fejlfinding](docs/troubleshooting/ai-troubleshooting.md)  
- **Fejlfindingsguide:** [Trin-for-trin fejlfinding](docs/troubleshooting/debugging.md)  
- **Få hjælp:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🔧 Hurtig Fejlfinding Guide

**Almindelige problemer som begyndere støder på og hurtige løsninger:**

<details>  
<summary><strong>❌ "azd: kommando ikke fundet"</strong></summary>

```bash
# Installer AZD først
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Bekræft installation
azd version
```
</details>

<details>  
<summary><strong>❌ "Ingen abonnement fundet" eller "Abonnement ikke sat"</strong></summary>

```bash
# Liste over tilgængelige abonnementer
az account list --output table

# Angiv standardabonnement
az account set --subscription "<subscription-id-or-name>"

# Indstil for AZD-miljø
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Bekræft
az account show
```
</details>

<details>  
<summary><strong>❌ "Utilstrækkelig Kvote" eller "Kvote overskredet"</strong></summary>

```bash
# Prøv en anden Azure-region
azd env set AZURE_LOCATION "westus2"
azd up

# Eller brug mindre SKU'er i udvikling
# Rediger infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>

<details>  
<summary><strong>❌ "azd up" fejler midt i processen</strong></summary>

```bash
# Mulighed 1: Ryd op og prøv igen
azd down --force --purge
azd up

# Mulighed 2: Ret bare infrastrukturen
azd provision

# Mulighed 3: Tjek detaljerede logfiler
azd show
azd logs
```
</details>

<details>  
<summary><strong>❌ "Godkendelse fejlede" eller "Token udløbet"</strong></summary>

```bash
# Genautentificer
az logout
az login

azd auth logout
azd auth login

# Bekræft autentificering
az account show
```
</details>

<details>  
<summary><strong>❌ "Ressource findes allerede" eller navnekonflikter</strong></summary>

```bash
# AZD genererer unikke navne, men hvis konflikt:
azd down --force --purge

# Så prøv igen med et nyt miljø
azd env new dev-v2
azd up
```
</details>

<details>  
<summary><strong>❌ Skabelonudrulning tager for lang tid</strong></summary>

**Normale ventetider:**  
- Simpel webapp: 5-10 minutter  
- App med database: 10-15 minutter  
- AI-applikationer: 15-25 minutter (OpenAI-provisionering er langsom)

```bash
# Tjek fremskridt
azd show

# Hvis fastlåst i >30 minutter, tjek Azure Portal:
azd monitor
# Se efter mislykkede implementeringer
```
</details>

<details>  
<summary><strong>❌ "Adgang nægtet" eller "Forbudt"</strong></summary>

```bash
# Tjek din Azure-rolle
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Du skal have mindst rollen "Contributor"
# Bed din Azure-administrator om at give:
# - Contributor (for ressourcer)
# - User Access Administrator (for rollefordelinger)
```
</details>

<details>  
<summary><strong>❌ Kan ikke finde URL til deployeret applikation</strong></summary>

```bash
# Vis alle serviceendepunkter
azd show

# Eller åbn Azure Portal
azd monitor

# Tjek specifik service
azd env get-values
# Kig efter *_URL variabler
```
</details>

### 📚 Fuldstændige fejlfinding ressourcer

- **Guide til almindelige problemer:** [Detaljerede løsninger](docs/troubleshooting/common-issues.md)  
- **AI-specifikke problemer:** [AI fejlfinding](docs/troubleshooting/ai-troubleshooting.md)  
- **Fejlfindingsguide:** [Trin-for-trin fejlfinding](docs/troubleshooting/debugging.md)  
- **Få hjælp:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🎓 Kursusafslutning & Certificering

### Fremgangssporing  
Hold styr på din læringsfremgang gennem hvert kapitel:

- [ ] **Kapitel 1**: Grundlag & Hurtig Start ✅  
- [ ] **Kapitel 2**: AI-Først Udvikling ✅  
- [ ] **Kapitel 3**: Konfiguration & Godkendelse ✅  
- [ ] **Kapitel 4**: Infrastruktur som kode & Udrulning ✅  
- [ ] **Kapitel 5**: Multi-Agent AI-løsninger ✅  
- [ ] **Kapitel 6**: Validering & Planlægning før udrulning ✅  
- [ ] **Kapitel 7**: Fejlfinding & Debugging ✅  
- [ ] **Kapitel 8**: Produktion & Enterprise-mønstre ✅

### Læringsverifikation  
Efter hvert kapitel bekræft din viden ved:  
1. **Praktisk Øvelse**: Gennemfør kapitlets hands-on deployment  
2. **Videnstjek**: Gennemgå FAQ-sektionen for dit kapitel  
3. **Community Diskussion**: Del dine erfaringer i Azure Discord  
4. **Næste Kapitel**: Gå til næste kompleksitetsniveau

### Fordele ved kursusafslutning  
Når du har gennemført alle kapitler, vil du have:  
- **Produktionserfaring**: Deployeret ægte AI-applikationer til Azure  
- **Professionelle færdigheder**: Enterprise-klar deployeringsevne  
- **Community Anerkendelse**: Aktiv medlem af Azure udviklerfællesskabet  
- **Karrierefremskridt**: Eftertragtet AZD og AI deployment ekspertise

---

## 🤝 Community & Support

### Få Hjælp & Support  
- **Tekniske problemer**: [Rapporter bugs og foreslå funktioner](https://github.com/microsoft/azd-for-beginners/issues)  
- **Læringsspørgsmål**: [Microsoft Azure Discord Community](https://discord.gg/microsoft-azure) og [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)  
- **AI-specifik hjælp**: Deltag i [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)  
- **Dokumentation**: [Officiel Azure Developer CLI dokumentation](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)

### Community Indsigter fra Microsoft Foundry Discord

**Seneste afstemningsresultater fra #Azure-kanalen:**  
- **45%** af udviklerne ønsker at bruge AZD til AI-arbejdsmængder  
- **Topudfordringer**: Multi-service udrulninger, credential management, produktionsklarhed  
- **Mest efterspurgte**: AI-specifikke skabeloner, fejlfinding guider, bedste praksis

**Bliv en del af vores community for at:**  
- Dele dine AZD + AI erfaringer og få hjælp  
- Få tidlige previews af nye AI-skabeloner  
- Bidrage til bedste praksis for AI-deployering  
- Påvirke fremtidige AI + AZD funktionsudviklinger

### Bidrag til Kurset  
Vi byder bidrag velkommen! Læs venligst vores [Bidragsguide](CONTRIBUTING.md) for detaljer om:  
- **Forbedringer af indhold**: Forbedr eksisterende kapitler og eksempler  
- **Nye eksempler**: Tilføj virkelighedsnære scenarier og skabeloner  
- **Oversættelse**: Hjælp med at vedligeholde flersproget support  
- **Bugrapporter**: Forbedr nøjagtighed og klarhed  
- **Community-standarder**: Følg vores inkluderende community-retningslinjer

---

## 📄 Kursus Information

### Licens  
Dette projekt er licenseret under MIT-licensen - se [LICENSE](../../LICENSE) filen for detaljer.

### Relaterede Microsoft Læringsressourcer

Vores team producerer andre omfattende læringskurser:

<!-- CO-OP TRANSLATOR OTHER COURSES START -->
### LangChain  
[![LangChain4j for Beginners](https://img.shields.io/badge/LangChain4j%20for%20Beginners-22C55E?style=for-the-badge&&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchain4j-for-beginners)  
[![LangChain.js for Beginners](https://img.shields.io/badge/LangChain.js%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchainjs-for-beginners?WT.mc_id=m365-94501-dwahlin)

---

### Azure / Edge / MCP / Agenter  
[![AZD for Beginners](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)  
[![Edge AI for Beginners](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)  
[![MCP for Beginners](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)  
[![AI Agents for Beginners](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)

---

### Generativ AI Serie  
[![Generative AI for Beginners](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)  
[![Generative AI (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)  
[![Generative AI (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)  
[![Generative AI (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---

### Kerne Læring  
[![ML for Beginners](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![Data Science for Beginners](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![AI for Beginners](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Cybersecurity for Beginners](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Web Dev for Beginners](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![IoT for Beginners](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![XR Development for Beginners](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Copilot Serien
[![Copilot for AI Paired Programming](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![Copilot for C#/.NET](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Copilot Adventure](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ Kursusnavigation

**🚀 Klar til at begynde at lære?**

**Begyndere**: Start med [Kapitel 1: Grundlag & Hurtig Start](../..)  
**AI-udviklere**: Gå til [Kapitel 2: AI-Første Udvikling](../..)  
**Erfarne Udviklere**: Begynd med [Kapitel 3: Konfiguration & Godkendelse](../..)

**Næste skridt**: [Begynd Kapitel 1 - AZD Grundlæggende](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Ansvarsfraskrivelse**:
Dette dokument er blevet oversat ved hjælp af AI-oversættelsestjenesten [Co-op Translator](https://github.com/Azure/co-op-translator). Selvom vi bestræber os på nøjagtighed, bedes du være opmærksom på, at automatiserede oversættelser kan indeholde fejl eller unøjagtigheder. Det oprindelige dokument på originalsproget bør betragtes som den autoritative kilde. For kritisk information anbefales professionel menneskelig oversættelse. Vi påtager os intet ansvar for misforståelser eller fejltolkninger, der opstår som følge af brugen af denne oversættelse.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->