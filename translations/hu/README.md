<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T14:17:22+00:00",
  "source_file": "README.md",
  "language_code": "hu"
}
-->
> Megjegyzés: Ez a dokumentáció folyamatosan frissül, hogy tükrözze a legújabb változásokat.

> ⚠️ Ez a tároló egy bemutató, amely az automatizált dokumentáció lokalizációját mutatja be a Localizeflow használatával.
>
> Az eredeti tartalom a Microsoft „AZD kezdőknek” projektjén alapul.


# AZD Kezdőknek: Egy Strukturált Tanulási Út

![AZD-for-beginners](../../translated_images/azdbeginners.5527441dd9f74068.hu.png) 

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## A tanfolyam megkezdése

Kövesse ezeket a lépéseket AZD tanulási útja elkezdéséhez:

1. **Tároló leképezése (Fork)**: Kattintson [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)
2. **Tároló klónozása**: `git clone https://github.com/microsoft/azd-for-beginners.git`
3. **Csatlakozás a közösséghez**: [Azure Discord közösségek](https://discord.com/invite/ByRwuEEgH4) szakértői támogatásért
4. **Válassza ki a tanulási útvonalat**: Válasszon egy alábbi fejezetet tapasztalati szintjének megfelelően

### Többnyelvű támogatás

#### Automatizált fordítások (Mindig naprakész)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](./README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Szeretnéd helyben klónozni?**

> Ez a tároló több mint 50 nyelvi fordítást tartalmaz, ami jelentősen növeli a letöltési méretet. Ha fordítások nélkül szeretnéd klónozni, használj sparse checkout-ot:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Ez mindent megad, amire a tanfolyam elvégzéséhez szükséged van, lényegesen gyorsabb letöltéssel.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## A tanfolyam áttekintése

Sajátítsd el az Azure Developer CLI (azd) használatát strukturált fejezeteken keresztül, amelyek a fokozatos tanulásra épülnek. **Különös figyelem az AI alkalmazások telepítésére a Microsoft Foundry integrációjával.**

### Miért lényeges ez a tanfolyam a modern fejlesztők számára?

A Microsoft Foundry Discord közösség tapasztalatai alapján a fejlesztők **45%-a az AI munkaterheléseknél szeretné használni az AZD-t**, de nehézségekbe ütköznek:
- Összetett több szolgáltatásból álló AI architektúrák
- AI üzembehelyezési gyakorlatok éles környezetben  
- Azure AI szolgáltatások integrációja és konfigurációja
- AI munkaterhelések költségoptimalizálása
- AI-specifikus telepítési hibák elhárítása

### Tanulási célok

Ezzel a strukturált tanfolyammal:
- **Mestere leszel az AZD alapjainak**: Alapfogalmak, telepítés, konfiguráció
- **AI alkalmazásokat telepítesz**: AZD használata Microsoft Foundry szolgáltatásokkal
- **Infrastruktúra kód formájában (IaC) kezelése**: Azure erőforrások kezelése Bicep sablonokkal
- **Telepítési hibák elhárítása**: Gyakori problémák megoldása, hibakeresés
- **Üzemeltetéshez optimalizálsz**: Biztonság, skálázás, monitorozás, költségkezelés
- **Több ügynökös megoldásokat építesz**: Összetett AI architektúrák telepítése

## 📚 Tanulási fejezetek

*Válaszd ki tanulási útvonalad tapasztalatod és céljaid szerint*

### 🚀 1. fejezet: Alapok és Gyors Kezdés
**Előfeltételek**: Azure előfizetés, alapvető parancssori ismeretek  
**Időtartam**: 30-45 perc  
**Bonyolultság**: ⭐

#### Amit tanulni fogsz
- Az Azure Developer CLI alapfogalmainak megértése
- AZD telepítése a platformodra
- Az első sikeres telepítés

#### Tanulási források
- **🎯 Kezd itt**: [Mi az Azure Developer CLI?](../..)
- **📖 Elmélet**: [AZD Alapok](docs/getting-started/azd-basics.md) - Alapfogalmak és szakszókincs
- **⚙️ Beállítás**: [Telepítés és beállítás](docs/getting-started/installation.md) - Platform-specifikus útmutatók
- **🛠️ Gyakorlati**: [Az első projekted](docs/getting-started/first-project.md) - Lépésről lépésre oktatóanyag
- **📋 Gyorsreferencia**: [Parancs gyorsmutató](resources/cheat-sheet.md)

#### Gyakorlati feladatok
```bash
# Gyors telepítési ellenőrzés
azd version

# Telepítse első alkalmazását
azd init --template todo-nodejs-mongo
azd up
```

**💡 Fejezet eredmény**: Sikeresen telepítesz egy egyszerű webalkalmazást az Azure-ra AZD-vel

**✅ Sikeres teljesítés ellenőrzése:**
```bash
# Az 1. fejezet befejezése után képesnek kell lenned:
azd version              # Megjeleníti a telepített verziót
azd init --template todo-nodejs-mongo  # Inicializálja a projektet
azd up                  # Telepítés Azure-ra
azd show                # Megjeleníti a futó alkalmazás URL-jét
# Az alkalmazás megnyílik a böngészőben és működik
azd down --force --purge  # Erőforrások takarítása
```

**📊 Időbefektetés:** 30-45 perc  
**📈 Képzettségi szint a végén:** Alap alkalmazásokat önállóan telepít képes

**✅ Sikeres teljesítés ellenőrzése:**
```bash
# Az 1. fejezet elvégzése után képesnek kell lenned:
azd version              # Telepített verzió megjelenítése
azd init --template todo-nodejs-mongo  # Projekt inicializálása
azd up                  # Telepítés Azure-ra
azd show                # Futtatott alkalmazás URL-jének megjelenítése
# Az alkalmazás megnyílik a böngészőben és működik
azd down --force --purge  # Erőforrások tisztítása
```

**📊 Időbefektetés:** 30-45 perc  
**📈 Képzettségi szint a végén:** Alap alkalmazásokat önállóan telepít képes

---

### 🤖 2. fejezet: AI-központú fejlesztés (Ajánlott AI fejlesztőknek)
**Előfeltételek**: 1. fejezet teljesítve  
**Időtartam**: 1-2 óra  
**Bonyolultság**: ⭐⭐

#### Amit tanulni fogsz
- Microsoft Foundry integráció AZD-vel
- AI-alapú alkalmazások telepítése
- AI szolgáltatások konfigurációjának megértése

#### Tanulási források
- **🎯 Kezd itt**: [Microsoft Foundry integráció](docs/microsoft-foundry/microsoft-foundry-integration.md)
- **📖 Minták**: [AI modell telepítés](docs/microsoft-foundry/ai-model-deployment.md) - AI modellek telepítése és kezelése
- **🛠️ Műhely**: [AI műhely labor](docs/microsoft-foundry/ai-workshop-lab.md) - AZD-hez készült AI megoldások
- **🎥 Interaktív útmutató**: [Műhely anyagok](workshop/README.md) - Böngésző alapú tanulás MkDocs * DevContainer környezetben
- **📋 Sablonok**: [Microsoft Foundry sablonok](../..)
- **📝 Példák**: [AZD telepítési példák](examples/README.md)

#### Gyakorlati feladatok
```bash
# Helyezze üzembe első AI alkalmazását
azd init --template azure-search-openai-demo
azd up

# Próbáljon ki további AI sablonokat
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```

**💡 Fejezet eredmény**: Telepíts és konfigurálj egy AI-alapú csevegőalkalmazást RAG képességekkel

**✅ Sikeres teljesítés ellenőrzése:**
```bash
# A 2. fejezet után képesnek kell lennie arra, hogy:
azd init --template azure-search-openai-demo
azd up
# Tesztelje az AI csevegőfelületet
# Tegyen fel kérdéseket és kapjon AI által támogatott válaszokat forrásokkal
# Ellenőrizze, hogy a keresési integráció működik
azd monitor  # Ellenőrizze, hogy az Application Insights mutatja a telemetriát
azd down --force --purge
```

**📊 Időbefektetés:** 1-2 óra  
**📈 Képzettségi szint a végén:** Képes éles, AI alkalmazások telepítésére és konfigurálására  
**💰 Költségismeret:** Megérti a fejlesztési költségeket ($80-150/hó), éles környezet költségeket ($300-3500/hó)

#### 💰 Költségszempontok az AI telepítésekhez

**Fejlesztői környezet (Becslés: $80-150/hónap):**
- Azure OpenAI (Pay-as-you-go): $0-50/hó (tokenfelhasználástól függően)
- AI Search (alapszint): $75/hó
- Container Apps (fogyasztás alapú): $0-20/hó
- Tárolás (szabványos): $1-5/hó

**Éles környezet (Becslés: $300-3,500+/hónap):**
- Azure OpenAI (PTU a konzisztens teljesítményért): $3,000+/hó VAGY nagy volumenű pay-as-you-go
- AI Search (szabványos szint): $250/hó
- Container Apps (dedikált): $50-100/hó
- Application Insights: $5-50/hó
- Tárolás (prémium): $10-50/hó

**💡 Költségoptimalizálási tippek:**
- Használj **Ingyenes szintű** Azure OpenAI-t tanuláshoz (50,000 token/hó benne van)
- Futtasd az `azd down` parancsot, ha nem fejlesztesz aktívan, hogy felszabadítsd az erőforrásokat
- Fogyasztás alapú számlázással kezdj, PTU-ra csak éles környezetben válts
- Használd az `azd provision --preview` parancsot a költségek előzetes becslésére
- Engedélyezd az automatikus skálázást: csak a tényleges használatért fizess

**Költségfigyelés:**
```bash
# Becslés havi költségek ellenőrzése
azd provision --preview

# A tényleges költségek figyelése az Azure Portálon
az consumption budget list --resource-group <your-rg>
```

---

### ⚙️ 3. fejezet: Konfiguráció és hitelesítés
**Előfeltételek**: 1. fejezet teljesítve  
**Időtartam**: 45-60 perc  
**Bonyolultság**: ⭐⭐

#### Amit tanulni fogsz
- Környezet konfiguráció és menedzsment
- Hitelesítés és biztonsági bevált gyakorlatok
- Erőforrásnevek és szervezés

#### Tanulási források
- **📖 Konfiguráció**: [Konfigurációs útmutató](docs/getting-started/configuration.md) - Környezet beállítása
- **🔐 Biztonság**: [Hitelesítési minták és kezelt identitás](docs/getting-started/authsecurity.md) - Hitelesítés
- **📝 Példák**: [Adatbázis alkalmazás példa](examples/database-app/README.md) - AZD adatbázis példák

#### Gyakorlati feladatok
- Több környezet konfigurálása (fejlesztői, teszt, éles)
- Kezelt identitás alapú hitelesítés beállítása
- Környezet-specifikus konfigurációk implementálása

**💡 Fejezet eredmény**: Több környezet kezelése megfelelő hitelesítéssel és biztonsággal

---

### 🏗️ 4. fejezet: Infrastruktúra kód formájában és telepítés
**Előfeltételek**: 1-3. fejezetek teljesítve  
**Időtartam**: 1-1,5 óra  
**Bonyolultság**: ⭐⭐⭐

#### Amit tanulni fogsz
- Haladó telepítési minták
- Infrastruktúra mint kód Bicep-pel
- Erőforrás provisioning stratégiák

#### Tanulási források
- **📖 Telepítés**: [Telepítési útmutató](docs/deployment/deployment-guide.md) - Teljes munkafolyamatok
- **🏗️ Provisioning**: [Erőforrások provisioningje](docs/deployment/provisioning.md) - Azure erőforrás menedzsment
- **📝 Példák**: [Container App példa](../../examples/container-app) - Konténeres telepítések

#### Gyakorlati feladatok
- Egyedi Bicep sablonok létrehozása
- Több szolgáltatásból álló alkalmazások telepítése
- Kék-zöld telepítési stratégiák implementálása

**💡 Fejezet eredmény**: Összetett több szolgáltatásos alkalmazások telepítése egyedi infrastruktúra sablonok használatával

---
### 🎯 5. fejezet: Többügynökös MI megoldások (Haladó)
**Előfeltételek**: 1-2. fejezet befejezve  
**Időtartam**: 2-3 óra  
**Bonyolultság**: ⭐⭐⭐⭐

#### Amit megtanulsz
- Többügynökös architektúra minták
- Ügynökök összehangolása és koordinációja
- Üzemkész MI telepítések

#### Tanulási források
- **🤖 Kiemelt projekt**: [Kiskereskedelmi többügynökös megoldás](examples/retail-scenario.md) - Teljes megvalósítás
- **🛠️ ARM sablonok**: [ARM sablon csomag](../../examples/retail-multiagent-arm-template) - Egykattintásos telepítés
- **📖 Architektúra**: [Többügynökös koordinációs minták](/docs/pre-deployment/coordination-patterns.md) - Minták

#### Gyakorlati feladatok
```bash
# Telepítse a teljes kiskereskedelmi több ügynökös megoldást
cd examples/retail-multiagent-arm-template
./deploy.sh

# Fedezze fel az ügynök konfigurációkat
az deployment group show --resource-group <rg-name> --name <deployment-name>
```

**💡 Fejezet eredmény**: Üzemkész többügynökös MI megoldás telepítése és kezelése Ügyfél és Készlet ügynökökkel

---

### 🔍 6. fejezet: Telepítés előtti érvényesítés és tervezés
**Előfeltételek**: 4. fejezet befejezve  
**Időtartam**: 1 óra  
**Bonyolultság**: ⭐⭐

#### Amit megtanulsz
- Kapacitástervezés és erőforrás-érvényesítés
- SKU kiválasztási stratégiák
- Telepítés előtti ellenőrzések és automatizálás

#### Tanulási források
- **📊 Tervezés**: [Kapacitástervezés](docs/pre-deployment/capacity-planning.md) - Erőforrás ellenőrzés
- **💰 Kiválasztás**: [SKU választás](docs/pre-deployment/sku-selection.md) - Költséghatékony döntések
- **✅ Érvényesítés**: [Telepítés előtti ellenőrzések](docs/pre-deployment/preflight-checks.md) - Automatizált szkriptek

#### Gyakorlati feladatok
- Futtasd a kapacitás ellenőrző szkripteket
- Optimalizáld az SKU választásokat költség szerint
- Valósíts meg automatizált telepítés előtti ellenőrzéseket

**💡 Fejezet eredmény**: Telepítések érvényesítése és optimalizálása végrehajtás előtt

---

### 🚨 7. fejezet: Hibakeresés és hibajavítás
**Előfeltételek**: Bármely telepítési fejezet befejezve  
**Időtartam**: 1-1,5 óra  
**Bonyolultság**: ⭐⭐

#### Amit megtanulsz
- Szisztematikus hibakeresési megközelítések
- Gyakori problémák és megoldások
- Mesterséges intelligenciára specializált hibakeresés

#### Tanulási források
- **🔧 Gyakori problémák**: [Gyakori problémák](docs/troubleshooting/common-issues.md) - GYIK és megoldások
- **🕵️ Hibakeresés**: [Hibakeresési útmutató](docs/troubleshooting/debugging.md) - Lépésről lépésre stratégiák
- **🤖 MI problémák**: [MI-specifikus hibakezelés](docs/troubleshooting/ai-troubleshooting.md) - MI szolgáltatás problémák

#### Gyakorlati feladatok
- Diagnosztizáld a telepítési hibákat
- Oldd meg az hitelesítési problémákat
- Hibakeresés MI szolgáltatás kapcsolódásban

**💡 Fejezet eredmény**: Önállóan diagnosztizáld és oldd meg a gyakori telepítési problémákat

---

### 🏢 8. fejezet: Termelési és vállalati minták
**Előfeltételek**: 1-4. fejezetek befejezve  
**Időtartam**: 2-3 óra  
**Bonyolultság**: ⭐⭐⭐⭐

#### Amit megtanulsz
- Termelési telepítési stratégiák
- Vállalati biztonsági minták
- Monitorozás és költségoptimalizálás

#### Tanulási források
- **🏭 Termelés**: [Termelési MI bevált gyakorlatok](docs/microsoft-foundry/production-ai-practices.md) - Vállalati minták
- **📝 Példák**: [Mikroszolgáltatások példa](../../examples/microservices) - Bonyolult architektúrák
- **📊 Monitorozás**: [Application Insights integráció](docs/pre-deployment/application-insights.md) - Monitorozás

#### Gyakorlati feladatok
- Vállalati biztonsági minták megvalósítása
- Átfogó monitorozás beállítása
- Telepítés termelésbe megfelelő irányítással

**💡 Fejezet eredmény**: Vállalatkész alkalmazások telepítése teljes termelési képességekkel

---

## 🎓 Műhely áttekintés: Gyakorlati tanulás

> **⚠️ MŰHELY ÁLLAPOT: Aktív fejlesztés**  
> A műhely anyagai fejlesztés alatt állnak. Az alap modulok működnek, de néhány haladó rész nem teljes. Folyamatosan dolgozunk a tartalom kiegészítésén. [Nyomon követés →](workshop/README.md)

### Interaktív műhely anyagok
**Átfogó gyakorlati tanulás böngésző-alapú eszközökkel és vezetett feladatokkal**

A műhely anyagai strukturált, interaktív tanulási élményt kínálnak, amely kiegészíti a fejezet-alapú tananyagot. A műhely önálló és oktató által vezetett munkamenetekre is alkalmas.

#### 🛠️ Műhely jellemzői
- **Böngésző alapú felület**: Teljes MkDocs-alapú műhely kereséssel, másolással és témával
- **GitHub Codespaces integráció**: Egykattintásos fejlesztői környezet beállítás
- **Strukturált tanulási út**: 7 lépéses vezetett feladatok (összesen 3,5 óra)
- **Felfedezés → Telepítés → Testreszabás**: Fokozatos módszertan
- **Interaktív DevContainer környezet**: Előkészített eszközök és függőségek

#### 📚 Műhely felépítése
A műhely a **Felfedezés → Telepítés → Testreszabás** módszertant követi:

1. **Felfedezési szakasz** (45 perc)
   - Microsoft Foundry sablonok és szolgáltatások felfedezése
   - Többügynökös architektúra minták megértése
   - Telepítési követelmények és előfeltételek áttekintése

2. **Telepítési szakasz** (2 óra)
   - MI alkalmazások gyakorlati telepítése AZD-vel
   - Azure MI szolgáltatások és végpontok konfigurálása
   - Biztonsági és hitelesítési minták megvalósítása

3. **Testreszabási szakasz** (45 perc)
   - Alkalmazások módosítása specifikus felhasználási esetekhez
   - Optimalizálás termelési telepítéshez
   - Monitorozás és költségkezelés bevezetése

#### 🚀 Indulás a műhellyel
```bash
# 1. lehetőség: GitHub Codespaces (Ajánlott)
# Kattintson a „Code” → „Create codespace on main” elemre a tárhelyen

# 2. lehetőség: Helyi fejlesztés
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# Kövesse a workshop/README.md fájlban található beállítási utasításokat
```

#### 🎯 Műhely tanulási eredmények
A műhely elvégzésével a résztvevők:
- **Telepítenek termelési MI alkalmazásokat**: AZD-vel és Microsoft Foundry szolgáltatásokkal
- **Elsajátítják a többügynökös architektúrákat**: Összehangolt MI ügynök megoldások implementálása
- **Megvalósítják a biztonsági legjobb gyakorlatokat**: Hitelesítés és hozzáférés-vezérlés beállítása
- **Optimalizálják a méretezést**: Költséghatékony, teljesítményorientált telepítések tervezése
- **Hibakeresési képességek**: Gyakori problémák önálló megoldása

#### 📖 Műhely források
- **🎥 Interaktív útmutató**: [Műhely anyagok](workshop/README.md) - Böngésző-alapú tanulási környezet
- **📋 Lépésenkénti útmutatók**: [Vezetett gyakorlatok](../../workshop/docs/instructions) - Részletes végigvezetés
- **🛠️ MI műhely labor**: [MI műhely labor](docs/microsoft-foundry/ai-workshop-lab.md) - MI fókuszú gyakorlatok
- **💡 Gyors indulás**: [Műhely beállítási útmutató](workshop/README.md#quick-start) - Környezetkonfiguráció

**Ideális**: Vállalati képzésekhez, egyetemi kurzusokhoz, önálló tanuláshoz és fejlesztői bootcamp-ekhez.

---

## 📖 Mi az az Azure Developer CLI?

Az Azure Developer CLI (azd) egy fejlesztőközpontú parancssori eszköz, amely felgyorsítja az alkalmazások Azure-ba történő építését és telepítését. A következőket kínálja:

- **Sablon alapú telepítések** – Előre elkészített sablonok gyakori alkalmazásmintákhoz  
- **Infrastructure as Code** – Azure erőforrások kezelése Bicep vagy Terraform segítségével  
- **Integrált munkafolyamatok** – Alkalmazások zökkenőmentes létrehozása, telepítése és monitorozása  
- **Fejlesztőbarát** – A fejlesztők hatékonyságának és élményének optimalizálása

### **AZD + Microsoft Foundry: Tökéletes MI telepítésekhez**

**Miért AZD az MI megoldásokhoz?** AZD a legfőbb kihívásokat célozza meg, amikkel az MI fejlesztők szembesülnek:

- **MI-re kész sablonok** – Azure OpenAI, Kognitív Szolgáltatások és ML terhelések előre konfigurált sablonjai  
- **Biztonságos MI telepítések** – Beépített biztonsági minták MI szolgáltatásokhoz, API kulcsokhoz és modellig végpontokhoz  
- **Termelési MI minták** – Bevett gyakorlatok skálázható, költséghatékony MI alkalmazás-telepítésekhez  
- **Végponttól-végpontig MI munkafolyamatok** – Modellfejlesztéstől a termelési telepítésig megfelelő monitorozással  
- **Költségoptimalizálás** – Okos erőforrás kiosztás és skálázási stratégiák MI terhelésekhez  
- **Microsoft Foundry integráció** – Zökkenőmentes csatlakozás a Microsoft Foundry modell katalógusához és végpontjaihoz

---

## 🎯 Sablontár és példatár

### Kiemelt: Microsoft Foundry sablonok
**Innen indulj, ha MI alkalmazásokat telepítesz!**

> **Megjegyzés:** Ezek a sablonok különféle MI mintákat mutatnak be. Egyesek külső Azure minták, mások helyi implementációk.

| Sablon | Fejezet | Bonyolultság | Szolgáltatások | Típus |
|--------|---------|--------------|----------------|-------|
| [**Az MI chat alapjai**](https://github.com/Azure-Samples/get-started-with-ai-chat) | 2. fejezet | ⭐⭐ | AzureOpenAI + Azure AI Modell Lekérdezés API + Azure AI Keresés + Azure Konténeralkalmazások + Application Insights | Külső |
| [**MI ügynökök alapjai**](https://github.com/Azure-Samples/get-started-with-ai-agents) | 2. fejezet | ⭐⭐ | Azure AI Ügynök szolgáltatás + AzureOpenAI + Azure AI Keresés + Azure Konténeralkalmazások + Application Insights | Külső |
| [**Azure Keresés + OpenAI Demó**](https://github.com/Azure-Samples/azure-search-openai-demo) | 2. fejezet | ⭐⭐ | AzureOpenAI + Azure AI Keresés + App Service + Storage | Külső |
| [**OpenAI Chat App Gyorsindítás**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | 2. fejezet | ⭐ | AzureOpenAI + Konténeralkalmazások + Application Insights | Külső |
| [**Agent OpenAI Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | 5. fejezet | ⭐⭐⭐ | AzureOpenAI + Azure Functions + Prompty | Külső |
| [**Contoso Chat RAG**](https://github.com/Azure-Samples/contoso-chat) | 8. fejezet | ⭐⭐⭐⭐ | AzureOpenAI + AI Keresés + Cosmos DB + Konténeralkalmazások | Külső |
| [**Kiskereskedelmi többügynökös megoldás**](examples/retail-scenario.md) | 5. fejezet | ⭐⭐⭐⭐ | AzureOpenAI + AI Keresés + Tárhely + Konténeralkalmazások + Cosmos DB | **Helyi** |

### Kiemelt: Teljes tanulási forgatókönyvek
**Termelésre kész alkalmazás sablonok tanulási fejezetekhez rendelve**

| Sablon | Tanulási fejezet | Bonyolultság | Fő tanulási pont |
|--------|------------------|--------------|------------------|
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | 2. fejezet | ⭐ | Alap MI telepítési minták |
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | 2. fejezet | ⭐⭐ | RAG megvalósítás Azure AI Kereséssel |
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | 4. fejezet | ⭐⭐ | Dokumentumintelligencia integráció |
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | 5. fejezet | ⭐⭐⭐ | Ügynök keretrendszer és függvényhívás |
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | 8. fejezet | ⭐⭐⭐ | Vállalati MI összehangolás |
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | 5. fejezet | ⭐⭐⭐⭐ | Többügynökös architektúra Ügyfél és Készlet ügynökökkel |

### Példa típus szerint tanulás

> **📌 Helyi vs. külső példák:**  
> **Helyi példák** (ebben a repo-ban) = Azonnal használható  
> **Külső példák** (Azure minták) = Linkelt repo-kból klónozandó

#### Helyi példák (Azonnal használható)
- [**Kiskereskedelmi többügynökös megoldás**](examples/retail-scenario.md) - Teljes üzemkész megvalósítás ARM sablonokkal
  - Többügynökös architektúra (Ügyfél + Készlet ügynökök)
  - Átfogó monitorozás és értékelés
  - Egykattintásos telepítés ARM sablonon keresztül

#### Helyi példák - Konténeralkalmazások (2-5. fejezet)
**Átfogó tárolós telepítés példák ebben a tárban:**
- [**Konténeralkalmazás példák**](examples/container-app/README.md) - Teljes útmutató konténeres telepítésekhez
  - [Egyszerű Flask API](../../examples/container-app/simple-flask-api) - Alap REST API skálázás nullára
  - [Mikroszolgáltatás architektúra](../../examples/container-app/microservices) - Üzemkész több szolgáltatás telepítés
  - Gyorsindítás, Termelés, Haladó telepítési minták
  - Monitorozás, biztonság és költségoptimalizálási útmutató

#### Külső példák – Egyszerű alkalmazások (1-2. fejezet)
**Klónozd ezeket az Azure mintapéldányokat az induláshoz:**
- [Egyszerű webalkalmazás - Node.js + MongoDB](https://github.com/Azure-Samples/todo-nodejs-mongo) - Alap telepítési minták
- [Statikus weboldal - React SPA](https://github.com/Azure-Samples/todo-csharp-sql-swa-func) - Statikus tartalom telepítés
- [Konténeralkalmazás - Python Flask](https://github.com/Azure-Samples/container-apps-store-api-microservice) - REST API telepítés

#### Külső példák – Adatbázis integráció (3-4. fejezet)  
- [Adatbázis alkalmazás - C# + SQL](https://github.com/Azure-Samples/todo-csharp-sql) - Adatbázis kapcsolódási minták
- [Funkciók + Cosmos DB](https://github.com/Azure-Samples/todo-python-mongo-swa-func) - Szerver nélküli adat munkafolyamat

#### Külső példák – Haladó minták (4-8. fejezet)
- [Java mikroszolgáltatások](https://github.com/Azure-Samples/java-microservices-aca-lab) - Több szolgáltatásos architektúrák
- [Konténeralkalmazás háttérfeladatok](https://github.com/Azure-Samples/container-apps-jobs) - Háttérfeldolgozás  
- [Vállalati gépi tanulási pipeline](https://github.com/Azure-Samples/mlops-v2) - Üzemkész ML minták

### Külső sablontárak  

- [**Hivatalos AZD sablongyűjtemény**](https://azure.github.io/awesome-azd/) - Válogatott hivatalos és közösségi sablonok gyűjteménye  
- [**Azure Developer CLI sablonok**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - Microsoft Learn sablon dokumentáció  
- [**Példák könyvtára**](examples/README.md) - Helyi tanulási példák részletes magyarázatokkal

---

## 📚 Tanulási anyagok és hivatkozások

### Gyorshivatkozások
- [**Parancs gyorslista**](resources/cheat-sheet.md) - Alapvető azd parancsok fejezetenként rendszerezve  
- [**Fogalomtár**](resources/glossary.md) - Azure és azd terminológia  
- [**GYIK**](resources/faq.md) - Gyakori kérdések tanulási fejezetenként rendszerezve  
- [**Tanulmányi útmutató**](resources/study-guide.md) - Átfogó gyakorlati feladatok

### Gyakorlati workshopok
- [**AI Workshop Lab**](docs/microsoft-foundry/ai-workshop-lab.md) - Készítsd el AI megoldásaidat AZD telepíthetővé (2-3 óra)  
- [**Interaktív workshop útmutató**](workshop/README.md) - Böngészőalapú workshop MkDocs és DevContainer környezettel  
- [**Strukturált tanulási út**](../../workshop/docs/instructions) - 7 lépéses vezetett gyakorlatok (Felfedezés → Telepítés → Testreszabás)  
- [**AZD kezdőknek workshop**](workshop/README.md) - Teljes gyakorlati workshop anyag GitHub Codespaces integrációval

### Külső tanulási források
- [Azure Developer CLI dokumentáció](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)  
- [Azure architektúra központ](https://learn.microsoft.com/en-us/azure/architecture/)  
- [Azure árkalkulátor](https://azure.microsoft.com/pricing/calculator/)  
- [Azure állapot](https://status.azure.com/)

---

## 🔧 Gyors hibaelhárítási útmutató

**Gyakori problémák, amikkel a kezdők szembesülnek, és azonnali megoldások:**

### ❌ "azd: parancs nem található"

```bash
# Először telepítse az AZD-t
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Telepítés ellenőrzése
azd version
```
  
### ❌ "Nem található előfizetés" vagy "Előfizetés nincs beállítva"

```bash
# Elérhető előfizetések listázása
az account list --output table

# Alapértelmezett előfizetés beállítása
az account set --subscription "<subscription-id-or-name>"

# Beállítás az AZD környezethez
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Ellenőrzés
az account show
```
  
### ❌ "InsufficientQuota" vagy "Kvóta túllépve"

```bash
# Próbáljon ki más Azure régiót
azd env set AZURE_LOCATION "westus2"
azd up

# Vagy használjon kisebb SKU-kat fejlesztéshez
# Szerkessze az infra/main.parameters.json fájlt:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
  
### ❌ "azd up" középen hibára fut

```bash
# 1. lehetőség: Tisztítás és újrapróbálkozás
azd down --force --purge
azd up

# 2. lehetőség: Csak az infrastruktúra javítása
azd provision

# 3. lehetőség: Részletes naplók ellenőrzése
azd show
azd logs
```
  
### ❌ "Hitelesítés sikertelen" vagy "Token lejárt"

```bash
# Újra hitelesítés
az logout
az login

azd auth logout
azd auth login

# Hitelesítés ellenőrzése
az account show
```
  
### ❌ "Erőforrás már létezik" vagy névütközések

```bash
# Az AZD egyedi neveket generál, de ha ütközés van:
azd down --force --purge

# Akkor próbáld újra friss környezettel
azd env new dev-v2
azd up
```
  
### ❌ Sablon telepítése túl hosszú ideig tart

**Normális várakozási idők:**  
- Egyszerű webalkalmazás: 5-10 perc  
- Adatbázissal rendelkező alkalmazás: 10-15 perc  
- AI alkalmazások: 15-25 perc (OpenAI szolgáltatás lassú)  

```bash
# Ellenőrizze a folyamatot
azd show

# Ha 30 percnél tovább elakadt, ellenőrizze az Azure Portal-t:
azd monitor
# Keresse az sikertelen telepítéseket
```
  
### ❌ "Hozzáférés megtagadva" vagy "Tiltott"

```bash
# Ellenőrizze az Azure szerepkörét
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Legalább "Közreműködő" szerepkörre van szüksége
# Kérje meg Azure adminisztrátorát, hogy adja meg:
# - Közreműködő (erőforrásokhoz)
# - Felhasználói hozzáférés-kezdeményező (szerepkör-hozzárendelésekhez)
```
  
### ❌ Nem található a telepített alkalmazás URL-je

```bash
# Az összes szolgáltatás végpontjainak megjelenítése
azd show

# Vagy nyissa meg az Azure Portált
azd monitor

# Ellenőrizzen egy adott szolgáltatást
azd env get-values
# Keresse meg a *_URL változókat
```
  
### 📚 Teljes hibaelhárítási erőforrások

- **Gyakori problémák útmutató:** [Részletes megoldások](docs/troubleshooting/common-issues.md)  
- **AI-specifikus problémák:** [AI hibaelhárítás](docs/troubleshooting/ai-troubleshooting.md)  
- **Hibakeresési útmutató:** [Lépésről lépésre hibakeresés](docs/troubleshooting/debugging.md)  
- **Segítségkérés:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🔧 Gyors hibaelhárítási útmutató

**Gyakori problémák, amikkel a kezdők szembesülnek, és azonnali megoldások:**

<details>
<summary><strong>❌ "azd: parancs nem található"</strong></summary>

```bash
# Először telepítse az AZD-t
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Ellenőrizze a telepítést
azd version
```
</details>

<details>
<summary><strong>❌ "Nem található előfizetés" vagy "Előfizetés nincs beállítva"</strong></summary>

```bash
# Elérhető előfizetések listázása
az account list --output table

# Alapértelmezett előfizetés beállítása
az account set --subscription "<subscription-id-or-name>"

# Beállítás az AZD környezethez
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Ellenőrzés
az account show
```
</details>

<details>
<summary><strong>❌ "InsufficientQuota" vagy "Kvóta túllépve"</strong></summary>

```bash
# Próbáljon ki más Azure régiót
azd env set AZURE_LOCATION "westus2"
azd up

# Vagy használjon kisebb SKU-kat fejlesztésben
# Szerkessze az infra/main.parameters.json fájlt:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>

<details>
<summary><strong>❌ "azd up" középen hibára fut</strong></summary>

```bash
# 1. lehetőség: Tisztítás és újrapróbálkozás
azd down --force --purge
azd up

# 2. lehetőség: Csak az infrastruktúra javítása
azd provision

# 3. lehetőség: Részletes naplók ellenőrzése
azd show
azd logs
```
</details>

<details>
<summary><strong>❌ "Hitelesítés sikertelen" vagy "Token lejárt"</strong></summary>

```bash
# Újrahitelesítés
az logout
az login

azd auth logout
azd auth login

# Hitelesítés ellenőrzése
az account show
```
</details>

<details>
<summary><strong>❌ "Erőforrás már létezik" vagy névütközések</strong></summary>

```bash
# Az AZD egyedi neveket generál, de ha ütközés van:
azd down --force --purge

# Akkor próbálja újra új környezettel
azd env new dev-v2
azd up
```
</details>

<details>
<summary><strong>❌ Sablon telepítése túl hosszú ideig tart</strong></summary>

**Normális várakozási idők:**  
- Egyszerű webalkalmazás: 5-10 perc  
- Adatbázissal rendelkező alkalmazás: 10-15 perc  
- AI alkalmazások: 15-25 perc (OpenAI szolgáltatás lassú)  

```bash
# Ellenőrizze a haladást
azd show

# Ha 30 percnél tovább fennakadt, ellenőrizze az Azure Portált:
azd monitor
# Keresse a sikertelen telepítéseket
```
</details>

<details>
<summary><strong>❌ "Hozzáférés megtagadva" vagy "Tiltott"</strong></summary>

```bash
# Ellenőrizze Azure szerepkörét
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Legalább a "Contributor" szerepkör szükséges
# Kérje Azure adminisztrátorát, hogy adja meg:
# - Contributor (erőforrásokhoz)
# - User Access Administrator (szerepkör-hozzárendelésekhez)
```
</details>

<details>
<summary><strong>❌ Nem található a telepített alkalmazás URL-je</strong></summary>

```bash
# Az összes szolgáltatási végpont megjelenítése
azd show

# Vagy nyissa meg az Azure Portált
azd monitor

# Ellenőrizze a konkrét szolgáltatást
azd env get-values
# Keresse a *_URL változókat
```
</details>

### 📚 Teljes hibaelhárítási erőforrások

- **Gyakori problémák útmutató:** [Részletes megoldások](docs/troubleshooting/common-issues.md)  
- **AI-specifikus problémák:** [AI hibaelhárítás](docs/troubleshooting/ai-troubleshooting.md)  
- **Hibakeresési útmutató:** [Lépésről lépésre hibakeresés](docs/troubleshooting/debugging.md)  
- **Segítségkérés:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🎓 Tanfolyam befejezése és tanúsítás

### Haladás nyomonkövetése  
Kövesd tanulási előrehaladásodat fejezetenként:

- [ ] **1. fejezet**: Alapok és gyors kezdés ✅  
- [ ] **2. fejezet**: AI-vezérelt fejlesztés ✅  
- [ ] **3. fejezet**: Konfiguráció és hitelesítés ✅  
- [ ] **4. fejezet**: Infrastruktúra kódként és telepítés ✅  
- [ ] **5. fejezet**: Többügynökös AI megoldások ✅  
- [ ] **6. fejezet**: Előzetes validáció és tervezés ✅  
- [ ] **7. fejezet**: Hibaelhárítás és hibakeresés ✅  
- [ ] **8. fejezet**: Termelési és vállalati minták ✅

### Tanulás ellenőrzése  
Minden fejezet elvégzése után ellenőrizd tudásod:  
1. **Gyakorlati feladat:** Végezd el a fejezet telepítési gyakorlatát  
2. **Tudásellenőrzés:** Tekintsd át a fejezet GYIK szekcióját  
3. **Közösségi beszélgetés:** Oszd meg tapasztalataid az Azure Discord-ban  
4. **Következő fejezet:** Lépj tovább a következő nehézségi szintre

### A tanfolyam elvégzésének előnyei  
Minden fejezet befejezése után rendelkezel majd:  
- **Termelési tapasztalat:** Valódi AI alkalmazások telepítése Azure-ba  
- **Szakmai képességek:** Vállalati szintű telepítési képességek  
- **Közösségi elismerés:** Az Azure fejlesztői közösség aktív tagja  
- **Karrier előrelépés:** Keresett AZD és AI telepítési szakértelem

---

## 🤝 Közösség és támogatás

### Segítségkérés és támogatás  
- **Technikai problémák:** [Hibajelentések és funkciókérések](https://github.com/microsoft/azd-for-beginners/issues)  
- **Tanulási kérdések:** [Microsoft Azure Discord közösség](https://discord.gg/microsoft-azure) és [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)  
- **AI-specifikus segítség:** Csatlakozz a [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG) szerverhez  
- **Dokumentáció:** [Hivatalos Azure Developer CLI dokumentáció](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)

### Közösségi betekintések a Microsoft Foundry Discordból

**Legfrissebb szavazási eredmények a #Azure csatornán:**  
- A fejlesztők **45%-a** szeretné az AZD-t AI feladatokra használni  
- **Legnagyobb kihívások:** Többszolgáltatásos telepítések, hitelesítés kezelése, termelési készültség  
- **Leggyakrabban kért:** AI-specifikus sablonok, hibaelhárítási útmutatók, legjobb gyakorlatok

**Csatlakozz közösségünkhöz, hogy:**  
- Megoszd AZD + AI tapasztalataidat és segítséget kapj  
- Hozzáférj új AI sablonok korai verzióihoz  
- Hozzájárulj AI telepítési legjobb gyakorlatokhoz  
- Befolyásold a jövő AI + AZD fejlesztéseit

### Hozzájárulás a tanfolyamhoz  
Örömmel fogadjuk a hozzájárulásokat! Kérjük, olvasd el a [Hozzájárulási útmutatót](CONTRIBUTING.md) a részletekért:  
- **Tartalomfejlesztés:** Fejlessz meglévő fejezeteket és példákat  
- **Új példák:** Adj hozzá valós helyzeteket és sablonokat  
- **Fordítás:** Segíts fenntartani a többnyelvű támogatást  
- **Hibajelentések:** Növeld a pontosságot és érthetőséget  
- **Közösségi irányelvek:** Kövesd befogadó közösségi szabályzatunkat

---

## 📄 Tanfolyaminformációk

### Licenc  
Ez a projekt az MIT licenc alatt áll - lásd a [LICENSE](../../LICENSE) fájlt a részletekért.

### Kapcsolódó Microsoft tanulási források

Csapatunk további átfogó tanfolyamokat kínál:

<!-- CO-OP TRANSLATOR OTHER COURSES START -->
### LangChain  
[![LangChain4j kezdőknek](https://img.shields.io/badge/LangChain4j%20for%20Beginners-22C55E?style=for-the-badge&&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchain4j-for-beginners)  
[![LangChain.js kezdőknek](https://img.shields.io/badge/LangChain.js%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchainjs-for-beginners?WT.mc_id=m365-94501-dwahlin)

---

### Azure / Edge / MCP / Ügynökök  
[![AZD kezdőknek](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)  
[![Edge AI kezdőknek](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)  
[![MCP kezdőknek](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)  
[![AI Ügynökök kezdőknek](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)

---

### Generatív AI sorozat  
[![Generatív AI kezdőknek](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)  
[![Generatív AI (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)  
[![Generatív AI (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)  
[![Generatív AI (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---

### Core Learning  
[![Gépi tanulás kezdőknek](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![Adattudomány kezdőknek](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![Mesterséges intelligencia kezdőknek](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Kiberbiztonság kezdőknek](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Webfejlesztés kezdőknek](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![IoT kezdőknek](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![XR fejlesztés kezdőknek](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Copilot sorozat
[![Copilot mesterséges intelligencia páros programozáshoz](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![Copilot C#/.NET fejlesztéshez](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Copilot kaland](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ Tanfolyam navigáció

**🚀 Készen állsz a tanulásra?**

**Kezdőknek**: Kezdj a [1. fejezettel: Alapok & Gyors kezdés](../..)  
**AI fejlesztőknek**: Ugorj a [2. fejezethez: AI-központú fejlesztés](../..)  
**Tapasztalt fejlesztőknek**: Kezdj a [3. fejezettel: Konfiguráció & hitelesítés](../..)

**Következő lépések**: [Kezdd az 1. fejezettel - AZD alapok](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Jogi nyilatkozat**:
Ez a dokumentum az AI fordító szolgáltatás, a [Co-op Translator](https://github.com/Azure/co-op-translator) segítségével készült. Bár az pontosságra törekszünk, kérjük, vegye figyelembe, hogy az automatikus fordítások hibákat vagy pontatlanságokat tartalmazhatnak. Az eredeti dokumentum az anyanyelvén tekintendő hivatalos forrásnak. Kritikus információk esetén profi, emberi fordítást javaslunk. Nem vállalunk felelősséget az ebből a fordításból eredő félreértésekért vagy félreértelmezésekért.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->