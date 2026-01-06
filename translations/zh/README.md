<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T12:44:19+00:00",
  "source_file": "README.md",
  "language_code": "zh"
}
-->
> 注意：本文档会持续更新以反映最新变化。

> ⚠️ 本仓库是一个演示，用于展示使用 Localizeflow 实现自动化文档本地化。
>
> 原始内容基于微软的 “AZD for Beginners” 项目。

# AZD 初学者指南：结构化学习旅程

![AZD-for-beginners](../../translated_images/azdbeginners.5527441dd9f74068.zh.png) 

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## 开始本课程

按照以下步骤开始您的 AZD 学习之旅：

1. **Fork 仓库**：点击 [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)
2. **克隆仓库**：`git clone https://github.com/microsoft/azd-for-beginners.git`
3. **加入社区**：[Azure Discord Communities](https://discord.com/invite/ByRwuEEgH4) 寻求专家支持
4. **选择学习路径**：从下方章节中选择符合您经验水平的内容

### 多语言支持

#### 自动翻译（始终保持最新）

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](./README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **更喜欢本地克隆？**

> 本仓库包含50多种语言翻译，显著增加了下载体积。若无需要翻译文件，建议使用稀疏检出：
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> 这样您可以获得完成课程所需的全部内容，且下载速度更快。
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## 课程概览

通过结构化的章节掌握 Azure Developer CLI (azd)，实现渐进式学习。**特别聚焦于借助 Microsoft Foundry 集成进行 AI 应用部署。**

### 为什么本课程是现代开发者的必修课

基于 Microsoft Foundry Discord 社区洞察，**有 45% 的开发者希望使用 AZD 处理 AI 工作负载**，但面临以下挑战：
- 复杂的多服务 AI 架构
- 生产环境 AI 部署最佳实践
- Azure AI 服务集成与配置
- AI 工作负载的成本优化
- AI 部署相关的故障排除

### 学习目标

完成本结构化课程后，您将能：
- **掌握 AZD 基础**：核心概念、安装及配置
- **部署 AI 应用**：结合 Microsoft Foundry 服务使用 AZD
- **实现基础设施即代码**：通过 Bicep 模板管理 Azure 资源
- **排查部署问题**：解决常见问题及调试
- **优化生产环境**：保障安全、扩展、监控及成本控制
- **构建多代理解决方案**：部署复杂 AI 架构

## 📚 学习章节

*根据经验水平和目标选择您的学习路径*

### 🚀 第1章：基础与快速入门
**前置条件**：拥有 Azure 订阅，具备基础命令行知识  
**时长**：30-45 分钟  
**难度**：⭐

#### 您将学习
- 理解 Azure Developer CLI 基础
- 在您的平台上安装 AZD
- 完成第一个成功部署

#### 学习资源
- **🎯 从这里开始**：[什么是 Azure Developer CLI？](../..)
- **📖 理论**：[AZD 基础](docs/getting-started/azd-basics.md) - 核心概念和术语
- **⚙️ 设置**：[安装与配置](docs/getting-started/installation.md) - 平台专用指南
- **🛠️ 实操**：[第一个项目](docs/getting-started/first-project.md) - 逐步教程
- **📋 快捷参考**：[命令速查表](resources/cheat-sheet.md)

#### 实践练习
```bash
# 快速安装检查
azd version

# 部署您的第一个应用程序
azd init --template todo-nodejs-mongo
azd up
```

**💡 章节成果**：使用 AZD 成功将一个简单的 Web 应用部署到 Azure

**✅ 成功验证：**
```bash
# 完成第一章后，您应该能够：
azd version              # 显示已安装的版本
azd init --template todo-nodejs-mongo  # 初始化项目
azd up                  # 部署到Azure
azd show                # 显示运行中的应用程序URL
# 应用程序在浏览器中打开并正常工作
azd down --force --purge  # 清理资源
```

**📊 时间投入：** 30-45 分钟  
**📈 完成后技能水平：** 可独立部署基本应用

**✅ 成功验证：**
```bash
# 完成第1章后，您应该能够：
azd version              # 显示已安装的版本
azd init --template todo-nodejs-mongo  # 初始化项目
azd up                  # 部署到Azure
azd show                # 显示正在运行的应用程序网址
# 应用程序在浏览器中打开并正常运行
azd down --force --purge  # 清理资源
```

**📊 时间投入：** 30-45 分钟  
**📈 完成后技能水平：** 可独立部署基本应用

---

### 🤖 第2章：AI 优先开发（推荐 AI 开发者）
**前置条件**：完成第1章  
**时长**：1-2 小时  
**难度**：⭐⭐

#### 您将学习
- Microsoft Foundry 与 AZD 的集成
- 部署 AI 驱动的应用程序
- 理解 AI 服务配置

#### 学习资源
- **🎯 从这里开始**：[Microsoft Foundry 集成](docs/microsoft-foundry/microsoft-foundry-integration.md)
- **📖 模式**：[AI 模型部署](docs/microsoft-foundry/ai-model-deployment.md) - 部署和管理 AI 模型
- **🛠️ 研讨会**：[AI 工作坊实验室](docs/microsoft-foundry/ai-workshop-lab.md) - 使您的 AI 解决方案适配 AZD
- **🎥 互动指南**：[研讨会资料](workshop/README.md) - 基于浏览器的 MkDocs * DevContainer 环境学习
- **📋 模板**：[Microsoft Foundry 模板](../..)
- **📝 示例**：[AZD 部署示例](examples/README.md)

#### 实践练习
```bash
# 部署你的第一个AI应用程序
azd init --template azure-search-openai-demo
azd up

# 试试更多的AI模板
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```

**💡 章节成果**：部署并配置具备 RAG 功能的 AI 驱动聊天应用

**✅ 成功验证：**
```bash
# 完成第2章后，您应该能够：
azd init --template azure-search-openai-demo
azd up
# 测试AI聊天界面
# 提出问题并获得带有来源的AI驱动响应
# 验证搜索集成是否正常
azd monitor  # 检查应用程序洞察是否显示遥测信息
azd down --force --purge
```

**📊 时间投入：** 1-2 小时  
**📈 完成后技能水平：** 可以部署和配置生产级 AI 应用  
**💰 费用认知：** 了解每月约 $80-150 的开发成本，生产环境 $300-3500 及以上成本

#### 💰 AI 部署的成本考虑

**开发环境（估计每月 $80-150）：**
- Azure OpenAI（按需付费）：$0-50/月（基于令牌使用量）
- AI 搜索（基础层）：$75/月
- 容器应用（按消费计费）：$0-20/月
- 存储（标准层）：$1-5/月

**生产环境（估计每月 $300-3500+）：**
- Azure OpenAI（PTU 保持性能一致）：$3,000+/月 或大批量按需付费
- AI 搜索（标准层）：$250/月
- 容器应用（专用层）：$50-100/月
- 应用洞察：$5-50/月
- 存储（高级层）：$10-50/月

**💡 成本优化建议：**
- 使用 **免费层** 的 Azure OpenAI 进行学习（每月包含 5 万令牌）
- 不开发时运行 `azd down` 释放资源
- 初期使用消费计费，生产环境再升级 PTU
- 使用 `azd provision --preview` 预估部署成本
- 启用自动扩缩容，只为实际使用付费

**费用监控：**
```bash
# 检查预计的每月费用
azd provision --preview

# 在 Azure 门户中监控实际费用
az consumption budget list --resource-group <your-rg>
```

---

### ⚙️ 第3章：配置与身份验证
**前置条件**：完成第1章  
**时长**：45-60 分钟  
**难度**：⭐⭐

#### 您将学习
- 环境配置与管理
- 身份验证与安全最佳实践
- 资源命名与组织规范

#### 学习资源
- **📖 配置**：[配置指南](docs/getting-started/configuration.md) - 环境设置
- **🔐 安全**：[身份验证模式和托管身份](docs/getting-started/authsecurity.md) - 身份验证模式
- **📝 示例**：[数据库应用示例](examples/database-app/README.md) - AZD 数据库示例

#### 实践练习
- 配置多个环境（开发、预发布、生产）
- 设置托管身份认证
- 实现环境特定配置

**💡 章节成果**：管理多环境，保障适当身份验证与安全性

---

### 🏗️ 第4章：基础设施即代码与部署
**前置条件**：完成第1-3章  
**时长**：1-1.5 小时  
**难度**：⭐⭐⭐

#### 您将学习
- 高级部署模式
- 通过 Bicep 实现基础设施即代码
- 资源配置策略

#### 学习资源
- **📖 部署**：[部署指南](docs/deployment/deployment-guide.md) - 完整工作流程
- **🏗️ 配置**：[资源配置](docs/deployment/provisioning.md) - Azure 资源管理
- **📝 示例**：[容器应用示例](../../examples/container-app) - 容器化部署

#### 实践练习
- 编写自定义 Bicep 模板
- 部署多服务应用
- 实现蓝绿部署策略

**💡 章节成果**：使用自定义基础设施模板部署复杂多服务应用

---
### 🎯 第五章：多代理 AI 解决方案（高级）
**先决条件**：完成第一至二章  
**时长**：2-3 小时  
**复杂度**：⭐⭐⭐⭐

#### 您将学习到
- 多代理架构模式
- 代理编排与协调
- 面向生产的 AI 部署

#### 学习资源
- **🤖 特色项目**：[零售多代理解决方案](examples/retail-scenario.md) - 完整实现
- **🛠️ ARM 模板**：[ARM 模板包](../../examples/retail-multiagent-arm-template) - 一键部署
- **📖 架构**：[多代理协调模式](/docs/pre-deployment/coordination-patterns.md) - 模式

#### 实践练习
```bash
# 部署完整的零售多智能体解决方案
cd examples/retail-multiagent-arm-template
./deploy.sh

# 探索智能体配置
az deployment group show --resource-group <rg-name> --name <deployment-name>
```

**💡 本章成果**：部署并管理具备客户和库存代理的生产级多代理 AI 解决方案

---

### 🔍 第六章：预部署验证与规划
**先决条件**：完成第四章  
**时长**：1 小时  
**复杂度**：⭐⭐

#### 您将学习到
- 容量规划与资源验证
- SKU 选择策略
- 预部署检查与自动化

#### 学习资源
- **📊 规划**：[容量规划](docs/pre-deployment/capacity-planning.md) - 资源验证
- **💰 选择**：[SKU 选择](docs/pre-deployment/sku-selection.md) - 高性价比选择
- **✅ 验证**：[预部署检查](docs/pre-deployment/preflight-checks.md) - 自动化脚本

#### 实践练习
- 运行容量验证脚本
- 优化 SKU 选择以降低成本
- 实现自动化的预部署检查

**💡 本章成果**：验证并优化部署方案，确保执行顺利

---

### 🚨 第七章：故障排查与调试
**先决条件**：完成任一部署章节  
**时长**：1-1.5 小时  
**复杂度**：⭐⭐

#### 您将学习到
- 系统化调试方法
- 常见问题及解决方案
- AI 特定故障排查

#### 学习资源
- **🔧 常见问题**：[常见问题](docs/troubleshooting/common-issues.md) - 常见问答与解决方案
- **🕵️ 调试**：[调试指南](docs/troubleshooting/debugging.md) - 逐步调试策略
- **🤖 AI 问题**：[AI 特定故障排查](docs/troubleshooting/ai-troubleshooting.md) - AI 服务问题

#### 实践练习
- 诊断部署失败原因
- 解决身份验证问题
- 调试 AI 服务连接

**💡 本章成果**：独立诊断并解决常见部署问题

---

### 🏢 第八章：生产及企业模式
**先决条件**：完成第一至四章  
**时长**：2-3 小时  
**复杂度**：⭐⭐⭐⭐

#### 您将学习到
- 生产部署策略
- 企业安全模式
- 监控与成本优化

#### 学习资源
- **🏭 生产**：[生产 AI 最佳实践](docs/microsoft-foundry/production-ai-practices.md) - 企业模式
- **📝 示例**：[微服务示例](../../examples/microservices) - 复杂架构
- **📊 监控**：[应用洞察整合](docs/pre-deployment/application-insights.md) - 监控

#### 实践练习
- 实施企业安全模式
- 建立全面监控
- 在合规治理下部署生产环境

**💡 本章成果**：部署具备完整生产能力的企业级应用

---

## 🎓 研讨会概览：动手学习体验

> **⚠️ 研讨会状态：开发中**  
> 研讨会材料正在开发和完善中。核心模块已可使用，但部分高级章节尚未完成。我们正积极推进所有内容完善。[查看进度 →](workshop/README.md)

### 交互式研讨会材料
**全面的浏览器工具与指导练习，提供互动学习体验**

研讨会材料为以上章节课程提供结构化、互动式学习体验，既适合自学也适合讲师授课。

#### 🛠️ 研讨会功能
- **基于浏览器界面**：完整的 MkDocs 支持研讨会，带搜索、复制和主题功能
- **GitHub Codespaces 集成**：一键搭建开发环境
- **结构化学习路径**：7 步指导练习（总时长 3.5 小时）
- **发现 → 部署 → 定制**：渐进式方法论
- **交互式 DevContainer 环境**：预装工具和依赖

#### 📚 研讨会结构
研讨会遵循**发现 → 部署 → 定制**方法：

1. **发现阶段**（45 分钟）
   - 探索 Microsoft Foundry 模板和服务
   - 理解多代理架构模式
   - 审核部署需求与先决条件

2. **部署阶段**（2 小时）
   - 使用 AZD 实践 AI 应用部署
   - 配置 Azure AI 服务与端点
   - 实施安全与认证模式

3. **定制阶段**（45 分钟）
   - 修改应用以适应特定场景
   - 优化生产环境部署
   - 实现监控与成本管理

#### 🚀 开始研讨会
```bash
# 选项1：GitHub Codespaces（推荐）
# 点击仓库中的“代码”→“在main上创建codespace”

# 选项2：本地开发
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# 按照 workshop/README.md 中的设置说明操作
```

#### 🎯 研讨会学习成果
完成本研讨会后，参与者将能够：
- **部署生产级 AI 应用**：使用 AZD 和 Microsoft Foundry 服务
- **掌握多代理架构**：实现协调的 AI 代理解决方案
- **执行安全最佳实践**：配置认证与访问控制
- **优化规模与成本**：设计高效性能和经济的部署方案
- **故障排查能力**：独立解决常见部署问题

#### 📖 研讨会资源
- **🎥 交互式指南**：[研讨会材料](workshop/README.md) - 基于浏览器的学习环境
- **📋 逐步指导**：[指导练习](../../workshop/docs/instructions) - 详细操作流程
- **🛠️ AI 研讨实验室**：[AI 研讨实验室](docs/microsoft-foundry/ai-workshop-lab.md) - AI 专题练习
- **💡 快速入门**：[研讨会配置指南](workshop/README.md#quick-start) - 环境配置

**适用场景**：企业培训、大学课程、自主学习和开发者训练营。

---

## 📖 什么是 Azure Developer CLI？

Azure Developer CLI（azd）是以开发者为中心的命令行界面，加速构建和部署应用到 Azure 的流程。它提供：

- **基于模板的部署**——为常用应用模式提供预构建模板
- **基础设施即代码**——使用 Bicep 或 Terraform 管理 Azure 资源  
- **集成工作流**——无缝完成资源配置、部署与监控
- **开发者友好**——提升开发效率与体验

### **AZD + Microsoft Foundry：AI 部署的理想选择**

**为什么选择 AZD 来部署 AI 解决方案？** AZD 解决 AI 开发者遇到的主要挑战：

- **AI 就绪模板**——预配置适用于 Azure OpenAI、认知服务及机器学习工作负载的模板
- **安全的 AI 部署**——内置 AI 服务、API 密钥及模型端点安全模式  
- **生产级 AI 模式**——可扩展和成本效益高的 AI 应用最佳实践
- **端到端 AI 工作流**——从模型开发到生产部署，支持完备监控
- **成本优化**——智能资源分配和扩展策略
- **Microsoft Foundry 集成**——无缝连接 Microsoft Foundry 模型目录及端点

---

## 🎯 模板与示例库

### 特色：Microsoft Foundry 模板
**如果你要部署 AI 应用，请从这里开始！**

> **注意：** 这些模板演示多种 AI 模式。有些是外部 Azure 示例，有些为本地实现。

| 模板 | 章节 | 复杂度 | 服务 | 类型 |
|----------|---------|------------|----------|------|
| [**开始 AI 聊天**](https://github.com/Azure-Samples/get-started-with-ai-chat) | 第二章 | ⭐⭐ | AzureOpenAI + Azure AI 模型推理 API + Azure AI 搜索 + Azure 容器应用 + 应用洞察 | 外部 |
| [**开始 AI 代理**](https://github.com/Azure-Samples/get-started-with-ai-agents) | 第二章 | ⭐⭐ | Azure AI 代理服务 + AzureOpenAI + Azure AI 搜索 + Azure 容器应用 + 应用洞察 | 外部 |
| [**Azure 搜索 + OpenAI 演示**](https://github.com/Azure-Samples/azure-search-openai-demo) | 第二章 | ⭐⭐ | AzureOpenAI + Azure AI 搜索 + 应用服务 + 存储 | 外部 |
| [**OpenAI 聊天应用快速入门**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | 第二章 | ⭐ | AzureOpenAI + 容器应用 + 应用洞察 | 外部 |
| [**代理 OpenAI Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | 第五章 | ⭐⭐⭐ | AzureOpenAI + Azure Functions + Prompty | 外部 |
| [**Contoso 聊天 RAG**](https://github.com/Azure-Samples/contoso-chat) | 第八章 | ⭐⭐⭐⭐ | AzureOpenAI + AI 搜索 + Cosmos DB + 容器应用 | 外部 |
| [**零售多代理解决方案**](examples/retail-scenario.md) | 第五章 | ⭐⭐⭐⭐ | AzureOpenAI + AI 搜索 + 存储 + 容器应用 + Cosmos DB | **本地** |

### 特色：完整学习场景
**面向生产的应用模板与学习章节对应**

| 模板 | 学习章节 | 复杂度 | 关键学习点 |
|----------|------------------|------------|--------------|
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | 第二章 | ⭐ | 基础 AI 部署模式 |
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | 第二章 | ⭐⭐ | Azure AI 搜索的 RAG 实现 |
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | 第四章 | ⭐⭐ | 文档智能集成 |
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | 第五章 | ⭐⭐⭐ | 代理框架和函数调用 |
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | 第八章 | ⭐⭐⭐ | 企业级 AI 编排 |
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | 第五章 | ⭐⭐⭐⭐ | 具备客户和库存代理的多代理架构 |

### 按示例类型学习

> **📌 本地示例与外部示例：**  
> **本地示例**（本仓库内）= 可立即使用  
> **外部示例**（Azure Samples）= 从对应仓库克隆

#### 本地示例（可立即使用）
- [**零售多代理解决方案**](examples/retail-scenario.md) - 完整生产级实现含 ARM 模板
  - 多代理架构（客户和库存代理）
  - 完善的监控与评估
  - 通过 ARM 模板一键部署

#### 本地示例 - 容器应用（第二至五章）
**本仓库内详尽的容器部署示例：**
- [**容器应用示例**](examples/container-app/README.md) - 容器化部署完整指南
  - [简单 Flask API](../../examples/container-app/simple-flask-api) - 具备自动伸缩至零的基础 REST API
  - [微服务架构](../../examples/container-app/microservices) - 生产级多服务部署
  - 快速入门、生产和高级部署模式
  - 监控、安全和成本优化指导

#### 外部示例 - 简单应用（第一、二章）
**克隆这些 Azure Samples 仓库快速启动：**
- [简单 Web 应用 - Node.js + MongoDB](https://github.com/Azure-Samples/todo-nodejs-mongo) - 基础部署模式
- [静态网站 - React SPA](https://github.com/Azure-Samples/todo-csharp-sql-swa-func) - 静态内容部署
- [容器应用 - Python Flask](https://github.com/Azure-Samples/container-apps-store-api-microservice) - REST API 部署

#### 外部示例 - 数据库集成（第三、四章）  
- [数据库应用 - C# + SQL](https://github.com/Azure-Samples/todo-csharp-sql) - 数据库连接模式
- [函数 + Cosmos DB](https://github.com/Azure-Samples/todo-python-mongo-swa-func) - 无服务器数据工作流

#### 外部示例 - 高级模式（第四至八章）
- [Java 微服务](https://github.com/Azure-Samples/java-microservices-aca-lab) - 多服务架构
- [容器应用作业](https://github.com/Azure-Samples/container-apps-jobs) - 后台处理  
- [企业 ML 流水线](https://github.com/Azure-Samples/mlops-v2) - 生产级 ML 模式

### 外部模板集合
- [**官方 AZD 模板库**](https://azure.github.io/awesome-azd/) - 精选官方及社区模板集合  
- [**Azure 开发者 CLI 模板**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - Microsoft Learn 模板文档  
- [**示例目录**](examples/README.md) - 详细讲解的本地学习示例

---

## 📚 学习资源与参考

### 快速参考
- [**命令速查表**](resources/cheat-sheet.md) - 按章节组织的核心 azd 命令  
- [**术语表**](resources/glossary.md) - Azure 和 azd 相关术语  
- [**常见问题**](resources/faq.md) - 按学习章节组织的常见问题  
- [**学习指南**](resources/study-guide.md) - 综合练习题集

### 实操工作坊
- [**AI 工作坊实验室**](docs/microsoft-foundry/ai-workshop-lab.md) - 使你的 AI 解决方案可通过 AZD 部署（2-3 小时）  
- [**交互式工作坊指南**](workshop/README.md) - 基于浏览器的 MkDocs 和 DevContainer 环境工作坊  
- [**结构化学习路径**](../../workshop/docs/instructions) - 7 步导引练习（探索 → 部署 → 定制）  
- [**AZD 初学者工作坊**](workshop/README.md) - 完整实操工作坊资料，集成 GitHub Codespaces

### 外部学习资源
- Azure Developer CLI 文档：https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/  
- Azure 架构中心：https://learn.microsoft.com/en-us/azure/architecture/  
- Azure 价格计算器：https://azure.microsoft.com/pricing/calculator/  
- Azure 状态：https://status.azure.com/

---

## 🔧 快速故障排除指南

**初学者常见问题及即时解决方案：**

### ❌ “azd: command not found”

```bash
# 先安装 AZD
# Windows（PowerShell）：
winget install microsoft.azd

# macOS：
brew tap azure/azd && brew install azd

# Linux：
curl -fsSL https://aka.ms/install-azd.sh | bash

# 验证安装
azd version
```

### ❌ “未找到订阅”或“订阅未设置”

```bash
# 列出可用的订阅
az account list --output table

# 设置默认订阅
az account set --subscription "<subscription-id-or-name>"

# 设置AZD环境
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# 验证
az account show
```

### ❌ “配额不足”或“超出配额”

```bash
# 尝试不同的Azure区域
azd env set AZURE_LOCATION "westus2"
azd up

# 或在开发中使用较小的SKU
# 编辑infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```

### ❌ “azd up” 执行到一半失败

```bash
# 选项1：清理并重试
azd down --force --purge
azd up

# 选项2：仅修复基础设施
azd provision

# 选项3：检查详细日志
azd show
azd logs
```

### ❌ “身份验证失败”或“令牌过期”

```bash
# 重新认证
az logout
az login

azd auth logout
azd auth login

# 验证身份认证
az account show
```

### ❌ “资源已存在”或命名冲突

```bash
# AZD 会生成唯一名称，但如果发生冲突：
azd down --force --purge

# 则使用新的环境重试
azd env new dev-v2
azd up
```

### ❌ 模板部署时间过长

**正常等待时间：**
- 简单网页应用：5-10 分钟  
- 带数据库的应用：10-15 分钟  
- AI 应用：15-25 分钟（OpenAI 配置较慢）

```bash
# 检查进度
azd show

# 如果卡住超过30分钟，检查Azure门户：
azd monitor
# 查找失败的部署
```

### ❌ “权限被拒绝”或“禁止访问”

```bash
# 检查您的 Azure 角色
az role assignment list --assignee $(az account show --query user.name -o tsv)

# 您至少需要“参与者”角色
# 请您的 Azure 管理员授予：
# - 参与者（针对资源）
# - 用户访问管理员（用于角色分配）
```

### ❌ 找不到已部署应用的 URL

```bash
# 显示所有服务端点
azd show

# 或打开 Azure 门户
azd monitor

# 检查特定服务
azd env get-values
# 查找 *_URL 变量
```

### 📚 完整故障排查资源

- **常见问题指南：**[详细解决方案](docs/troubleshooting/common-issues.md)  
- **AI 相关问题：**[AI 故障排查](docs/troubleshooting/ai-troubleshooting.md)  
- **调试指南：**[逐步调试](docs/troubleshooting/debugging.md)  
- **寻求帮助：**[Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🔧 快速故障排除指南

**初学者常见问题及即时解决方案：**

<details>
<summary><strong>❌ “azd: command not found”</strong></summary>

```bash
# 首先安装 AZD
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# 验证安装
azd version
```
</details>

<details>
<summary><strong>❌ “未找到订阅”或“订阅未设置”</strong></summary>

```bash
# 列出可用的订阅
az account list --output table

# 设置默认订阅
az account set --subscription "<subscription-id-or-name>"

# 设置AZD环境
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# 验证
az account show
```
</details>

<details>
<summary><strong>❌ “配额不足”或“超出配额”</strong></summary>

```bash
# 尝试不同的 Azure 区域
azd env set AZURE_LOCATION "westus2"
azd up

# 或在开发中使用较小的 SKU
# 编辑 infra/main.parameters.json：
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>

<details>
<summary><strong>❌ “azd up” 执行到一半失败</strong></summary>

```bash
# 选项 1：清理并重试
azd down --force --purge
azd up

# 选项 2：仅修复基础设施
azd provision

# 选项 3：检查详细日志
azd show
azd logs
```
</details>

<details>
<summary><strong>❌ “身份验证失败”或“令牌过期”</strong></summary>

```bash
# 重新认证
az logout
az login

azd auth logout
azd auth login

# 验证认证
az account show
```
</details>

<details>
<summary><strong>❌ “资源已存在”或命名冲突</strong></summary>

```bash
# AZD 会生成唯一名称，但如果发生冲突：
azd down --force --purge

# 则使用新的环境重试
azd env new dev-v2
azd up
```
</details>

<details>
<summary><strong>❌ 模板部署时间过长</strong></summary>

**正常等待时间：**
- 简单网页应用：5-10 分钟  
- 带数据库的应用：10-15 分钟  
- AI 应用：15-25 分钟（OpenAI 配置较慢）

```bash
# 检查进度
azd show

# 如果卡住超过30分钟，检查Azure门户：
azd monitor
# 查找失败的部署
```
</details>

<details>
<summary><strong>❌ “权限被拒绝”或“禁止访问”</strong></summary>

```bash
# 检查您的 Azure 角色
az role assignment list --assignee $(az account show --query user.name -o tsv)

# 您至少需要“参与者”角色
# 请您的 Azure 管理员授予：
# - 参与者（针对资源）
# - 用户访问管理员（针对角色分配）
```
</details>

<details>
<summary><strong>❌ 找不到已部署应用的 URL</strong></summary>

```bash
# 显示所有服务端点
azd show

# 或者打开 Azure 门户
azd monitor

# 检查特定服务
azd env get-values
# 查找 *_URL 变量
```
</details>

### 📚 完整故障排查资源

- **常见问题指南：**[详细解决方案](docs/troubleshooting/common-issues.md)  
- **AI 相关问题：**[AI 故障排查](docs/troubleshooting/ai-troubleshooting.md)  
- **调试指南：**[逐步调试](docs/troubleshooting/debugging.md)  
- **寻求帮助：**[Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🎓 课程完成与认证

### 进度追踪
跟踪你在每章的学习进度：

- [ ] **第 1 章**：基础与快速入门 ✅  
- [ ] **第 2 章**：AI 优先开发 ✅  
- [ ] **第 3 章**：配置与身份验证 ✅  
- [ ] **第 4 章**：基础设施即代码与部署 ✅  
- [ ] **第 5 章**：多代理 AI 解决方案 ✅  
- [ ] **第 6 章**：部署前验证与规划 ✅  
- [ ] **第 7 章**：故障排查与调试 ✅  
- [ ] **第 8 章**：生产与企业模式 ✅

### 学习验证
完成每章后，通过以下方式验证你的知识：
1. **实操练习**：完成本章的实际部署  
2. **知识检测**：复习本章的常见问题  
3. **社区讨论**：在 Azure Discord 分享经验  
4. **进入下一章**：挑战更高难度

### 课程完成收益
完成全部章节后，你将获得：
- **生产实践经验**：已将真实 AI 应用部署至 Azure  
- **职业技能**：具备企业级部署能力  
- **社区认可**：成为活跃的 Azure 开发者社区成员  
- **职业晋升**：掌握热门 AZD 和 AI 部署技术

---

## 🤝 社区与支持

### 获取帮助与支持
- **技术问题**：[报告错误与功能请求](https://github.com/microsoft/azd-for-beginners/issues)  
- **学习问题**：[Microsoft Azure Discord 社区](https://discord.gg/microsoft-azure) 和 [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)  
- **AI 专属帮助**：加入 [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)  
- **文档指导**：[官方 Azure Developer CLI 文档](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)

### Microsoft Foundry Discord 的社区见解

**#Azure 频道最新投票结果：**  
- **45%** 的开发者希望使用 AZD 进行 AI 工作负载  
- **主要挑战**：多服务部署、凭证管理、生产准备  
- **最受欢迎需求**：AI 专用模板，故障排查指南，最佳实践

**加入社区，即可：**  
- 分享你的 AZD + AI 经验，获取帮助  
- 先行体验最新 AI 模板  
- 参与 AI 部署最佳实践贡献  
- 影响未来 AI + AZD 功能开发

### 参与课程贡献
欢迎贡献！请阅读我们的 [贡献指南](CONTRIBUTING.md) 了解详情：
- **内容改进**：完善现有章节与示例  
- **新增示例**：添加真实场景与模板  
- **翻译支持**：维护多语言支持  
- **错误报告**：提升准确度和清晰度  
- **社区规范**：遵守包容性社区准则

---

## 📄 课程信息

### 许可证
本项目采用 MIT 许可证 - 详情请查看 [LICENSE](../../LICENSE) 文件。

### 相关 Microsoft 学习资源

我们的团队还制作了其它综合学习课程：

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
 
### 生成式 AI 系列
[![生成式 AI 初学者](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![生成式 AI (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
[![生成式 AI (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)
[![生成式 AI (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---
 
### 核心学习
[![机器学习初学者](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![初学者数据科学](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![初学者人工智能](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![初学者网络安全](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![初学者网页开发](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![初学者物联网](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![初学者XR开发](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Copilot 系列
[![AI 配对编程的 Copilot](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![C#/.NET 的 Copilot](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Copilot 冒险](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ 课程导航

**🚀 准备开始学习了吗？**

**初学者**：从[第1章：基础与快速入门](../..)开始  
**AI 开发者**：跳转到[第2章：AI优先开发](../..)  
**有经验的开发者**：从[第3章：配置与认证](../..)开始

**下一步**：[开始第1章 - AZD 基础](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**免责声明**：  
本文件由人工智能翻译服务[Co-op Translator](https://github.com/Azure/co-op-translator)进行翻译。虽然我们努力保证准确性，但请注意自动翻译可能包含错误或不准确之处。原始语言的文档应被视为权威来源。对于重要信息，建议使用专业人工翻译。我们不对因使用本翻译而产生的任何误解或曲解承担责任。
<!-- CO-OP TRANSLATOR DISCLAIMER END -->