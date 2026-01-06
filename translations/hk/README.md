<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T12:50:00+00:00",
  "source_file": "README.md",
  "language_code": "hk"
}
-->
> 注意：本文件將持續更新以反映最新變更。

> ⚠️ 此倉庫為示範用途，展示使用 Localizeflow 進行自動化文件本地化。
>
> 原始內容基於微軟的「AZD 入門」專案。


# AZD 入門：結構化學習旅程

![AZD-for-beginners](../../translated_images/azdbeginners.5527441dd9f74068.hk.png) 

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## 本課程入門指南

按照以下步驟開始你的 AZD 學習之旅：

1. **Fork 倉庫**：點擊 [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)
2. **Clone 倉庫**：`git clone https://github.com/microsoft/azd-for-beginners.git`
3. **加入社群**：[Azure Discord Communities](https://discord.com/invite/ByRwuEEgH4) 尋求專家支援
4. **選擇你的學習路徑**：從以下章節選擇最符合你經驗的內容

### 多語言支援

#### 自動翻譯（始終保持最新）

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](./README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **希望本地克隆？**

> 此倉庫包含 50 多種語言的翻譯，會顯著增加下載大小。若想不帶翻譯克隆，請使用稀疏檢出：
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> 這會讓你以更快的下載速度取得完成課程所需的所有內容。
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## 課程概覽

透過結構化章節掌握 Azure Developer CLI (azd)，為進階學習而設。**特別聚焦於與 Microsoft Foundry 整合的 AI 應用部署。**

### 為何此課程對現代開發者至關重要

根據 Microsoft Foundry Discord 社群見解，**45% 的開發者希望使用 AZD 來處理 AI 工作負載**，但面臨挑戰：
- 複雜的多服務 AI 架構
- AI 生產部署最佳實踐
- Azure AI 服務整合與配置
- AI 工作負載的成本優化
- AI 專屬部署問題的疑難排解

### 學習目標

完成此結構化課程後，你將能：
- **精通 AZD 基礎**：核心概念、安裝與配置
- **部署 AI 應用**：結合 AZD 與 Microsoft Foundry 服務
- **實作基於代碼的基礎架構**：使用 Bicep 模板管理 Azure 資源
- **故障排除部署**：解決常見問題並進行除錯
- **優化生產環境**：安全性、擴展性、監控與成本管理
- **建構多代理解決方案**：部署複雜 AI 架構

## 📚 學習章節

*依據經驗層級及目標選擇學習路徑*

### 🚀 第1章：基礎與快速入門
**先決條件**：Azure 訂閱，基本命令行知識  
**時間長度**：30-45 分鐘  
**複雜度**：⭐

#### 你將學到
- Azure Developer CLI 基本概念
- 在你的平台安裝 AZD
- 成功完成首次部署

#### 學習資源
- **🎯 入門**：[什麼是 Azure Developer CLI？](../..)
- **📖 理論**：[AZD 基礎](docs/getting-started/azd-basics.md) - 核心概念與術語
- **⚙️ 設定**：[安裝與設定](docs/getting-started/installation.md) - 各平台指南
- **🛠️ 實作**：[你的第一個專案](docs/getting-started/first-project.md) - 逐步教學
- **📋 快速參考**：[指令速查表](resources/cheat-sheet.md)

#### 實作練習
```bash
# 快速安裝檢查
azd version

# 部署您的第一個應用程式
azd init --template todo-nodejs-mongo
azd up
```

**💡 章節成果**：成功使用 AZD 部署簡易網頁應用至 Azure

**✅ 成功判定：**
```bash
# 完成第一章後，你應該能夠：
azd version              # 顯示已安裝的版本
azd init --template todo-nodejs-mongo  # 初始化專案
azd up                  # 部署至 Azure
azd show                # 顯示運行中的應用程式網址
# 應用程式會在瀏覽器中開啟並運作
azd down --force --purge  # 清理資源
```

**📊 預計耗時：** 30-45 分鐘  
**📈 完成後技能等級：** 可獨立部署基本應用

**✅ 成功判定：**
```bash
# 完成第一章後，你應該能夠：
azd version              # 顯示已安裝的版本
azd init --template todo-nodejs-mongo  # 初始化專案
azd up                  # 部署到 Azure
azd show                # 顯示正在運行的應用程式網址
# 在瀏覽器中開啟應用程式並運作
azd down --force --purge  # 清理資源
```

**📊 預計耗時：** 30-45 分鐘  
**📈 完成後技能等級：** 可獨立部署基本應用

---

### 🤖 第2章：以 AI 為先的開發（推薦 AI 開發者）
**先決條件**：完成第1章  
**時間長度**：1-2 小時  
**複雜度**：⭐⭐

#### 你將學到
- Microsoft Foundry 與 AZD 的整合
- 部署 AI 驅動的應用程式
- 理解 AI 服務配置

#### 學習資源
- **🎯 入門**：[Microsoft Foundry 整合](docs/microsoft-foundry/microsoft-foundry-integration.md)
- **📖 模式**：[AI 模型部署](docs/microsoft-foundry/ai-model-deployment.md) - 部署與管理 AI 模型
- **🛠️ 工作坊**：[AI 工作坊實作](docs/microsoft-foundry/ai-workshop-lab.md) - 使你的 AI 解決方案 AZD 就緒
- **🎥 互動教學**：[工作坊教材](workshop/README.md) - 基於瀏覽器的學習及 MkDocs * DevContainer 環境
- **📋 範本**：[Microsoft Foundry 範本](../..)
- **📝 範例**：[AZD 部署範例](examples/README.md)

#### 實作練習
```bash
# 部署你嘅第一個人工智能應用程式
azd init --template azure-search-openai-demo
azd up

# 試用更多人工智能範本
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```

**💡 章節成果**：部署並配置具備 RAG 功能的 AI 驅動聊天應用

**✅ 成功判定：**
```bash
# 完成第二章後，你應該能夠：
azd init --template azure-search-openai-demo
azd up
# 測試 AI 聊天介面
# 提問並取得帶有來源的 AI 驅動回應
# 驗證搜索整合功能是否正常
azd monitor  # 檢查 Application Insights 是否顯示遙測數據
azd down --force --purge
```

**📊 預計耗時：** 1-2 小時  
**📈 完成後技能等級：** 能部署及配置生產級 AI 應用  
**💰 成本認知：** 瞭解開發成本約 $80-150/月，生產成本約 $300-3500/月

#### 💰 AI 部署成本考量

**開發環境（估計 $80-150/月）：**
- Azure OpenAI（依用量計費）：$0-50/月（依 token 使用量）
- AI 搜索（基礎方案）：$75/月
- 容器應用（消耗計費）：$0-20/月
- 儲存（標準）：$1-5/月

**生產環境（估計 $300-3,500+/月）：**
- Azure OpenAI（PTU 保持性能穩定）：$3,000+/月 或 大量使用依用量計費
- AI 搜索（標準方案）：$250/月
- 容器應用（專用方案）：$50-100/月
- Application Insights：$5-50/月
- 儲存（高階）：$10-50/月

**💡 成本優化建議：**
- 使用 **免費方案** 的 Azure OpenAI 進行學習（包含每月 50,000 令牌）
- 不開發時執行 `azd down` 以釋放資源
- 從消耗計費開始，生產時改用 PTU
- 執行 `azd provision --preview` 於部署前預估成本
- 啟用自動縮放：僅支付實際使用量

**成本監控：**
```bash
# 檢查預估每月成本
azd provision --preview

# 在 Azure 入口網站監控實際成本
az consumption budget list --resource-group <your-rg>
```

---

### ⚙️ 第3章：配置與認證
**先決條件**：完成第1章  
**時間長度**：45-60 分鐘  
**複雜度**：⭐⭐

#### 你將學到
- 環境配置與管理
- 認證與安全最佳實踐
- 資源命名與組織結構

#### 學習資源
- **📖 配置**：[配置指南](docs/getting-started/configuration.md) - 環境設置
- **🔐 安全性**：[認證模式與管理身份](docs/getting-started/authsecurity.md) - 認證模式
- **📝 範例**：[資料庫應用範例](examples/database-app/README.md) - AZD 資料庫範例

#### 實作練習
- 配置多環境（開發、測試、生產）
- 設置管理身份認證
- 實施環境特有配置

**💡 章節成果**：有效管理多環境且確保認證與安全性

---

### 🏗️ 第4章：基礎架構即代碼與部署
**先決條件**：完成第1-3章  
**時間長度**：1-1.5 小時  
**複雜度**：⭐⭐⭐

#### 你將學到
- 進階部署模式
- 以 Bicep 實作基礎架構即代碼
- 資源佈建策略

#### 學習資源
- **📖 部署**：[部署指南](docs/deployment/deployment-guide.md) - 完整工作流程
- **🏗️ 佈建**：[佈建資源](docs/deployment/provisioning.md) - Azure 資源管理
- **📝 範例**：[容器應用範例](../../examples/container-app) - 容器化部署

#### 實作練習
- 製作自訂 Bicep 模板
- 部署多服務應用
- 實現藍綠部署策略

**💡 章節成果**：使用自訂基礎架構模板部署複雜多服務應用

---
### 🎯 第五章：多智能體 AI 解決方案（進階）
**先決條件**：完成第一至二章  
**時長**：2-3 小時  
**複雜度**：⭐⭐⭐⭐

#### 你將學到的內容
- 多智能體架構模式
- 智能體的協同與協調
- 可投入生產的 AI 部署

#### 學習資源
- **🤖 精選專案**：[零售多智能體解決方案](examples/retail-scenario.md) - 完整實作
- **🛠️ ARM 範本**：[ARM 範本套件](../../examples/retail-multiagent-arm-template) - 一鍵部署
- **📖 架構**：[多智能體協調模式](/docs/pre-deployment/coordination-patterns.md) - 模式介紹

#### 實作練習
```bash
# 部署完整的零售多代理解決方案
cd examples/retail-multiagent-arm-template
./deploy.sh

# 探索代理配置
az deployment group show --resource-group <rg-name> --name <deployment-name>
```

**💡 本章成果**：部署並管理具備客戶與庫存智能體的生產級多智能體 AI 解決方案

---

### 🔍 第六章：部署前驗證與規劃
**先決條件**：完成第四章  
**時長**：1 小時  
**複雜度**：⭐⭐

#### 你將學到的內容
- 容量規劃與資源驗證
- SKU 選擇策略
- 預先檢查與自動化

#### 學習資源
- **📊 規劃**：[容量規劃](docs/pre-deployment/capacity-planning.md) - 資源驗證
- **💰 選擇**：[SKU 選擇](docs/pre-deployment/sku-selection.md) - 成本效益考量
- **✅ 驗證**：[預檢查](docs/pre-deployment/preflight-checks.md) - 自動化腳本

#### 實作練習
- 執行容量驗證腳本
- 優化 SKU 選擇以節省成本
- 實施自動化部署前檢查

**💡 本章成果**：能在部署前驗證並優化資源配置

---

### 🚨 第七章：故障排除與除錯
**先決條件**：完成任一部署章節  
**時長**：1-1.5 小時  
**複雜度**：⭐⭐

#### 你將學到的內容
- 系統性除錯方法
- 常見問題與解決方案
- AI 相關故障排除

#### 學習資源
- **🔧 常見問題**：[常見問題](docs/troubleshooting/common-issues.md) - 常見問答與解法
- **🕵️ 除錯**：[除錯指南](docs/troubleshooting/debugging.md) - 逐步策略
- **🤖 AI 問題**：[AI 專屬故障排除](docs/troubleshooting/ai-troubleshooting.md) - AI 服務問題

#### 實作練習
- 診斷部署失敗原因
- 解決驗證身份問題
- 除錯 AI 服務連線問題

**💡 本章成果**：能獨立診斷與解決常見部署問題

---

### 🏢 第八章：生產與企業級架構模式
**先決條件**：完成第一至四章  
**時長**：2-3 小時  
**複雜度**：⭐⭐⭐⭐

#### 你將學到的內容
- 生產環境部署策略
- 企業安全架構模式
- 監控與成本優化

#### 學習資源
- **🏭 生產環境**：[生產 AI 最佳實踐](docs/microsoft-foundry/production-ai-practices.md) - 企業級模式
- **📝 範例**：[微服務範例](../../examples/microservices) - 複雜架構
- **📊 監控**：[Application Insights 整合](docs/pre-deployment/application-insights.md) - 監控設定

#### 實作練習
- 實施企業安全模式
- 建立完整監控系統
- 正確治理下部署至生產環境

**💡 本章成果**：部署具備完整生產能力的企業級應用程式

---

## 🎓 工作坊總覽：實戰學習體驗

> **⚠️ 工作坊狀態：持續開發中**  
> 工作坊教材正進行製作與優化。核心模組已完整，但部分進階章節尚未完成。我們正積極完成所有內容。[查看進度 →](workshop/README.md)

### 互動式工作坊教材
**結合瀏覽器工具與引導練習的全面實作學習體驗**

工作坊教材提供有結構的互動學習，與前述章節課程相輔相成。設計適合自學與講師帶領課程。

#### 🛠️ 工作坊特色
- **瀏覽器介面**：完整 MkDocs 支援，含搜尋、複製與主題功能
- **GitHub Codespaces 整合**：一鍵開發環境啟動
- **結構化學習路徑**：7 步驟引導練習 (共 3.5 小時)
- **探索 → 部署 → 客製化**：分階段教學方法
- **互動 DevContainer 環境**：預先配置工具與依賴

#### 📚 工作坊架構
工作坊依循 **探索 → 部署 → 客製化** 方法：

1. **探索階段**（45 分鐘）
   - 探索 Microsoft Foundry 範本與服務
   - 理解多智能體架構模式
   - 複習部署需求與先決條件

2. **部署階段**（2 小時）
   - 使用 AZD 實戰部署 AI 應用
   - 配置 Azure AI 服務與端點
   - 實作安全與身份驗證模式

3. **客製化階段**（45 分鐘）
   - 針對特定案例修改應用
   - 優化生產部署
   - 實施監控與成本管理

#### 🚀 工作坊入門
```bash
# 選項 1：GitHub Codespaces（推薦）
# 在倉庫中點擊「Code」→「Create codespace on main」

# 選項 2：本地開發
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# 按照 workshop/README.md 中的設定指引操作
```

#### 🎯 工作坊學習成效
完成工作坊後，參與者將能夠：
- **部署生產級 AI 應用**：運用 AZD 與 Microsoft Foundry 服務
- **精通多智能體架構**：實作協同的 AI 智能體解決方案
- **實施安全最佳實踐**：設定身份認證與存取控制
- **優化擴充性**：設計成本效益與效能兼備的部署
- **故障排除**：獨立解決常見部署問題

#### 📖 工作坊資源
- **🎥 互動指南**：[工作坊教材](workshop/README.md) - 瀏覽器學習環境
- **📋 逐步指引**：[引導練習](../../workshop/docs/instructions) - 詳細教學
- **🛠️ AI 工作坊實驗室**：[AI 工作坊實驗室](docs/microsoft-foundry/ai-workshop-lab.md) - AI 專題練習
- **💡 快速入門**：[工作坊設定指南](workshop/README.md#quick-start) - 環境配置介紹

**適合對象**：企業培訓、大學課程、自主學習及開發者培訓營。

---

## 📖 什麼是 Azure Developer CLI？

Azure Developer CLI（azd）是一款以開發者為中心的命令列工具，加速應用程式在 Azure 上的建置與部署流程。它提供：

- **範本部署** - 使用預建範本快速完成常見應用模式
- **基礎架構即程式碼** - 透過 Bicep 或 Terraform 管理 Azure 資源  
- **整合化工作流程** - 無縫執行資源配置、應用程式部署與監控
- **開發者友善** - 強化開發效率與使用體驗

### **AZD + Microsoft Foundry：AI 部署的完美組合**

**為什麼選擇 AZD 進行 AI 解決方案？** AZD 解決 AI 開發者面臨的主要挑戰：

- **AI 專用範本** - 預配置 Azure OpenAI、認知服務及機器學習工作負載範本
- **安全的 AI 部署** - 內建 AI 服務、API 金鑰與模型端點的安全模式  
- **生產等級 AI 模式** - 可擴展且成本效益高的 AI 應用最佳實踐
- **端到端 AI 工作流程** - 從模型開發至生產部署並附設監控
- **成本優化** - AI 工作負載的智慧資源配置與擴展策略
- **Microsoft Foundry 整合** - 無縫連接 Microsoft Foundry 模型目錄與端點

---

## 🎯 範本與範例庫

### 精選：Microsoft Foundry 範本
**想部署 AI 應用，從這裡開始！**

> **注意：** 這些範本展示多種 AI 模式。有些為外部 Azure 範例，有些為本地實作。

| 範本 | 章節 | 複雜度 | 服務 | 類型 |
|----------|---------|------------|----------|------|
| [**聊天 AI 入門**](https://github.com/Azure-Samples/get-started-with-ai-chat) | 第二章 | ⭐⭐ | AzureOpenAI + Azure AI 推理 API + Azure AI 搜尋 + Azure Container Apps + Application Insights | 外部 |
| [**AI 智能體入門**](https://github.com/Azure-Samples/get-started-with-ai-agents) | 第二章 | ⭐⭐ | Azure AI 智能體服務 + AzureOpenAI + Azure AI 搜尋 + Azure Container Apps + Application Insights| 外部 |
| [**Azure 搜尋 + OpenAI 展示**](https://github.com/Azure-Samples/azure-search-openai-demo) | 第二章 | ⭐⭐ | AzureOpenAI + Azure AI 搜尋 + App Service + Storage | 外部 |
| [**OpenAI 聊天應用快速入門**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | 第二章 | ⭐ | AzureOpenAI + Container Apps + Application Insights | 外部 |
| [**Agent OpenAI Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | 第五章 | ⭐⭐⭐ | AzureOpenAI + Azure Functions + Prompty | 外部 |
| [**Contoso Chat RAG**](https://github.com/Azure-Samples/contoso-chat) | 第八章 | ⭐⭐⭐⭐ | AzureOpenAI + AI 搜尋 + Cosmos DB + Container Apps | 外部 |
| [**零售多智能體解決方案**](examples/retail-scenario.md) | 第五章 | ⭐⭐⭐⭐ | AzureOpenAI + AI 搜尋 + Storage + Container Apps + Cosmos DB | **本地** |

### 精選：完整學習範例
**生產級應用範本對應學習章節**

| 範本 | 學習章節 | 複雜度 | 主要學習內容 |
|----------|------------------|------------|--------------|
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | 第二章 | ⭐ | 基礎 AI 部署模式 |
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | 第二章 | ⭐⭐ | 利用 Azure AI 搜尋實作 RAG |
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | 第四章 | ⭐⭐ | 文件智能整合 |
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | 第五章 | ⭐⭐⭐ | 智能體框架與函數呼叫 |
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | 第八章 | ⭐⭐⭐ | 企業級 AI 協調 |
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | 第五章 | ⭐⭐⭐⭐ | 多智能體架構：客戶與庫存智能體 |

### 依範例類型學習

> **📌 本地與外部範例：**  
> **本地範例**（在此倉庫）= 可立即使用  
> **外部範例**（Azure Samples）= 需從連結倉庫克隆

#### 本地範例（立即使用）
- [**零售多智能體解決方案**](examples/retail-scenario.md) - 生產級完整實作與 ARM 範本
  - 多智能體架構（客戶與庫存智能體）
  - 全面監控與評估
  - 透過 ARM 範本一鍵部署

#### 本地範例 - Container 應用（第二至五章）
**倉庫內全面的容器部署範例：**
- [**Container App 範例**](examples/container-app/README.md) - 容器化部署完整指南
  - [簡易 Flask API](../../examples/container-app/simple-flask-api) - 基本 REST API，支援 scale-to-zero
  - [微服務架構](../../examples/container-app/microservices) - 生產級多服務部署
  - 快速入門、生產與進階部署模式
  - 監控、安全及成本優化指引

#### 外部範例 - 簡單應用（第一至二章）
**從這些 Azure Samples 倉庫克隆開始：**
- [簡易 Web App - Node.js + MongoDB](https://github.com/Azure-Samples/todo-nodejs-mongo) - 基礎部署模式
- [靜態網站 - React SPA](https://github.com/Azure-Samples/todo-csharp-sql-swa-func) - 靜態內容部署
- [Container App - Python Flask](https://github.com/Azure-Samples/container-apps-store-api-microservice) - REST API 部署

#### 外部範例 - 資料庫整合（第三至四章）  
- [資料庫應用 - C# + SQL](https://github.com/Azure-Samples/todo-csharp-sql) - 資料庫連接模式
- [Functions + Cosmos DB](https://github.com/Azure-Samples/todo-python-mongo-swa-func) - 無伺服器資料工作流程

#### 外部範例 - 進階架構（第四至八章）
- [Java 微服務](https://github.com/Azure-Samples/java-microservices-aca-lab) - 多服務架構
- [Container Apps 任務](https://github.com/Azure-Samples/container-apps-jobs) - 背景處理  
- [企業 ML 管線](https://github.com/Azure-Samples/mlops-v2) - 生產級機器學習模式

### 外部範本集錦
- [**官方 AZD 範本庫**](https://azure.github.io/awesome-azd/) - 精選官方和社群範本集合
- [**Azure 開發者 CLI 範本**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - Microsoft Learn 範本文件
- [**範例目錄**](examples/README.md) - 本地學習範例詳盡說明

---

## 📚 學習資源與參考

### 快速參考
- [**指令速查表**](resources/cheat-sheet.md) - 依章節組織的關鍵 azd 指令
- [**詞彙表**](resources/glossary.md) - Azure 與 azd 術語  
- [**常見問題**](resources/faq.md) - 按學習章節整理的常見問題
- [**學習指南**](resources/study-guide.md) - 全面練習題目

### 實作工作坊
- [**AI 工作坊實驗室**](docs/microsoft-foundry/ai-workshop-lab.md) - 讓您的 AI 解決方案可使用 AZD 部署 (2-3 小時)
- [**互動式工作坊指南**](workshop/README.md) - 利用 MkDocs 和 DevContainer 環境的瀏覽器工作坊
- [**結構化學習路徑**](../../workshop/docs/instructions) - 7 步驟引導練習（探索 → 部署 → 客製化）
- [**AZD 初學者工作坊**](workshop/README.md) - 完整實作工作坊教材，結合 GitHub Codespaces

### 外部學習資源
- [Azure 開發者 CLI 文件](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)
- [Azure 架構中心](https://learn.microsoft.com/en-us/azure/architecture/)
- [Azure 價格計算器](https://azure.microsoft.com/pricing/calculator/)
- [Azure 狀態](https://status.azure.com/)

---

## 🔧 快速故障排除指南

**初學者常見問題與即時解決方案：**

### ❌ 「azd: command not found」  

```bash
# 首先安裝 AZD
# Windows（PowerShell）：
winget install microsoft.azd

# macOS：
brew tap azure/azd && brew install azd

# Linux：
curl -fsSL https://aka.ms/install-azd.sh | bash

# 驗證安裝
azd version
```
  
### ❌ 「找不到訂閱」或「未設定訂閱」

```bash
# 列出可用訂閱
az account list --output table

# 設定默認訂閱
az account set --subscription "<subscription-id-or-name>"

# 設定 AZD 環境
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# 驗證
az account show
```
  
### ❌ 「InsufficientQuota」或「配額超出」

```bash
# 嘗試不同的 Azure 地區
azd env set AZURE_LOCATION "westus2"
azd up

# 或在開發時使用較小的 SKU
# 編輯 infra/main.parameters.json：
{
  "sku": "B1"  // Instead of "P1V2"
}
```
  
### ❌ 「azd up」中途失敗

```bash
# 選項 1：清理並重試
azd down --force --purge
azd up

# 選項 2：只修復基礎設施
azd provision

# 選項 3：檢查詳細日誌
azd show
azd logs
```
  
### ❌ 「驗證失敗」或「令牌過期」

```bash
# 重新驗證
az logout
az login

azd auth logout
azd auth login

# 驗證身份認證
az account show
```
  
### ❌ 「資源已存在」或命名衝突

```bash
# AZD 會生成獨特名稱，但如果發生衝突：
azd down --force --purge

# 就會在新的環境下重試
azd env new dev-v2
azd up
```
  
### ❌ 範本部署時間過長

**正常等待時間：**  
- 簡單網頁應用程式：5-10 分鐘  
- 含資料庫之應用程式：10-15 分鐘  
- AI 應用程式：15-25 分鐘（OpenAI 預配較慢）

```bash
# 檢查進度
azd show

# 如果停留超過30分鐘，檢查 Azure 入口網站：
azd monitor
# 尋找失敗的部署
```
  
### ❌ 「權限被拒」或「禁止存取」

```bash
# 檢查你的 Azure 角色
az role assignment list --assignee $(az account show --query user.name -o tsv)

# 你至少需要「貢獻者」角色
# 請你的 Azure 管理員授權：
# - 貢獻者（用於資源）
# - 使用者存取管理員（用於角色指派）
```
  
### ❌ 找不到已部署應用程式網址

```bash
# 顯示所有服務端點
azd show

# 或打開 Azure 入口網站
azd monitor

# 檢查特定服務
azd env get-values
# 尋找 *_URL 變數
```
  
### 📚 完整故障排除資源

- **常見問題指南：** [詳細解決方案](docs/troubleshooting/common-issues.md)  
- **AI 特有問題：** [AI 故障排除](docs/troubleshooting/ai-troubleshooting.md)  
- **除錯指南：** [逐步除錯](docs/troubleshooting/debugging.md)  
- **獲取協助：** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🔧 快速故障排除指南

**初學者常見問題與即時解決方案：**

<details>
<summary><strong>❌ 「azd: command not found」</strong></summary>

```bash
# 先安裝 AZD
# Windows（PowerShell）：
winget install microsoft.azd

# macOS：
brew tap azure/azd && brew install azd

# Linux：
curl -fsSL https://aka.ms/install-azd.sh | bash

# 驗證安裝
azd version
```
</details>

<details>
<summary><strong>❌ 「找不到訂閱」或「未設定訂閱」</strong></summary>

```bash
# 列出可用的訂閱
az account list --output table

# 設定預設訂閱
az account set --subscription "<subscription-id-or-name>"

# 設定 AZD 環境用
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# 驗證
az account show
```
</details>

<details>
<summary><strong>❌ 「InsufficientQuota」或「配額超出」</strong></summary>

```bash
# 嘗試不同的 Azure 地區
azd env set AZURE_LOCATION "westus2"
azd up

# 或在開發時使用較小的 SKU
# 編輯 infra/main.parameters.json：
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>

<details>
<summary><strong>❌ 「azd up」中途失敗</strong></summary>

```bash
# 選項 1：清理並重試
azd down --force --purge
azd up

# 選項 2：只修復基礎設施
azd provision

# 選項 3：檢查詳細日誌
azd show
azd logs
```
</details>

<details>
<summary><strong>❌ 「驗證失敗」或「令牌過期」</strong></summary>

```bash
# 重新驗證
az logout
az login

azd auth logout
azd auth login

# 驗證身份認證
az account show
```
</details>

<details>
<summary><strong>❌ 「資源已存在」或命名衝突</strong></summary>

```bash
# AZD 會產生獨特的名稱，但如果發生衝突：
azd down --force --purge

# 則會使用新的環境重試
azd env new dev-v2
azd up
```
</details>

<details>
<summary><strong>❌ 範本部署時間過長</strong></summary>

**正常等待時間：**  
- 簡單網頁應用程式：5-10 分鐘  
- 含資料庫之應用程式：10-15 分鐘  
- AI 應用程式：15-25 分鐘（OpenAI 預配較慢）

```bash
# 檢查進度
azd show

# 如果停滯超過30分鐘，請檢查 Azure 入口網站：
azd monitor
# 尋找失敗的部署
```
</details>

<details>
<summary><strong>❌ 「權限被拒」或「禁止存取」</strong></summary>

```bash
# 檢查你的 Azure 角色
az role assignment list --assignee $(az account show --query user.name -o tsv)

# 你至少需要「貢獻者」角色
# 請你的 Azure 管理員授予：
# - 貢獻者（針對資源）
# - 使用者存取管理員（針對角色指派）
```
</details>

<details>
<summary><strong>❌ 找不到已部署應用程式網址</strong></summary>

```bash
# 顯示所有服務端點
azd show

# 或打開 Azure 入口網站
azd monitor

# 檢查特定服務
azd env get-values
# 尋找 *_URL 變量
```
</details>

### 📚 完整故障排除資源

- **常見問題指南：** [詳細解決方案](docs/troubleshooting/common-issues.md)  
- **AI 特有問題：** [AI 故障排除](docs/troubleshooting/ai-troubleshooting.md)  
- **除錯指南：** [逐步除錯](docs/troubleshooting/debugging.md)  
- **獲取協助：** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🎓 課程完成與認證

### 進度追蹤
追蹤每個章節的學習進度：

- [ ] **第一章**：基礎與快速入門 ✅  
- [ ] **第二章**：AI 為先的開發 ✅  
- [ ] **第三章**：配置與驗證 ✅  
- [ ] **第四章**：基礎架構即程式碼與部署 ✅  
- [ ] **第五章**：多代理 AI 解決方案 ✅  
- [ ] **第六章**：部署前驗證與規劃 ✅  
- [ ] **第七章**：故障排除與除錯 ✅  
- [ ] **第八章**：生產與企業模式 ✅

### 學習驗證
完成每章後，透過以下方式核實知識：  
1. **實務練習**：完成該章節的部署實作  
2. **知識檢核**：檢視該章節常見問題區  
3. **社群討論**：在 Azure Discord 分享您的學習經驗  
4. **下一章節**：挑戰更高複雜度的課程

### 課程完成收益
完成所有章節後，您將擁有：  
- **生產經驗**：將真實 AI 應用部署至 Azure  
- **專業技能**：具備企業級部署能力  
- **社群認可**：成為活躍的 Azure 開發者社群成員  
- **職涯提升**：掌握熱門的 AZD 與 AI 部署技術

---

## 🤝 社群與支援

### 尋求協助與支援
- **技術問題**：[回報錯誤與功能請求](https://github.com/microsoft/azd-for-beginners/issues)  
- **學習問題**：[Microsoft Azure Discord 社群](https://discord.gg/microsoft-azure) 與 [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)  
- **AI 專項協助**：加入 [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)  
- **文件資源**：[官方 Azure 開發者 CLI 文件](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)

### Microsoft Foundry Discord 社群洞察

**#Azure 頻道最新投票結果：**  
- **45%** 開發者希望使用 AZD 於 AI 工作負載  
- **主要挑戰**：多服務部署、憑證管理、上線準備  
- **熱門需求**：AI 專用範本、故障排除指南、最佳實務

**加入我們社群可享：**  
- 分享您的 AZD + AI 體驗並獲得協助  
- 取得 AI 範本的早期預覽  
- 參與 AI 部署最佳實務貢獻  
- 影響未來 AI + AZD 新功能開發

### 課程貢獻
歡迎貢獻！請閱讀我們的 [貢獻指南](CONTRIBUTING.md)，了解：  
- **內容改進**：優化現有章節與範例  
- **新增範例**：增列實務案例與範本  
- **翻譯**：協助多語言維護  
- **錯誤回報**：提升準確性與清晰度  
- **社群規範**：遵守包容性社群準則

---

## 📄 課程資訊

### 授權條款
本專案採用 MIT 授權條款 - 詳情請參閱 [LICENSE](../../LICENSE) 檔案。

### 相關 Microsoft 學習資源

我們團隊還提供其他全面學習課程：

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
[![Generative AI for Beginners](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)  
[![Generative AI (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)  
[![Generative AI (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)  
[![Generative AI (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---
 
### 核心學習
[![ML for Beginners](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![初學者數據科學](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![初學者人工智能](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![初學者網絡安全](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![初學者網站開發](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![初學者物聯網](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![初學者XR開發](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Copilot 系列
[![AI 配對編程的 Copilot](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![C#/.NET 的 Copilot](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Copilot 冒險](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ 課程導航

**🚀 準備好開始學習？**

**初學者**：從 [第 1 章：基礎與快速入門](../..) 開始  
**人工智能開發者**：跳至 [第 2 章：AI 優先開發](../..)  
**資深開發者**：開始於 [第 3 章：配置與認證](../..)

**下一步**：[開始第 1 章 - AZD 基礎](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**免責聲明**：  
本文件由 AI 翻譯服務 [Co-op Translator](https://github.com/Azure/co-op-translator) 進行翻譯。雖然我們致力於確保翻譯準確，但請注意自動翻譯可能存在錯誤或不準確之處。原始文件的母語版本應視為權威來源。對於重要資訊，建議採用專業人工翻譯。我們不對因使用本翻譯而引致的任何誤解或誤釋承擔責任。
<!-- CO-OP TRANSLATOR DISCLAIMER END -->