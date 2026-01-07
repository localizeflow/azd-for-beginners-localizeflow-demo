<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T13:54:42+00:00",
  "source_file": "README.md",
  "language_code": "nl"
}
-->
> Opmerking: Deze documentatie wordt continu bijgewerkt om de laatste veranderingen weer te geven.

> ⚠️ Deze repository is een demo gemaakt om
> geautomatiseerde documentatielokalisatie met Localizeflow te demonstreren.
>
> De originele inhoud is gebaseerd op
> Microsoft’s "AZD voor Beginners" project.


# AZD Voor Beginners: Een Gestructureerde Leertraject

![AZD-voor-beginners](../../translated_images/azdbeginners.5527441dd9f74068.nl.png) 

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## Aan de Slag met Deze Cursus

Volg deze stappen om je AZD leertraject te beginnen:

1. **Fork de Repository**: Klik [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)
2. **Clone de Repository**: `git clone https://github.com/microsoft/azd-for-beginners.git`
3. **Word lid van de Community**: [Azure Discord Communities](https://discord.com/invite/ByRwuEEgH4) voor deskundige ondersteuning
4. **Kies je Leerpad**: Selecteer een hoofdstuk hieronder dat aansluit bij je ervaringsniveau

### Meertalige Ondersteuning

#### Geautomatiseerde Vertalingen (Altijd Up-to-Date)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabisch](../ar/README.md) | [Bengaals](../bn/README.md) | [Bulgaars](../bg/README.md) | [Birmaans (Myanmar)](../my/README.md) | [Chinees (Vereenvoudigd)](../zh/README.md) | [Chinees (Traditioneel, Hongkong)](../hk/README.md) | [Chinees (Traditioneel, Macau)](../mo/README.md) | [Chinees (Traditioneel, Taiwan)](../tw/README.md) | [Kroatisch](../hr/README.md) | [Tsjechisch](../cs/README.md) | [Deens](../da/README.md) | [Nederlands](./README.md) | [Ests](../et/README.md) | [Fins](../fi/README.md) | [Frans](../fr/README.md) | [Duits](../de/README.md) | [Grieks](../el/README.md) | [Hebreeuws](../he/README.md) | [Hindi](../hi/README.md) | [Hongaars](../hu/README.md) | [Indonesisch](../id/README.md) | [Italiaans](../it/README.md) | [Japans](../ja/README.md) | [Kannada](../kn/README.md) | [Koreaans](../ko/README.md) | [Litouws](../lt/README.md) | [Maleis](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepalees](../ne/README.md) | [Nigeriaans Pidgin](../pcm/README.md) | [Noors](../no/README.md) | [Perzisch (Farsi)](../fa/README.md) | [Pools](../pl/README.md) | [Portugees (Brazilië)](../br/README.md) | [Portugees (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Roemeens](../ro/README.md) | [Russisch](../ru/README.md) | [Servisch (Cyrillisch)](../sr/README.md) | [Slowaaks](../sk/README.md) | [Sloveens](../sl/README.md) | [Spaans](../es/README.md) | [Swahili](../sw/README.md) | [Zweeds](../sv/README.md) | [Tagalog (Filipijns)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thais](../th/README.md) | [Turks](../tr/README.md) | [Oekraïens](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamees](../vi/README.md)

> **Lieveling lokaal clonen?**

> Deze repository bevat 50+ taalvertalingen die de downloadgrootte aanzienlijk vergroten. Om te clonen zonder vertalingen, gebruik de sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Dit geeft je alles wat je nodig hebt om de cursus te voltooien met een veel snellere download.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## Cursusoverzicht

Beheers Azure Developer CLI (azd) via gestructureerde hoofdstukken ontworpen voor stapsgewijs leren. **Specifieke focus op AI-toepassingsimplementatie met Microsoft Foundry integratie.**

### Waarom Deze Cursus Essentieel is voor Moderne Ontwikkelaars

Gebaseerd op inzichten uit de Microsoft Foundry Discord-community, **wil 45% van de ontwikkelaars AZD gebruiken voor AI workloads**, maar ondervinden uitdagingen met:
- Complexe multi-service AI-architecturen
- Best practices voor AI-implementatie in productie  
- Integratie en configuratie van Azure AI-diensten
- Kostenoptimalisatie voor AI workloads
- Problemen oplossen bij AI-specifieke implementaties

### Leerdoelen

Door deze gestructureerde cursus te voltooien, zal je:
- **AZD Basisprincipes Beheersen**: Kernconcepten, installatie en configuratie
- **AI-toepassingen Implementeren**: AZD gebruiken met Microsoft Foundry-diensten
- **Infrastructuur als Code Implementeren**: Azure resources beheren met Bicep-templates
- **Problemen bij Implementaties Oplossen**: Veelvoorkomende problemen herkennen en debuggen
- **Optimaliseren voor Productie**: Beveiliging, schaalbaarheid, monitoring en kostenbeheer
- **Multi-Agent Oplossingen Bouwen**: Complexe AI-architecturen implementeren

## 📚 Leerhoofdstukken

*Kies je leerpad op basis van ervaringsniveau en doelen*

### 🚀 Hoofdstuk 1: Basis & Snelle Start
**Vereisten**: Azure-abonnement, basiskennis command line  
**Duur**: 30-45 minuten  
**Complexiteit**: ⭐

#### Wat je leert
- Begrijpen van Azure Developer CLI basisprincipes
- AZD installeren op jouw platform
- Je eerste succesvolle implementatie

#### Leerbronnen
- **🎯 Begin Hier**: [Wat is Azure Developer CLI?](../..)
- **📖 Theorie**: [AZD Basics](docs/getting-started/azd-basics.md) - Kernconcepten en terminologie
- **⚙️ Installatie**: [Installatie & Setup](docs/getting-started/installation.md) - Platformspecificaties
- **🛠️ Praktijk**: [Je Eerste Project](docs/getting-started/first-project.md) - Stap-voor-stap tutorial
- **📋 Snel Overzicht**: [Command Cheat Sheet](resources/cheat-sheet.md)

#### Praktische Oefeningen
```bash
# Snelle installatiecontrole
azd version

# Zet je eerste toepassing uit
azd init --template todo-nodejs-mongo
azd up
```

**💡 Hoofdstukresultaat**: Een eenvoudige webapplicatie succesvol naar Azure implementeren met AZD

**✅ Succesvalidatie:**
```bash
# Na het voltooien van Hoofdstuk 1 zou je in staat moeten zijn om:
azd version              # Toont geïnstalleerde versie
azd init --template todo-nodejs-mongo  # Initialiseert project
azd up                  # Zet uit op Azure
azd show                # Toont URL van draaiende app
# Applicatie opent in browser en werkt
azd down --force --purge  # Ruimt bronnen op
```

**📊 Tijdsinvestering:** 30-45 minuten  
**📈 Vaardigheidsniveau daarna:** Kan basistoepassingen zelfstandig implementeren

**✅ Succesvalidatie:**
```bash
# Na het voltooien van Hoofdstuk 1 zou je moeten kunnen:
azd version              # Toont geïnstalleerde versie
azd init --template todo-nodejs-mongo  # Initialiseert project
azd up                  # Zet uit naar Azure
azd show                # Toont URL van draaiende app
# Applicatie opent in browser en werkt
azd down --force --purge  # Ruimt middelen op
```

**📊 Tijdsinvestering:** 30-45 minuten  
**📈 Vaardigheidsniveau daarna:** Kan basistoepassingen zelfstandig implementeren

---

### 🤖 Hoofdstuk 2: AI-Eerst Ontwikkeling (Aanbevolen voor AI-ontwikkelaars)
**Vereisten**: Hoofdstuk 1 voltooid  
**Duur**: 1-2 uur  
**Complexiteit**: ⭐⭐

#### Wat je leert
- Microsoft Foundry integratie met AZD
- Implementeren van AI-gedreven applicaties
- Begrijpen van AI-dienstconfiguraties

#### Leerbronnen
- **🎯 Begin Hier**: [Microsoft Foundry Integratie](docs/microsoft-foundry/microsoft-foundry-integration.md)
- **📖 Patronen**: [AI Model Implementatie](docs/microsoft-foundry/ai-model-deployment.md) - AI modellen implementeren en beheren
- **🛠️ Workshop**: [AI Workshop Lab](docs/microsoft-foundry/ai-workshop-lab.md) - Maak je AI-oplossingen AZD-klaar
- **🎥 Interactieve Gids**: [Workshop Materialen](workshop/README.md) - Browsergebaseerd leren met MkDocs * DevContainer Omgeving
- **📋 Templates**: [Microsoft Foundry Templates](../..)
- **📝 Voorbeelden**: [AZD Implementatie Voorbeelden](examples/README.md)

#### Praktische Oefeningen
```bash
# Zet je eerste AI-toepassing in
azd init --template azure-search-openai-demo
azd up

# Probeer extra AI-sjablonen
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```

**💡 Hoofdstukresultaat**: Een AI-gedreven chatapplicatie met RAG-mogelijkheden implementeren en configureren

**✅ Succesvalidatie:**
```bash
# Na hoofdstuk 2 zou je in staat moeten zijn om:
azd init --template azure-search-openai-demo
azd up
# De AI-chatinterface te testen
# Vragen te stellen en AI-ondersteunde antwoorden met bronnen te krijgen
# Verifiëren dat de zoekintegratie werkt
azd monitor  # Controleren of Application Insights telemetrie toont
azd down --force --purge
```

**📊 Tijdsinvestering:** 1-2 uur  
**📈 Vaardigheidsniveau daarna:** Kan productieklare AI-applicaties implementeren en configureren  
**💰 Kostenbewustzijn:** Begrijpt ontwikkelkosten $80-150/maand, productiekosten $300-3500/maand

#### 💰 Kostenoverwegingen voor AI-implementaties

**Ontwikkelomgeving (Geschat $80-150/maand):**
- Azure OpenAI (Pay-as-you-go): $0-50/maand (afhankelijk van tokenverbruik)
- AI Search (Basic tier): $75/maand
- Container Apps (Consumption): $0-20/maand
- Opslag (Standaard): $1-5/maand

**Productieomgeving (Geschat $300-3.500+/maand):**
- Azure OpenAI (PTU voor consistente prestaties): $3.000+/maand OF Pay-as-you-go bij hoog volume
- AI Search (Standaard tier): $250/maand
- Container Apps (Dedicated): $50-100/maand
- Application Insights: $5-50/maand
- Opslag (Premium): $10-50/maand

**💡 Tips voor Kostenoptimalisatie:**
- Gebruik **Free Tier** Azure OpenAI voor leren (50.000 tokens/maand inbegrepen)
- Voer `azd down` uit om resources te de-alloceren als je niet actief ontwikkelt
- Begin met consumption-based billing, upgrade alleen naar PTU voor productie
- Gebruik `azd provision --preview` om kosten vooraf te schatten
- Schakel auto-scaling in: betaal alleen voor het daadwerkelijke gebruik

**Kostenmonitoring:**
```bash
# Controleer geschatte maandelijkse kosten
azd provision --preview

# Houd werkelijke kosten in de Azure Portal bij
az consumption budget list --resource-group <your-rg>
```

---

### ⚙️ Hoofdstuk 3: Configuratie & Authenticatie
**Vereisten**: Hoofdstuk 1 voltooid  
**Duur**: 45-60 minuten  
**Complexiteit**: ⭐⭐

#### Wat je leert
- Omgevingsconfiguratie en beheer
- Authenticatie en beste beveiligingspraktijken
- Naamgeving en organisatie van resources

#### Leerbronnen
- **📖 Configuratie**: [Configuratiegids](docs/getting-started/configuration.md) - Omgevingsinstellingen
- **🔐 Beveiliging**: [Authenticatiepatronen en managed identity](docs/getting-started/authsecurity.md) - Authenticatiepatronen
- **📝 Voorbeelden**: [Database App Voorbeeld](examples/database-app/README.md) - AZD Database Voorbeelden

#### Praktische Oefeningen
- Configureer meerdere omgevingen (dev, staging, prod)
- Stel managed identity authentication in
- Implementeer omgevingsspecifieke configuraties

**💡 Hoofdstukresultaat**: Beheer meerdere omgevingen met juiste authenticatie en beveiliging

---

### 🏗️ Hoofdstuk 4: Infrastructuur als Code & Implementatie
**Vereisten**: Hoofdstukken 1-3 voltooid  
**Duur**: 1-1,5 uur  
**Complexiteit**: ⭐⭐⭐

#### Wat je leert
- Geavanceerde implementatiepatronen
- Infrastructuur als Code met Bicep
- Strategieën voor resource provisioning

#### Leerbronnen
- **📖 Implementatie**: [Implementatiegids](docs/deployment/deployment-guide.md) - Complete workflows
- **🏗️ Provisioning**: [Provisioning Resources](docs/deployment/provisioning.md) - Azure resource beheer
- **📝 Voorbeelden**: [Container App Voorbeeld](../../examples/container-app) - Containerized implementaties

#### Praktische Oefeningen
- Maak aangepaste Bicep-templates
- Implementeer multi-service applicaties
- Implementeer blue-green deployment strategieën

**💡 Hoofdstukresultaat**: Complexe multi-service applicaties implementeren met aangepaste infrastructuur templates

---
### 🎯 Hoofdstuk 5: Multi-Agent AI-oplossingen (Geavanceerd)
**Vereisten**: Hoofdstukken 1-2 voltooid  
**Duur**: 2-3 uur  
**Complexiteit**: ⭐⭐⭐⭐

#### Wat Je Zal Leren
- Multi-agent architectuurpatronen
- Agentorchestratie en coördinatie
- Productiegereed AI-implementaties

#### Leerbronnen
- **🤖 Uitgelicht Project**: [Retail Multi-Agent Oplossing](examples/retail-scenario.md) - Volledige implementatie
- **🛠️ ARM Sjablonen**: [ARM Sjabloonpakket](../../examples/retail-multiagent-arm-template) - Implementatie met één klik
- **📖 Architectuur**: [Multi-agent coördinatiepatronen](/docs/pre-deployment/coordination-patterns.md) - Patronen

#### Praktische Oefeningen
```bash
# Implementeer de complete retail multi-agent oplossing
cd examples/retail-multiagent-arm-template
./deploy.sh

# Verken agentconfiguraties
az deployment group show --resource-group <rg-name> --name <deployment-name>
```

**💡 Resultaat Hoofdstuk**: Implementeer en beheer een productiegereed multi-agent AI-oplossing met Customer en Inventory agents

---

### 🔍 Hoofdstuk 6: Validatie & Planning voor Implementatie
**Vereisten**: Hoofdstuk 4 voltooid  
**Duur**: 1 uur  
**Complexiteit**: ⭐⭐

#### Wat Je Zal Leren
- Capaciteitsplanning en resourcevalidatie
- Strategieën voor SKU-selectie
- Pre-flight controles en automatisering

#### Leerbronnen
- **📊 Planning**: [Capaciteitsplanning](docs/pre-deployment/capacity-planning.md) - Resourcevalidatie
- **💰 Selectie**: [SKU-selectie](docs/pre-deployment/sku-selection.md) - Kosteneffectieve keuzes
- **✅ Validatie**: [Pre-flight controles](docs/pre-deployment/preflight-checks.md) - Geautomatiseerde scripts

#### Praktische Oefeningen
- Voer scripts voor capaciteitsvalidatie uit
- Optimaliseer SKU-selecties voor kostenbesparing
- Implementeer geautomatiseerde pre-implementatie controles

**💡 Resultaat Hoofdstuk**: Valideer en optimaliseer implementaties vóór uitvoering

---

### 🚨 Hoofdstuk 7: Probleemoplossing & Debuggen
**Vereisten**: Elk implementatiehoofdstuk voltooid  
**Duur**: 1-1,5 uur  
**Complexiteit**: ⭐⭐

#### Wat Je Zal Leren
- Systematische debugmethoden
- Veelvoorkomende problemen en oplossingen
- AI-specifieke probleemoplossing

#### Leerbronnen
- **🔧 Veelvoorkomende Problemen**: [Veelvoorkomende problemen](docs/troubleshooting/common-issues.md) - FAQ en oplossingen
- **🕵️ Debuggen**: [Debuggids](docs/troubleshooting/debugging.md) - Stapsgewijze strategieën
- **🤖 AI Problemen**: [AI-specifieke probleemoplossing](docs/troubleshooting/ai-troubleshooting.md) - Problemen met AI-diensten

#### Praktische Oefeningen
- Diagnoseer implementatiefouten
- Los authenticatieproblemen op
- Debug verbindingsproblemen met AI-diensten

**💡 Resultaat Hoofdstuk**: Diagnoseer en los zelfstandig veelvoorkomende implementatieproblemen op

---

### 🏢 Hoofdstuk 8: Productie- & Enterprisepatronen
**Vereisten**: Hoofdstukken 1-4 voltooid  
**Duur**: 2-3 uur  
**Complexiteit**: ⭐⭐⭐⭐

#### Wat Je Zal Leren
- Productie-implementatiestrategieën
- Enterprise-beveiligingspatronen
- Monitoring en kostenoptimalisatie

#### Leerbronnen
- **🏭 Productie**: [Productie AI Best Practices](docs/microsoft-foundry/production-ai-practices.md) - Enterprisepatronen
- **📝 Voorbeelden**: [Microservices Voorbeeld](../../examples/microservices) - Complexe architecturen
- **📊 Monitoring**: [Application Insights-integratie](docs/pre-deployment/application-insights.md) - Monitoring

#### Praktische Oefeningen
- Implementeer enterprise-beveiligingspatronen
- Stel uitgebreide monitoring in
- Implementeer in productie met correcte governance

**💡 Resultaat Hoofdstuk**: Implementeer enterprise-gereed applicaties met volledige productiecapaciteiten

---

## 🎓 Workshop Overzicht: Praktische Leerervaring

> **⚠️ WORKSHOPSTATUS: Actieve Ontwikkeling**  
> De workshopmaterialen worden momenteel ontwikkeld en verfijnd. Kernmodules zijn functioneel, maar sommige geavanceerde secties zijn nog onvolledig. We werken actief aan het afronden van alle inhoud. [Volg de voortgang →](workshop/README.md)

### Interactieve Workshopmaterialen
**Uitgebreide hands-on leerervaring met browsergebaseerde tools en begeleide oefeningen**

Onze workshopmaterialen bieden een gestructureerde, interactieve leerervaring die het hoofdstuk-gebaseerde curriculum hierboven aanvult. De workshop is ontworpen voor zelfgestuurd leren en sessies onder begeleiding.

#### 🛠️ Workshop Kenmerken
- **Browsergebaseerde Interface**: Volledige MkDocs-gedreven workshop met zoek-, kopieer- en themafuncties
- **GitHub Codespaces-integratie**: Eén-klik ontwikkelomgeving setup
- **Gestructureerd Leerpad**: 7-staps begeleide oefeningen (3,5 uur in totaal)
- **Ontdekking → Implementatie → Aanpassing**: Progressieve methodiek
- **Interactieve DevContainer-omgeving**: Vooraf geconfigureerde tools en afhankelijkheden

#### 📚 Workshopstructuur
De workshop volgt een **Ontdekking → Implementatie → Aanpassing** methodologie:

1. **Ontdekkingsfase** (45 min)
   - Verken Microsoft Foundry-sjablonen en services
   - Begrijp multi-agent architectuurpatronen
   - Beoordeel implementatievereisten en -voorschriften

2. **Implementatiefase** (2 uur)
   - Hands-on implementatie van AI-applicaties met AZD
   - Configureer Azure AI-diensten en endpoints
   - Implementeer beveiligings- en authenticatiepatronen

3. **Aanpassingsfase** (45 min)
   - Wijzig applicaties voor specifieke gebruiksscenario's
   - Optimaliseer voor productie-implementaties
   - Implementeer monitoring en kostenbeheer

#### 🚀 Aan de Slag met de Workshop
```bash
# Optie 1: GitHub Codespaces (Aanbevolen)
# Klik op "Code" → "Create codespace on main" in de repository

# Optie 2: Lokale ontwikkeling
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# Volg de installatie-instructies in workshop/README.md
```

#### 🎯 Workshop Leerresultaten
Door de workshop te voltooien zullen deelnemers:
- **Productie AI-applicaties implementeren**: Gebruik AZD met Microsoft Foundry-services
- **Multi-agent architecturen beheersen**: Gecoördineerde AI-agentoplossingen implementeren
- **Beveiligingsbest practices toepassen**: Authenticatie en toegangscontrole configureren
- **Optimaliseren voor schaal**: Kosteneffectieve, prestatiegerichte implementaties ontwerpen
- **Problemen met implementaties oplossen**: Veelvoorkomende problemen zelfstandig oplossen

#### 📖 Workshopbronnen
- **🎥 Interactieve Gids**: [Workshopmaterialen](workshop/README.md) - Browsergebaseerde leeromgeving
- **📋 Stapsgewijze Instructies**: [Begeleide Oefeningen](../../workshop/docs/instructions) - Gedetailleerde walkthroughs
- **🛠️ AI Workshop Lab**: [AI Workshop Lab](docs/microsoft-foundry/ai-workshop-lab.md) - AI-gerichte oefeningen
- **💡 Quick Start**: [Workshop Setup Guide](workshop/README.md#quick-start) - Omgevingsconfiguratie

**Ideaal voor**: Bedrijfstrainingen, universitaire cursussen, zelfgestuurd leren en ontwikkelaar-bootcamps.

---

## 📖 Wat is Azure Developer CLI?

Azure Developer CLI (azd) is een ontwikkelaar-gerichte commandoregelinterface die het proces van bouwen en implementeren van applicaties naar Azure versnelt. Het biedt:

- **Sjabloon-gebaseerde implementaties** - Gebruik vooraf gebouwde sjablonen voor veelvoorkomende applicatiepatronen
- **Infrastructure as Code** - Beheer Azure-resources met Bicep of Terraform  
- **Geïntegreerde workflows** - Naadloos provisie, implementatie en monitoring van applicaties
- **Ontwikkelaarvriendelijk** - Geoptimaliseerd voor ontwikkelaarsproductiviteit en -ervaring

### **AZD + Microsoft Foundry: Perfect voor AI-Implementaties**

**Waarom AZD voor AI-oplossingen?** AZD pakt de belangrijkste uitdagingen aan waar AI-ontwikkelaars tegenaan lopen:

- **AI-Gereed Sjablonen** - Vooraf geconfigureerde sjablonen voor Azure OpenAI, Cognitive Services en ML workloads
- **Veilige AI-Implementaties** - Ingebouwde beveiligingspatronen voor AI-diensten, API-sleutels en modelendpoints  
- **Productie AI-Patronen** - Best practices voor schaalbare, kosteneffectieve AI-applicatie-implementaties
- **End-to-End AI Workflows** - Van modelontwikkeling tot productie-implementatie met correcte monitoring
- **Kostenoptimalisatie** - Slimme resource-toewijzing en schaalstrategieën voor AI workloads
- **Microsoft Foundry Integratie** - Naadloze koppeling met Microsoft Foundry modelcatalogus en endpoints

---

## 🎯 Sjablonen & Voorbeeldenbibliotheek

### Uitgelicht: Microsoft Foundry-sjablonen
**Begin hier als je AI-applicaties implementeert!**

> **Opmerking:** Deze sjablonen demonstreren diverse AI-patronen. Sommige zijn externe Azure Samples, andere lokale implementaties.

| Sjabloon | Hoofdstuk | Complexiteit | Services | Type |
|----------|---------|------------|----------|------|
| [**Begin met AI chat**](https://github.com/Azure-Samples/get-started-with-ai-chat) | Hoofdstuk 2 | ⭐⭐ | AzureOpenAI + Azure AI Model Inference API + Azure AI Search + Azure Container Apps + Application Insights | Extern |
| [**Begin met AI agents**](https://github.com/Azure-Samples/get-started-with-ai-agents) | Hoofdstuk 2 | ⭐⭐ | Azure AI Agent Service + AzureOpenAI + Azure AI Search + Azure Container Apps + Application Insights| Extern |
| [**Azure Search + OpenAI Demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Hoofdstuk 2 | ⭐⭐ | AzureOpenAI + Azure AI Search + App Service + Storage | Extern |
| [**OpenAI Chat App Quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Hoofdstuk 2 | ⭐ | AzureOpenAI + Container Apps + Application Insights | Extern |
| [**Agent OpenAI Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Hoofdstuk 5 | ⭐⭐⭐ | AzureOpenAI + Azure Functions + Prompty | Extern |
| [**Contoso Chat RAG**](https://github.com/Azure-Samples/contoso-chat) | Hoofdstuk 8 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Cosmos DB + Container Apps | Extern |
| [**Retail Multi-Agent Oplossing**](examples/retail-scenario.md) | Hoofdstuk 5 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Storage + Container Apps + Cosmos DB | **Lokaal** |

### Uitgelicht: Complete Leerscenario's
**Productiegereede applicatiesjablonen gekoppeld aan leerhoofdstukken**

| Sjabloon | Leerhoofdstuk | Complexiteit | Belangrijkste Leerpunten |
|----------|------------------|------------|--------------|
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Hoofdstuk 2 | ⭐ | Basale AI-implementatiepatronen |
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Hoofdstuk 2 | ⭐⭐ | RAG-implementatie met Azure AI Search |
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | Hoofdstuk 4 | ⭐⭐ | Integratie van Document Intelligence |
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Hoofdstuk 5 | ⭐⭐⭐ | Agent-framework en functieoproepen |
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | Hoofdstuk 8 | ⭐⭐⭐ | Enterprise AI-orchestatie |
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | Hoofdstuk 5 | ⭐⭐⭐⭐ | Multi-agent architectuur met Customer en Inventory agents |

### Leren door Voorbeeldtype

> **📌 Lokale versus Externe Voorbeelden:**  
> **Lokale Voorbeelden** (in deze repo) = Direct gebruiksklaar  
> **Externe Voorbeelden** (Azure Samples) = Klonen vanuit gekoppelde repositories

#### Lokale Voorbeelden (Direct Gebruikbaar)
- [**Retail Multi-Agent Oplossing**](examples/retail-scenario.md) - Volledige productiegereede implementatie met ARM-sjablonen
  - Multi-agent architectuur (Customer + Inventory agents)
  - Uitgebreide monitoring en evaluatie
  - Implementatie met één klik via ARM-sjabloon

#### Lokale Voorbeelden - Containerapplicaties (Hoofdstukken 2-5)
**Uitgebreide containerimplementatievoorbeelden in deze repository:**
- [**Container App Voorbeelden**](examples/container-app/README.md) - Complete handleiding voor containerimplementaties
  - [Eenvoudige Flask API](../../examples/container-app/simple-flask-api) - Basale REST API met scale-to-zero
  - [Microservices Architectuur](../../examples/container-app/microservices) - Productiegereede multi-service implementatie
  - Quick Start, Productie en Geavanceerde implementatiepatronen
  - Richtlijnen voor monitoring, beveiliging en kostenoptimalisatie

#### Externe Voorbeelden - Eenvoudige Applicaties (Hoofdstukken 1-2)
**Kloon deze Azure Samples-repositories om te starten:**
- [Eenvoudige Webapp - Node.js + MongoDB](https://github.com/Azure-Samples/todo-nodejs-mongo) - Basale implementatiepatronen
- [Statische Website - React SPA](https://github.com/Azure-Samples/todo-csharp-sql-swa-func) - Implementatie statische content
- [Container App - Python Flask](https://github.com/Azure-Samples/container-apps-store-api-microservice) - REST API implementatie

#### Externe Voorbeelden - Database Integratie (Hoofdstuk 3-4)  
- [Database App - C# + SQL](https://github.com/Azure-Samples/todo-csharp-sql) - Databaseconnectiviteitspatronen
- [Functions + Cosmos DB](https://github.com/Azure-Samples/todo-python-mongo-swa-func) - Serverless data workflow

#### Externe Voorbeelden - Geavanceerde Patronen (Hoofdstukken 4-8)
- [Java Microservices](https://github.com/Azure-Samples/java-microservices-aca-lab) - Multi-service architecturen
- [Container Apps Jobs](https://github.com/Azure-Samples/container-apps-jobs) - Achtergrondverwerking  
- [Enterprise ML Pipeline](https://github.com/Azure-Samples/mlops-v2) - Productiegereede ML-patronen

### Externe Sjabloonverzamelingen
- [**Officiële AZD Template Galerie**](https://azure.github.io/awesome-azd/) - Geselecteerde collectie van officiële en community-templates  
- [**Azure Developer CLI Templates**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - Microsoft Learn template documentatie  
- [**Voorbeeldmap**](examples/README.md) - Lokale leervoorbeelden met uitgebreide uitleg  

---

## 📚 Leerbronnen & Verwijzingen

### Snelle verwijzingen  
- [**Command Cheat Sheet**](resources/cheat-sheet.md) - Essentiële azd-commando’s georganiseerd per hoofdstuk  
- [**Verklarende Woordenlijst**](resources/glossary.md) - Azure en azd terminologie  
- [**Veelgestelde Vragen**](resources/faq.md) - Veelvoorkomende vragen georganiseerd per leervoordracht  
- [**Studiegids**](resources/study-guide.md) - Uitgebreide oefenopdrachten  

### Praktijkgerichte Workshops  
- [**AI Workshop Lab**](docs/microsoft-foundry/ai-workshop-lab.md) - Maak je AI-oplossingen AZD-deployable (2-3 uur)  
- [**Interactieve Workshop Gids**](workshop/README.md) - Browsergebaseerde workshop met MkDocs en DevContainer-omgeving  
- [**Gestructureerd Leertraject**](../../workshop/docs/instructions) - 7-staps begeleide oefeningen (Ontdekking → Uitrol → Aanpassing)  
- [**AZD Voor Beginners Workshop**](workshop/README.md) - Volledige hands-on workshopmaterialen met GitHub Codespaces-integratie  

### Externe Leerbronnen  
- [Azure Developer CLI Documentatie](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)  
- [Azure Architectuurcentrum](https://learn.microsoft.com/en-us/azure/architecture/)  
- [Azure Prijscalculator](https://azure.microsoft.com/pricing/calculator/)  
- [Azure Status](https://status.azure.com/)  

---

## 🔧 Snelproblemen Oplossen Gids

**Veelvoorkomende problemen bij beginners en directe oplossingen:**

### ❌ "azd: command not found"  

```bash
# Installeer eerst AZD
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Verifieer de installatie
azd version
```
  
### ❌ "Geen abonnement gevonden" of "Abonnement niet ingesteld"  

```bash
# Lijst beschikbare abonnementen
az account list --output table

# Stel standaardabonnement in
az account set --subscription "<subscription-id-or-name>"

# Instellen voor AZD-omgeving
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Verifiëren
az account show
```
  
### ❌ "OnvoldoendeQuota" of "Quota overschreden"  

```bash
# Probeer een andere Azure-regio
azd env set AZURE_LOCATION "westus2"
azd up

# Of gebruik kleinere SKUs tijdens ontwikkeling
# Bewerk infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
  
### ❌ "azd up" faalt halverwege  

```bash
# Optie 1: Schoonmaken en opnieuw proberen
azd down --force --purge
azd up

# Optie 2: Alleen infrastructuur repareren
azd provision

# Optie 3: Controleer gedetailleerde logs
azd show
azd logs
```
  
### ❌ "Authenticatie mislukt" of "Token verlopen"  

```bash
# Opnieuw authenticeren
az logout
az login

azd auth logout
azd auth login

# Verifieer authenticatie
az account show
```
  
### ❌ "Resource bestaat al" of naamconflicten  

```bash
# AZD genereert unieke namen, maar bij een conflict:
azd down --force --purge

# Probeer het dan opnieuw met een nieuwe omgeving
azd env new dev-v2
azd up
```
  
### ❌ Template uitrol duurt te lang  

**Normale wachttijden:**  
- Eenvoudige webapp: 5-10 minuten  
- App met database: 10-15 minuten  
- AI-toepassingen: 15-25 minuten (OpenAI provisioning is traag)  

```bash
# Controleer voortgang
azd show

# Als vastgelopen >30 minuten, controleer Azure Portal:
azd monitor
# Zoek naar mislukte implementaties
```
  
### ❌ "Toegang geweigerd" of "Verboden"  

```bash
# Controleer uw Azure-rol
az role assignment list --assignee $(az account show --query user.name -o tsv)

# U heeft minimaal de rol "Contributor" nodig
# Vraag uw Azure-beheerder om te verlenen:
# - Contributor (voor resources)
# - User Access Administrator (voor roltoewijzingen)
```
  
### ❌ Kan uitgevoerde applicatie-URL niet vinden  

```bash
# Toon alle service-eindpunten
azd show

# Of open Azure Portal
azd monitor

# Controleer specifieke service
azd env get-values
# Zoek naar *_URL-variabelen
```
  
### 📚 Volledige Probleemoplossingsbronnen  

- **Gids voor veelvoorkomende problemen:** [Gedetailleerde oplossingen](docs/troubleshooting/common-issues.md)  
- **AI-specifieke problemen:** [AI Probleemoplossing](docs/troubleshooting/ai-troubleshooting.md)  
- **Debuggids:** [Stap-voor-stap debuggen](docs/troubleshooting/debugging.md)  
- **Hulp vragen:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli  

---

## 🔧 Snelproblemen Oplossen Gids

**Veelvoorkomende problemen bij beginners en directe oplossingen:**

<details>  
<summary><strong>❌ "azd: command not found"</strong></summary>  

```bash
# Installeer eerst AZD
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Verifieer installatie
azd version
```
</details>  

<details>  
<summary><strong>❌ "Geen abonnement gevonden" of "Abonnement niet ingesteld"</strong></summary>  

```bash
# Lijst beschikbare abonnementen
az account list --output table

# Stel standaardabonnement in
az account set --subscription "<subscription-id-or-name>"

# Instellen voor AZD-omgeving
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Verifiëren
az account show
```
</details>  

<details>  
<summary><strong>❌ "OnvoldoendeQuota" of "Quota overschreden"</strong></summary>  

```bash
# Probeer een andere Azure-regio
azd env set AZURE_LOCATION "westus2"
azd up

# Of gebruik kleinere SKU's in ontwikkeling
# Bewerk infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>  

<details>  
<summary><strong>❌ "azd up" faalt halverwege</strong></summary>  

```bash
# Optie 1: Schoonmaken en opnieuw proberen
azd down --force --purge
azd up

# Optie 2: Alleen infrastructuur repareren
azd provision

# Optie 3: Gedetailleerde logs controleren
azd show
azd logs
```
</details>  

<details>  
<summary><strong>❌ "Authenticatie mislukt" of "Token verlopen"</strong></summary>  

```bash
# Herauthenticeren
az logout
az login

azd auth logout
azd auth login

# Authenticatie verifiëren
az account show
```
</details>  

<details>  
<summary><strong>❌ "Resource bestaat al" of naamconflicten</strong></summary>  

```bash
# AZD genereert unieke namen, maar bij conflicten:
azd down --force --purge

# Probeer dan opnieuw met een nieuwe omgeving
azd env new dev-v2
azd up
```
</details>  

<details>  
<summary><strong>❌ Template uitrol duurt te lang</strong></summary>  

**Normale wachttijden:**  
- Eenvoudige webapp: 5-10 minuten  
- App met database: 10-15 minuten  
- AI-toepassingen: 15-25 minuten (OpenAI provisioning is traag)  

```bash
# Controleer voortgang
azd show

# Als je langer dan 30 minuten vastzit, controleer dan de Azure Portal:
azd monitor
# Zoek naar mislukte implementaties
```
</details>  

<details>  
<summary><strong>❌ "Toegang geweigerd" of "Verboden"</strong></summary>  

```bash
# Controleer uw Azure-rol
az role assignment list --assignee $(az account show --query user.name -o tsv)

# U hebt minimaal de rol "Contributor" nodig
# Vraag uw Azure-beheerder om toestemming te verlenen:
# - Contributor (voor middelen)
# - User Access Administrator (voor roltoewijzingen)
```
</details>  

<details>  
<summary><strong>❌ Kan uitgevoerde applicatie-URL niet vinden</strong></summary>  

```bash
# Toon alle service-eindpunten
azd show

# Of open de Azure Portal
azd monitor

# Controleer specifieke service
azd env get-values
# Zoek naar *_URL variabelen
```
</details>  

### 📚 Volledige Probleemoplossingsbronnen  

- **Gids voor veelvoorkomende problemen:** [Gedetailleerde oplossingen](docs/troubleshooting/common-issues.md)  
- **AI-specifieke problemen:** [AI Probleemoplossing](docs/troubleshooting/ai-troubleshooting.md)  
- **Debuggids:** [Stap-voor-stap debuggen](docs/troubleshooting/debugging.md)  
- **Hulp vragen:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli  

---

## 🎓 Cursusafronding & Certificering

### Voortgang bijhouden  
Volg je leerproces door elk hoofdstuk:  

- [ ] **Hoofdstuk 1**: Basis & Snelstart ✅  
- [ ] **Hoofdstuk 2**: AI-First Ontwikkeling ✅  
- [ ] **Hoofdstuk 3**: Configuratie & Authenticatie ✅  
- [ ] **Hoofdstuk 4**: Infrastructuur als Code & Uitrol ✅  
- [ ] **Hoofdstuk 5**: Multi-Agent AI Oplossingen ✅  
- [ ] **Hoofdstuk 6**: Validatie & Planning voor Uitrol ✅  
- [ ] **Hoofdstuk 7**: Probleemoplossing & Debugging ✅  
- [ ] **Hoofdstuk 8**: Productie- & Enterprisepatronen ✅  

### Leercontrole  
Controleer je kennis na voltooiing van elk hoofdstuk door:  
1. **Praktische oefening**: Voltooi de hands-on uitrol van het hoofdstuk  
2. **Kenniscontrole**: Bekijk de FAQ sectie van je hoofdstuk  
3. **Community-discussie**: Deel je ervaring in Azure Discord  
4. **Volgend hoofdstuk**: Ga verder naar het volgende complexiteitsniveau  

### Voordelen bij cursusafronding  
Na afronding van alle hoofdstukken heb je:  
- **Productie-ervaring**: Echte AI-applicaties uitgerold naar Azure  
- **Professionele vaardigheden**: Enterprise-klaar uitrolvermogen  
- **Communityerkenning**: Actief lid van de Azure developer community  
- **Carrièrebevordering**: Gewilde AZD- en AI-uitrolexpertise  

---

## 🤝 Community & Ondersteuning

### Hulp & Ondersteuning  
- **Technische problemen**: [Meld bugs en vraag functies aan](https://github.com/microsoft/azd-for-beginners/issues)  
- **Leervragen**: [Microsoft Azure Discord Community](https://discord.gg/microsoft-azure) en [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)  
- **AI-specifieke hulp**: Word lid van de [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)  
- **Documentatie**: [Officiële Azure Developer CLI documentatie](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)  

### Community-inzichten van Microsoft Foundry Discord  

**Recente pollresultaten van het #Azure-kanaal:**  
- **45%** van de ontwikkelaars wil AZD gebruiken voor AI workloads  
- **Top uitdagingen:** Multi-service uitrol, credential management, productie-klaarheid  
- **Meest gevraagd:** AI-specifieke templates, probleemoplossingsgidsen, best practices  

**Word lid van onze community om:**  
- Je AZD + AI-ervaringen te delen en hulp te krijgen  
- Vroege previews van nieuwe AI-templates te krijgen  
- Bij te dragen aan AI-uitrol best practices  
- Invloed uit te oefenen op toekomstige AI + AZD functieontwikkeling  

### Bijdragen aan de cursus  
We verwelkomen bijdragen! Lees onze [Bijdragerhandleiding](CONTRIBUTING.md) voor details over:  
- **Inhoud verbeteren:** Verfraai bestaande hoofdstukken en voorbeelden  
- **Nieuwe voorbeelden:** Voeg praktijkvoorbeelden en templates toe  
- **Vertaling:** Help meertalige ondersteuning behouden  
- **Bugrapportages:** Verbeter nauwkeurigheid en duidelijkheid  
- **Community-standaarden:** Volg onze inclusieve communityrichtlijnen  

---

## 📄 Cursusinformatie

### Licentie  
Dit project is gelicenseerd onder de MIT-licentie - zie het [LICENSE](../../LICENSE) bestand voor details.

### Gerelateerde Microsoft Leerbronnen

Ons team produceert andere uitgebreide leercursussen:  

<!-- CO-OP TRANSLATOR OTHER COURSES START -->  
### LangChain  
[![LangChain4j voor Beginners](https://img.shields.io/badge/LangChain4j%20for%20Beginners-22C55E?style=for-the-badge&&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchain4j-for-beginners)  
[![LangChain.js voor Beginners](https://img.shields.io/badge/LangChain.js%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchainjs-for-beginners?WT.mc_id=m365-94501-dwahlin)  

---  

### Azure / Edge / MCP / Agents  
[![AZD voor Beginners](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)  
[![Edge AI voor Beginners](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)  
[![MCP voor Beginners](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)  
[![AI Agents voor Beginners](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)  

---  
 
### Generatieve AI-serie  
[![Generatieve AI voor Beginners](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)  
[![Generatieve AI (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)  
[![Generatieve AI (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)  
[![Generatieve AI (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)  

---  
 
### Kernleren  
[![ML voor Beginners](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![Data Science for Beginners](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![AI for Beginners](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Cybersecurity for Beginners](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Web Dev for Beginners](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![IoT for Beginners](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![XR Development for Beginners](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Copilot-serie
[![Copilot for AI Paired Programming](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![Copilot for C#/.NET](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Copilot Adventure](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ Cursusnavigatie

**🚀 Klaar om te beginnen met leren?**

**Beginners**: Begin met [Hoofdstuk 1: Basis & Snelle Start](../..)  
**AI-ontwikkelaars**: Ga naar [Hoofdstuk 2: AI-First Ontwikkeling](../..)  
**Ervaren ontwikkelaars**: Begin met [Hoofdstuk 3: Configuratie & Authenticatie](../..)

**Volgende stappen**: [Begin Hoofdstuk 1 - AZD Basics](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Disclaimer**:  
Dit document is vertaald met behulp van de AI-vertalingsservice [Co-op Translator](https://github.com/Azure/co-op-translator). Hoewel wij streven naar nauwkeurigheid, dient u er rekening mee te houden dat automatische vertalingen fouten of onjuistheden kunnen bevatten. Het originele document in de oorspronkelijke taal geldt als de gezaghebbende bron. Voor kritieke informatie wordt professionele menselijke vertaling aanbevolen. Wij zijn niet aansprakelijk voor eventuele misverstanden of verkeerde interpretaties die voortvloeien uit het gebruik van deze vertaling.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->