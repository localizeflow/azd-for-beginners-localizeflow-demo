<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T12:28:22+00:00",
  "source_file": "README.md",
  "language_code": "de"
}
-->
> Hinweis: Diese Dokumentation wird kontinuierlich aktualisiert, um die neuesten Änderungen zu berücksichtigen.

> ⚠️ Dieses Repository ist eine Demo, die dazu erstellt wurde,
> eine automatisierte Dokumentationslokalisierung mit Localizeflow zu demonstrieren.
>
> Der Originalinhalt basiert auf
> Microsofts „AZD for Beginners“-Projekt.


# AZD für Anfänger: Eine strukturierte Lernreise

![AZD-for-beginners](../../translated_images/azdbeginners.5527441dd9f74068.de.png) 

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## Erste Schritte mit diesem Kurs

Folgen Sie diesen Schritten, um Ihre AZD-Lernreise zu beginnen:

1. **Forken Sie das Repository**: Klicken Sie auf [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)
2. **Klonen Sie das Repository**: `git clone https://github.com/microsoft/azd-for-beginners.git`
3. **Treten Sie der Community bei**: [Azure Discord Communities](https://discord.com/invite/ByRwuEEgH4) für Expertenunterstützung
4. **Wählen Sie Ihren Lernpfad**: Wählen Sie ein Kapitel unten entsprechend Ihrem Erfahrungsniveau aus

### Mehrsprachige Unterstützung

#### Automatisierte Übersetzungen (immer auf dem neuesten Stand)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabisch](../ar/README.md) | [Bengalisch](../bn/README.md) | [Bulgarisch](../bg/README.md) | [Birmanisch (Myanmar)](../my/README.md) | [Chinesisch (vereinfacht)](../zh/README.md) | [Chinesisch (traditionell, Hongkong)](../hk/README.md) | [Chinesisch (traditionell, Macau)](../mo/README.md) | [Chinesisch (traditionell, Taiwan)](../tw/README.md) | [Kroatisch](../hr/README.md) | [Tschechisch](../cs/README.md) | [Dänisch](../da/README.md) | [Niederländisch](../nl/README.md) | [Estnisch](../et/README.md) | [Finnisch](../fi/README.md) | [Französisch](../fr/README.md) | [Deutsch](./README.md) | [Griechisch](../el/README.md) | [Hebräisch](../he/README.md) | [Hindi](../hi/README.md) | [Ungarisch](../hu/README.md) | [Indonesisch](../id/README.md) | [Italienisch](../it/README.md) | [Japanisch](../ja/README.md) | [Kannada](../kn/README.md) | [Koreanisch](../ko/README.md) | [Litauisch](../lt/README.md) | [Malaiisch](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepalesisch](../ne/README.md) | [Nigerianisches Pidgin](../pcm/README.md) | [Norwegisch](../no/README.md) | [Persisch (Farsi)](../fa/README.md) | [Polnisch](../pl/README.md) | [Portugiesisch (Brasilien)](../br/README.md) | [Portugiesisch (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Rumänisch](../ro/README.md) | [Russisch](../ru/README.md) | [Serbisch (Kyrillisch)](../sr/README.md) | [Slowakisch](../sk/README.md) | [Slowenisch](../sl/README.md) | [Spanisch](../es/README.md) | [Swahili](../sw/README.md) | [Schwedisch](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thailändisch](../th/README.md) | [Türkisch](../tr/README.md) | [Ukrainisch](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamesisch](../vi/README.md)

> **Möchten Sie lieber lokal klonen?**

> Dieses Repository enthält über 50 Sprachübersetzungen, was die Downloadgröße erheblich erhöht. Um ohne Übersetzungen zu klonen, verwenden Sie Sparse Checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Damit erhalten Sie alles, was Sie benötigen, um den Kurs mit einem viel schnelleren Download abzuschließen.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## Kursübersicht

Meistern Sie die Azure Developer CLI (azd) durch strukturierte Kapitel, die für progressives Lernen ausgelegt sind. **Besonderer Fokus auf AI-Anwendungsbereitstellung mit Microsoft Foundry-Integration.**

### Warum dieser Kurs für moderne Entwickler unerlässlich ist

Basierend auf Erkenntnissen der Microsoft Foundry Discord-Community möchten **45 % der Entwickler AZD für AI Workloads verwenden**, stoßen jedoch auf Herausforderungen bei:
- Komplexen Multi-Service AI-Architekturen
- Best Practices für produktionsreife AI-Bereitstellungen  
- Integration und Konfiguration von Azure AI-Diensten
- Kostenoptimierung für AI Workloads
- Fehlerbehebung spezifischer AI-Bereitstellungsprobleme

### Lernziele

Nach Abschluss dieses strukturierten Kurses werden Sie:
- **Grundlagen von AZD beherrschen**: Kernkonzepte, Installation und Konfiguration
- **AI-Anwendungen bereitstellen**: Verwenden Sie AZD mit Microsoft Foundry-Diensten
- **Infrastructure as Code implementieren**: Verwalten Sie Azure-Ressourcen mit Bicep-Vorlagen
- **Fehler bei Bereitstellungen beheben**: Beheben Sie häufige Probleme und Debuggen
- **Für Produktion optimieren**: Sicherheit, Skalierung, Monitoring und Kostenmanagement
- **Multi-Agenten-Lösungen erstellen**: Bereitstellung komplexer AI-Architekturen

## 📚 Lernkapitel

*Wählen Sie Ihren Lernpfad basierend auf Erfahrung und Zielen*

### 🚀 Kapitel 1: Grundlagen & Schnellstart
**Voraussetzungen**: Azure-Abonnement, grundlegende Kommandozeilenkenntnisse  
**Dauer**: 30-45 Minuten  
**Komplexität**: ⭐

#### Was Sie lernen werden
- Verständnis der Grundlagen der Azure Developer CLI
- Installation von AZD auf Ihrer Plattform
- Ihre erste erfolgreiche Bereitstellung

#### Lernressourcen
- **🎯 Einstieg**: [Was ist Azure Developer CLI?](../..)
- **📖 Theorie**: [AZD Grundlagen](docs/getting-started/azd-basics.md) – Kernkonzepte und Terminologie
- **⚙️ Einrichtung**: [Installation & Setup](docs/getting-started/installation.md) – Plattform-spezifische Anleitungen
- **🛠️ Praxis**: [Ihr erstes Projekt](docs/getting-started/first-project.md) – Schritt-für-Schritt-Tutorial
- **📋 Schnellreferenz**: [Befehlsübersicht](resources/cheat-sheet.md)

#### Praktische Übungen
```bash
# Schnelle Installationsüberprüfung
azd version

# Stellen Sie Ihre erste Anwendung bereit
azd init --template todo-nodejs-mongo
azd up
```

**💡 Kapitel-Ergebnis**: Erfolgreiche Bereitstellung einer einfachen Webanwendung auf Azure mit AZD

**✅ Erfolgsvalidierung:**
```bash
# Nach Abschluss von Kapitel 1 sollten Sie in der Lage sein:
azd version              # Zeigt installierte Version an
azd init --template todo-nodejs-mongo  # Initialisiert das Projekt
azd up                  # Stellt auf Azure bereit
azd show                # Zeigt die URL der laufenden App an
# Anwendung öffnet sich im Browser und funktioniert
azd down --force --purge  # Bereinigt Ressourcen
```

**📊 Zeitaufwand:** 30-45 Minuten  
**📈 Fähigkeitsniveau danach:** Kann grundlegende Anwendungen eigenständig bereitstellen

**✅ Erfolgsvalidierung:**
```bash
# Nach Abschluss von Kapitel 1 sollten Sie in der Lage sein:
azd version              # Installierte Version anzeigen
azd init --template todo-nodejs-mongo  # Projekt initialisieren
azd up                  # Bereitstellung in Azure
azd show                # URL der laufenden Anwendung anzeigen
# Anwendung öffnet sich im Browser und funktioniert
azd down --force --purge  # Ressourcen bereinigen
```

**📊 Zeitaufwand:** 30-45 Minuten  
**📈 Fähigkeitsniveau danach:** Kann grundlegende Anwendungen eigenständig bereitstellen

---

### 🤖 Kapitel 2: AI-First Entwicklung (Empfohlen für AI-Entwickler)
**Voraussetzungen**: Kapitel 1 abgeschlossen  
**Dauer**: 1-2 Stunden  
**Komplexität**: ⭐⭐

#### Was Sie lernen werden
- Microsoft Foundry Integration mit AZD
- Bereitstellung AI-gestützter Anwendungen
- Verständnis der AI-Dienstkonfigurationen

#### Lernressourcen
- **🎯 Einstieg**: [Microsoft Foundry Integration](docs/microsoft-foundry/microsoft-foundry-integration.md)
- **📖 Muster**: [AI Modellbereitstellung](docs/microsoft-foundry/ai-model-deployment.md) – AI-Modelle bereitstellen und verwalten
- **🛠️ Workshop**: [AI Workshop Lab](docs/microsoft-foundry/ai-workshop-lab.md) – Machen Sie Ihre AI-Lösungen AZD-bereit
- **🎥 Interaktiver Leitfaden**: [Workshop-Materialien](workshop/README.md) – Browserbasiertes Lernen mit MkDocs * DevContainer-Umgebung
- **📋 Vorlagen**: [Microsoft Foundry Vorlagen](../..)
- **📝 Beispiele**: [AZD Bereitstellungsbeispiele](examples/README.md)

#### Praktische Übungen
```bash
# Stellen Sie Ihre erste KI-Anwendung bereit
azd init --template azure-search-openai-demo
azd up

# Probieren Sie weitere KI-Vorlagen aus
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```

**💡 Kapitel-Ergebnis**: Bereitstellung und Konfiguration einer AI-gestützten Chat-Anwendung mit RAG-Funktionalitäten

**✅ Erfolgsvalidierung:**
```bash
# Nach Kapitel 2 solltest du in der Lage sein:
azd init --template azure-search-openai-demo
azd up
# Die AI-Chat-Oberfläche zu testen
# Fragen zu stellen und KI-gestützte Antworten mit Quellen zu erhalten
# Überprüfen, ob die Suchintegration funktioniert
azd monitor  # Prüfen, ob Application Insights Telemetriedaten anzeigt
azd down --force --purge
```

**📊 Zeitaufwand:** 1-2 Stunden  
**📈 Fähigkeitsniveau danach:** Kann produktionsreife AI-Anwendungen bereitstellen und konfigurieren  
**💰 Kostenbewusstsein:** Verstehen der Entwicklungskosten von $80-150/Monat und Produktionskosten von $300-3500/Monat

#### 💰 Kostenüberlegungen für AI-Bereitstellungen

**Entwicklungsumgebung (geschätzt $80-150/Monat):**
- Azure OpenAI (Pay-as-you-go): $0-50/Monat (abhängig vom Tokenverbrauch)
- AI Search (Basic-Stufe): $75/Monat
- Container Apps (Verbrauch): $0-20/Monat
- Speicher (Standard): $1-5/Monat

**Produktionsumgebung (geschätzt $300-3.500+/Monat):**
- Azure OpenAI (PTU für konsistente Leistung): $3.000+/Monat ODER Pay-as-you-go bei hohem Volumen
- AI Search (Standard-Stufe): $250/Monat
- Container Apps (Dediziert): $50-100/Monat
- Application Insights: $5-50/Monat
- Speicher (Premium): $10-50/Monat

**💡 Tipps zur Kostenoptimierung:**
- Verwenden Sie **Free Tier** Azure OpenAI zum Lernen (50.000 Tokens/Monat inklusive)
- Führen Sie `azd down` aus, um Ressourcen freizugeben, wenn Sie nicht aktiv entwickeln
- Beginnen Sie mit verbrauchsbasierter Abrechnung, upgraden Sie auf PTU nur für Produktion
- Verwenden Sie `azd provision --preview`, um Kosten vor der Bereitstellung zu schätzen
- Aktivieren Sie Auto-Scaling: zahlen Sie nur für tatsächliche Nutzung

**Kostenüberwachung:**
```bash
# Geschätzte monatliche Kosten überprüfen
azd provision --preview

# Tatsächliche Kosten im Azure-Portal überwachen
az consumption budget list --resource-group <your-rg>
```

---

### ⚙️ Kapitel 3: Konfiguration & Authentifizierung
**Voraussetzungen**: Kapitel 1 abgeschlossen  
**Dauer**: 45-60 Minuten  
**Komplexität**: ⭐⭐

#### Was Sie lernen werden
- Umweltkonfiguration und -verwaltung
- Authentifizierungs- und Sicherheitsbest Practices
- Benennung und Organisation von Ressourcen

#### Lernressourcen
- **📖 Konfiguration**: [Konfigurationsanleitung](docs/getting-started/configuration.md) – Environment Setup
- **🔐 Sicherheit**: [Authentifizierungsmuster und Managed Identity](docs/getting-started/authsecurity.md) – Authentifizierungsmuster
- **📝 Beispiele**: [Datenbank-App Beispiel](examples/database-app/README.md) – AZD Datenbankbeispiele

#### Praktische Übungen
- Mehrere Umgebungen konfigurieren (Dev, Staging, Prod)
- Managed Identity Authentifizierung einrichten
- Umgebungspezifische Konfigurationen implementieren

**💡 Kapitel-Ergebnis**: Verwalten mehrerer Umgebungen mit ordnungsgemäßer Authentifizierung und Sicherheit

---

### 🏗️ Kapitel 4: Infrastructure as Code & Bereitstellung
**Voraussetzungen**: Kapitel 1-3 abgeschlossen  
**Dauer**: 1-1,5 Stunden  
**Komplexität**: ⭐⭐⭐

#### Was Sie lernen werden
- Erweiterte Bereitstellungsmuster
- Infrastructure as Code mit Bicep
- Strategien für Ressourcenbereitstellung

#### Lernressourcen
- **📖 Bereitstellung**: [Bereitstellungsanleitung](docs/deployment/deployment-guide.md) – Komplette Workflows
- **🏗️ Provisionierung**: [Ressourcen bereitstellen](docs/deployment/provisioning.md) – Azure Ressourcenverwaltung
- **📝 Beispiele**: [Container App Beispiel](../../examples/container-app) – Containerisierte Bereitstellungen

#### Praktische Übungen
- Eigene Bicep-Vorlagen erstellen
- Multi-Service Anwendungen bereitstellen
- Blue-Green-Bereitstellungsstrategien implementieren

**💡 Kapitel-Ergebnis**: Komplexe Multi-Service-Anwendungen mit benutzerdefinierten Infrastrukturvorlagen bereitstellen

---
### 🎯 Kapitel 5: Multi-Agent KI-Lösungen (Fortgeschritten)  
**Voraussetzungen**: Kapitel 1-2 abgeschlossen  
**Dauer**: 2-3 Stunden  
**Komplexität**: ⭐⭐⭐⭐

#### Was Sie lernen werden
- Multi-Agent Architektur-Muster  
- Agenten-Orchestrierung und -Koordination  
- Produktionsreife KI-Bereitstellungen  

#### Lernressourcen
- **🤖 Vorgestelltes Projekt**: [Retail Multi-Agent Solution](examples/retail-scenario.md) - Vollständige Implementierung  
- **🛠️ ARM-Vorlagen**: [ARM Template Package](../../examples/retail-multiagent-arm-template) - Bereitstellung mit einem Klick  
- **📖 Architektur**: [Multi-agent coordination patterns](/docs/pre-deployment/coordination-patterns.md) - Muster  

#### Praktische Übungen  
```bash
# Implementieren Sie die vollständige Multi-Agenten-Lösung für den Einzelhandel
cd examples/retail-multiagent-arm-template
./deploy.sh

# Erkunden Sie Agentenkonfigurationen
az deployment group show --resource-group <rg-name> --name <deployment-name>
```
  
**💡 Kapitel-Ergebnis**: Produktionstaugliche Multi-Agent-KI-Lösung mit Kunden- und Bestandsagenten bereitstellen und verwalten

---

### 🔍 Kapitel 6: Validierung & Planung vor der Bereitstellung  
**Voraussetzungen**: Kapitel 4 abgeschlossen  
**Dauer**: 1 Stunde  
**Komplexität**: ⭐⭐

#### Was Sie lernen werden  
- Kapazitätsplanung und Ressourcenvalidierung  
- Strategien zur SKU-Auswahl  
- Pre-Flight-Checks und Automatisierung  

#### Lernressourcen  
- **📊 Planung**: [Capacity Planning](docs/pre-deployment/capacity-planning.md) - Ressourcenvalidierung  
- **💰 Auswahl**: [SKU Selection](docs/pre-deployment/sku-selection.md) - Kostenoptimierte Entscheidungen  
- **✅ Validierung**: [Pre-flight Checks](docs/pre-deployment/preflight-checks.md) - Automatisierte Skripte  

#### Praktische Übungen  
- Kapazitätsvalidierungsskripte ausführen  
- SKU-Auswahlen für Kosteneffizienz optimieren  
- Automatisierte Vorbereitungsprüfungen implementieren  

**💡 Kapitel-Ergebnis**: Bereitstellungen vor der Ausführung validieren und optimieren

---

### 🚨 Kapitel 7: Fehlerbehebung & Debugging  
**Voraussetzungen**: Beliebiges Bereitstellungskapitel abgeschlossen  
**Dauer**: 1-1,5 Stunden  
**Komplexität**: ⭐⭐

#### Was Sie lernen werden  
- Systematische Debugging-Methoden  
- Häufige Probleme und Lösungen  
- KI-spezifische Fehlersuche  

#### Lernressourcen  
- **🔧 Häufige Probleme**: [Common Issues](docs/troubleshooting/common-issues.md) - FAQ und Lösungen  
- **🕵️ Debugging**: [Debugging Guide](docs/troubleshooting/debugging.md) - Schritt-für-Schritt-Strategien  
- **🤖 KI-Probleme**: [AI-Specific Troubleshooting](docs/troubleshooting/ai-troubleshooting.md) - KI-Service-Probleme  

#### Praktische Übungen  
- Fehler bei Bereitstellungen diagnostizieren  
- Authentifizierungsprobleme beheben  
- KI-Service-Verbindungsprobleme debuggen  

**💡 Kapitel-Ergebnis**: Häufige Bereitstellungsprobleme eigenständig diagnostizieren und beheben

---

### 🏢 Kapitel 8: Produktions- & Unternehmensmuster  
**Voraussetzungen**: Kapitel 1-4 abgeschlossen  
**Dauer**: 2-3 Stunden  
**Komplexität**: ⭐⭐⭐⭐

#### Was Sie lernen werden  
- Strategien für Produktionsbereitstellungen  
- Sicherheitsmuster für Unternehmen  
- Monitoring und Kostenoptimierung  

#### Lernressourcen  
- **🏭 Produktion**: [Production AI Best Practices](docs/microsoft-foundry/production-ai-practices.md) - Unternehmensmuster  
- **📝 Beispiele**: [Microservices Example](../../examples/microservices) - Komplexe Architekturen  
- **📊 Monitoring**: [Application Insights integration](docs/pre-deployment/application-insights.md) - Überwachung  

#### Praktische Übungen  
- Unternehmenssicherheitsmuster implementieren  
- Umfassendes Monitoring einrichten  
- Produktionsbereitstellung mit Governance durchführen  

**💡 Kapitel-Ergebnis**: Produktiv einsetzbare Unternehmensanwendungen mit vollständigen Produktionsfähigkeiten bereitstellen

---

## 🎓 Workshop-Übersicht: Praxisnahes Lernerlebnis

> **⚠️ WORKSHOP STATUS: Aktive Entwicklung**  
> Die Workshop-Materialien werden derzeit entwickelt und verfeinert. Kernmodule sind funktionsfähig, einige fortgeschrittene Abschnitte unvollständig. Wir arbeiten aktiv an der Fertigstellung aller Inhalte. [Fortschritt verfolgen →](workshop/README.md)

### Interaktive Workshop-Materialien  
**Umfassendes praxisnahes Lernen mit browserbasierten Tools und geführten Übungen**

Unsere Workshop-Materialien bieten ein strukturiertes, interaktives Lernerlebnis, das den oben beschriebenen kapitelbasierten Lehrplan ergänzt. Der Workshop ist sowohl für Selbstlerner als auch für geleitete Kurse konzipiert.

#### 🛠️ Workshop-Funktionen  
- **Browserbasierte Benutzeroberfläche**: Vollständiger MkDocs-basierter Workshop mit Suche, Kopierfunktion und Themenoptionen  
- **GitHub Codespaces-Integration**: Entwicklungssystem mit einem Klick einrichten  
- **Strukturierter Lernpfad**: 7-stufige geführte Übungen (insgesamt 3,5 Stunden)  
- **Entdeckung → Bereitstellung → Anpassung**: Progressive Methodik  
- **Interaktive DevContainer-Umgebung**: Vorgefertigte Tools und Abhängigkeiten  

#### 📚 Workshop-Struktur  
Der Workshop folgt der Methodik **Entdeckung → Bereitstellung → Anpassung**:

1. **Entdeckungsphase** (45 Minuten)  
   - Microsoft Foundry Vorlagen und Dienste erkunden  
   - Multi-Agent Architektur-Muster verstehen  
   - Anforderungen und Voraussetzungen der Bereitstellung prüfen  

2. **Bereitstellungsphase** (2 Stunden)  
   - Praktische Bereitstellung von KI-Anwendungen mit AZD  
   - Azure KI-Dienste und Endpunkte konfigurieren  
   - Sicherheits- und Authentifizierungsmuster implementieren  

3. **Anpassungsphase** (45 Minuten)  
   - Anwendungen für spezifische Anwendungsfälle modifizieren  
   - Produktionsbereitstellung optimieren  
   - Monitoring und Kostenmanagement implementieren  

#### 🚀 Workshop-Start  
```bash
# Option 1: GitHub Codespaces (Empfohlen)
# Klicken Sie im Repository auf „Code“ → „Codespace auf main erstellen“

# Option 2: Lokale Entwicklung
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# Befolgen Sie die Einrichtungshinweise in workshop/README.md
```
  
#### 🎯 Lernziele des Workshops  
Teilnehmende sind nach Abschluss in der Lage:  
- **Produktionsfähige KI-Anwendungen bereitzustellen**: Einsatz von AZD mit Microsoft Foundry-Diensten  
- **Multi-Agent-Architekturen zu meistern**: Koordinierte KI-Agenten-Lösungen implementieren  
- **Sicherheitsbest Practices umzusetzen**: Authentifizierung und Zugriff steuern  
- **Bereitstellungen für Skalierung zu optimieren**: Kosten-effiziente und leistungsfähige Deployments entwerfen  
- **Bereitstellungen zu debuggen**: Häufige Probleme eigenständig lösen  

#### 📖 Workshop-Ressourcen  
- **🎥 Interaktiver Leitfaden**: [Workshop Materials](workshop/README.md) - Browserbasiertes Lernumfeld  
- **📋 Schritt-für-Schritt-Anleitungen**: [Guided Exercises](../../workshop/docs/instructions) - Detaillierte Anleitungen  
- **🛠️ KI-Workshop-Labor**: [AI Workshop Lab](docs/microsoft-foundry/ai-workshop-lab.md) - KI-fokussierte Übungen  
- **💡 Schnellstart**: [Workshop Setup Guide](workshop/README.md#quick-start) - Einrichtung der Umgebung  

**Perfekt für**: Firmenschulungen, Universitätskurse, Selbstlernen und Entwickler-Bootcamps.

---

## 📖 Was ist Azure Developer CLI?

Azure Developer CLI (azd) ist eine entwicklerzentrierte Befehlszeilenschnittstelle, die den Prozess der Erstellung und Bereitstellung von Anwendungen in Azure beschleunigt. Sie bietet:

- **Vorlagenbasierte Bereitstellungen** – Verwenden Sie vorgefertigte Vorlagen für gängige Anwendungsmuster  
- **Infrastructure as Code** – Verwalten Sie Azure-Ressourcen mit Bicep oder Terraform  
- **Integrierte Workflows** – Provisionieren, bereitstellen und überwachen Sie Anwendungen nahtlos  
- **Entwicklerfreundlich** – Optimiert für Produktivität und Nutzererlebnis  

### **AZD + Microsoft Foundry: Perfekt für KI-Bereitstellungen**

**Warum AZD für KI-Lösungen?** AZD adressiert die wichtigsten Herausforderungen von KI-Entwicklern:

- **KI-fertige Vorlagen** – Vorgefertigte Templates für Azure OpenAI, Cognitive Services und ML-Workloads  
- **Sichere KI-Bereitstellungen** – Eingebaute Sicherheitsmuster für KI-Dienste, API-Schlüssel und Modellendpunkte  
- **Produktionsreife KI-Muster** – Best Practices für skalierbare, kosteneffiziente KI-Anwendungen  
- **End-to-End KI-Workflows** – Von der Modellentwicklung bis zur Produktionsbereitstellung mit Überwachung  
- **Kostenoptimierung** – Intelligente Ressourcenallokation und Skalierungsstrategien für KI-Workloads  
- **Microsoft Foundry-Integration** – Nahtlose Verbindung zum Microsoft Foundry Modellkatalog und Endpunkten  

---

## 🎯 Vorlagen & Beispielbibliothek

### Vorgestellt: Microsoft Foundry Vorlagen  
**Starten Sie hier, wenn Sie KI-Anwendungen bereitstellen!**

> **Hinweis:** Diese Vorlagen zeigen verschiedene KI-Muster. Einige stammen von externen Azure Samples, andere sind lokale Implementierungen.

| Vorlage | Kapitel | Komplexität | Dienste | Typ |
|----------|---------|------------|----------|------|
| [**Get started with AI chat**](https://github.com/Azure-Samples/get-started-with-ai-chat) | Kapitel 2 | ⭐⭐ | AzureOpenAI + Azure AI Model Inference API + Azure AI Search + Azure Container Apps + Application Insights | Extern |
| [**Get started with AI agents**](https://github.com/Azure-Samples/get-started-with-ai-agents) | Kapitel 2 | ⭐⭐ | Azure AI Agent Service + AzureOpenAI + Azure AI Search + Azure Container Apps + Application Insights | Extern |
| [**Azure Search + OpenAI Demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Kapitel 2 | ⭐⭐ | AzureOpenAI + Azure AI Search + App Service + Storage | Extern |
| [**OpenAI Chat App Quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Kapitel 2 | ⭐ | AzureOpenAI + Container Apps + Application Insights | Extern |
| [**Agent OpenAI Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Kapitel 5 | ⭐⭐⭐ | AzureOpenAI + Azure Functions + Prompty | Extern |
| [**Contoso Chat RAG**](https://github.com/Azure-Samples/contoso-chat) | Kapitel 8 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Cosmos DB + Container Apps | Extern |
| [**Retail Multi-Agent Solution**](examples/retail-scenario.md) | Kapitel 5 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Storage + Container Apps + Cosmos DB | **Lokal** |

### Vorgestellt: Komplette Lernszenarien  
**Produktionsreife Anwendungsvorlagen zugeordnet zu Lernkapiteln**

| Vorlage | Lernkapitel | Komplexität | Schlüsselelement |
|----------|------------------|------------|--------------|
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Kapitel 2 | ⭐ | Grundlegende KI-Bereitstellungsmuster |
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Kapitel 2 | ⭐⭐ | RAG-Implementierung mit Azure AI Search |
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | Kapitel 4 | ⭐⭐ | Document Intelligence Integration |
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Kapitel 5 | ⭐⭐⭐ | Agent Framework und Funktionsaufrufe |
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | Kapitel 8 | ⭐⭐⭐ | Unternehmens-KI-Orchestrierung |
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | Kapitel 5 | ⭐⭐⭐⭐ | Multi-Agent Architektur mit Kunden- und Inventuragenten |

### Lernen nach Beispieltyp

> **📌 Lokale vs. Externe Beispiele:**  
> **Lokale Beispiele** (in diesem Repository) = Sofort einsatzbereit  
> **Externe Beispiele** (Azure Samples) = Aus verlinkten Repositories klonen  

#### Lokale Beispiele (Sofort einsatzbereit)  
- [**Retail Multi-Agent Solution**](examples/retail-scenario.md) - Vollständige produktionsreife Implementierung mit ARM-Vorlagen  
  - Multi-Agent Architektur (Kunden- + Inventur-Agenten)  
  - Umfassendes Monitoring und Auswertung  
  - Bereitstellung mit einem Klick via ARM-Vorlage  

#### Lokale Beispiele - Container-Anwendungen (Kapitel 2-5)  
**Umfassende Container-Bereitstellungsbeispiele in diesem Repository:**  
- [**Container App Examples**](examples/container-app/README.md) - Vollständiger Leitfaden für containerisierte Deployments  
  - [Simple Flask API](../../examples/container-app/simple-flask-api) - Basis-REST-API mit Scale-to-Zero  
  - [Microservices Architecture](../../examples/container-app/microservices) - Produktionsreife Multi-Service-Bereitstellung  
  - Schnellstart-, Produktions- und erweiterte Bereitstellungsmuster  
  - Überwachung, Sicherheit und Kostenoptimierung  

#### Externe Beispiele - Einfache Anwendungen (Kapitel 1-2)  
**Folgende Azure-Sample-Repositories klonen, um loszulegen:**  
- [Simple Web App - Node.js + MongoDB](https://github.com/Azure-Samples/todo-nodejs-mongo) - Grundlegende Bereitstellungsmuster  
- [Static Website - React SPA](https://github.com/Azure-Samples/todo-csharp-sql-swa-func) - Statische Inhaltsbereitstellung  
- [Container App - Python Flask](https://github.com/Azure-Samples/container-apps-store-api-microservice) - REST API-Bereitstellung  

#### Externe Beispiele - Datenbankintegration (Kapitel 3-4)  
- [Database App - C# + SQL](https://github.com/Azure-Samples/todo-csharp-sql) - Datenbankanbindungsmuster  
- [Functions + Cosmos DB](https://github.com/Azure-Samples/todo-python-mongo-swa-func) - Serverloser Datenworkflow  

#### Externe Beispiele - Erweiterte Muster (Kapitel 4-8)  
- [Java Microservices](https://github.com/Azure-Samples/java-microservices-aca-lab) - Multi-Service-Architekturen  
- [Container Apps Jobs](https://github.com/Azure-Samples/container-apps-jobs) - Hintergrundverarbeitung  
- [Enterprise ML Pipeline](https://github.com/Azure-Samples/mlops-v2) - Produktionsreife ML-Muster  

### Externe Vorlage-Sammlungen  
- [**Offizielle AZD-Vorlagen-Galerie**](https://azure.github.io/awesome-azd/) - Kuratierte Sammlung offizieller und Community-Vorlagen
- [**Azure Developer CLI-Vorlagen**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - Microsoft Learn Vorlagendokumentation
- [**Beispiel-Verzeichnis**](examples/README.md) - Lokale Lernbeispiele mit ausführlichen Erklärungen

---

## 📚 Lernressourcen & Referenzen

### Schnellreferenzen
- [**Befehlsübersicht**](resources/cheat-sheet.md) - Wichtige azd-Befehle nach Kapiteln geordnet
- [**Glossar**](resources/glossary.md) - Azure- und azd-Terminologie  
- [**FAQ**](resources/faq.md) - Häufige Fragen nach Lernkapiteln organisiert
- [**Studienführer**](resources/study-guide.md) - Umfangreiche Übungsaufgaben

### Praktische Workshops
- [**KI-Workshop-Labor**](docs/microsoft-foundry/ai-workshop-lab.md) - Machen Sie Ihre KI-Lösungen AZD-bereit (2–3 Stunden)
- [**Interaktiver Workshop-Leitfaden**](workshop/README.md) - Browserbasierter Workshop mit MkDocs und DevContainer-Umgebung
- [**Strukturierter Lernpfad**](../../workshop/docs/instructions) - 7-stufige geführte Übungen (Entdeckung → Bereitstellung → Anpassung)
- [**AZD Für Anfänger Workshop**](workshop/README.md) - Komplette praktische Workshop-Materialien mit GitHub Codespaces-Integration

### Externe Lernressourcen
- [Azure Developer CLI Dokumentation](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)
- [Azure Architekturzentrum](https://learn.microsoft.com/en-us/azure/architecture/)
- [Azure Preisrechner](https://azure.microsoft.com/pricing/calculator/)
- [Azure Status](https://status.azure.com/)

---

## 🔧 Schnelle Fehlerbehebung

**Häufige Probleme von Anfängern und sofortige Lösungen:**

### ❌ "azd: Befehl nicht gefunden"

```bash
# Installieren Sie zuerst AZD
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Installation überprüfen
azd version
```

### ❌ "Kein Abonnement gefunden" oder "Abonnement nicht gesetzt"

```bash
# Verfügbare Abonnements auflisten
az account list --output table

# Standardabonnement festlegen
az account set --subscription "<subscription-id-or-name>"

# Für AZD-Umgebung festlegen
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Überprüfen
az account show
```

### ❌ "Unzureichendes Kontingent" oder "Kontingent überschritten"

```bash
# Probieren Sie eine andere Azure-Region aus
azd env set AZURE_LOCATION "westus2"
azd up

# Oder verwenden Sie kleinere SKUs in der Entwicklung
# Bearbeiten Sie infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```

### ❌ "azd up" schlägt mitten im Prozess fehl

```bash
# Option 1: Bereinigen und erneut versuchen
azd down --force --purge
azd up

# Option 2: Nur Infrastruktur reparieren
azd provision

# Option 3: Detaillierte Protokolle überprüfen
azd show
azd logs
```

### ❌ "Authentifizierung fehlgeschlagen" oder "Token abgelaufen"

```bash
# Erneut authentifizieren
az logout
az login

azd auth logout
azd auth login

# Authentifizierung überprüfen
az account show
```

### ❌ "Ressource existiert bereits" oder Namenskonflikte

```bash
# AZD generiert eindeutige Namen, aber falls ein Konflikt auftritt:
azd down --force --purge

# Dann erneut mit frischer Umgebung versuchen
azd env new dev-v2
azd up
```

### ❌ Vorlagenbereitstellung dauert zu lange

**Normale Wartezeiten:**
- Einfache Web-App: 5-10 Minuten
- App mit Datenbank: 10-15 Minuten
- KI-Anwendungen: 15-25 Minuten (OpenAI-Provisionierung ist langsam)

```bash
# Fortschritt überprüfen
azd show

# Wenn länger als 30 Minuten festgefahren, Azure-Portal überprüfen:
azd monitor
# Nach fehlgeschlagenen Bereitstellungen suchen
```

### ❌ "Zugriff verweigert" oder "Verboten"

```bash
# Überprüfen Sie Ihre Azure-Rolle
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Sie benötigen mindestens die Rolle "Mitwirkender"
# Bitten Sie Ihren Azure-Administrator um Zuweisung:
# - Mitwirkender (für Ressourcen)
# - Benutzerzugriffsadministrator (für Rollenzuweisungen)
```

### ❌ Kann URL der bereitgestellten Anwendung nicht finden

```bash
# Alle Serviceendpunkte anzeigen
azd show

# Oder Azure-Portal öffnen
azd monitor

# Bestimmten Dienst überprüfen
azd env get-values
# Nach *_URL Variablen suchen
```

### 📚 Vollständige Ressourcen zur Fehlerbehebung

- **Leitfaden zu häufigen Problemen:** [Detaillierte Lösungen](docs/troubleshooting/common-issues.md)
- **KI-spezifische Probleme:** [KI-Fehlerbehebung](docs/troubleshooting/ai-troubleshooting.md)
- **Debugging-Leitfaden:** [Schritt-für-Schritt-Debugging](docs/troubleshooting/debugging.md)
- **Hilfe erhalten:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🔧 Schnelle Fehlerbehebung

**Häufige Probleme von Anfängern und sofortige Lösungen:**

<details>
<summary><strong>❌ "azd: Befehl nicht gefunden"</strong></summary>

```bash
# Installieren Sie zuerst AZD
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Installation überprüfen
azd version
```
</details>

<details>
<summary><strong>❌ "Kein Abonnement gefunden" oder "Abonnement nicht gesetzt"</strong></summary>

```bash
# Verfügbare Abonnements auflisten
az account list --output table

# Standardabonnement festlegen
az account set --subscription "<subscription-id-or-name>"

# Für AZD-Umgebung festlegen
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Überprüfen
az account show
```
</details>

<details>
<summary><strong>❌ "Unzureichendes Kontingent" oder "Kontingent überschritten"</strong></summary>

```bash
# Versuchen Sie eine andere Azure-Region
azd env set AZURE_LOCATION "westus2"
azd up

# Oder verwenden Sie kleinere SKUs in der Entwicklung
# Bearbeiten Sie infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>

<details>
<summary><strong>❌ "azd up" schlägt mitten im Prozess fehl</strong></summary>

```bash
# Option 1: Säubern und erneut versuchen
azd down --force --purge
azd up

# Option 2: Nur Infrastruktur reparieren
azd provision

# Option 3: Detaillierte Protokolle überprüfen
azd show
azd logs
```
</details>

<details>
<summary><strong>❌ "Authentifizierung fehlgeschlagen" oder "Token abgelaufen"</strong></summary>

```bash
# Erneut authentifizieren
az logout
az login

azd auth logout
azd auth login

# Authentifizierung überprüfen
az account show
```
</details>

<details>
<summary><strong>❌ "Ressource existiert bereits" oder Namenskonflikte</strong></summary>

```bash
# AZD generiert eindeutige Namen, aber bei Konflikten:
azd down --force --purge

# Dann erneut mit frischer Umgebung versuchen
azd env new dev-v2
azd up
```
</details>

<details>
<summary><strong>❌ Vorlagenbereitstellung dauert zu lange</strong></summary>

**Normale Wartezeiten:**
- Einfache Web-App: 5-10 Minuten
- App mit Datenbank: 10-15 Minuten
- KI-Anwendungen: 15-25 Minuten (OpenAI-Provisionierung ist langsam)

```bash
# Fortschritt überprüfen
azd show

# Wenn länger als 30 Minuten blockiert, Azure-Portal überprüfen:
azd monitor
# Nach fehlgeschlagenen Bereitstellungen suchen
```
</details>

<details>
<summary><strong>❌ "Zugriff verweigert" oder "Verboten"</strong></summary>

```bash
# Überprüfen Sie Ihre Azure-Rolle
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Sie benötigen mindestens die Rolle "Mitwirkender"
# Bitten Sie Ihren Azure-Administrator um Gewährung:
# - Mitwirkender (für Ressourcen)
# - Benutzerzugriffsadministrator (für Rollenzuweisungen)
```
</details>

<details>
<summary><strong>❌ Kann URL der bereitgestellten Anwendung nicht finden</strong></summary>

```bash
# Alle Dienstendpunkte anzeigen
azd show

# Oder Azure-Portal öffnen
azd monitor

# Bestimmten Dienst prüfen
azd env get-values
# Nach *_URL Variablen suchen
```
</details>

### 📚 Vollständige Ressourcen zur Fehlerbehebung

- **Leitfaden zu häufigen Problemen:** [Detaillierte Lösungen](docs/troubleshooting/common-issues.md)
- **KI-spezifische Probleme:** [KI-Fehlerbehebung](docs/troubleshooting/ai-troubleshooting.md)
- **Debugging-Leitfaden:** [Schritt-für-Schritt-Debugging](docs/troubleshooting/debugging.md)
- **Hilfe erhalten:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🎓 Kursabschluss & Zertifizierung

### Fortschrittsverfolgung
Verfolgen Sie Ihren Lernfortschritt durch jedes Kapitel:

- [ ] **Kapitel 1**: Grundlagen & Schnellstart ✅
- [ ] **Kapitel 2**: KI-First-Entwicklung ✅  
- [ ] **Kapitel 3**: Konfiguration & Authentifizierung ✅
- [ ] **Kapitel 4**: Infrastruktur als Code & Bereitstellung ✅
- [ ] **Kapitel 5**: Multi-Agent-KI-Lösungen ✅
- [ ] **Kapitel 6**: Vorbereitende Validierung & Planung ✅
- [ ] **Kapitel 7**: Fehlerbehebung & Debugging ✅
- [ ] **Kapitel 8**: Produktions- & Enterprise-Muster ✅

### Lernüberprüfung
Nach Abschluss jedes Kapitels überprüfen Sie Ihr Wissen durch:
1. **Praxisübung**: Durchführung der praktischen Bereitstellung des Kapitels
2. **Wissenscheck**: Durchsicht des FAQ-Bereichs zu Ihrem Kapitel
3. **Community-Diskussion**: Teilen Sie Ihre Erfahrungen im Azure Discord
4. **Nächstes Kapitel**: Wechseln Sie zur nächsten Komplexitätsstufe

### Vorteile des Kursabschlusses
Nach Abschluss aller Kapitel haben Sie:
- **Production-Erfahrung**: Echte KI-Anwendungen in Azure bereitgestellt
- **Professionelle Fähigkeiten**: Enterprise-fähige Bereitstellungsfähigkeiten  
- **Community-Anerkennung**: Aktives Mitglied der Azure-Entwickler-Community
- **Karriereförderung**: Gefragte AZD- und KI-Bereitstellungskompetenz

---

## 🤝 Community & Support

### Hilfe & Support erhalten
- **Technische Probleme:** [Fehler melden und Funktionen anfragen](https://github.com/microsoft/azd-for-beginners/issues)
- **Lernfragen:** [Microsoft Azure Discord Community](https://discord.gg/microsoft-azure) und [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **KI-spezifische Hilfe:** Treten Sie dem [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG) bei
- **Dokumentation:** [Offizielle Azure Developer CLI-Dokumentation](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)

### Community-Einblicke vom Microsoft Foundry Discord

**Neueste Umfrageergebnisse aus dem #Azure-Kanal:**
- **45%** der Entwickler möchten AZD für KI-Workloads nutzen
- **Top-Herausforderungen**: Multi-Service-Bereitstellungen, Credential-Management, Produktionsreife  
- **Am meisten gewünscht**: KI-spezifische Vorlagen, Fehlerbehebungshandbücher, Best Practices

**Treten Sie unserer Community bei, um:**
- Ihre AZD + KI-Erfahrungen zu teilen und Hilfe zu erhalten
- Frühzugänge zu neuen KI-Vorlagen zu bekommen
- Zu Best Practices für KI-Bereitstellungen beizutragen
- Die zukünftige Entwicklung von KI + AZD-Funktionen zu beeinflussen

### Beitrag zum Kurs
Beiträge sind willkommen! Bitte lesen Sie unseren [Contributing Guide](CONTRIBUTING.md) für Details zu:
- **Inhaltsverbesserungen**: Bestehende Kapitel und Beispiele verbessern
- **Neue Beispiele**: Realistische Szenarien und Vorlagen hinzufügen  
- **Übersetzungen**: Unterstützung mehrsprachiger Unterstützung
- **Fehlerberichte**: Genauigkeit und Klarheit verbessern
- **Community-Standards**: Unsere inklusiven Community-Richtlinien einhalten

---

## 📄 Kursinformationen

### Lizenz
Dieses Projekt ist unter der MIT-Lizenz lizenziert – Details finden Sie in der [LICENSE](../../LICENSE)-Datei.

### Verwandte Microsoft-Lernressourcen

Unser Team produziert weitere umfassende Lernkurse:

<!-- CO-OP TRANSLATOR OTHER COURSES START -->
### LangChain
[![LangChain4j für Anfänger](https://img.shields.io/badge/LangChain4j%20for%20Beginners-22C55E?style=for-the-badge&&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchain4j-for-beginners)
[![LangChain.js für Anfänger](https://img.shields.io/badge/LangChain.js%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchainjs-for-beginners?WT.mc_id=m365-94501-dwahlin)

---

### Azure / Edge / MCP / Agents
[![AZD für Anfänger](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Edge AI für Anfänger](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![MCP für Anfänger](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)
[![KI-Agenten für Anfänger](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Generative AI-Serie
[![Generative KI für Anfänger](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Generative KI (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
[![Generative KI (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)
[![Generative KI (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---
 
### Kernlerninhalt
[![ML für Anfänger](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![Data Science for Beginners](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![AI for Beginners](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Cybersecurity for Beginners](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Web Dev for Beginners](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![IoT for Beginners](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![XR Development for Beginners](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Copilot-Serie
[![Copilot for AI Paired Programming](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![Copilot for C#/.NET](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Copilot Adventure](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ Kursnavigation

**🚀 Bereit zu starten?**

**Anfänger**: Beginnen Sie mit [Kapitel 1: Grundlagen & Schnellstart](../..)  
**KI-Entwickler**: Springen Sie zu [Kapitel 2: KI-First-Entwicklung](../..)  
**Erfahrene Entwickler**: Starten Sie mit [Kapitel 3: Konfiguration & Authentifizierung](../..)

**Nächste Schritte**: [Beginnen Sie Kapitel 1 - AZD Grundlagen](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Haftungsausschluss**:  
Dieses Dokument wurde mit dem KI-Übersetzungsdienst [Co-op Translator](https://github.com/Azure/co-op-translator) übersetzt. Obwohl wir um Genauigkeit bemüht sind, können automatisierte Übersetzungen Fehler oder Ungenauigkeiten enthalten. Das Originaldokument in seiner Originalsprache ist als maßgebliche Quelle zu betrachten. Für wichtige Informationen wird eine professionelle menschliche Übersetzung empfohlen. Wir übernehmen keine Haftung für Missverständnisse oder Fehlinterpretationen, die durch die Verwendung dieser Übersetzung entstehen.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->