<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T14:20:40+00:00",
  "source_file": "README.md",
  "language_code": "cs"
}
-->
> Poznámka: Tato dokumentace je průběžně aktualizována, aby odrážela nejnovější změny.

> ⚠️ Tento repozitář je demo vytvořené pro předvedení
> automatizované lokalizace dokumentace pomocí Localizeflow.
>
> Původní obsah je založen na
> projektu Microsoftu „AZD pro začátečníky“.


# AZD pro začátečníky: Strukturovaná cesta učením

![AZD-pro-zacatecniky](../../translated_images/azdbeginners.5527441dd9f74068.cs.png) 

[![GitHub sledující](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub hvězdy](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## Začínáme s tímto kurzem

Postupujte podle těchto kroků, abyste zahájili svou cestu učením AZD:

1. **Rozvětvěte repozitář**: Klikněte [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)
2. **Klonujte repozitář**: `git clone https://github.com/microsoft/azd-for-beginners.git`
3. **Připojte se ke komunitě**: [Azure Discord Communities](https://discord.com/invite/ByRwuEEgH4) pro odbornou podporu
4. **Vyberte si cestu učení**: Vyberte kapitolu níže odpovídající vaší úrovni zkušeností

### Podpora více jazyků

#### Automatizované překlady (vždy aktuální)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabština](../ar/README.md) | [Bengálština](../bn/README.md) | [Bulharština](../bg/README.md) | [Barmština (Myanmar)](../my/README.md) | [Čínština (zjednodušená)](../zh/README.md) | [Čínština (tradiční, Hongkong)](../hk/README.md) | [Čínština (tradiční, Macau)](../mo/README.md) | [Čínština (tradiční, Tchaj-wan)](../tw/README.md) | [Chorvatština](../hr/README.md) | [Čeština](./README.md) | [Dánština](../da/README.md) | [Nizozemština](../nl/README.md) | [Estonština](../et/README.md) | [Finština](../fi/README.md) | [Francouzština](../fr/README.md) | [Němčina](../de/README.md) | [Řečtina](../el/README.md) | [Hebrejština](../he/README.md) | [hindština](../hi/README.md) | [Maďarština](../hu/README.md) | [Indonéština](../id/README.md) | [Italština](../it/README.md) | [Japonština](../ja/README.md) | [Kannadština](../kn/README.md) | [Korejština](../ko/README.md) | [Litevština](../lt/README.md) | [Malajština](../ms/README.md) | [Malayalam](../ml/README.md) | [Maráthština](../mr/README.md) | [Nepálština](../ne/README.md) | [Nigérijská pidžinština](../pcm/README.md) | [Norština](../no/README.md) | [Perština (Farsi)](../fa/README.md) | [Polština](../pl/README.md) | [Portugalština (Brazílie)](../br/README.md) | [Portugalština (Portugalsko)](../pt/README.md) | [Paňdžábština (Gurmukhí)](../pa/README.md) | [Rumunština](../ro/README.md) | [Ruština](../ru/README.md) | [Srbština (cyrilice)](../sr/README.md) | [Slovenština](../sk/README.md) | [Slovinština](../sl/README.md) | [Španělština](../es/README.md) | [Svahilština](../sw/README.md) | [Švédština](../sv/README.md) | [Tagalog (Filipínština)](../tl/README.md) | [Tamilština](../ta/README.md) | [Telugština](../te/README.md) | [Thajština](../th/README.md) | [Turečtina](../tr/README.md) | [Ukrajinština](../uk/README.md) | [Urdština](../ur/README.md) | [Vietnamština](../vi/README.md)

> **Raději klonovat lokálně?**

> Tento repozitář obsahuje více než 50 překladů jazyků, což výrazně zvyšuje velikost stahování. Pro klonování bez překladů použijte sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Díky tomu získáte vše potřebné ke splnění kurzu s mnohem rychlejším stahováním.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## Přehled kurzu

Osvojte si Azure Developer CLI (azd) pomocí strukturovaných kapitol navržených pro postupné učení. **Speciální zaměření na nasazení AI aplikací s integrací Microsoft Foundry.**

### Proč je tento kurz nezbytný pro moderní vývojáře

Na základě poznatků komunity Microsoft Foundry na Discordu **45 % vývojářů chce používat AZD pro AI úlohy**, ale narážejí na výzvy s:
- Složitými více-službovými AI architekturami
- Osvedčenými postupy nasazení AI do produkce  
- Integrací a konfigurací Azure AI služeb
- Optimalizací nákladů pro AI úlohy
- Řešením problémů specifických pro nasazení AI

### Cíle učení

Dokončením tohoto strukturovaného kurzu budete:
- **Ovládat základy AZD**: Klíčové koncepty, instalace a konfigurace
- **Nasazovat AI aplikace**: Použití AZD s Microsoft Foundry službami
- **Implementovat infrastrukturu jako kód**: Správa Azure zdrojů pomocí Bicep šablon
- **Řešit problémy s nasazením**: Odstraňování běžných problémů a ladění
- **Optimalizovat pro produkci**: Bezpečnost, škálování, monitoring a správa nákladů
- **Budovat multi-agentní řešení**: Nasazení složitých AI architektur

## 📚 Učební kapitoly

*Vyberte si cestu učení podle úrovně zkušeností a cílů*

### 🚀 Kapitola 1: Základy a rychlý start
**Požadavky**: Azure předplatné, základní znalosti příkazové řádky  
**Doba trvání**: 30-45 minut  
**Složitost**: ⭐

#### Co se naučíte
- Pochopení základů Azure Developer CLI
- Instalace AZD na vaši platformu
- Vaše první úspěšné nasazení

#### Výukové zdroje
- **🎯 Začněte zde**: [Co je Azure Developer CLI?](../..)
- **📖 Teorie**: [Základy AZD](docs/getting-started/azd-basics.md) - Klíčové koncepty a terminologie
- **⚙️ Nastavení**: [Instalace a nastavení](docs/getting-started/installation.md) - Návody specifické pro platformu
- **🛠️ Prakticky**: [Váš první projekt](docs/getting-started/first-project.md) - Krok za krokem
- **📋 Rychlá reference**: [Přehled příkazů](resources/cheat-sheet.md)

#### Praktická cvičení
```bash
# Rychlá kontrola instalace
azd version

# Nasazení vaší první aplikace
azd init --template todo-nodejs-mongo
azd up
```

**💡 Výsledek kapitoly**: Úspěšně nasadit jednoduchou webovou aplikaci do Azure pomocí AZD

**✅ Ověření úspěchu:**
```bash
# Po dokončení kapitoly 1 budete schopni:
azd version              # Zobrazuje nainstalovanou verzi
azd init --template todo-nodejs-mongo  # Inicializuje projekt
azd up                  # Nasazuje na Azure
azd show                # Zobrazuje URL běžící aplikace
# Aplikace se otevře v prohlížeči a funguje
azd down --force --purge  # Čistí zdroje
```

**📊 Časová investice:** 30-45 minut  
**📈 Úroveň dovedností po dokončení:** Dokáže nasadit základní aplikace samostatně

**✅ Ověření úspěchu:**
```bash
# Po dokončení kapitoly 1 byste měli být schopni:
azd version              # Zobrazuje nainstalovanou verzi
azd init --template todo-nodejs-mongo  # Inicializuje projekt
azd up                  # Nasazuje do Azure
azd show                # Zobrazuje URL běžící aplikace
# Aplikace se otevře v prohlížeči a funguje
azd down --force --purge  # Čistí zdroje
```

**📊 Časová investice:** 30-45 minut  
**📈 Úroveň dovedností po dokončení:** Dokáže nasadit základní aplikace samostatně

---

### 🤖 Kapitola 2: Vývoj zaměřený na AI (doporučeno pro AI vývojáře)
**Požadavky**: Kapitola 1 dokončena  
**Doba trvání**: 1-2 hodiny  
**Složitost**: ⭐⭐

#### Co se naučíte
- Integrace Microsoft Foundry s AZD
- Nasazení aplikací využívajících AI
- Pochopení konfigurace AI služeb

#### Výukové zdroje
- **🎯 Začněte zde**: [Integrace Microsoft Foundry](docs/microsoft-foundry/microsoft-foundry-integration.md)
- **📖 Vzory**: [Nasazení AI modelu](docs/microsoft-foundry/ai-model-deployment.md) - Nasazení a správa AI modelů
- **🛠️ Workshop**: [AI Workshop Lab](docs/microsoft-foundry/ai-workshop-lab.md) - Připravte svá AI řešení pro AZD
- **🎥 Interaktivní průvodce**: [Materiály workshopu](workshop/README.md) - Učení v prohlížeči s MkDocs * DevContainer prostředím
- **📋 Šablony**: [Microsoft Foundry šablony](../..)
- **📝 Příklady**: [Příklady nasazení AZD](examples/README.md)

#### Praktická cvičení
```bash
# Nasadíte svou první AI aplikaci
azd init --template azure-search-openai-demo
azd up

# Vyzkoušejte další AI šablony
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```

**💡 Výsledek kapitoly**: Nasadit a nakonfigurovat AI poháněnou chatovací aplikaci s funkcemi RAG

**✅ Ověření úspěchu:**
```bash
# Po kapitole 2 byste měli být schopni:
azd init --template azure-search-openai-demo
azd up
# Otestovat AI chatovací rozhraní
# Pokládat otázky a získávat odpovědi s podporou AI včetně zdrojů
# Ověřit, že integrace vyhledávání funguje
azd monitor  # Zkontrolovat, zda Application Insights zobrazuje telemetrii
azd down --force --purge
```

**📊 Časová investice:** 1-2 hodiny  
**📈 Úroveň dovedností po dokončení:** Dokáže nasadit a nakonfigurovat AI aplikace připravené pro produkci  
**💰 Povědomí o nákladech:** Rozumí vývojovým nákladům 80-150 $/měsíc, produkčním 300-3500 $/měsíc

#### 💰 Nákladové úvahy pro AI nasazení

**Vývojové prostředí (odhadem 80-150 $/měsíc):**
- Azure OpenAI (pay-as-you-go): 0-50 $/měsíc (podle využití tokenů)
- AI Search (základní úroveň): 75 $/měsíc
- Container Apps (za spotřebu): 0-20 $/měsíc
- Úložiště (standardní): 1-5 $/měsíc

**Produkční prostředí (odhadem 300-3 500+/měsíc):**
- Azure OpenAI (PTU pro konzistentní výkon): 3000+ $/měsíc NEBO pay-as-you-go při vysokém objemu
- AI Search (standardní úroveň): 250 $/měsíc
- Container Apps (dedikované): 50-100 $/měsíc
- Application Insights: 5-50 $/měsíc
- Úložiště (prémiové): 10-50 $/měsíc

**💡 Tipy pro optimalizaci nákladů:**
- Používejte **Free Tier** Azure OpenAI pro učení (50 000 tokenů/měsíc zahrnuto)
- Spouštějte `azd down` pro uvolnění prostředků, když aktivně nevyvíjíte
- Začněte s účtováním na základě spotřeby, přejděte na PTU pouze pro produkci
- Použijte `azd provision --preview` pro odhad nákladů před nasazením
- Povolit automatické škálování: platíte jen za skutečné využití

**Monitorování nákladů:**
```bash
# Zkontrolujte odhadované měsíční náklady
azd provision --preview

# Sledujte skutečné náklady v portálu Azure
az consumption budget list --resource-group <your-rg>
```

---

### ⚙️ Kapitola 3: Konfigurace a ověřování identity
**Požadavky**: Kapitola 1 dokončena  
**Doba trvání**: 45-60 minut  
**Složitost**: ⭐⭐

#### Co se naučíte
- Konfigurace a správa prostředí
- Ověřování identity a osvědčené bezpečnostní praktiky
- Pojmenování a organizace zdrojů

#### Výukové zdroje
- **📖 Konfigurace**: [Návod na konfiguraci](docs/getting-started/configuration.md) - Nastavení prostředí
- **🔐 Bezpečnost**: [Vzory autentizace a spravovaná identita](docs/getting-started/authsecurity.md) - Vzory autentizace
- **📝 Příklady**: [Příklad databázové aplikace](examples/database-app/README.md) - AZD příklady databází

#### Praktická cvičení
- Konfigurace více prostředí (dev, staging, prod)
- Nastavení autentizace pomocí spravované identity
- Implementace konfigurací specifických pro prostředí

**💡 Výsledek kapitoly**: Spravovat více prostředí s řádnou autentizací a bezpečností

---

### 🏗️ Kapitola 4: Infrastruktura jako kód a nasazení
**Požadavky**: Kapitoly 1-3 dokončeny  
**Doba trvání**: 1-1,5 hodiny  
**Složitost**: ⭐⭐⭐

#### Co se naučíte
- Pokročilé vzory nasazení
- Infrastruktura jako kód s Bicep
- Strategie provisioningu zdrojů

#### Výukové zdroje
- **📖 Nasazení**: [Průvodce nasazením](docs/deployment/deployment-guide.md) - Kompletní pracovní postupy
- **🏗️ Provisioning**: [Provisioning zdrojů](docs/deployment/provisioning.md) - Správa Azure zdrojů
- **📝 Příklady**: [Příklad Container App](../../examples/container-app) - Nasazení kontejnerovaných aplikací

#### Praktická cvičení
- Vytvoření vlastních Bicep šablon
- Nasazení víceslužbových aplikací
- Implementace strategií blue-green deploymentu

**💡 Výsledek kapitoly**: Nasadit složité víceslužbové aplikace pomocí vlastních infrastrukturních šablon

---
### 🎯 Kapitola 5: Řešení víceagentních AI systémů (Pokročilé)
**Požadavky**: Dokončeno v kapitolách 1-2  
**Délka**: 2-3 hodiny  
**Složitost**: ⭐⭐⭐⭐

#### Co se naučíte
- Vzory architektury více agentů
- Orchestrace a koordinace agentů
- Nasazení AI připravené pro produkci

#### Výukové zdroje
- **🤖 Hlavní projekt**: [Retail Multi-Agent Solution](examples/retail-scenario.md) - Kompletní implementace
- **🛠️ ARM šablony**: [ARM Template Package](../../examples/retail-multiagent-arm-template) - Jedním kliknutím nasazení
- **📖 Architektura**: [Vzory koordinace více agentů](/docs/pre-deployment/coordination-patterns.md) - Vzory

#### Praktická cvičení
```bash
# Nasadit kompletní maloobchodní řešení s více agenty
cd examples/retail-multiagent-arm-template
./deploy.sh

# Prozkoumat konfigurace agentů
az deployment group show --resource-group <rg-name> --name <deployment-name>
```

**💡 Výsledek kapitoly**: Nasadit a spravovat produkční řešení víceagentní AI s agenty pro zákazníky a skladové zásoby

---

### 🔍 Kapitola 6: Validace a plánování před nasazením
**Požadavky**: Dokončeno v kapitole 4  
**Délka**: 1 hodina  
**Složitost**: ⭐⭐

#### Co se naučíte
- Plánování kapacity a ověřování zdrojů
- Strategie výběru SKU
- Kontroly před nasazením a automatizace

#### Výukové zdroje
- **📊 Plánování**: [Capacity Planning](docs/pre-deployment/capacity-planning.md) - Ověření zdrojů
- **💰 Výběr**: [SKU Selection](docs/pre-deployment/sku-selection.md) - Nákladově efektivní volby
- **✅ Validace**: [Pre-flight Checks](docs/pre-deployment/preflight-checks.md) - Automatizované skripty

#### Praktická cvičení
- Spuštění skriptů ověřujících kapacitu
- Optimalizace výběru SKU z hlediska nákladů
- Implementace automatizovaných kontrol před nasazením

**💡 Výsledek kapitoly**: Validovat a optimalizovat nasazení před jejich spuštěním

---

### 🚨 Kapitola 7: Odstraňování problémů a ladění
**Požadavky**: Dokončená jakákoliv kapitola o nasazení  
**Délka**: 1-1,5 hodiny  
**Složitost**: ⭐⭐

#### Co se naučíte
- Systematické přístupy k ladění
- Běžné problémy a řešení
- Řešení problémů specifických pro AI

#### Výukové zdroje
- **🔧 Běžné problémy**: [Common Issues](docs/troubleshooting/common-issues.md) - FAQ a řešení
- **🕵️ Ladění**: [Debugging Guide](docs/troubleshooting/debugging.md) - Krok za krokem strategie
- **🤖 AI problémy**: [AI-Specific Troubleshooting](docs/troubleshooting/ai-troubleshooting.md) - Problémy AI služeb

#### Praktická cvičení
- Diagnostika chyb nasazení
- Řešení problémů s autentizací
- Ladění konektivity AI služeb

**💡 Výsledek kapitoly**: Samostatně diagnostikovat a řešit běžné chyby nasazení

---

### 🏢 Kapitola 8: Produkční a podnikové vzory
**Požadavky**: Dokončeno v kapitolách 1-4  
**Délka**: 2-3 hodiny  
**Složitost**: ⭐⭐⭐⭐

#### Co se naučíte
- Strategie produkčního nasazení
- Bezpečnostní vzory pro podnikové prostředí
- Monitorování a optimalizace nákladů

#### Výukové zdroje
- **🏭 Produkce**: [Production AI Best Practices](docs/microsoft-foundry/production-ai-practices.md) - Vzory pro podnikové nasazení
- **📝 Příklady**: [Microservices Example](../../examples/microservices) - Komplexní architektury
- **📊 Monitorování**: [Application Insights integration](docs/pre-deployment/application-insights.md) - Monitorování

#### Praktická cvičení
- Implementace podnikových bezpečnostních vzorů
- Nastavení komplexního monitoringu
- Nasazení do produkce s odpovídající správou a řízením

**💡 Výsledek kapitoly**: Nasadit aplikace připravené pro podnikové prostředí s plnou produkční funkcionalitou

---

## 🎓 Přehled workshopu: Praktické učení

> **⚠️ STAV WORKSHOPU: Aktivní vývoj**  
> Materiály workshopu jsou právě vyvíjeny a zdokonalovány. Základní moduly jsou funkční, pokročilé části jsou ještě neúplné. Aktivně pracujeme na dokončení všech obsahů. [Sledujte pokrok →](workshop/README.md)

### Interaktivní materiály workshopu
**Komplexní praktické učení pomocí nástrojů v prohlížeči a vedených cvičení**

Materiály workshopu nabízejí strukturovaný a interaktivní vzdělávací zážitek, který doplňuje výukový plán pořádaný podle kapitol. Workshop je určen jak pro samostudium, tak i pro vedené lekce instruktorů.

#### 🛠️ Vlastnosti workshopu
- **Práce v prohlížeči**: Kompletní workshop MkDocs s funkcemi vyhledávání, kopírování a témat
- **Integrace GitHub Codespaces**: Jedním kliknutím nastavení vývojového prostředí
- **Strukturovaná cesta učením**: 7 kroků vedených cvičení (celkem 3,5 hodiny)
- **Objevování → Nasazení → Přizpůsobení**: Postupná metodika
- **Interaktivní DevContainer prostředí**: Přednastavené nástroje a závislosti

#### 📚 Struktura workshopu
Workshop sleduje metodiku **Objevování → Nasazení → Přizpůsobení**:

1. **Fáze objevování** (45 minut)
   - Prozkoumat Microsoft Foundry šablony a služby
   - Pochopit vzory architektury více agentů
   - Prohlédnout požadavky a předpoklady nasazení

2. **Fáze nasazení** (2 hodiny)
   - Praktické nasazení AI aplikací pomocí AZD
   - Konfigurace Azure AI služeb a endpointů
   - Implementace bezpečnostních a autentizačních vzorů

3. **Fáze přizpůsobení** (45 minut)
   - Úprava aplikací pro konkrétní scénáře použití
   - Optimalizace pro produkční nasazení
   - Implementace monitoringu a správy nákladů

#### 🚀 Začínáme s workshopem
```bash
# Možnost 1: GitHub Codespaces (Doporučeno)
# Klikněte na "Code" → "Create codespace on main" v repozitáři

# Možnost 2: Lokální vývoj
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# Postupujte podle instalačních pokynů v workshop/README.md
```

#### 🎯 Výstupy z workshopu
Po dokončení workshopu účastníci:
- **Nasadí produkční AI aplikace**: Použitím AZD a služeb Microsoft Foundry
- **Zvládnou víceagentní architektury**: Implementují koordinovaná řešení AI agentů
- **Implementují bezpečnostní postupy**: Nakonfigurují autentizaci a řízení přístupů
- **Optimalizují škálování**: Navrhnou nákladově efektivní a výkonná nasazení
- **Řeší problémy nasazení**: Samostatně opravují běžné chyby

#### 📖 Materiály workshopu
- **🎥 Interaktivní průvodce**: [Workshop Materials](workshop/README.md) - Učení v prohlížeči
- **📋 Návody krok za krokem**: [Guided Exercises](../../workshop/docs/instructions) - Detailní průvodce
- **🛠️ AI Workshop Lab**: [AI Workshop Lab](docs/microsoft-foundry/ai-workshop-lab.md) - AI zaměřená cvičení
- **💡 Rychlý start**: [Workshop Setup Guide](workshop/README.md#quick-start) - Konfigurace prostředí

**Ideální pro**: firemní školení, univerzitní kurzy, samostudium a bootcampy pro vývojáře.

---

## 📖 Co je Azure Developer CLI?

Azure Developer CLI (azd) je vývojářské příkazové rozhraní, které urychluje proces vytváření a nasazování aplikací do Azure. Nabízí:

- **Nasazení založené na šablonách** - Používání předpřipravených šablon pro běžné vzory aplikací
- **Infrastruktura jako kód** - Správa Azure zdrojů pomocí Bicep nebo Terraform  
- **Integrované pracovní postupy** - Bezproblémové pořizování, nasazení a monitorování aplikací
- **Přátelské pro vývojáře** - Optimalizováno pro produktivitu a pohodlí vývojářů

### **AZD + Microsoft Foundry: Ideální pro AI nasazení**

**Proč AZD pro AI řešení?** AZD řeší hlavní výzvy, kterým vývojáři AI čelí:

- **Připravené šablony pro AI** - Předkonfigurované šablony pro Azure OpenAI, Kognitivní služby a ML pracovní zátěže
- **Bezpečné AI nasazení** - Vložené bezpečnostní vzory pro AI služby, API klíče a model endpointy  
- **Produkční AI vzory** - Nejlepší praxe pro škálovatelná, nákladově efektivní AI nasazení
- **End-to-end AI pracovní toky** - Od vývoje modelu po produkční nasazení s monitorováním
- **Optimalizace nákladů** - Chytré přidělení zdrojů a škálování AI aplikací
- **Integrace Microsoft Foundry** - Plynulé propojení s katalogem a endpointy modelů Microsoft Foundry

---

## 🎯 Knihovna šablon a příkladů

### Doporučeno: Microsoft Foundry šablony
**Začněte zde, pokud nasazujete AI aplikace!**

> **Poznámka:** Tyto šablony ukazují různé AI vzory. Některé jsou externí Azure Samples, jiné lokální implementace.

| Šablona | Kapitola | Složitost | Služby | Typ |
|----------|----------|-----------|--------|-----|
| [**Get started with AI chat**](https://github.com/Azure-Samples/get-started-with-ai-chat) | Kapitola 2 | ⭐⭐ | AzureOpenAI + Azure AI Model Inference API + Azure AI Search + Azure Container Apps + Application Insights | Externí |
| [**Get started with AI agents**](https://github.com/Azure-Samples/get-started-with-ai-agents) | Kapitola 2 | ⭐⭐ | Azure AI Agent Service + AzureOpenAI + Azure AI Search + Azure Container Apps + Application Insights| Externí |
| [**Azure Search + OpenAI Demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Kapitola 2 | ⭐⭐ | AzureOpenAI + Azure AI Search + App Service + Storage | Externí |
| [**OpenAI Chat App Quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Kapitola 2 | ⭐ | AzureOpenAI + Container Apps + Application Insights | Externí |
| [**Agent OpenAI Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Kapitola 5 | ⭐⭐⭐ | AzureOpenAI + Azure Functions + Prompty | Externí |
| [**Contoso Chat RAG**](https://github.com/Azure-Samples/contoso-chat) | Kapitola 8 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Cosmos DB + Container Apps | Externí |
| [**Retail Multi-Agent Solution**](examples/retail-scenario.md) | Kapitola 5 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Storage + Container Apps + Cosmos DB | **Lokální** |

### Doporučeno: Kompletní výukové scénáře
**Produkční šablony aplikací mapované na učební kapitoly**

| Šablona | Kapitola | Složitost | Klíčové učení |
|----------|---------|-----------|---------------|
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Kapitola 2 | ⭐ | Základní vzory AI nasazení |
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Kapitola 2 | ⭐⭐ | Implementace RAG s Azure AI Search |
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | Kapitola 4 | ⭐⭐ | Integrace inteligence dokumentů |
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Kapitola 5 | ⭐⭐⭐ | Agentní rámec a volání funkcí |
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | Kapitola 8 | ⭐⭐⭐ | Podniková AI orchestraci |
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | Kapitola 5 | ⭐⭐⭐⭐ | Víceagentní architektura se zákaznickými a skladovými agenty |

### Učení podle typu příkladu

> **📌 Lokální vs. externí příklady:**  
> **Lokální příklady** (v tomto repozitáři) = ihned připravené k použití  
> **Externí příklady** (Azure Samples) = Klonujte z odkazovaných repozitářů

#### Lokální příklady (ihned k použití)
- [**Retail Multi-Agent Solution**](examples/retail-scenario.md) - Kompletní produkční implementace s ARM šablonami
  - Víceagentní architektura (zákazník + sklad)
  - Komplexní monitoring a vyhodnocování
  - Nasazení jedním kliknutím přes ARM šablonu

#### Lokální příklady - kontejnery (kapitoly 2-5)
**Komplexní příklady nasazení kontejnerů v tomto repozitáři:**
- [**Container App Examples**](examples/container-app/README.md) - Kompletní průvodce kontejnerovými nasazeními
  - [Jednoduché Flask API](../../examples/container-app/simple-flask-api) - Základní REST API s podporou scale-to-zero
  - [Architektura microservices](../../examples/container-app/microservices) - Produkční nasazení více služeb
  - Rychlý start, produkční a pokročilé vzory nasazení
  - Pokyny pro monitoring, bezpečnost a optimalizaci nákladů

#### Externí příklady - jednoduché aplikace (kapitoly 1-2)
**Klonujte tyto Azure Samples repozitáře pro začátek:**
- [Jednoduchá webová aplikace - Node.js + MongoDB](https://github.com/Azure-Samples/todo-nodejs-mongo) - Základní vzory nasazení
- [Statická webová stránka - React SPA](https://github.com/Azure-Samples/todo-csharp-sql-swa-func) - Nasazení statického obsahu
- [Container App - Python Flask](https://github.com/Azure-Samples/container-apps-store-api-microservice) - Nasazení REST API

#### Externí příklady - integrace databází (kapitoly 3-4)  
- [Databázová aplikace - C# + SQL](https://github.com/Azure-Samples/todo-csharp-sql) - Vzory připojení k databázi
- [Functions + Cosmos DB](https://github.com/Azure-Samples/todo-python-mongo-swa-func) - Serverless datové workflow

#### Externí příklady - pokročilé vzory (kapitoly 4-8)
- [Java mikro služby](https://github.com/Azure-Samples/java-microservices-aca-lab) - Architektury více služeb
- [Container Apps Jobs](https://github.com/Azure-Samples/container-apps-jobs) - Zpracování na pozadí  
- [Enterprise ML Pipeline](https://github.com/Azure-Samples/mlops-v2) - Produkční ML vzory

### Externí kolekce šablon
- [**Oficiální galerie šablon AZD**](https://azure.github.io/awesome-azd/) - Pečlivě vybraná kolekce oficiálních a komunitních šablon
- [**Šablony Azure Developer CLI**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - Dokumentace šablon Microsoft Learn
- [**Adresář příkladů**](examples/README.md) - Místní příklady pro učení s podrobným vysvětlením

---

## 📚 Výukové zdroje a reference

### Rychlé odkazy
- [**Přehled příkazů**](resources/cheat-sheet.md) - Základní příkazy azd seskupené dle kapitol
- [**Glosář**](resources/glossary.md) - Terminologie Azure a azd  
- [**Často kladené otázky (FAQ)**](resources/faq.md) - Časté dotazy podle učebních kapitol
- [**Studijní průvodce**](resources/study-guide.md) - Komplexní cvičení

### Praktické workshopy
- [**AI Workshop Lab**](docs/microsoft-foundry/ai-workshop-lab.md) - Umožněte nasazení svých AI řešení pomocí AZD (2-3 hodiny)
- [**Interaktivní průvodce workshopem**](workshop/README.md) - Workshop v prohlížeči s MkDocs a DevContainer prostředím
- [**Strukturovaná výuková cesta**](../../workshop/docs/instructions) - 7-krokové vedené cvičení (Objevování → Nasazení → Přizpůsobení)
- [**AZD pro začátečníky workshop**](workshop/README.md) - Kompletní materiály s integrací GitHub Codespaces

### Vnější vzdělávací zdroje
- Dokumentace Azure Developer CLI: https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/
- Azure Architecture Center: https://learn.microsoft.com/en-us/azure/architecture/
- Azure kalkulačka cen: https://azure.microsoft.com/pricing/calculator/
- Stav Azure: https://status.azure.com/

---

## 🔧 Rychlý průvodce řešením problémů

**Časté problémy začátečníků a okamžitá řešení:**

### ❌ "azd: příkaz nenalezen"

```bash
# Nejprve nainstalujte AZD
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Ověřte instalaci
azd version
```

### ❌ "Nenalezena žádná předplatná" nebo "Předplatné není nastaveno"

```bash
# Vypsat dostupná předplatná
az account list --output table

# Nastavit výchozí předplatné
az account set --subscription "<subscription-id-or-name>"

# Nastavit pro prostředí AZD
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Ověřit
az account show
```

### ❌ "Nedostatečný kvótní limit" nebo "Kvóta překročena"

```bash
# Vyzkoušejte jiný Azure region
azd env set AZURE_LOCATION "westus2"
azd up

# Nebo použijte menší SKU ve vývoji
# Upravte infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```

### ❌ "azd up" selže v polovině procesu

```bash
# Možnost 1: Vyčistit a zkusit znovu
azd down --force --purge
azd up

# Možnost 2: Opravit pouze infrastrukturu
azd provision

# Možnost 3: Zkontrolovat podrobné protokoly
azd show
azd logs
```

### ❌ "Autentizace selhala" nebo "Platnost tokenu vypršela"

```bash
# Znovu ověřit
az logout
az login

azd auth logout
azd auth login

# Ověřit autentizaci
az account show
```

### ❌ "Zdroj již existuje" nebo kolize pojmenování

```bash
# AZD generuje jedinečná jména, ale pokud dojde ke konfliktu:
azd down --force --purge

# Pak zkuste znovu s novým prostředím
azd env new dev-v2
azd up
```

### ❌ Nasazení šablony trvá příliš dlouho

**Normální doby čekání:**
- Jednoduchá webová aplikace: 5-10 minut
- Aplikace s databází: 10-15 minut
- AI aplikace: 15-25 minut (provisioning OpenAI je pomalý)

```bash
# Zkontrolujte postup
azd show

# Pokud zůstanete zaseknutí více než 30 minut, zkontrolujte Azure Portal:
azd monitor
# Hledejte neúspěšné nasazení
```

### ❌ "Odepřeno oprávnění" nebo "Zakázáno"

```bash
# Zkontrolujte svou roli v Azure
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Potřebujete alespoň roli "Přispěvatel"
# Požádejte svého správce Azure o udělení:
# - Přispěvatel (pro zdroje)
# - Správce přístupu uživatelů (pro přiřazení rolí)
```

### ❌ Nelze nalézt URL nasazené aplikace

```bash
# Zobrazit všechny koncové body služby
azd show

# Nebo otevřít Azure Portál
azd monitor

# Zkontrolovat konkrétní službu
azd env get-values
# Hledat proměnné *_URL
```

### 📚 Kompletní zdroje pro řešení problémů

- **Průvodce častými problémy:** [Podrobné řešení](docs/troubleshooting/common-issues.md)
- **AI-specifické problémy:** [Řešení problémů s AI](docs/troubleshooting/ai-troubleshooting.md)
- **Průvodce laděním:** [Krok za krokem debugování](docs/troubleshooting/debugging.md)
- **Získejte pomoc:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🔧 Rychlý průvodce řešením problémů

**Časté problémy začátečníků a okamžitá řešení:**

<details>
<summary><strong>❌ "azd: příkaz nenalezen"</strong></summary>

```bash
# Nejprve nainstalujte AZD
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Ověřte instalaci
azd version
```
</details>

<details>
<summary><strong>❌ "Nenalezena žádná předplatná" nebo "Předplatné není nastaveno"</strong></summary>

```bash
# Vypsat dostupné předplatné
az account list --output table

# Nastavit výchozí předplatné
az account set --subscription "<subscription-id-or-name>"

# Nastavit pro prostředí AZD
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Ověřit
az account show
```
</details>

<details>
<summary><strong>❌ "Nedostatečný kvótní limit" nebo "Kvóta překročena"</strong></summary>

```bash
# Vyzkoušejte jiný Azure region
azd env set AZURE_LOCATION "westus2"
azd up

# Nebo použijte menší SKU během vývoje
# Upravte infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>

<details>
<summary><strong>❌ "azd up" selže v polovině procesu</strong></summary>

```bash
# Možnost 1: Vyčistit a zkusit znovu
azd down --force --purge
azd up

# Možnost 2: Opravit pouze infrastrukturu
azd provision

# Možnost 3: Zkontrolovat podrobné záznamy
azd show
azd logs
```
</details>

<details>
<summary><strong>❌ "Autentizace selhala" nebo "Platnost tokenu vypršela"</strong></summary>

```bash
# Znovu ověřit
az logout
az login

azd auth logout
azd auth login

# Ověřit autentizaci
az account show
```
</details>

<details>
<summary><strong>❌ "Zdroj již existuje" nebo kolize pojmenování</strong></summary>

```bash
# AZD generuje unikátní názvy, ale pokud dojde ke konfliktu:
azd down --force --purge

# Pak zkusit znovu s novým prostředím
azd env new dev-v2
azd up
```
</details>

<details>
<summary><strong>❌ Nasazení šablony trvá příliš dlouho</strong></summary>

**Normální doby čekání:**
- Jednoduchá webová aplikace: 5-10 minut
- Aplikace s databází: 10-15 minut
- AI aplikace: 15-25 minut (provisioning OpenAI je pomalý)

```bash
# Zkontrolujte průběh
azd show

# Pokud se zaseknete >30 minut, zkontrolujte Azure Portal:
azd monitor
# Hledejte neúspěšné nasazení
```
</details>

<details>
<summary><strong>❌ "Odepřeno oprávnění" nebo "Zakázáno"</strong></summary>

```bash
# Zkontrolujte svou roli v Azure
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Potřebujete alespoň roli „Přispěvatel“
# Požádejte svého správce Azure o udělení:
# - Přispěvatel (pro prostředky)
# - Správce přístupu uživatelů (pro přiřazení rolí)
```
</details>

<details>
<summary><strong>❌ Nelze nalézt URL nasazené aplikace</strong></summary>

```bash
# Zobrazit všechny koncové body služby
azd show

# Nebo otevřít Azure Portal
azd monitor

# Zkontrolovat konkrétní službu
azd env get-values
# Hledat proměnné *_URL
```
</details>

### 📚 Kompletní zdroje pro řešení problémů

- **Průvodce častými problémy:** [Podrobné řešení](docs/troubleshooting/common-issues.md)
- **AI-specifické problémy:** [Řešení problémů s AI](docs/troubleshooting/ai-troubleshooting.md)
- **Průvodce laděním:** [Krok za krokem debugování](docs/troubleshooting/debugging.md)
- **Získejte pomoc:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🎓 Ukončení kurzu a certifikace

### Sledování pokroku
Sledujte svůj učební pokrok podle kapitol:

- [ ] **Kapitola 1**: Základy a rychlý start ✅
- [ ] **Kapitola 2**: Vývoj zaměřený na AI ✅  
- [ ] **Kapitola 3**: Konfigurace a autentizace ✅
- [ ] **Kapitola 4**: Infrastruktura jako kód a nasazení ✅
- [ ] **Kapitola 5**: AI řešení s více agenty ✅
- [ ] **Kapitola 6**: Přednasazovací validace a plánování ✅
- [ ] **Kapitola 7**: Řešení problémů a ladění ✅
- [ ] **Kapitola 8**: Produkční a podnikové vzory ✅

### Ověření učiva
Po dokončení každé kapitoly ověřte své znalosti:
1. **Praktické cvičení**: Dokončete nasazení kapitoly
2. **Kontrola znalostí**: Projděte FAQ pro danou kapitolu
3. **Diskuze komunity**: Sdílejte zkušenosti na Azure Discordu
4. **Další kapitola**: Pokračujte na další úroveň složitosti

### Výhody dokončení kurzu
Po dokončení všech kapitol získáte:
- **Produkční zkušenosti**: Nasazení reálných AI aplikací do Azure
- **Profesionální dovednosti**: Schopnost nasazení připraveného pro podnikové prostředí  
- **Uznání v komunitě**: Aktivní člen Azure vývojářské komunity
- **Kariérní postup**: Žádané znalosti nasazení AZD a AI

---

## 🤝 Komunita a podpora

### Získejte pomoc a podporu
- **Technické problémy**: [Nahlášení chyb a požadavky na funkce](https://github.com/microsoft/azd-for-beginners/issues)
- **Dotazy k učení**: [Microsoft Azure Discord komunitní kanál](https://discord.gg/microsoft-azure) a [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **AI-specifická pomoc**: Připojte se do [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **Dokumentace**: [Oficiální dokumentace Azure Developer CLI](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)

### Přehled komunity z Microsoft Foundry Discordu

**Aktuální výsledky ankety z kanálu #Azure:**
- **45 %** vývojářů chce používat AZD pro AI úlohy
- **Hlavní výzvy**: Nasazení více služeb, správa přihlašovacích údajů, připravenost do produkce  
- **Nejčastější požadavky**: AI-specifické šablony, průvodce řešením problémů, osvědčené postupy

**Připojte se k naší komunitě a:**
- Sdílejte zkušenosti s AZD + AI a získejte pomoc
- Získejte přístup k raným náhledům nových AI šablon
- Přispívejte k osvědčeným postupům nasazování AI
- Ovlivněte vývoj budoucích funkcí AI + AZD

### Přispívání do kurzu
Vítáme přispění! Prosím, přečtěte si náš [Průvodce přispěvateli](CONTRIBUTING.md) pro podrobnosti o:
- **Vylepšení obsahu**: Zdokonalování kapitol a příkladů
- **Nové příklady**: Přidání reálných scénářů a šablon  
- **Překlady**: Pomozte s udržením vícejazyčné podpory
- **Hlásení chyb**: Zlepšení přesnosti a srozumitelnosti
- **Standardy komunity**: Dodržujte naše pravidla inkluzivní komunity

---

## 📄 Informace o kurzu

### Licence
Tento projekt je licencován pod licencí MIT - podrobnosti naleznete v souboru [LICENSE](../../LICENSE).

### Související vzdělávací zdroje Microsoft Learn

Náš tým vytváří další komplexní výukové kurzy:

<!-- CO-OP TRANSLATOR OTHER COURSES START -->
### LangChain
[![LangChain4j pro začátečníky](https://img.shields.io/badge/LangChain4j%20for%20Beginners-22C55E?style=for-the-badge&&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchain4j-for-beginners)
[![LangChain.js pro začátečníky](https://img.shields.io/badge/LangChain.js%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchainjs-for-beginners?WT.mc_id=m365-94501-dwahlin)

---

### Azure / Edge / MCP / Agent
[![AZD pro začátečníky](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Edge AI pro začátečníky](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![MCP pro začátečníky](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)
[![AI Agents pro začátečníky](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Série Generativní AI
[![Generativní AI pro začátečníky](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Generativní AI (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
[![Generativní AI (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)
[![Generativní AI (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---
 
### Základní výuka
[![ML pro začátečníky](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![Data Science for Beginners](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![AI for Beginners](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Cybersecurity for Beginners](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Web Dev for Beginners](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![IoT for Beginners](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![XR Development for Beginners](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Série Copilot
[![Copilot for AI Paired Programming](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![Copilot for C#/.NET](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Copilot Adventure](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ Navigace kurzem

**🚀 Připraven začít se učit?**

**Začátečníci**: Začněte [Kapitolou 1: Základy a rychlý start](../..)  
**Vývojáři AI**: Přeskočte na [Kapitolu 2: Vývoj zaměřený na AI](../..)  
**Zkušení vývojáři**: Začněte [Kapitolu 3: Konfigurace a autentizace](../..)

**Další kroky**: [Začněte Kapitolu 1 - Základy AZD](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Upozornění**:  
Tento dokument byl přeložen pomocí služby automatického překladu AI [Co-op Translator](https://github.com/Azure/co-op-translator). I když usilujeme o přesnost, mějte prosím na paměti, že automatické překlady mohou obsahovat chyby nebo nepřesnosti. Původní dokument v jeho mateřském jazyce by měl být považován za autoritativní zdroj. Pro důležité informace se doporučuje profesionální lidský překlad. Nebereme odpovědnost za jakékoliv nedorozumění nebo chybné výklady vyplývající z použití tohoto překladu.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->