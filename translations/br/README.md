<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T13:22:25+00:00",
  "source_file": "README.md",
  "language_code": "br"
}
-->
> Nota: Esta documentação é continuamente atualizada para refletir as últimas mudanças.

> ⚠️ Este repositório é uma demonstração criada para exibir
> localização automatizada de documentação usando Localizeflow.
>
> O conteúdo original é baseado no
> projeto “AZD para Iniciantes” da Microsoft.


# AZD para Iniciantes: Uma Jornada de Aprendizado Estruturada

![AZD-for-beginners](../../translated_images/azdbeginners.5527441dd9f74068.br.png) 

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## Começando com este Curso

Siga estes passos para iniciar sua jornada de aprendizado AZD:

1. **Faça um Fork do Repositório**: Clique [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)
2. **Clone o Repositório**: `git clone https://github.com/microsoft/azd-for-beginners.git`
3. **Junte-se à Comunidade**: [Comunidades Azure Discord](https://discord.com/invite/ByRwuEEgH4) para suporte especializado
4. **Escolha Seu Caminho de Aprendizado**: Selecione um capítulo abaixo que corresponda ao seu nível de experiência

### Suporte a Múltiplos Idiomas

#### Traduções Automatizadas (Sempre Atualizadas)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Árabe](../ar/README.md) | [Bengali](../bn/README.md) | [Búlgaro](../bg/README.md) | [Birmanês (Myanmar)](../my/README.md) | [Chinês (Simplificado)](../zh/README.md) | [Chinês (Tradicional, Hong Kong)](../hk/README.md) | [Chinês (Tradicional, Macau)](../mo/README.md) | [Chinês (Tradicional, Taiwan)](../tw/README.md) | [Croata](../hr/README.md) | [Tcheco](../cs/README.md) | [Dinamarquês](../da/README.md) | [Holandês](../nl/README.md) | [Estoniano](../et/README.md) | [Finlandês](../fi/README.md) | [Francês](../fr/README.md) | [Alemão](../de/README.md) | [Grego](../el/README.md) | [Hebraico](../he/README.md) | [Hindi](../hi/README.md) | [Húngaro](../hu/README.md) | [Indonésio](../id/README.md) | [Italiano](../it/README.md) | [Japonês](../ja/README.md) | [Canarês](../kn/README.md) | [Coreano](../ko/README.md) | [Lituano](../lt/README.md) | [Malaio](../ms/README.md) | [Malaiala](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Pidgin Nigeriano](../pcm/README.md) | [Norueguês](../no/README.md) | [Persa (Farsi)](../fa/README.md) | [Polonês](../pl/README.md) | [Português (Brasil)](./README.md) | [Português (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romeno](../ro/README.md) | [Russo](../ru/README.md) | [Sérvio (Cirílico)](../sr/README.md) | [Eslovaco](../sk/README.md) | [Esloveno](../sl/README.md) | [Espanhol](../es/README.md) | [Suaíli](../sw/README.md) | [Sueco](../sv/README.md) | [Tagalo (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Tailandês](../th/README.md) | [Turco](../tr/README.md) | [Ucraniano](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamita](../vi/README.md)

> **Prefere Clonar Localmente?**

> Este repositório inclui mais de 50 traduções de idiomas, o que aumenta significativamente o tamanho do download. Para clonar sem traduções, use o checkout esparso:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Isso te dá tudo que precisa para completar o curso com um download muito mais rápido.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## Visão Geral do Curso

Domine o Azure Developer CLI (azd) por meio de capítulos estruturados projetados para aprendizado progressivo. **Foco especial em implantação de aplicações de IA com integração Microsoft Foundry.**

### Por que este Curso é Essencial para Desenvolvedores Modernos

Baseado em insights da comunidade Microsoft Foundry no Discord, **45% dos desenvolvedores desejam usar AZD para workloads de IA** mas enfrentam desafios com:
- Arquiteturas complexas de IA com múltiplos serviços
- Melhores práticas para implantação de IA em produção  
- Integração e configuração de serviços Azure AI
- Otimização de custos para workloads de IA
- Resolução de problemas específicos de implantação em IA

### Objetivos de Aprendizado

Ao completar este curso estruturado, você irá:
- **Dominar os Fundamentos do AZD**: Conceitos principais, instalação e configuração
- **Implantar Aplicações de IA**: Usar AZD com serviços Microsoft Foundry
- **Implementar Infraestrutura como Código**: Gerenciar recursos Azure com templates Bicep
- **Solucionar Problemas de Implantação**: Resolver problemas comuns e depurar erros
- **Otimizar para Produção**: Segurança, scaling, monitoramento e gestão de custos
- **Construir Soluções Multi-Agente**: Implantar arquiteturas avançadas de IA

## 📚 Capítulos de Aprendizado

*Selecione seu caminho de aprendizado com base no nível de experiência e objetivos*

### 🚀 Capítulo 1: Fundamentos & Início Rápido
**Pré-requisitos**: Assinatura Azure, conhecimento básico de linha de comando  
**Duração**: 30-45 minutos  
**Complexidade**: ⭐

#### O que Você Vai Aprender
- Entender os fundamentos do Azure Developer CLI
- Instalar o AZD na sua plataforma
- Sua primeira implantação bem-sucedida

#### Recursos de Aprendizado
- **🎯 Comece Aqui**: [O que é Azure Developer CLI?](../..)
- **📖 Teoria**: [Noções básicas do AZD](docs/getting-started/azd-basics.md) - Conceitos principais e terminologia
- **⚙️ Configuração**: [Instalação & Configuração](docs/getting-started/installation.md) - Guias específicos por plataforma
- **🛠️ Prático**: [Seu Primeiro Projeto](docs/getting-started/first-project.md) - Tutorial passo a passo
- **📋 Referência Rápida**: [Resumo de Comandos](resources/cheat-sheet.md)

#### Exercícios Práticos
```bash
# Verificação rápida de instalação
azd version

# Implemente sua primeira aplicação
azd init --template todo-nodejs-mongo
azd up
```

**💡 Resultado do Capítulo**: Implantar com sucesso uma aplicação web simples no Azure usando AZD

**✅ Validação de Sucesso:**
```bash
# Após completar o Capítulo 1, você deve ser capaz de:
azd version              # Mostra a versão instalada
azd init --template todo-nodejs-mongo  # Inicializa o projeto
azd up                  # Realiza o deploy para o Azure
azd show                # Exibe a URL do aplicativo em execução
# Aplicativo abre no navegador e funciona
azd down --force --purge  # Limpa os recursos
```

**📊 Tempo Investido:** 30-45 minutos  
**📈 Nível de Habilidade Após:** Capacidade de implantar aplicações básicas de forma independente

**✅ Validação de Sucesso:**
```bash
# Após completar o Capítulo 1, você deverá ser capaz de:
azd version              # Mostra a versão instalada
azd init --template todo-nodejs-mongo  # Inicializa o projeto
azd up                  # Realiza o deploy para o Azure
azd show                # Exibe a URL do app em execução
# Aplicação abre no navegador e funciona
azd down --force --purge  # Limpa os recursos
```

**📊 Tempo Investido:** 30-45 minutos  
**📈 Nível de Habilidade Após:** Capacidade de implantar aplicações básicas de forma independente

---

### 🤖 Capítulo 2: Desenvolvimento com Foco em IA (Recomendado para Desenvolvedores de IA)
**Pré-requisitos**: Capítulo 1 concluído  
**Duração**: 1-2 horas  
**Complexidade**: ⭐⭐

#### O que Você Vai Aprender
- Integração Microsoft Foundry com AZD
- Implantação de aplicações com IA
- Entender configurações de serviços de IA

#### Recursos de Aprendizado
- **🎯 Comece Aqui**: [Integração Microsoft Foundry](docs/microsoft-foundry/microsoft-foundry-integration.md)
- **📖 Padrões**: [Implantação de Modelos de IA](docs/microsoft-foundry/ai-model-deployment.md) - Implantar e gerenciar modelos de IA
- **🛠️ Oficina**: [Laboratório de IA](docs/microsoft-foundry/ai-workshop-lab.md) - Prepare suas soluções de IA para AZD
- **🎥 Guia Interativo**: [Materiais da Oficina](workshop/README.md) - Aprendizado via navegador com MkDocs * Ambiente DevContainer
- **📋 Modelos**: [Templates Microsoft Foundry](../..)
- **📝 Exemplos**: [Exemplos de Implantação AZD](examples/README.md)

#### Exercícios Práticos
```bash
# Implante sua primeira aplicação de IA
azd init --template azure-search-openai-demo
azd up

# Experimente modelos adicionais de IA
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```

**💡 Resultado do Capítulo**: Implantar e configurar um chat alimentado por IA com capacidades RAG

**✅ Validação de Sucesso:**
```bash
# Após o Capítulo 2, você deverá ser capaz de:
azd init --template azure-search-openai-demo
azd up
# Testar a interface de chat da IA
# Fazer perguntas e obter respostas com IA com fontes
# Verificar se a integração de busca funciona
azd monitor  # Checar se o Application Insights mostra telemetria
azd down --force --purge
```

**📊 Tempo Investido:** 1-2 horas  
**📈 Nível de Habilidade Após:** Capaz de implantar e configurar aplicações de IA prontas para produção  
**💰 Consciência de Custos:** Entender custos de desenvolvimento $80-150/mês, produção $300-3500/mês

#### 💰 Considerações de Custo para Implantações de IA

**Ambiente de Desenvolvimento (Estimado $80-150/mês):**
- Azure OpenAI (Pagamento conforme uso): $0-50/mês (baseado no uso de tokens)
- AI Search (Camada básica): $75/mês
- Container Apps (Consumo): $0-20/mês
- Storage (Padrão): $1-5/mês

**Ambiente de Produção (Estimado $300-3.500+/mês):**
- Azure OpenAI (PTU para performance consistente): $3.000+/mês OU Pagamento conforme uso com volume alto
- AI Search (Camada padrão): $250/mês
- Container Apps (Dedicado): $50-100/mês
- Application Insights: $5-50/mês
- Storage (Premium): $10-50/mês

**💡 Dicas de Otimização de Custos:**
- Use a camada **Free Tier** do Azure OpenAI para aprendizado (50.000 tokens/mês incluídos)
- Execute `azd down` para desalocar recursos quando não estiver desenvolvendo ativamente
- Comece com faturamento por consumo, faça upgrade para PTU apenas na produção
- Use `azd provision --preview` para estimar custos antes da implantação
- Ative auto-scaling: pague só pelo uso real

**Monitoramento de Custos:**
```bash
# Verificar custos mensais estimados
azd provision --preview

# Monitorar custos reais no Portal do Azure
az consumption budget list --resource-group <your-rg>
```

---

### ⚙️ Capítulo 3: Configuração & Autenticação
**Pré-requisitos**: Capítulo 1 concluído  
**Duração**: 45-60 minutos  
**Complexidade**: ⭐⭐

#### O que Você Vai Aprender
- Configuração e gerenciamento de ambientes
- Autenticação e melhores práticas de segurança
- Nomeação e organização de recursos

#### Recursos de Aprendizado
- **📖 Configuração**: [Guia de Configuração](docs/getting-started/configuration.md) - Preparação do ambiente
- **🔐 Segurança**: [Padrões de autenticação e identidade gerenciada](docs/getting-started/authsecurity.md) - Padrões de autenticação
- **📝 Exemplos**: [Exemplo de Aplicativo de Banco de Dados](examples/database-app/README.md) - Exemplos AZD com banco de dados

#### Exercícios Práticos
- Configurar múltiplos ambientes (dev, staging, prod)
- Configurar autenticação com identidade gerenciada
- Implementar configurações específicas para ambiente

**💡 Resultado do Capítulo**: Gerenciar múltiplos ambientes com autenticação e segurança adequadas

---

### 🏗️ Capítulo 4: Infraestrutura como Código & Implantação
**Pré-requisitos**: Capítulos 1-3 concluídos  
**Duração**: 1-1,5 horas  
**Complexidade**: ⭐⭐⭐

#### O que Você Vai Aprender
- Padrões avançados de implantação
- Infraestrutura como Código com Bicep
- Estratégias de provisionamento de recursos

#### Recursos de Aprendizado
- **📖 Implantação**: [Guia de Implantação](docs/deployment/deployment-guide.md) - Fluxos de trabalho completos
- **🏗️ Provisionamento**: [Provisionamento de Recursos](docs/deployment/provisioning.md) - Gerenciamento de recursos Azure
- **📝 Exemplos**: [Exemplo de Container App](../../examples/container-app) - Implantações conteinerizadas

#### Exercícios Práticos
- Criar templates Bicep personalizados
- Implantar aplicações multi-serviço
- Implementar estratégias de implantação blue-green

**💡 Resultado do Capítulo**: Implantar aplicações multi-serviço complexas usando templates personalizados de infraestrutura

---
### 🎯 Capítulo 5: Soluções de IA Multiagente (Avançado)
**Pré-requisitos**: Capítulos 1-2 concluídos  
**Duração**: 2-3 horas  
**Complexidade**: ⭐⭐⭐⭐

#### O Que Você Vai Aprender
- Padrões de arquitetura multiagente
- Orquestração e coordenação de agentes
- Implantações de IA prontas para produção

#### Recursos de Aprendizado
- **🤖 Projeto em Destaque**: [Solução Multiagente para Varejo](examples/retail-scenario.md) - Implementação completa
- **🛠️ Templates ARM**: [Pacote de Template ARM](../../examples/retail-multiagent-arm-template) - Implantação com um clique
- **📖 Arquitetura**: [Padrões de Coordenação Multiagente](/docs/pre-deployment/coordination-patterns.md) - Padrões

#### Exercícios Práticos
```bash
# Implante a solução completa de múltiplos agentes para varejo
cd examples/retail-multiagent-arm-template
./deploy.sh

# Explore as configurações dos agentes
az deployment group show --resource-group <rg-name> --name <deployment-name>
```

**💡 Resultado do Capítulo**: Implantar e gerenciar uma solução de IA multiagente pronta para produção com agentes de Cliente e Inventário

---

### 🔍 Capítulo 6: Validação e Planejamento Pré-Implantação
**Pré-requisitos**: Capítulo 4 concluído  
**Duração**: 1 hora  
**Complexidade**: ⭐⭐

#### O Que Você Vai Aprender
- Planejamento de capacidade e validação de recursos
- Estratégias de seleção de SKU
- Verificações prévias e automação

#### Recursos de Aprendizado
- **📊 Planejamento**: [Planejamento de Capacidade](docs/pre-deployment/capacity-planning.md) - Validação de recursos
- **💰 Seleção**: [Seleção de SKU](docs/pre-deployment/sku-selection.md) - Escolhas econômicas
- **✅ Validação**: [Verificações Prévias](docs/pre-deployment/preflight-checks.md) - Scripts automatizados

#### Exercícios Práticos
- Executar scripts de validação de capacidade
- Otimizar seleções de SKU para custo
- Implementar verificações pré-implantação automatizadas

**💡 Resultado do Capítulo**: Validar e otimizar implantações antes da execução

---

### 🚨 Capítulo 7: Solução de Problemas e Depuração
**Pré-requisitos**: Qualquer capítulo de implantação concluído  
**Duração**: 1-1.5 horas  
**Complexidade**: ⭐⭐

#### O Que Você Vai Aprender
- Abordagens sistemáticas de depuração
- Problemas comuns e soluções
- Solução de problemas específica para IA

#### Recursos de Aprendizado
- **🔧 Problemas Comuns**: [Problemas Comuns](docs/troubleshooting/common-issues.md) - FAQ e soluções
- **🕵️ Depuração**: [Guia de Depuração](docs/troubleshooting/debugging.md) - Estratégias passo a passo
- **🤖 Problemas de IA**: [Solução de Problemas para IA](docs/troubleshooting/ai-troubleshooting.md) - Problemas de serviços de IA

#### Exercícios Práticos
- Diagnosticar falhas de implantação
- Resolver problemas de autenticação
- Depurar conectividade de serviços de IA

**💡 Resultado do Capítulo**: Diagnosticar e resolver independentemente problemas comuns de implantação

---

### 🏢 Capítulo 8: Padrões de Produção e Empresariais
**Pré-requisitos**: Capítulos 1-4 concluídos  
**Duração**: 2-3 horas  
**Complexidade**: ⭐⭐⭐⭐

#### O Que Você Vai Aprender
- Estratégias de implantação para produção
- Padrões de segurança empresarial
- Monitoramento e otimização de custos

#### Recursos de Aprendizado
- **🏭 Produção**: [Melhores Práticas de IA para Produção](docs/microsoft-foundry/production-ai-practices.md) - Padrões empresariais
- **📝 Exemplos**: [Exemplo Microservices](../../examples/microservices) - Arquiteturas complexas
- **📊 Monitoramento**: [Integração com Application Insights](docs/pre-deployment/application-insights.md) - Monitoramento

#### Exercícios Práticos
- Implementar padrões de segurança empresarial
- Configurar monitoramento abrangente
- Implantar em produção com governança adequada

**💡 Resultado do Capítulo**: Implantar aplicações prontas para o ambiente empresarial com capacidades completas de produção

---

## 🎓 Visão Geral do Workshop: Experiência Prática de Aprendizado

> **⚠️ STATUS DO WORKSHOP: Desenvolvimento Ativo**  
> Os materiais do workshop estão sendo desenvolvidos e refinados. Módulos principais estão funcionais, mas algumas seções avançadas ainda estão incompletas. Estamos trabalhando ativamente para concluir todo o conteúdo. [Acompanhe o progresso →](workshop/README.md)

### Materiais Interativos do Workshop
**Aprendizado prático e completo com ferramentas baseadas no navegador e exercícios guiados**

Nossos materiais oferecem uma experiência estruturada e interativa que complementa o currículo baseado nos capítulos acima. O workshop é projetado para aprendizado autônomo e sessões conduzidas por instrutores.

#### 🛠️ Funcionalidades do Workshop
- **Interface Baseada no Navegador**: Workshop completo com MkDocs, com pesquisa, cópia e temas
- **Integração com GitHub Codespaces**: Configuração de ambiente de desenvolvimento com um clique
- **Caminho Estruturado de Aprendizagem**: Exercícios guiados em 7 etapas (3.5 horas no total)
- **Descoberta → Implantação → Customização**: Metodologia progressiva
- **Ambiente DevContainer Interativo**: Ferramentas e dependências pré-configuradas

#### 📚 Estrutura do Workshop
O workshop segue a metodologia **Descoberta → Implantação → Customização**:

1. **Fase de Descoberta** (45 minutos)
   - Explorar templates e serviços Microsoft Foundry
   - Entender padrões de arquitetura multiagente
   - Revisar requisitos e pré-requisitos de implantação

2. **Fase de Implantação** (2 horas)
   - Implantação prática de aplicações de IA com AZD
   - Configurar serviços e endpoints de IA no Azure
   - Implementar padrões de segurança e autenticação

3. **Fase de Customização** (45 minutos)
   - Modificar aplicações para casos específicos
   - Otimizar para implantação em produção
   - Implementar monitoramento e controle de custos

#### 🚀 Começando o Workshop
```bash
# Opção 1: GitHub Codespaces (Recomendado)
# Clique em "Code" → "Create codespace on main" no repositório

# Opção 2: Desenvolvimento Local
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# Siga as instruções de configuração em workshop/README.md
```

#### 🎯 Resultados de Aprendizado do Workshop
Ao concluir o workshop, os participantes irão:
- **Implantar Aplicações de IA para Produção**: Usar AZD com serviços Microsoft Foundry
- **Dominar Arquiteturas Multiagente**: Implementar soluções coordenadas de agentes de IA
- **Implementar Melhores Práticas de Segurança**: Configurar autenticação e controle de acesso
- **Otimizar para Escalabilidade**: Projetar implantações econômicas e performáticas
- **Resolver Problemas de Implantação**: Diagnosticar e solucionar problemas comuns autonomamente

#### 📖 Recursos do Workshop
- **🎥 Guia Interativo**: [Materiais do Workshop](workshop/README.md) - Ambiente de aprendizado baseado no navegador
- **📋 Instruções Passo a Passo**: [Exercícios Guiados](../../workshop/docs/instructions) - Orientações detalhadas
- **🛠️ Laboratório de IA no Workshop**: [Laboratório de IA](docs/microsoft-foundry/ai-workshop-lab.md) - Exercícios focados em IA
- **💡 Início Rápido**: [Guia de Configuração do Workshop](workshop/README.md#quick-start) - Configuração do ambiente

**Perfeito para**: Treinamento corporativo, cursos universitários, aprendizado autodidata e bootcamps para desenvolvedores.

---

## 📖 O que é Azure Developer CLI?

Azure Developer CLI (azd) é uma interface de linha de comando focada no desenvolvedor que acelera o processo de criação e implantação de aplicações no Azure. Ela oferece:

- **Implantações baseadas em templates** - Use templates pré-construídos para padrões comuns de aplicação
- **Infraestrutura como Código** - Gerencie recursos Azure usando Bicep ou Terraform  
- **Fluxos de trabalho integrados** - Provisionar, implantar e monitorar aplicações sem falhas
- **Focado em desenvolvedores** - Otimizado para produtividade e experiência do desenvolvedor

### **AZD + Microsoft Foundry: Perfeito para Implantações de IA**

**Por que AZD para Soluções de IA?** AZD resolve os principais desafios enfrentados por desenvolvedores de IA:

- **Templates prontos para IA** - Templates pré-configurados para Azure OpenAI, Serviços Cognitivos e cargas de trabalho ML
- **Implantações seguras de IA** - Padrões de segurança incorporados para serviços de IA, chaves API e endpoints de modelo  
- **Padrões de IA para Produção** - Melhores práticas para implantações escaláveis e econômicas de aplicações de IA
- **Fluxos de trabalho de IA de ponta a ponta** - Do desenvolvimento do modelo à implantação em produção com monitoramento adequado
- **Otimização de custos** - Alocação inteligente de recursos e estratégias de escalonamento para cargas de trabalho de IA
- **Integração Microsoft Foundry** - Conexão perfeita ao catálogo de modelos e endpoints Microsoft Foundry

---

## 🎯 Biblioteca de Templates & Exemplos

### Em Destaque: Templates Microsoft Foundry
**Comece aqui se você está implantando aplicações de IA!**

> **Nota:** Estes templates demonstram vários padrões de IA. Alguns são Azure Samples externos, outros são implementações locais.

| Template | Capítulo | Complexidade | Serviços | Tipo |
|----------|---------|------------|----------|------|
| [**Get started with AI chat**](https://github.com/Azure-Samples/get-started-with-ai-chat) | Capítulo 2 | ⭐⭐ | AzureOpenAI + Azure AI Model Inference API + Azure AI Search + Azure Container Apps + Application Insights | Externo |
| [**Get started with AI agents**](https://github.com/Azure-Samples/get-started-with-ai-agents) | Capítulo 2 | ⭐⭐ | Azure AI Agent Service + AzureOpenAI + Azure AI Search + Azure Container Apps + Application Insights| Externo |
| [**Azure Search + OpenAI Demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Capítulo 2 | ⭐⭐ | AzureOpenAI + Azure AI Search + App Service + Storage | Externo |
| [**OpenAI Chat App Quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Capítulo 2 | ⭐ | AzureOpenAI + Container Apps + Application Insights | Externo |
| [**Agent OpenAI Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Capítulo 5 | ⭐⭐⭐ | AzureOpenAI + Azure Functions + Prompty | Externo |
| [**Contoso Chat RAG**](https://github.com/Azure-Samples/contoso-chat) | Capítulo 8 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Cosmos DB + Container Apps | Externo |
| [**Retail Multi-Agent Solution**](examples/retail-scenario.md) | Capítulo 5 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Storage + Container Apps + Cosmos DB | **Local** |

### Em Destaque: Cenários Completos de Aprendizado
**Templates de aplicação prontos para produção mapeados para capítulos de aprendizado**

| Template | Capítulo de Aprendizado | Complexidade | Aprendizado Principal |
|----------|------------------|------------|--------------|
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Capítulo 2 | ⭐ | Padrões básicos de implantação de IA |
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Capítulo 2 | ⭐⭐ | Implementação RAG com Azure AI Search |
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | Capítulo 4 | ⭐⭐ | Integração de Inteligência Documental |
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Capítulo 5 | ⭐⭐⭐ | Framework de agentes e chamadas de função |
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | Capítulo 8 | ⭐⭐⭐ | Orquestração empresarial de IA |
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | Capítulo 5 | ⭐⭐⭐⭐ | Arquitetura multiagente com agentes Cliente e Inventário |

### Aprendizado por Tipo de Exemplo

> **📌 Exemplos Locais vs. Externos:**  
> **Exemplos Locais** (neste repositório) = Prontos para uso imediato  
> **Exemplos Externos** (Azure Samples) = Clonar dos repositórios vinculados

#### Exemplos Locais (Prontos para Uso)
- [**Solução Multiagente para Varejo**](examples/retail-scenario.md) - Implementação completa pronta para produção com templates ARM
  - Arquitetura multiagente (agentes Cliente + Inventário)
  - Monitoramento e avaliação abrangentes
  - Implantação com um clique via template ARM

#### Exemplos Locais - Aplicações em Contêineres (Capítulos 2-5)
**Exemplos completos de implantação de contêineres neste repositório:**
- [**Exemplos de Aplicações em Contêiner**](examples/container-app/README.md) - Guia completo para implantações conteinerizadas
  - [API Flask Simples](../../examples/container-app/simple-flask-api) - API REST básica com scale-to-zero
  - [Arquitetura de Microservices](../../examples/container-app/microservices) - Implantação multi-serviço pronta para produção
  - Padrões Rápido Início, Produção e Avançado
  - Guia de monitoramento, segurança e otimização de custos

#### Exemplos Externos - Aplicações Simples (Capítulos 1-2)
**Clone esses repositórios Azure Samples para começar:**
- [Aplicação Web Simples - Node.js + MongoDB](https://github.com/Azure-Samples/todo-nodejs-mongo) - Padrões básicos de implantação
- [Site Estático - React SPA](https://github.com/Azure-Samples/todo-csharp-sql-swa-func) - Implantação de conteúdo estático
- [Aplicação em Contêiner - Python Flask](https://github.com/Azure-Samples/container-apps-store-api-microservice) - Implantação API REST

#### Exemplos Externos - Integração com Banco de Dados (Capítulos 3-4)  
- [Aplicação de Banco de Dados - C# + SQL](https://github.com/Azure-Samples/todo-csharp-sql) - Padrões de conectividade com banco de dados
- [Functions + Cosmos DB](https://github.com/Azure-Samples/todo-python-mongo-swa-func) - Workflow de dados serverless

#### Exemplos Externos - Padrões Avançados (Capítulos 4-8)
- [Microservices Java](https://github.com/Azure-Samples/java-microservices-aca-lab) - Arquiteturas multi-serviço
- [Jobs em Container Apps](https://github.com/Azure-Samples/container-apps-jobs) - Processamento em segundo plano  
- [Pipeline ML Empresarial](https://github.com/Azure-Samples/mlops-v2) - Padrões ML prontos para produção

### Coleções de Templates Externos
- [**Galeria Oficial de Modelos AZD**](https://azure.github.io/awesome-azd/) - Coleção selecionada de modelos oficiais e da comunidade
- [**Modelos do Azure Developer CLI**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - Documentação de modelos do Microsoft Learn
- [**Diretório de Exemplos**](examples/README.md) - Exemplos locais de aprendizado com explicações detalhadas

---

## 📚 Recursos de Aprendizado & Referências

### Referências Rápidas
- [**Resumo de Comandos**](resources/cheat-sheet.md) - Comandos essenciais do azd organizados por capítulo
- [**Glossário**](resources/glossary.md) - Terminologia Azure e azd  
- [**Perguntas Frequentes (FAQ)**](resources/faq.md) - Perguntas comuns organizadas por capítulo de aprendizado
- [**Guia de Estudos**](resources/study-guide.md) - Exercícios práticos abrangentes

### Oficinas Práticas
- [**Laboratório de Oficina de IA**](docs/microsoft-foundry/ai-workshop-lab.md) - Torne suas soluções de IA implantáveis via AZD (2-3 horas)
- [**Guia Interativo da Oficina**](workshop/README.md) - Oficina baseada em navegador com MkDocs e Ambiente DevContainer
- [**Caminho de Aprendizado Estruturado**](../../workshop/docs/instructions) - Exercícios guiados em 7 etapas (Descoberta → Implantação → Customização)
- [**Oficina AZD para Iniciantes**](workshop/README.md) - Materiais completos de oficina prática com integração GitHub Codespaces

### Recursos Externos de Aprendizado
- Documentação do Azure Developer CLI: https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/
- Centro de Arquitetura Azure: https://learn.microsoft.com/en-us/azure/architecture/
- Calculadora de Preços Azure: https://azure.microsoft.com/pricing/calculator/
- Status Azure: https://status.azure.com/

---

## 🔧 Guia Rápido de Solução de Problemas

**Problemas comuns enfrentados por iniciantes e soluções imediatas:**

### ❌ "azd: command not found"

```bash
# Instale o AZD primeiro
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Verifique a instalação
azd version
```

### ❌ "Nenhuma assinatura encontrada" ou "Assinatura não definida"

```bash
# Listar assinaturas disponíveis
az account list --output table

# Definir assinatura padrão
az account set --subscription "<subscription-id-or-name>"

# Definir para ambiente AZD
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Verificar
az account show
```

### ❌ "Cota insuficiente" ou "Cota excedida"

```bash
# Tente diferentes regiões do Azure
azd env set AZURE_LOCATION "westus2"
azd up

# Ou use SKUs menores no desenvolvimento
# Edite infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```

### ❌ "azd up" falha na metade do processo

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

### ❌ "Autenticação falhou" ou "Token expirado"

```bash
# Reautenticar
az logout
az login

azd auth logout
azd auth login

# Verificar autenticação
az account show
```

### ❌ "Recurso já existe" ou conflitos de nomeação

```bash
# AZD gera nomes únicos, mas em caso de conflito:
azd down --force --purge

# Então tente novamente com um ambiente novo
azd env new dev-v2
azd up
```

### ❌ Implantação do modelo levando muito tempo

**Tempos normais de espera:**
- Aplicativo web simples: 5-10 minutos
- Aplicativo com banco de dados: 10-15 minutos
- Aplicações de IA: 15-25 minutos (Provisionamento OpenAI é lento)

```bash
# Verificar progresso
azd show

# Se estiver travado por mais de 30 minutos, verifique o Portal do Azure:
azd monitor
# Procure por implantações falhadas
```

### ❌ "Permissão negada" ou "Proibido"

```bash
# Verifique seu papel no Azure
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Você precisa pelo menos da função "Colaborador"
# Peça ao administrador do Azure que conceda:
# - Colaborador (para recursos)
# - Administrador de Acesso de Usuário (para atribuições de função)
```

### ❌ Não consegue encontrar URL da aplicação implantada

```bash
# Mostrar todos os pontos de extremidade do serviço
azd show

# Ou abrir o Portal do Azure
azd monitor

# Verificar serviço específico
azd env get-values
# Procurar variáveis *_URL
```

### 📚 Recursos completos de solução de problemas

- **Guia de Problemas Comuns:** [Soluções Detalhadas](docs/troubleshooting/common-issues.md)
- **Problemas Específicos de IA:** [Solução de Problemas de IA](docs/troubleshooting/ai-troubleshooting.md)
- **Guia de Depuração:** [Depuração passo a passo](docs/troubleshooting/debugging.md)
- **Obtenha Ajuda:** [Discord do Azure](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🔧 Guia Rápido de Solução de Problemas

**Problemas comuns enfrentados por iniciantes e soluções imediatas:**

<details>
<summary><strong>❌ "azd: command not found"</strong></summary>

```bash
# Instale o AZD primeiro
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
<summary><strong>❌ "Nenhuma assinatura encontrada" ou "Assinatura não definida"</strong></summary>

```bash
# Listar assinaturas disponíveis
az account list --output table

# Definir assinatura padrão
az account set --subscription "<subscription-id-or-name>"

# Definir para ambiente AZD
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Verificar
az account show
```
</details>

<details>
<summary><strong>❌ "Cota insuficiente" ou "Cota excedida"</strong></summary>

```bash
# Tente diferentes regiões do Azure
azd env set AZURE_LOCATION "westus2"
azd up

# Ou use SKUs menores no desenvolvimento
# Edite infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>

<details>
<summary><strong>❌ "azd up" falha na metade do processo</strong></summary>

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
<summary><strong>❌ "Autenticação falhou" ou "Token expirado"</strong></summary>

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
<summary><strong>❌ "Recurso já existe" ou conflitos de nomeação</strong></summary>

```bash
# AZD gera nomes únicos, mas se houver conflito:
azd down --force --purge

# Então tente novamente com um ambiente novo
azd env new dev-v2
azd up
```
</details>

<details>
<summary><strong>❌ Implantação do modelo levando muito tempo</strong></summary>

**Tempos normais de espera:**
- Aplicativo web simples: 5-10 minutos
- Aplicativo com banco de dados: 10-15 minutos
- Aplicações de IA: 15-25 minutos (Provisionamento OpenAI é lento)

```bash
# Verificar progresso
azd show

# Se estiver travado >30 minutos, verifique o Portal do Azure:
azd monitor
# Procure por implantações com falha
```
</details>

<details>
<summary><strong>❌ "Permissão negada" ou "Proibido"</strong></summary>

```bash
# Verifique sua função no Azure
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Você precisa de pelo menos a função "Colaborador"
# Peça ao seu administrador Azure para conceder:
# - Colaborador (para recursos)
# - Administrador de Acesso de Usuário (para atribuições de função)
```
</details>

<details>
<summary><strong>❌ Não consegue encontrar URL da aplicação implantada</strong></summary>

```bash
# Mostrar todos os pontos de extremidade do serviço
azd show

# Ou abrir o Portal do Azure
azd monitor

# Verificar serviço específico
azd env get-values
# Procure por variáveis *_URL
```
</details>

### 📚 Recursos completos de solução de problemas

- **Guia de Problemas Comuns:** [Soluções Detalhadas](docs/troubleshooting/common-issues.md)
- **Problemas Específicos de IA:** [Solução de Problemas de IA](docs/troubleshooting/ai-troubleshooting.md)
- **Guia de Depuração:** [Depuração passo a passo](docs/troubleshooting/debugging.md)
- **Obtenha Ajuda:** [Discord do Azure](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🎓 Conclusão do Curso & Certificação

### Rastreamento de Progresso
Acompanhe seu progresso de aprendizado em cada capítulo:

- [ ] **Capítulo 1**: Fundamentos & Início Rápido ✅
- [ ] **Capítulo 2**: Desenvolvimento AI-First ✅  
- [ ] **Capítulo 3**: Configuração & Autenticação ✅
- [ ] **Capítulo 4**: Infraestrutura como Código & Implantação ✅
- [ ] **Capítulo 5**: Soluções Multi-Agentes de IA ✅
- [ ] **Capítulo 6**: Validação & Planejamento Pré-Implantação ✅
- [ ] **Capítulo 7**: Resolução de Problemas & Debugging ✅
- [ ] **Capítulo 8**: Padrões de Produção & Empresariais ✅

### Verificação do Aprendizado
Após completar cada capítulo, verifique seu conhecimento:
1. **Exercício Prático**: Complete a implantação prática do capítulo
2. **Checagem de Conhecimento**: Revise a seção FAQ do seu capítulo
3. **Discussão Comunitária**: Compartilhe sua experiência no Discord do Azure
4. **Próximo Capítulo**: Avance para o próximo nível de complexidade

### Benefícios da Conclusão do Curso
Ao completar todos os capítulos, você terá:
- **Experiência em Produção**: Aplicações reais de IA implantadas no Azure
- **Habilidades Profissionais**: Capacidades de implantação prontas para o ambiente empresarial  
- **Reconhecimento na Comunidade**: Membro ativo da comunidade de desenvolvedores Azure
- **Avanço na Carreira**: Expertise requisitada em AZD e implantação de IA

---

## 🤝 Comunidade & Suporte

### Obtenha Ajuda & Suporte
- **Problemas Técnicos**: [Reporte bugs e solicite recursos](https://github.com/microsoft/azd-for-beginners/issues)
- **Dúvidas de Aprendizado**: [Comunidade Discord Microsoft Azure](https://discord.gg/microsoft-azure) e [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **Ajuda Específica de IA**: Participe do [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **Documentação**: [Documentação oficial do Azure Developer CLI](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)

### Insights da Comunidade do Microsoft Foundry Discord

**Resultados recentes da enquete no canal #Azure:**
- **45%** dos desenvolvedores querem usar AZD para cargas de trabalho de IA
- **Principais desafios**: implantações multi-serviços, gerenciamento de credenciais, prontidão para produção  
- **Mais solicitados**: modelos específicos de IA, guias de solução de problemas, melhores práticas

**Junte-se à nossa comunidade para:**
- Compartilhar suas experiências com AZD + IA e obter ajuda
- Acessar prévias antecipadas de novos modelos de IA
- Contribuir para melhores práticas de implantação de IA
- Influenciar o desenvolvimento futuro de recursos de IA + AZD

### Contribuindo para o Curso
Recebemos contribuições! Por favor, leia nosso [Guia de Contribuição](CONTRIBUTING.md) para detalhes sobre:
- **Melhorias de Conteúdo**: Aprimore capítulos e exemplos existentes
- **Novos Exemplos**: Adicione cenários e modelos do mundo real  
- **Tradução**: Ajude a manter suporte multilíngue
- **Relatos de Bugs**: Melhore a precisão e clareza
- **Padrões Comunitários**: Siga nossas diretrizes inclusivas para a comunidade

---

## 📄 Informações do Curso

### Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](../../LICENSE) para detalhes.

### Recursos de Aprendizado Microsoft Relacionados

Nossa equipe produz outros cursos abrangentes de aprendizado:

<!-- CO-OP TRANSLATOR OTHER COURSES START -->
### LangChain
[![LangChain4j para Iniciantes](https://img.shields.io/badge/LangChain4j%20for%20Beginners-22C55E?style=for-the-badge&&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchain4j-for-beginners)
[![LangChain.js para Iniciantes](https://img.shields.io/badge/LangChain.js%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchainjs-for-beginners?WT.mc_id=m365-94501-dwahlin)

---

### Azure / Edge / MCP / Agentes
[![AZD para Iniciantes](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Edge AI para Iniciantes](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![MCP para Iniciantes](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Agentes de IA para Iniciantes](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Série de IA Generativa
[![IA Generativa para Iniciantes](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![IA Generativa (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
[![IA Generativa (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)
[![IA Generativa (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---
 
### Aprendizado Básico
[![ML para Iniciantes](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![Ciência de Dados para Iniciantes](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![IA para Iniciantes](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Cibersegurança para Iniciantes](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Desenvolvimento Web para Iniciantes](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![IoT para Iniciantes](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![Desenvolvimento XR para Iniciantes](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Série Copilot
[![Copilot para Programação em Par com IA](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![Copilot para C#/.NET](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Aventura Copilot](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ Navegação do Curso

**🚀 Pronto para Começar a Aprender?**

**Iniciantes**: Comece com [Capítulo 1: Fundamentos & Início Rápido](../..)  
**Desenvolvedores de IA**: Vá para [Capítulo 2: Desenvolvimento AI-First](../..)  
**Desenvolvedores Experientes**: Comece com [Capítulo 3: Configuração & Autenticação](../..)

**Próximos Passos**: [Iniciar Capítulo 1 - Noções básicas do AZD](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Aviso Legal**:  
Este documento foi traduzido utilizando o serviço de tradução automática [Co-op Translator](https://github.com/Azure/co-op-translator). Embora nos esforcemos para garantir a precisão, esteja ciente de que traduções automáticas podem conter erros ou imprecisões. O documento original em seu idioma nativo deve ser considerado a fonte autoritativa. Para informações críticas, recomenda-se a tradução profissional realizada por humanos. Não nos responsabilizamos por quaisquer mal-entendidos ou interpretações incorretas decorrentes do uso desta tradução.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->