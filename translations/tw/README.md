<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T12:52:44+00:00",
  "source_file": "README.md",
  "language_code": "tw"
}
-->
> 注意：本文件持續更新以反映最新變更。

> ⚠️ 本存放庫為示範用途，展示
> 使用 Localizeflow 的自動化文件本地化。
>
> 原始內容基於
> Microsoft 的「AZD for Beginners」專案。


# AZD For Beginners：有結構的學習旅程

![AZD-for-beginners](../../translated_images/azdbeginners.5527441dd9f74068.tw.png) 

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## 開始這門課程

請依照以下步驟開始您的 AZD 學習旅程：

1. **派生此存放庫**：點擊 [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)
2. **複製存放庫**：`git clone https://github.com/microsoft/azd-for-beginners.git`
3. **加入社群**：[Azure Discord 社群](https://discord.com/invite/ByRwuEEgH4) 尋求專家協助
4. **選擇您的學習路線**：從下方章節選擇符合您經驗的路線

### 多語言支援

#### 自動翻譯（持續更新）

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[阿拉伯語](../ar/README.md) | [孟加拉語](../bn/README.md) | [保加利亞語](../bg/README.md) | [緬甸語](../my/README.md) | [中文（簡體）](../zh/README.md) | [中文（繁體，香港）](../hk/README.md) | [中文（繁體，澳門）](../mo/README.md) | [中文（繁體，台灣）](./README.md) | [克羅埃西亞語](../hr/README.md) | [捷克語](../cs/README.md) | [丹麥語](../da/README.md) | [荷蘭語](../nl/README.md) | [愛沙尼亞語](../et/README.md) | [芬蘭語](../fi/README.md) | [法語](../fr/README.md) | [德語](../de/README.md) | [希臘語](../el/README.md) | [希伯來語](../he/README.md) | [印地語](../hi/README.md) | [匈牙利語](../hu/README.md) | [印尼語](../id/README.md) | [義大利語](../it/README.md) | [日語](../ja/README.md) | [坎那達語](../kn/README.md) | [韓語](../ko/README.md) | [立陶宛語](../lt/README.md) | [馬來語](../ms/README.md) | [馬拉雅拉姆語](../ml/README.md) | [馬拉地語](../mr/README.md) | [尼泊爾語](../ne/README.md) | [奈及利亞皮欽語](../pcm/README.md) | [挪威語](../no/README.md) | [波斯語（法爾西語）](../fa/README.md) | [波蘭語](../pl/README.md) | [葡萄牙語（巴西）](../br/README.md) | [葡萄牙語（葡萄牙）](../pt/README.md) | [旁遮普語（古魯穆奇字母）](../pa/README.md) | [羅馬尼亞語](../ro/README.md) | [俄語](../ru/README.md) | [塞爾維亞語（西里爾字母）](../sr/README.md) | [斯洛伐克語](../sk/README.md) | [斯洛文尼亞語](../sl/README.md) | [西班牙語](../es/README.md) | [斯瓦希里語](../sw/README.md) | [瑞典語](../sv/README.md) | [他加祿語（菲律賓語）](../tl/README.md) | [坦米爾語](../ta/README.md) | [泰盧固語](../te/README.md) | [泰語](../th/README.md) | [土耳其語](../tr/README.md) | [烏克蘭語](../uk/README.md) | [烏爾都語](../ur/README.md) | [越南語](../vi/README.md)

> **偏好本機複製？**

> 本存放庫包含50多種語言翻譯，會大幅增加下載大小。若想不含翻譯檔案複製，請使用稀疏檢出：
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> 這樣您可以更快速下載所需的課程內容。
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## 課程概覽

透過設計良好的章節，循序漸進掌握 Azure Developer CLI (azd)。**特別著重於結合 Microsoft Foundry 的 AI 應用部署。**

### 為什麼現代開發者必須學這門課

根據 Microsoft Foundry Discord 社群調查，**45% 的開發者想用 AZD 進行 AI 工作載入**，但碰到下列挑戰：
- 複雜的多服務 AI 架構
- AI 產線部署最佳實務  
- Azure AI 服務整合與設定
- AI 工作負載的成本優化
- AI 相關部署疑難排解

### 學習目標

完成此結構化課程後，您將能夠：
- **掌握 AZD 基礎**：核心概念、安裝和設定
- **部署 AI 應用**：利用 AZD 搭配 Microsoft Foundry 服務
- **實現基礎設施即程式碼**：使用 Bicep 模板管理 Azure 資源
- **疑難排解部署**：解決常見問題並除錯
- **優化生產環境**：安全性、擴充、監控及成本管控
- **建置多代理解決方案**：部署複雜 AI 架構

## 📚 學習章節

*根據經驗與目標選擇您的學習路徑*

### 🚀 第1章：基礎與快速起步
**前置條件**：Azure 訂閱，基本命令列知識  
**時長**：30-45 分鐘  
**難度**：⭐

#### 您將學到
- Azure Developer CLI 基本概念介紹
- 在您的平台安裝 AZD
- 完成第一個成功部署

#### 學習資源
- **🎯 起點**：[什麼是 Azure Developer CLI？](../..)
- **📖 理論**：[AZD 基礎知識](docs/getting-started/azd-basics.md) - 核心概念與術語
- **⚙️ 設定**：[安裝與設定](docs/getting-started/installation.md) - 平台特定指南
- **🛠️ 實作**：[您的第一個專案](docs/getting-started/first-project.md) - 循序漸進教程
- **📋 快速參考**：[命令小抄](resources/cheat-sheet.md)

#### 實務練習
```bash
# 快速安裝檢查
azd version

# 部署您的第一個應用程式
azd init --template todo-nodejs-mongo
azd up
```

**💡 章節成果**：成功使用 AZD 部署簡單的 Web 應用程式到 Azure

**✅ 成功驗證：**
```bash
# 完成第一章後，您應該能夠：
azd version              # 顯示已安裝的版本
azd init --template todo-nodejs-mongo  # 初始化專案
azd up                  # 部署到 Azure
azd show                # 顯示執行中的應用程式 URL
# 應用程式在瀏覽器中開啟並運作
azd down --force --purge  # 清理資源
```

**📊 時間投入：** 30-45 分鐘  
**📈 學習後技能：** 可以獨立部署基礎應用程式

**✅ 成功驗證：**
```bash
# 完成第一章後，你應該能夠：
azd version              # 顯示已安裝的版本
azd init --template todo-nodejs-mongo  # 初始化專案
azd up                  # 部署到 Azure
azd show                # 顯示執行中應用程式的 URL
# 應用程式在瀏覽器中開啟且運作正常
azd down --force --purge  # 清除資源
```

**📊 時間投入：** 30-45 分鐘  
**📈 學習後技能：** 可以獨立部署基礎應用程式

---

### 🤖 第2章：以 AI 為先的開發（推薦 AI 開發者）
**前置條件**：完成第1章  
**時長**：1-2 小時  
**難度**：⭐⭐

#### 您將學到
- Microsoft Foundry 與 AZD 整合
- 部署 AI 動力的應用程式
- 理解 AI 服務設定

#### 學習資源
- **🎯 起點**：[Microsoft Foundry 整合](docs/microsoft-foundry/microsoft-foundry-integration.md)
- **📖 範例模式**：[AI 模型部署](docs/microsoft-foundry/ai-model-deployment.md) - 部署與管理 AI 模型
- **🛠️ 工作坊**：[AI 工作坊實驗室](docs/microsoft-foundry/ai-workshop-lab.md) - 讓您的 AI 解決方案與 AZD 相容
- **🎥 互動指南**：[工作坊資源](workshop/README.md) - 使用 MkDocs * DevContainer 環境的瀏覽器學習
- **📋 範本**：[Microsoft Foundry 範本](../..)
- **📝 範例**：[AZD 部署範例](examples/README.md)

#### 實務練習
```bash
# 部署您的第一個人工智慧應用程式
azd init --template azure-search-openai-demo
azd up

# 嘗試更多人工智慧範本
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```

**💡 章節成果**：部署並設定具備 RAG 功能的 AI 聊天應用程式

**✅ 成功驗證：**
```bash
# 在第2章之後，您應該能夠：
azd init --template azure-search-openai-demo
azd up
# 測試AI聊天介面
# 提問並獲得帶有來源的AI回應
# 驗證搜尋整合功能是否有效
azd monitor  # 檢查應用程式洞察是否顯示遙測資料
azd down --force --purge
```

**📊 時間投入：** 1-2 小時  
**📈 學習後技能：** 能部署設定生產級的 AI 應用程式  
**💰 成本認知：** 理解開發每月約80-150美元，生產環境約300-3500美元

#### 💰 AI 部署的成本考量

**開發環境（估計每月80-150美元）：**
- Azure OpenAI（按使用付費）：每月0-50美元（根據 token 使用量）
- AI 搜尋（基本層）：75美元/月
- 容器應用（消耗模式）：0-20美元/月
- 儲存體（標準）：1-5美元/月

**生產環境（估計每月300-3,500美元以上）：**
- Azure OpenAI（PTU 保持穩定效能）：每月3,000美元以上 或 按使用量付費但大量使用
- AI 搜尋（標準層）：250美元/月
- 容器應用（專用）：50-100美元/月
- Application Insights：5-50美元/月
- 儲存體（高級）：10-50美元/月

**💡 成本優化技巧：**
- 使用 **免費層** 的 Azure OpenAI 學習（包含每月 50,000 token）
- 開發不使用時，執行 `azd down` 釋放資源
- 先用消耗計費，只有生產環境升級成 PTU
- 部署前用 `azd provision --preview` 預估花費
- 啟用自動調整，只付實際使用量

**成本監控：**
```bash
# 檢查預估月度費用
azd provision --preview

# 在 Azure 入口網站監控實際費用
az consumption budget list --resource-group <your-rg>
```

---

### ⚙️ 第3章：設定與驗證
**前置條件**：完成第1章  
**時長**：45-60 分鐘  
**難度**：⭐⭐

#### 您將學到
- 環境設定與管理
- 驗證與安全最佳實踐
- 資源命名與組織

#### 學習資源
- **📖 設定**：[設定指南](docs/getting-started/configuration.md) - 環境配置
- **🔐 安全**：[驗證模式與託管身份](docs/getting-started/authsecurity.md) - 驗證模式
- **📝 範例**：[資料庫應用範例](examples/database-app/README.md) - AZD 資料庫範例

#### 實務練習
- 設定多個環境（開發、預備、產品）
- 建置托管身份認證
- 實作環境專屬設定

**💡 章節成果**：能管理多環境，具備適當驗證與安全措施

---

### 🏗️ 第4章：基礎設施即程式碼與部署
**前置條件**：完成第1至3章  
**時長**：1-1.5 小時  
**難度**：⭐⭐⭐

#### 您將學到
- 進階部署模式
- 使用 Bicep 執行基礎設施即程式碼
- 資源規劃策略

#### 學習資源
- **📖 部署**：[部署指南](docs/deployment/deployment-guide.md) - 完整工作流程
- **🏗️ 規劃**：[資源規劃](docs/deployment/provisioning.md) - Azure 資源管理
- **📝 範例**：[容器應用範例](../../examples/container-app) - 容器化部署

#### 實務練習
- 建立自訂 Bicep 範本
- 部署多服務應用
- 實施藍綠部署策略

**💡 章節成果**：能使用自訂基礎設施範本部署複雜多服務應用

---
### 🎯 第五章：多代理 AI 解決方案（進階）  
**先決條件**：完成第一至二章  
**時長**：2-3 小時  
**難度**：⭐⭐⭐⭐

#### 你將學習的內容  
- 多代理架構模式  
- 代理協調與調度  
- 生產環境就緒的 AI 部署

#### 學習資源  
- **🤖 精選專案**：[零售多代理解決方案](examples/retail-scenario.md) - 完整實作  
- **🛠️ ARM 模板**：[ARM 模板套件](../../examples/retail-multiagent-arm-template) - 一鍵部署  
- **📖 架構**：[多代理協調模式](/docs/pre-deployment/coordination-patterns.md) - 模式說明

#### 實務練習  
```bash
# 部署完整的零售多代理解決方案
cd examples/retail-multiagent-arm-template
./deploy.sh

# 探索代理配置
az deployment group show --resource-group <rg-name> --name <deployment-name>
```
  
**💡 章節成果**：部署並管理生產環境就緒的多代理 AI 解決方案，包含客戶與庫存代理

---

### 🔍 第六章：部署前驗證與計劃  
**先決條件**：完成第四章  
**時長**：1 小時  
**難度**：⭐⭐

#### 你將學習的內容  
- 容量規劃與資源驗證  
- SKU 選擇策略  
- 預檢與自動化

#### 學習資源  
- **📊 規劃**：[容量規劃](docs/pre-deployment/capacity-planning.md) - 資源驗證  
- **💰 選擇**：[SKU 選擇](docs/pre-deployment/sku-selection.md) - 成本效益選擇  
- **✅ 驗證**：[預檢作業](docs/pre-deployment/preflight-checks.md) - 自動化腳本

#### 實務練習  
- 執行容量驗證腳本  
- 優化 SKU 選擇以降低成本  
- 實作自動化部署前檢查

**💡 章節成果**：在執行前驗證並優化部署方案

---

### 🚨 第七章：故障排除與除錯  
**先決條件**：完成任一部署章節  
**時長**：1-1.5 小時  
**難度**：⭐⭐

#### 你將學習的內容  
- 系統化的除錯方法  
- 常見問題與解決方案  
- AI 特有故障排除

#### 學習資源  
- **🔧 常見問題**：[常見問題](docs/troubleshooting/common-issues.md) - FAQ 與解決方案  
- **🕵️ 除錯**：[除錯指南](docs/troubleshooting/debugging.md) - 分步策略  
- **🤖 AI 問題**：[AI 專屬故障排除](docs/troubleshooting/ai-troubleshooting.md) - AI 服務問題

#### 實務練習  
- 診斷部署失敗原因  
- 解決驗證問題  
- 除錯 AI 服務連線

**💡 章節成果**：能獨立診斷並解決常見部署問題

---

### 🏢 第八章：生產與企業模式  
**先決條件**：完成第一至四章  
**時長**：2-3 小時  
**難度**：⭐⭐⭐⭐

#### 你將學習的內容  
- 生產環境部署策略  
- 企業安全模式  
- 監控與成本優化

#### 學習資源  
- **🏭 生產環境**：[生產 AI 最佳實踐](docs/microsoft-foundry/production-ai-practices.md) - 企業模式  
- **📝 範例**：[微服務範例](../../examples/microservices) - 複雜架構  
- **📊 監控**：[Application Insights 整合](docs/pre-deployment/application-insights.md) - 監控

#### 實務練習  
- 實作企業安全模式  
- 建立完善監控  
- 以適當治理部署到生產環境

**💡 章節成果**：部署具備完整生產能力的企業級應用

---

## 🎓 工作坊總覽：實作學習體驗

> **⚠️ 工作坊狀態：開發中**  
> 工作坊教材正在開發與調整中。核心模組已功能完成，部分進階章節尚未完成。我們正積極完善所有內容。 [追蹤進度 →](workshop/README.md)

### 互動式工作坊教材  
**以瀏覽器為基礎的完整實作學習與引導練習**

本工作坊教材提供結構化、互動式的學習體驗，作為上述章節課程的補充。此工作坊設計適合自學與教師帶領課程。

#### 🛠️ 工作坊特色  
- **瀏覽器介面**：完整的 MkDocs 支援，具備搜尋、複製及主題切換功能  
- **GitHub Codespaces 整合**：一鍵啟動開發環境  
- **結構化學習路徑**：7 步驟引導練習（共 3.5 小時）  
- **探索 → 部署 → 客製化**：漸進式學習法  
- **互動式 DevContainer 環境**：預先設定好工具與相依套件

#### 📚 工作坊架構  
工作坊依照 **探索 → 部署 → 客製化** 的流程：

1. **探索階段**（45 分鐘）  
   - 探索 Microsoft Foundry 範本與服務  
   - 理解多代理架構模式  
   - 了解部署需求與先決條件

2. **部署階段**（2 小時）  
   - 實作 AZD 部署 AI 應用  
   - 設定 Azure AI 服務與端點  
   - 實作安全與驗證模式

3. **客製化階段**（45 分鐘）  
   - 修改應用以符合特定場景  
   - 優化至生產部署標準  
   - 實作監控與成本管理

#### 🚀 開始使用工作坊  
```bash
# 選項 1：GitHub Codespaces（推薦）
# 在儲存庫中點擊「Code」→「在 main 上建立 codespace」

# 選項 2：本地開發
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# 依照 workshop/README.md 中的設定說明進行操作
```
  
#### 🎯 工作坊學習成果  
完成工作坊後，參與者將能：  
- **部署生產級 AI 應用**：利用 AZD 和 Microsoft Foundry 服務  
- **掌握多代理架構**：實現協調的 AI 代理解決方案  
- **實作安全最佳實務**：設定驗證與存取控管  
- **優化規模與成本**：設計具成本效益且效能良好的部署  
- **進行部署故障排除**：獨立解決常見問題

#### 📖 工作坊資源  
- **🎥 互動指南**：[工作坊教材](workshop/README.md) - 瀏覽器學習環境  
- **📋 分步教學**：[引導練習](../../workshop/docs/instructions) - 詳細流程  
- **🛠️ AI 工作坊實驗室**：[AI 工作坊實驗室](docs/microsoft-foundry/ai-workshop-lab.md) - 專注 AI 練習  
- **💡 快速入門**：[工作坊設定指南](workshop/README.md#quick-start) - 環境配置

**適合對象**：企業培訓、大學課程、自學與開發者訓練營

---

## 📖 什麼是 Azure Developer CLI？

Azure Developer CLI (azd) 是專為開發者設計的命令行界面，加快建立與部署至 Azure 的流程。它提供：

- **範本式部署** - 使用預建範本實現常見應用模式  
- **基礎設施即程式碼** - 透過 Bicep 或 Terraform 管理 Azure 資源  
- **整合式工作流程** - 無縫地進行資源配置、部署及監控  
- **開發者友好** - 優化開發者生產力與體驗

### **AZD + Microsoft Foundry：AI 部署的最佳搭配**

**為什麼 AI 解決方案選用 AZD？** AZD 解決 AI 開發者面臨的主要挑戰：

- **AI 就緒範本** - 預先設定 Azure OpenAI、認知服務與機器學習工作負載範本  
- **安全 AI 部署** - 內建 AI 服務、API 金鑰與模型端點的安全模式  
- **生產 AI 模式** - 可擴展且成本效益高的 AI 應用最佳實務  
- **端到端 AI 工作流程** - 從模型開發到生產部署並具備完善監控  
- **成本優化** - 智慧化資源分配與擴展策略  
- **Microsoft Foundry 整合** - 與 Microsoft Foundry 模型目錄及端點無縫連接

---

## 🎯 範本與範例庫

### 精選：Microsoft Foundry 範本  
**如果你要部署 AI 應用，從這裡開始！**

> **注意：** 這些範本展示各種 AI 模式。有些來自外部 Azure 範例，有些是本地實作。

| 範本 | 章節 | 難度 | 服務 | 類型 |
|----------|---------|------------|----------|------|
| [**開始使用 AI 聊天**](https://github.com/Azure-Samples/get-started-with-ai-chat) | 第二章 | ⭐⭐ | AzureOpenAI + Azure AI Model Inference API + Azure AI Search + Azure Container Apps + Application Insights | 外部 |
| [**開始使用 AI 代理**](https://github.com/Azure-Samples/get-started-with-ai-agents) | 第二章 | ⭐⭐ | Azure AI Agent Service + AzureOpenAI + Azure AI Search + Azure Container Apps + Application Insights | 外部 |
| [**Azure Search + OpenAI 範例**](https://github.com/Azure-Samples/azure-search-openai-demo) | 第二章 | ⭐⭐ | AzureOpenAI + Azure AI Search + App Service + Storage | 外部 |
| [**OpenAI 聊天應用快速入門**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | 第二章 | ⭐ | AzureOpenAI + Container Apps + Application Insights | 外部 |
| [**OpenAI 代理 Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | 第五章 | ⭐⭐⭐ | AzureOpenAI + Azure Functions + Prompty | 外部 |
| [**Contoso 聊天 RAG**](https://github.com/Azure-Samples/contoso-chat) | 第八章 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Cosmos DB + Container Apps | 外部 |
| [**零售多代理解決方案**](examples/retail-scenario.md) | 第五章 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Storage + Container Apps + Cosmos DB | **本地** |

### 精選：完整學習場景  
**生產環境就緒的應用範本，搭配學習章節**

| 範本 | 學習章節 | 難度 | 主要學習內容 |
|----------|------------------|------------|--------------|
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | 第二章 | ⭐ | 基本 AI 部署模式 |
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | 第二章 | ⭐⭐ | 以 Azure AI Search 實現 RAG |
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | 第四章 | ⭐⭐ | 文件智能整合 |
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | 第五章 | ⭐⭐⭐ | 代理框架與函式呼叫 |
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | 第八章 | ⭐⭐⭐ | 企業級 AI 協調 |
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | 第五章 | ⭐⭐⭐⭐ | 多代理架構，含客戶與庫存代理 |

### 按範例類型學習

> **📌 本地與外部範例說明：**  
> **本地範例**（此存放庫）= 可立即使用  
> **外部範例**（Azure 範例）= 從連結的存放庫克隆

#### 本地範例（可立即使用）  
- [**零售多代理解決方案**](examples/retail-scenario.md) - 完整生產環境實作，含 ARM 模板  
  - 多代理架構（客戶與庫存代理）  
  - 完善監控與評估  
  - 透過 ARM 模板一鍵部署

#### 本地範例 - 容器應用（第二至五章）  
**本存放庫中完整的容器部署範例：**  
- [**容器應用範例**](examples/container-app/README.md) - 容器化部署完整指南  
  - [簡單 Flask API](../../examples/container-app/simple-flask-api) - 基本 REST API，支援 scale-to-zero  
  - [微服務架構](../../examples/container-app/microservices) - 生產環境級多服務部署  
  - 快速入門、生產、進階部署模式  
  - 監控、安全與成本優化指南

#### 外部範例 - 簡易應用（第一至二章）  
**克隆以下 Azure 範例 GitHub 存放庫開始：**  
- [簡單網頁應用 - Node.js + MongoDB](https://github.com/Azure-Samples/todo-nodejs-mongo) - 基本部署模式  
- [靜態網站 - React SPA](https://github.com/Azure-Samples/todo-csharp-sql-swa-func) - 靜態內容部署  
- [容器應用 - Python Flask](https://github.com/Azure-Samples/container-apps-store-api-microservice) - REST API 部署

#### 外部範例 - 資料庫整合（第三至四章）  
- [資料庫應用 - C# + SQL](https://github.com/Azure-Samples/todo-csharp-sql) - 資料庫連接模式  
- [Functions + Cosmos DB](https://github.com/Azure-Samples/todo-python-mongo-swa-func) - Serverless 資料工作流

#### 外部範例 - 進階模式（第四至八章）  
- [Java 微服務](https://github.com/Azure-Samples/java-microservices-aca-lab) - 多服務架構  
- [容器應用背景工作](https://github.com/Azure-Samples/container-apps-jobs) - 背景處理  
- [企業 ML 流程](https://github.com/Azure-Samples/mlops-v2) - 生產就緒 ML 模式

### 外部模板套件
- [**官方 AZD 範本集**](https://azure.github.io/awesome-azd/) - 精選官方與社群範本收藏
- [**Azure Developer CLI 範本**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - Microsoft Learn 範本文件
- [**範例資料夾**](examples/README.md) - 本機教學範例及詳細說明

---

## 📚 學習資源與參考

### 快速參考
- [**指令速查表**](resources/cheat-sheet.md) - 按章節組織的必要 azd 指令
- [**術語表**](resources/glossary.md) - Azure 與 azd 術語  
- [**常見問題**](resources/faq.md) - 按學習章節整理的常見問題
- [**學習指南**](resources/study-guide.md) - 完整練習題庫

### 實作工作坊
- [**AI 工作坊實驗室**](docs/microsoft-foundry/ai-workshop-lab.md) - 建立可由 AZD 部署的 AI 解決方案（2-3 小時）
- [**互動式工作坊指南**](workshop/README.md) - 基於瀏覽器的 MkDocs 與 DevContainer 環境工作坊
- [**結構化學習路徑**](../../workshop/docs/instructions) - 7 步驟引導練習（探索 → 部署 → 自訂）
- [**AZD 初學者工作坊**](workshop/README.md) - 完整實作教材整合 GitHub Codespaces

### 外部學習資源
- [Azure Developer CLI 文件](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)
- [Azure 架構中心](https://learn.microsoft.com/en-us/azure/architecture/)
- [Azure 定價計算機](https://azure.microsoft.com/pricing/calculator/)
- [Azure 服務狀態](https://status.azure.com/)

---

## 🔧 快速故障排除指南

**初學者常見問題與立即解決方案：**

### ❌ 「azd: 找不到指令」

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

### ❌ 「找不到訂閱」或「未設定訂閱」

```bash
# 列出可用訂閱
az account list --output table

# 設定預設訂閱
az account set --subscription "<subscription-id-or-name>"

# 設定 AZD 環境
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# 驗證
az account show
```

### ❌ 「配額不足」或「配額超限」

```bash
# 嘗試不同的 Azure 區域
azd env set AZURE_LOCATION "westus2"
azd up

# 或在開發中使用較小的 SKU
# 編輯 infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```

### ❌ 「azd up」執行至一半失敗

```bash
# 選項 1：清理並重試
azd down --force --purge
azd up

# 選項 2：僅修復基礎設施
azd provision

# 選項 3：檢查詳細日誌
azd show
azd logs
```

### ❌ 「身份驗證失敗」或「憑證過期」

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
# AZD 會產生唯一名稱，但如果發生衝突：
azd down --force --purge

# 則重新嘗試使用新的環境
azd env new dev-v2
azd up
```

### ❌ 範本部署時間過長

**正常等待時間：**
- 簡單網頁應用：5-10 分鐘
- 含資料庫的應用：10-15 分鐘
- AI 應用：15-25 分鐘（OpenAI 配置較慢）

```bash
# 檢查進度
azd show

# 如果卡住超過30分鐘，請檢查 Azure 入口網站：
azd monitor
# 尋找失敗的部署
```

### ❌ 「權限被拒絕」或「禁止存取」

```bash
# 檢查您的 Azure 角色
az role assignment list --assignee $(az account show --query user.name -o tsv)

# 您至少需要「參與者」角色
# 請您的 Azure 管理員授予：
# - 參與者（資源用）
# - 使用者存取管理員（角色指派用）
```

### ❌ 找不到已部署的應用程式 URL

```bash
# 顯示所有服務端點
azd show

# 或開啟 Azure 入口網站
azd monitor

# 檢查特定服務
azd env get-values
# 尋找 *_URL 變數
```

### 📚 完整故障排除資源

- **常見問題指南：** [詳細解決方案](docs/troubleshooting/common-issues.md)
- **AI 專用問題：** [AI 故障排除](docs/troubleshooting/ai-troubleshooting.md)
- **除錯指南：** [逐步除錯](docs/troubleshooting/debugging.md)
- **取得協助：** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🔧 快速故障排除指南

**初學者常見問題與立即解決方案：**

<details>
<summary><strong>❌ 「azd: 找不到指令」</strong></summary>

```bash
# 首先安裝 AZD
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
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

# 設定 AZD 環境
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# 驗證
az account show
```
</details>

<details>
<summary><strong>❌ 「配額不足」或「配額超限」</strong></summary>

```bash
# 嘗試不同的 Azure 區域
azd env set AZURE_LOCATION "westus2"
azd up

# 或在開發中使用較小的 SKU
# 編輯 infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>

<details>
<summary><strong>❌ 「azd up」執行至一半失敗</strong></summary>

```bash
# 選項1：清理並重試
azd down --force --purge
azd up

# 選項2：僅修復基礎設施
azd provision

# 選項3：檢查詳細日誌
azd show
azd logs
```
</details>

<details>
<summary><strong>❌ 「身份驗證失敗」或「憑證過期」</strong></summary>

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
# AZD 會生成唯一名稱，但如果有衝突：
azd down --force --purge

# 則重新嘗試使用全新環境
azd env new dev-v2
azd up
```
</details>

<details>
<summary><strong>❌ 範本部署時間過長</strong></summary>

**正常等待時間：**
- 簡單網頁應用：5-10 分鐘
- 含資料庫的應用：10-15 分鐘
- AI 應用：15-25 分鐘（OpenAI 配置較慢）

```bash
# 檢查進度
azd show

# 如果卡住超過30分鐘，請檢查Azure入口網站：
azd monitor
# 尋找失敗的部署
```
</details>

<details>
<summary><strong>❌ 「權限被拒絕」或「禁止存取」</strong></summary>

```bash
# 檢查您的 Azure 角色
az role assignment list --assignee $(az account show --query user.name -o tsv)

# 您至少需要「參與者」角色
# 請您的 Azure 管理員授予：
# - 參與者（用於資源）
# - 使用者存取管理員（用於角色指派）
```
</details>

<details>
<summary><strong>❌ 找不到已部署的應用程式 URL</strong></summary>

```bash
# 顯示所有服務端點
azd show

# 或打開 Azure 入口網站
azd monitor

# 檢查特定服務
azd env get-values
# 查找 *_URL 變數
```
</details>

### 📚 完整故障排除資源

- **常見問題指南：** [詳細解決方案](docs/troubleshooting/common-issues.md)
- **AI 專用問題：** [AI 故障排除](docs/troubleshooting/ai-troubleshooting.md)
- **除錯指南：** [逐步除錯](docs/troubleshooting/debugging.md)
- **取得協助：** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🎓 課程完成與認證

### 進度追蹤
追蹤你每個章節的學習進度：

- [ ] **第 1 章**：基礎與快速開始 ✅
- [ ] **第 2 章**：AI 優先開發 ✅  
- [ ] **第 3 章**：設定與身份驗證 ✅
- [ ] **第 4 章**：基礎架構即程式碼與部署 ✅
- [ ] **第 5 章**：多代理 AI 解決方案 ✅
- [ ] **第 6 章**：部署前驗證與規劃 ✅
- [ ] **第 7 章**：故障排除與除錯 ✅
- [ ] **第 8 章**：生產環境與企業模式 ✅

### 學習驗證
完成每章後，透過以下方式確認你的知識：
1. **實務練習**：完成該章的實作部署
2. **知識檢核**：檢視該章 FAQ 內容
3. **社群討論**：分享心得於 Azure Discord
4. **進入下一章**：進階下一複雜度層級

### 課程完成效益
全部章節學完後，你將擁有：
- **生產實務經驗**：成功將真實 AI 應用部署至 Azure
- **專業技能**：企業級部署能力  
- **社群認可**：成為活躍 Azure 開發者成員
- **職涯躍升**：具備熱門 AZD 與 AI 部署專長

---

## 🤝 社群與支援

### 取得協助與支援
- **技術問題**： [回報錯誤與功能需求](https://github.com/microsoft/azd-for-beginners/issues)
- **學習疑問**： [Microsoft Azure Discord 社群](https://discord.gg/microsoft-azure) 與 [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **AI 專項協助**： 加入 [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **文件資源**： [官方 Azure Developer CLI 文件](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)

### Microsoft Foundry Discord 社群洞見

**#Azure 頻道近期調查結果：**
- **45%** 的開發者想用 AZD 進行 AI 工作負載
- **主要挑戰**：多服務部署、憑證管理、生產環境準備  
- **熱門需求**：AI 專用範本、故障排除指南、最佳實踐

**加入我們社群，享有：**
- 分享你的 AZD + AI 經驗與協助
- 優先使用全新 AI 範本預覽
- 參與 AI 部署最佳實踐制定
- 影響未來 AI + AZD 功能發展

### 參與課程貢獻
歡迎你投稿！詳見我們的 [貢獻指南](CONTRIBUTING.md)，內容包含：
- **內容改進**：增強既有章節與範例
- **新增範例**：添加實務情境與範本  
- **翻譯協助**：維護多語系支援
- **問題回報**：提升文件準確與清晰度
- **社群規範**：遵守我們包容性社群指導方針

---

## 📄 課程資訊

### 授權條款
本專案採用 MIT 授權，詳細見 [LICENSE](../../LICENSE) 檔案。

### 微軟相關學習資源

我們團隊推出其他完整學習課程：

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
[![初學者資料科學](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![初學者人工智慧](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![初學者資安](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![初學者網頁開發](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![初學者物聯網](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![初學者擴增實境開發](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Copilot 系列
[![AI 配對程式設計的 Copilot](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![C#/.NET 的 Copilot](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Copilot 冒險](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ 課程導航

**🚀 準備好開始學習了嗎？**

**初學者**：從 [第一章：基礎與快速入門](../..) 開始  
**人工智慧開發者**：直接前往 [第二章：以 AI 為先的開發](../..)  
**有經驗的開發者**：從 [第三章：配置與驗證](../..) 開始

**下一步**：[開始第一章 - AZD 基礎](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**免責聲明**：  
本文件係使用 AI 翻譯服務 [Co-op Translator](https://github.com/Azure/co-op-translator) 進行翻譯。雖然我們致力於達成準確性，但請注意，自動翻譯可能包含錯誤或不準確之處。文件之原始語言版本應視為權威來源。對於重要資訊，建議採用專業人工翻譯。我們不對因使用本翻譯所引起之任何誤解或誤譯負責。
<!-- CO-OP TRANSLATOR DISCLAIMER END -->