<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T12:47:05+00:00",
  "source_file": "README.md",
  "language_code": "mo"
}
-->
> Note: 此文件會不斷更新，以反映最新變更。

> ⚠️ 此儲存庫為示範，旨在展示
> 如何使用 Localizeflow 自動化文件本地化。
>
> 原始內容基於
> 微軟的 “AZD for Beginners” 專案。


# AZD For Beginners：結構化學習之旅

![AZD-for-beginners](../../translated_images/azdbeginners.5527441dd9f74068.mo.png) 

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## 開始此課程

按照下列步驟開始您的 AZD 學習之旅：

1. **Fork 此儲存庫**：點擊 [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)
2. **Clone 此儲存庫**：`git clone https://github.com/microsoft/azd-for-beginners.git`
3. **加入社區**：參加 [Azure Discord Communities](https://discord.com/invite/ByRwuEEgH4) 尋求專家支援
4. **選擇學習路徑**：從下方選擇符合您經驗程度的章節

### 多語言支援

#### 自動翻譯（持續最新）

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[阿拉伯語](../ar/README.md) | [孟加拉語](../bn/README.md) | [保加利亞語](../bg/README.md) | [緬甸語](../my/README.md) | [中文（簡體）](../zh/README.md) | [中文（繁體，香港）](../hk/README.md) | [中文（繁體，澳門）](./README.md) | [中文（繁體，臺灣）](../tw/README.md) | [克羅地亞語](../hr/README.md) | [捷克語](../cs/README.md) | [丹麥語](../da/README.md) | [荷蘭語](../nl/README.md) | [愛沙尼亞語](../et/README.md) | [芬蘭語](../fi/README.md) | [法語](../fr/README.md) | [德語](../de/README.md) | [希臘語](../el/README.md) | [希伯來語](../he/README.md) | [印地語](../hi/README.md) | [匈牙利語](../hu/README.md) | [印尼語](../id/README.md) | [義大利語](../it/README.md) | [日語](../ja/README.md) | [坎納達語](../kn/README.md) | [韓語](../ko/README.md) | [立陶宛語](../lt/README.md) | [馬來語](../ms/README.md) | [馬拉雅拉姆語](../ml/README.md) | [馬拉地語](../mr/README.md) | [尼泊爾語](../ne/README.md) | [奈及利亞皮欽語](../pcm/README.md) | [挪威語](../no/README.md) | [波斯語（法爾西語）](../fa/README.md) | [波蘭語](../pl/README.md) | [葡萄牙語（巴西）](../br/README.md) | [葡萄牙語（葡萄牙）](../pt/README.md) | [旁遮普語（古爾穆奇）](../pa/README.md) | [羅馬尼亞語](../ro/README.md) | [俄語](../ru/README.md) | [塞爾維亞語（西里爾字母）](../sr/README.md) | [斯洛伐克語](../sk/README.md) | [斯洛文尼亞語](../sl/README.md) | [西班牙語](../es/README.md) | [斯瓦希里語](../sw/README.md) | [瑞典語](../sv/README.md) | [他加祿語（菲律賓語）](../tl/README.md) | [泰米爾語](../ta/README.md) | [泰盧固語](../te/README.md) | [泰語](../th/README.md) | [土耳其語](../tr/README.md) | [烏克蘭語](../uk/README.md) | [烏爾都語](../ur/README.md) | [越南語](../vi/README.md)

> **想要本地 Clone 嗎？**

> 此儲存庫包含 50 多種語言翻譯，這會大幅提升下載大小。如想不含翻譯地 Clone，使用 sparse checkout：
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> 這樣能讓您以更快速度下載完成課程所需所有內容。
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## 課程概覽

透過設計成循序漸進的章節，精通 Azure Developer CLI (azd)。**特別強調與 Microsoft Foundry 整合的 AI 應用部署。**

### 為何此課程對現代開發者不可或缺

根據 Microsoft Foundry Discord 社群洞察，**45% 的開發者希望使用 AZD 處理 AI 工作負載**，但遇到以下挑戰：
- 複雜的多服務 AI 架構
- 生產階段 AI 部署最佳實踐
- Azure AI 服務整合與配置
- AI 工作負載的成本優化
- 故障排除 AI 特定部署問題

### 學習目標

完成此結構化課程，您將能：
- **掌握 AZD 基礎**：核心概念、安裝與配置
- **部署 AI 應用**：結合 Microsoft Foundry 服務使用 AZD
- **實作基於程式碼的基礎建設**：使用 Bicep 範本管理 Azure 資源
- **排除部署錯誤**：解決常見問題與除錯
- **優化生產環境**：安全性、擴展、監控與成本管理
- **打造多代理解決方案**：部署複雜 AI 架構

## 📚 學習章節

*根據經驗與目標選擇您的學習路徑*

### 🚀 第一章：基礎與快速開始
**先決條件**：Azure 訂閱、基本指令列知識  
**時間長度**：30-45 分鐘  
**難易度**：⭐

#### 您將學到
- 了解 Azure Developer CLI 基礎
- 在您的平台安裝 AZD
- 成功完成您的首次部署

#### 學習資源
- **🎯 從這裡開始**：[何謂 Azure Developer CLI？](../..)
- **📖 理論**：[AZD 基本知識](docs/getting-started/azd-basics.md) - 核心概念與術語
- **⚙️ 安裝設定**：[安裝與設置](docs/getting-started/installation.md) - 各平台指南
- **🛠️ 實作**：[您的第一個專案](docs/getting-started/first-project.md) - 逐步教學
- **📋 快速參考**：[指令速查表](resources/cheat-sheet.md)

#### 實務練習
```bash
# 快速安裝檢查
azd version

# 部署您的第一個應用程式
azd init --template todo-nodejs-mongo
azd up
```

**💡 本章目標**：成功使用 AZD 將簡單的網頁應用部署到 Azure

**✅ 成功驗證：**
```bash
# 完成第1章後，你應該能夠：
azd version              # 顯示已安裝版本
azd init --template todo-nodejs-mongo  # 初始化專案
azd up                  # 部署到 Azure
azd show                # 顯示正在運行的應用程式網址
# 應用程式會在瀏覽器開啟並運作
azd down --force --purge  # 清理資源
```

**📊 所需時間：** 30-45 分鐘  
**📈 達成技能：** 能夠獨立部署基本應用程式

**✅ 成功驗證：**
```bash
# 完成第一章後，您應該能夠：
azd version              # 顯示已安裝版本
azd init --template todo-nodejs-mongo  # 初始化專案
azd up                  # 部署到 Azure
azd show                # 顯示運行中的應用程式 URL
# 應用程式會在瀏覽器中打開並運作
azd down --force --purge  # 清理資源
```

**📊 所需時間：** 30-45 分鐘  
**📈 達成技能：** 能夠獨立部署基本應用程式

---

### 🤖 第二章：AI 優先開發（推薦 AI 開發者）
**先決條件**：完成第一章  
**時間長度**：1-2 小時  
**難易度**：⭐⭐

#### 您將學到
- Microsoft Foundry 與 AZD 的整合
- 部署 AI 驅動應用程式
- 理解 AI 服務配置

#### 學習資源
- **🎯 從這裡開始**：[Microsoft Foundry 整合](docs/microsoft-foundry/microsoft-foundry-integration.md)
- **📖 範例模式**：[AI 模型部署](docs/microsoft-foundry/ai-model-deployment.md) - 部署與管理 AI 模型
- **🛠️ 工作坊**：[AI 工作坊實驗室](docs/microsoft-foundry/ai-workshop-lab.md) - 讓您的 AI 解決方案 AZD 準備就緒
- **🎥 互動指南**：[工作坊教材](workshop/README.md) - 透過瀏覽器與 MkDocs * DevContainer 環境學習
- **📋 範本**：[Microsoft Foundry 範本](../..)
- **📝 範例**：[AZD 部署範例](examples/README.md)

#### 實務練習
```bash
# 部署您的第一個人工智能應用程式
azd init --template azure-search-openai-demo
azd up

# 嘗試其他人工智能範本
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```

**💡 本章目標**：部署並配置具備 RAG 能力的 AI 聊天應用

**✅ 成功驗證：**
```bash
# 完成第二章後，您應該能夠：
azd init --template azure-search-openai-demo
azd up
# 測試 AI 聊天介面
# 提問並獲得帶來源的 AI 回答
# 驗證搜尋整合是否正常運作
azd monitor  # 檢查 Application Insights 是否顯示遙測資料
azd down --force --purge
```

**📊 所需時間：** 1-2 小時  
**📈 達成技能：** 能部署及配置生產就緒的 AI 應用  
**💰 成本意識：** 了解每月約 80-150 美元開發成本，300-3500 美元生產成本

#### 💰 AI 部署成本考量

**開發環境（預估每月 80-150 美元）：**
- Azure OpenAI（按使用付費）：每月 0-50 美元（根據 Token 使用量）
- AI 搜尋（基本級）：每月 75 美元
- Container Apps（消耗計費）：每月 0-20 美元
- 儲存（標準）：每月 1-5 美元

**生產環境（預估每月 300-3,500+ 美元）：**
- Azure OpenAI（PTU 保持效能穩定）：每月 3,000+ 美元 或 大量使用按使用付費
- AI 搜尋（標準級）：每月 250 美元
- Container Apps（專用）：每月 50-100 美元
- Application Insights：每月 5-50 美元
- 儲存（高階）：每月 10-50 美元

**💡 成本優化建議：**
- 使用 Azure OpenAI **免費等級** 學習（含 50,000 tokens/月）
- 非活躍開發時運行 `azd down` 釋放資源
- 初期採用消耗計費，生產時升級至 PTU
- 部署前使用 `azd provision --preview` 預估成本
- 啟用自動擴展：只為實際用量付費

**成本監控：**
```bash
# 檢查估計每月費用
azd provision --preview

# 在 Azure 入口網站監控實際費用
az consumption budget list --resource-group <your-rg>
```

---

### ⚙️ 第三章：配置與身份驗證
**先決條件**：完成第一章  
**時間長度**：45-60 分鐘  
**難易度**：⭐⭐

#### 您將學到
- 環境配置與管理
- 身份驗證與安全最佳實踐
- 資源命名與組織

#### 學習資源
- **📖 配置**：[配置指南](docs/getting-started/configuration.md) - 環境設置
- **🔐 安全**：[身份驗證模式及託管身份](docs/getting-started/authsecurity.md) - 身份驗證模式
- **📝 範例**：[資料庫應用範例](examples/database-app/README.md) - AZD 資料庫實例

#### 實務練習
- 配置多個環境（開發、測試、正式）
- 設定託管身份身份驗證
- 實作環境特定配置

**💡 本章目標**：使用適當身份驗證與安全管理多環境

---

### 🏗️ 第四章：基礎設施即程式碼與部署
**先決條件**：完成第一到三章  
**時間長度**：1-1.5 小時  
**難易度**：⭐⭐⭐

#### 您將學到
- 進階部署模式
- 使用 Bicep 實作基礎設施即程式碼
- 資源提供策略

#### 學習資源
- **📖 部署**：[部署指南](docs/deployment/deployment-guide.md) - 完整工作流程
- **🏗️ 提供資源**：[資源提供](docs/deployment/provisioning.md) - Azure 資源管理
- **📝 範例**：[Container App 範例](../../examples/container-app) - 容器化部署

#### 實務練習
- 建立自訂 Bicep 範本
- 部署多服務應用
- 實作藍綠部署策略

**💡 本章目標**：運用自訂基礎設施範本部署複雜多服務應用

---
### 🎯 第五章：多代理 AI 解決方案（進階）
**先決條件**：完成第一至第二章  
**時長**：2-3 小時  
**難度**：⭐⭐⭐⭐

#### 你將學到
- 多代理架構模式
- 代理協同與協調
- 生產環境 AI 部署

#### 學習資源
- **🤖 精選專案**：[零售多代理解決方案](examples/retail-scenario.md) - 完整實作
- **🛠️ ARM 範本**：[ARM 範本套件](../../examples/retail-multiagent-arm-template) - 一鍵式部署
- **📖 架構**：[多代理協調模式](/docs/pre-deployment/coordination-patterns.md) - 模式

#### 實作練習
```bash
# 部署完整嘅零售多代理方案
cd examples/retail-multiagent-arm-template
./deploy.sh

# 探索代理配置
az deployment group show --resource-group <rg-name> --name <deployment-name>
```

**💡 章節成果**：部署及管理具備客戶與庫存代理之生產級多代理 AI 解決方案

---

### 🔍 第六章：部署前驗證與規劃
**先決條件**：完成第四章  
**時長**：1 小時  
**難度**：⭐⭐

#### 你將學到
- 容量規劃與資源驗證
- SKU 選擇策略
- 預檢與自動化

#### 學習資源
- **📊 規劃**：[容量規劃](docs/pre-deployment/capacity-planning.md) - 資源驗證
- **💰 選擇**：[SKU 選擇](docs/pre-deployment/sku-selection.md) - 成本效益選擇
- **✅ 驗證**：[預檢檢查](docs/pre-deployment/preflight-checks.md) - 自動化腳本

#### 實作練習
- 執行容量驗證腳本
- 優化 SKU 選擇以降低成本
- 實施自動化部署前檢查

**💡 章節成果**：驗證及優化部署前的環境與配置

---

### 🚨 第七章：故障排除與除錯
**先決條件**：完成任何部署章節  
**時長**：1-1.5 小時  
**難度**：⭐⭐

#### 你將學到
- 系統性除錯方法
- 常見問題與解決方案
- AI 專屬故障排除

#### 學習資源
- **🔧 常見問題**：[常見問題](docs/troubleshooting/common-issues.md) - 常見問答與解決方法
- **🕵️ 除錯**：[除錯指南](docs/troubleshooting/debugging.md) - 循序策略
- **🤖 AI 問題**：[AI 專屬故障排除](docs/troubleshooting/ai-troubleshooting.md) - AI 服務問題

#### 實作練習
- 診斷部署失敗
- 解決驗證問題
- 除錯 AI 服務連線問題

**💡 章節成果**：獨立診斷及解決常見部署問題

---

### 🏢 第八章：生產與企業模式
**先決條件**：完成第一至第四章  
**時長**：2-3 小時  
**難度**：⭐⭐⭐⭐

#### 你將學到
- 生產環境部署策略
- 企業安全模式
- 監控與成本優化

#### 學習資源
- **🏭 生產**：[生產 AI 最佳實務](docs/microsoft-foundry/production-ai-practices.md) - 企業模式
- **📝 範例**：[微服務範例](../../examples/microservices) - 複雜架構
- **📊 監控**：[Application Insights 整合](docs/pre-deployment/application-insights.md) - 監控

#### 實作練習
- 實施企業安全模式
- 設定完整監控系統
- 以正確治理方式部署至生產環境

**💡 章節成果**：部署具備完整生產能力的企業級應用

---

## 🎓 工作坊概覽：實作學習體驗

> **⚠️ 工作坊狀態：開發中**  
> 工作坊教材目前持續開發與優化中，核心模組已運作，有部分進階內容尚未完成，我們正積極補足全部內容。  [追蹤進度 →](workshop/README.md)

### 互動式工作坊教材
**結合瀏覽器式工具與引導式練習，打造完整實作學習**

本工作坊教材提供結構化且互動的學習體驗，輔助上述章節式課程設計，適合自學與講師帶領。

#### 🛠️ 工作坊特色
- **瀏覽器介面**：完整 MkDocs 支援，包含搜尋、複製與主題功能
- **GitHub Codespaces 整合**：一鍵設定開發環境
- **結構化學習路徑**：7 步驟引導式練習（共 3.5 小時）
- **探索 → 部署 → 自訂**：漸進式方法
- **互動式 DevContainer 環境**：預先設定的工具與依賴

#### 📚 工作坊架構
工作坊依據 **探索 → 部署 → 自訂** 流程：

1. **探索階段**（45 分鐘）
   - 探索 Microsoft Foundry 範本與服務
   - 理解多代理架構模式
   - 檢視部署需求與前置條件

2. **部署階段**（2 小時）
   - 實作使用 AZD 部署 AI 應用
   - 配置 Azure AI 服務與端點
   - 實施安全與認證模式

3. **自訂階段**（45 分鐘）
   - 修改應用實現特定用例
   - 優化生產部署
   - 部署監控與成本管理

#### 🚀 開始工作坊
```bash
# 選項 1：GitHub Codespaces（推薦）
# 在儲存庫中按「Code」→「Create codespace on main」

# 選項 2：本地開發
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# 跟隨 workshop/README.md 中的設定說明
```

#### 🎯 工作坊學習成果
完成工作坊後，學員將能：
- **部署生產級 AI 應用**：結合 AZD 與 Microsoft Foundry 服務
- **精通多代理架構**：實作協調 AI 代理解決方案
- **實踐安全最佳實務**：配置認證與存取控制
- **優化擴展效能**：設計成本效益高且效能良好的部署
- **故障排解能力**：獨立解決常見部署問題

#### 📖 工作坊資源
- **🎥 互動指南**：[工作坊教材](workshop/README.md) - 瀏覽器學習環境
- **📋 詳細步驟說明**：[引導式練習](../../workshop/docs/instructions) - 詳盡導覽
- **🛠️ AI 工作坊實驗室**：[AI 工作坊實驗室](docs/microsoft-foundry/ai-workshop-lab.md) - AI 重點練習
- **💡 快速入門**：[工作坊設定指南](workshop/README.md#quick-start) - 環境設定

**適用於**：企業培訓、大學課程、自學與開發者密集訓練營。

---

## 📖 什麼是 Azure Developer CLI？

Azure Developer CLI（azd）是一個以開發者為中心的命令行介面，能加速應用程式建置與部署至 Azure 的流程。功能包括：

- **範本化部署** — 使用預建範本實現常見應用模式
- **基礎設施即程式碼** — 透過 Bicep 或 Terraform 管理 Azure 資源  
- **整合工作流程** — 無縫配置、部署與監控應用程式
- **開發者友善** — 優化提升開發者生產力與體驗

### **AZD 與 Microsoft Foundry：AI 部署理想組合**

**為何選擇 AZD 來部署 AI 解決方案？** AZD 針對 AI 開發者面臨的主要挑戰提供對應：

- **AI 專用範本** — 預配置 Azure OpenAI、認知服務與機器學習工作負載範本
- **安全 AI 部署** — 內建 AI 服務、API 金鑰與模型端點安全模式  
- **生產 AI 模式** — 可擴展且成本效益高的 AI 應用最佳實務
- **端到端 AI 工作流程** — 從模型開發到生產部署並實施監控
- **成本優化** — 智慧資源配置與調整 AI 工作負載
- **Microsoft Foundry 整合** — 無縫連結 Microsoft Foundry 模型目錄與端點

---

## 🎯 範本與範例庫

### 精選：Microsoft Foundry 範本
**若要部署 AI 應用，請從這裡開始！**

> **注意：**這些範本示範多種 AI 模式。部分為外部 Azure 範例，部分為本地實作。

| 範本 | 章節 | 難度 | 服務 | 類型 |
|------|------|------|------|------|
| [**AI 聊天快速上手**](https://github.com/Azure-Samples/get-started-with-ai-chat) | 第二章 | ⭐⭐ | AzureOpenAI + Azure AI 模型推論 API + Azure AI 搜尋 + Azure Container Apps + Application Insights | 外部 |
| [**AI 代理快速上手**](https://github.com/Azure-Samples/get-started-with-ai-agents) | 第二章 | ⭐⭐ | Azure AI 代理服務 + AzureOpenAI + Azure AI 搜尋 + Azure Container Apps + Application Insights | 外部 |
| [**Azure 搜尋 + OpenAI 示範**](https://github.com/Azure-Samples/azure-search-openai-demo) | 第二章 | ⭐⭐ | AzureOpenAI + Azure AI 搜尋 + App Service + 儲存 | 外部 |
| [**OpenAI 聊天應用快速啟動**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | 第二章 | ⭐ | AzureOpenAI + Container Apps + Application Insights | 外部 |
| [**Agent OpenAI Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | 第五章 | ⭐⭐⭐ | AzureOpenAI + Azure Functions + Prompty | 外部 |
| [**Contoso Chat RAG**](https://github.com/Azure-Samples/contoso-chat) | 第八章 | ⭐⭐⭐⭐ | AzureOpenAI + AI 搜尋 + Cosmos DB + Container Apps | 外部 |
| [**零售多代理解決方案**](examples/retail-scenario.md) | 第五章 | ⭐⭐⭐⭐ | AzureOpenAI + AI 搜尋 + 儲存 + Container Apps + Cosmos DB | **本地** |

### 精選：完整學習範例
**生產就緒的應用範本，對應學習章節**

| 範本 | 學習章節 | 難度 | 主要學習內容 |
|------|----------|------|--------------|
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | 第二章 | ⭐ | 基本 AI 部署模式 |
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | 第二章 | ⭐⭐ | 利用 Azure AI 搜尋實作 RAG |
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | 第四章 | ⭐⭐ | 文件智能整合 |
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | 第五章 | ⭐⭐⭐ | 代理框架與函式呼叫 |
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | 第八章 | ⭐⭐⭐ | 企業級 AI 協作 |
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | 第五章 | ⭐⭐⭐⭐ | 客戶與庫存代理多代理架構 |

### 範例類型學習

> **📌 本地與外部範例：**  
> **本地範例**（儲存在本倉庫）= 可立即使用  
> **外部範例**（Azure 範例）= 從連結的外部資源庫克隆

#### 本地範例（可立即使用）
- [**零售多代理解決方案**](examples/retail-scenario.md) - 完整生產就緒實作含 ARM 範本
  - 多代理架構（客戶代理 + 庫存代理）
  - 全面監控與評估
  - 一鍵 ARM 範本部署

#### 本地範例 - 容器應用（第二至第五章）
**本儲存庫的完整容器部署範例：**
- [**容器應用範例**](examples/container-app/README.md) - 容器化部署全方位指南
  - [簡易 Flask API](../../examples/container-app/simple-flask-api) - 具備零擴展及縮減的基本 REST API
  - [微服務架構](../../examples/container-app/microservices) - 生產就緒多服務部署
  - 快速入門、生產與進階部署模式
  - 監控、安全與成本優化指引

#### 外部範例 - 簡單應用（第一至第二章）
**克隆下列 Azure 範例資源庫開始使用：**
- [簡單網頁應用 - Node.js + MongoDB](https://github.com/Azure-Samples/todo-nodejs-mongo) - 基本部署模式
- [靜態網站 - React SPA](https://github.com/Azure-Samples/todo-csharp-sql-swa-func) - 靜態內容部署
- [容器應用 - Python Flask](https://github.com/Azure-Samples/container-apps-store-api-microservice) - REST API 部署

#### 外部範例 - 資料庫整合（第三至第四章）  
- [資料庫應用 - C# + SQL](https://github.com/Azure-Samples/todo-csharp-sql) - 資料庫連接模式
- [Functions + Cosmos DB](https://github.com/Azure-Samples/todo-python-mongo-swa-func) - 無伺服器資料工作流

#### 外部範例 - 進階模式（第四至第八章）
- [Java 微服務](https://github.com/Azure-Samples/java-microservices-aca-lab) - 多服務架構
- [容器應用工作](https://github.com/Azure-Samples/container-apps-jobs) - 背景處理  
- [企業 ML 流水線](https://github.com/Azure-Samples/mlops-v2) - 生產就緒 ML 模式

### 外部範本合集
- [**官方 AZD 範本庫**](https://azure.github.io/awesome-azd/) - 精選官方與社群範本集錦
- [**Azure Developer CLI 範本**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - Microsoft Learn 範本文檔
- [**範例目錄**](examples/README.md) - 本地學習範例與詳細說明

---

## 📚 學習資源與參考資料

### 快速參考
- [**指令速查表**](resources/cheat-sheet.md) - 依章節整理的關鍵 azd 指令
- [**詞彙表**](resources/glossary.md) - Azure 與 azd 專業術語
- [**常見問題**](resources/faq.md) - 按學習章節分類的常見問題
- [**學習指南**](resources/study-guide.md) - 全面練習題

### 實作工作坊
- [**AI 工作坊實驗室**](docs/microsoft-foundry/ai-workshop-lab.md) - 讓你的 AI 解決方案可用 AZD 部署（2-3 小時）
- [**互動工作坊指南**](workshop/README.md) - 使用 MkDocs 與 DevContainer 環境的瀏覽器工作坊
- [**結構化學習路徑**](../../workshop/docs/instructions) - 7 步驟引導練習（探索 → 部署 → 客製化）
- [**AZD 初學者工作坊**](workshop/README.md) - 完整實作工作坊教材與 GitHub Codespaces 整合

### 外部學習資源
- [Azure Developer CLI 文件](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)
- [Azure 架構中心](https://learn.microsoft.com/en-us/azure/architecture/)
- [Azure 價格計算器](https://azure.microsoft.com/pricing/calculator/)
- [Azure 狀態](https://status.azure.com/)

---

## 🔧 快速故障排除指南

**初學者常見問題與即時解決方法：**

### ❌「azd: command not found」

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

### ❌「找不到訂閱」或「訂閱未設定」

```bash
# 列出可用訂閱
az account list --output table

# 設定預設訂閱
az account set --subscription "<subscription-id-or-name>"

# 設定為 AZD 環境
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# 驗證
az account show
```

### ❌「InsufficientQuota」或「超出配額」

```bash
# 嘗試不同嘅 Azure 地區
azd env set AZURE_LOCATION "westus2"
azd up

# 或者喺開發時用細啲嘅 SKU
# 編輯 infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```

### ❌「azd up」執行到一半失敗

```bash
# 選項 1：清除並重試
azd down --force --purge
azd up

# 選項 2：只修復基建
azd provision

# 選項 3：檢查詳細日誌
azd show
azd logs
```

### ❌「身份驗證失敗」或「權杖過期」

```bash
# 重新驗證
az logout
az login

azd auth logout
azd auth login

# 核實身份驗證
az account show
```

### ❌「資源已存在」或命名衝突

```bash
# AZD 會產生獨特名稱，但如果有衝突：
azd down --force --purge

# 然後在新環境中重試
azd env new dev-v2
azd up
```

### ❌ 範本部署時間過長

**正常等待時間：**
- 簡單網站應用：5-10 分鐘
- 附帶資料庫應用：10-15 分鐘
- AI 應用程式：15-25 分鐘（OpenAI 佈建較慢）

```bash
# 檢查進度
azd show

# 如果卡住超過30分鐘，檢查Azure門戶：
azd monitor
# 尋找失敗的部署
```

### ❌「權限拒絕」或「禁止存取」

```bash
# 檢查你嘅 Azure 角色
az role assignment list --assignee $(az account show --query user.name -o tsv)

# 你最少需要「貢獻者」角色
# 請你嘅 Azure 管理員授予：
# - 貢獻者（用於資源）
# - 使用者存取管理員（用於角色指派）
```

### ❌ 找不到已部署應用程式的 URL

```bash
# 顯示所有服務端點
azd show

# 或打開 Azure 入口網站
azd monitor

# 檢查特定服務
azd env get-values
# 尋找 *_URL 變量
```

### 📚 完整故障排除資源

- **常見問題指南：** [詳細解決方案](docs/troubleshooting/common-issues.md)
- **AI 專用問題：** [AI 故障排除](docs/troubleshooting/ai-troubleshooting.md)
- **除錯指南：** [逐步除錯](docs/troubleshooting/debugging.md)
- **求助管道：** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🔧 快速故障排除指南

**初學者常見問題與即時解決方法：**

<details>
<summary><strong>❌「azd: command not found」</strong></summary>

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
<summary><strong>❌「找不到訂閱」或「訂閱未設定」</strong></summary>

```bash
# 列出可用訂閱
az account list --output table

# 設定預設訂閱
az account set --subscription "<subscription-id-or-name>"

# 設定用於 AZD 環境
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# 驗證
az account show
```
</details>

<details>
<summary><strong>❌「InsufficientQuota」或「超出配額」</strong></summary>

```bash
# 嘗試不同嘅 Azure 區域
azd env set AZURE_LOCATION "westus2"
azd up

# 或者喺開發期間使用較細嘅 SKU
# 編輯 infra/main.parameters.json：
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>

<details>
<summary><strong>❌「azd up」執行到一半失敗</strong></summary>

```bash
# 選項 1：清理並重試
azd down --force --purge
azd up

# 選項 2：只修復基建
azd provision

# 選項 3：查看詳細日誌
azd show
azd logs
```
</details>

<details>
<summary><strong>❌「身份驗證失敗」或「權杖過期」</strong></summary>

```bash
# 重新認證
az logout
az login

azd auth logout
azd auth login

# 驗證認證
az account show
```
</details>

<details>
<summary><strong>❌「資源已存在」或命名衝突</strong></summary>

```bash
# AZD 會生成獨特名稱，但如有衝突：
azd down --force --purge

# 則重試使用新環境
azd env new dev-v2
azd up
```
</details>

<details>
<summary><strong>❌ 範本部署時間過長</strong></summary>

**正常等待時間：**
- 簡單網站應用：5-10 分鐘
- 附帶資料庫應用：10-15 分鐘
- AI 應用程式：15-25 分鐘（OpenAI 佈建較慢）

```bash
# 檢查進度
azd show

# 如果卡住超過30分鐘，請檢查Azure入口網站：
azd monitor
# 尋找失敗的部署
```
</details>

<details>
<summary><strong>❌「權限拒絕」或「禁止存取」</strong></summary>

```bash
# 檢查您的 Azure 角色
az role assignment list --assignee $(az account show --query user.name -o tsv)

# 您至少需要「貢獻者」角色
# 請您的 Azure 管理員授予：
# - 貢獻者（適用於資源）
# - 使用者存取管理員（適用於角色分配）
```
</details>

<details>
<summary><strong>❌ 找不到已部署應用程式的 URL</strong></summary>

```bash
# 顯示所有服務端點
azd show

# 或打開 Azure 門戶
azd monitor

# 檢查特定服務
azd env get-values
# 尋找 *_URL 變量
```
</details>

### 📚 完整故障排除資源

- **常見問題指南：** [詳細解決方案](docs/troubleshooting/common-issues.md)
- **AI 專用問題：** [AI 故障排除](docs/troubleshooting/ai-troubleshooting.md)
- **除錯指南：** [逐步除錯](docs/troubleshooting/debugging.md)
- **求助管道：** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🎓 課程完成與認證

### 進度追蹤
追蹤你每個章節的學習進度：

- [ ] **第 1 章**：基礎與快速入門 ✅
- [ ] **第 2 章**：AI 為先的開發 ✅  
- [ ] **第 3 章**：設定與身份驗證 ✅
- [ ] **第 4 章**：基礎架構即程式碼與部署 ✅
- [ ] **第 5 章**：多代理 AI 解決方案 ✅
- [ ] **第 6 章**：部署前驗證與規劃 ✅
- [ ] **第 7 章**：故障排除與除錯 ✅
- [ ] **第 8 章**：生產環境與企業模式 ✅

### 學習驗證
完成每個章節後，透過以下方式驗證你的知識：
1. **實作練習**：完成章節的實作部署
2. **知識檢核**：檢視該章節的常見問題區
3. **社群討論**：在 Azure Discord 分享你的經驗
4. **下一章節**：進入下一階段的學習內容

### 課程完成收益
完成所有章節後，你將擁有：
- **生產經驗**：成功於 Azure 部署真實 AI 應用
- **專業技能**：企業級部署能力  
- **社群認可**：活躍的 Azure 開發者社群會員
- **職涯提升**：備受需求的 AZD 與 AI 部署專長

---

## 🤝 社群與支援

### 尋求幫助與支援
- **技術問題**：[回報錯誤與功能請求](https://github.com/microsoft/azd-for-beginners/issues)
- **學習問題**：[Microsoft Azure Discord 社群](https://discord.gg/microsoft-azure) 與 [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **AI 專用支援**：加入 [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **文件資源**： [官方 Azure Developer CLI 文件](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)

### Microsoft Foundry Discord 社群洞察

**#Azure 頻道最新調查結果：**
- **45%** 的開發者想用 AZD 來處理 AI 工作負載
- **最大挑戰**：多服務部署、憑證管理、生產環境準備  
- **最受期待**：AI 專用範本、故障排除指南、最佳實踐

**加入我們的社群獲得：**
- 分享你的 AZD + AI 經驗並取得協助
- 優先使用新 AI 範本預覽版
- 共同制定 AI 部署最佳實務
- 影響未來 AI + AZD 功能開發

### 課程貢獻指南
歡迎各種貢獻！請參閱我們的 [貢獻指南](CONTRIBUTING.md) 了解更多：
- **內容改進**：強化現有章節與範例
- **新增範例**：增加實務情境與範本  
- **翻譯協助**：維護多語言支援
- **錯誤回報**：提升準確度與清晰度
- **社群準則**：遵守我們的包容性社群規範

---

## 📄 課程資訊

### 授權條款
本專案以 MIT 授權條款釋出 — 詳見 [LICENSE](../../LICENSE) 檔案。

### 相關 Microsoft 學習資源

我們團隊製作了其他全面學習課程：

<!-- CO-OP TRANSLATOR OTHER COURSES START -->
### LangChain
[![LangChain4j 初學者](https://img.shields.io/badge/LangChain4j%20for%20Beginners-22C55E?style=for-the-badge&&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchain4j-for-beginners)
[![LangChain.js 初學者](https://img.shields.io/badge/LangChain.js%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchainjs-for-beginners?WT.mc_id=m365-94501-dwahlin)

---

### Azure / Edge / MCP / Agents
[![AZD 初學者](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)
[![邊緣 AI 初學者](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![MCP 初學者](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)
[![AI 代理人初學者](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### 生成式 AI 系列
[![生成式 AI 初學者](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![生成式 AI (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
[![生成式 AI (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)
[![生成式 AI (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---
 
### 核心學習
[![ML 初學者](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![數據科學入門](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![人工智能入門](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![網絡安全入門](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![網頁開發入門](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![物聯網入門](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![擴增實境開發入門](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Copilot 系列
[![AI 搭檔程式設計的 Copilot](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![C#/.NET 的 Copilot](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Copilot 冒險](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ 課程導航

**🚀 準備開始學習？**

**初學者**：從[第 1 章：基礎與快速起步](../..)開始  
**人工智能開發者**：跳至[第 2 章：AI 優先開發](../..)  
**有經驗的開發者**：從[第 3 章：配置與認證](../..)開始

**下一步**：[開始第 1 章 - AZD 基礎](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**免責聲明**：  
本文件由AI翻譯服務 [Co-op Translator](https://github.com/Azure/co-op-translator) 翻譯而成。雖然我們力求準確，但請注意自動翻譯可能包含錯誤或不準確之處。原始文件的母語版本應視為權威來源。對於重要資訊，建議採用專業人工翻譯。對因使用本翻譯所引致的任何誤解或誤釋，我們概不負責。
<!-- CO-OP TRANSLATOR DISCLAIMER END -->