<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T14:14:09+00:00",
  "source_file": "README.md",
  "language_code": "sw"
}
-->
> Kumbuka: Nyaraka hizi zinaendelea kusasishwa ili kuonyesha mabadiliko ya hivi karibuni.

> ⚠️ Hifadhi hii ni maonyesho yaliyoandaliwa kuonyesha
> utafsiri wa nyaraka kiotomatiki kwa kutumia Localizeflow.
>
> Yaliyomo ya awali yanatokana na
> mradi wa Microsoft uitwao “AZD kwa Waanzilishi”.


# AZD Kwa Waanzilishi: Safari ya Kujifunza Yenye Muundo

![AZD-for-beginners](../../translated_images/azdbeginners.5527441dd9f74068.sw.png) 

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## Kuanzia na Kozi Hii

Fuata hatua hizi kuanza safari yako ya kujifunza AZD:

1. **Fungua Hifadhi**: Bonyeza [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)
2. **Nakili Hifadhi**: `git clone https://github.com/microsoft/azd-for-beginners.git`
3. **Jiunge na Jamii**: [Jamii za Azure Discord](https://discord.com/invite/ByRwuEEgH4) kwa msaada wa wataalamu
4. **Chagua Njia ya Kujifunza**: Chagua sura hapa chini inayoendana na kiwango chako cha uzoefu

### Usaidizi wa Lugha Nyingi

#### Utafisiri wa Kiotomatiki (Daima Ukiwa wa Kisasa)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](./README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Unapendelea Nakili Kwenye Kioshi?**

> Hifadhi hii inajumuisha tafsiri za lugha zaidi ya 50 zinazoongeza kiasi cha kupakua sana. Ili kunakili bila tafsiri, tumia sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Hii itakupa kila unachohitaji kumaliza kozi kwa upakuaji wa haraka zaidi.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## Muhtasari wa Kozi

Jizoeze Azure Developer CLI (azd) kupitia sura zilizoandaliwa kwa ajili ya kujifunza kidogo kidogo. **Mkazo maalum juu ya usambazaji wa programu za AI kwa integrasiyo ya Microsoft Foundry.**

### Kwa Nini Kozi Hii ni Muhimu kwa Waendelezaji wa Kisasa

Kulingana na maoni kutoka jamii ya Microsoft Foundry Discord, **45% ya waendelezaji wanataka kutumia AZD kwa mzigo wa kazi wa AI** lakini wanakutana na changamoto za:
- Miundo tata ya huduma nyingi za AI
- Mbinu bora za kusambaza AI kwenye uzalishaji  
- Integrasiyo na usanidi wa huduma za AI za Azure
- Uboreshaji wa gharama kwa mzigo wa kazi za AI
- Kufafanua na kutatua matatizo maalum ya usambazaji wa AI

### Malengo ya Kujifunza

Kwa kumaliza kozi hii yenye muundo, utakuwa umekamilisha:
- **Uwezo wa Msingi wa AZD**: Dhana za msingi, usakinishaji, na usanidi
- **Sambaza Programu za AI**: Tumia AZD na huduma za Microsoft Foundry
- **Tekeleza Miundombinu kama Msimbo**: Simamia rasilimali za Azure iwe kwa kutumia templeti za Bicep
- **Tatua Matatizo ya Usambazaji**: Rekebisha shida za kawaida na kufanyia debugger matatizo
- **Boreshaji kwa Uzalishaji**: Usalama, upanuaji, ufuatiliaji, na usimamizi wa gharama
- **Jenga Suluhisho za Wakala Wengi**: Sambaza miundo tata ya AI

## 📚 Sura za Kujifunza

*Chagua njia yako ya kujifunza kulingana na kiwango cha uzoefu na malengo*

### 🚀 Sura 1: Msingi & Anza Haraka  
**Vigezo vya awali**: Usajili wa Azure, maarifa ya msingi ya mstari wa amri  
**Muduu ya muda**: Dakika 30-45  
**Ungumu**: ⭐

#### Utafundishwa nini
- Kuelewa msingi wa Azure Developer CLI
- Kusakinisha AZD kwenye jukwaa lako
- Usambazaji wako wa kwanza wenye mafanikio

#### Rasilimali za Kujifunza
- **🎯 Anza Hapa**: [Azure Developer CLI ni Nini?](../..)
- **📖 Nadharia**: [Misingi ya AZD](docs/getting-started/azd-basics.md) - Dhana na istilahi kuu
- **⚙️ Usanidi**: [Usakinishaji & Usanidi](docs/getting-started/installation.md) - Mwongozo wa jukwaa
- **🛠️ Vitendo**: [Mradi Wako wa Kwanza](docs/getting-started/first-project.md) - Mafunzo kwa hatua
- **📋 Marejeo ya Haraka**: [Karata ya Amri](resources/cheat-sheet.md)

#### Mafunzo ya Vitendo
```bash
# Ukaguzi wa usakinishaji wa haraka
azd version

# Weka programu yako ya kwanza
azd init --template todo-nodejs-mongo
azd up
```

**💡 Matokeo ya Sura**: Kusambaza programu rahisi ya wavuti kwenye Azure kwa kutumia AZD

**✅ Uthibitisho wa Mafanikio:**
```bash
# Baada ya kumaliza Sura ya 1, unapaswa kuwa na uwezo wa:
azd version              # Inaonyesha toleo lililowekwa
azd init --template todo-nodejs-mongo  # Huanzisha mradi
azd up                  # Hupeleka kwenye Azure
azd show                # Inaonyesha URL ya programu inayotumika
# Programu hufunguka kwenye kivinjari na inafanya kazi
azd down --force --purge  # Hufuta rasilimali
```

**📊 Muda Uliotumika:** Dakika 30-45  
**📈 Kiwango cha Ujuzi Baada:** Unaweza kusambaza programu za msingi bila mshono

**✅ Uthibitisho wa Mafanikio:**
```bash
# Baada ya kumaliza Sura ya 1, unapaswa kuwa na uwezo wa:
azd version              # Inaonyesha toleo lililosanikishwa
azd init --template todo-nodejs-mongo  # Inaanzisha mradi
azd up                  # Inaeneza kwenye Azure
azd show                # Inaonyesha URL ya app inayotumika
# Programu inafunguka kwenye kivinjari na inafanya kazi
azd down --force --purge  # Inasafisha rasilimali
```

**📊 Muda Uliotumika:** Dakika 30-45  
**📈 Kiwango cha Ujuzi Baada:** Unaweza kusambaza programu za msingi bila mshono

---

### 🤖 Sura 2: Maendeleo ya Kwanza ya AI (Inapendekezwa kwa Waendelezaji AI)
**Vigezo vya awali**: Sura 1 imekamilika  
**Muduu ya muda**: Saa 1-2  
**Ungumu**: ⭐⭐

#### Utafundishwa nini
- Integrasiyo ya Microsoft Foundry na AZD
- Kusambaza programu zenye nguvu za AI
- Kuelewa usanidi wa huduma za AI

#### Rasilimali za Kujifunza
- **🎯 Anza Hapa**: [Integrasiyo ya Microsoft Foundry](docs/microsoft-foundry/microsoft-foundry-integration.md)
- **📖 Mifumo**: [Usambazaji wa Mfano wa AI](docs/microsoft-foundry/ai-model-deployment.md) - Sambaza na simamia mifano ya AI
- **🛠️ Warsha**: [Warsha ya AI](docs/microsoft-foundry/ai-workshop-lab.md) - Tengeneza suluhisho za AI tayari kwa AZD
- **🎥 Mwongozo wa Kiingilio**: [Vifaa vya Warsha](workshop/README.md) - Kujifunza kupitia kivinjari kwa MkDocs * Mazingira ya DevContainer
- **📋 Templeti**: [Templeti za Microsoft Foundry](../..)
- **📝 Mifano**: [Mifano ya Usambazaji ya AZD](examples/README.md)

#### Mafunzo ya Vitendo
```bash
# Tengeneza programu yako ya kwanza ya AI
azd init --template azure-search-openai-demo
azd up

# Jaribu template nyingine za AI
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```

**💡 Matokeo ya Sura**: Sambaza na usanidi programu ya mazungumzo yenye nguvu za AI yenye uwezo wa RAG

**✅ Uthibitisho wa Mafanikio:**
```bash
# Baada ya Sura ya 2, unapaswa kuwa na uwezo wa:
azd init --template azure-search-openai-demo
azd up
# Jaribu kiolesura cha mazungumzo cha AI
# Uliza maswali na upate majibu yanayotokana na AI yenye vyanzo
# Thibitisha kuwa muunganisho wa utafutaji unafanya kazi
azd monitor  # Angalia kuwa Application Insights inaonyesha telemetry
azd down --force --purge
```

**📊 Muda Uliotumika:** Saa 1-2  
**📈 Kiwango cha Ujuzi Baada:** Unaweza kusambaza na kusanidi programu za AI tayari kwa uzalishaji  
**💰 Uelewa wa Gharama:** Fahamu gharama za maendeleo $80-150/mwezi, gharama za uzalishaji $300-3500/mwezi

#### 💰 Mambo ya Kuweka Akilini Kuhusu Gharama za Usambazaji wa AI

**Mazingira ya Maendeleo (Kiwango cha Makadirio $80-150/mwezi):**
- Azure OpenAI (Lipa kwa matumizi): $0-50/mwezi (kutegemea matumizi ya tokeni)
- AI Search (Kidokezo cha msingi): $75/mwezi
- Container Apps (Matumizi): $0-20/mwezi
- Hifadhi (Kawaida): $1-5/mwezi

**Mazingira ya Uzalishaji (Kiwango cha Makadirio $300-3,500+/mwezi):**
- Azure OpenAI (PTU kwa utendakazi thabiti): $3,000+/mwezi AU Lipa kwa matumizi yenye kiasi kikubwa
- AI Search (Kidokezo cha kawaida): $250/mwezi
- Container Apps (Zilizotengwa): $50-100/mwezi
- Application Insights: $5-50/mwezi
- Hifadhi (Premium): $10-50/mwezi

**💡 Vidokezo vya Kuboresha Gharama:**
- Tumia **Kiwango cha Bure** cha Azure OpenAI kwa ajili ya kujifunza (tokeni 50,000 kwa mwezi ni pamoja)
- Endesha `azd down` kuondoa rasilimali wakati huhariri tena kwa sasa
- Anza kwa bili ya kulipia kwa matumizi, boresha hadi PTU kwa uzalishaji tu
- Tumia `azd provision --preview` kukadiria gharama kabla ya usambazaji
- Washa upanuzi wa kiotomatiki: lipa tu kwa matumizi halisi

**Ufuatiliaji wa Gharama:**
```bash
# Angalia makadirio ya gharama za mwezi
azd provision --preview

# Fuatilia gharama halisi katika Azure Portal
az consumption budget list --resource-group <your-rg>
```

---

### ⚙️ Sura 3: Usanidi na Uthibitishaji  
**Vigezo vya awali**: Sura 1 imekamilika  
**Muduu ya muda**: Dakika 45-60  
**Ungumu**: ⭐⭐

#### Utafundishwa nini
- Usanidi na usimamizi wa mazingira
- Mbinu bora za uthibitishaji na usalama
- Kuitambulisha na kupanga rasilimali

#### Rasilimali za Kujifunza
- **📖 Usanidi**: [Mwongozo wa Usanidi](docs/getting-started/configuration.md) - Usanidi wa mazingira
- **🔐 Usalama**: [Mifumo ya uthibitishaji na utambulisho unaodhibitiwa](docs/getting-started/authsecurity.md) - Mifumo ya uthibitishaji
- **📝 Mifano**: [Mfano wa Programu ya Hifadhidata](examples/database-app/README.md) - Mifano ya AZD ya Hifadhidata

#### Mafunzo ya Vitendo
- Sanidi mazingira mengi (dev, staging, prod)
- Weka uthibitishaji wa utambulisho unaodhibitiwa
- Tekeleza usanidi maalum kwa kila mazingira

**💡 Matokeo ya Sura**: Simamia mazingira mengi kwa uthibitishaji na usalama stahiki

---

### 🏗️ Sura 4: Miundombinu kama Msimbo & Usambazaji  
**Vigezo vya awali**: Sura 1-3 zimekamilika  
**Muduu ya muda**: Saa 1-1.5  
**Ungumu**: ⭐⭐⭐

#### Utafundishwa nini
- Mifumo ya usambazaji yenye maendeleo zaidi
- Miundombinu kama Msimbo kwa kutumia Bicep
- Mikakati ya upangaji wa rasilimali

#### Rasilimali za Kujifunza
- **📖 Usambazaji**: [Mwongozo wa Usambazaji](docs/deployment/deployment-guide.md) - Mchezo kamili wa kazi
- **🏗️ Kuandaa Rasilimali**: [Usimamizi wa Rasilimali za Azure](docs/deployment/provisioning.md) - Usimamizi wa rasilimali za Azure
- **📝 Mifano**: [Mfano wa Programu ya Container](../../examples/container-app) - Usambazaji wa kuanzisha kwa container

#### Mafunzo ya Vitendo
- Tengeneza templeti za Bicep za kibinafsi
- Sambaza programu zenye huduma nyingi
- Tekeleza mikakati ya usambazaji ya blue-green

**💡 Matokeo ya Sura**: Sambaza programu tata za huduma nyingi kwa kutumia templeti za kiundombinu ulizoandaa binafsi

---
### 🎯 Sura ya 5: Suluhisho za AI za Wakala Wengi (Zaidi)
**Mahitaji**: Surah 1-2 zimekamilika  
**Muda**: Masaa 2-3  
**Ugumu**: ⭐⭐⭐⭐

#### Utajifunza Nini
- Mifumo ya usanifu wa wakala wengi
- Usimamizi na uratibu wa wakala
- Utekelezaji wa AI tayari kwa uzalishaji

#### Vyanzo vya Kujifunza
- **🤖 Mradi Ulioangaziwa**: [Suluhisho la Wakala Wengi la Rejareja](examples/retail-scenario.md) - Utekelezaji kamili
- **🛠️ Templates za ARM**: [Kifurushi cha Template za ARM](../../examples/retail-multiagent-arm-template) - Utekelezaji kwa bonyeza moja
- **📖 Usanifu**: [Mifumo ya uratibu wa wakala wengi](/docs/pre-deployment/coordination-patterns.md) - Mifumo

#### Mazoezi ya Vitendo
```bash
# Tengeneza suluhisho kamili la mawakala wengi la rejareja
cd examples/retail-multiagent-arm-template
./deploy.sh

# Chunguza usanidi wa mawakala
az deployment group show --resource-group <rg-name> --name <deployment-name>
```

**💡 Matokeo ya Sura**: Tekeleza na usimamishe suluhisho la AI la wakala wengi tayari kwa uzalishaji pamoja na mawakala wa Mteja na Hisa

---

### 🔍 Sura ya 6: Uthibitishaji na Mipango ya Kabla ya Utekelezaji
**Mahitaji**: Sura 4 imekamilika  
**Muda**: Saa 1  
**Ugumu**: ⭐⭐

#### Utajifunza Nini
- Mipango ya uwezo na uthibitishaji wa rasilimali
- Mikakati ya uchaguzi wa SKU
- Ukaguzi wa kabla ya kuanza na uendeshaji wa moja kwa moja

#### Vyanzo vya Kujifunza
- **📊 Mipango**: [Mipango ya Uwezo](docs/pre-deployment/capacity-planning.md) - Uthibitishaji wa rasilimali
- **💰 Uchaguzi**: [Uchaguzi wa SKU](docs/pre-deployment/sku-selection.md) - Chaguzi za gharama nafuu
- **✅ Uthibitishaji**: [Ukaguzi wa Kabla ya Kuanzisha](docs/pre-deployment/preflight-checks.md) - Skripti za moja kwa moja

#### Mazoezi ya Vitendo
- Endesha skripti za uthibitishaji wa uwezo
- Boresha uchaguzi wa SKU kwa gharama
- Tekeleza ukaguzi wa moja kwa moja kabla ya utekelezaji

**💡 Matokeo ya Sura**: Thibitisha na boresha utekelezaji kabla ya kuanza

---

### 🚨 Sura ya 7: Utatuzi wa Matatizo na Urekebishaji
**Mahitaji**: Surah yoyote ya utekelezaji imekamilika  
**Muda**: Saa 1-1.5  
**Ugumu**: ⭐⭐

#### Utajifunza Nini
- Njia za kawaida za urekebishaji matatizo
- Masuala ya kawaida na suluhisho
- Utatuzi maalum wa matatizo ya AI

#### Vyanzo vya Kujifunza
- **🔧 Masuala ya Kawaida**: [Masuala ya Kawaida](docs/troubleshooting/common-issues.md) - Maswali na majibu
- **🕵️ Urekebishaji**: [Mwongozo wa Urekebishaji](docs/troubleshooting/debugging.md) - Mikakati hatua kwa hatua
- **🤖 Masuala ya AI**: [Utatuzi Maalum wa AI](docs/troubleshooting/ai-troubleshooting.md) - Matatizo ya huduma za AI

#### Mazoezi ya Vitendo
- Tambua sababu za kushindwa kwa utekelezaji
- Rekebisha matatizo ya uthibitishaji
- Rekebisha matatizo ya muunganisho wa huduma za AI

**💡 Matokeo ya Sura**: Tambua na utatuze matatizo ya kawaida ya utekelezaji kwa kujitegemea

---

### 🏢 Sura ya 8: Mifumo ya Uzalishaji na Kampuni
**Mahitaji**: Surah 1-4 zimekamilika  
**Muda**: Masaa 2-3  
**Ugumu**: ⭐⭐⭐⭐

#### Utajifunza Nini
- Mikakati ya utekelezaji wa uzalishaji
- Mifumo ya usalama wa shirika
- Ufuatiliaji na uboreshaji wa gharama

#### Vyanzo vya Kujifunza
- **🏭 Uzalishaji**: [Mbinu Bora za AI kwa Uzalishaji](docs/microsoft-foundry/production-ai-practices.md) - Mifumo ya shirika
- **📝 Mifano**: [Mfano wa Microservices](../../examples/microservices) - Mifumo tata
- **📊 Ufuatiliaji**: [Muungano wa Application Insights](docs/pre-deployment/application-insights.md) - Ufuatiliaji

#### Mazoezi ya Vitendo
- Tekeleza mifumo ya usalama wa shirika
- Weka ufuatiliaji kamili
- Tekeleza kwa uzalishaji kwa usimamizi sahihi

**💡 Matokeo ya Sura**: Tekeleza programu za shirika zenye uwezo kamili wa uzalishaji

---

## 🎓 Muhtasari wa Warsha: Uzoefu wa Kujifunza wa Vitendo

> **⚠️ HALI YA WARSHA: Maendeleo Hai**  
> Vifaa vya warsha vinaendelea kuandaliwa na kuboreshwa. Moduli kuu zinafanya kazi, lakini baadhi ya sehemu za juu hazijakamilika. Tunaendelea kuhakikisha maudhui yote yatakamilika. [Fuata maendeleo →](workshop/README.md)

### Vifaa vya Warsha Yenye Mwingiliano
**Uzoefu kamili wa kujifunza wa vitendo ukitumia zana za kivinjari na mazoezi yaliyofundishwa**

Vifaa vya warsha vinatoa uzoefu wa kujifunza uliopangwa, unaowezesha kujifunza kiurahisi sambamba na mtaala wa sura ulio hapo juu. Warsha imeundwa kwa ajili ya kujifunza kwa kasi binafsi na pia kwa kipindi chini ya mwalimu.

#### 🛠️ Sifa za Warsha
- **Muonekano wa Kivinjari**: Warsha iliyo kamilika yenye MkDocs na vipengele vya utafutaji, nakala, na mandhari
- **Muungano na GitHub Codespaces**: Kuanzisha mazingira ya maendeleo kwa bonyeza moja
- **Njia ya Kujifunza Iliyo Pangiliwa**: Mazoezi 7 yanayoongozwa (saa 3.5 jumla)
- **Ugunduzi → Utekelezaji → Urekebishaji**: Mbinu ya hatua kwa hatua
- **Mazingira ya DevContainer yenye Mwingiliano**: Zana na utegemezi tayari umewekwa

#### 📚 Muundo wa Warsha
Warsha inafuata mbinu ya **Ugunduzi → Utekelezaji → Urekebishaji**:

1. **Awamu ya Ugunduzi** (dakika 45)
   - Chunguza templates na huduma za Microsoft Foundry
   - Elewa mifumo ya usanifu wa wakala wengi
   - Pitia mahitaji na yanayotakiwa kabla ya utekelezaji

2. **Awamu ya Utekelezaji** (masaa 2)
   - Tekeleza vitendo utekelezaji wa programu za AI kwa kutumia AZD
   - Sanidi huduma za Azure AI na viunganishi
   - Tekeleza mifumo ya usalama na uthibitishaji

3. **Awamu ya Urekebishaji** (dakika 45)
   - Badilisha programu kwa matumizi maalum
   - Boresha kwa ajili ya utekelezaji wa uzalishaji
   - Tekeleza ufuatiliaji na usimamizi wa gharama

#### 🚀 Anza na Warsha
```bash
# Chaguo 1: GitHub Codespaces (Inapendekezwa)
# Bonyeza "Code" → "Create codespace on main" kwenye hifadhi

# Chaguo 2: Maendeleo ya Ndani
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# Fuata maagizo ya usanidi katika workshop/README.md
```

#### 🎯 Matokeo ya Kujifunza Warsha
Kwa kukamilisha warsha, washiriki wataweza:
- **Tekeleza Programu za AI kwa Uzalishaji**: Tumia AZD na huduma za Microsoft Foundry
- **Zoeza Mifumo ya Wakala Wengi**: Tekeleza suluhisho za wakala wa AI zinazoendeshwa kwa ushirikiano
- **Tekeleza Mbinu Bora za Usalama**: Sanidi uthibitishaji na udhibiti wa upatikanaji
- **Boreshaji kwa Wiani**: Tengeneza utekelezaji wa gharama nafuu na wenye utendaji mzuri
- **Tatua Matatizo ya Utekelezaji**: Rekebisha matatizo ya kawaida kwa kujitegemea

#### 📖 Vyanzo vya Warsha
- **🎥 Mwongozo Mwingiliano**: [Vifaa vya Warsha](workshop/README.md) - Mazingira ya kujifunza kupitia kivinjari
- **📋 Maelekezo Hatua kwa Hatua**: [Mazoezi ya Kuelekezwa](../../workshop/docs/instructions) - Mwongozo wa kina
- **🛠️ Maabara ya Warsha ya AI**: [Maabara ya Warsha ya AI](docs/microsoft-foundry/ai-workshop-lab.md) - Mazoezi ya AI
- **💡 Anza Haraka**: [Mwongozo wa Usanidi wa Warsha](workshop/README.md#quick-start) - Usanidi wa mazingira

**Inafaa kwa**: Mafunzo ya kampuni, kozi za vyuo vikuu, kujifunza binafsi, na mafunzo ya watengenezaji.

---

## 📖 Azure Developer CLI ni Nini?

Azure Developer CLI (azd) ni interface ya mstari wa amri inayolenga watengenezaji ambayo huharakisha mchakato wa kujenga na kupeleka programu kwenye Azure. Inatoa:

- **Utekelezaji kwa kutumia templates** - Tumia templates zilizojengwa kwa mifumo ya kawaida ya programu
- **Miundombinu kama Msimbo** - Simamia rasilimali za Azure kwa kutumia Bicep au Terraform  
- **Mtiririko wa kazi uliounganishwa** - Tengeneza, tekeleza, na fuatilia programu bila usumbufu
- **Raha kwa watengenezaji** - Imeboreshwa kwa ajili ya uzalishaji na uzoefu wa mtengenezaji

### **AZD + Microsoft Foundry: Kamili kwa Utekelezaji wa AI**

**Kwanini AZD kwa Suluhisho za AI?** AZD inashughulikia changamoto kuu zinazowakabili waendelezaji wa AI:

- **Templates Tayari kwa AI** - Templates zilizosanidiwa kwa Azure OpenAI, Huduma za Cognitive, na majukumu ya ML
- **Utekelezaji Salama wa AI** - Mifumo ya usalama kwa huduma za AI, funguo za API, na viunganishi vya modeli  
- **Mifumo Bora ya AI kwa Uzalishaji** - Mbinu bora za utekelezaji wa programu za AI zinazoweza kupanuka na gharama nafuu
- **Mtiririko wa Kazi wa AI Kuanzia Mwanzo hadi Uzalishaji** - Kuanzia maendeleo ya modeli hadi utekelezaji kwa ufuatiliaji sahihi
- **Uboreshaji wa Gharama** - Mikakati ya usambazaji rasilimali na upanuzi kwa majukumu ya AI
- **Muungano na Microsoft Foundry** - Muunganisho mzuri wa Orodha ya modeli na viunganishi vya Microsoft Foundry

---

## 🎯 Maktaba ya Templates & Mifano

### Ilioangaziwa: Templates za Microsoft Foundry
**Anza hapa ikiwa unatekeleza programu za AI!**

> **Kumbuka:** Templates hizi zinaonyesha mifano mbalimbali ya AI. Baadhi ni Sampuli za Azure za nje, wengine ni utekelezaji wa ndani.

| Template | Sura | Ugumu | Huduma | Aina |
|----------|---------|------------|----------|------|
| [**Anza na mazungumzo ya AI**](https://github.com/Azure-Samples/get-started-with-ai-chat) | Sura 2 | ⭐⭐ | AzureOpenAI + Azure AI Model Inference API + Azure AI Search + Azure Container Apps + Application Insights | Nje |
| [**Anza na mawakala wa AI**](https://github.com/Azure-Samples/get-started-with-ai-agents) | Sura 2 | ⭐⭐ | Azure AI Agent Service + AzureOpenAI + Azure AI Search + Azure Container Apps + Application Insights| Nje |
| [**Demo ya Azure Search + OpenAI**](https://github.com/Azure-Samples/azure-search-openai-demo) | Sura 2 | ⭐⭐ | AzureOpenAI + Azure AI Search + App Service + Storage | Nje |
| [**Anza Haraka ya App ya OpenAI Chat**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Sura 2 | ⭐ | AzureOpenAI + Container Apps + Application Insights | Nje |
| [**Agent OpenAI Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Sura 5 | ⭐⭐⭐ | AzureOpenAI + Azure Functions + Prompty | Nje |
| [**Contoso Chat RAG**](https://github.com/Azure-Samples/contoso-chat) | Sura 8 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Cosmos DB + Container Apps | Nje |
| [**Suluhisho la Wakala Wengi la Rejareja**](examples/retail-scenario.md) | Sura 5 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Storage + Container Apps + Cosmos DB | **Ndani** |

### Ilioangaziwa: Mifano Kamili ya Kujifunza
**Templates za programu tayari kwa uzalishaji zinazolingana na sura za kujifunza**

| Template | Sura ya Kujifunza | Ugumu | Msingi wa Kujifunza |
|----------|------------------|------------|--------------|
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Sura 2 | ⭐ | Mifumo ya msingi ya utekelezaji wa AI |
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Sura 2 | ⭐⭐ | Utekelezaji wa RAG na Azure AI Search |
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | Sura 4 | ⭐⭐ | Uingizaji wa Akili ya Nyaraka |
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Sura 5 | ⭐⭐⭐ | Mfumo wa wakala na uitoaji wa simu |
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | Sura 8 | ⭐⭐⭐ | Uratibu wa AI wa shirika |
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | Sura 5 | ⭐⭐⭐⭐ | Mifumo ya wakala wengi na mawakala wa Mteja na Hisa |

### Kujifunza kwa Aina ya Mfano

> **📌 Mifano ya Ndani dhidi ya Nje:**  
> **Mifano ya Ndani** (kwenye hii repo) = Tayari kutumika mara moja  
> **Mifano ya Nje** (Sampuli za Azure) = Nakili kutoka kwa repo zilizo kwenye viungo

#### Mifano ya Ndani (Tayari Kutumika)
- [**Suluhisho la Wakala Wengi la Rejareja**](examples/retail-scenario.md) - Utekelezaji kamili tayari kwa uzalishaji pamoja na templates za ARM
  - Mifumo ya wakala wengi (Mteja + Wakala wa Hisa)
  - Ufuatiliaji na tathmini kamili
  - Utekelezaji kwa bonyeza moja kupitia template ya ARM

#### Mifano ya Ndani - Programu za Kontena (Sura 2-5)
**Mifano kamili ya utekelezaji wa kontena kwenye repo hii:**
- [**Mifano ya Programu za Kontena**](examples/container-app/README.md) - Mwongozo kamili wa utekelezaji wa kontena
  - [API Rahisi ya Flask](../../examples/container-app/simple-flask-api) - API ya msingi ya REST yenye upanuzi hadi sifuri
  - [Usanifu wa Microservices](../../examples/container-app/microservices) - Utekelezaji wa huduma nyingi tayari kwa uzalishaji
  - Mifano ya Anza Haraka, Uzalishaji, na Mifumo ya Juu
  - Mwongozo wa ufuatiliaji, usalama, na uboreshaji wa gharama

#### Mifano ya Nje - Programu Rahisi (Sura 1-2)
**Nakili repo hizi za Sampuli za Azure kuanza:**
- [Programu Rahisi ya Wavuti - Node.js + MongoDB](https://github.com/Azure-Samples/todo-nodejs-mongo) - Mifumo ya msingi ya utekelezaji
- [Tovuti Immuiwa - React SPA](https://github.com/Azure-Samples/todo-csharp-sql-swa-func) - Utekelezaji wa maudhui ya takatifu
- [Programu ya Kontena - Python Flask](https://github.com/Azure-Samples/container-apps-store-api-microservice) - Utekelezaji wa API ya REST

#### Mifano ya Nje - Uingizaji wa Database (Sura 3-4)  
- [Programu ya Database - C# + SQL](https://github.com/Azure-Samples/todo-csharp-sql) - Mifumo ya muunganisho wa database
- [Funguo + Cosmos DB](https://github.com/Azure-Samples/todo-python-mongo-swa-func) - Mtiririko wa data usio na seva

#### Mifano ya Nje - Mifumo ya Juu (Sura 4-8)
- [Microservices za Java](https://github.com/Azure-Samples/java-microservices-aca-lab) - Mifumo ya huduma nyingi
- [Jobs za Container Apps](https://github.com/Azure-Samples/container-apps-jobs) - Uendeshaji wa kazi za nyuma  
- [Mpangilio wa ML wa Shirika](https://github.com/Azure-Samples/mlops-v2) - Mifumo ya ML tayari kwa uzalishaji

### Maktaba za Templates za Nje
- [**Makusanyo Rasmi ya Violezo vya AZD**](https://azure.github.io/awesome-azd/) - Mkusanyiko ulioratibiwa wa violezo rasmi na vya jumuiya
- [**Violezo vya Azure Developer CLI**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - Nyaraka za violezo za Microsoft Learn
- [**Kabrasha la Mifano**](examples/README.md) - Mifano ya kujifunza ya ndani yenye maelezo ya kina

---

## 📚 Vyanzo vya Kujifunza & Marejeleo

### Marejeleo ya Haraka
- [**Karatasi ya Amri**](resources/cheat-sheet.md) - Amri muhimu za azd zilizo pangwa kwa sura
- [**Fasili**](resources/glossary.md) - Istilahi za Azure na azd  
- [**Maswali Yanayoulizwa Mara kwa Mara**](resources/faq.md) - Maswali ya kawaida yaliyopangwa kwa sura za kujifunza
- [**Mwongozo wa Kusoma**](resources/study-guide.md) - Mazoezi kamili ya vitendo

### Warsha za Vitendo
- [**Warsha ya AI**](docs/microsoft-foundry/ai-workshop-lab.md) - Fanya suluhisho zako za AI ziweze kuzinduliwa na AZD (saa 2-3)
- [**Mwongozo wa Warsha ya Kihusishaji**](workshop/README.md) - Warsha ya kivinjari inayotumia MkDocs na Mazingira ya DevContainer
- [**Njia ya Kujifunza Iliyopangwa**](../../workshop/docs/instructions) - Mazoezi ya hatua 7 yaliyoongozwa (Ugunduzi → Utekelezaji → Urekebishaji)
- [**Warsha ya AZD Kwa Waanzilishi**](workshop/README.md) - Vifaa kamili vya warsha ya vitendo ikiwa na ushirikiano wa GitHub Codespaces

### Vyanzo vya Kujifunza vya Nje
- Nyaraka za Azure Developer CLI (https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)
- Kituo cha Usanifu wa Azure (https://learn.microsoft.com/en-us/azure/architecture/)
- Kihesabu bei cha Azure (https://azure.microsoft.com/pricing/calculator/)
- Hali ya Azure (https://status.azure.com/)

---

## 🔧 Mwongozo wa Haraka wa Utatuzi wa Matatizo

**Matatizo ya kawaida yanayokumbukwa na waanzilishi na suluhisho za haraka:**

### ❌ "azd: amri haikupatikana"

```bash
# Sakinisha AZD kwanza
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Thibitisha usakinishaji
azd version
```

### ❌ "Hakuna usajili uliopatikana" au "Usajili haujawekewa"

```bash
# Orodhesha usajili unaopatikana
az account list --output table

# Weka usajili wa chaguo-msingi
az account set --subscription "<subscription-id-or-name>"

# Weka kwa mazingira ya AZD
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Thibitisha
az account show
```

### ❌ "InsufficientQuota" au "Kiasi kimetanguliwa"

```bash
# Jaribu eneo tofauti la Azure
azd env set AZURE_LOCATION "westus2"
azd up

# Au tumia SKUs ndogo katika maendeleo
# Hariri infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```

### ❌ "azd up" imeshindwa katikati

```bash
# Chaguo 1: Safisha na jaribu tena
azd down --force --purge
azd up

# Chaguo 2: Rekebisha miundombinu tu
azd provision

# Chaguo 3: Angalia kumbukumbu za kina
azd show
azd logs
```

### ❌ "Uthibitishaji umeshindikana" au "Kipindi cha token kimekwisha"

```bash
# Thibitisha tena
az logout
az login

azd auth logout
azd auth login

# Thibitisha uthibitishaji
az account show
```

### ❌ "Rasilimali tayari ipo" au migogoro ya majina

```bash
# AZD huunda majina ya kipekee, lakini ikiwa kuna mgongano:
azd down --force --purge

# Kisha jaribu tena kwa mazingira mapya
azd env new dev-v2
azd up
```

### ❌ Utekelezaji wa kiolezo unachukua muda mrefu sana

**Muda wa kusubiri wa kawaida:**
- Programu rahisi ya wavuti: dakika 5-10
- Programu yenye hifadhidata: dakika 10-15
- Programu za AI: dakika 15-25 (Upatikanaji wa OpenAI ni mzito)

```bash
# Angalia maendeleo
azd show

# Ikiwa umekwama kwa zaidi ya dakika 30, angalia Azure Portal:
azd monitor
# Tafuta uanzishaji ulioshindwa
```

### ❌ "Ruhusa imetolewa" au "Imezuiwa"

```bash
# Angalia nafasi yako ya Azure
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Unahitaji angalau nafasi ya "Contributor"
# Muombe msimamizi wako wa Azure kupewa:
# - Contributor (kwa rasilimali)
# - Msimamizi wa Upatikanaji wa Mtumiaji (kwa uteuzi wa nafasi)
```

### ❌ Haiwezi kupata anwani ya programu iliyotekelezwa

```bash
# Onyesha vituo vyote vya huduma
azd show

# Au fungua Portal ya Azure
azd monitor

# Angalia huduma maalum
azd env get-values
# Tazama kwa ajili ya mabadiliko ya *_URL
```

### 📚 Vyanzo Kamili vya Utatuzi wa Matatizo

- **Mwongozo wa Matatizo ya Kawaida:** [Suluhisho Zaidi](docs/troubleshooting/common-issues.md)
- **Matatizo Maalum ya AI:** [Utatuzi wa AI](docs/troubleshooting/ai-troubleshooting.md)
- **Mwongozo wa Kurekebisha Makosa:** [Utatuzi Hatua kwa Hatua](docs/troubleshooting/debugging.md)
- **Pata Msaada:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🔧 Mwongozo wa Haraka wa Utatuzi wa Matatizo

**Matatizo ya kawaida yanayokumbukwa na waanzilishi na suluhisho za haraka:**

<details>
<summary><strong>❌ "azd: amri haikupatikana"</strong></summary>

```bash
# Sakinisha AZD kwanza
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Thibitisha ufungaji
azd version
```
</details>

<details>
<summary><strong>❌ "Hakuna usajili uliopatikana" au "Usajili haujawekewa"</strong></summary>

```bash
# Orodhesha usajili uliopo
az account list --output table

# Weka usajili wa default
az account set --subscription "<subscription-id-or-name>"

# Weka kwa mazingira ya AZD
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Thibitisha
az account show
```
</details>

<details>
<summary><strong>❌ "InsufficientQuota" au "Kiasi kimetanguliwa"</strong></summary>

```bash
# Jaribu kanda tofauti ya Azure
azd env set AZURE_LOCATION "westus2"
azd up

# Au tumia SKU ndogo zaidi katika maendeleo
# Hariri infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>

<details>
<summary><strong>❌ "azd up" imeshindwa katikati</strong></summary>

```bash
# Chaguo 1: Safisha na jaribu tena
azd down --force --purge
azd up

# Chaguo 2: Rekebisha miundombinu tu
azd provision

# Chaguo 3: Angalia kumbukumbu za kina
azd show
azd logs
```
</details>

<details>
<summary><strong>❌ "Uthibitishaji umeshindikana" au "Kipindi cha token kimekwisha"</strong></summary>

```bash
# Thibitisha upya
az logout
az login

azd auth logout
azd auth login

# Thibitisha uthibitishaji
az account show
```
</details>

<details>
<summary><strong>❌ "Rasilimali tayari ipo" au migogoro ya majina</strong></summary>

```bash
# AZD huunda majina ya kipekee, lakini ikiwa kuna mgongano:
azd down --force --purge

# Kisha jaribu tena kwa mazingira mapya
azd env new dev-v2
azd up
```
</details>

<details>
<summary><strong>❌ Utekelezaji wa kiolezo unachukua muda mrefu sana</strong></summary>

**Muda wa kusubiri wa kawaida:**
- Programu rahisi ya wavuti: dakika 5-10
- Programu yenye hifadhidata: dakika 10-15
- Programu za AI: dakika 15-25 (Upatikanaji wa OpenAI ni mzito)

```bash
# Angalia maendeleo
azd show

# Ikiwa umekwama kwa zaidi ya dakika 30, angalia Azure Portal:
azd monitor
# Angalia kwa ajili ya usambazaji ulioshindwa
```
</details>

<details>
<summary><strong>❌ "Ruhusa imetolewa" au "Imezuiwa"</strong></summary>

```bash
# Angalia nafasi yako ya Azure
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Unahitaji angalau nafasi ya "Contributor"
# Muulize msimamizi wako wa Azure kutoa:
# - Contributor (kwa rasilimali)
# - Msimamizi wa Upatikanaji wa Mtumiaji (kwa uteuzi wa nafasi)
```
</details>

<details>
<summary><strong>❌ Haiwezi kupata anwani ya programu iliyotekelezwa</strong></summary>

```bash
# Onyesha vikomo vyote vya huduma
azd show

# Au fungua Azure Portal
azd monitor

# Angalia huduma maalum
azd env get-values
# Tafuta vigezo vya *_URL
```
</details>

### 📚 Vyanzo Kamili vya Utatuzi wa Matatizo

- **Mwongozo wa Matatizo ya Kawaida:** [Suluhisho Zaidi](docs/troubleshooting/common-issues.md)
- **Matatizo Maalum ya AI:** [Utatuzi wa AI](docs/troubleshooting/ai-troubleshooting.md)
- **Mwongozo wa Kurekebisha Makosa:** [Utatuzi Hatua kwa Hatua](docs/troubleshooting/debugging.md)
- **Pata Msaada:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🎓 Kukamilisha Kozi & Cheti

### Ufuatiliaji wa Maendeleo
Fuata maendeleo ya kujifunza kupitia kila sura:

- [ ] **Sura 1**: Msingi & Mwanzo wa Haraka ✅
- [ ] **Sura 2**: Maendeleo ya AI-Kwanza ✅  
- [ ] **Sura 3**: Usanidi & Uthibitishaji ✅
- [ ] **Sura 4**: Miundombinu kama Kanuni & Utekelezaji ✅
- [ ] **Sura 5**: Suluhisho za AI za Wakala Wengi ✅
- [ ] **Sura 6**: Ukaguzi & Mipango Kabla ya Utekelezaji ✅
- [ ] **Sura 7**: Utatuzi wa Matatizo & Kurekebisha Makosa ✅
- [ ] **Sura 8**: Mifumo ya Uzalishaji & Biashara ✅

### Uhakikisho wa Kujifunza
Baada ya kukamilisha kila sura, thibitisha maarifa yako kwa:
1. **Zoeezi la Vitendo**: Kamilia utekelezaji wa sura
2. **Kagua Maarifa**: Pitia sehemu ya maswali yanayoulizwa mara kwa mara kwa sura yako
3. **Majadiliano ya Jamii**: Shiriki uzoefu wako kwenye Azure Discord
4. **Sura Ifuatayo**: Hudhuria kiwango kingine cha ugumu

### Faida za Kukamilisha Kozi
Baada ya kukamilisha sura zote, utakuwa na:
- **Uzoefu wa Uzalishaji**: Programu halisi za AI zilizotekelezwa Azure
- **Ujuzi wa Kitaalamu**: Ujuzi wa utekelezaji tayari kwa biashara  
- **Utambuzi wa Jamii**: Mwanachama hai wa jumuiya ya waendelezaji Azure
- **Kuendeleza Kazi**: Utaalamu unaohitajika wa AZD na utekelezaji wa AI

---

## 🤝 Jamii & Msaada

### Pata Msaada na Usaidizi
- **Matatizo ya Kiufundi**: [Ripoti kasoro na omba vipengele](https://github.com/microsoft/azd-for-beginners/issues)
- **Maswali ya Kujifunza**: [Jumuiya ya Microsoft Azure Discord](https://discord.gg/microsoft-azure) na [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **Msaada Maalum wa AI**: Jiunge na [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **Nyaraka**: [Nyaraka rasmi za Azure Developer CLI](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)

### Mwanga wa Jamii kutoka Microsoft Foundry Discord

**Matokeo ya Dodoso la Hivi Karibuni kutoka Kituo cha #Azure:**
- **45%** ya waendelezaji wanataka kutumia AZD kwa mizigo ya AI
- **Changamoto kuu**: Utekelezaji wa huduma nyingi, usimamizi wa hati, tayari wa uzalishaji  
- **Iliyotakiwa zaidi**: Violezo maalum vya AI, miongozo ya utatuzi, mbinu bora

**Jiunge na jamii yetu ili:**
- Kushiriki uzoefu wako wa AZD + AI na kupata msaada
- Kupata mapema matoleo ya violezo vipya vya AI
- Kuchangia mbinu bora za utekelezaji wa AI
- Kuathiri maendeleo ya vipengele vya AI + AZD siku za usoni

### Kuchangia kwenye Kozi
Tunakaribisha michango! Tafadhali soma [Mwongozo wa Kuchangia](CONTRIBUTING.md) kwa maelezo juu ya:
- **Kuboresha Maudhui**: Boresha sura na mifano iliyopo
- **Mifano Mpya**: Ongeza matukio halisi na violezo  
- **Tafsiri**: Saidia kudumisha msaada wa lugha nyingi
- **Ripoti za Kasoro**: Boresha usahihi na uwazi
- **Viwango vya Jamii**: Fuata miongozo yetu ya jamii jumuishi

---

## 📄 Taarifa za Kozi

### Leseni
Mradi huu umepewa leseni chini ya Leseni ya MIT - angalia faili la [LICENSE](../../LICENSE) kwa maelezo.

### Vyanzo vingine vya Kujifunza vya Microsoft

Timu yetu hutengeneza kozi zingine kamili za kujifunza:

<!-- CO-OP TRANSLATOR OTHER COURSES START -->
### LangChain
[![LangChain4j for Beginners](https://img.shields.io/badge/LangChain4j%20for%20Beginners-22C55E?style=for-the-badge&&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchain4j-for-beginners)
[![LangChain.js for Beginners](https://img.shields.io/badge/LangChain.js%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchainjs-for-beginners?WT.mc_id=m365-94501-dwahlin)

---

### Azure / Edge / MCP / Wakala
[![AZD for Beginners](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Edge AI for Beginners](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![MCP for Beginners](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)
[![AI Agents for Beginners](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Mfululizo wa AI ya Kuzalisha
[![Generative AI for Beginners](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Generative AI (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
[![Generative AI (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)
[![Generative AI (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---
 
### Kujifunza Msingi
[![ML for Beginners](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![Sayansi ya Data kwa Waanzilishi](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![AI kwa Waanzilishi](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Usalama Mtandao kwa Waanzilishi](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Maendeleo ya Mtandao kwa Waanzilishi](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![IoT kwa Waanzilishi](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![Maendeleo ya XR kwa Waanzilishi](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Mfululizo wa Copilot
[![Copilot kwa Kuprogramu Pamoja na AI](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![Copilot kwa C#/.NET](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Copilot Adventure](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ Mwelekeo wa Kozi

**🚀 Tayari Kuanzia Kujifunza?**

**Waanzilishi**: Anza na [Sura ya 1: Msingi & Anza Haraka](../..)  
**Waendelezaji wa AI**: Ruka kwenda [Sura ya 2: Maendeleo ya AI-Kwanza](../..)  
**Waendelezaji Wenye Uzoefu**: Anza na [Sura ya 3: Usanidi & Uthibitishaji](../..)

**Hatua Zifuatazo**: [Anza Sura ya 1 - Msingi wa AZD](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Kauli ya Kutotegemea**:
Nyaraka hii imetafsiriwa kwa kutumia huduma ya tafsiri ya AI [Co-op Translator](https://github.com/Azure/co-op-translator). Ingawa tunajitahidi kwa usahihi, tafadhali fahamu kwamba tafsiri zinazofanywa kwa mashine zinaweza kuwa na makosa au upungufu wa usahihi. Nyaraka asili katika lugha yake ya asili inapaswa kuzingatiwa kama chanzo cha mamlaka. Kwa taarifa muhimu, tafsiri ya kitaalamu inayo fanywa na binadamu inapendekezwa. Hatubebwi dhamana kwa kutokuelewana au tafsiri zisizo sahihi zinazotokana na matumizi ya tafsiri hii.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->