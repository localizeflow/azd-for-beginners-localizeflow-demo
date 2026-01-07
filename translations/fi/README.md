<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T13:50:34+00:00",
  "source_file": "README.md",
  "language_code": "fi"
}
-->
> Huomautus: Tämä dokumentaatio päivitetään jatkuvasti vastaamaan viimeisimpiä muutoksia.

> ⚠️ Tämä varasto on demoversio, joka on luotu esittelemään
> automatisoitua dokumentaation lokalisaatiota Localizeflow:n avulla.
>
> Alkuperäinen sisältö perustuu
> Microsoftin ”AZD for Beginners” -projektiin.


# AZD Aloittelijoille: Jäsennelty Oppimispolku

![AZD-for-beginners](../../translated_images/azdbeginners.5527441dd9f74068.fi.png) 

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## Aloittaminen tämän kurssin kanssa

Seuraa näitä vaiheita aloittaaksesi AZD-oppimismatkan:

1. **Forkkaa repositorio**: Klikkaa [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)
2. **Kloonaa repositorio**: `git clone https://github.com/microsoft/azd-for-beginners.git`
3. **Liity yhteisöön**: [Azure Discord -yhteisöt](https://discord.com/invite/ByRwuEEgH4) asiantuntijatukea varten
4. **Valitse oppimispolku**: Valitse alla oleva luku, joka vastaa kokemustasoasi

### Monikielinen tuki

#### Automaattiset käännökset (aina ajan tasalla)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabia](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgaria](../bg/README.md) | [Burma (Myanmar)](../my/README.md) | [Kiina (yksinkertaistettu)](../zh/README.md) | [Kiina (perinteinen, Hong Kong)](../hk/README.md) | [Kiina (perinteinen, Makao)](../mo/README.md) | [Kiina (perinteinen, Taiwan)](../tw/README.md) | [Kroatia](../hr/README.md) | [Tšekki](../cs/README.md) | [Tanska](../da/README.md) | [Hollanti](../nl/README.md) | [Viro](../et/README.md) | [Suomi](./README.md) | [Ranska](../fr/README.md) | [Saksa](../de/README.md) | [Kreikka](../el/README.md) | [Heprea](../he/README.md) | [Hindi](../hi/README.md) | [Unkari](../hu/README.md) | [Indonesia](../id/README.md) | [Italia](../it/README.md) | [Japani](../ja/README.md) | [Kannada](../kn/README.md) | [Korea](../ko/README.md) | [Liettua](../lt/README.md) | [Malaiji](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norja](../no/README.md) | [Persia (Farsi)](../fa/README.md) | [Puola](../pl/README.md) | [Portugali (Brasilia)](../br/README.md) | [Portugali (Portugali)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romania](../ro/README.md) | [Venäjä](../ru/README.md) | [Serbia (kyrillinen)](../sr/README.md) | [Slovakki](../sk/README.md) | [Slovenia](../sl/README.md) | [Espanja](../es/README.md) | [Swahili](../sw/README.md) | [Ruotsi](../sv/README.md) | [Tagalog (filipino)](../tl/README.md) | [Tamili](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkki](../tr/README.md) | [Ukraina](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnami](../vi/README.md)

> **Haluatko kloonata paikallisesti?**

> Tässä varastossa on yli 50 käännöstä, mikä kasvattaa lataustiedoston kokoa merkittävästi. Jos haluat kloonata ilman käännöksiä, käytä sparse checkoutia:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Tämä sisältää kaiken tarvittavan kurssin suorittamiseen nopeammalla latauksella.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## Kurssin yleiskuvaus

Hallinnoi Azure Developer CLI:tä (azd) jäsenneltyjen lukujen kautta, jotka on suunniteltu asteittaiseen oppimiseen. **Erityinen painotus AI-sovellusten käyttöönotossa Microsoft Foundry -integraation kanssa.**

### Miksi tämä kurssi on tärkeä nykyaikaisille kehittäjille

Microsoft Foundryn Discord-yhteisön näkemyksiin perustuen, **45 % kehittäjistä haluaa käyttää AZD:tä AI-työkuormissa**, mutta kohtaa haasteita:
- Monimutkaiset monipalveluisten AI-arkkitehtuurien rakenteet
- AI:n tuotantokäyttöönoton parhaat käytännöt  
- Azure AI -palveluiden integrointi ja konfigurointi
- AI-työkuormien kustannustehokkuus
- AI-spesifien käyttöönotto-ongelmien vianmääritys

### Oppimistavoitteet

Suorittamalla tämän kurssin:
- **Hallinnoit AZD:n perusteet**: ydinkäsitteet, asennus ja konfigurointi
- **Ota käyttöön AI-sovelluksia**: käytä AZD:tä Microsoft Foundryn palveluiden kanssa
- **Ota käyttöön infrastruktuuri koodina**: hallitse Azure-resursseja Bicep-mallien avulla
- **Vianmääritys käyttöönotossa**: ratkaise yleisiä ongelmia ja debuggaa
- **Optimoi tuotantoon**: turvallisuus, skaalaus, monitorointi ja kustannusten hallinta
- **Rakenna moni-agenttijärjestelmiä**: ota käyttöön monimutkaisia AI-arkkitehtuureja

## 📚 Oppimislukupolut

*Valitse oppimispolkusi kokemuksesi ja tavoitteidesi mukaan*

### 🚀 Luku 1: Perusteet ja pika-aloitus
**Esivaatimukset**: Azure-tilaus, peruskäskyjen tuntemus  
**Kesto**: 30-45 minuuttia  
**Vaativuus**: ⭐

#### Mitä opit
- Azure Developer CLI:n perusteiden ymmärtäminen
- AZD:n asentaminen alustallesi
- Ensimmäinen onnistunut käyttöönotto

#### Oppimateriaalit
- **🎯 Aloita tästä**: [Mikä on Azure Developer CLI?](../..)
- **📖 Teoria**: [AZD:n perusteet](docs/getting-started/azd-basics.md) - ydinkäsitteet ja terminologia
- **⚙️ Asennus**: [Asennus ja määritys](docs/getting-started/installation.md) - alusta-kohtaiset ohjeet
- **🛠️ Käytännössä**: [Ensimmäinen projektisi](docs/getting-started/first-project.md) - vaihe vaiheelta opastus
- **📋 Nopea vinkkivihko**: [Komentojen pikaopas](resources/cheat-sheet.md)

#### Käytännön harjoitukset
```bash
# Nopea asennuksen tarkistus
azd version

# Ota käyttöön ensimmäinen sovelluksesi
azd init --template todo-nodejs-mongo
azd up
```

**💡 Luvun lopputulos**: Pystyä onnistuneesti ottamaan käyttöön yksinkertainen web-sovellus Azureen AZD:n avulla

**✅ Onnistumisen varmistus:**
```bash
# Lukemalla luvun 1 loppuun mennessä sinun pitäisi pystyä:
azd version              # Näyttää asennetun version
azd init --template todo-nodejs-mongo  # Alustaa projektin
azd up                  # Julkaisee Azureen
azd show                # Näyttää käynnissä olevan sovelluksen URL-osoitteen
# Sovellus avautuu selaimessa ja toimii
azd down --force --purge  # Siivoaa resurssit
```

**📊 Aikapanos:** 30-45 minuuttia  
**📈 Taitotaso jälkeen:** Osaa ottaa käyttöön perustason sovelluksia itsenäisesti

**✅ Onnistumisen varmistus:**
```bash
# Luvun 1 suorittamisen jälkeen sinun pitäisi osata:
azd version              # Näyttää asennetun version
azd init --template todo-nodejs-mongo  # Alustaa projekti
azd up                  # Julkaisee Azureen
azd show                # Näyttää käynnissä olevan sovelluksen URL-osoitteen
# Sovellus avautuu selaimessa ja toimii
azd down --force --purge  # Siivoaa resurssit
```

**📊 Aikapanos:** 30-45 minuuttia  
**📈 Taitotaso jälkeen:** Osaa ottaa käyttöön perustason sovelluksia itsenäisesti

---

### 🤖 Luku 2: AI-ensimmäinen kehitys (suositellaan AI-kehittäjille)
**Esivaatimukset**: Luku 1 suoritettu  
**Kesto**: 1-2 tuntia  
**Vaativuus**: ⭐⭐

#### Mitä opit
- Microsoft Foundryn integraatio AZD:n kanssa
- AI-tehostettujen sovellusten käyttöönotto
- AI-palveluiden konfiguraatioiden ymmärtäminen

#### Oppimateriaalit
- **🎯 Aloita tästä**: [Microsoft Foundryn integraatio](docs/microsoft-foundry/microsoft-foundry-integration.md)
- **📖 Mallit**: [AI-mallien käyttöönotto](docs/microsoft-foundry/ai-model-deployment.md) - AI-mallien käyttö ja hallinta
- **🛠️ Työpaja**: [AI-työpaja](docs/microsoft-foundry/ai-workshop-lab.md) - tee AI-ratkaisuistasi AZD-valmiita
- **🎥 Interaktiivinen opas**: [Työpajamateriaali](workshop/README.md) - selainpohjainen oppiminen MkDocs * DevContainer -ympäristössä
- **📋 Mallipohjat**: [Microsoft Foundryn mallipohjat](../..)
- **📝 Esimerkit**: [AZD:n käyttöönottoesimerkit](examples/README.md)

#### Käytännön harjoitukset
```bash
# Ota ensimmäinen tekoälysovelluksesi käyttöön
azd init --template azure-search-openai-demo
azd up

# Kokeile lisää tekoälymalleja
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```

**💡 Luvun lopputulos**: Käyttöönotto ja konfiguraatio AI-tehostetulle chat-sovellukselle, jossa on RAG-ominaisuudet

**✅ Onnistumisen varmistus:**
```bash
# Luvun 2 jälkeen sinun tulisi osata:
azd init --template azure-search-openai-demo
azd up
# Testata AI-keskustelukäyttöliittymää
# Esittää kysymyksiä ja saada AI-vastausten lähteiden kanssa
# Varmistaa, että hakutoiminto toimii
azd monitor  # Tarkistaa, että Application Insights näyttää telemetrian
azd down --force --purge
```

**📊 Aikapanos:** 1-2 tuntia  
**📈 Taitotaso jälkeen:** Osaa ottaa käyttöön ja konfiguroida tuotantovalmiita AI-sovelluksia  
**💰 Kustannustietoisuus:** Ymmärtää kehityskulut $80-150/kuukausi, tuotantokulut $300-3500/kuukausi

#### 💰 Kustannusnäkökohdat AI-käyttöönotossa

**Kehitysympäristö (arvio $80-150/kuukausi):**
- Azure OpenAI (Maksu käytön mukaan): $0-50/kk (tokeneiden käytön perusteella)
- AI-haku (Peruskerros): $75/kk
- Container Apps (Kulutukseen perustuva): $0-20/kk
- Tallennustila (Perus): $1-5/kk

**Tuotantoympäristö (arvio $300-3,500+/kk):**
- Azure OpenAI (PTU vakaan suorituskyvyn vuoksi): $3,000+/kk TAI maksu käytön mukaan suuressa määrässä
- AI-haku (Standardikerros): $250/kk
- Container Apps (Oma): $50-100/kk
- Application Insights: $5-50/kk
- Tallennustila (Premium): $10-50/kk

**💡 Kustannusten optimointivinkit:**
- Käytä **Free Tier** Azure OpenAI:ta oppimiseen (sisältää 50 000 tokenia/kk)
- Suorita `azd down` vapauttaaksesi resursseja, kun et aktiivisesti kehitä
- Aloita kulutuksen mukaan veloitettavasta mallista, päivitä PTU:hun vain tuotannossa
- Käytä `azd provision --preview` kustannusarvioon ennen käyttöönottoa
- Ota automaattinen skaalaus käyttöön: maksa vain todellisesta käytöstä

**Kustannusseuranta:**
```bash
# Tarkista arvioidut kuukausikustannukset
azd provision --preview

# Seuraa todellisia kustannuksia Azure-portaalissa
az consumption budget list --resource-group <your-rg>
```

---

### ⚙️ Luku 3: Konfiguraatio ja todennus
**Esivaatimukset**: Luku 1 suoritettu  
**Kesto**: 45-60 minuuttia  
**Vaativuus**: ⭐⭐

#### Mitä opit
- Ympäristöjen konfigurointi ja hallinta
- Todennus ja tietoturvan parhaat käytännöt
- Resurssien nimeäminen ja organisointi

#### Oppimateriaalit
- **📖 Konfigurointi**: [Konfigurointiopas](docs/getting-started/configuration.md) - ympäristön määritys
- **🔐 Tietoturva**: [Todennusmallit ja hallittu identiteetti](docs/getting-started/authsecurity.md) - todennusmallit
- **📝 Esimerkit**: [Tietokantasovellus](examples/database-app/README.md) - AZD-tietokantaesimerkit

#### Käytännön harjoitukset
- Konfiguroi useita ympäristöjä (kehitys, testaus, tuotanto)
- Ota käyttöön hallittu identiteetti todennuksessa
- Toteuta ympäristökohtaiset määritykset

**💡 Luvun lopputulos**: Hallitsee useita ympäristöjä asianmukaisella todennuksella ja tietoturvalla

---

### 🏗️ Luku 4: Infrastruktuuri koodina & käyttöönotto
**Esivaatimukset**: Luvut 1-3 suoritettu  
**Kesto**: 1-1,5 tuntia  
**Vaativuus**: ⭐⭐⭐

#### Mitä opit
- Edistyneet käyttöönoton mallit
- Infrastruktuuri koodina Bicep:n avulla
- Resurssien provisiointistrategiat

#### Oppimateriaalit
- **📖 Käyttöönotto**: [Käyttöönotto-opas](docs/deployment/deployment-guide.md) - täydelliset työnkulut
- **🏗️ Provisiointi**: [Resurssien provisiointi](docs/deployment/provisioning.md) - Azure-resurssien hallinta
- **📝 Esimerkit**: [Container App -esimerkki](../../examples/container-app) - konttikäytöt

#### Käytännön harjoitukset
- Luo omia Bicep-malleja
- Käynnistä monipalvelusovelluksia
- Toteuta blue-green -käyttöönotto strategioita

**💡 Luvun lopputulos**: Ota käyttöön monimutkaisia monipalvelusovelluksia omilla infrastruktuurimalleilla

---
### 🎯 Luku 5: Monen agentin tekoälyratkaisut (edistynyt)
**Esivaatimukset**: Luvut 1-2 suoritettu  
**Kesto**: 2-3 tuntia  
**Vaativuus**: ⭐⭐⭐⭐

#### Mitä opit
- Monen agentin arkkitehtuurimallit
- Agenttien orkestrointi ja koordinointi
- Tuotantovalmiit tekoälyn käyttöönotot

#### Oppimateriaalit
- **🤖 Esittelyprojekti**: [Retail-monen agentin ratkaisu](examples/retail-scenario.md) - Täydellinen toteutus
- **🛠️ ARM-mallit**: [ARM-mallit-paketti](../../examples/retail-multiagent-arm-template) - Yhdellä napsautuksella käyttöönotto
- **📖 Arkkitehtuuri**: [Monen agentin koordinointimallit](/docs/pre-deployment/coordination-patterns.md) - Mallit

#### Käytännön harjoitukset
```bash
# Ota käyttöön täydellinen vähittäiskaupan moniedustajaratkaisu
cd examples/retail-multiagent-arm-template
./deploy.sh

# Tutki agenttien kokoonpanoja
az deployment group show --resource-group <rg-name> --name <deployment-name>
```

**💡 Luvun tulos**: Ota käyttöön ja hallinnoi tuotantovalmiita monen agentin tekoälyratkaisuja Asiakas- ja Varasto-agenttien avulla

---

### 🔍 Luku 6: Ennen käyttöönottoa tehtävä validointi ja suunnittelu
**Esivaatimukset**: Luku 4 suoritettu  
**Kesto**: 1 tunti  
**Vaativuus**: ⭐⭐

#### Mitä opit
- Kapasiteettisuunnittelu ja resurssien validointi
- SKU-valintastrategiat
- Ennen käyttöönottoa tehtävät tarkistukset ja automaatio

#### Oppimateriaalit
- **📊 Suunnittelu**: [Kapasiteettisuunnittelu](docs/pre-deployment/capacity-planning.md) - Resurssien validointi
- **💰 Valinta**: [SKU-valinta](docs/pre-deployment/sku-selection.md) - Kustannustehokkaat valinnat
- **✅ Validointi**: [Pre-flight-tarkistukset](docs/pre-deployment/preflight-checks.md) - Automaattiset skriptit

#### Käytännön harjoitukset
- Suorita kapasiteetin validointiskriptit
- Optimoi SKU-valinnat kustannusten kannalta
- Toteuta automatisoidut ennen käyttöönottoa tehtävät tarkastukset

**💡 Luvun tulos**: Validioi ja optimoi käyttöönotot ennen niiden toteutusta

---

### 🚨 Luku 7: Vianmääritys ja virheenkorjaus
**Esivaatimukset**: Mikä tahansa käyttöönotto-luku suoritettu  
**Kesto**: 1-1,5 tuntia  
**Vaativuus**: ⭐⭐

#### Mitä opit
- Järjestelmälliset virheenkorjausmenetelmät
- Yleisimmät ongelmat ja ratkaisut
- Tekoälyyn liittyvä vianmääritys

#### Oppimateriaalit
- **🔧 Yleiset ongelmat**: [Yleiset ongelmat](docs/troubleshooting/common-issues.md) - Usein kysytyt kysymykset ja ratkaisut
- **🕵️ Virheenkorjaus**: [Virheenkorjausopas](docs/troubleshooting/debugging.md) - Askelsarjat
- **🤖 Tekoälyn ongelmat**: [Tekoälykohtainen vianmääritys](docs/troubleshooting/ai-troubleshooting.md) - Tekoälypalvelun ongelmat

#### Käytännön harjoitukset
- Tunnista käyttöönoton virheet
- Ratkaise autentikointiongelmat
- Virheenkorjaa tekoäly palvelun yhteysongelmat

**💡 Luvun tulos**: Opi itsenäisesti tunnistamaan ja ratkaisemaan yleisimpiä käyttöönoton ongelmia

---

### 🏢 Luku 8: Tuotanto- ja yritysmallit
**Esivaatimukset**: Luvut 1-4 suoritettu  
**Kesto**: 2-3 tuntia  
**Vaativuus**: ⭐⭐⭐⭐

#### Mitä opit
- Tuotantokäyttöön sopivat käyttöönotto-strategiat
- Yritysturvallisuusmallit
- Monitorointi ja kustannusten optimointi

#### Oppimateriaalit
- **🏭 Tuotanto**: [Tuotannon tekoälyn parhaat käytännöt](docs/microsoft-foundry/production-ai-practices.md) - Yritysmallit
- **📝 Esimerkit**: [Mikropalvelu-esimerkki](../../examples/microservices) - Monimutkaiset arkkitehtuurit
- **📊 Monitorointi**: [Application Insights -integraatio](docs/pre-deployment/application-insights.md) - Monitorointi

#### Käytännön harjoitukset
- Toteuta yritysturvallisuusmallit
- Ota käyttöön kattava monitorointi
- Käyttöönotto tuotantoon asianmukaisella hallinnalla

**💡 Luvun tulos**: Ota käyttöön yritysvalmiita sovelluksia, joissa on täydet tuotantovalmiudet

---

## 🎓 Työpajan yleiskatsaus: Käytännön oppimiskokemus

> **⚠️ TYÖPAJAN TILA: Kehitteillä**  
> Työpajamateriaalit ovat parhaillaan kehitysvaiheessa ja hiotaan. Ydinmoduulit toimivat, mutta jotkin edistyneet osiot ovat keskeneräisiä. Teemme aktiivisesti töitä kaikkien sisältöjen täydentämiseen. [Seuraa etenemistä →](workshop/README.md)

### Interaktiiviset työpajamateriaalit
**Kattava käytännön oppiminen selaimessa toimivilla työkaluilla ja ohjatuilla harjoituksilla**

Työpajamateriaalimme tarjoavat rakenteellisen, interaktiivisen oppimiskokemuksen, joka täydentää yllä olevaa lukuopetusta. Työpaja on suunniteltu sekä itsenäiseen opiskeluun että ohjattuihin sessioihin.

#### 🛠️ Työpajan ominaisuuksia
- **Selainpohjainen käyttöliittymä**: Täydellinen MkDocs-pohjainen työpaja haku-, kopiointi- ja teemaominaisuuksilla
- **GitHub Codespaces–integraatio**: Yhdellä napsautuksella kehitysympäristön pystytys
- **Rakenne**: 7-vaiheinen ohjattu harjoituspolku (3,5 tuntia yhteensä)
- **Löytö → Käyttöönotto → Mukautus**: Progressiivinen metodologia
- **Interaktiivinen DevContainer-ympäristö**: Esiasennetut työkalut ja riippuvuudet

#### 📚 Työpajan rakenne
Työpaja noudattaa **Löytö → Käyttöönotto → Mukautus** -metodologiaa:

1. **Löytövaihe** (45 min)
   - Tutustu Microsoft Foundry -malleihin ja palveluihin
   - Ymmärrä monen agentin arkkitehtuurimallit
   - Tarkastele käyttöönoton vaatimuksia ja esivaatimuksia

2. **Käyttöönotto-vaihe** (2 tuntia)
   - Käytännön AI-sovellusten käyttöönotto AZD:llä
   - Azure AI -palveluiden ja päätepisteiden määritys
   - Turva- ja autentikointimallien toteutus

3. **Mukautusvaihe** (45 min)
   - Sovellusten muokkaus erityistapauksiin
   - Optimointi tuotantokäyttöön
   - Monitoroinnin ja kustannusten hallinnan toteutus

#### 🚀 Työpajan aloitus
```bash
# Vaihtoehto 1: GitHub Codespaces (Suositeltu)
# Napsauta "Code" → "Create codespace on main" repositoriossa

# Vaihtoehto 2: Paikallinen kehitys
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# Seuraa workshop/README.md -tiedoston asennusohjeita
```

#### 🎯 Työpajan oppimistulokset
Työpajan suorittamalla osallistujat:
- **Ottavat käyttöön tuotantotason AI-sovelluksia**: Käyttö AZD:n ja Microsoft Foundryn palveluiden kanssa
- **Hallinnoivat monen agentin arkkitehtuureja**: Toteuttavat koordinoidut tekoälyagenttiratkaisut
- **Toteuttavat turvallisuuden parhaat käytännöt**: Määrittävät autentikoinnin ja käyttöoikeudet
- **Optimoivat skaalautumisen**: Suunnittelevat kustannustehokkaat ja suorituskykyiset käyttöönotot
- **Vianmääritysosaaminen**: Ratkaisevat yleisiä ongelmia itsenäisesti

#### 📖 Työpajan resurssit
- **🎥 Interaktiivinen opas**: [Työpajan materiaalit](workshop/README.md) - Selainpohjainen oppimisympäristö
- **📋 Askeltainen opastus**: [Ohjatut harjoitukset](../../workshop/docs/instructions) - Yksityiskohtaiset läpikäynnit
- **🛠️ AI-työpajan laboratorio**: [AI-työpajalaboratorio](docs/microsoft-foundry/ai-workshop-lab.md) - Tekoälyyn keskittyneet harjoitukset
- **💡 Pika-aloitus**: [Työpajan asennusopas](workshop/README.md#quick-start) - Ympäristön määritys

**Täydellinen**: Yrityskoulutukseen, yliopistokursseille, itsenäiseen opiskeluun ja kehittäjävalmennuksiin.

---

## 📖 Mikä on Azure Developer CLI?

Azure Developer CLI (azd) on kehittäjäkeskeinen komentorivityökalu, joka nopeuttaa sovellusten rakentamista ja käyttöönottoa Azureen. Se tarjoaa:

- **Mallipohjaiset käyttöönotot** - Käytä valmiita malleja yleisiin sovellusmalleihin
- **Infrastruktuuri koodina** - Hallitse Azure-resursseja Bicepillä tai Terraformilla  
- **Integroitu työnkulku** - Sujuva provisiointi, käyttöönotto ja monitorointi
- **Kehittäjäystävällinen** - Optimoitu kehittäjän tuottavuuteen ja käyttökokemukseen

### **AZD + Microsoft Foundry: Täydellinen tekoälyn käyttöönottoon**

**Miksi AZD tekoälyratkaisuihin?** AZD ratkaisee tekoälykehittäjien suurimmat haasteet:

- **Tekoälyvalmiit mallit** - Esiasennetut mallit Azure OpenAI:lle, Cognitive Servicesille ja koneoppimis kuormille
- **Turvalliset tekoälyn käyttöönotot** - Sisäänrakennetut turvamallit tekoälypalveluille, API-avaimille ja mallipäätteille  
- **Tuotannon tekoälymallit** - Parhaat käytännöt skaalautuviin ja kustannustehokkaisiin AI-sovelluksiin
- **End-to-end tekoälyn työnkulut** - Mallikehityksestä tuotantokäyttöön asianmukaisella monitoroinnilla
- **Kustannusten optimointi** - Älykkäät resurssien hallinta ja skaalausratkaisut AI-kuormille
- **Microsoft Foundry -integraatio** - Saumaton yhteys Microsoft Foundryn mallikatalogiin ja päätteisiin

---

## 🎯 Mallit ja esimerkkikirjasto

### Esillä: Microsoft Foundryn mallit
**Aloita täältä, jos otat käyttöön tekoälysovelluksia!**

> **Huom:** Nämä mallit demonstroivat erilaisia tekoälymalleja. Osa on ulkoisia Azure Sampleja, osa paikallisia toteutuksia.

| Malli | Luku | Vaativuus | Palvelut | Tyyppi |
|----------|---------|------------|----------|------|
| [**Get started with AI chat**](https://github.com/Azure-Samples/get-started-with-ai-chat) | Luku 2 | ⭐⭐ | AzureOpenAI + Azure AI Model Inference API + Azure AI Search + Azure Container Apps + Application Insights | Ulkoinen |
| [**Get started with AI agents**](https://github.com/Azure-Samples/get-started-with-ai-agents) | Luku 2 | ⭐⭐ | Azure AI Agent Service + AzureOpenAI + Azure AI Search + Azure Container Apps + Application Insights| Ulkoinen |
| [**Azure Search + OpenAI Demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Luku 2 | ⭐⭐ | AzureOpenAI + Azure AI Search + App Service + Storage | Ulkoinen |
| [**OpenAI Chat App Quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Luku 2 | ⭐ | AzureOpenAI + Container Apps + Application Insights | Ulkoinen |
| [**Agent OpenAI Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Luku 5 | ⭐⭐⭐ | AzureOpenAI + Azure Functions + Prompty | Ulkoinen |
| [**Contoso Chat RAG**](https://github.com/Azure-Samples/contoso-chat) | Luku 8 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Cosmos DB + Container Apps | Ulkoinen |
| [**Retail Multi-Agent Solution**](examples/retail-scenario.md) | Luku 5 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Storage + Container Apps + Cosmos DB | **Paikallinen** |

### Esillä: Täydelliset oppimisskenaariot
**Tuotantovalmiit sovellusmallit linkitettynä oppimislukuihin**

| Malli | Oppimisluku | Vaativuus | Keskeinen oppi |
|----------|------------------|------------|--------------|
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Luku 2 | ⭐ | Perustason AI-käyttöönottomallit |
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Luku 2 | ⭐⭐ | RAG-menetelmän toteutus Azure AI Searchilla |
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | Luku 4 | ⭐⭐ | Dokumenttien älykäs käsittely |
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Luku 5 | ⭐⭐⭐ | Agenttikehys ja funktion kutsuminen |
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | Luku 8 | ⭐⭐⭐ | Yrityksen tekoälyorkestrointi |
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | Luku 5 | ⭐⭐⭐⭐ | Monen agentin arkkitehtuuri Asiakas- ja Varasto-agenteilla |

### Oppiminen esimerkkityypin mukaan

> **📌 Paikalliset vs. Ulkoiset Esimerkit:**  
> **Paikalliset Esimerkit** (tässä repossa) = Valmiita välittömään käyttöön  
> **Ulkoiset Esimerkit** (Azure Samplet) = Kopioi linkatuista repositorioista

#### Paikalliset esimerkit (valmiit käyttöön)
- [**Retail-monen agentin ratkaisu**](examples/retail-scenario.md) - Täydellinen tuotantovalmiin toteutus ARM-malleilla
  - Monen agentin arkkitehtuuri (Asiakas + Varasto-agentit)
  - Kattava monitorointi ja arviointi
  - Yhdellä napsautuksella käyttöönotto ARM-mallilla

#### Paikalliset esimerkit - Konttisovellukset (luvut 2-5)
**Kattavat konttijakeluesimerkit tässä repossa:**
- [**Konttisovellus-esimerkit**](examples/container-app/README.md) - Täydellinen opas konttikäyttöönottoon
  - [Yksinkertainen Flask API](../../examples/container-app/simple-flask-api) - Perus REST API skaalautuu nollaan
  - [Mikropalveluarkkitehtuuri](../../examples/container-app/microservices) - Tuotantovalmiit moni-palvelukäyttöönotot
  - Pika-aloitus, Tuotanto ja Edistyneet käyttöönotto-mallit
  - Monitorointi, turvallisuus ja kustannusoptimointiopastus

#### Ulkoiset esimerkit - Yksinkertaiset sovellukset (luvut 1-2)
**Kopioi nämä Azure Samplet repositorit aloittaaksesi:**
- [Yksinkertainen Web-sovellus - Node.js + MongoDB](https://github.com/Azure-Samples/todo-nodejs-mongo) - Perustason käyttöönotot
- [Staattinen sivusto - React SPA](https://github.com/Azure-Samples/todo-csharp-sql-swa-func) - Staattisen sisällön käyttöönotto
- [Konttisovellus - Python Flask](https://github.com/Azure-Samples/container-apps-store-api-microservice) - REST API:n käyttöönotto

#### Ulkoiset esimerkit - Tietokantaintegraatio (luvut 3-4)  
- [Tietokantasovellus - C# + SQL](https://github.com/Azure-Samples/todo-csharp-sql) - Tietokantayhteysmallit
- [Functions + Cosmos DB](https://github.com/Azure-Samples/todo-python-mongo-swa-func) - Serverittömät tietotyönkulut

#### Ulkoiset esimerkit - Edistyneet mallit (luvut 4-8)
- [Java-mikropalvelut](https://github.com/Azure-Samples/java-microservices-aca-lab) - Monipalveluarkkitehtuurit
- [Konttisovellusten taustatyöt](https://github.com/Azure-Samples/container-apps-jobs) - Taustaprosessointi  
- [Yrityksen ML-putki](https://github.com/Azure-Samples/mlops-v2) - Tuotantovalmiit ML-mallit

### Ulkoiset mallikokoelmat
- [**Virallinen AZD-malligalleria**](https://azure.github.io/awesome-azd/) - Kuraattori kokoelma virallisia ja yhteisön malleja
- [**Azure Developer CLI -mallit**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - Microsoft Learn -mallidokumentaatio
- [**Esimerkkihakemisto**](examples/README.md) - Paikalliset oppimisesimerkit yksityiskohtaisine selityksineen

---

## 📚 Oppimisresurssit & Viitteet

### Nopeat viitteet
- [**Komentovihje**](resources/cheat-sheet.md) - Tärkeimmät azd-komennot järjestettynä lukuihin
- [**Sanasto**](resources/glossary.md) - Azure- ja azd-terminologia  
- [**UKK**](resources/faq.md) - Yleiset kysymykset järjestettynä oppimislukuihin
- [**Opas harjoitteluun**](resources/study-guide.md) - Kattavat harjoitustehtävät

### Käytännön työpajat
- [**AI Workshop Lab**](docs/microsoft-foundry/ai-workshop-lab.md) - Tee AI-ratkaisuistasi AZD-jakelukelpoisia (2-3 tuntia)
- [**Interaktiivinen työpajaopas**](workshop/README.md) - Selainpohjainen työpaja MkDocsilla ja DevContainer-ympäristöllä
- [**Jäsennelty oppimispolku**](../../workshop/docs/instructions) - 7-vaiheiset ohjatut harjoitukset (Löytö → Julkaisu → Räätälöinti)
- [**AZD Aloittelijoille -työpaja**](workshop/README.md) - Täydelliset käytännön työpajamateriaalit GitHub Codespaces -integraatiolla

### Ulkoiset oppimisresurssit
- [Azure Developer CLI -dokumentaatio](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)
- [Azure Architecture Center](https://learn.microsoft.com/en-us/azure/architecture/)
- [Azure Hinnoittelulaskin](https://azure.microsoft.com/pricing/calculator/)
- [Azure Status](https://status.azure.com/)

---

## 🔧 Pikavianetsintäopas

**Yleiset aloittelevien käyttäjien kohtaamat ongelmat ja välittömät ratkaisut:**

### ❌ "azd: komentoa ei löydy"

```bash
# Asenna ensin AZD
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Vahvista asennus
azd version
```

### ❌ "Ei tilausta löydetty" tai "Tilausta ei asetettu"

```bash
# Listaa käytettävissä olevat tilaukset
az account list --output table

# Aseta oletustilaus
az account set --subscription "<subscription-id-or-name>"

# Aseta AZD-ympäristöön
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Vahvista
az account show
```

### ❌ "Riittämätön kiintiö" tai "Kiintiö ylitetty"

```bash
# Kokeile eri Azure-aluetta
azd env set AZURE_LOCATION "westus2"
azd up

# Tai käytä pienempiä SKUja kehityksessä
# Muokkaa infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```

### ❌ "azd up" epäonnistuu puolivälissä

```bash
# Vaihtoehto 1: Puhdista ja yritä uudelleen
azd down --force --purge
azd up

# Vaihtoehto 2: Korjaa vain infrastruktuuri
azd provision

# Vaihtoehto 3: Tarkista tarkemmat lokit
azd show
azd logs
```

### ❌ "Todennus epäonnistui" tai "Tokenin voimassaolo päättynyt"

```bash
# Vahvista uudelleen
az logout
az login

azd auth logout
azd auth login

# Tarkista todennus
az account show
```

### ❌ "Resurssi on jo olemassa" tai nimeämiskonfliktit

```bash
# AZD luo ainutlaatuisia nimiä, mutta jos tulee ristiriita:
azd down --force --purge

# Yritä sitten uudelleen uudella ympäristöllä
azd env new dev-v2
azd up
```

### ❌ Mallin käyttöönotto kestää liian kauan

**Normaalit odotusajat:**
- Yksinkertainen web-sovellus: 5-10 minuuttia
- Sovellus tietokannalla: 10-15 minuuttia
- AI-sovellukset: 15-25 minuuttia (OpenAI:n varaaminen on hidasta)

```bash
# Tarkista eteneminen
azd show

# Jos jumissa yli 30 minuuttia, tarkista Azure-portaali:
azd monitor
# Etsi epäonnistuneita käyttöönottoja
```

### ❌ "Lupa evätty" tai "Kielletty"

```bash
# Tarkista Azure-roolisi
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Tarvitset vähintään "Avustaja" -roolin
# Pyydä Azure-järjestelmänvalvojaasi myöntämään:
# - Avustaja (resursseille)
# - Käyttäjäoikeuksien hallinnoija (roolien määrityksiin)
```

### ❌ Käyttöönotetun sovelluksen URL-osoitetta ei löydy

```bash
# Näytä kaikki palvelupisteet
azd show

# Tai avaa Azure-portaali
azd monitor

# Tarkista tietty palvelu
azd env get-values
# Etsi *_URL-muuttujia
```

### 📚 Kattavat vianmääritysresurssit

- **Yleiset ongelmat:** [Yksityiskohtaiset ratkaisut](docs/troubleshooting/common-issues.md)
- **AI-spesifiset ongelmat:** [AI-vianmääritys](docs/troubleshooting/ai-troubleshooting.md)
- **Virheenkorjausopas:** [Vaiheittainen virheenkorjaus](docs/troubleshooting/debugging.md)
- **Hanki apua:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🔧 Pikavianetsintäopas

**Yleiset aloittelevien käyttäjien kohtaamat ongelmat ja välittömät ratkaisut:**

<details>
<summary><strong>❌ "azd: komentoa ei löydy"</strong></summary>

```bash
# Asenna ensin AZD
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Vahvista asennus
azd version
```
</details>

<details>
<summary><strong>❌ "Ei tilausta löydetty" tai "Tilausta ei asetettu"</strong></summary>

```bash
# Listaa saatavilla olevat tilaukset
az account list --output table

# Aseta oletustilaus
az account set --subscription "<subscription-id-or-name>"

# Aseta AZD-ympäristölle
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Vahvista
az account show
```
</details>

<details>
<summary><strong>❌ "Riittämätön kiintiö" tai "Kiintiö ylitetty"</strong></summary>

```bash
# Kokeile eri Azure-aluetta
azd env set AZURE_LOCATION "westus2"
azd up

# Tai käytä pienempiä SKUja kehityksessä
# Muokkaa infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>

<details>
<summary><strong>❌ "azd up" epäonnistuu puolivälissä</strong></summary>

```bash
# Vaihtoehto 1: Puhdista ja yritä uudelleen
azd down --force --purge
azd up

# Vaihtoehto 2: Korjaa vain infrastruktuuri
azd provision

# Vaihtoehto 3: Tarkista yksityiskohtaiset lokit
azd show
azd logs
```
</details>

<details>
<summary><strong>❌ "Todennus epäonnistui" tai "Tokenin voimassaolo päättynyt"</strong></summary>

```bash
# Tarkista tunnistus uudelleen
az logout
az login

azd auth logout
azd auth login

# Vahvista todennus
az account show
```
</details>

<details>
<summary><strong>❌ "Resurssi on jo olemassa" tai nimeämiskonfliktit</strong></summary>

```bash
# AZD luo ainutlaatuisia nimiä, mutta jos tulee ristiriita:
azd down --force --purge

# Yritä sitten uudelleen uudella ympäristöllä
azd env new dev-v2
azd up
```
</details>

<details>
<summary><strong>❌ Mallin käyttöönotto kestää liian kauan</strong></summary>

**Normaalit odotusajat:**
- Yksinkertainen web-sovellus: 5-10 minuuttia
- Sovellus tietokannalla: 10-15 minuuttia
- AI-sovellukset: 15-25 minuuttia (OpenAI:n varaaminen on hidasta)

```bash
# Tarkista eteneminen
azd show

# Jos jumissa yli 30 minuuttia, tarkista Azure-portaali:
azd monitor
# Etsi epäonnistuneet käyttöönotot
```
</details>

<details>
<summary><strong>❌ "Lupa evätty" tai "Kielletty"</strong></summary>

```bash
# Tarkista Azure-roolisi
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Tarvitset vähintään "Contributor"-roolin
# Pyydä Azure-järjestelmänvalvojaasi myöntämään:
# - Contributor (resursseille)
# - User Access Administrator (roolien myöntämiseen)
```
</details>

<details>
<summary><strong>❌ Käyttöönotetun sovelluksen URL-osoitetta ei löydy</strong></summary>

```bash
# Näytä kaikki palvelun päätepisteet
azd show

# Tai avaa Azure-portaali
azd monitor

# Tarkista tietty palvelu
azd env get-values
# Etsi *_URL-muuttujat
```
</details>

### 📚 Kattavat vianmääritysresurssit

- **Yleiset ongelmat:** [Yksityiskohtaiset ratkaisut](docs/troubleshooting/common-issues.md)
- **AI-spesifiset ongelmat:** [AI-vianmääritys](docs/troubleshooting/ai-troubleshooting.md)
- **Virheenkorjausopas:** [Vaiheittainen virheenkorjaus](docs/troubleshooting/debugging.md)
- **Hanki apua:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🎓 Kurssin päättäminen & sertifiointi

### Edistymisen seuranta
Seuraa oppimisesi etenemistä kunkin luvun läpi:

- [ ] **Luku 1**: Perusteet & pika-aloitus ✅
- [ ] **Luku 2**: AI-ensimmäinen kehitys ✅  
- [ ] **Luku 3**: Konfigurointi & todennus ✅
- [ ] **Luku 4**: Infrastruktuuri koodina & käyttöönotto ✅
- [ ] **Luku 5**: Moniagenttiset AI-ratkaisut ✅
- [ ] **Luku 6**: Esijulkaisun validointi & suunnittelu ✅
- [ ] **Luku 7**: Vianetsintä & virheenkorjaus ✅
- [ ] **Luku 8**: Tuotanto & yritysmallit ✅

### Oppimisen varmentaminen
Jokaisen luvun jälkeen varmista osaamisesi:
1. **Käytännön harjoitus**: Suorita luvun käytännön käyttöönotto
2. **Tietotesti**: Tarkista luvun UKK-osio
3. **Yhteisön keskustelu**: Jaa kokemuksesi Azure Discordissa
4. **Seuraava luku**: Siirry seuraavalle vaativuustasolle

### Kurssin suorittamisen edut
Kun olet suorittanut kaikki luvut, sinulla on:
- **Tuotantokokemus**: Toteuttanut todellisia AI-sovelluksia Azureen
- **Ammatilliset taidot**: Yrityskäyttöön valmis käyttöönotto  
- **Yhteisön tunnustus**: Aktiivinen jäsen Azure-kehittäjäyhteisössä
- **Uramahdollisuudet**: Kysytyt AZD- ja AI-käyttöönotto-osaamiset

---

## 🤝 Yhteisö & Tuki

### Hanki apua & tukea
- **Tekniset ongelmat**: [Raportoi virheitä ja pyydä ominaisuuksia](https://github.com/microsoft/azd-for-beginners/issues)
- **Oppimiskysymykset**: [Microsoft Azure Discord -yhteisö](https://discord.gg/microsoft-azure) ja [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **AI-kohtainen apu**: Liity [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **Dokumentaatio**: [Virallinen Azure Developer CLI -dokumentaatio](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)

### Yhteisön näkemyksiä Microsoft Foundry Discordista

**Viimeaikaiset kyselytulokset #Azure-kanavalta:**
- **45%** kehittäjistä haluaa käyttää AZD:tä AI-kuormituksissa
- **Suurimmat haasteet**: Monipalveluiden käyttöönotot, tunnistetietojen hallinta, tuotantovalmius  
- **Eniten pyydettyjä**: AI-spesifiset mallit, vianetsintäoppaat, parhaat käytännöt

**Liity yhteisöömme:**
- Jaa AZD- ja AI-kokemuksiasi ja saa apua
- Pääse käsiksi AI-mallien varhaisiin esikatseluihin
- Osallistu AI-käyttöönoton parhaiden käytäntöjen kehittämiseen
- Vaikuta tuleviin AI + AZD -ominaisuuksiin

### Osallistuminen kurssiin
Otamme mielellämme vastaan panoksia! Lue [Osallistumisopas](CONTRIBUTING.md) tiedoista:
- **Sisällön parannukset**: Paranna olemassa olevia lukuja ja esimerkkejä
- **Uudet esimerkit**: Lisää tosielämän tilanteita ja malleja  
- **Käännöstyö**: Auta monikielisen tuen ylläpidossa
- **Virheraportit**: Paranna tarkkuutta ja selkeyttä
- **Yhteisön toimintasäännöt**: Noudata kaikenkattavia yhteisöohjeitamme

---

## 📄 Kurssitiedot

### Lisenssi
Tämä projekti on lisensoitu MIT-lisenssillä - katso [LICENSE](../../LICENSE) tiedosto yksityiskohdista.

### Muihin Microsoftin oppimisresursseihin liittyvät

Tiimimme tuottaa myös muita kattavia oppimiskursseja:

<!-- CO-OP TRANSLATOR OTHER COURSES START -->
### LangChain
[![LangChain4j aloittelijoille](https://img.shields.io/badge/LangChain4j%20for%20Beginners-22C55E?style=for-the-badge&&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchain4j-for-beginners)
[![LangChain.js aloittelijoille](https://img.shields.io/badge/LangChain.js%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchainjs-for-beginners?WT.mc_id=m365-94501-dwahlin)

---

### Azure / Edge / MCP / Agentit
[![AZD aloittelijoille](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Edge AI aloittelijoille](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![MCP aloittelijoille](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)
[![AI-agentit aloittelijoille](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Generatiivinen AI -sarja
[![Generatiivinen AI aloittelijoille](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Generatiivinen AI (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
[![Generatiivinen AI (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)
[![Generatiivinen AI (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---
 
### Ydinkurssit
[![ML aloittelijoille](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![Data Science for Beginners](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![AI for Beginners](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Cybersecurity for Beginners](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Web Dev for Beginners](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![IoT for Beginners](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![XR Development for Beginners](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Copilot-sarja
[![Copilot for AI Paired Programming](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![Copilot for C#/.NET](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Copilot Adventure](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ Kurssin navigointi

**🚀 Valmiina aloittamaan oppimisen?**

**Aloittelijat**: Aloita [Luvusta 1: Perusta & Nopeasti käyntiin](../..)  
**AI-kehittäjät**: Siirry kohtaan [Luku 2: AI-ensimmäinen kehitys](../..)  
**Kokeneet kehittäjät**: Aloita [Luku 3: Konfigurointi & Todennus](../..)

**Seuraavat vaiheet**: [Aloita luku 1 - AZD-perusteet](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Vastuuvapauslauseke**:
Tämä asiakirja on käännetty käyttämällä tekoälypohjaista käännöspalvelua [Co-op Translator](https://github.com/Azure/co-op-translator). Vaikka pyrimme tarkkuuteen, huomaathan, että automaattiset käännökset saattavat sisältää virheitä tai epätarkkuuksia. Alkuperäinen asiakirja alkuperäiskielellä on pidettävä virallisena lähteenä. Tärkeissä asioissa suositellaan ammattimaista ihmiskäännöstä. Emme ole vastuussa tämän käännöksen käytöstä aiheutuvista väärinymmärryksistä tai tulkinnoista.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->