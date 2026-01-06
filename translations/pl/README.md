<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T13:28:08+00:00",
  "source_file": "README.md",
  "language_code": "pl"
}
-->
> Uwaga: Ta dokumentacja jest na bieżąco aktualizowana, aby odzwierciedlać najnowsze zmiany.

> ⚠️ To repozytorium jest demonstracją stworzoną w celu zaprezentowania
> automatycznej lokalizacji dokumentacji przy użyciu Localizeflow.
>
> Oryginalna treść bazuje na
> projekcie Microsoft „AZD dla początkujących”.


# AZD dla początkujących: Strukturalna ścieżka nauki

![AZD-for-beginners](../../translated_images/azdbeginners.5527441dd9f74068.pl.png) 

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## Rozpocznij kurs

Wykonaj te kroki, aby rozpocząć swoją ścieżkę nauki AZD:

1. **Rozgałęź repozytorium**: Kliknij [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)
2. **Sklonuj repozytorium**: `git clone https://github.com/microsoft/azd-for-beginners.git`
3. **Dołącz do społeczności**: [Społeczności Azure Discord](https://discord.com/invite/ByRwuEEgH4) dla wsparcia ekspertów
4. **Wybierz ścieżkę nauki**: Wybierz rozdział poniżej odpowiadający Twojemu poziomowi doświadczenia

### Obsługa wielu języków

#### Automatyczne tłumaczenia (zawsze aktualne)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabski](../ar/README.md) | [Bengalski](../bn/README.md) | [Bułgarski](../bg/README.md) | [Birmański (Myanmar)](../my/README.md) | [Chiński (uproszczony)](../zh/README.md) | [Chiński (tradycyjny, Hongkong)](../hk/README.md) | [Chiński (tradycyjny, Makau)](../mo/README.md) | [Chiński (tradycyjny, Tajwan)](../tw/README.md) | [Chorwacki](../hr/README.md) | [Czeski](../cs/README.md) | [Duński](../da/README.md) | [Niderlandzki](../nl/README.md) | [Estoński](../et/README.md) | [Fiński](../fi/README.md) | [Francuski](../fr/README.md) | [Niemiecki](../de/README.md) | [Grecki](../el/README.md) | [Hebrajski](../he/README.md) | [Hindi](../hi/README.md) | [Węgierski](../hu/README.md) | [Indonezyjski](../id/README.md) | [Włoski](../it/README.md) | [Japoński](../ja/README.md) | [Kannada](../kn/README.md) | [Koreański](../ko/README.md) | [Litewski](../lt/README.md) | [Malajski](../ms/README.md) | [Malajalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepalski](../ne/README.md) | [Nigeryjski pidżyn](../pcm/README.md) | [Norweski](../no/README.md) | [Perski (Farsi)](../fa/README.md) | [Polski](./README.md) | [Portugalski (Brazylia)](../br/README.md) | [Portugalski (Portugalia)](../pt/README.md) | [Pendżabski (Gurmukhi)](../pa/README.md) | [Rumuński](../ro/README.md) | [Rosyjski](../ru/README.md) | [Serbski (Cyrylica)](../sr/README.md) | [Słowacki](../sk/README.md) | [Słoweński](../sl/README.md) | [Hiszpański](../es/README.md) | [Suahili](../sw/README.md) | [Szwedzki](../sv/README.md) | [Tagalog (Filipiński)](../tl/README.md) | [Tamilski](../ta/README.md) | [Telugu](../te/README.md) | [Tajski](../th/README.md) | [Turecki](../tr/README.md) | [Ukraiński](../uk/README.md) | [Urdu](../ur/README.md) | [Wietnamski](../vi/README.md)

> **Wolisz klonować lokalnie?**

> To repozytorium zawiera tłumaczenia na ponad 50 języków, co znacznie zwiększa rozmiar pobierania. Aby sklonować bez tłumaczeń, użyj sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Dzięki temu otrzymujesz wszystko, co potrzebne do ukończenia kursu, ale pobieranie jest znacznie szybsze.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## Przegląd kursu

Opanuj Azure Developer CLI (azd) przez strukturalne rozdziały zaprojektowane dla stopniowego uczenia się. **Specjalny nacisk na wdrażanie aplikacji AI z integracją Microsoft Foundry.**

### Dlaczego ten kurs jest niezbędny dla współczesnych programistów

Na podstawie informacji z Microsoft Foundry Discord, **45% programistów chce używać AZD do obciążeń AI**, ale napotyka wyzwania związane z:
- Złożonymi architekturami AI z wieloma usługami
- Najlepszymi praktykami wdrożeń produkcyjnych AI  
- Integracją i konfiguracją usług Azure AI
- Optymalizacją kosztów dla obciążeń AI
- Rozwiązywaniem problemów specyficznych dla wdrożeń AI

### Cele nauki

Po ukończeniu tego strukturalnego kursu:
- **Opanujesz podstawy AZD**: kluczowe koncepcje, instalacja i konfiguracja
- **Wdrożysz aplikacje AI**: używając AZD razem z usługami Microsoft Foundry
- **Wdrożysz infrastrukturę jako kod**: zarządzanie zasobami Azure za pomocą szablonów Bicep
- **Rozwiążesz problemy wdrożeń**: diagnoza i usuwanie błędów
- **Zoptymalizujesz wdrożenia produkcyjne**: bezpieczeństwo, skalowanie, monitorowanie i zarządzanie kosztami
- **Stworzysz rozwiązania multi-agentowe**: wdrażanie złożonych architektur AI

## 📚 Rozdziały kursu

*Wybierz swoją ścieżkę nauki w zależności od poziomu doświadczenia i celów*

### 🚀 Rozdział 1: Podstawy i szybki start
**Wymagania wstępne**: subskrypcja Azure, podstawowa znajomość linii poleceń  
**Czas trwania**: 30-45 minut  
**Poziom trudności**: ⭐

#### Czego się nauczysz
- Podstawy Azure Developer CLI
- Instalacja AZD na Twojej platformie
- Twoje pierwsze udane wdrożenie

#### Materiały do nauki
- **🎯 Zacznij tutaj**: [Czym jest Azure Developer CLI?](../..)
- **📖 Teoria**: [Podstawy AZD](docs/getting-started/azd-basics.md) - Kluczowe pojęcia i terminologia
- **⚙️ Konfiguracja**: [Instalacja i ustawienia](docs/getting-started/installation.md) - Przewodniki dla platform
- **🛠️ Praktyka**: [Twój pierwszy projekt](docs/getting-started/first-project.md) - Tutorial krok po kroku
- **📋 Skrócony przewodnik**: [Tabela poleceń](resources/cheat-sheet.md)

#### Ćwiczenia praktyczne
```bash
# Szybkie sprawdzenie instalacji
azd version

# Wdróż swoją pierwszą aplikację
azd init --template todo-nodejs-mongo
azd up
```

**💡 Efekt rozdziału**: Pomyślnie wdrożysz prostą aplikację webową do Azure przy użyciu AZD

**✅ Potwierdzenie sukcesu:**
```bash
# Po ukończeniu rozdziału 1 powinieneś być w stanie:
azd version              # Pokazuje zainstalowaną wersję
azd init --template todo-nodejs-mongo  # Inicjalizuje projekt
azd up                  # Wdraża do Azure
azd show                # Wyświetla adres URL działającej aplikacji
# Aplikacja otwiera się w przeglądarce i działa
azd down --force --purge  # Usuwa zasoby
```

**📊 Czas potrzebny:** 30-45 minut  
**📈 Poziom umiejętności po ukończeniu:** Potrafi samodzielnie wdrażać podstawowe aplikacje

**✅ Potwierdzenie sukcesu:**
```bash
# Po ukończeniu Rozdziału 1, powinieneś być w stanie:
azd version              # Pokazuje zainstalowaną wersję
azd init --template todo-nodejs-mongo  # Inicjalizuje projekt
azd up                  # Wdraża do Azure
azd show                # Wyświetla URL działającej aplikacji
# Aplikacja otwiera się w przeglądarce i działa
azd down --force --purge  # Czyści zasoby
```

**📊 Czas potrzebny:** 30-45 minut  
**📈 Poziom umiejętności po ukończeniu:** Potrafi samodzielnie wdrażać podstawowe aplikacje

---

### 🤖 Rozdział 2: Rozwój AI (zalecany dla programistów AI)
**Wymagania wstępne**: ukończony rozdział 1  
**Czas trwania**: 1-2 godziny  
**Poziom trudności**: ⭐⭐

#### Czego się nauczysz
- Integracja Microsoft Foundry z AZD
- Wdrażanie aplikacji zasilanych AI
- Zrozumienie konfiguracji usług AI

#### Materiały do nauki
- **🎯 Zacznij tutaj**: [Integracja Microsoft Foundry](docs/microsoft-foundry/microsoft-foundry-integration.md)
- **📖 Wzorce**: [Wdrażanie modeli AI](docs/microsoft-foundry/ai-model-deployment.md) - Wdrażaj i zarządzaj modelami AI
- **🛠️ Laboratorium**: [Warsztaty AI](docs/microsoft-foundry/ai-workshop-lab.md) - Przygotuj swoje rozwiązania AI do AZD
- **🎥 Interaktywny przewodnik**: [Materiały warsztatowe](workshop/README.md) - nauka przez przeglądarkę z MkDocs * środowisko DevContainer
- **📋 Szablony**: [Szablony Microsoft Foundry](../..)
- **📝 Przykłady**: [Przykłady wdrożeń AZD](examples/README.md)

#### Ćwiczenia praktyczne
```bash
# Wdróż swoją pierwszą aplikację AI
azd init --template azure-search-openai-demo
azd up

# Wypróbuj dodatkowe szablony AI
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```

**💡 Efekt rozdziału**: Wdrożysz i skonfigurujesz aplikację czatu zasilaną AI z funkcjonalnościami RAG

**✅ Potwierdzenie sukcesu:**
```bash
# Po rozdziale 2 powinieneś być w stanie:
azd init --template azure-search-openai-demo
azd up
# Testować interfejs czatu AI
# Zadawać pytania i otrzymywać odpowiedzi wspierane przez AI z źródłami
# Sprawdzić, czy integracja wyszukiwania działa
azd monitor  # Sprawdzić, czy Application Insights pokazuje telemetrię
azd down --force --purge
```

**📊 Czas potrzebny:** 1-2 godziny  
**📈 Poziom umiejętności po ukończeniu:** Potrafi wdrażać i konfigurować aplikacje AI gotowe do produkcji  
**💰 Świadomość kosztów:** Rozumie koszty rozwoju $80-150/mies., koszty produkcji $300-3500/mies.

#### 💰 Rozważania kosztowe dla wdrożeń AI

**Środowisko deweloperskie (szacunkowo $80-150/mies.):**
- Azure OpenAI (płatność zgodnie z użyciem): $0-50/mies. (w zależności od liczby tokenów)
- AI Search (poziom podstawowy): $75/mies.
- Container Apps (rozliczenie zużycia): $0-20/mies.
- Storage (standardowy): $1-5/mies.

**Środowisko produkcyjne (szacunkowo $300-3,500+/mies.):**
- Azure OpenAI (PTU dla stałej wydajności): $3000+/mies. LUB płatność zgodnie z użyciem przy dużym wolumenie
- AI Search (poziom standard): $250/mies.
- Container Apps (dedykowane): $50-100/mies.
- Application Insights: $5-50/mies.
- Storage (premium): $10-50/mies.

**💡 Wskazówki optymalizacji kosztów:**
- Używaj planu **Free Tier** Azure OpenAI do nauki (wliczone 50,000 tokenów/mies.)
- Wykonuj `azd down` aby zwolnić zasoby gdy nie rozwijasz aktywnie
- Zacznij od rozliczenia zużycia, a PTU wdrażaj tylko w produkcji
- Używaj `azd provision --preview` aby oszacować koszty przed wdrożeniem
- Włącz auto-skalowanie: płacisz tylko za rzeczywiste użycie

**Monitorowanie kosztów:**
```bash
# Sprawdź szacowane miesięczne koszty
azd provision --preview

# Monitoruj rzeczywiste koszty w Azure Portal
az consumption budget list --resource-group <your-rg>
```

---

### ⚙️ Rozdział 3: Konfiguracja i uwierzytelnianie
**Wymagania wstępne**: ukończony rozdział 1  
**Czas trwania**: 45-60 minut  
**Poziom trudności**: ⭐⭐

#### Czego się nauczysz
- Konfiguracja i zarządzanie środowiskami
- Najlepsze praktyki uwierzytelniania i bezpieczeństwa
- Nazewnictwo i organizacja zasobów

#### Materiały do nauki
- **📖 Konfiguracja**: [Przewodnik konfiguracji](docs/getting-started/configuration.md) - ustawienia środowiska
- **🔐 Bezpieczeństwo**: [Wzorce uwierzytelniania i managed identity](docs/getting-started/authsecurity.md)  
- **📝 Przykłady**: [Przykład aplikacji bazodanowej](examples/database-app/README.md) - przykłady użycia AZD z bazą danych

#### Ćwiczenia praktyczne
- Skonfiguruj wiele środowisk (dev, staging, prod)
- Skonfiguruj uwierzytelnianie managed identity
- Wdroż konfiguracje specyficzne dla środowisk

**💡 Efekt rozdziału**: Zarządzaj wieloma środowiskami z poprawnym uwierzytelnianiem i zabezpieczeniami

---

### 🏗️ Rozdział 4: Infrastruktura jako kod i wdrożenie
**Wymagania wstępne**: ukończone rozdziały 1-3  
**Czas trwania**: 1-1,5 godziny  
**Poziom trudności**: ⭐⭐⭐

#### Czego się nauczysz
- Zaawansowane wzorce wdrożeń
- Infrastruktura jako kod z Bicep
- Strategie zarządzania zasobami

#### Materiały do nauki
- **📖 Wdrożenie**: [Przewodnik wdrożeń](docs/deployment/deployment-guide.md) - kompletne workflow
- **🏗️ Provisioning**: [Provisioning zasobów](docs/deployment/provisioning.md) - zarządzanie zasobami Azure
- **📝 Przykłady**: [Przykład aplikacji kontenerowej](../../examples/container-app) - wdrożenia konteneryzowane

#### Ćwiczenia praktyczne
- Twórz własne szablony Bicep
- Wdrażaj aplikacje wielousługowe
- Stosuj strategie blue-green deployment

**💡 Efekt rozdziału**: Wdrażaj złożone aplikacje wielousługowe używając niestandardowych szablonów infrastruktury

---
### 🎯 Rozdział 5: Rozwiązania AI z wieloma agentami (Zaawansowane)  
**Wymagania wstępne**: Rozdziały 1-2 ukończone  
**Czas trwania**: 2-3 godziny  
**Stopień trudności**: ⭐⭐⭐⭐

#### Czego się nauczysz  
- Wzorce architektury wieloagentowej  
- Orkiestracja i koordynacja agentów  
- Gotowe do produkcji wdrożenia AI

#### Zasoby edukacyjne  
- **🤖 Projekt specjalny**: [Rozwiązanie wieloagentowe dla handlu detalicznego](examples/retail-scenario.md) - Pełna implementacja  
- **🛠️ Szablony ARM**: [Pakiet szablonów ARM](../../examples/retail-multiagent-arm-template) - Wdrożenie jednym kliknięciem  
- **📖 Architektura**: [Wzorce koordynacji wieloagentowej](/docs/pre-deployment/coordination-patterns.md) - Wzorce

#### Ćwiczenia praktyczne  
```bash
# Wdroż kompletne rozwiązanie wieloagentowe dla handlu detalicznego
cd examples/retail-multiagent-arm-template
./deploy.sh

# Eksploruj konfiguracje agentów
az deployment group show --resource-group <rg-name> --name <deployment-name>
```
  
**💡 Efekt rozdziału**: Wdrożenie i zarządzanie produkcyjnym rozwiązaniem AI z wieloma agentami: agent klienta oraz agent zapasów

---

### 🔍 Rozdział 6: Walidacja i planowanie przed wdrożeniem  
**Wymagania wstępne**: Rozdział 4 ukończony  
**Czas trwania**: 1 godzina  
**Stopień trudności**: ⭐⭐

#### Czego się nauczysz  
- Planowanie pojemności i walidacja zasobów  
- Strategie wyboru SKU  
- Kontrole pre-flight i automatyzacja

#### Zasoby edukacyjne  
- **📊 Planowanie**: [Planowanie pojemności](docs/pre-deployment/capacity-planning.md) - Walidacja zasobów  
- **💰 Wybór**: [Wybór SKU](docs/pre-deployment/sku-selection.md) - Kosztowo efektywne decyzje  
- **✅ Walidacja**: [Kontrole pre-flight](docs/pre-deployment/preflight-checks.md) - Automatyczne skrypty

#### Ćwiczenia praktyczne  
- Uruchomienie skryptów walidacji pojemności  
- Optymalizacja wyboru SKU pod kątem kosztów  
- Implementacja zautomatyzowanych kontroli przed wdrożeniem

**💡 Efekt rozdziału**: Walidacja i optymalizacja wdrożeń przed wykonaniem

---

### 🚨 Rozdział 7: Rozwiązywanie problemów i debugowanie  
**Wymagania wstępne**: Wdrożeniowy rozdział ukończony  
**Czas trwania**: 1-1,5 godziny  
**Stopień trudności**: ⭐⭐

#### Czego się nauczysz  
- Systematyczne podejścia do debugowania  
- Typowe problemy i rozwiązania  
- Specyficzne dla AI rozwiązywanie problemów

#### Zasoby edukacyjne  
- **🔧 Typowe problemy**: [Typowe problemy](docs/troubleshooting/common-issues.md) - FAQ i rozwiązania  
- **🕵️ Debugowanie**: [Przewodnik po debugowaniu](docs/troubleshooting/debugging.md) - Strategie krok po kroku  
- **🤖 Problemy AI**: [Rozwiązywanie problemów w AI](docs/troubleshooting/ai-troubleshooting.md) - Problemy usług AI

#### Ćwiczenia praktyczne  
- Diagnoza błędów wdrożenia  
- Rozwiązywanie problemów z autoryzacją  
- Debugowanie łączności usług AI

**💡 Efekt rozdziału**: Samodzielna diagnoza i rozwiązanie najczęstszych problemów wdrożeniowych

---

### 🏢 Rozdział 8: Wzorce produkcyjne i korporacyjne  
**Wymagania wstępne**: Rozdziały 1-4 ukończone  
**Czas trwania**: 2-3 godziny  
**Stopień trudności**: ⭐⭐⭐⭐

#### Czego się nauczysz  
- Strategie wdrożeń produkcyjnych  
- Korporacyjne wzorce bezpieczeństwa  
- Monitorowanie i optymalizacja kosztów

#### Zasoby edukacyjne  
- **🏭 Produkcja**: [Najlepsze praktyki AI w produkcji](docs/microsoft-foundry/production-ai-practices.md) - Wzorce korporacyjne  
- **📝 Przykłady**: [Przykład mikroserwisów](../../examples/microservices) - Złożone architektury  
- **📊 Monitorowanie**: [Integracja Application Insights](docs/pre-deployment/application-insights.md) - Monitorowanie

#### Ćwiczenia praktyczne  
- Implementacja wzorców bezpieczeństwa korporacyjnego  
- Konfiguracja kompleksowego monitorowania  
- Wdrożenie produkcyjne z właściwym zarządzaniem

**💡 Efekt rozdziału**: Wdrożenie aplikacji gotowych do produkcji z pełną funkcjonalnością produkcyjną

---

## 🎓 Przegląd warsztatów: Praktyczne doświadczenie edukacyjne

> **⚠️ STATUS WARSZTATU: W trakcie rozwoju**  
> Materiały warsztatowe są obecnie opracowywane i dopracowywane. Podstawowe moduły działają, ale niektóre sekcje zaawansowane są nieukończone. Intensywnie pracujemy nad ukończeniem całości. [Śledź postępy →](workshop/README.md)

### Interaktywne materiały warsztatowe  
**Kompleksowa nauka praktyczna z narzędziami przeglądarkowymi i ćwiczeniami z przewodnikiem**

Materiały warsztatowe oferują ustrukturyzowane, interaktywne doświadczenie edukacyjne uzupełniające powyższy program rozdziałów. Warsztat jest przeznaczony zarówno do samodzielnej nauki, jak i prowadzenia z instruktorem.

#### 🛠️ Cechy warsztatu  
- **Interfejs przeglądarkowy**: Pełny warsztat zasilany MkDocs z funkcją wyszukiwania, kopiowania i motywami  
- **Integracja GitHub Codespaces**: Konfiguracja środowiska developerskiego jednym kliknięciem  
- **Ustrukturyzowana ścieżka nauki**: 7-etapowe ćwiczenia z przewodnikiem (łączny czas 3,5 godziny)  
- **Discovery → Deployment → Customization**: Metodologia progresywna  
- **Interaktywne środowisko DevContainer**: Wstępnie skonfigurowane narzędzia i zależności

#### 📚 Struktura warsztatu  
Warsztat realizuje metodologię **Discovery → Deployment → Customization**:

1. **Faza odkrywania** (45 min)  
   - Poznanie szablonów i usług Microsoft Foundry  
   - Zrozumienie wzorców architektury wieloagentowej  
   - Przegląd wymagań i wymogów wdrożenia

2. **Faza wdrożeniowa** (2 godziny)  
   - Praktyczne wdrożenie aplikacji AI z AZD  
   - Konfiguracja usług AI i punktów końcowych Azure  
   - Implementacja wzorców bezpieczeństwa i autoryzacji

3. **Faza dostosowania** (45 min)  
   - Modyfikacja aplikacji pod specyficzne przypadki użycia  
   - Optymalizacja wdrożenia produkcyjnego  
   - Implementacja monitorowania i zarządzania kosztami

#### 🚀 Rozpoczęcie pracy z warsztatem  
```bash
# Opcja 1: GitHub Codespaces (zalecane)
# Kliknij "Code" → "Create codespace on main" w repozytorium

# Opcja 2: Lokalny rozwój
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# Postępuj zgodnie z instrukcjami instalacji w workshop/README.md
```
  
#### 🎯 Efekty nauki z warsztatu  
Po ukończeniu warsztatu uczestnicy:  
- **Wdrożą aplikacje AI do produkcji**: Korzystając z AZD i usług Microsoft Foundry  
- **Opanują architektury wieloagentowe**: Implementacja skoordynowanych rozwiązań AI  
- **Wdrożą najlepsze praktyki bezpieczeństwa**: Konfiguracja uwierzytelniania i kontroli dostępu  
- **Optymalizują wdrożenia na skalę**: Projektowanie kosztowo efektywnych i wydajnych rozwiązań  
- **Rozwiążą problemy wdrożeniowe**: Samodzielne diagnozowanie i naprawianie błędów

#### 📖 Zasoby warsztatowe  
- **🎥 Interaktywny przewodnik**: [Materiały warsztatowe](workshop/README.md) - Środowisko nauki przeglądarkowej  
- **📋 Instrukcje krok po kroku**: [Ćwiczenia prowadzone](../../workshop/docs/instructions) - Szczegółowe przewodniki  
- **🛠️ Laboratorium AI**: [Laboratorium AI](docs/microsoft-foundry/ai-workshop-lab.md) - Ćwiczenia skoncentrowane na AI  
- **💡 Szybki start**: [Przewodnik konfiguracji warsztatu](workshop/README.md#quick-start) - Konfiguracja środowiska

**Idealne dla**: szkoleń korporacyjnych, kursów uniwersyteckich, nauki samodzielnej oraz bootcampów dla programistów.

---

## 📖 Czym jest Azure Developer CLI?

Azure Developer CLI (azd) to interfejs wiersza poleceń skoncentrowany na deweloperze, który przyspiesza proces tworzenia i wdrażania aplikacji na platformie Azure. Oferuje:

- **Wdrożenia oparte na szablonach** – używanie gotowych szablonów dla popularnych wzorców aplikacji  
- **Infrastruktura jako kod** – zarządzanie zasobami Azure za pomocą Bicep lub Terraform  
- **Zintegrowane przepływy pracy** – płynne provisionowanie, wdrażanie i monitorowanie aplikacji  
- **Przyjazne dla dewelopera** – zoptymalizowany dla produktywności i doświadczenia deweloperskiego

### **AZD + Microsoft Foundry: Idealne rozwiązanie dla wdrożeń AI**

**Dlaczego AZD dla rozwiązań AI?** AZD odpowiada na największe wyzwania programistów AI:

- **Szablony gotowe do AI** – prekonfigurowane wzorce dla Azure OpenAI, usług kognitywnych i ML  
- **Bezpieczne wdrożenia AI** – wbudowane wzorce bezpieczeństwa dla usług AI, kluczy API i punktów końcowych modeli  
- **Wzorce produkcyjne AI** – najlepsze praktyki dla skalowalnych i kosztowo efektywnych wdrożeń  
- **Kompleksowe przepływy pracy AI** – od rozwoju modelu do wdrożenia produkcyjnego z odpowiednim monitorowaniem  
- **Optymalizacja kosztów** – inteligentne zarządzanie zasobami i skalowalnością obciążeń AI  
- **Integracja Microsoft Foundry** – płynne połączenie z katalogiem modeli i punktami końcowymi Foundry

---

## 🎯 Biblioteka szablonów i przykładów

### Polecane: Szablony Microsoft Foundry  
**Zacznij tutaj, jeśli wdrażasz aplikacje AI!**

> **Uwaga:** Te szablony ilustrują różne wzorce AI. Niektóre pochodzą z zewnętrznych przykładów Azure Samples, inne są implementacjami lokalnymi.

| Szablon | Rozdział | Stopień trudności | Usługi | Typ |
|----------|---------|------------|----------|------|
| [**Start z czatem AI**](https://github.com/Azure-Samples/get-started-with-ai-chat) | Rozdział 2 | ⭐⭐ | AzureOpenAI + Azure AI Model Inference API + Azure AI Search + Azure Container Apps + Application Insights | Zewnętrzny |
| [**Start z agentami AI**](https://github.com/Azure-Samples/get-started-with-ai-agents) | Rozdział 2 | ⭐⭐ | Azure AI Agent Service + AzureOpenAI + Azure AI Search + Azure Container Apps + Application Insights | Zewnętrzny |
| [**Demo Azure Search + OpenAI**](https://github.com/Azure-Samples/azure-search-openai-demo) | Rozdział 2 | ⭐⭐ | AzureOpenAI + Azure AI Search + App Service + Storage | Zewnętrzny |
| [**Szybki start aplikacji czatu OpenAI**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Rozdział 2 | ⭐ | AzureOpenAI + Container Apps + Application Insights | Zewnętrzny |
| [**Agent OpenAI Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Rozdział 5 | ⭐⭐⭐ | AzureOpenAI + Azure Functions + Prompty | Zewnętrzny |
| [**Contoso Chat RAG**](https://github.com/Azure-Samples/contoso-chat) | Rozdział 8 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Cosmos DB + Container Apps | Zewnętrzny |
| [**Rozwiązanie wieloagentowe dla handlu detalicznego**](examples/retail-scenario.md) | Rozdział 5 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Storage + Container Apps + Cosmos DB | **Lokalny** |

### Polecane: Kompleksowe scenariusze edukacyjne  
**Szablony aplikacji gotowych do produkcji przypisane do rozdziałów nauki**

| Szablon | Rozdział nauki | Stopień trudności | Kluczowa nauka |
|----------|------------------|------------|--------------|
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Rozdział 2 | ⭐ | Podstawowe wzorce wdrożeń AI |
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Rozdział 2 | ⭐⭐ | Implementacja RAG z Azure AI Search |
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | Rozdział 4 | ⭐⭐ | Integracja Document Intelligence |
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Rozdział 5 | ⭐⭐⭐ | Framework agentów oraz wywoływanie funkcji |
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | Rozdział 8 | ⭐⭐⭐ | Orkiestracja AI korporacyjnego |
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | Rozdział 5 | ⭐⭐⭐⭐ | Architektura wieloagentowa z agentami klienta i zapasów |

### Nauka przez przykład - rodzaj przykładów

> **📌 Przykłady lokalne kontra zewnętrzne:**  
> **Przykłady lokalne** (w tym repozytorium) = gotowe do natychmiastowego użycia  
> **Przykłady zewnętrzne** (Azure Samples) = klonowanie z powiązanych repozytoriów

#### Przykłady lokalne (gotowe do użycia)  
- [**Rozwiązanie wieloagentowe dla handlu detalicznego**](examples/retail-scenario.md) - Pełna implementacja produkcyjna z szablonami ARM  
  - Architektura wieloagentowa (agent klienta + agent zapasów)  
  - Kompleksowe monitorowanie i ewaluacja  
  - Wdrożenie jednym kliknięciem przez szablon ARM

#### Przykłady lokalne - aplikacje kontenerowe (rozdziały 2-5)  
**Kompleksowe przykłady wdrożeń kontenerowych w tym repozytorium:**  
- [**Przykłady aplikacji kontenerowych**](examples/container-app/README.md) - Kompletny przewodnik po wdrożeniach kontenerowych  
  - [Proste API Flask](../../examples/container-app/simple-flask-api) - Podstawowe API REST z automatycznym skalowaniem do zera  
  - [Architektura mikroserwisów](../../examples/container-app/microservices) - Produkcyjne wdrożenie wielu usług  
  - Wzorce szybkiego startu, produkcji i zaawansowane  
  - Poradniki dotyczące monitorowania, bezpieczeństwa i optymalizacji kosztów

#### Przykłady zewnętrzne - proste aplikacje (rozdziały 1-2)  
**Sklonuj te repozytoria Azure Samples, aby zacząć:**  
- [Prosta aplikacja webowa - Node.js + MongoDB](https://github.com/Azure-Samples/todo-nodejs-mongo) - Podstawowe wzorce wdrożeniowe  
- [Statyczna strona - React SPA](https://github.com/Azure-Samples/todo-csharp-sql-swa-func) - Wdrożenie statycznej zawartości  
- [Aplikacja kontenerowa - Python Flask](https://github.com/Azure-Samples/container-apps-store-api-microservice) - Wdrożenie REST API

#### Przykłady zewnętrzne - integracja bazy danych (rozdziały 3-4)  
- [Aplikacja z bazą danych - C# + SQL](https://github.com/Azure-Samples/todo-csharp-sql) - Wzorce łączności z bazą danych  
- [Funkcje + Cosmos DB](https://github.com/Azure-Samples/todo-python-mongo-swa-func) - Bezserwerowe przetwarzanie danych

#### Przykłady zewnętrzne - wzorce zaawansowane (rozdziały 4-8)  
- [Java mikroserwisy](https://github.com/Azure-Samples/java-microservices-aca-lab) - Architektury multi-usługowe  
- [Zadania aplikacji kontenerowych](https://github.com/Azure-Samples/container-apps-jobs) - Przetwarzanie w tle  
- [Korporacyjna linia produkcyjna ML](https://github.com/Azure-Samples/mlops-v2) - Produkcyjne wzorce ML

### Kolekcje szablonów zewnętrznych
- [**Oficjalna Galeria Szablonów AZD**](https://azure.github.io/awesome-azd/) - Wyselekcjonowana kolekcja oficjalnych i społecznościowych szablonów
- [**Szablony Azure Developer CLI**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - Dokumentacja szablonów Microsoft Learn
- [**Katalog Przykładów**](examples/README.md) - Lokalne przykłady do nauki z szczegółowymi objaśnieniami

---

## 📚 Zasoby do nauki i odniesienia

### Szybkie odniesienia
- [**Skrócony spis poleceń**](resources/cheat-sheet.md) - Podstawowe komendy azd pogrupowane według rozdziałów
- [**Słownik**](resources/glossary.md) - Terminologia Azure i azd  
- [**FAQ**](resources/faq.md) - Najczęściej zadawane pytania uszeregowane według rozdziałów nauki
- [**Przewodnik do nauki**](resources/study-guide.md) - Kompleksowe ćwiczenia praktyczne

### Warsztaty praktyczne
- [**Laboratorium Warsztatów AI**](docs/microsoft-foundry/ai-workshop-lab.md) - Uczyń swoje rozwiązania AI możliwymi do wdrożenia za pomocą AZD (2-3 godziny)
- [**Interaktywny przewodnik warsztatowy**](workshop/README.md) - Warsztat przeglądarkowy z MkDocs i środowiskiem DevContainer
- [**Strukturalna ścieżka nauki**](../../workshop/docs/instructions) - 7-stopniowe ćwiczenia (Odkrywanie → Wdrożenie → Dostosowanie)
- [**Warsztat AZD dla początkujących**](workshop/README.md) - Kompletny materiał ćwiczeniowy z integracją GitHub Codespaces

### Zewnętrzne zasoby edukacyjne
- Dokumentacja Azure Developer CLI (https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)
- Centrum Architektury Azure (https://learn.microsoft.com/en-us/azure/architecture/)
- Kalkulator cen Azure (https://azure.microsoft.com/pricing/calculator/)
- Status Azure (https://status.azure.com/)

---

## 🔧 Szybki przewodnik rozwiązywania problemów

**Typowe problemy, z jakimi spotykają się początkujący, i natychmiastowe rozwiązania:**

### ❌ "azd: polecenie nie znalezione"

```bash
# Najpierw zainstaluj AZD
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Zweryfikuj instalację
azd version
```

### ❌ "Nie znaleziono subskrypcji" lub "Subskrypcja nie została ustawiona"

```bash
# Wyświetl dostępne subskrypcje
az account list --output table

# Ustaw domyślną subskrypcję
az account set --subscription "<subscription-id-or-name>"

# Ustaw dla środowiska AZD
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Zweryfikuj
az account show
```

### ❌ "Niewystarczający limit" lub "Limit przekroczony"

```bash
# Wypróbuj inny region Azure
azd env set AZURE_LOCATION "westus2"
azd up

# Lub użyj mniejszych SKU podczas tworzenia
# Edytuj infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```

### ❌ "azd up" przerywa działanie w połowie

```bash
# Opcja 1: Wyczyść i spróbuj ponownie
azd down --force --purge
azd up

# Opcja 2: Tylko napraw infrastrukturę
azd provision

# Opcja 3: Sprawdź szczegółowe logi
azd show
azd logs
```

### ❌ "Błąd uwierzytelniania" lub "Token wygasł"

```bash
# Ponownie uwierzytelnij
az logout
az login

azd auth logout
azd auth login

# Zweryfikuj uwierzytelnianie
az account show
```

### ❌ "Zasób już istnieje" lub konflikty nazw

```bash
# AZD generuje unikalne nazwy, ale jeśli wystąpi konflikt:
azd down --force --purge

# Następnie ponów próbę z nowym środowiskiem
azd env new dev-v2
azd up
```

### ❌ Wdrażanie szablonu trwa zbyt długo

**Normalny czas oczekiwania:**
- Prosta aplikacja webowa: 5-10 minut
- Aplikacja z bazą danych: 10-15 minut
- Aplikacje AI: 15-25 minut (prowizjonowanie OpenAI trwa długo)

```bash
# Sprawdź postęp
azd show

# Jeśli utkniesz na >30 minut, sprawdź Portal Azure:
azd monitor
# Szukaj nieudanych wdrożeń
```

### ❌ "Brak uprawnień" lub "Odmowa dostępu"

```bash
# Sprawdź swoją rolę w Azure
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Potrzebujesz co najmniej roli "Współtwórca"
# Poproś administratora Azure o przyznanie:
# - Współtwórca (dla zasobów)
# - Administrator dostępu użytkowników (dla przydziałów ról)
```

### ❌ Nie można znaleźć URL wdrożonej aplikacji

```bash
# Pokaż wszystkie końcówki usług
azd show

# Lub otwórz portal Azure
azd monitor

# Sprawdź konkretną usługę
azd env get-values
# Szukaj zmiennych *_URL
```

### 📚 Pełne zasoby do rozwiązywania problemów

- **Przewodnik po typowych problemach:** [Szczegółowe rozwiązania](docs/troubleshooting/common-issues.md)
- **Problemy specyficzne dla AI:** [Rozwiązywanie problemów AI](docs/troubleshooting/ai-troubleshooting.md)
- **Przewodnik debugowania:** [Debugowanie krok po kroku](docs/troubleshooting/debugging.md)
- **Uzyskaj pomoc:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🔧 Szybki przewodnik rozwiązywania problemów

**Typowe problemy, z jakimi spotykają się początkujący, i natychmiastowe rozwiązania:**

<details>
<summary><strong>❌ "azd: polecenie nie znalezione"</strong></summary>

```bash
# Najpierw zainstaluj AZD
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Zweryfikuj instalację
azd version
```
</details>

<details>
<summary><strong>❌ "Nie znaleziono subskrypcji" lub "Subskrypcja nie została ustawiona"</strong></summary>

```bash
# Wyświetl dostępne subskrypcje
az account list --output table

# Ustaw domyślną subskrypcję
az account set --subscription "<subscription-id-or-name>"

# Ustaw dla środowiska AZD
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Zweryfikuj
az account show
```
</details>

<details>
<summary><strong>❌ "Niewystarczający limit" lub "Limit przekroczony"</strong></summary>

```bash
# Wypróbuj inny region Azure
azd env set AZURE_LOCATION "westus2"
azd up

# Lub użyj mniejszych SKU w fazie rozwoju
# Edytuj infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>

<details>
<summary><strong>❌ "azd up" przerywa działanie w połowie</strong></summary>

```bash
# Opcja 1: Wyczyść i spróbuj ponownie
azd down --force --purge
azd up

# Opcja 2: Napraw tylko infrastrukturę
azd provision

# Opcja 3: Sprawdź szczegółowe logi
azd show
azd logs
```
</details>

<details>
<summary><strong>❌ "Błąd uwierzytelniania" lub "Token wygasł"</strong></summary>

```bash
# Ponownie uwierzytelnij
az logout
az login

azd auth logout
azd auth login

# Zweryfikuj uwierzytelnienie
az account show
```
</details>

<details>
<summary><strong>❌ "Zasób już istnieje" lub konflikty nazw</strong></summary>

```bash
# AZD generuje unikalne nazwy, ale jeśli wystąpi konflikt:
azd down --force --purge

# Następnie spróbuj ponownie z nowym środowiskiem
azd env new dev-v2
azd up
```
</details>

<details>
<summary><strong>❌ Wdrażanie szablonu trwa zbyt długo</strong></summary>

**Normalny czas oczekiwania:**
- Prosta aplikacja webowa: 5-10 minut
- Aplikacja z bazą danych: 10-15 minut
- Aplikacje AI: 15-25 minut (prowizjonowanie OpenAI trwa długo)

```bash
# Sprawdź postęp
azd show

# Jeśli utkniesz na ponad 30 minut, sprawdź Azure Portal:
azd monitor
# Szukaj nieudanych wdrożeń
```
</details>

<details>
<summary><strong>❌ "Brak uprawnień" lub "Odmowa dostępu"</strong></summary>

```bash
# Sprawdź swoją rolę w Azure
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Potrzebujesz co najmniej roli „Współtwórca”
# Poproś administratora Azure o przyznanie:
# - Współtwórca (dla zasobów)
# - Administrator dostępu użytkownika (dla przypisań ról)
```
</details>

<details>
<summary><strong>❌ Nie można znaleźć URL wdrożonej aplikacji</strong></summary>

```bash
# Pokaż wszystkie punkty końcowe usług
azd show

# Lub otwórz portal Azure
azd monitor

# Sprawdź konkretną usługę
azd env get-values
# Szukaj zmiennych *_URL
```
</details>

### 📚 Pełne zasoby do rozwiązywania problemów

- **Przewodnik po typowych problemach:** [Szczegółowe rozwiązania](docs/troubleshooting/common-issues.md)
- **Problemy specyficzne dla AI:** [Rozwiązywanie problemów AI](docs/troubleshooting/ai-troubleshooting.md)
- **Przewodnik debugowania:** [Debugowanie krok po kroku](docs/troubleshooting/debugging.md)
- **Uzyskaj pomoc:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🎓 Ukończenie kursu i certyfikacja

### Śledzenie postępów
Śledź swoje postępy w nauce przez każdy rozdział:

- [ ] **Rozdział 1**: Podstawy i szybki start ✅
- [ ] **Rozdział 2**: Rozwój AI jako pierwszy ✅  
- [ ] **Rozdział 3**: Konfiguracja i uwierzytelnianie ✅
- [ ] **Rozdział 4**: Infrastruktura jako kod i wdrożenie ✅
- [ ] **Rozdział 5**: Rozwiązania Multi-Agent AI ✅
- [ ] **Rozdział 6**: Weryfikacja i planowanie przed wdrożeniem ✅
- [ ] **Rozdział 7**: Rozwiązywanie problemów i debugowanie ✅
- [ ] **Rozdział 8**: Wzorce produkcyjne i korporacyjne ✅

### Weryfikacja nauki
Po ukończeniu każdego rozdziału zweryfikuj swoją wiedzę poprzez:
1. **Ćwiczenie praktyczne**: Ukończ praktyczne wdrożenie z rozdziału
2. **Sprawdzenie wiedzy**: Przejrzyj sekcję FAQ danego rozdziału
3. **Dyskusję społecznościową**: Podziel się doświadczeniami na Azure Discord
4. **Kolejny rozdział**: Przejdź do następnego poziomu zaawansowania

### Korzyści z ukończenia kursu
Po ukończeniu wszystkich rozdziałów będziesz mieć:
- **Doświadczenie produkcyjne**: Wdrożone prawdziwe aplikacje AI na Azure
- **Umiejętności zawodowe**: Gotowość do wdrożenia w środowisku korporacyjnym  
- **Rozpoznanie w społeczności**: Aktywny członek społeczności deweloperów Azure
- **Postęp w karierze**: Pożądane kompetencje AZD i wdrożeń AI

---

## 🤝 Społeczność i wsparcie

### Uzyskaj pomoc i wsparcie
- **Problemy techniczne:** [Zgłaszaj błędy i prośby o funkcje](https://github.com/microsoft/azd-for-beginners/issues)
- **Pytania dotyczące nauki:** [Społeczność Microsoft Azure Discord](https://discord.gg/microsoft-azure) oraz [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **Pomoc specyficzna dla AI:** Dołącz do [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **Dokumentacja:** [Oficjalna dokumentacja Azure Developer CLI](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)

### Wgląd społeczności z Microsoft Foundry Discord

**Ostatnie wyniki ankiety z kanału #Azure:**
- **45%** deweloperów chce używać AZD do zadań AI
- **Główne wyzwania**: Wielousługowe wdrożenia, zarządzanie poświadczeniami, gotowość produkcyjna  
- **Najczęściej żądane**: Szablony AI, przewodniki rozwiązywania problemów, dobre praktyki

**Dołącz do naszej społeczności, aby:**
- Dzielenie się doświadczeniami AZD + AI i uzyskać pomoc
- Uzyskać wcześniejszy dostęp do nowych szablonów AI
- Wspierać najlepsze praktyki wdrażania AI
- Wpływać na rozwój przyszłych funkcji AI + AZD

### Współtworzenie kursu
Serdecznie zapraszamy do współtworzenia! Prosimy o zapoznanie się z naszym [Przewodnikiem współpracy](CONTRIBUTING.md), który zawiera szczegóły dotyczące:
- **Ulepszeń treści:** Doskonalenie istniejących rozdziałów i przykładów
- **Nowych przykładów:** Dodawanie scenariuszy i szablonów z życia wziętych  
- **Tłumaczeń:** Pomoc w utrzymaniu wsparcia wielojęzycznego
- **Zgłoszeń błędów:** Poprawa dokładności i jasności
- **Standardów społeczności:** Przestrzeganie naszych inkluzywnych wytycznych społecznościowych

---

## 📄 Informacje o kursie

### Licencja
Projekt jest udostępniony na licencji MIT - szczegóły w pliku [LICENSE](../../LICENSE).

### Powiązane zasoby Microsoft Learn

Nasz zespół tworzy również inne kompleksowe kursy:

<!-- CO-OP TRANSLATOR OTHER COURSES START -->
### LangChain
[![LangChain4j dla początkujących](https://img.shields.io/badge/LangChain4j%20for%20Beginners-22C55E?style=for-the-badge&&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchain4j-for-beginners)
[![LangChain.js dla początkujących](https://img.shields.io/badge/LangChain.js%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchainjs-for-beginners?WT.mc_id=m365-94501-dwahlin)

---

### Azure / Edge / MCP / Agenci
[![AZD dla początkujących](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Edge AI dla początkujących](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![MCP dla początkujących](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Agenci AI dla początkujących](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Seria Generatywnego AI
[![Generatywne AI dla początkujących](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Generatywne AI (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
[![Generatywne AI (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)
[![Generatywne AI (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---
 
### Podstawy nauki
[![ML dla początkujących](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![Data Science dla początkujących](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![AI dla początkujących](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Cyberbezpieczeństwo dla początkujących](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Tworzenie stron WWW dla początkujących](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![IoT dla początkujących](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![Tworzenie XR dla początkujących](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Seria Copilot
[![Copilot do AI w programowaniu parami](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![Copilot do C#/.NET](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Przygody z Copilotem](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ Nawigacja po kursie

**🚀 Gotowy, aby zacząć naukę?**

**Początkujący**: Zacznij od [Rozdziału 1: Podstawy i szybki start](../..)  
**Twórcy AI**: Przejdź do [Rozdziału 2: Rozwój AI w pierwszej kolejności](../..)  
**Doświadczeni programiści**: Zacznij od [Rozdziału 3: Konfiguracja i uwierzytelnianie](../..)

**Następne kroki**: [Rozpocznij Rozdział 1 - Podstawy AZD](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Zastrzeżenie**:  
Dokument ten został przetłumaczony przy użyciu usługi tłumaczenia AI [Co-op Translator](https://github.com/Azure/co-op-translator). Mimo że dążymy do dokładności, prosimy mieć na uwadze, że automatyczne tłumaczenia mogą zawierać błędy lub niedokładności. Oryginalny dokument w języku źródłowym powinien być uważany za wersję wiążącą. W przypadku informacji krytycznych zalecane jest skorzystanie z profesjonalnego tłumaczenia wykonanego przez człowieka. Nie ponosimy odpowiedzialności za jakiekolwiek nieporozumienia lub błędne interpretacje wynikające z korzystania z tego tłumaczenia.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->