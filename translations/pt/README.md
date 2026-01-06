<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T13:19:59+00:00",
  "source_file": "README.md",
  "language_code": "pt"
}
-->
> Nota: Esta documentação é continuamente atualizada para refletir as últimas alterações.

> ⚠️ Este repositório é uma demo criada para demonstrar
> a localização automática de documentação usando o Localizeflow.
>
> O conteúdo original é baseado
> no projeto “AZD for Beginners” da Microsoft.


# AZD Para Iniciantes: Uma Jornada de Aprendizagem Estruturada

![AZD-for-beginners](../../translated_images/azdbeginners.5527441dd9f74068.pt.png) 

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## Introdução a Este Curso

Siga estes passos para iniciar a sua jornada de aprendizagem AZD:

1. **Fazer Fork do Repositório**: Clique [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)
2. **Clonar o Repositório**: `git clone https://github.com/microsoft/azd-for-beginners.git`
3. **Juntar-se à Comunidade**: [Comunidades Discord Azure](https://discord.com/invite/ByRwuEEgH4) para suporte especializado
4. **Escolher o Seu Caminho de Aprendizagem**: Seleccione abaixo um capítulo que corresponda ao seu nível de experiência

### Suporte Multilíngue

#### Traduções Automáticas (Sempre Atualizadas)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Árabe](../ar/README.md) | [Bengali](../bn/README.md) | [Búlgaro](../bg/README.md) | [Birmanês (Myanmar)](../my/README.md) | [Chinês (Simplificado)](../zh/README.md) | [Chinês (Tradicional, Hong Kong)](../hk/README.md) | [Chinês (Tradicional, Macau)](../mo/README.md) | [Chinês (Tradicional, Taiwan)](../tw/README.md) | [Croata](../hr/README.md) | [Checo](../cs/README.md) | [Dinamarquês](../da/README.md) | [Holandês](../nl/README.md) | [Estónio](../et/README.md) | [Finlandês](../fi/README.md) | [Francês](../fr/README.md) | [Alemão](../de/README.md) | [Grego](../el/README.md) | [Hebraico](../he/README.md) | [Hindi](../hi/README.md) | [Húngaro](../hu/README.md) | [Indonésio](../id/README.md) | [Italiano](../it/README.md) | [Japonês](../ja/README.md) | [Kannada](../kn/README.md) | [Coreano](../ko/README.md) | [Lituano](../lt/README.md) | [Malaio](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Pidgin Nigeriano](../pcm/README.md) | [Norueguês](../no/README.md) | [Persa (Farsi)](../fa/README.md) | [Polaco](../pl/README.md) | [Português (Brasil)](../br/README.md) | [Português (Portugal)](./README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romeno](../ro/README.md) | [Russo](../ru/README.md) | [Sérvio (Cirílico)](../sr/README.md) | [Eslovaco](../sk/README.md) | [Esloveno](../sl/README.md) | [Espanhol](../es/README.md) | [Suaíli](../sw/README.md) | [Sueco](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Tailandês](../th/README.md) | [Turco](../tr/README.md) | [Ucraniano](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamita](../vi/README.md)

> **Prefere Clonar Localmente?**

> Este repositório inclui mais de 50 traduções de idiomas, o que aumenta significativamente o tamanho do download. Para clonar sem traduções, use o sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Isto dá-lhe tudo o que necessita para completar o curso com um download muito mais rápido.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## Visão Geral do Curso

Domine o Azure Developer CLI (azd) através de capítulos estruturados, concebidos para uma aprendizagem progressiva. **Foco especial no deployment de aplicações de IA com integração Microsoft Foundry.**

### Porque Este Curso é Essencial para Desenvolvedores Modernos

Baseado nas percepções da comunidade Microsoft Foundry Discord, **45% dos desenvolvedores querem usar o AZD para cargas de trabalho em IA** mas encontram desafios em:
- Arquiteturas complexas multi-serviço de IA
- Melhores práticas para deployment de IA em produção  
- Integração e configuração de serviços AI Azure
- Otimização de custos para cargas de trabalho IA
- Resolução de problemas específicos de deploy IA

### Objetivos de Aprendizagem

Com a conclusão deste curso estruturado, você irá:
- **Dominar os Fundamentos do AZD**: Conceitos principais, instalação e configuração
- **Deploy de Aplicações IA**: Usar AZD com serviços Microsoft Foundry
- **Implementar Infraestrutura como Código**: Gerir recursos Azure com templates Bicep
- **Resolver Problemas de Deploy**: Diagnosticar problemas e fazer debugging
- **Otimizar para Produção**: Segurança, escalabilidade, monitorização e controlo de custos
- **Criar Soluções Multi-Agente**: Deploy de arquiteturas IA complexas

## 📚 Capítulos de Aprendizagem

*Selecione o seu caminho de aprendizagem baseado no nível de experiência e objetivos*

### 🚀 Capítulo 1: Fundamentos & Arranque Rápido
**Pré-Requisitos**: Subscrição Azure, conhecimentos básicos de linha de comando  
**Duração**: 30-45 minutos  
**Complexidade**: ⭐

#### O Que Vai Aprender
- Compreender os fundamentos do Azure Developer CLI
- Instalar o AZD na sua plataforma
- O seu primeiro deployment bem-sucedido

#### Recursos de Aprendizagem
- **🎯 Comece Aqui**: [O que é o Azure Developer CLI?](../..)
- **📖 Teoria**: [Noções Básicas de AZD](docs/getting-started/azd-basics.md) - Conceitos e terminologia essenciais
- **⚙️ Configuração**: [Instalação & Configuração](docs/getting-started/installation.md) - Guias específicos para plataforma
- **🛠️ Práticos**: [O Seu Primeiro Projeto](docs/getting-started/first-project.md) - Tutorial passo a passo
- **📋 Referência Rápida**: [Folha de Consulta de Comandos](resources/cheat-sheet.md)

#### Exercícios Práticos
```bash
# Verificação rápida de instalação
azd version

# Faça o deploy da sua primeira aplicação
azd init --template todo-nodejs-mongo
azd up
```

**💡 Resultado do Capítulo**: Conseguir fazer deploy com sucesso de uma aplicação web simples no Azure usando o AZD

**✅ Validação de Sucesso:**
```bash
# Depois de completar o Capítulo 1, deverá ser capaz de:
azd version              # Mostra a versão instalada
azd init --template todo-nodejs-mongo  # Inicializa o projeto
azd up                  # Faz o deploy para o Azure
azd show                # Mostra a URL da aplicação em execução
# A aplicação abre no navegador e funciona
azd down --force --purge  # Limpa os recursos
```

**📊 Tempo Estimado:** 30-45 minutos  
**📈 Nível de Competência Após:** Capaz de fazer deploy de aplicações básicas de forma independente

**✅ Validação de Sucesso:**
```bash
# Depois de completar o Capítulo 1, deverá ser capaz de:
azd version              # Mostra a versão instalada
azd init --template todo-nodejs-mongo  # Inicializa o projeto
azd up                  # Faça o deploy para o Azure
azd show                # Mostra a URL da aplicação em execução
# A aplicação abre no navegador e funciona
azd down --force --purge  # Limpa os recursos
```

**📊 Tempo Estimado:** 30-45 minutos  
**📈 Nível de Competência Após:** Capaz de fazer deploy de aplicações básicas de forma independente

---

### 🤖 Capítulo 2: Desenvolvimento Focado em IA (Recomendado para Desenvolvedores IA)
**Pré-Requisitos**: Capítulo 1 concluído  
**Duração**: 1-2 horas  
**Complexidade**: ⭐⭐

#### O Que Vai Aprender
- Integração Microsoft Foundry com AZD
- Deployment de aplicações potenciadas por IA
- Compreender configurações de serviços IA

#### Recursos de Aprendizagem
- **🎯 Comece Aqui**: [Integração Microsoft Foundry](docs/microsoft-foundry/microsoft-foundry-integration.md)
- **📖 Padrões**: [Deployment de Modelos IA](docs/microsoft-foundry/ai-model-deployment.md) - Deploy e gestão de modelos de IA
- **🛠️ Workshop**: [Laboratório AI Workshop](docs/microsoft-foundry/ai-workshop-lab.md) - Prepare as suas soluções IA para AZD
- **🎥 Guia Interativo**: [Materiais do Workshop](workshop/README.md) - Aprendizagem no navegador com MkDocs * Ambiente DevContainer
- **📋 Templates**: [Templates Microsoft Foundry em destaque](../..)
- **📝 Exemplos**: [Exemplos de Deployment AZD](examples/README.md)

#### Exercícios Práticos
```bash
# Implemente a sua primeira aplicação de IA
azd init --template azure-search-openai-demo
azd up

# Experimente modelos adicionais de IA
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```

**💡 Resultado do Capítulo**: Deploy e configuração de uma aplicação de chat IA com capacidades RAG

**✅ Validação de Sucesso:**
```bash
# Depois do Capítulo 2, deverá ser capaz de:
azd init --template azure-search-openai-demo
azd up
# Testar a interface de chat da IA
# Fazer perguntas e obter respostas com IA e fontes
# Verificar que a integração de pesquisa funciona
azd monitor  # Confirmar que o Application Insights mostra telemetria
azd down --force --purge
```

**📊 Tempo Estimado:** 1-2 horas  
**📈 Nível de Competência Após:** Capaz de fazer deploy e configurar aplicações IA prontas para produção  
**💰 Consciência de Custos:** Entende custos de desenvolvimento de $80-150/mês, custos de produção $300-3500/mês

#### 💰 Considerações de Custo para Deployments IA

**Ambiente de Desenvolvimento (Estimado $80-150/mês):**
- Azure OpenAI (pagamento conforme uso): $0-50/mês (baseado em uso de tokens)
- AI Search (nível básico): $75/mês
- Container Apps (Consumo): $0-20/mês
- Armazenamento (Standard): $1-5/mês

**Ambiente de Produção (Estimado $300-3.500+/mês):**
- Azure OpenAI (PTU para desempenho consistente): $3.000+/mês OU pagamento conforme uso com volume elevado
- AI Search (nível Standard): $250/mês
- Container Apps (Dedicado): $50-100/mês
- Application Insights: $5-50/mês
- Armazenamento (Premium): $10-50/mês

**💡 Dicas de Otimização de Custos:**
- Use Azure OpenAI **Tier Gratuito** para aprendizagem (50.000 tokens/mês incluídos)
- Execute `azd down` para desalocar recursos quando não estiver a desenvolver ativamente
- Comece com faturação por consumo, só faça upgrade para PTU em produção
- Use `azd provision --preview` para estimar custos antes do deployment
- Ative escalabilidade automática: pague só pelo uso real

**Monitorização de Custos:**
```bash
# Verificar custos mensais estimados
azd provision --preview

# Monitorizar custos reais no Portal Azure
az consumption budget list --resource-group <your-rg>
```

---

### ⚙️ Capítulo 3: Configuração & Autenticação
**Pré-Requisitos**: Capítulo 1 concluído  
**Duração**: 45-60 minutos  
**Complexidade**: ⭐⭐

#### O Que Vai Aprender
- Configuração e gestão de ambientes
- Melhores práticas de autenticação e segurança
- Nomeação e organização de recursos

#### Recursos de Aprendizagem
- **📖 Configuração**: [Guia de Configuração](docs/getting-started/configuration.md) - Configuração do ambiente
- **🔐 Segurança**: [Padrões de autenticação e identidade gerida](docs/getting-started/authsecurity.md) - Padrões de autenticação
- **📝 Exemplos**: [Exemplo de Aplicação de Base de Dados](examples/database-app/README.md) - Exemplos AZD para base de dados

#### Exercícios Práticos
- Configurar múltiplos ambientes (dev, staging, prod)
- Configurar autenticação por identidade gerida
- Implementar configurações específicas para ambiente

**💡 Resultado do Capítulo**: Gerir múltiplos ambientes com autenticação e segurança adequadas

---

### 🏗️ Capítulo 4: Infraestrutura como Código & Deployment
**Pré-Requisitos**: Capítulos 1-3 concluídos  
**Duração**: 1-1.5 horas  
**Complexidade**: ⭐⭐⭐

#### O Que Vai Aprender
- Padrões avançados de deployment
- Infraestrutura como Código com Bicep
- Estratégias de provisão de recursos

#### Recursos de Aprendizagem
- **📖 Deployment**: [Guia de Deployment](docs/deployment/deployment-guide.md) - Workflows completos
- **🏗️ Provisão**: [Provisão de Recursos](docs/deployment/provisioning.md) - Gestão de recursos Azure
- **📝 Exemplos**: [Exemplo de Container App](../../examples/container-app) - Deployments conteinerizados

#### Exercícios Práticos
- Criar templates Bicep personalizados
- Fazer deploy de aplicações multi-serviço
- Implementar estratégias de deployment azul-verde

**💡 Resultado do Capítulo**: Deploy de aplicações multi-serviço complexas usando templates de infraestrutura personalizados

---
### 🎯 Capítulo 5: Soluções de IA Multi-Agente (Avançado)
**Pré-requisitos**: Capítulos 1-2 concluídos  
**Duração**: 2-3 horas  
**Complexidade**: ⭐⭐⭐⭐

#### O que Vai Aprender
- Padrões de arquitetura multi-agente
- Orquestração e coordenação de agentes
- Desdobramentos de IA prontos para produção

#### Recursos de Aprendizagem
- **🤖 Projeto em Destaque**: [Solução Multi-Agente para Retalho](examples/retail-scenario.md) - Implementação completa
- **🛠️ Templates ARM**: [Pacote de Template ARM](../../examples/retail-multiagent-arm-template) - Desdobramento com um clique
- **📖 Arquitetura**: [Padrões de coordenação multi-agente](/docs/pre-deployment/coordination-patterns.md) - Padrões

#### Exercícios Práticos
```bash
# Implementar a solução completa de multi-agentes para retalho
cd examples/retail-multiagent-arm-template
./deploy.sh

# Explorar as configurações do agente
az deployment group show --resource-group <rg-name> --name <deployment-name>
```

**💡 Resultado do Capítulo**: Desdobrar e gerir uma solução de IA multi-agente pronta para produção com agentes de Cliente e Inventário

---

### 🔍 Capítulo 6: Validação & Planeamento Pré-Desdobramento
**Pré-requisitos**: Capítulo 4 concluído  
**Duração**: 1 hora  
**Complexidade**: ⭐⭐

#### O que Vai Aprender
- Planeamento de capacidade e validação de recursos
- Estratégias de seleção de SKU
- Verificações prévias e automação

#### Recursos de Aprendizagem
- **📊 Planeamento**: [Planeamento de Capacidade](docs/pre-deployment/capacity-planning.md) - Validação de recursos
- **💰 Seleção**: [Seleção de SKU](docs/pre-deployment/sku-selection.md) - Escolhas custo-efetivas
- **✅ Validação**: [Verificações Prévias](docs/pre-deployment/preflight-checks.md) - Scripts automatizados

#### Exercícios Práticos
- Executar scripts de validação de capacidade
- Otimizar seleções de SKU para custo
- Implementar verificações automatizadas pré-desdobramento

**💡 Resultado do Capítulo**: Validar e otimizar desdobramentos antes da execução

---

### 🚨 Capítulo 7: Resolução de Problemas & Depuração
**Pré-requisitos**: Qualquer capítulo de desdobramento concluído  
**Duração**: 1-1.5 horas  
**Complexidade**: ⭐⭐

#### O que Vai Aprender
- Abordagens sistemáticas de depuração
- Problemas comuns e soluções
- Resolução de problemas específica de IA

#### Recursos de Aprendizagem
- **🔧 Problemas Comuns**: [Problemas Comuns](docs/troubleshooting/common-issues.md) - FAQ e soluções
- **🕵️ Depuração**: [Guia de Depuração](docs/troubleshooting/debugging.md) - Estratégias passo a passo
- **🤖 Problemas de IA**: [Resolução de Problemas de IA](docs/troubleshooting/ai-troubleshooting.md) - Problemas de serviço IA

#### Exercícios Práticos
- Diagnosticar falhas de desdobramento
- Resolver problemas de autenticação
- Depurar conectividade de serviços IA

**💡 Resultado do Capítulo**: Diagnosticar e resolver problemas comuns de desdobramento de forma independente

---

### 🏢 Capítulo 8: Padrões de Produção & Empresariais
**Pré-requisitos**: Capítulos 1-4 concluídos  
**Duração**: 2-3 horas  
**Complexidade**: ⭐⭐⭐⭐

#### O que Vai Aprender
- Estratégias de desdobramento para produção
- Padrões de segurança empresariais
- Monitorização e otimização de custos

#### Recursos de Aprendizagem
- **🏭 Produção**: [Melhores Práticas de IA em Produção](docs/microsoft-foundry/production-ai-practices.md) - Padrões empresariais
- **📝 Exemplos**: [Exemplo de Microsserviços](../../examples/microservices) - Arquiteturas complexas
- **📊 Monitorização**: [Integração com Application Insights](docs/pre-deployment/application-insights.md) - Monitorização

#### Exercícios Práticos
- Implementar padrões de segurança empresariais
- Configurar monitorização abrangente
- Desdobrar para produção com governança adequada

**💡 Resultado do Capítulo**: Desdobrar aplicações prontas para ambiente empresarial com total capacidade de produção

---

## 🎓 Visão Geral do Workshop: Experiência Prática

> **⚠️ ESTADO DO WORKSHOP: Desenvolvimento Ativo**  
> Os materiais do workshop estão a ser desenvolvidos e aperfeiçoados. Os módulos principais estão funcionais, mas algumas secções avançadas ainda estão incompletas. Estamos a trabalhar ativamente para completar todo o conteúdo. [Acompanhar progresso →](workshop/README.md)

### Materiais Interativos do Workshop
**Aprendizagem prática abrangente com ferramentas baseadas no navegador e exercícios guiados**

Os materiais do workshop fornecem uma experiência de aprendizagem estruturada e interativa que complementa o currículo baseado em capítulos acima. O workshop é desenhado tanto para aprendizagem autónoma como para sessões guiadas por instrutor.

#### 🛠️ Características do Workshop
- **Interface Baseada em Browser**: Workshop completo com MkDocs, pesquisa, cópia e funcionalidades de tema
- **Integração com GitHub Codespaces**: Configuração do ambiente de desenvolvimento com um clique
- **Caminho de Aprendizagem Estruturado**: 7 exercícios guiados (3,5 horas no total)
- **Descoberta → Desdobramento → Personalização**: Metodologia progressiva
- **Ambiente DevContainer Interativo**: Ferramentas e dependências pré-configuradas

#### 📚 Estrutura do Workshop
O workshop segue a metodologia **Descoberta → Desdobramento → Personalização**:

1. **Fase de Descoberta** (45 mins)
   - Explorar templates e serviços Microsoft Foundry
   - Compreender padrões de arquitetura multi-agente
   - Rever requisitos e pré-requisitos de desdobramento

2. **Fase de Desdobramento** (2 horas)
   - Desdobramento prático de aplicações de IA com AZD
   - Configurar serviços e endpoints Azure AI
   - Implementar padrões de segurança e autenticação

3. **Fase de Personalização** (45 mins)
   - Modificar aplicações para casos de uso específicos
   - Otimizar para desdobramento em produção
   - Implementar monitorização e gestão de custos

#### 🚀 Começar com o Workshop
```bash
# Opção 1: GitHub Codespaces (Recomendado)
# Clique em "Code" → "Create codespace on main" no repositório

# Opção 2: Desenvolvimento Local
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# Siga as instruções de configuração em workshop/README.md
```

#### 🎯 Resultados de Aprendizagem do Workshop
Ao concluir o workshop, os participantes irão:
- **Desdobrar Aplicações IA em Produção**: Usar AZD com serviços Microsoft Foundry
- **Dominar Arquiteturas Multi-Agente**: Implementar soluções coordenadas de agentes IA
- **Implementar Melhores Práticas de Segurança**: Configurar autenticação e controlo de acesso
- **Otimizar para Escalabilidade**: Projetar desdobramentos custo-efetivos e performativos
- **Resolver Problemas em Desdobramentos**: Solucionar problemas comuns de forma autónoma

#### 📖 Recursos do Workshop
- **🎥 Guia Interativo**: [Materiais do Workshop](workshop/README.md) - Ambiente de aprendizagem baseado em navegador
- **📋 Instruções Passo a Passo**: [Exercícios Guiados](../../workshop/docs/instructions) - Passo a passo detalhado
- **🛠️ Laboratório de IA**: [Laboratório de IA do Workshop](docs/microsoft-foundry/ai-workshop-lab.md) - Exercícios focados em IA
- **💡 Arranque Rápido**: [Guia de Configuração do Workshop](workshop/README.md#quick-start) - Configuração do ambiente

**Perfeito para**: Formação corporativa, cursos universitários, aprendizagem autónoma e bootcamps para programadores.

---

## 📖 O que é o Azure Developer CLI?

Azure Developer CLI (azd) é uma interface de linha de comandos centrada no programador que acelera o processo de construção e desdobramento de aplicações para Azure. Oferece:

- **Desdobramentos baseados em templates** - Usar templates pré-construídos para padrões comuns de aplicação
- **Infraestrutura como Código** - Gerir recursos Azure usando Bicep ou Terraform  
- **Fluxos de trabalho integrados** - Provisionar, desdobrar e monitorizar aplicações de forma fluída
- **Amigável para programadores** - Otimizado para produtividade e experiência do programador

### **AZD + Microsoft Foundry: Perfeito para Desdobramentos IA**

**Porque AZD para Soluções de IA?** O AZD resolve os principais desafios enfrentados pelos programadores de IA:

- **Templates Prontos para IA** - Templates pré-configurados para Azure OpenAI, Serviços Cognitivos e cargas de trabalho ML
- **Desdobramentos IA Seguros** - Padrões de segurança integrados para serviços IA, chaves API e endpoints de modelos  
- **Padrões IA para Produção** - Melhores práticas para desdobramentos escaláveis e custo-efetivos
- **Fluxos de Trabalho IA de Ponta a Ponta** - Desde o desenvolvimento do modelo até ao desdobramento em produção com monitorização adequada
- **Otimização de Custos** - Alocação inteligente de recursos e estratégias de escalamento para cargas IA
- **Integração Microsoft Foundry** - Ligação transparente ao catálogo de modelos e endpoints Microsoft Foundry

---

## 🎯 Biblioteca de Templates & Exemplos

### Em Destaque: Templates Microsoft Foundry
**Comece aqui se estiver a desdobrar aplicações IA!**

> **Nota:** Estes templates demonstram vários padrões IA. Alguns são Azure Samples externos, outros são implementações locais.

| Template | Capítulo | Complexidade | Serviços | Tipo |
|----------|---------|------------|----------|------|
| [**Começar com chat IA**](https://github.com/Azure-Samples/get-started-with-ai-chat) | Capítulo 2 | ⭐⭐ | AzureOpenAI + API de Inferência de Modelo Azure AI + Azure AI Search + Azure Container Apps + Application Insights | Externo |
| [**Começar com agentes IA**](https://github.com/Azure-Samples/get-started-with-ai-agents) | Capítulo 2 | ⭐⭐ | Serviço Azure AI Agent + AzureOpenAI + Azure AI Search + Azure Container Apps + Application Insights| Externo |
| [**Demo Azure Search + OpenAI**](https://github.com/Azure-Samples/azure-search-openai-demo) | Capítulo 2 | ⭐⭐ | AzureOpenAI + Azure AI Search + App Service + Storage | Externo |
| [**OpenAI Chat App Quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Capítulo 2 | ⭐ | AzureOpenAI + Container Apps + Application Insights | Externo |
| [**Agent OpenAI Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Capítulo 5 | ⭐⭐⭐ | AzureOpenAI + Azure Functions + Prompty | Externo |
| [**Contoso Chat RAG**](https://github.com/Azure-Samples/contoso-chat) | Capítulo 8 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Cosmos DB + Container Apps | Externo |
| [**Solução Multi-Agente para Retalho**](examples/retail-scenario.md) | Capítulo 5 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Storage + Container Apps + Cosmos DB | **Local** |

### Em Destaque: Cenários de Aprendizagem Completos
**Templates de aplicações prontos para produção mapeados para capítulos de aprendizagem**

| Template | Capítulo de Aprendizagem | Complexidade | Aprendizagem-Chave |
|----------|--------------------------|--------------|--------------------|
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Capítulo 2 | ⭐ | Padrões básicos de desdobramento IA |
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Capítulo 2 | ⭐⭐ | Implementação RAG com Azure AI Search |
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | Capítulo 4 | ⭐⭐ | Integração Document Intelligence |
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Capítulo 5 | ⭐⭐⭐ | Framework de agentes e chamada de funções |
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | Capítulo 8 | ⭐⭐⭐ | Orquestração IA empresarial |
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | Capítulo 5 | ⭐⭐⭐⭐ | Arquitetura multi-agente com agentes Cliente e Inventário |

### Aprendizagem por Tipo de Exemplo

> **📌 Exemplos Locais vs. Externos:**  
> **Exemplos Locais** (neste repositório) = Prontos a usar imediatamente  
> **Exemplos Externos** (Azure Samples) = Clonar a partir dos repositórios ligados

#### Exemplos Locais (Prontos a Usar)
- [**Solução Multi-Agente para Retalho**](examples/retail-scenario.md) - Implementação completa pronta para produção com templates ARM
  - Arquitetura multi-agente (agentes Cliente + Inventário)
  - Monitorização e avaliação abrangentes
  - Desdobramento com um clique via template ARM

#### Exemplos Locais - Aplicações em Container (Capítulos 2-5)
**Exemplos abrangentes de desdobramento em container neste repositório:**
- [**Exemplos de Container App**](examples/container-app/README.md) - Guia completo para desdobramentos conteinerizados
  - [API Flask Simples](../../examples/container-app/simple-flask-api) - API REST básica com scale-to-zero
  - [Arquitetura de Microsserviços](../../examples/container-app/microservices) - Desdobramento multi-serviço pronto para produção
  - Padrões de desdobramento Quick Start, Produção e Avançado
  - Orientação para monitorização, segurança e otimização de custos

#### Exemplos Externos - Aplicações Simples (Capítulos 1-2)
**Clone estes repositórios Azure Samples para começar:**
- [App Web Simples - Node.js + MongoDB](https://github.com/Azure-Samples/todo-nodejs-mongo) - Padrões básicos de desdobramento
- [Website Estático - React SPA](https://github.com/Azure-Samples/todo-csharp-sql-swa-func) - Desdobramento de conteúdo estático
- [Container App - Python Flask](https://github.com/Azure-Samples/container-apps-store-api-microservice) - Desdobramento API REST

#### Exemplos Externos - Integração com Base de Dados (Capítulos 3-4)  
- [App Base de Dados - C# + SQL](https://github.com/Azure-Samples/todo-csharp-sql) - Padrões de conectividade de base de dados
- [Functions + Cosmos DB](https://github.com/Azure-Samples/todo-python-mongo-swa-func) - Fluxo de trabalho serverless de dados

#### Exemplos Externos - Padrões Avançados (Capítulos 4-8)
- [Microsserviços Java](https://github.com/Azure-Samples/java-microservices-aca-lab) - Arquiteturas multi-serviço
- [Traballhos Container Apps](https://github.com/Azure-Samples/container-apps-jobs) - Processamento em segundo plano  
- [Pipeline ML Empresarial](https://github.com/Azure-Samples/mlops-v2) - Padrões ML prontos para produção

### Coleções de Templates Externas
- [**Galeria Oficial de Modelos AZD**](https://azure.github.io/awesome-azd/) - Coleção selecionada de modelos oficiais e da comunidade
- [**Modelos do Azure Developer CLI**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - Documentação dos modelos Microsoft Learn
- [**Directório de Exemplos**](examples/README.md) - Exemplos locais de aprendizagem com explicações detalhadas

---

## 📚 Recursos de Aprendizagem & Referências

### Referências Rápidas
- [**Folha de Truques de Comandos**](resources/cheat-sheet.md) - Comandos essenciais do azd organizados por capítulo
- [**Glossário**](resources/glossary.md) - Terminologia Azure e azd  
- [**FAQ**](resources/faq.md) - Perguntas comuns organizadas por capítulo de aprendizagem
- [**Guia de Estudo**](resources/study-guide.md) - Exercícios práticos abrangentes

### Workshops Práticos
- [**Laboratório de Workshop de IA**](docs/microsoft-foundry/ai-workshop-lab.md) - Torne as suas soluções de IA implantáveis com AZD (2-3 horas)
- [**Guia Interativo do Workshop**](workshop/README.md) - Workshop baseado em browser com MkDocs e Ambiente DevContainer
- [**Caminho de Aprendizagem Estruturado**](../../workshop/docs/instructions) - Exercícios guiados em 7 passos (Descoberta → Implantação → Personalização)
- [**Workshop AZD para Iniciantes**](workshop/README.md) - Materiais completos do workshop prático com integração GitHub Codespaces

### Recursos Externos de Aprendizagem
- Documentação do Azure Developer CLI ([Azure Developer CLI Documentation](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/))
- Centro de Arquitetura Azure ([Azure Architecture Center](https://learn.microsoft.com/en-us/azure/architecture/))
- Calculadora de Preços Azure ([Azure Pricing Calculator](https://azure.microsoft.com/pricing/calculator/))
- Estado do Azure ([Azure Status](https://status.azure.com/))

---

## 🔧 Guia Rápido de Resolução de Problemas

**Problemas comuns que os iniciantes encontram e soluções imediatas:**

### ❌ "azd: comando não encontrado"

```bash
# Instale primeiro o AZD
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Verificar instalação
azd version
```

### ❌ "Nenhuma subscrição encontrada" ou "Subscrição não definida"

```bash
# Listar subscrições disponíveis
az account list --output table

# Definir subscrição padrão
az account set --subscription "<subscription-id-or-name>"

# Definir para ambiente AZD
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Verificar
az account show
```

### ❌ "Quota Insuficiente" ou "Quota excedida"

```bash
# Experimente diferentes regiões do Azure
azd env set AZURE_LOCATION "westus2"
azd up

# Ou utilize SKUs mais pequenos no desenvolvimento
# Edite infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```

### ❌ "azd up" falha a meio do processo

```bash
# Opção 1: Limpar e tentar novamente
azd down --force --purge
azd up

# Opção 2: Apenas corrigir a infraestrutura
azd provision

# Opção 3: Verificar os registos detalhados
azd show
azd logs
```

### ❌ "Falha na autenticação" ou "Token expirado"

```bash
# Reautenticar
az logout
az login

azd auth logout
azd auth login

# Verificar autenticação
az account show
```

### ❌ "Recurso já existe" ou conflitos de nomenclatura

```bash
# AZD gera nomes únicos, mas se houver conflito:
azd down --force --purge

# Então tente novamente com um ambiente novo
azd env new dev-v2
azd up
```

### ❌ A implantação do modelo está a demorar demasiado

**Tempos normais de espera:**
- Aplicação web simples: 5-10 minutos
- Aplicação com base de dados: 10-15 minutos
- Aplicações de IA: 15-25 minutos (o provisionamento do OpenAI é lento)

```bash
# Verificar progresso
azd show

# Se estiver preso >30 minutos, verifique o Portal Azure:
azd monitor
# Procure por implantações falhadas
```

### ❌ "Permissão negada" ou "Proibido"

```bash
# Verifique o seu papel no Azure
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Precisa pelo menos do papel de "Contribuidor"
# Peça ao seu administrador do Azure para conceder:
# - Contribuidor (para recursos)
# - Administrador de Acesso de Utilizador (para atribuições de papéis)
```

### ❌ Não consegue encontrar a URL da aplicação implementada

```bash
# Mostrar todos os pontos finais do serviço
azd show

# Ou abrir o Portal Azure
azd monitor

# Verificar serviço específico
azd env get-values
# Procurar variáveis *_URL
```

### 📚 Recursos completos de resolução de problemas

- **Guia de Problemas Comuns:** [Soluções Detalhadas](docs/troubleshooting/common-issues.md)
- **Problemas Específicos de IA:** [Resolução de Problemas de IA](docs/troubleshooting/ai-troubleshooting.md)
- **Guia de Depuração:** [Depuração Passo a Passo](docs/troubleshooting/debugging.md)
- **Obtenha Ajuda:** [Discord Azure](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🔧 Guia Rápido de Resolução de Problemas

**Problemas comuns que os iniciantes encontram e soluções imediatas:**

<details>
<summary><strong>❌ "azd: comando não encontrado"</strong></summary>

```bash
# Instalar primeiro o AZD
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Verificar instalação
azd version
```
</details>

<details>
<summary><strong>❌ "Nenhuma subscrição encontrada" ou "Subscrição não definida"</strong></summary>

```bash
# Listar subscrições disponíveis
az account list --output table

# Definir subscrição padrão
az account set --subscription "<subscription-id-or-name>"

# Definir para ambiente AZD
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Verificar
az account show
```
</details>

<details>
<summary><strong>❌ "Quota Insuficiente" ou "Quota excedida"</strong></summary>

```bash
# Tente uma região do Azure diferente
azd env set AZURE_LOCATION "westus2"
azd up

# Ou use SKUs menores em desenvolvimento
# Edite infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>

<details>
<summary><strong>❌ "azd up" falha a meio do processo</strong></summary>

```bash
# Opção 1: Limpar e tentar novamente
azd down --force --purge
azd up

# Opção 2: Apenas corrigir a infraestrutura
azd provision

# Opção 3: Verificar logs detalhados
azd show
azd logs
```
</details>

<details>
<summary><strong>❌ "Falha na autenticação" ou "Token expirado"</strong></summary>

```bash
# Reautenticar
az logout
az login

azd auth logout
azd auth login

# Verificar autenticação
az account show
```
</details>

<details>
<summary><strong>❌ "Recurso já existe" ou conflitos de nomenclatura</strong></summary>

```bash
# AZD gera nomes únicos, mas se houver conflito:
azd down --force --purge

# Então tente novamente com um ambiente novo
azd env new dev-v2
azd up
```
</details>

<details>
<summary><strong>❌ A implantação do modelo está a demorar demasiado</strong></summary>

**Tempos normais de espera:**
- Aplicação web simples: 5-10 minutos
- Aplicação com base de dados: 10-15 minutos
- Aplicações de IA: 15-25 minutos (o provisionamento do OpenAI é lento)

```bash
# Verificar progresso
azd show

# Se estiver preso >30 minutos, verifique o Portal Azure:
azd monitor
# Procure implantações falhadas
```
</details>

<details>
<summary><strong>❌ "Permissão negada" ou "Proibido"</strong></summary>

```bash
# Verifique o seu papel no Azure
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Precisa pelo menos do papel "Contribuidor"
# Peça ao seu administrador Azure para conceder:
# - Contribuidor (para recursos)
# - Administrador de Acesso de Utilizadores (para atribuições de papéis)
```
</details>

<details>
<summary><strong>❌ Não consegue encontrar a URL da aplicação implementada</strong></summary>

```bash
# Mostrar todos os endpoints de serviço
azd show

# Ou abrir o Portal Azure
azd monitor

# Verificar serviço específico
azd env get-values
# Procurar por variáveis *_URL
```
</details>

### 📚 Recursos completos de resolução de problemas

- **Guia de Problemas Comuns:** [Soluções Detalhadas](docs/troubleshooting/common-issues.md)
- **Problemas Específicos de IA:** [Resolução de Problemas de IA](docs/troubleshooting/ai-troubleshooting.md)
- **Guia de Depuração:** [Depuração Passo a Passo](docs/troubleshooting/debugging.md)
- **Obtenha Ajuda:** [Discord Azure](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🎓 Conclusão do Curso & Certificação

### Acompanhamento do Progresso
Acompanhe o seu progresso de aprendizagem em cada capítulo:

- [ ] **Capítulo 1**: Fundamentos & Arranque Rápido ✅
- [ ] **Capítulo 2**: Desenvolvimento AI-First ✅  
- [ ] **Capítulo 3**: Configuração & Autenticação ✅
- [ ] **Capítulo 4**: Infraestrutura como Código & Implantação ✅
- [ ] **Capítulo 5**: Soluções AI Multi-Agente ✅
- [ ] **Capítulo 6**: Validação & Planeamento Pré-Implantação ✅
- [ ] **Capítulo 7**: Resolução de Problemas & Depuração ✅
- [ ] **Capítulo 8**: Padrões de Produção & Empresariais ✅

### Verificação da Aprendizagem
Após completar cada capítulo, verifique os seus conhecimentos através de:
1. **Exercício Prático**: Complete a implantação prática do capítulo
2. **Verificação de Conhecimento**: Reveja a secção FAQ do seu capítulo
3. **Discussão Comunitária**: Partilhe a sua experiência no Discord Azure
4. **Próximo Capítulo**: Avance para o próximo nível de complexidade

### Benefícios da Conclusão do Curso
Ao concluir todos os capítulos, terá:
- **Experiência em Produção**: Aplicações reais de IA implementadas no Azure
- **Competências Profissionais**: Capacidades de implantação prontas para a empresa  
- **Reconhecimento Comunitário**: Membro ativo da comunidade de desenvolvedores Azure
- **Avanço na Carreira**: Expertise procurada em AZD e implantação de IA

---

## 🤝 Comunidade & Suporte

### Obtenha Ajuda & Suporte
- **Problemas Técnicos**: [Reportar bugs e pedir funcionalidades](https://github.com/microsoft/azd-for-beginners/issues)
- **Perguntas de Aprendizagem**: [Comunidade Discord Microsoft Azure](https://discord.gg/microsoft-azure) e [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **Ajuda Específica de IA**: Junte-se ao [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **Documentação**: [Documentação Oficial do Azure Developer CLI](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)

### Insights da Comunidade do Microsoft Foundry Discord

**Resultados Recentes da Votação no Canal #Azure:**
- **45%** dos desenvolvedores querem usar AZD para cargas de trabalho AI
- **Principais desafios**: Implantações multi-serviço, gestão de credenciais, prontidão para produção  
- **Mais solicitados**: Modelos específicos para IA, guias de resolução de problemas, melhores práticas

**Junte-se à nossa comunidade para:**
- Partilhar as suas experiências AZD + IA e obter ajuda
- Aceder a pré-visualizações antecipadas de novos modelos de IA
- Contribuir para as melhores práticas de implantação de IA
- Influenciar o desenvolvimento futuro das funcionalidades AI + AZD

### Contribuir para o Curso
Aceitamos contribuições! Por favor, consulte o nosso [Guia de Contribuição](CONTRIBUTING.md) para detalhes sobre:
- **Melhorias de Conteúdo**: Aperfeiçoe capítulos e exemplos existentes
- **Novos Exemplos**: Adicione cenários e modelos do mundo real  
- **Tradução**: Ajude a manter o suporte multilíngue
- **Relatório de Bugs**: Melhore a precisão e clareza
- **Normas Comunitárias**: Siga as nossas diretrizes inclusivas de comunidade

---

## 📄 Informações do Curso

### Licença
Este projeto está licenciado sob a Licença MIT - veja o ficheiro [LICENSE](../../LICENSE) para detalhes.

### Recursos Microsoft Learning Relacionados

A nossa equipa produz outros cursos de aprendizagem abrangentes:

<!-- CO-OP TRANSLATOR OTHER COURSES START -->
### LangChain
[![LangChain4j para Iniciantes](https://img.shields.io/badge/LangChain4j%20for%20Beginners-22C55E?style=for-the-badge&&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchain4j-for-beginners)
[![LangChain.js para Iniciantes](https://img.shields.io/badge/LangChain.js%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchainjs-for-beginners?WT.mc_id=m365-94501-dwahlin)

---

### Azure / Edge / MCP / Agentes
[![AZD para Iniciantes](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Edge AI para Iniciantes](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![MCP para Iniciantes](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Agentes AI para Iniciantes](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Série de IA Generativa
[![IA Generativa para Iniciantes](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![IA Generativa (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
[![IA Generativa (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)
[![IA Generativa (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---
 
### Aprendizagem Core
[![ML para Iniciantes](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![Ciência de Dados para Iniciantes](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![IA para Iniciantes](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Cibersegurança para Iniciantes](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Desenvolvimento Web para Iniciantes](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![IoT para Iniciantes](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![Desenvolvimento XR para Iniciantes](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Série Copilot
[![Copilot para Programação Emparelhada com IA](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![Copilot para C#/.NET](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Aventura Copilot](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ Navegação do Curso

**🚀 Pronto para Começar a Aprender?**

**Iniciantes**: Comece com [Capítulo 1: Fundamentos e Arranque Rápido](../..)  
**Desenvolvedores de IA**: Avance para [Capítulo 2: Desenvolvimento AI-First](../..)  
**Desenvolvedores Experientes**: Comece com [Capítulo 3: Configuração e Autenticação](../..)

**Próximos Passos**: [Iniciar Capítulo 1 - Noções Básicas de AZD](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Aviso Legal**:  
Este documento foi traduzido utilizando o serviço de tradução automática [Co-op Translator](https://github.com/Azure/co-op-translator). Embora nos esforcemos para garantir a precisão, por favor esteja atento(a) que traduções automáticas podem conter erros ou imprecisões. O documento original na sua língua nativa deve ser considerado a fonte autorizada. Para informações críticas, recomenda-se tradução profissional humana. Não nos responsabilizamos por quaisquer mal-entendidos ou interpretações incorretas decorrentes do uso desta tradução.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->