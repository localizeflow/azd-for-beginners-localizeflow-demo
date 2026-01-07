<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T14:10:06+00:00",
  "source_file": "README.md",
  "language_code": "tl"
}
-->
> Tala: Patuloy na ina-update ang dokumentasyong ito upang ipakita ang pinakabagong mga pagbabago.

> ⚠️ Ang repositoryong ito ay isang demo na ginawa upang ipakita
> awtomatikong lokalisisayon ng dokumentasyon gamit ang Localizeflow.
>
> Ang orihinal na nilalaman ay batay sa
> proyekto ng Microsoft na "AZD para sa mga Baguhan".


# AZD Para sa mga Baguhan: Isang Istrakturadong Paglalakbay sa Pag-aaral

![AZD-for-beginners](../../translated_images/azdbeginners.5527441dd9f74068.tl.png) 

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## Pagsisimula sa Kurso na Ito

Sundin ang mga hakbang na ito upang simulan ang iyong paglalakbay sa pag-aaral ng AZD:

1. **I-fork ang Repository**: I-click ang [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)
2. **I-clone ang Repository**: `git clone https://github.com/microsoft/azd-for-beginners.git`
3. **Sumali sa Komunidad**: [Azure Discord Communities](https://discord.com/invite/ByRwuEEgH4) para sa ekspertong suporta
4. **Pumili ng Landas ng Pag-aaral**: Piliin ang isang kabanata sa ibaba na umaangkop sa iyong antas ng karanasan

### Suporta sa Maramihang Wika

#### Awtomatikong Mga Pagsasalin (Laging Napapanahon)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](./README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Mas Gusto Mo Bang Mag-Clone Lokal?**

> Kasama sa repositoryong ito ang mahigit 50 na pagsasalin sa wika na malaki ang dagdag sa laki ng download. Upang mag-clone nang walang mga pagsasalin, gamitin ang sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Nagbibigay ito sa iyo ng lahat ng kailangan mo upang makumpleto ang kurso nang mas mabilis ang pag-download.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## Pangkalahatang-ideya ng Kurso

Masterin ang Azure Developer CLI (azd) sa pamamagitan ng istrakturadong mga kabanata na idinisenyo para sa progresibong pag-aaral. **Espesyal na pokus sa pag-deploy ng AI application gamit ang integrasyon ng Microsoft Foundry.**

### Bakit Mahalaga ang Kurso na Ito para sa mga Makabagong Developer

Batay sa mga pananaw mula sa Microsoft Foundry Discord community, **45% ng mga developer ay nais gamitin ang AZD para sa mga AI workloads** ngunit nahaharap sa mga hamon tulad ng:
- Kumplikadong multi-service AI architectures
- Mga pinakamahusay na gawi sa production AI deployment  
- Integrasyon at pagsasaayos ng Azure AI service
- Pag-optimize ng gastos para sa AI workloads
- Pag-troubleshoot ng mga ispesipikong isyu sa AI deployment

### Mga Layunin sa Pag-aaral

Sa pagtatapos ng kursong ito, magagawa mong:
- **Masterin ang mga Pangunahing Kaalaman sa AZD**: Mga pangunahing konsepto, pag-install, at pagsasaayos
- **Mag-deploy ng AI Applications**: Gamitin ang AZD kasama ang Microsoft Foundry services
- **Ipatupad ang Infrastructure as Code**: Pamahalaan ang Azure resources gamit ang Bicep templates
- **Mag-troubleshoot ng Deployment**: Lutasin ang mga karaniwang problema at debug issues
- **I-optimize para sa Production**: Seguridad, scaling, monitoring, at cost management
- **Gumawa ng Multi-Agent Solutions**: Mag-deploy ng komplikadong AI architectures

## 📚 Mga Kabanata ng Pag-aaral

*Pumili ng landas sa pag-aaral base sa antas ng karanasan at mga layunin*

### 🚀 Kabanata 1: Pundasyon at Mabilis na Pagsisimula
**Mga Kinakailangan**: Azure subscription, batayang kaalaman sa command line  
**Tagal**: 30-45 minuto  
**Kumplikado**: ⭐

#### Ano ang Matututuhan Mo
- Pag-unawa sa mga pangunahing kaalaman ng Azure Developer CLI
- Pag-install ng AZD sa iyong platform
- Ang iyong unang matagumpay na deployment

#### Mga Mapagkukunan ng Pag-aaral
- **🎯 Simulan Dito**: [Ano ang Azure Developer CLI?](../..)
- **📖 Teorya**: [AZD Basics](docs/getting-started/azd-basics.md) - Mga pangunahing konsepto at termino
- **⚙️ Setup**: [Pag-install at Setup](docs/getting-started/installation.md) - Mga gabay para sa bawat platform
- **🛠️ Hands-On**: [Ang Iyong Unang Proyekto](docs/getting-started/first-project.md) - Step-by-step tutorial
- **📋 Quick Reference**: [Command Cheat Sheet](resources/cheat-sheet.md)

#### Praktikal na Ehersisyo
```bash
# Mabilis na tsek ng pag-install
azd version

# I-deploy ang iyong unang aplikasyon
azd init --template todo-nodejs-mongo
azd up
```

**💡 Kinalabasan ng Kabanata**: Matagumpay na maideploy ang isang simpleng web application sa Azure gamit ang AZD

**✅ Patunay ng Tagumpay:**
```bash
# Pagkatapos makumpleto ang Kabanata 1, dapat mong magawa ang mga sumusunod:
azd version              # Ipinapakita ang naka-install na bersyon
azd init --template todo-nodejs-mongo  # Inisyalisa ang proyekto
azd up                  # Nagde-deploy sa Azure
azd show                # Ipinapakita ang URL ng tumatakbong app
# Nagbubukas ang aplikasyon sa browser at gumagana
azd down --force --purge  # Nililinis ang mga resources
```

**📊 Inilaan na Oras:** 30-45 minuto  
**📈 Antas ng Kakayahan Pagkatapos:** Kayang mag-deploy ng mga basic na aplikasyon nang mag-isa

**✅ Patunay ng Tagumpay:**
```bash
# Pagkatapos makumpleto ang Kabanata 1, dapat mong magawa ang mga sumusunod:
azd version              # Ipinapakita ang naka-install na bersyon
azd init --template todo-nodejs-mongo  # Inaayos ang proyekto
azd up                  # Nagpapadala sa Azure
azd show                # Ipinapakita ang URL ng tumatakbong app
# Binubuksan ang aplikasyon sa browser at gumagana
azd down --force --purge  # Nililinis ang mga resources
```

**📊 Inilaan na Oras:** 30-45 minuto  
**📈 Antas ng Kakayahan Pagkatapos:** Kayang mag-deploy ng mga basic na aplikasyon nang mag-isa

---

### 🤖 Kabanata 2: AI-First Development (Inirerekomenda para sa mga AI Developer)
**Mga Kinakailangan**: Natapos ang Kabanata 1  
**Tagal**: 1-2 oras  
**Kumplikado**: ⭐⭐

#### Ano ang Matututuhan Mo
- Integrasyon ng Microsoft Foundry sa AZD
- Pag-deploy ng AI-powered na mga aplikasyon
- Pag-unawa sa mga pagsasaayos ng AI service

#### Mga Mapagkukunan ng Pag-aaral
- **🎯 Simulan Dito**: [Integrasyon ng Microsoft Foundry](docs/microsoft-foundry/microsoft-foundry-integration.md)
- **📖 Mga Pattern**: [Pag-deploy ng AI Model](docs/microsoft-foundry/ai-model-deployment.md) - Deploy at pamahalaan ang AI models
- **🛠️ Workshop**: [AI Workshop Lab](docs/microsoft-foundry/ai-workshop-lab.md) - Ihanda ang iyong AI solutions para sa AZD
- **🎥 Interactive Guide**: [Mga Materyales sa Workshop](workshop/README.md) - Pag-aaral gamit ang browser na may MkDocs * DevContainer Environment
- **📋 Mga Template**: [Microsoft Foundry Templates](../..)
- **📝 Mga Halimbawa**: [Halimbawa ng AZD Deployment](examples/README.md)

#### Praktikal na Ehersisyo
```bash
# I-deploy ang iyong unang AI na aplikasyon
azd init --template azure-search-openai-demo
azd up

# Subukan ang karagdagang mga AI template
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```

**💡 Kinalabasan ng Kabanata**: Mag-deploy at mag-configure ng AI-powered chat application na may RAG capabilities

**✅ Patunay ng Tagumpay:**
```bash
# Pagkatapos ng Kabanata 2, dapat mong magawa ang mga sumusunod:
azd init --template azure-search-openai-demo
azd up
# Subukan ang interface ng AI chat
# Magtanong at makakuha ng mga sagot na pinapagana ng AI na may mga sanggunian
# Tiyakin na gumagana ang integrasyon ng paghahanap
azd monitor  # Suriin kung nagpapakita ang Application Insights ng telemetry
azd down --force --purge
```

**📊 Inilaan na Oras:** 1-2 oras  
**📈 Antas ng Kakayahan Pagkatapos:** Kayang mag-deploy at mag-configure ng production-ready na AI applications  
**💰 Kamalayan sa Gastos:** Nauunawaan ang $80-150/buwan na gastos para sa dev, $300-3500/buwan para sa production

#### 💰 Mga Pagsasaalang-alang sa Gastos para sa AI Deployments

**Development Environment (Tinatayang $80-150/buwan):**
- Azure OpenAI (Pay-as-you-go): $0-50/buwan (batay sa token usage)
- AI Search (Basic tier): $75/buwan
- Container Apps (Consumption): $0-20/buwan
- Storage (Standard): $1-5/buwan

**Production Environment (Tinatayang $300-3,500+/buwan):**
- Azure OpenAI (PTU para sa consistent performance): $3,000+/buwan O Pay-as-you-go sa mataas na volume
- AI Search (Standard tier): $250/buwan
- Container Apps (Dedicated): $50-100/buwan
- Application Insights: $5-50/buwan
- Storage (Premium): $10-50/buwan

**💡 Mga Tip para sa Pag-optimize ng Gastos:**
- Gamitin ang **Free Tier** ng Azure OpenAI para sa pag-aaral (kasama ang 50,000 tokens/buwan)
- Patakbuhin ang `azd down` upang i-deallocate ang mga resource kapag hindi aktibong nagde-develop
- Magsimula sa consumption-based billing, i-upgrade lang sa PTU para sa production
- Gamitin ang `azd provision --preview` upang tantiyahin ang gastos bago mag-deploy
- I-enable ang auto-scaling: magbayad lamang sa aktwal na paggamit

**Pagsubaybay ng Gastos:**
```bash
# Suriin ang tinantyang buwanang gastos
azd provision --preview

# Subaybayan ang aktwal na gastos sa Azure Portal
az consumption budget list --resource-group <your-rg>
```

---

### ⚙️ Kabanata 3: Pagsasaayos at Pagpapatunay
**Mga Kinakailangan**: Natapos ang Kabanata 1  
**Tagal**: 45-60 minuto  
**Kumplikado**: ⭐⭐

#### Ano ang Matututuhan Mo
- Pagsasaayos at pamamahala ng environment
- Pinakamahusay na kasanayan sa authentication at seguridad
- Pangalan at organisasyon ng mga resource

#### Mga Mapagkukunan ng Pag-aaral
- **📖 Pagsasaayos**: [Configuration Guide](docs/getting-started/configuration.md) - Setup ng environment
- **🔐 Seguridad**: [Authentication patterns and managed identity](docs/getting-started/authsecurity.md) - Mga pattern ng authentication
- **📝 Mga Halimbawa**: [Database App Example](examples/database-app/README.md) - Mga halimbawa ng AZD Database

#### Praktikal na Ehersisyo
- Mag-configure ng maraming environment (dev, staging, prod)
- Mag-set up ng managed identity authentication
- Magpatupad ng mga environment-specific configuration

**💡 Kinalabasan ng Kabanata**: Pamahalaan ang maraming environment nang may tamang authentication at seguridad

---

### 🏗️ Kabanata 4: Infrastructure as Code at Deployment
**Mga Kinakailangan**: Natapos ang Kabanata 1-3  
**Tagal**: 1-1.5 oras  
**Kumplikado**: ⭐⭐⭐

#### Ano ang Matututuhan Mo
- Mga advanced na pattern sa deployment
- Infrastructure as Code gamit ang Bicep
- Mga estratehiya sa pag-provision ng resource

#### Mga Mapagkukunan ng Pag-aaral
- **📖 Deployment**: [Deployment Guide](docs/deployment/deployment-guide.md) - Kumpletong workflows
- **🏗️ Provisioning**: [Provisioning Resources](docs/deployment/provisioning.md) - Pamamahala ng Azure resources
- **📝 Mga Halimbawa**: [Container App Example](../../examples/container-app) - Mga containerized deployment

#### Praktikal na Ehersisyo
- Gumawa ng custom Bicep templates
- Mag-deploy ng multi-service applications
- Magpatupad ng blue-green deployment strategies

**💡 Kinalabasan ng Kabanata**: Ma-deploy ang mga komplikadong multi-service applications gamit ang custom infrastructure templates

---
### 🎯 Kabanata 5: Mga Multi-Agent AI Solutions (Advanced)
**Mga Kinakailangan**: Natapos ang Mga Kabanata 1-2  
**Tagal**: 2-3 oras  
**Kumplikado**: ⭐⭐⭐⭐

#### Ano ang Matututunan Mo
- Mga pattern ng multi-agent architecture
- Orkestrasyon at koordinasyon ng mga ahente
- Mga AI deployment na handa sa produksyon

#### Mga Learning Resources
- **🤖 Tampok na Proyekto**: [Retail Multi-Agent Solution](examples/retail-scenario.md) - Kumpletong implementasyon
- **🛠️ ARM Templates**: [ARM Template Package](../../examples/retail-multiagent-arm-template) - Isang-click na deployment
- **📖 Arkitektura**: [Multi-agent coordination patterns](/docs/pre-deployment/coordination-patterns.md) - Mga pattern

#### Mga Praktikal na Ehersisyo
```bash
# I-deploy ang kumpletong retail na multi-agent solution
cd examples/retail-multiagent-arm-template
./deploy.sh

# Tuklasin ang mga configuration ng ahente
az deployment group show --resource-group <rg-name> --name <deployment-name>
```

**💡 Kinalabasan ng Kabanata**: Mag-deploy at pamahalaan ang production-ready na multi-agent AI solution gamit ang Customer at Inventory agents

---

### 🔍 Kabanata 6: Pre-Deployment Validation & Planning
**Mga Kinakailangan**: Natapos ang Kabanata 4  
**Tagal**: 1 oras  
**Kumplikado**: ⭐⭐

#### Ano ang Matututunan Mo
- Pagpaplano sa kapasidad at pag-validate ng mga resource
- Mga estratehiya sa pagpili ng SKU
- Pre-flight checks at automation

#### Mga Learning Resources
- **📊 Pagpaplano**: [Capacity Planning](docs/pre-deployment/capacity-planning.md) - Pag-validate ng resource
- **💰 Pagpili**: [SKU Selection](docs/pre-deployment/sku-selection.md) - Mga murang pagpipilian
- **✅ Validation**: [Pre-flight Checks](docs/pre-deployment/preflight-checks.md) - Automated scripts

#### Mga Praktikal na Ehersisyo
- Patakbuhin ang mga capacity validation script
- I-optimize ang mga pagpili ng SKU para sa gastos
- Ipatupad ang automated pre-deployment checks

**💡 Kinalabasan ng Kabanata**: I-validate at i-optimize ang mga deployment bago isagawa

---

### 🚨 Kabanata 7: Troubleshooting & Debugging
**Mga Kinakailangan**: Natapos ang alin mang deployment chapter  
**Tagal**: 1-1.5 oras  
**Kumplikado**: ⭐⭐

#### Ano ang Matututunan Mo
- Sistematikong mga pamamaraan sa debugging
- Mga karaniwang isyu at solusyon
- Troubleshooting na partikular sa AI

#### Mga Learning Resources
- **🔧 Mga Karaniwang Isyu**: [Common Issues](docs/troubleshooting/common-issues.md) - FAQ at mga solusyon
- **🕵️ Gabay sa Debugging**: [Debugging Guide](docs/troubleshooting/debugging.md) - Step-by-step na estratehiya
- **🤖 AI Issues**: [AI-Specific Troubleshooting](docs/troubleshooting/ai-troubleshooting.md) - Mga problema sa AI service

#### Mga Praktikal na Ehersisyo
- Diagnose ang mga pagkabigo sa deployment
- Lutasin ang mga isyu sa authentication
- Debug ang konektibidad ng AI service

**💡 Kinalabasan ng Kabanata**: Magsariling diagnose at lutasin ang mga karaniwang isyu sa deployment

---

### 🏢 Kabanata 8: Mga Pattern sa Produksyon at Enterprise
**Mga Kinakailangan**: Natapos ang Mga Kabanata 1-4  
**Tagal**: 2-3 oras  
**Kumplikado**: ⭐⭐⭐⭐

#### Ano ang Matututunan Mo
- Mga estratehiya sa production deployment
- Mga pattern ng seguridad para sa enterprise
- Pagsubaybay at pag-optimize ng gastos

#### Mga Learning Resources
- **🏭 Produksyon**: [Production AI Best Practices](docs/microsoft-foundry/production-ai-practices.md) - Mga pattern para sa enterprise
- **📝 Mga Halimbawa**: [Microservices Example](../../examples/microservices) - Kumplikadong arkitektura
- **📊 Pagsubaybay**: [Application Insights integration](docs/pre-deployment/application-insights.md) - Pagsubaybay

#### Mga Praktikal na Ehersisyo
- Ipatupad ang mga pattern ng seguridad para sa enterprise
- Mag-setup ng komprehensibong pagsubaybay
- Mag-deploy sa produksyon na may tamang pamamahala

**💡 Kinalabasan ng Kabanata**: Mag-deploy ng enterprise-ready na mga aplikasyon na may kumpletong kakayahan sa produksyon

---

## 🎓 Workshop Overview: Hands-On Learning Experience

> **⚠️ STATUS NG WORKSHOP: Aktibong Pag-unlad**  
> Ang mga materyales ng workshop ay kasalukuyang dine-develop at pinapabuti. Ang mga pangunahing module ay gumagana, ngunit may ilang advanced na seksyon na hindi pa kumpleto. Aktibong nagtatrabaho kami upang matapos ang lahat ng nilalaman. [Subaybayan ang progreso →](workshop/README.md)

### Interactive Workshop Materials
**Komprehensibong hands-on na pag-aaral gamit ang browser-based tools at mga guided na ehersisyo**

Nagbibigay ang aming mga materyales sa workshop ng structured, interactive na karanasan sa pag-aaral na nagpapakumpleto sa chapter-based curriculum sa itaas. Ang workshop ay idinisenyo para sa self-paced learning at instructor-led sessions.

#### 🛠️ Mga Tampok ng Workshop
- **Browser-Based Interface**: Kumpletong MkDocs-powered workshop na may search, copy, at mga tema
- **GitHub Codespaces Integration**: Isang-click na pag-setup ng development environment
- **Structured Learning Path**: 7-step guided exercises (3.5 oras kabuuan)
- **Discovery → Deployment → Customization**: Progressive methodology
- **Interactive DevContainer Environment**: Pre-configured na mga tool at dependencies

#### 📚 Workshop Structure
Sinasunod ng workshop ang **Discovery → Deployment → Customization** na metodolohiya:

1. **Discovery Phase** (45 minuto)
   - Suriin ang Microsoft Foundry templates at mga serbisyo
   - Unawain ang mga pattern ng multi-agent architecture
   - Repasuhin ang mga kinakailangan at prerequisites sa deployment

2. **Deployment Phase** (2 oras)
   - Hands-on na pag-deploy ng AI applications gamit ang AZD
   - I-configure ang Azure AI services at endpoints
   - Ipatupad ang mga pattern ng seguridad at authentication

3. **Customization Phase** (45 minuto)
   - Baguhin ang mga aplikasyon para sa mga tiyak na kaso ng paggamit
   - I-optimize para sa production deployment
   - Ipatupad ang pagsubaybay at pamamahala ng gastos

#### 🚀 Pagsisimula sa Workshop
```bash
# Opsyon 1: GitHub Codespaces (Inirerekomenda)
# I-click ang "Code" → "Create codespace on main" sa repository

# Opsyon 2: Lokal na Pag-unlad
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# Sundan ang mga tagubilin sa setup sa workshop/README.md
```

#### 🎯 Mga Kinalabasan ng Pag-aaral sa Workshop
Sa pagtatapos ng workshop, ang mga kalahok ay:
- **Maka-deploy ng Production AI Applications**: Gumamit ng AZD kasama ang mga Microsoft Foundry services
- **Maging Master sa Multi-Agent Architectures**: Mag-implementa ng coordinated AI agent solutions
- **Magtamo ng Security Best Practices**: Mag-configure ng authentication at access control
- **I-optimize para sa Sukat**: Magdisenyo ng cost-effective at performant na deployments
- **Mag-troubleshoot ng Mga Deployment**: Malutas ang mga karaniwang isyu nang mag-isa

#### 📖 Mga Resources ng Workshop
- **🎥 Interactive Guide**: [Workshop Materials](workshop/README.md) - Browser-based na learning environment
- **📋 Step-by-Step Instructions**: [Guided Exercises](../../workshop/docs/instructions) - Detalyadong walkthroughs
- **🛠️ AI Workshop Lab**: [AI Workshop Lab](docs/microsoft-foundry/ai-workshop-lab.md) - Mga ehersisyong nakatuon sa AI
- **💡 Quick Start**: [Workshop Setup Guide](workshop/README.md#quick-start) - Configuration ng environment

**Perpekto para sa**: Corporate training, mga kurso sa unibersidad, self-paced learning, at mga developer bootcamp.

---

## 📖 Ano ang Azure Developer CLI?

Ang Azure Developer CLI (azd) ay isang developer-centric command-line interface na nagpapabilis ng proseso ng pagbuo at pag-deploy ng mga aplikasyon sa Azure. Nagbibigay ito ng:

- **Template-based deployments** - Gumamit ng mga pre-built na template para sa karaniwang mga pattern ng aplikasyon
- **Infrastructure as Code** - Pamahalaan ang Azure resources gamit ang Bicep o Terraform  
- **Integrated workflows** - Makinis na provisioning, deployment, at pagsubaybay ng mga aplikasyon
- **Developer-friendly** - Na-optimize para sa produktibidad at karanasan ng developer

### **AZD + Microsoft Foundry: Perpekto para sa AI Deployments**

**Bakit AZD para sa AI Solutions?** Tinugunan ng AZD ang mga pangunahing hamon na hinaharap ng mga AI developer:

- **AI-Ready Templates** - Pre-configured na mga template para sa Azure OpenAI, Cognitive Services, at ML workloads
- **Secure AI Deployments** - Built-in na mga pattern ng seguridad para sa AI services, API keys, at mga model endpoints  
- **Production AI Patterns** - Mga best practice para sa scalable at cost-effective na AI application deployments
- **End-to-End AI Workflows** - Mula sa pagbuo ng modelo hanggang sa production deployment na may tamang pagsubaybay
- **Cost Optimization** - Matalinong alokasyon ng resource at mga estratehiya sa scaling para sa AI workloads
- **Microsoft Foundry Integration** - Makinis na koneksyon sa Microsoft Foundry model catalog at endpoints

---

## 🎯 Mga Library ng Template at Halimbawa

### Tampok: Microsoft Foundry Templates
**Magsimula dito kung magde-deploy ka ng AI applications!**

> **Tandaan:** Ipinapakita ng mga template na ito ang iba't ibang mga AI pattern. Ang ilan ay mga external Azure Samples, ang iba ay mga lokal na implementasyon.

| Template | Kabanata | Kumplikado | Mga Serbisyo | Uri |
|----------|---------|------------|----------|------|
| [**Get started with AI chat**](https://github.com/Azure-Samples/get-started-with-ai-chat) | Kabanata 2 | ⭐⭐ | AzureOpenAI + Azure AI Model Inference API + Azure AI Search + Azure Container Apps + Application Insights | External |
| [**Get started with AI agents**](https://github.com/Azure-Samples/get-started-with-ai-agents) | Kabanata 2 | ⭐⭐ | Azure AI Agent Service + AzureOpenAI + Azure AI Search + Azure Container Apps + Application Insights| External |
| [**Azure Search + OpenAI Demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Kabanata 2 | ⭐⭐ | AzureOpenAI + Azure AI Search + App Service + Storage | External |
| [**OpenAI Chat App Quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Kabanata 2 | ⭐ | AzureOpenAI + Container Apps + Application Insights | External |
| [**Agent OpenAI Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Kabanata 5 | ⭐⭐⭐ | AzureOpenAI + Azure Functions + Prompty | External |
| [**Contoso Chat RAG**](https://github.com/Azure-Samples/contoso-chat) | Kabanata 8 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Cosmos DB + Container Apps | External |
| [**Retail Multi-Agent Solution**](examples/retail-scenario.md) | Kabanata 5 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Storage + Container Apps + Cosmos DB | **Lokal** |

### Tampok: Kumpletong Mga Scenario sa Pag-aaral
**Production-ready na mga template ng aplikasyon na naka-map sa mga learning chapter**

| Template | Learning Chapter | Kumplikado | Pangunahing Aral |
|----------|------------------|------------|--------------|
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Kabanata 2 | ⭐ | Mga pangunahing pattern sa AI deployment |
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Kabanata 2 | ⭐⭐ | RAG implementation gamit ang Azure AI Search |
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | Kabanata 4 | ⭐⭐ | Pagsasama ng Document Intelligence |
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Kabanata 5 | ⭐⭐⭐ | Agent framework at pagtawag sa function |
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | Kabanata 8 | ⭐⭐⭐ | Enterprise AI orchestration |
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | Kabanata 5 | ⭐⭐⭐⭐ | Multi-agent architecture gamit ang Customer at Inventory agents |

### Pag-aaral Batay sa Uri ng Halimbawa

> **📌 Lokal vs. External na Mga Halimbawa:**  
> **Lokal na Mga Halimbawa** (sa repo na ito) = Agad magagamit  
> **External na Mga Halimbawa** (Azure Samples) = I-clone mula sa mga naka-link na repositoryo

#### Lokal na Mga Halimbawa (Agad magagamit)
- [**Retail Multi-Agent Solution**](examples/retail-scenario.md) - Kumpletong production-ready na implementasyon kasama ang ARM templates
  - Multi-agent architecture (Customer + Inventory agents)
  - Komprehensibong pagsubaybay at ebalwasyon
  - Isang-click na deployment gamit ang ARM template

#### Lokal na Mga Halimbawa - Mga Container Application (Mga Kabanata 2-5)
**Komprehensibong mga halimbawa ng container deployment sa repositoryong ito:**
- [**Container App Examples**](examples/container-app/README.md) - Kumpletong gabay sa containerized deployments
  - [Simple Flask API](../../examples/container-app/simple-flask-api) - Pangunahing REST API na scale-to-zero
  - [Microservices Architecture](../../examples/container-app/microservices) - Production-ready na multi-service deployment
  - Quick Start, Production, at Advanced deployment patterns
  - Gabay sa pagsubaybay, seguridad, at pag-optimize ng gastos

#### External na Mga Halimbawa - Mga Simpleng Aplikasyon (Mga Kabanata 1-2)
**I-clone ang mga Azure Samples na repositoryo na ito upang makapagsimula:**
- [Simple Web App - Node.js + MongoDB](https://github.com/Azure-Samples/todo-nodejs-mongo) - Mga pangunahing pattern ng deployment
- [Static Website - React SPA](https://github.com/Azure-Samples/todo-csharp-sql-swa-func) - Static content deployment
- [Container App - Python Flask](https://github.com/Azure-Samples/container-apps-store-api-microservice) - REST API deployment

#### External na Mga Halimbawa - Pagsasama ng Database (Mga Kabanata 3-4)  
- [Database App - C# + SQL](https://github.com/Azure-Samples/todo-csharp-sql) - Mga pattern ng database connectivity
- [Functions + Cosmos DB](https://github.com/Azure-Samples/todo-python-mongo-swa-func) - Serverless na workflow ng data

#### External na Mga Halimbawa - Advanced na Mga Pattern (Mga Kabanata 4-8)
- [Java Microservices](https://github.com/Azure-Samples/java-microservices-aca-lab) - Mga architecture ng multi-service
- [Container Apps Jobs](https://github.com/Azure-Samples/container-apps-jobs) - Background processing  
- [Enterprise ML Pipeline](https://github.com/Azure-Samples/mlops-v2) - Production-ready na mga pattern ng ML

### Koleksyon ng External na Template
- [**Opisyal na AZD Template Gallery**](https://azure.github.io/awesome-azd/) - Piniling koleksyon ng opisyal at komunidad na mga template  
- [**Azure Developer CLI Templates**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - Dokumentasyon ng Microsoft Learn para sa mga template  
- [**Directory ng mga Halimbawa**](examples/README.md) - Lokal na mga halimbawa ng pag-aaral na may detalyadong mga paliwanag  

---

## 📚 Mga Mapagkukunan sa Pag-aaral at Mga Sanggunian

### Mabilisang Sanggunian
- [**Command Cheat Sheet**](resources/cheat-sheet.md) - Mahalagang mga utos ng azd na inayos ayon sa kabanata  
- [**Glossary**](resources/glossary.md) - Terminolohiya ng Azure at azd    
- [**FAQ**](resources/faq.md) - Mga karaniwang tanong na inayos ayon sa kabanata ng pag-aaral  
- [**Study Guide**](resources/study-guide.md) - Komprehensibong mga pagsasanay  

### Mga Hands-On Workshop
- [**AI Workshop Lab**](docs/microsoft-foundry/ai-workshop-lab.md) - Gawing AZD-deployable ang iyong mga solusyong AI (2-3 oras)  
- [**Interactive Workshop Guide**](workshop/README.md) - Browser-based na workshop gamit ang MkDocs at DevContainer Environment  
- [**Structured Learning Path**](../../workshop/docs/instructions) - 7-hakbang na gabay na mga pagsasanay (Discovery → Deployment → Customization)  
- [**AZD Para sa mga Baguhan Workshop**](workshop/README.md) - Kumpletong mga materyales ng hands-on na workshop na may integrasyon ng GitHub Codespaces  

### Mga Panlabas na Mapagkukunan sa Pag-aaral
- [Azure Developer CLI Documentation](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)
- [Azure Architecture Center](https://learn.microsoft.com/en-us/azure/architecture/)
- [Azure Pricing Calculator](https://azure.microsoft.com/pricing/calculator/)
- [Azure Status](https://status.azure.com/)

---

## 🔧 Mabilisang Gabay sa Pag-troubleshoot

**Mga karaniwang isyu na nararanasan ng mga baguhan at agarang mga solusyon:**

### ❌ "azd: command not found"

```bash
# I-install muna ang AZD
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Suriin ang pag-install
azd version
```

### ❌ "No subscription found" o "Subscription not set"

```bash
# Ilan ang mga magagamit na subscription
az account list --output table

# Itakda ang default na subscription
az account set --subscription "<subscription-id-or-name>"

# Itakda para sa AZD na kapaligiran
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Suriin
az account show
```

### ❌ "InsufficientQuota" o "Quota exceeded"

```bash
# Subukan ang iba't ibang Azure region
azd env set AZURE_LOCATION "westus2"
azd up

# O gumamit ng mas maliit na SKUs sa development
# I-edit ang infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```

### ❌ Nabigo ang "azd up" sa kalagitnaan

```bash
# Opsyon 1: Linisin at subukang muli
azd down --force --purge
azd up

# Opsyon 2: Ayusin lamang ang imprastraktura
azd provision

# Opsyon 3: Suriin ang detalyadong mga talaan
azd show
azd logs
```

### ❌ "Authentication failed" o "Token expired"

```bash
# Muling magpatunay ng pagkakakilanlan
az logout
az login

azd auth logout
azd auth login

# Suriin ang pagpapatunay ng pagkakakilanlan
az account show
```

### ❌ "Resource already exists" o mga salungatan sa pangalan

```bash
# Gumagawa ang AZD ng mga natatanging pangalan, ngunit kung mayroong salungatan:
azd down --force --purge

# Subukan muli gamit ang bagong kapaligiran
azd env new dev-v2
azd up
```

### ❌ Masyadong matagal ang deployment ng template

**Karaniwang oras ng paghihintay:**
- Simpleng web app: 5-10 minuto
- App na may database: 10-15 minuto
- Mga aplikasyon ng AI: 15-25 minuto (mabagal ang provisioning ng OpenAI)

```bash
# Suriin ang progreso
azd show

# Kung na-stuck ng higit sa 30 minuto, suriin ang Azure Portal:
azd monitor
# Hanapin ang mga nabigong deployment
```

### ❌ "Permission denied" o "Forbidden"

```bash
# Suriin ang iyong Azure role
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Kailangan mo ng hindi bababa sa "Contributor" na role
# Humiling sa iyong Azure admin na magbigay ng:
# - Contributor (para sa mga resources)
# - User Access Administrator (para sa mga role assignments)
```

### ❌ Hindi makita ang URL ng naka-deploy na aplikasyon

```bash
# Ipakita ang lahat ng mga endpoint ng serbisyo
azd show

# O buksan ang Azure Portal
azd monitor

# Suriin ang tiyak na serbisyo
azd env get-values
# Hanapin ang mga variable na *_URL
```

### 📚 Mga Kumpletong Mapagkukunan sa Pag-troubleshoot

- **Gabay sa Mga Karaniwang Isyu:** [Detalyadong Mga Solusyon](docs/troubleshooting/common-issues.md)
- **Mga Isyu na Nauukol sa AI:** [AI Troubleshooting](docs/troubleshooting/ai-troubleshooting.md)
- **Gabay sa Pag-debug:** [Hakbang-hakbang na Pag-debug](docs/troubleshooting/debugging.md)
- **Humingi ng Tulong:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🔧 Mabilisang Gabay sa Pag-troubleshoot

**Mga karaniwang isyu na nararanasan ng mga baguhan at agarang mga solusyon:**

<details>
<summary><strong>❌ "azd: command not found"</strong></summary>

```bash
# I-install muna ang AZD
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Suriin ang pag-install
azd version
```
</details>

<details>
<summary><strong>❌ "No subscription found" o "Subscription not set"</strong></summary>

```bash
# Ilista ang mga magagamit na subscription
az account list --output table

# Itakda ang default na subscription
az account set --subscription "<subscription-id-or-name>"

# Itakda para sa kapaligiran ng AZD
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Suriin
az account show
```
</details>

<details>
<summary><strong>❌ "InsufficientQuota" o "Quota exceeded"</strong></summary>

```bash
# Subukan ang ibang Azure region
azd env set AZURE_LOCATION "westus2"
azd up

# O gumamit ng mas maliit na SKUs sa development
# I-edit ang infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>

<details>
<summary><strong>❌ Nabigo ang "azd up" sa kalagitnaan</strong></summary>

```bash
# Opsyon 1: Linisin at subukang muli
azd down --force --purge
azd up

# Opsyon 2: Ayusin lamang ang imprastraktura
azd provision

# Opsyon 3: Suriin ang detalyadong mga tala
azd show
azd logs
```
</details>

<details>
<summary><strong>❌ "Authentication failed" o "Token expired"</strong></summary>

```bash
# Muling patunayan ang pagkakakilanlan
az logout
az login

azd auth logout
azd auth login

# Suriin ang pagpapatunay
az account show
```
</details>

<details>
<summary><strong>❌ "Resource already exists" o mga salungatan sa pangalan</strong></summary>

```bash
# Lumilikha ang AZD ng mga natatanging pangalan, ngunit kung may pagtatalo:
azd down --force --purge

# Magsubukang muli gamit ang bagong kapaligiran
azd env new dev-v2
azd up
```
</details>

<details>
<summary><strong>❌ Masyadong matagal ang deployment ng template</strong></summary>

**Karaniwang oras ng paghihintay:**
- Simpleng web app: 5-10 minuto
- App na may database: 10-15 minuto
- Mga aplikasyon ng AI: 15-25 minuto (mabagal ang provisioning ng OpenAI)

```bash
# Suriin ang progreso
azd show

# Kung na-stuck nang higit sa 30 minuto, tingnan ang Azure Portal:
azd monitor
# Hanapin ang mga nabigong deployment
```
</details>

<details>
<summary><strong>❌ "Permission denied" o "Forbidden"</strong></summary>

```bash
# Suriin ang iyong Azure na papel
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Kailangan mo ng hindi bababa sa "Contributor" na papel
# Hilingin sa iyong Azure admin na magbigay:
# - Contributor (para sa mga resources)
# - User Access Administrator (para sa mga pag-assign ng papel)
```
</details>

<details>
<summary><strong>❌ Hindi makita ang URL ng naka-deploy na aplikasyon</strong></summary>

```bash
# Ipakita lahat ng mga endpoint ng serbisyo
azd show

# O buksan ang Azure Portal
azd monitor

# Suriin ang partikular na serbisyo
azd env get-values
# Hanapin ang mga variable na *_URL
```
</details>

### 📚 Mga Kumpletong Mapagkukunan sa Pag-troubleshoot

- **Gabay sa Mga Karaniwang Isyu:** [Detalyadong Mga Solusyon](docs/troubleshooting/common-issues.md)
- **Mga Isyu na Nauukol sa AI:** [AI Troubleshooting](docs/troubleshooting/ai-troubleshooting.md)
- **Gabay sa Pag-debug:** [Hakbang-hakbang na Pag-debug](docs/troubleshooting/debugging.md)
- **Humingi ng Tulong:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🎓 Pagtatapos ng Kurso at Sertipikasyon

### Pagsubaybay ng Progreso
Subaybayan ang iyong progreso sa pag-aaral sa bawat kabanata:

- [ ] **Kabanata 1**: Pundasyon at Mabilisang Pagsisimula ✅  
- [ ] **Kabanata 2**: AI-First Development ✅  
- [ ] **Kabanata 3**: Konpigurasyon at Authentication ✅  
- [ ] **Kabanata 4**: Infrastructure as Code at Deployment ✅  
- [ ] **Kabanata 5**: Multi-Agent AI Solutions ✅  
- [ ] **Kabanata 6**: Pre-Deployment Validation at Pagpaplano ✅  
- [ ] **Kabanata 7**: Pag-troubleshoot at Pag-debug ✅  
- [ ] **Kabanata 8**: Mga Pattern sa Produksyon at Enterprise ✅  

### Pagpapatunay ng Pag-aaral
Pagkatapos makumpleto ang bawat kabanata, patunayan ang iyong kaalaman sa pamamagitan ng:
1. **Praktikal na Ehersisyo**: Kumpletuhin ang hands-on deployment ng kabanata  
2. **Pagsusuri sa Kaalaman**: Balikan ang FAQ na seksyon para sa iyong kabanata  
3. **Diskusyon sa Komunidad**: Ibahagi ang iyong karanasan sa Azure Discord  
4. **Susunod na Kabanata**: Lumipat sa susunod na antas ng pagiging kumplikado  

### Mga Benepisyo ng Pagtatapos ng Kurso
Kapag nakumpleto mo ang lahat ng kabanata, magkakaroon ka ng:
- **Karanasan sa Produksyon**: Na-deploy na totoong mga aplikasyon ng AI sa Azure  
- **Propesyonal na Kasanayan**: Kasanayan sa enterprise-ready na pag-deploy  
- **Pagkilala sa Komunidad**: Aktibong kasapi ng Azure developer community  
- **Pag-unlad ng Karera**: Kadalubhasaan sa AZD at deployment ng AI na hinahanap  

---

## 🤝 Komunidad at Suporta

### Humingi ng Tulong at Suporta
- **Mga Isyung Teknikal**: [I-report ang bugs at humiling ng mga tampok](https://github.com/microsoft/azd-for-beginners/issues)  
- **Mga Tanong sa Pag-aaral**: [Microsoft Azure Discord Community](https://discord.gg/microsoft-azure) at [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)  
- **Tulong na Nauukol sa AI**: Sumali sa [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)  
- **Dokumentasyon**: [Opisyal na Azure Developer CLI documentation](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)  

### Mga Pananaw ng Komunidad mula sa Microsoft Foundry Discord

**Mga Bagong Resulta ng Poll mula sa #Azure Channel:**
- **45%** ng mga developer ay nais gamitin ang AZD para sa mga AI workload  
- **Pinaka-malalaking hamon**: Multi-service deployments, credential management, kahandaan sa produksyon    
- **Pinakakailanganin**: AI-specific templates, troubleshooting guides, best practices  

**Sumali sa aming komunidad para:**
- Ibahagi ang iyong mga karanasan sa AZD + AI at humingi ng tulong  
- Makakuha ng mga maagang preview ng mga bagong AI template  
- Mag-ambag sa mga pinakamahuhusay na kasanayan sa deployment ng AI  
- Makaimpluwensiya sa mga hinaharap na pag-unlad ng AI + AZD na tampok  

### Pagsuporta sa Kurso
Malugod naming tinatanggap ang mga kontribusyon! Mangyaring basahin ang aming [Contributing Guide](CONTRIBUTING.md) para sa detalye sa:
- **Pagpapahusay ng Nilalaman**: Palawakin ang umiiral na mga kabanata at halimbawa  
- **Bagong Halimbawa**: Magdagdag ng mga totoong senaryo at mga template  
- **Pagsasalin**: Tumulong na panatilihin ang suporta sa maraming wika  
- **Pag-uulat ng Bug**: Pagbutihin ang katumpakan at kalinawan  
- **Mga Pamantayan ng Komunidad**: Sundin ang aming mga inklusibong patnubay sa komunidad  

---

## 📄 Impormasyon tungkol sa Kurso

### Lisensya
Ang proyektong ito ay lisensyado sa ilalim ng MIT License - tingnan ang file na [LICENSE](../../LICENSE) para sa mga detalye.

### Mga Kaugnay na Microsoft Learning Resources

Ang aming koponan ay gumagawa ng iba pang komprehensibong kurso sa pag-aaral:

<!-- CO-OP TRANSLATOR OTHER COURSES START -->
### LangChain
[![LangChain4j for Beginners](https://img.shields.io/badge/LangChain4j%20for%20Beginners-22C55E?style=for-the-badge&&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchain4j-for-beginners)
[![LangChain.js for Beginners](https://img.shields.io/badge/LangChain.js%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchainjs-for-beginners?WT.mc_id=m365-94501-dwahlin)

---

### Azure / Edge / MCP / Agents
[![AZD for Beginners](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Edge AI for Beginners](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![MCP for Beginners](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)
[![AI Agents for Beginners](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Generative AI Series
[![Generative AI for Beginners](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Generative AI (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
[![Generative AI (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)
[![Generative AI (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---
 
### Core Learning
[![ML for Beginners](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![Data Science for Beginners](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![AI for Beginners](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Cybersecurity for Beginners](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Web Dev for Beginners](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![IoT for Beginners](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![XR Development for Beginners](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Copilot Series
[![Copilot for AI Paired Programming](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![Copilot for C#/.NET](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Copilot Adventure](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ Course Navigation

**🚀 Handa Ka Na Bang Magsimulang Matuto?**

**Mga Baguhan**: Magsimula sa [Kabanata 1: Pundasyon at Mabilis na Pagsisimula](../..)  
**Mga AI Developer**: Tumalon sa [Kabanata 2: AI-First Development](../..)  
**Mga May Karanasan na Developer**: Simulan sa [Kabanata 3: Configuration at Authentication](../..)

**Mga Susunod na Hakbang**: [Simulan ang Kabanata 1 - AZD Basics](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Pahayag ng Pagsuway**:
Ang dokumentong ito ay isinalin gamit ang AI translation service na [Co-op Translator](https://github.com/Azure/co-op-translator). Bagama't nagsusumikap kami para sa katumpakan, mangyaring tandaan na ang awtomatikong pagsasalin ay maaaring maglaman ng mga pagkakamali o hindi pagkakatugma. Ang orihinal na dokumento sa orihinal nitong wika ang dapat ituring na pangunahing pinagkukunan. Para sa mahahalagang impormasyon, inirerekomenda ang propesyonal na pagsasalin ng tao. Hindi kami mananagot sa anumang hindi pagkakaintindihan o maling interpretasyon na nagmula sa paggamit ng pagsasaling ito.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->