<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T13:47:45+00:00",
  "source_file": "README.md",
  "language_code": "no"
}
-->
> Merk: Denne dokumentasjonen oppdateres kontinuerlig for å gjenspeile de siste endringene.

> ⚠️ Dette depotet er en demo laget for å vise frem
> automatisert dokumentasjonslokalisering ved bruk av Localizeflow.
>
> Det originale innholdet er basert på
> Microsofts “AZD for nybegynnere”-prosjekt.


# AZD For Nybegynnere: En Strukturert Læringsreise

![AZD-for-beginners](../../translated_images/azdbeginners.5527441dd9f74068.no.png) 

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## Komme i gang med dette kurset

Følg disse trinnene for å starte din AZD læringsreise:

1. **Fork depotet**: Klikk [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)
2. **Klone depotet**: `git clone https://github.com/microsoft/azd-for-beginners.git`
3. **Bli med i fellesskapet**: [Azure Discord Communities](https://discord.com/invite/ByRwuEEgH4) for ekspertstøtte
4. **Velg din læringssti**: Velg et kapittel nedenfor som passer ditt erfaringsnivå

### Støtte for flere språk

#### Automatiserte oversettelser (alltid oppdatert)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](./README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Foretrekker du å klone lokalt?**

> Dette depotet inkluderer 50+ språkoversettelser som betydelig øker nedlastingsstørrelsen. For å klone uten oversettelser, bruk sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Dette gir deg alt du trenger for å fullføre kurset med en mye raskere nedlasting.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## Kursoversikt

Mestre Azure Developer CLI (azd) gjennom strukturerte kapitler designet for progressiv læring. **Spesiell fokus på AI-applikasjonsdistribusjon med Microsoft Foundry-integrasjon.**

### Hvorfor dette kurset er essensielt for dagens utviklere

Basert på innsikt fra Microsoft Foundry Discord-fellesskapet, ønsker **45 % av utviklerne å bruke AZD for AI-arbeidsbelastninger**, men møter utfordringer med:
- Kompleks fler-tjeneste AI-arkitektur
- Beste praksis for produksjonsdistribusjon av AI  
- Azure AI-tjenesteintegrering og konfigurering
- Kostnadsoptimalisering for AI-arbeidsbelastninger
- Feilsøking av AI-spesifikke distribusjonsproblemer

### Læringsmål

Ved å fullføre dette strukturerte kurset vil du:
- **Mestre AZD Grunnleggende**: Kjernkonsepter, installasjon og konfigurasjon
- **Distribuere AI-applikasjoner**: Bruk AZD med Microsoft Foundry-tjenester
- **Implementere Infrastructure as Code**: Administrer Azure-ressurser med Bicep-maler
- **Feilsøke distribusjoner**: Løs vanlige problemer og debugge utfordringer
- **Optimalisere for produksjon**: Sikkerhet, skalering, overvåking og kostnadsstyring
- **Bygge Multi-Agent løsninger**: Distribuere komplekse AI-arkitekturer

## 📚 Læringskapitler

*Velg din læringssti basert på erfaringsnivå og mål*

### 🚀 Kapittel 1: Grunnlag og rask start
**Forutsetninger**: Azure-abonnement, grunnleggende kunnskap om kommandolinje  
**Varighet**: 30-45 minutter  
**Vanskelighetsgrad**: ⭐

#### Hva du vil lære
- Forstå Azure Developer CLI-grunnleggende
- Installere AZD på din plattform
- Din første vellykkede distribusjon

#### Læringsressurser
- **🎯 Start her**: [Hva er Azure Developer CLI?](../..)
- **📖 Teori**: [AZD Grunnprinsipper](docs/getting-started/azd-basics.md) - Grunnleggende konsepter og terminologi
- **⚙️ Oppsett**: [Installasjon & Oppsett](docs/getting-started/installation.md) - Plattformspesifikke guider
- **🛠️ Praktisk**: [Ditt første prosjekt](docs/getting-started/first-project.md) - Steg-for-steg veiledning
- **📋 Rask referanse**: [Kommandooversikt](resources/cheat-sheet.md)

#### Praktiske øvelser
```bash
# Rask installasjonssjekk
azd version

# Distribuer din første applikasjon
azd init --template todo-nodejs-mongo
azd up
```

**💡 Kapittelresultat**: Distribuere en enkel webapplikasjon til Azure ved hjelp av AZD

**✅ Suksessvalidering:**
```bash
# Etter å ha fullført kapittel 1, bør du kunne:
azd version              # Viser installert versjon
azd init --template todo-nodejs-mongo  # Initialiserer prosjekt
azd up                  # Distribuerer til Azure
azd show                # Viser URL for kjørende app
# Applikasjonen åpnes i nettleser og fungerer
azd down --force --purge  # Rydder opp ressurser
```

**📊 Tidsbruk:** 30-45 minutter  
**📈 Ferdighetsnivå etter:** Kan distribuere grunnleggende applikasjoner selvstendig

**✅ Suksessvalidering:**
```bash
# Etter å ha fullført kapittel 1, bør du kunne:
azd version              # Viser installert versjon
azd init --template todo-nodejs-mongo  # Initialiserer prosjekt
azd up                  # Distribuerer til Azure
azd show                # Viser URL for kjørende app
# Applikasjonen åpnes i nettleseren og fungerer
azd down --force --purge  # Rydder opp ressurser
```

**📊 Tidsbruk:** 30-45 minutter  
**📈 Ferdighetsnivå etter:** Kan distribuere grunnleggende applikasjoner selvstendig

---

### 🤖 Kapittel 2: AI-Først utvikling (Anbefalt for AI-utviklere)
**Forutsetninger**: Kapittel 1 fullført  
**Varighet**: 1-2 timer  
**Vanskelighetsgrad**: ⭐⭐

#### Hva du vil lære
- Microsoft Foundry-integrasjon med AZD
- Distribuere AI-drevne applikasjoner
- Forstå AI-tjenestekonfigurasjoner

#### Læringsressurser
- **🎯 Start her**: [Microsoft Foundry-integrasjon](docs/microsoft-foundry/microsoft-foundry-integration.md)
- **📖 Mønstre**: [AI Modell-distribusjon](docs/microsoft-foundry/ai-model-deployment.md) - Distribuer og administrer AI-modeller
- **🛠️ Workshop**: [AI Workshop Lab](docs/microsoft-foundry/ai-workshop-lab.md) - Gjør dine AI-løsninger AZD-klare
- **🎥 Interaktiv guide**: [Workshop Materiell](workshop/README.md) - Nettleserbasert læring med MkDocs * DevContainer miljø
- **📋 Maler**: [Microsoft Foundry-maler](../..)
- **📝 Eksempler**: [AZD Distribusjonseksempler](examples/README.md)

#### Praktiske øvelser
```bash
# Distribuer din første AI-applikasjon
azd init --template azure-search-openai-demo
azd up

# Prøv flere AI-maler
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```

**💡 Kapittelresultat**: Distribuere og konfigurere en AI-drevet chatapplikasjon med RAG-funksjonalitet

**✅ Suksessvalidering:**
```bash
# Etter kapittel 2 bør du kunne:
azd init --template azure-search-openai-demo
azd up
# Teste AI-chatgrensesnittet
# Stille spørsmål og få AI-drevne svar med kilder
# Bekrefte at søkeintegrasjonen fungerer
azd monitor  # Sjekke at Application Insights viser telemetri
azd down --force --purge
```

**📊 Tidsbruk:** 1-2 timer  
**📈 Ferdighetsnivå etter:** Kan distribuere og konfigurere produksjonsklare AI-applikasjoner  
**💰 Kostnadsbevissthet:** Forstå utviklingskostnader på $80-150/måned, produksjonskostnader $300-3500/måned

#### 💰 Kostnadsbetraktninger for AI-distribusjoner

**Utviklingsmiljø (estimat $80-150/måned):**
- Azure OpenAI (Betal etter bruk): $0-50/måned (basert på token-bruk)
- AI Search (Grunnleggende nivå): $75/måned
- Container Apps (Forbruk): $0-20/måned
- Lagring (Standard): $1-5/måned

**Produksjonsmiljø (estimat $300-3500+/måned):**
- Azure OpenAI (PTU for konsistent ytelse): $3000+/måned ELLER Betal-etter-bruk med høy volum
- AI Search (Standard nivå): $250/måned
- Container Apps (Dedikert): $50-100/måned
- Application Insights: $5-50/måned
- Lagring (Premium): $10-50/måned

**💡 Kostnadsoptimaliseringstips:**
- Bruk **Gratisnivå** Azure OpenAI for læring (inkluderer 50,000 tokens/måned)
- Kjør `azd down` for å frigjøre ressurser når du ikke utvikler aktivt
- Start med forbruksbasert fakturering, oppgrader til PTU kun for produksjon
- Bruk `azd provision --preview` for å estimere kostnader før distribusjon
- Aktiver autoskalering: betal kun for faktisk bruk

**Kostnadsovervåking:**
```bash
# Sjekk estimerte månedlige kostnader
azd provision --preview

# Overvåk faktiske kostnader i Azure-portalen
az consumption budget list --resource-group <your-rg>
```

---

### ⚙️ Kapittel 3: Konfigurasjon & Autentisering
**Forutsetninger**: Kapittel 1 fullført  
**Varighet**: 45-60 minutter  
**Vanskelighetsgrad**: ⭐⭐

#### Hva du vil lære
- Miljøkonfigurasjon og administrasjon
- Autentisering og sikkerhets beste praksis
- Navngiving og organisering av ressurser

#### Læringsressurser
- **📖 Konfigurasjon**: [Konfigurasjonsveiledning](docs/getting-started/configuration.md) - Miljøoppsett
- **🔐 Sikkerhet**: [Autentiseringsmønstre og administrert identitet](docs/getting-started/authsecurity.md) - Autentiseringsmønstre
- **📝 Eksempler**: [Databaseapplikasjonseksempel](examples/database-app/README.md) - AZD Databaseeksempler

#### Praktiske øvelser
- Konfigurer flere miljøer (dev, staging, prod)
- Sett opp autentisering med administrert identitet
- Implementer miljøspesifikke konfigurasjoner

**💡 Kapittelresultat**: Administrere flere miljøer med korrekt autentisering og sikkerhet

---

### 🏗️ Kapittel 4: Infrastructure as Code & Distribusjon
**Forutsetninger**: Kapitler 1-3 fullført  
**Varighet**: 1-1,5 timer  
**Vanskelighetsgrad**: ⭐⭐⭐

#### Hva du vil lære
- Avanserte distribusjonsmønstre
- Infrastructure as Code med Bicep
- Ressursprovisjoneringsstrategier

#### Læringsressurser
- **📖 Distribusjon**: [Distribusjonsveiledning](docs/deployment/deployment-guide.md) - Fullstendige arbeidsflyter
- **🏗️ Provisjonering**: [Provisjonering av ressurser](docs/deployment/provisioning.md) - Azure ressursadministrasjon
- **📝 Eksempler**: [Container App Eksempel](../../examples/container-app) - Containeriserte distribusjoner

#### Praktiske øvelser
- Lag egendefinerte Bicep-maler
- Distribuer fler-tjeneste applikasjoner
- Implementer blue-green distribusjonsstrategier

**💡 Kapittelresultat**: Distribuere komplekse fler-tjeneste applikasjoner ved bruk av egendefinerte infrastrukturenmaler

---
### 🎯 Kapittel 5: Multi-agent AI-løsninger (Avansert)
**Forutsetninger**: Kapitlene 1-2 fullført  
**Varighet**: 2-3 timer  
**Kompleksitet**: ⭐⭐⭐⭐

#### Hva du vil lære
- Mønstre for multi-agent arkitektur
- Agent-orkestrering og koordinering
- AI-distribusjoner klare for produksjon

#### Læringsressurser
- **🤖 Utvalgt prosjekt**: [Retail Multi-Agent Solution](examples/retail-scenario.md) - Fullstendig implementasjon
- **🛠️ ARM-maler**: [ARM Template Package](../../examples/retail-multiagent-arm-template) - Ett-klikks distribusjon
- **📖 Arkitektur**: [Multi-agent koordinasjon mønstre](/docs/pre-deployment/coordination-patterns.md) - Mønstre

#### Praktiske øvelser
```bash
# Distribuer den komplette detaljhandel multi-agent løsningen
cd examples/retail-multiagent-arm-template
./deploy.sh

# Utforsk agentkonfigurasjoner
az deployment group show --resource-group <rg-name> --name <deployment-name>
```

**💡 Kapittelutbytte**: Distribuer og administrer en produksjonsklar multi-agent AI-løsning med Kunde- og Lager-agenter

---

### 🔍 Kapittel 6: Validering og planlegging før distribusjon
**Forutsetninger**: Kapittel 4 fullført  
**Varighet**: 1 time  
**Kompleksitet**: ⭐⭐

#### Hva du vil lære
- Kapasitetsplanlegging og ressursvalidering
- Strategier for valg av SKU
- Pre-flight-sjekker og automatisering

#### Læringsressurser
- **📊 Planlegging**: [Kapasitetsplanlegging](docs/pre-deployment/capacity-planning.md) - Ressursvalidering
- **💰 Valg**: [SKU-valg](docs/pre-deployment/sku-selection.md) - Kostnadseffektive valg
- **✅ Validering**: [Pre-flight-sjekker](docs/pre-deployment/preflight-checks.md) - Automatiserte skript

#### Praktiske øvelser
- Kjør skript for kapasitetsvalidering
- Optimer SKU-valg for kostnad
- Implementer automatiserte pre-deployment-sjekker

**💡 Kapittelutbytte**: Valider og optimaliser distribusjoner før gjennomføring

---

### 🚨 Kapittel 7: Feilsøking og debugging
**Forutsetninger**: Fullført et hvilket som helst distribusjonskapittel  
**Varighet**: 1-1,5 timer  
**Kompleksitet**: ⭐⭐

#### Hva du vil lære
- Systematiske tilnærminger til feilsøking
- Vanlige problemer og løsninger
- AI-spesifikk feilsøking

#### Læringsressurser
- **🔧 Vanlige problemer**: [Vanlige problemer](docs/troubleshooting/common-issues.md) - FAQ og løsninger
- **🕵️ Feilsøking**: [Feilsøkingsveiledning](docs/troubleshooting/debugging.md) - Trinnvise strategier
- **🤖 AI-problemer**: [AI-spesifikk feilsøking](docs/troubleshooting/ai-troubleshooting.md) - AI-tjenesteproblemer

#### Praktiske øvelser
- Diagnostiser distribusjonssvikt
- Løs autentiseringsproblemer
- Feilsøk AI-tjenestetilkobling

**💡 Kapittelutbytte**: Selvstendig diagnostisere og løse vanlige distribusjonsproblemer

---

### 🏢 Kapittel 8: Produksjon og enterprise-mønstre
**Forutsetninger**: Kapitlene 1-4 fullført  
**Varighet**: 2-3 timer  
**Kompleksitet**: ⭐⭐⭐⭐

#### Hva du vil lære
- Strategier for produksjonsdistribusjon
- Enterprise sikkerhetsmønstre
- Overvåkning og kostnadsoptimalisering

#### Læringsressurser
- **🏭 Produksjon**: [Produksjons AI beste praksis](docs/microsoft-foundry/production-ai-practices.md) - Enterprise-mønstre
- **📝 Eksempler**: [Mikrotjeneste-eksempel](../../examples/microservices) - Komplekse arkitekturer
- **📊 Overvåkning**: [Application Insights-integrasjon](docs/pre-deployment/application-insights.md) - Overvåkning

#### Praktiske øvelser
- Implementer enterprise sikkerhetsmønstre
- Sett opp omfattende overvåkning
- Distribuer til produksjon med korrekt styring

**💡 Kapittelutbytte**: Distribuer enterprise-klare applikasjoner med full produksjonskapasitet

---

## 🎓 Workshop Oversikt: Praktisk læringserfaring

> **⚠️ WORKSHOP STATUS: Aktiv utvikling**  
> Workshop-materialene er under utvikling og forbedring. Kjernemoduler fungerer, men noen avanserte deler er ufullstendige. Vi jobber aktivt med å fullføre alt innhold. [Følg fremdrift →](workshop/README.md)

### Interaktive workshop-materialer
**Omfattende praktisk læring med nettleserbaserte verktøy og veiledede øvelser**

Våre workshop-materialer tilbyr en strukturert, interaktiv læringsopplevelse som kompletterer kapittelkursene ovenfor. Workshoppen er designet for både selvstyrt læring og instruktørledede sesjoner.

#### 🛠️ Workshop-funksjoner
- **Nettleserbasert grensesnitt**: Fullstendig MkDocs-drevet workshop med søk, kopiering og tema-funksjoner
- **GitHub Codespaces integrasjon**: Ett-klikks utviklingsmiljøoppsett
- **Strukturert læringsløp**: 7-trinns veiledede øvelser (totalt 3,5 timer)
- **Discover → Deploy → Customize**: Progressiv metodikk
- **Interaktiv DevContainer-miljø**: Ferdigkonfigurerte verktøy og avhengigheter

#### 📚 Workshop-struktur
Workshop følger metodikken **Discover → Deploy → Customize**:

1. **Discover-fase** (45 min)
   - Utforsk Microsoft Foundry-maler og tjenester
   - Forstå multi-agent arkitektur mønstre
   - Gå gjennom distribusjonskrav og forutsetninger

2. **Deploy-fase** (2 timer)
   - Praktisk deployering av AI-applikasjoner med AZD
   - Konfigurer Azure AI-tjenester og endepunkter
   - Implementer sikkerhets- og autentiseringsmønstre

3. **Customize-fase** (45 min)
   - Modifiser applikasjoner for spesifikke brukstilfeller
   - Optimaliser for produksjonsdistribusjon
   - Implementer overvåkning og kostnadsstyring

#### 🚀 Komme i gang med workshoppen
```bash
# Alternativ 1: GitHub Codespaces (Anbefalt)
# Klikk "Code" → "Create codespace on main" i depotet

# Alternativ 2: Lokal utvikling
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# Følg oppsettinstruksjonene i workshop/README.md
```

#### 🎯 Workshop læringsmål
Ved å fullføre workshoppen vil deltakerne:
- **Distribuere produksjonsklare AI-applikasjoner**: Bruke AZD med Microsoft Foundry-tjenester
- **Beherske multi-agent arkitekturer**: Implementere koordinerte AI-agent-løsninger
- **Implementere sikkerhetsbeste praksis**: Konfigurere autentisering og tilgangskontroll
- **Optimalisere for skalerbarhet**: Designe kostnadseffektive, høytytende distribusjoner
- **Feilsøke distribusjoner**: Løse vanlige problemer selvstendig

#### 📖 Workshop-ressurser
- **🎥 Interaktiv veiledning**: [Workshop-materialer](workshop/README.md) - Nettleserbasert læringsmiljø
- **📋 Trinnvise instruksjoner**: [Veiledede øvelser](../../workshop/docs/instructions) - Detaljerte gjennomganger
- **🛠️ AI Workshop-lab**: [AI Workshop Lab](docs/microsoft-foundry/ai-workshop-lab.md) - AI-fokuserte øvelser
- **💡 Rask start**: [Workshop Oppsettsguide](workshop/README.md#quick-start) - Konfigurasjon av miljø

**Perfekt for**: Bedriftstrening, universitetskurs, selvstyrt læring og utvikler bootcamps.

---

## 📖 Hva er Azure Developer CLI?

Azure Developer CLI (azd) er et utviklerfokusert kommandolinjeverktøy som akselererer prosessen med å bygge og distribuere applikasjoner til Azure. Det tilbyr:

- **Malbaserte distribusjoner** - Bruk forhåndsbygde maler for vanlige applikasjonsmønstre  
- **Infrastructure as Code** - Administrer Azure-ressurser med Bicep eller Terraform  
- **Integrerte arbeidsflyter** - Problemfri provisjonering, distribusjon og overvåkning av applikasjoner  
- **Utviklervennlig** - Optimalisert for utviklerproduktivitet og opplevelse

### **AZD + Microsoft Foundry: Perfekt for AI-distribusjoner**

**Hvorfor AZD for AI-løsninger?** AZD adresserer de viktigste utfordringene AI-utviklere møter:

- **AI-klare maler** - Forhåndskonfigurerte maler for Azure OpenAI, Cognitive Services og ML arbeidsmengder  
- **Sikre AI-distribusjoner** - Innebygde sikkerhetsmønstre for AI-tjenester, API-nøkler og modelendepunkter  
- **Produksjons AI-mønstre** - Beste praksis for skalerbare, kostnadseffektive AI-applikasjonsdistribusjoner  
- **Ende-til-ende AI-arbeidsflyter** - Fra modellutvikling til produksjonsdistribusjon med riktig overvåkning  
- **Kostnadsoptimalisering** - Smarte ressursallokeringer og skaleringsstrategier for AI arbeidsmengder  
- **Microsoft Foundry-integrasjon** - Sømløs tilkobling til Microsoft Foundry modellkatalog og endepunkter

---

## 🎯 Maler & Eksempelsamling

### Utvalgt: Microsoft Foundry-maler
**Start her hvis du distribuerer AI-applikasjoner!**

> **Merk:** Disse malene demonstrerer ulike AI-mønstre. Noen er eksterne Azure Samples, andre er lokale implementasjoner.

| Mal | Kapittel | Kompleksitet | Tjenester | Type |
|----------|---------|------------|----------|------|
| [**Get started with AI chat**](https://github.com/Azure-Samples/get-started-with-ai-chat) | Kapittel 2 | ⭐⭐ | AzureOpenAI + Azure AI Model Inference API + Azure AI Search + Azure Container Apps + Application Insights | Ekstern |
| [**Get started with AI agents**](https://github.com/Azure-Samples/get-started-with-ai-agents) | Kapittel 2 | ⭐⭐ | Azure AI Agent Service + AzureOpenAI + Azure AI Search + Azure Container Apps + Application Insights| Ekstern |
| [**Azure Search + OpenAI Demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Kapittel 2 | ⭐⭐ | AzureOpenAI + Azure AI Search + App Service + Storage | Ekstern |
| [**OpenAI Chat App Quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Kapittel 2 | ⭐ | AzureOpenAI + Container Apps + Application Insights | Ekstern |
| [**Agent OpenAI Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Kapittel 5 | ⭐⭐⭐ | AzureOpenAI + Azure Functions + Prompty | Ekstern |
| [**Contoso Chat RAG**](https://github.com/Azure-Samples/contoso-chat) | Kapittel 8 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Cosmos DB + Container Apps | Ekstern |
| [**Retail Multi-Agent Solution**](examples/retail-scenario.md) | Kapittel 5 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Storage + Container Apps + Cosmos DB | **Lokal** |

### Utvalgt: Fullstendige læringsscenarier
**Produksjonsklare applikasjonsmaler kartlagt til læringskapitler**

| Mal | Læringskapittel | Kompleksitet | Hovedlæring |
|----------|------------------|------------|--------------|
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Kapittel 2 | ⭐ | Grunnleggende AI-distribusjonsmønstre |
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Kapittel 2 | ⭐⭐ | RAG-implementasjon med Azure AI Search |
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | Kapittel 4 | ⭐⭐ | Document Intelligence-integrasjon |
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Kapittel 5 | ⭐⭐⭐ | Agent-rammeverk og funksjonskall |
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | Kapittel 8 | ⭐⭐⭐ | Enterprise AI-orkestrering |
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | Kapittel 5 | ⭐⭐⭐⭐ | Multi-agent arkitektur med Kunde- og Lager-agenter |

### Læring etter eksempeltype

> **📌 Lokale vs. Eksterne eksempler:**  
> **Lokale eksempler** (i dette repoet) = Klare til umiddelbar bruk  
> **Eksterne eksempler** (Azure Samples) = Klon fra lenkede repositorier

#### Lokale eksempler (Klar til bruk)
- [**Retail Multi-Agent Solution**](examples/retail-scenario.md) - Fullstendig produksjonsklar implementasjon med ARM-maler
  - Multi-agent arkitektur (Kunde + Lager-agenter)
  - Omfattende overvåking og evaluering
  - Ett-klikks distribusjon via ARM-mal

#### Lokale eksempler - Container applikasjoner (Kapitler 2-5)
**Omfattende eksempler på containerdistribusjon i dette depotet:**
- [**Container App Eksempler**](examples/container-app/README.md) - Fullstendig guide til containeriserte distribusjoner
  - [Enkel Flask API](../../examples/container-app/simple-flask-api) - Grunnleggende REST API med scale-to-zero
  - [Mikrotjenestearkitektur](../../examples/container-app/microservices) - Produksjonsklar multi-tjeneste distribusjon
  - Hurtigstart, Produksjon og Avanserte distribusjonsmønstre
  - Veiledning om overvåking, sikkerhet og kostnadsoptimalisering

#### Eksterne eksempler - Enkle applikasjoner (Kapitler 1-2)
**Klon disse Azure Samples repositoriene for å komme i gang:**
- [Enkel webapp - Node.js + MongoDB](https://github.com/Azure-Samples/todo-nodejs-mongo) - Grunnleggende distribusjonsmønstre
- [Statisk nettside - React SPA](https://github.com/Azure-Samples/todo-csharp-sql-swa-func) - Statisk innhold distribusjon
- [Container App - Python Flask](https://github.com/Azure-Samples/container-apps-store-api-microservice) - REST API distribusjon

#### Eksterne eksempler - Databaseintegrasjon (Kapitler 3-4)  
- [Databaseapp - C# + SQL](https://github.com/Azure-Samples/todo-csharp-sql) - Database-tilkoblingsmønstre
- [Functions + Cosmos DB](https://github.com/Azure-Samples/todo-python-mongo-swa-func) - Serverløse dataarbeidsflyter

#### Eksterne eksempler - Avanserte mønstre (Kapitler 4-8)
- [Java mikrotjenester](https://github.com/Azure-Samples/java-microservices-aca-lab) - Multi-tjenestearkitekturer
- [Container Apps Jobber](https://github.com/Azure-Samples/container-apps-jobs) - Bakgrunnsbehandling  
- [Enterprise ML Pipeline](https://github.com/Azure-Samples/mlops-v2) - Produksjonsklare ML-mønstre

### Eksterne mal-samlinger
- [**Offisiell AZD-mal-galleri**](https://azure.github.io/awesome-azd/) - Kuratert samling av offisielle og fellesskaps-baserte maler  
- [**Azure Developer CLI-maler**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - Microsoft Learn-mal-dokumentasjon  
- [**Eksempelkatalog**](examples/README.md) - Lokale læringseksempler med detaljerte forklaringer

---

## 📚 Læringsressurser & Referanser

### Rask referanse
- [**Kommandohurtigguide**](resources/cheat-sheet.md) - Viktige azd-kommandoer organisert per kapittel  
- [**Ordlist**](resources/glossary.md) - Azure- og azd-terminologi  
- [**FAQ**](resources/faq.md) - Vanlige spørsmål organisert per læringskapittel  
- [**Studieveiledning**](resources/study-guide.md) - Omfattende øvelser

### Praktiske workshops
- [**AI Workshop Lab**](docs/microsoft-foundry/ai-workshop-lab.md) - Gjør AI-løsningene dine deployerbare med AZD (2-3 timer)  
- [**Interaktiv workshop-veiledning**](workshop/README.md) - Nettleserbasert workshop med MkDocs og DevContainer-miljø  
- [**Strukturert læringsvei**](../../workshop/docs/instructions) - 7-trinns guidede øvelser (Oppdagelse → Distribusjon → Tilpasning)  
- [**AZD for nybegynnere Workshop**](workshop/README.md) - Fullstendige praktiske workshop-materialer med GitHub Codespaces-integrasjon

### Eksterne læringsressurser
- [Azure Developer CLI-dokumentasjon](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)  
- [Azure Architecture Center](https://learn.microsoft.com/en-us/azure/architecture/)  
- [Azure Pris-kalkulator](https://azure.microsoft.com/pricing/calculator/)  
- [Azure Status](https://status.azure.com/)

---

## 🔧 Rask feilrettingsguide

**Vanlige problemer nybegynnere møter og øyeblikkelige løsninger:**

### ❌ "azd: kommando ikke funnet"

```bash
# Installer AZD først
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Verifiser installasjonen
azd version
```
  
### ❌ "Ingen abonnement funnet" eller "Abonnement ikke satt"

```bash
# List tilgjengelige abonnementer
az account list --output table

# Angi standardabonnement
az account set --subscription "<subscription-id-or-name>"

# Angi for AZD-miljø
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Verifiser
az account show
```
  
### ❌ "Utilstrekkelig kvote" eller "Kvote overskredet"

```bash
# Prøv en annen Azure-region
azd env set AZURE_LOCATION "westus2"
azd up

# Eller bruk mindre SKUer i utvikling
# Rediger infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
  
### ❌ "azd up" feiler halvveis

```bash
# Alternativ 1: Rens og prøv igjen
azd down --force --purge
azd up

# Alternativ 2: Bare fiks infrastrukturen
azd provision

# Alternativ 3: Sjekk detaljerte logger
azd show
azd logs
```
  
### ❌ "Autentisering mislyktes" eller "Token utløpt"

```bash
# Autentiser på nytt
az logout
az login

azd auth logout
azd auth login

# Verifiser autentisering
az account show
```
  
### ❌ "Ressurs eksisterer allerede" eller navnekonflikter

```bash
# AZD genererer unike navn, men hvis konflikt:
azd down --force --purge

# Prøv da på nytt med et nytt miljø
azd env new dev-v2
azd up
```
  
### ❌ Mal-distribusjon tar for lang tid

**Normale ventetider:**  
- Enkel webapp: 5-10 minutter  
- App med database: 10-15 minutter  
- AI-applikasjoner: 15-25 minutter (OpenAI-provisjonering er treg)

```bash
# Sjekk fremgang
azd show

# Hvis fastlåst >30 minutter, sjekk Azure-portalen:
azd monitor
# Se etter mislykkede distribusjoner
```
  
### ❌ "Tillatelse nektet" eller "Forbidden"

```bash
# Sjekk din Azure-rolle
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Du trenger minst "Bidragsyter"-rollen
# Be din Azure-administrator om å gi:
# - Bidragsyter (for ressurser)
# - Brukertilgangsadministrator (for rolleoppgaver)
```
  
### ❌ Finner ikke URL for distribuert applikasjon

```bash
# Vis alle tjenesteendepunkter
azd show

# Eller åpne Azure-portalen
azd monitor

# Sjekk spesifikk tjeneste
azd env get-values
# Se etter *_URL variabler
```
  
### 📚 Fullstendige feilsøkingsressurser

- **Vanlige problemer-guide:** [Detaljerte løsninger](docs/troubleshooting/common-issues.md)  
- **AI-spesifikke problemer:** [AI-feilsøking](docs/troubleshooting/ai-troubleshooting.md)  
- **Feilsøkingsveiledning:** [Trinnvis feilsøking](docs/troubleshooting/debugging.md)  
- **Få hjelp:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🔧 Rask feilrettingsguide

**Vanlige problemer nybegynnere møter og øyeblikkelige løsninger:**

<details>
<summary><strong>❌ "azd: kommando ikke funnet"</strong></summary>

```bash
# Installer AZD først
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Verifiser installasjonen
azd version
```
</details>

<details>
<summary><strong>❌ "Ingen abonnement funnet" eller "Abonnement ikke satt"</strong></summary>

```bash
# List tilgjengelige abonnementer
az account list --output table

# Sett standardabonnement
az account set --subscription "<subscription-id-or-name>"

# Sett for AZD-miljø
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Verifiser
az account show
```
</details>

<details>
<summary><strong>❌ "Utilstrekkelig kvote" eller "Kvote overskredet"</strong></summary>

```bash
# Prøv forskjellige Azure-regioner
azd env set AZURE_LOCATION "westus2"
azd up

# Eller bruk mindre SKUer i utvikling
# Rediger infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>

<details>
<summary><strong>❌ "azd up" feiler halvveis</strong></summary>

```bash
# Alternativ 1: Rens og prøv igjen
azd down --force --purge
azd up

# Alternativ 2: Bare fiks infrastruktur
azd provision

# Alternativ 3: Sjekk detaljerte logger
azd show
azd logs
```
</details>

<details>
<summary><strong>❌ "Autentisering mislyktes" eller "Token utløpt"</strong></summary>

```bash
# Re-autentiser
az logout
az login

azd auth logout
azd auth login

# Verifiser autentisering
az account show
```
</details>

<details>
<summary><strong>❌ "Ressurs eksisterer allerede" eller navnekonflikter</strong></summary>

```bash
# AZD genererer unike navn, men ved konflikt:
azd down --force --purge

# Prøv igjen med et nytt miljø
azd env new dev-v2
azd up
```
</details>

<details>
<summary><strong>❌ Mal-distribusjon tar for lang tid</strong></summary>

**Normale ventetider:**  
- Enkel webapp: 5-10 minutter  
- App med database: 10-15 minutter  
- AI-applikasjoner: 15-25 minutter (OpenAI-provisjonering er treg)

```bash
# Sjekk fremdrift
azd show

# Hvis fast i >30 minutter, sjekk Azure-portalen:
azd monitor
# Se etter mislykkede distribusjoner
```
</details>

<details>
<summary><strong>❌ "Tillatelse nektet" eller "Forbidden"</strong></summary>

```bash
# Sjekk din Azure-rolle
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Du trenger minst rollen "Bidragsyter"
# Be Azure-administratoren din om å gi:
# - Bidragsyter (for ressurser)
# - Brukertilgangsadministrator (for rolleoppdragelser)
```
</details>

<details>
<summary><strong>❌ Finner ikke URL for distribuert applikasjon</strong></summary>

```bash
# Vis alle tjenesteendepunkter
azd show

# Eller åpne Azure Portal
azd monitor

# Sjekk spesifikk tjeneste
azd env get-values
# Se etter *_URL variabler
```
</details>

### 📚 Fullstendige feilsøkingsressurser

- **Vanlige problemer-guide:** [Detaljerte løsninger](docs/troubleshooting/common-issues.md)  
- **AI-spesifikke problemer:** [AI-feilsøking](docs/troubleshooting/ai-troubleshooting.md)  
- **Feilsøkingsveiledning:** [Trinnvis feilsøking](docs/troubleshooting/debugging.md)  
- **Få hjelp:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🎓 Kursfullføring & Sertifisering

### Fremdriftssporing
Følg med på læringsfremgangen din gjennom hvert kapittel:

- [ ] **Kapittel 1**: Grunnlag & Rask start ✅  
- [ ] **Kapittel 2**: AI-først Utvikling ✅  
- [ ] **Kapittel 3**: Konfigurasjon & Autentisering ✅  
- [ ] **Kapittel 4**: Infrastruktur som kode & Distribusjon ✅  
- [ ] **Kapittel 5**: Multi-Agent AI-løsninger ✅  
- [ ] **Kapittel 6**: Forhåndsvalidering & Planlegging før distribusjon ✅  
- [ ] **Kapittel 7**: Feilsøking & Debugging ✅  
- [ ] **Kapittel 8**: Produksjon & Enterprise-mønstre ✅

### Læringsverifisering  
Etter å ha fullført hvert kapittel, verifiser kunnskapen din ved å:  
1. **Praktisk øvelse**: Fullfør kapittelets praktiske distribusjon  
2. **Kunnskapssjekk**: Gå gjennom FAQ-seksjonen for kapittelet ditt  
3. **Fellesskapsdiskusjon**: Del erfaringen din i Azure Discord  
4. **Neste kapittel**: Gå videre til neste kompleksitetsnivå

### Fordeler ved kursfullføring  
Når du har fullført alle kapitlene, vil du ha:  
- **Produksjonserfaring**: Deployert ekte AI-applikasjoner til Azure  
- **Profesjonelle ferdigheter**: Enterprise-klare distribusjonsmuligheter  
- **Fellesskapsgjenkjenning**: Aktivt medlem av Azure-utviklerfellesskapet  
- **Karriereutvikling**: Etterspurt AZD- og AI-distribusjonsekspertise

---

## 🤝 Fellesskap & Support

### Få hjelp & support  
- **Tekniske problemer**: [Rapporter feil og be om funksjoner](https://github.com/microsoft/azd-for-beginners/issues)  
- **Læringsspørsmål**: [Microsoft Azure Discord-fellesskapet](https://discord.gg/microsoft-azure) og [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)  
- **AI-spesifikk hjelp**: Bli med i [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)  
- **Dokumentasjon**: [Offisiell Azure Developer CLI-dokumentasjon](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)

### Fellesskapsinnsikt fra Microsoft Foundry Discord

**Nylige avstemningsresultater fra #Azure-kanalen:**  
- **45 %** av utviklere vil bruke AZD for AI-arbeidsbelastninger  
- **Topp utfordringer**: Multi-tjeneste-distribusjoner, håndtering av legitimasjon, produksjonsklarhet  
- **Mest etterspurt**: AI-spesifikke maler, feilsøkingsguider, beste praksis

**Bli med i vårt fellesskap for å:**  
- Dele dine erfaringer med AZD + AI og få hjelp  
- Få tidlig tilgang til nye AI-maler  
- Bidra til beste praksis for AI-distribusjon  
- Påvirke fremtidig AI + AZD-funksjonsutvikling

### Bidra til kurset  
Vi ønsker bidrag velkommen! Vennligst les vår [Bidragsveiledning](CONTRIBUTING.md) for detaljer om:  
- **Forbedringer av innhold**: Forbedre eksisterende kapitler og eksempler  
- **Nye eksempler**: Legg til virkelige scenarier og maler  
- **Oversettelse**: Hjelp til å vedlikeholde fler-språks støtte  
- **Feilrapporter**: Forbedre nøyaktighet og klarhet  
- **Fellesskapsstandarder**: Følg våre inkluderende retningslinjer

---

## 📄 Kursinformasjon

### Lisens  
Dette prosjektet er lisensiert under MIT-lisensen - se [LICENSE](../../LICENSE)-filen for detaljer.

### Relaterte Microsoft-læringsressurser

Vårt team produserer andre omfattende læringskurs:

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

### Generativ AI-serie  
[![Generative AI for Beginners](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)  
[![Generative AI (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)  
[![Generative AI (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)  
[![Generative AI (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---

### Grunnleggende læring  
[![ML for Beginners](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![Data Science for Beginners](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![AI for Beginners](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Cybersecurity for Beginners](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Web Dev for Beginners](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![IoT for Beginners](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![XR Development for Beginners](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Copilot-serien
[![Copilot for AI Paired Programming](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![Copilot for C#/.NET](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Copilot Adventure](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ Kursnavigasjon

**🚀 Klar til å begynne å lære?**

**Nybegynnere**: Start med [Kapittel 1: Grunnlag og Rask start](../..)  
**AI-utviklere**: Hopp til [Kapittel 2: AI-først utvikling](../..)  
**Erfarne utviklere**: Begynn med [Kapittel 3: Konfigurasjon og autentisering](../..)

**Neste steg**: [Begynn Kapittel 1 - AZD-grunnleggende](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Ansvarsfraskrivelse**:
Dette dokumentet er oversatt ved bruk av AI-oversettelsestjenesten [Co-op Translator](https://github.com/Azure/co-op-translator). Selv om vi streber etter nøyaktighet, vennligst vær oppmerksom på at automatiske oversettelser kan inneholde feil eller unøyaktigheter. Det opprinnelige dokumentet på dets eget språk bør anses som den autoritative kilden. For kritisk informasjon anbefales profesjonell menneskelig oversettelse. Vi er ikke ansvarlige for eventuelle misforståelser eller feiltolkninger som oppstår ved bruk av denne oversettelsen.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->