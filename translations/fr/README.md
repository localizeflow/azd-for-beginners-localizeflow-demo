<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T12:22:13+00:00",
  "source_file": "README.md",
  "language_code": "fr"
}
-->
> Note : Cette documentation est continuellement mise à jour pour refléter les dernières modifications.

> ⚠️ Ce dépôt est une démo créée pour présenter  
> la localisation automatisée de documentation avec Localizeflow.  
>
> Le contenu original est basé sur  
> le projet « AZD for Beginners » de Microsoft.


# AZD Pour Débutants : Un Parcours d’Apprentissage Structuré

![AZD-for-beginners](../../translated_images/azdbeginners.5527441dd9f74068.fr.png) 

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## Commencer Avec Ce Cours

Suivez ces étapes pour commencer votre parcours d’apprentissage AZD :

1. **Forkez le Dépôt** : Cliquez sur [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)
2. **Clonez le Dépôt** : `git clone https://github.com/microsoft/azd-for-beginners.git`
3. **Rejoignez la Communauté** : [Communautés Discord Azure](https://discord.com/invite/ByRwuEEgH4) pour un support expert
4. **Choisissez Votre Parcours d’Apprentissage** : Sélectionnez un chapitre ci-dessous correspondant à votre niveau d’expérience

### Support Multilingue

#### Traductions Automatisées (Toujours à Jour)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabe](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgare](../bg/README.md) | [Birman (Myanmar)](../my/README.md) | [Chinois (simplifié)](../zh/README.md) | [Chinois (traditionnel, Hong Kong)](../hk/README.md) | [Chinois (traditionnel, Macao)](../mo/README.md) | [Chinois (traditionnel, Taïwan)](../tw/README.md) | [Croate](../hr/README.md) | [Tchèque](../cs/README.md) | [Danois](../da/README.md) | [Néerlandais](../nl/README.md) | [Estonien](../et/README.md) | [Finnois](../fi/README.md) | [Français](./README.md) | [Allemand](../de/README.md) | [Grec](../el/README.md) | [Hébreu](../he/README.md) | [Hindi](../hi/README.md) | [Hongrois](../hu/README.md) | [Indonésien](../id/README.md) | [Italien](../it/README.md) | [Japonais](../ja/README.md) | [Kannada](../kn/README.md) | [Coréen](../ko/README.md) | [Lituanien](../lt/README.md) | [Malais](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Népalais](../ne/README.md) | [Pidgin nigérian](../pcm/README.md) | [Norvégien](../no/README.md) | [Persan (Farsi)](../fa/README.md) | [Polonais](../pl/README.md) | [Portugais (Brésil)](../br/README.md) | [Portugais (Portugal)](../pt/README.md) | [Pendjabi (Gurmukhi)](../pa/README.md) | [Roumain](../ro/README.md) | [Russe](../ru/README.md) | [Serbe (cyrillique)](../sr/README.md) | [Slovaque](../sk/README.md) | [Slovène](../sl/README.md) | [Espagnol](../es/README.md) | [Swahili](../sw/README.md) | [Suédois](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamoul](../ta/README.md) | [Télougou](../te/README.md) | [Thaï](../th/README.md) | [Turc](../tr/README.md) | [Ukrainien](../uk/README.md) | [Ourdou](../ur/README.md) | [Vietnamien](../vi/README.md)

> **Préférez Cloner Localement ?**

> Ce dépôt inclut plus de 50 traductions de langues, ce qui augmente considérablement la taille du téléchargement. Pour cloner sans les traductions, utilisez le sparse checkout :  
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Cela vous donne tout ce dont vous avez besoin pour compléter le cours avec un téléchargement beaucoup plus rapide.  
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## Aperçu du Cours

Maîtrisez Azure Developer CLI (azd) à travers des chapitres structurés conçus pour un apprentissage progressif. **Focus particulier sur le déploiement d’applications IA avec intégration Microsoft Foundry.**

### Pourquoi Ce Cours est Essentiel pour les Développeurs Modernes

Basé sur les retours de la communauté Discord Microsoft Foundry, **45 % des développeurs veulent utiliser AZD pour les charges de travail IA** mais rencontrent des défis tels que :  
- Architectures IA multi-services complexes  
- Meilleures pratiques de déploiement IA en production  
- Intégration et configuration des services Azure AI  
- Optimisation des coûts pour les charges IA  
- Résolution des problèmes spécifiques au déploiement IA

### Objectifs d’Apprentissage

En suivant ce cours structuré, vous allez :  
- **Maîtriser les Fondamentaux d’AZD** : Concepts de base, installation et configuration  
- **Déployer des Applications IA** : Utiliser AZD avec les services Microsoft Foundry  
- **Mettre en œuvre l’Infrastructure as Code** : Gérer des ressources Azure avec des templates Bicep  
- **Dépanner les Déploiements** : Résoudre les erreurs courantes et déboguer  
- **Optimiser pour la Production** : Sécurité, montée en charge, monitoring et gestion des coûts  
- **Construire des Solutions Multi-Agents** : Déployer des architectures IA complexes

## 📚 Chapitres d’Apprentissage

*Choisissez votre parcours d’apprentissage selon votre niveau d’expérience et vos objectifs*

### 🚀 Chapitre 1 : Fondations & Démarrage Rapide  
**Pré-requis** : Abonnement Azure, connaissances basiques en ligne de commande  
**Durée** : 30-45 minutes  
**Complexité** : ⭐

#### Ce que Vous Apprendrez  
- Comprendre les fondamentaux d’Azure Developer CLI  
- Installer AZD sur votre plateforme  
- Votre premier déploiement réussi

#### Ressources d’Apprentissage  
- **🎯 Commencez Ici** : [Qu’est-ce qu’Azure Developer CLI ?](../..)  
- **📖 Théorie** : [Bases d’AZD](docs/getting-started/azd-basics.md) - Concepts clés et terminologie  
- **⚙️ Installation** : [Installation & Configuration](docs/getting-started/installation.md) - Guides spécifiques par plateforme  
- **🛠️ Pratique** : [Votre Premier Projet](docs/getting-started/first-project.md) - Tutoriel étape par étape  
- **📋 Référence Rapide** : [Cheat Sheet des Commandes](resources/cheat-sheet.md)

#### Exercices Pratiques  
```bash
# Vérification rapide de l'installation
azd version

# Déployez votre première application
azd init --template todo-nodejs-mongo
azd up
```
  
**💡 Résultat du Chapitre** : Déployer avec succès une application web simple sur Azure avec AZD

**✅ Validation du Succès :**  
```bash
# Après avoir terminé le chapitre 1, vous devriez être capable de :
azd version              # Affiche la version installée
azd init --template todo-nodejs-mongo  # Initialise le projet
azd up                  # Déploie sur Azure
azd show                # Affiche l'URL de l'application en cours d'exécution
# L'application s'ouvre dans le navigateur et fonctionne
azd down --force --purge  # Nettoie les ressources
```
  
**📊 Temps Investi :** 30-45 minutes  
**📈 Niveau Après :** Peut déployer des applications basiques de manière autonome

**✅ Validation du Succès :**  
```bash
# Après avoir terminé le Chapitre 1, vous devriez être capable de :
azd version              # Affiche la version installée
azd init --template todo-nodejs-mongo  # Initialise le projet
azd up                  # Déploie sur Azure
azd show                # Affiche l'URL de l'application en cours d'exécution
# L'application s'ouvre dans le navigateur et fonctionne
azd down --force --purge  # Nettoie les ressources
```
  
**📊 Temps Investi :** 30-45 minutes  
**📈 Niveau Après :** Peut déployer des applications basiques de manière autonome

---

### 🤖 Chapitre 2 : Développement AI-First (Recommandé pour les Développeurs IA)  
**Pré-requis** : Chapitre 1 terminé  
**Durée** : 1-2 heures  
**Complexité** : ⭐⭐

#### Ce que Vous Apprendrez  
- Intégration Microsoft Foundry avec AZD  
- Déploiement d’applications alimentées par l’IA  
- Comprendre les configurations des services IA

#### Ressources d’Apprentissage  
- **🎯 Commencez Ici** : [Intégration Microsoft Foundry](docs/microsoft-foundry/microsoft-foundry-integration.md)  
- **📖 Modèles** : [Déploiement de Modèles IA](docs/microsoft-foundry/ai-model-deployment.md) - Déployer et gérer les modèles IA  
- **🛠️ Atelier** : [Lab Atelier IA](docs/microsoft-foundry/ai-workshop-lab.md) - Préparez vos solutions IA pour AZD  
- **🎥 Guide Interactif** : [Matériel de l’Atelier](workshop/README.md) - Apprentissage en navigateur avec MkDocs * Environnement DevContainer  
- **📋 Modèles** : [Templates Microsoft Foundry](../..)  
- **📝 Exemples** : [Exemples de Déploiement AZD](examples/README.md)

#### Exercices Pratiques  
```bash
# Déployez votre première application d'IA
azd init --template azure-search-openai-demo
azd up

# Essayez des modèles d'IA supplémentaires
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```
  
**💡 Résultat du Chapitre** : Déployer et configurer une application de chat IA avec capacités RAG

**✅ Validation du Succès :**  
```bash
# Après le chapitre 2, vous devriez être capable de :
azd init --template azure-search-openai-demo
azd up
# Tester l'interface de chat IA
# Poser des questions et obtenir des réponses alimentées par l'IA avec des sources
# Vérifier que l'intégration de la recherche fonctionne
azd monitor  # Vérifier que Application Insights affiche la télémétrie
azd down --force --purge
```
  
**📊 Temps Investi :** 1-2 heures  
**📈 Niveau Après :** Peut déployer et configurer des applications IA prêtes pour la production  
**💰 Sensibilisation aux Coûts :** Comprendre les coûts de dev $80-150/mois, coûts production $300-3500/mois

#### 💰 Considérations de Coût pour les Déploiements IA

**Environnement de Développement (Estimation $80-150/mois) :**  
- Azure OpenAI (Pay-as-you-go) : $0-50/mois (selon usage de tokens)  
- AI Search (niveau basique) : $75/mois  
- Container Apps (Consommation) : $0-20/mois  
- Stockage (Standard) : $1-5/mois

**Environnement Production (Estimation $300-3,500+/mois) :**  
- Azure OpenAI (PTU pour performance constante) : $3,000+/mois OU Pay-as-you-go avec volume élevé  
- AI Search (niveau standard) : $250/mois  
- Container Apps (Dédié) : $50-100/mois  
- Application Insights : $5-50/mois  
- Stockage (Premium) : $10-50/mois

**💡 Conseils d’Optimisation des Coûts :**  
- Utilisez la **version gratuite** Azure OpenAI pour apprendre (50 000 tokens/mois inclus)  
- Exécutez `azd down` pour désallouer les ressources quand vous ne développez pas activement  
- Débutez en mode facturation à la consommation, passez au PTU uniquement en production  
- Utilisez `azd provision --preview` pour estimer les coûts avant déploiement  
- Activez l’auto-scaling : ne payez que pour l’usage réel

**Suivi des Coûts :**  
```bash
# Vérifier les coûts mensuels estimés
azd provision --preview

# Surveiller les coûts réels dans le portail Azure
az consumption budget list --resource-group <your-rg>
```

---

### ⚙️ Chapitre 3 : Configuration & Authentification  
**Pré-requis** : Chapitre 1 terminé  
**Durée** : 45-60 minutes  
**Complexité** : ⭐⭐

#### Ce que Vous Apprendrez  
- Configuration et gestion des environnements  
- Authentification et meilleures pratiques de sécurité  
- Nommage et organisation des ressources

#### Ressources d’Apprentissage  
- **📖 Configuration** : [Guide de Configuration](docs/getting-started/configuration.md) - Mise en place des environnements  
- **🔐 Sécurité** : [Schémas d’authentification et identité gérée](docs/getting-started/authsecurity.md) - Modèles d’authentification  
- **📝 Exemples** : [Exemple d’application base de données](examples/database-app/README.md) - Exemples AZD base de données

#### Exercices Pratiques  
- Configurer plusieurs environnements (dev, staging, prod)  
- Mettre en place l’authentification par identité gérée  
- Implémenter des configurations spécifiques à chaque environnement

**💡 Résultat du Chapitre** : Gérer plusieurs environnements avec authentification et sécurité appropriées

---

### 🏗️ Chapitre 4 : Infrastructure as Code & Déploiement  
**Pré-requis** : Chapitres 1-3 terminés  
**Durée** : 1-1,5 heure  
**Complexité** : ⭐⭐⭐

#### Ce que Vous Apprendrez  
- Modèles avancés de déploiement  
- Infrastructure as Code avec Bicep  
- Stratégies de provisionnement des ressources

#### Ressources d’Apprentissage  
- **📖 Déploiement** : [Guide de Déploiement](docs/deployment/deployment-guide.md) - Workflows complets  
- **🏗️ Provisionnement** : [Provisionnement des ressources](docs/deployment/provisioning.md) - Gestion des ressources Azure  
- **📝 Exemples** : [Exemple Container App](../../examples/container-app) - Déploiements conteneurisés

#### Exercices Pratiques  
- Créer des templates Bicep personnalisés  
- Déployer des applications multi-services  
- Mettre en œuvre des stratégies de déploiement blue-green

**💡 Résultat du Chapitre** : Déployer des applications multi-services complexes en utilisant des templates d’infrastructure personnalisés

---
### 🎯 Chapitre 5 : Solutions d’IA Multi-Agent (Avancé)
**Prérequis** : Chapitres 1-2 complétés  
**Durée** : 2-3 heures  
**Complexité** : ⭐⭐⭐⭐

#### Ce que vous apprendrez
- Modèles d’architecture multi-agent
- Orchestration et coordination des agents
- Déploiements d’IA prêts pour la production

#### Ressources pédagogiques
- **🤖 Projet en vedette** : [Solution Multi-Agent Retail](examples/retail-scenario.md) - Implémentation complète
- **🛠️ Modèles ARM** : [Package de modèle ARM](../../examples/retail-multiagent-arm-template) - Déploiement en un clic
- **📖 Architecture** : [Modèles de coordination multi-agent](/docs/pre-deployment/coordination-patterns.md) - Modèles

#### Exercices pratiques
```bash
# Déployer la solution complète multi-agent pour le commerce de détail
cd examples/retail-multiagent-arm-template
./deploy.sh

# Explorer les configurations des agents
az deployment group show --resource-group <rg-name> --name <deployment-name>
```

**💡 Résultat du chapitre** : Déployer et gérer une solution IA multi-agent prête pour la production avec des agents Clients et Inventaire

---

### 🔍 Chapitre 6 : Validation & Planification Avant Déploiement
**Prérequis** : Chapitre 4 complété  
**Durée** : 1 heure  
**Complexité** : ⭐⭐

#### Ce que vous apprendrez
- Planification des capacités et validation des ressources
- Stratégies de sélection des SKU
- Vérifications préalables et automatisation

#### Ressources pédagogiques
- **📊 Planification** : [Planification des capacités](docs/pre-deployment/capacity-planning.md) - Validation des ressources
- **💰 Sélection** : [Sélection des SKU](docs/pre-deployment/sku-selection.md) - Choix économiques
- **✅ Validation** : [Vérifications préalables](docs/pre-deployment/preflight-checks.md) - Scripts automatisés

#### Exercices pratiques
- Exécuter les scripts de validation des capacités
- Optimiser la sélection des SKU pour le coût
- Mettre en œuvre des vérifications automatisées avant déploiement

**💡 Résultat du chapitre** : Valider et optimiser les déploiements avant exécution

---

### 🚨 Chapitre 7 : Dépannage & Debugging
**Prérequis** : Un chapitre de déploiement complété  
**Durée** : 1-1,5 heures  
**Complexité** : ⭐⭐

#### Ce que vous apprendrez
- Approches systématiques de débogage
- Problèmes courants et solutions
- Dépannage spécifique à l’IA

#### Ressources pédagogiques
- **🔧 Problèmes courants** : [Problèmes courants](docs/troubleshooting/common-issues.md) - FAQ et solutions
- **🕵️ Débogage** : [Guide de débogage](docs/troubleshooting/debugging.md) - Stratégies pas à pas
- **🤖 Problèmes IA** : [Dépannage spécifique à l’IA](docs/troubleshooting/ai-troubleshooting.md) - Problèmes des services IA

#### Exercices pratiques
- Diagnostiquer les échecs de déploiement
- Résoudre les problèmes d’authentification
- Déboguer la connectivité aux services IA

**💡 Résultat du chapitre** : Diagnostiquer et résoudre de manière autonome les problèmes courants de déploiement

---

### 🏢 Chapitre 8 : Modèles de Production & Entreprise
**Prérequis** : Chapitres 1-4 complétés  
**Durée** : 2-3 heures  
**Complexité** : ⭐⭐⭐⭐

#### Ce que vous apprendrez
- Stratégies de déploiement en production
- Modèles de sécurité en entreprise
- Supervision et optimisation des coûts

#### Ressources pédagogiques
- **🏭 Production** : [Bonnes pratiques IA en production](docs/microsoft-foundry/production-ai-practices.md) - Modèles entreprise
- **📝 Exemples** : [Exemple Microservices](../../examples/microservices) - Architectures complexes
- **📊 Supervision** : [Intégration Application Insights](docs/pre-deployment/application-insights.md) - Supervision

#### Exercices pratiques
- Mettre en œuvre des modèles de sécurité entreprise
- Configurer une supervision complète
- Déployer en production avec une gouvernance adéquate

**💡 Résultat du chapitre** : Déployer des applications prêtes pour l’entreprise avec toutes les capacités de production

---

## 🎓 Aperçu de l’atelier : Expérience d’apprentissage pratique

> **⚠️ ÉTAT DE L’ATELIER : Développement actif**  
> Les supports d’atelier sont en cours de développement et d’affinement. Les modules principaux sont fonctionnels, mais certaines sections avancées sont incomplètes. Nous travaillons activement pour compléter tout le contenu. [Suivre le progrès →](workshop/README.md)

### Matériel interactif de l’atelier
**Apprentissage pratique complet avec outils basés sur navigateur et exercices guidés**

Nos supports d’atelier offrent une expérience d’apprentissage structurée et interactive qui complète le cursus par chapitre ci-dessus. L’atelier est conçu pour l’auto-apprentissage et les sessions avec formateur.

#### 🛠️ Fonctionnalités de l’atelier
- **Interface basée sur navigateur** : Atelier complet propulsé par MkDocs avec recherche, copier et thèmes
- **Intégration GitHub Codespaces** : Configuration de l’environnement de développement en un clic
- **Parcours d’apprentissage structuré** : Exercices guidés en 7 étapes (3,5 heures au total)
- **Découverte → Déploiement → Personnalisation** : Méthodologie progressive
- **Environnement DevContainer interactif** : Outils et dépendances préconfigurés

#### 📚 Structure de l’atelier
L’atelier suit une méthodologie **Découverte → Déploiement → Personnalisation** :

1. **Phase de Découverte** (45 min)
   - Explorer les modèles et services Microsoft Foundry
   - Comprendre les modèles d’architecture multi-agent
   - Examiner les exigences et prérequis de déploiement

2. **Phase de Déploiement** (2 heures)
   - Déploiement pratique d’applications IA avec AZD
   - Configurer les services Azure AI et endpoints
   - Implémenter les modèles de sécurité et d’authentification

3. **Phase de Personnalisation** (45 min)
   - Modifier les applications pour cas d’usage spécifiques
   - Optimiser pour le déploiement en production
   - Mettre en place la supervision et gestion des coûts

#### 🚀 Démarrer avec l’atelier
```bash
# Option 1 : GitHub Codespaces (Recommandé)
# Cliquez sur "Code" → "Créer un codespace sur main" dans le dépôt

# Option 2 : Développement local
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# Suivez les instructions d'installation dans workshop/README.md
```

#### 🎯 Résultats d’apprentissage de l’atelier
En complétant l’atelier, les participants seront capables de :
- **Déployer des applications IA en production** : Utiliser AZD avec les services Microsoft Foundry
- **Maîtriser les architectures multi-agent** : Implémenter des solutions coordonnées d’agents IA
- **Mettre en œuvre les meilleures pratiques de sécurité** : Configurer authentification et contrôle d’accès
- **Optimiser pour l’échelle** : Concevoir des déploiements performants et économiques
- **Dépanner les déploiements** : Résoudre les problèmes courants de façon autonome

#### 📖 Ressources de l’atelier
- **🎥 Guide interactif** : [Matériel d’atelier](workshop/README.md) - Environnement d’apprentissage basé sur navigateur
- **📋 Instructions détaillées** : [Exercices guidés](../../workshop/docs/instructions) - Pas à pas approfondi
- **🛠️ Laboratoire IA** : [Laboratoire IA](docs/microsoft-foundry/ai-workshop-lab.md) - Exercices orientés IA
- **💡 Démarrage rapide** : [Guide d’installation atelier](workshop/README.md#quick-start) - Configuration de l’environnement

**Parfait pour** : formation en entreprise, cours universitaires, apprentissage autonome, bootcamps développeurs.

---

## 📖 Qu’est-ce que Azure Developer CLI ?

Azure Developer CLI (azd) est une interface en ligne de commande centrée développeur qui accélère la construction et le déploiement d’applications sur Azure. Il offre :

- **Déploiements basés sur modèles** – Utilisation de modèles préexistants pour des scénarios applicatifs courants
- **Infrastructure en tant que Code** – Gestion des ressources Azure via Bicep ou Terraform  
- **Flux de travail intégrés** – Provisionnement, déploiement et supervision fluide des applications
- **Convivialité développeur** – Optimisé pour la productivité et l’expérience développeur

### **AZD + Microsoft Foundry : Parfait pour les déploiements IA**

**Pourquoi AZD pour les solutions IA ?** AZD adresse les principaux défis des développeurs IA :

- **Modèles prêts pour l’IA** – Modèles préconfigurés pour Azure OpenAI, Cognitive Services et charges ML
- **Déploiements IA sécurisés** – Modèles de sécurité intégrés pour services IA, clés API et endpoints de modèles  
- **Modèles IA en production** – Bonnes pratiques pour des déploiements IA évolutifs et économiques
- **Flux IA de bout en bout** – Du développement du modèle au déploiement en production avec supervision adaptée
- **Optimisation des coûts** – Allocation et mise à l’échelle intelligente des ressources IA
- **Intégration Microsoft Foundry** – Connexion transparente au catalogue et endpoints Microsoft Foundry

---

## 🎯 Bibliothèque de modèles et exemples

### En vedette : Modèles Microsoft Foundry
**Commencez ici si vous déployez des applications IA !**

> **Note :** Ces modèles illustrent divers modèles IA. Certains sont des exemples externes Azure Samples, d’autres des implémentations locales.

| Modèle | Chapitre | Complexité | Services | Type |
|--------|----------|------------|----------|------|
| [**Get started with AI chat**](https://github.com/Azure-Samples/get-started-with-ai-chat) | Chapitre 2 | ⭐⭐ | AzureOpenAI + Azure AI Model Inference API + Azure AI Search + Azure Container Apps + Application Insights | Externe |
| [**Get started with AI agents**](https://github.com/Azure-Samples/get-started-with-ai-agents) | Chapitre 2 | ⭐⭐ | Azure AI Agent Service + AzureOpenAI + Azure AI Search + Azure Container Apps + Application Insights| Externe |
| [**Azure Search + OpenAI Demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Chapitre 2 | ⭐⭐ | AzureOpenAI + Azure AI Search + App Service + Storage | Externe |
| [**OpenAI Chat App Quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Chapitre 2 | ⭐ | AzureOpenAI + Container Apps + Application Insights | Externe |
| [**Agent OpenAI Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Chapitre 5 | ⭐⭐⭐ | AzureOpenAI + Azure Functions + Prompty | Externe |
| [**Contoso Chat RAG**](https://github.com/Azure-Samples/contoso-chat) | Chapitre 8 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Cosmos DB + Container Apps | Externe |
| [**Retail Multi-Agent Solution**](examples/retail-scenario.md) | Chapitre 5 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Storage + Container Apps + Cosmos DB | **Local** |

### En vedette : Scénarios d’apprentissage complets
**Modèles d'applications production mappés aux chapitres d’apprentissage**

| Modèle | Chapitre d’apprentissage | Complexité | Apprentissage clé |
|--------|----------------------------|------------|-------------------|
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Chapitre 2 | ⭐ | Modèles de déploiement IA de base |
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Chapitre 2 | ⭐⭐ | Implémentation RAG avec Azure AI Search |
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | Chapitre 4 | ⭐⭐ | Intégration Document Intelligence |
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Chapitre 5 | ⭐⭐⭐ | Cadre d’agents et appels de fonctions |
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | Chapitre 8 | ⭐⭐⭐ | Orchestration IA entreprise |
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | Chapitre 5 | ⭐⭐⭐⭐ | Architecture multi-agent avec agents Client et Inventaire |

### Apprentissage par type d’exemple

> **📌 Exemples locaux vs externes :**  
> **Exemples locaux** (dans ce dépôt) = Prêts à l’usage immédiat  
> **Exemples externes** (Azure Samples) = Clonables depuis les dépôts liés

#### Exemples locaux (prêts à l’usage)
- [**Solution Multi-Agent Retail**](examples/retail-scenario.md) - Implémentation complète prête pour la production avec modèles ARM
  - Architecture multi-agent (agents Clients + Inventaire)
  - Supervision et évaluation complètes
  - Déploiement en un clic via modèle ARM

#### Exemples locaux - Applications conteneurisées (Chapitres 2-5)
**Exemples complets de déploiement conteneur dans ce dépôt :**
- [**Exemples Container App**](examples/container-app/README.md) - Guide complet des déploiements conteneurisés
  - [API Flask simple](../../examples/container-app/simple-flask-api) - API REST basique avec scale-to-zero
  - [Architecture Microservices](../../examples/container-app/microservices) - Déploiement multi-service prêt pour production
  - Modèles Début rapide, Production et Avancé
  - Conseils pour supervision, sécurité et optimisation des coûts

#### Exemples externes - Applications simples (Chapitres 1-2)
**Cloner ces dépôts Azure Samples pour démarrer :**
- [Application Web Simple - Node.js + MongoDB](https://github.com/Azure-Samples/todo-nodejs-mongo) - Modèles de déploiement basiques
- [Site statique - SPA React](https://github.com/Azure-Samples/todo-csharp-sql-swa-func) - Déploiement contenu statique
- [Container App - Python Flask](https://github.com/Azure-Samples/container-apps-store-api-microservice) - Déploiement API REST

#### Exemples externes - Intégration base de données (Chapitres 3-4)  
- [Application BDD - C# + SQL](https://github.com/Azure-Samples/todo-csharp-sql) - Modèles de connectivité base
- [Functions + Cosmos DB](https://github.com/Azure-Samples/todo-python-mongo-swa-func) - Workflow serverless

#### Exemples externes - Modèles avancés (Chapitres 4-8)
- [Microservices Java](https://github.com/Azure-Samples/java-microservices-aca-lab) - Architectures multi-service
- [Container Apps Jobs](https://github.com/Azure-Samples/container-apps-jobs) - Traitement en tâche de fond  
- [Pipeline ML Entreprise](https://github.com/Azure-Samples/mlops-v2) - Modèles ML prêts pour production

### Collections de modèles externes
- [**Galerie Officielle des Modèles AZD**](https://azure.github.io/awesome-azd/) - Collection sélectionnée de modèles officiels et communautaires  
- [**Modèles Azure Developer CLI**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - Documentation des modèles Microsoft Learn  
- [**Répertoire d’Exemples**](examples/README.md) - Exemples d’apprentissage locaux avec explications détaillées  

---

## 📚 Ressources d’Apprentissage & Références

### Références Rapides  
- [**Fiche de Commandes**](resources/cheat-sheet.md) - Commandes azd essentielles organisées par chapitre  
- [**Glossaire**](resources/glossary.md) - Terminologie Azure et azd  
- [**FAQ**](resources/faq.md) - Questions fréquentes organisées par chapitre d’apprentissage  
- [**Guide d’Étude**](resources/study-guide.md) - Exercices pratiques complets  

### Ateliers Pratiques  
- [**Atelier AI**](docs/microsoft-foundry/ai-workshop-lab.md) - Rendez vos solutions IA déployables avec AZD (2-3 heures)  
- [**Guide d’Atelier Interactif**](workshop/README.md) - Atelier en navigateur avec MkDocs et environnement DevContainer  
- [**Parcours d’Apprentissage Structuré**](../../workshop/docs/instructions) - Exercices guidés en 7 étapes (Découverte → Déploiement → Personnalisation)  
- [**Atelier AZD pour Débutants**](workshop/README.md) - Matériel complet d’atelier pratique avec intégration GitHub Codespaces  

### Ressources d’Apprentissage Externes  
- Documentation Azure Developer CLI ([Azure Developer CLI Documentation](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/))  
- Centre d’Architecture Azure ([Azure Architecture Center](https://learn.microsoft.com/en-us/azure/architecture/))  
- Calculateur de Prix Azure ([Azure Pricing Calculator](https://azure.microsoft.com/pricing/calculator/))  
- Statut Azure ([Azure Status](https://status.azure.com/))  

---

## 🔧 Guide Rapide de Résolution des Problèmes

**Problèmes courants rencontrés par les débutants et solutions immédiates :**

### ❌ "azd : commande introuvable"

```bash
# Installer AZD d'abord
# Windows (PowerShell) :
winget install microsoft.azd

# macOS :
brew tap azure/azd && brew install azd

# Linux :
curl -fsSL https://aka.ms/install-azd.sh | bash

# Vérifier l'installation
azd version
```
  
### ❌ "Aucun abonnement trouvé" ou "Abonnement non défini"

```bash
# Lister les abonnements disponibles
az account list --output table

# Définir l'abonnement par défaut
az account set --subscription "<subscription-id-or-name>"

# Définir pour l'environnement AZD
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Vérifier
az account show
```
  
### ❌ "Quota insuffisant" ou "Quota dépassé"

```bash
# Essayez une autre région Azure
azd env set AZURE_LOCATION "westus2"
azd up

# Ou utilisez des SKU plus petits en développement
# Modifiez infra/main.parameters.json :
{
  "sku": "B1"  // Instead of "P1V2"
}
```
  
### ❌ Échec de "azd up" à mi-chemin

```bash
# Option 1 : Nettoyer et réessayer
azd down --force --purge
azd up

# Option 2 : Simplement réparer l'infrastructure
azd provision

# Option 3 : Vérifier les journaux détaillés
azd show
azd logs
```
  
### ❌ "Échec d’authentification" ou "Jeton expiré"

```bash
# Ré-authentifier
az logout
az login

azd auth logout
azd auth login

# Vérifier l'authentification
az account show
```
  
### ❌ "Ressource déjà existante" ou conflits de noms

```bash
# AZD génère des noms uniques, mais en cas de conflit :
azd down --force --purge

# Puis réessayez avec un environnement neuf
azd env new dev-v2
azd up
```
  
### ❌ Le déploiement du modèle prend trop de temps

**Temps d’attente normaux :**  
- Application web simple : 5-10 minutes  
- Application avec base de données : 10-15 minutes  
- Applications IA : 15-25 minutes (le provisionnement OpenAI est lent)  

```bash
# Vérifier les progrès
azd show

# Si bloqué >30 minutes, vérifiez le portail Azure :
azd monitor
# Recherchez les déploiements échoués
```
  
### ❌ "Permission refusée" ou "Interdit"

```bash
# Vérifiez votre rôle Azure
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Vous avez besoin d'au moins le rôle "Contributeur"
# Demandez à votre administrateur Azure d'accorder :
# - Contributeur (pour les ressources)
# - Administrateur de l'accès utilisateur (pour les attributions de rôle)
```
  
### ❌ Impossible de trouver l’URL de l’application déployée

```bash
# Afficher tous les points de terminaison de service
azd show

# Ou ouvrir le portail Azure
azd monitor

# Vérifier un service spécifique
azd env get-values
# Rechercher les variables *_URL
```
  
### 📚 Ressources Complètes de Résolution des Problèmes

- **Guide des problèmes courants :** [Solutions Détaillées](docs/troubleshooting/common-issues.md)  
- **Problèmes spécifiques à l’IA :** [Résolution IA](docs/troubleshooting/ai-troubleshooting.md)  
- **Guide de débogage :** [Débogage étape par étape](docs/troubleshooting/debugging.md)  
- **Obtenez de l’aide :** [Discord Azure](https://discord.gg/microsoft-azure) #azure-developer-cli  

---

## 🔧 Guide Rapide de Résolution des Problèmes

**Problèmes courants rencontrés par les débutants et solutions immédiates :**

<details>
<summary><strong>❌ "azd : commande introuvable"</strong></summary>

```bash
# Installer d'abord AZD
# Windows (PowerShell) :
winget install microsoft.azd

# macOS :
brew tap azure/azd && brew install azd

# Linux :
curl -fsSL https://aka.ms/install-azd.sh | bash

# Vérifier l'installation
azd version
```
</details>

<details>
<summary><strong>❌ "Aucun abonnement trouvé" ou "Abonnement non défini"</strong></summary>

```bash
# Lister les abonnements disponibles
az account list --output table

# Définir l'abonnement par défaut
az account set --subscription "<subscription-id-or-name>"

# Configurer pour l'environnement AZD
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Vérifier
az account show
```
</details>

<details>
<summary><strong>❌ "Quota insuffisant" ou "Quota dépassé"</strong></summary>

```bash
# Essayez une autre région Azure
azd env set AZURE_LOCATION "westus2"
azd up

# Ou utilisez des SKU plus petits en développement
# Modifiez infra/main.parameters.json :
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>

<details>
<summary><strong>❌ Échec de "azd up" à mi-chemin</strong></summary>

```bash
# Option 1 : Nettoyer et réessayer
azd down --force --purge
azd up

# Option 2 : Simplement réparer l'infrastructure
azd provision

# Option 3 : Vérifier les journaux détaillés
azd show
azd logs
```
</details>

<details>
<summary><strong>❌ "Échec d’authentification" ou "Jeton expiré"</strong></summary>

```bash
# Ré-authentifier
az logout
az login

azd auth logout
azd auth login

# Vérifier l'authentification
az account show
```
</details>

<details>
<summary><strong>❌ "Ressource déjà existante" ou conflits de noms</strong></summary>

```bash
# AZD génère des noms uniques, mais en cas de conflit :
azd down --force --purge

# Puis réessayez avec un nouvel environnement
azd env new dev-v2
azd up
```
</details>

<details>
<summary><strong>❌ Le déploiement du modèle prend trop de temps</strong></summary>

**Temps d’attente normaux :**  
- Application web simple : 5-10 minutes  
- Application avec base de données : 10-15 minutes  
- Applications IA : 15-25 minutes (le provisionnement OpenAI est lent)  

```bash
# Vérifier la progression
azd show

# Si bloqué >30 minutes, vérifier le portail Azure :
azd monitor
# Rechercher les déploiements échoués
```
</details>

<details>
<summary><strong>❌ "Permission refusée" ou "Interdit"</strong></summary>

```bash
# Vérifiez votre rôle Azure
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Vous avez besoin d'au moins le rôle "Contributeur"
# Demandez à votre administrateur Azure d'accorder :
# - Contributeur (pour les ressources)
# - Administrateur d'accès utilisateur (pour les attributions de rôle)
```
</details>

<details>
<summary><strong>❌ Impossible de trouver l’URL de l’application déployée</strong></summary>

```bash
# Afficher tous les points de terminaison de service
azd show

# Ou ouvrir le portail Azure
azd monitor

# Vérifier un service spécifique
azd env get-values
# Rechercher les variables *_URL
```
</details>

### 📚 Ressources Complètes de Résolution des Problèmes

- **Guide des problèmes courants :** [Solutions Détaillées](docs/troubleshooting/common-issues.md)  
- **Problèmes spécifiques à l’IA :** [Résolution IA](docs/troubleshooting/ai-troubleshooting.md)  
- **Guide de débogage :** [Débogage étape par étape](docs/troubleshooting/debugging.md)  
- **Obtenez de l’aide :** [Discord Azure](https://discord.gg/microsoft-azure) #azure-developer-cli  

---

## 🎓 Achèvement du Cours & Certification

### Suivi de la Progression  
Suivez votre progression d’apprentissage à travers chaque chapitre :  

- [ ] **Chapitre 1** : Fondations & Démarrage Rapide ✅  
- [ ] **Chapitre 2** : Développement AI-First ✅  
- [ ] **Chapitre 3** : Configuration & Authentification ✅  
- [ ] **Chapitre 4** : Infrastructure as Code & Déploiement ✅  
- [ ] **Chapitre 5** : Solutions Multi-Agents IA ✅  
- [ ] **Chapitre 6** : Validation & Planification pré-déploiement ✅  
- [ ] **Chapitre 7** : Résolution de problèmes & Débogage ✅  
- [ ] **Chapitre 8** : Production & Modèles Entreprise ✅  

### Vérification des Acquis  
Après chaque chapitre, vérifiez vos connaissances en :  
1. **Exercice Pratique :** Complétez le déploiement pratique du chapitre  
2. **Contrôle des Connaissances :** Consultez la FAQ de votre chapitre  
3. **Discussion Communautaire :** Partagez votre expérience dans Azure Discord  
4. **Chapitre Suivant :** Passez au niveau de complexité suivant  

### Avantages de l’Achèvement du Cours  
Lorsque vous aurez terminé tous les chapitres, vous disposerez de :  
- **Expérience en Production :** Applications IA réelles déployées sur Azure  
- **Compétences Professionnelles :** Capacités de déploiement prêtes pour l’entreprise  
- **Reconnaissance Communautaire :** Membre actif de la communauté des développeurs Azure  
- **Avancement de Carrière :** Expertise AZD et IA très demandée  

---

## 🤝 Communauté & Support

### Obtenez de l’Aide & du Support  
- **Problèmes Techniques :** [Signaler des bugs et demander des fonctionnalités](https://github.com/microsoft/azd-for-beginners/issues)  
- **Questions d’Apprentissage :** [Communauté Discord Microsoft Azure](https://discord.gg/microsoft-azure) et [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)  
- **Aide Spécifique à l’IA :** Rejoignez le [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)  
- **Documentation :** [Documentation officielle Azure Developer CLI](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)  

### Perspectives Communautaires du Discord Microsoft Foundry  

**Résultats récents du sondage sur le canal #Azure :**  
- **45 %** des développeurs souhaitent utiliser AZD pour les charges de travail IA  
- **Principaux défis :** Déploiements multi-services, gestion des identifiants, préparation à la production  
- **Plus demandés :** Modèles spécifiques à l’IA, guides de dépannage, bonnes pratiques  

**Rejoignez notre communauté pour :**  
- Partager vos expériences AZD + IA et obtenir de l’aide  
- Accéder aux premières versions des nouveaux modèles IA  
- Contribuer aux meilleures pratiques de déploiement IA  
- Influencer le développement futur des fonctionnalités IA + AZD  

### Contribution au Cours  
Vos contributions sont les bienvenues ! Veuillez consulter notre [Guide de Contribution](CONTRIBUTING.md) pour les détails sur :  
- **Améliorations du contenu :** Améliorez les chapitres et exemples existants  
- **Nouveaux exemples :** Ajoutez des scénarios et modèles concrets  
- **Traduction :** Aidez à maintenir la prise en charge multilingue  
- **Rapports de bugs :** Améliorez précision et clarté  
- **Normes communautaires :** Respectez nos directives inclusives  

---

## 📄 Informations sur le Cours

### Licence  
Ce projet est sous licence MIT - voir le fichier [LICENSE](../../LICENSE) pour plus de détails.  

### Ressources Microsoft Learning Associées

Notre équipe produit d’autres cours complets d’apprentissage :  

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
   
### Série IA Générative  
[![Generative AI for Beginners](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)  
[![Generative AI (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)  
[![Generative AI (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)  
[![Generative AI (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)  

---  
   
### Apprentissage Fondamental  
[![ML for Beginners](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![Data Science pour les débutants](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![IA pour les débutants](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Cybersécurité pour les débutants](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Développement Web pour les débutants](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![IoT pour les débutants](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![Développement XR pour les débutants](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---

### Série Copilot
[![Copilot pour la programmation assistée par IA](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![Copilot pour C#/.NET](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Aventure Copilot](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ Navigation du cours

**🚀 Prêt à commencer à apprendre ?**

**Débutants** : Commencez par [Chapitre 1 : Fondations & Démarrage rapide](../..)  
**Développeurs IA** : Passez à [Chapitre 2 : Développement AI-first](../..)  
**Développeurs expérimentés** : Débutez par [Chapitre 3 : Configuration & Authentification](../..)

**Étapes suivantes** : [Commencez Chapitre 1 - Notions de base AZD](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Avertissement** :  
Ce document a été traduit à l’aide du service de traduction automatique [Co-op Translator](https://github.com/Azure/co-op-translator). Bien que nous œuvrions pour garantir l’exactitude, veuillez noter que les traductions automatiques peuvent contenir des erreurs ou des inexactitudes. Le document original dans sa langue d’origine doit être considéré comme la source faisant foi. Pour les informations critiques, une traduction professionnelle humaine est recommandée. Nous ne sommes pas responsables des malentendus ou interprétations erronées résultant de l’utilisation de cette traduction.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->