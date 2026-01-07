<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T12:56:47+00:00",
  "source_file": "README.md",
  "language_code": "ja"
}
-->
> Note: このドキュメントは最新の変更を反映するために継続的に更新されています。

> ⚠️ このリポジトリは、Localizeflowを使った自動ドキュメントローカリゼーションのデモとして作成されています。
>
> オリジナルの内容はMicrosoftの「AZD for Beginners」プロジェクトに基づいています。


# AZD For Beginners: 構造化された学習の旅

![AZD-for-beginners](../../translated_images/azdbeginners.5527441dd9f74068.ja.png) 

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## このコースの開始方法

以下の手順に従ってAZDの学習を始めましょう：

1. **リポジトリをフォーク**：クリック [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)
2. **リポジトリをクローン**：`git clone https://github.com/microsoft/azd-for-beginners.git`
3. **コミュニティに参加**：[Azure Discord Communities](https://discord.com/invite/ByRwuEEgH4) で専門家からサポートを受ける
4. **学習パスを選択**：自分の経験レベルに合った章を以下から選んでください

### 多言語対応

#### 自動翻訳（常に最新）

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](./README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **ローカルでクローンするのが好みですか？**

> このリポジトリには50以上の言語翻訳が含まれており、ダウンロードサイズが大幅に増加します。翻訳なしでクローンするには、スパースチェックアウトを使用してください：
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> これによりコース完了に必要なすべてを入手でき、ダウンロードが高速化します。
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## コース概要

段階的に学べる章で構成されたAzure Developer CLI (azd) の習得コース。**Microsoft Foundryとの連携によるAIアプリケーションのデプロイに特化。**

### なぜこのコースは現代の開発者に不可欠か

Microsoft Foundry Discordコミュニティの意見に基づき、**45%の開発者がAIワークロードにAZDを使いたい**ものの以下の課題に直面しています：
- 複雑なマルチサービスAIアーキテクチャ
- 本番AIデプロイのベストプラクティス
- Azure AIサービスとの統合と設定
- AIワークロードのコスト最適化
- AI特有のデプロイ問題のトラブルシューティング

### 学習目標

この構造化されたコースを完了すると：
- **AZDの基礎を習得**：コアコンセプト、インストール、設定
- **AIアプリケーションをデプロイ**：Microsoft FoundryサービスとAZDの活用
- **Infrastructure as Codeを実践**：BicepテンプレートでAzureリソース管理
- **デプロイ問題を解決**：一般的な問題のトラブルシューティングとデバッグ
- **本番向け最適化**：セキュリティ、スケーリング、モニタリング、コスト管理
- **マルチエージェントソリューションの構築**：複雑なAIアーキテクチャの展開

## 📚 学習章

*経験レベルと目標に基づき学習パスを選択してください*

### 🚀 Chapter 1: 基礎＆クイックスタート
**前提条件**：Azureサブスクリプション、基本的なコマンドライン知識  
**所要時間**：30-45分  
**難易度**：⭐

#### 学習内容
- Azure Developer CLIの基本理解
- プラットフォームへのAZDインストール
- 最初の正常なデプロイ

#### 学習リソース
- **🎯 はじめに**： [Azure Developer CLIとは？](../..)
- **📖 理論**： [AZDの基礎](docs/getting-started/azd-basics.md) - コアコンセプトと用語
- **⚙️ 設定**： [インストール＆セットアップ](docs/getting-started/installation.md) - プラットフォーム別ガイド
- **🛠️ ハンズオン**： [最初のプロジェクト](docs/getting-started/first-project.md) - ステップバイステップのチュートリアル
- **📋 クイックリファレンス**： [コマンドチートシート](resources/cheat-sheet.md)

#### 実践演習
```bash
# クイックインストールチェック
azd version

# 最初のアプリケーションをデプロイする
azd init --template todo-nodejs-mongo
azd up
```

**💡 章の成果**：AZDを使って簡単なWebアプリケーションをAzureに正常にデプロイ

**✅ 成功の検証：**
```bash
# 第1章を完了した後、以下ができるようになります：
azd version              # インストールされているバージョンを表示します
azd init --template todo-nodejs-mongo  # プロジェクトを初期化します
azd up                  # Azureにデプロイします
azd show                # 実行中のアプリのURLを表示します
# アプリケーションがブラウザで開いて動作します
azd down --force --purge  # リソースをクリーンアップします
```

**📊 所要時間：** 30-45分  
**📈 習得レベル：** 基本的なアプリケーションを独力でデプロイ可能

**✅ 成功の検証：**
```bash
# 第1章を完了すると、以下のことができるようになります:
azd version              # インストールされているバージョンを表示します
azd init --template todo-nodejs-mongo  # プロジェクトを初期化します
azd up                  # Azureにデプロイします
azd show                # 実行中のアプリのURLを表示します
# アプリケーションがブラウザで開き、動作します
azd down --force --purge  # リソースをクリーンアップします
```

**📊 所要時間：** 30-45分  
**📈 習得レベル：** 基本的なアプリケーションを独力でデプロイ可能

---

### 🤖 Chapter 2: AIファースト開発（AI開発者推奨）
**前提条件**：Chapter 1修了  
**所要時間**：1-2時間  
**難易度**：⭐⭐

#### 学習内容
- Microsoft FoundryとAZDの連携
- AI搭載アプリケーションのデプロイ
- AIサービス構成の理解

#### 学習リソース
- **🎯 はじめに**： [Microsoft Foundry連携](docs/microsoft-foundry/microsoft-foundry-integration.md)
- **📖 パターン**： [AIモデルのデプロイ](docs/microsoft-foundry/ai-model-deployment.md) - AIモデルの展開と管理
- **🛠️ ワークショップ**： [AIワークショップラボ](docs/microsoft-foundry/ai-workshop-lab.md) - AIソリューションをAZD対応に
- **🎥 インタラクティブガイド**： [ワークショップ資料](workshop/README.md) - MkDocs * DevContainer環境でのブラウザ学習
- **📋 テンプレート**： [Microsoft Foundryテンプレート](../..)
- **📝 例**： [AZDデプロイ例](examples/README.md)

#### 実践演習
```bash
# 最初のAIアプリケーションをデプロイする
azd init --template azure-search-openai-demo
azd up

# 追加のAIテンプレートを試す
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```

**💡 章の成果**：RAG機能を持つAIチャットアプリのデプロイと設定

**✅ 成功の検証：**
```bash
# 第2章の後、あなたは以下ができるようになっているはずです：
azd init --template azure-search-openai-demo
azd up
# AIチャットインターフェースをテストする
# 質問をして、出典付きのAIによる応答を得る
# 検索統合が機能していることを確認する
azd monitor  # Application Insightsがテレメトリーを表示しているか確認する
azd down --force --purge
```

**📊 所要時間：** 1-2時間  
**📈 習得レベル：** 本番対応可能なAIアプリケーションをデプロイ・設定可能  
**💰 コストの認識：** 開発環境で月額約80～150ドル、本番環境で月額約300～3500ドルのコスト感を理解

#### 💰 AIデプロイのコスト考慮事項

**開発環境（推定 月額80～150ドル）：**
- Azure OpenAI (従量課金)：トークン使用量により月0～50ドル
- AI Search（Basic層）：75ドル/月
- コンテナアプリ（消費課金）：0～20ドル/月
- ストレージ（標準）：1～5ドル/月

**本番環境（推定 月額300～3500ドル以上）：**
- Azure OpenAI (PTUで安定パフォーマンス)：3,000ドル以上/月 または 高負荷の従量課金
- AI Search（Standard層）：250ドル/月
- コンテナアプリ（専用）：50～100ドル/月
- Application Insights：5～50ドル/月
- ストレージ（プレミアム）：10～50ドル/月

**💡 コスト最適化のヒント：**
- 学習時は**無料ティア**のAzure OpenAIを活用（50,000トークン/月含む）
- 開発していない時は`azd down`でリソースの割当を解除
- はじめは従量課金で使用し、本番でのみPTUにアップグレード
- `azd provision --preview`でデプロイ前にコスト見積もり
- オートスケールを有効にし、実使用量に対してのみ課金

**コストモニタリング：**
```bash
# 推定月額費用を確認する
azd provision --preview

# Azure ポータルで実際の費用を監視する
az consumption budget list --resource-group <your-rg>
```

---

### ⚙️ Chapter 3: 設定＆認証
**前提条件**：Chapter 1修了  
**所要時間**：45-60分  
**難易度**：⭐⭐

#### 学習内容
- 環境設定と管理
- 認証とセキュリティのベストプラクティス
- リソース命名と整理

#### 学習リソース
- **📖 設定**： [設定ガイド](docs/getting-started/configuration.md) - 環境構築
- **🔐 セキュリティ**： [認証パターンとマネージドID](docs/getting-started/authsecurity.md) - 認証パターン
- **📝 例**： [データベースアプリ例](examples/database-app/README.md) - AZDデータベースサンプル

#### 実践演習
- 複数環境（開発、ステージング、本番）の設定
- マネージドID認証のセットアップ
- 環境ごとの設定の実装

**💡 章の成果**：適切な認証・セキュリティを備えた複数環境の管理

---

### 🏗️ Chapter 4: Infrastructure as Code & デプロイ
**前提条件**：Chapters 1～3修了  
**所要時間**：1～1.5時間  
**難易度**：⭐⭐⭐

#### 学習内容
- 高度なデプロイパターン
- BicepによるInfrastructure as Code
- リソースプロビジョニング戦略

#### 学習リソース
- **📖 デプロイ**： [デプロイガイド](docs/deployment/deployment-guide.md) - 完全なワークフロー
- **🏗️ プロビジョニング**： [リソースプロビジョニング](docs/deployment/provisioning.md) - Azureリソース管理
- **📝 例**： [コンテナアプリ例](../../examples/container-app) - コンテナ化デプロイ

#### 実践演習
- カスタムBicepテンプレートの作成
- マルチサービスアプリケーションのデプロイ
- ブルーグリーンデプロイ戦略の実装

**💡 章の成果**：カスタムインフラテンプレートを用いて複雑なマルチサービスアプリをデプロイ

---
### 🎯 第5章：マルチエージェントAIソリューション（上級）
**前提条件**: 第1～2章完了  
**所要時間**: 2～3時間  
**難易度**: ⭐⭐⭐⭐

#### 学習内容
- マルチエージェントアーキテクチャパターン
- エージェントのオーケストレーションと調整
- 本番環境対応のAIデプロイメント

#### 学習リソース
- **🤖 注目プロジェクト**: [小売業向けマルチエージェントソリューション](examples/retail-scenario.md) - 完全な実装例
- **🛠️ ARMテンプレート**: [ARMテンプレートパッケージ](../../examples/retail-multiagent-arm-template) - ワンクリック展開
- **📖 アーキテクチャ**: [マルチエージェント調整パターン](/docs/pre-deployment/coordination-patterns.md) - パターン集

#### 実践演習
```bash
# 完全な小売マルチエージェントソリューションを展開する
cd examples/retail-multiagent-arm-template
./deploy.sh

# エージェントの構成を探索する
az deployment group show --resource-group <rg-name> --name <deployment-name>
```

**💡 本章の成果**: カスタマーおよび在庫エージェントによる本番対応マルチエージェントAIソリューションを展開・管理

---

### 🔍 第6章：事前展開の検証と計画
**前提条件**: 第4章完了  
**所要時間**: 1時間  
**難易度**: ⭐⭐

#### 学習内容
- キャパシティプランニングとリソース検証
- SKU選択戦略
- 事前チェックと自動化

#### 学習リソース
- **📊 計画**: [キャパシティプランニング](docs/pre-deployment/capacity-planning.md) - リソース検証
- **💰 選択**: [SKU選択](docs/pre-deployment/sku-selection.md) - コスト効率のよい選択
- **✅ 検証**: [事前チェック](docs/pre-deployment/preflight-checks.md) - 自動化スクリプト

#### 実践演習
- キャパシティ検証スクリプトの実行
- コスト最適化のSKU選択
- 自動事前検証チェックの実装

**💡 本章の成果**: デプロイ前に検証と最適化を行う

---

### 🚨 第7章：トラブルシューティング＆デバッグ
**前提条件**: 任意のデプロイ章完了  
**所要時間**: 1～1.5時間  
**難易度**: ⭐⭐

#### 学習内容
- 系統的なデバッグ手法
- よくある問題と解決策
- AI特有のトラブルシューティング

#### 学習リソース
- **🔧 よくある問題**: [よくある問題](docs/troubleshooting/common-issues.md) - FAQと解決策
- **🕵️ デバッグ**: [デバッグガイド](docs/troubleshooting/debugging.md) - 手順ごとの戦略
- **🤖 AI関連の問題**: [AI特有のトラブルシューティング](docs/troubleshooting/ai-troubleshooting.md) - AIサービスの問題

#### 実践演習
- デプロイ失敗の診断
- 認証問題の解消
- AIサービス接続のデバッグ

**💡 本章の成果**: 共通のデプロイ問題を自力で診断・解決できる

---

### 🏢 第8章：本番環境＆エンタープライズパターン
**前提条件**: 第1～4章完了  
**所要時間**: 2～3時間  
**難易度**: ⭐⭐⭐⭐

#### 学習内容
- 本番展開戦略
- エンタープライズセキュリティパターン
- モニタリングとコスト最適化

#### 学習リソース
- **🏭 本番環境**: [本番用AIベストプラクティス](docs/microsoft-foundry/production-ai-practices.md) - エンタープライズパターン
- **📝 事例**: [マイクロサービス例](../../examples/microservices) - 複雑なアーキテクチャ
- **📊 モニタリング**: [Application Insights連携](docs/pre-deployment/application-insights.md) - モニタリング

#### 実践演習
- エンタープライズセキュリティパターンの実装
- 包括的なモニタリング設定
- 適切なガバナンスによる本番展開

**💡 本章の成果**: 本番対応可能なエンタープライズアプリケーションを展開できる

---

## 🎓 ワークショップ概要：実践型学習体験

> **⚠️ ワークショップ状況：開発中**  
> ワークショップ資料は現在開発・調整中です。基本モジュールは動作していますが、一部上級セクションは未完成です。全コンテンツ完成に向けて積極的に進めています。 [進捗を確認 →](workshop/README.md)

### インタラクティブワークショップ資料
**ブラウザベースのツールとガイド付き演習による総合的な実践学習**

本ワークショップ資料は、上記の章ごとのカリキュラムを補完する構造的かつインタラクティブな学習体験を提供します。自己学習および講師主導のセッション双方に対応可能です。

#### 🛠️ ワークショップ特徴
- **ブラウザベースインターフェイス**: MkDocsを活用した完全ワークショップ、検索・コピー・テーマ機能付き
- **GitHub Codespaces連携**: ワンクリックで開発環境をセットアップ
- **体系的学習パス**: 7ステップのガイド付き演習（合計3.5時間）
- **発見 → 展開 → カスタマイズ**: 進行型メソッド
- **インタラクティブなDevContainer環境**: 事前設定済みツール・依存関係付き

#### 📚 ワークショップ構成
ワークショップは**発見 → 展開 → カスタマイズ**の手法に基づきます：

1. **発見フェーズ**（45分）  
   - Microsoft Foundryテンプレートとサービスを探索  
   - マルチエージェントアーキテクチャパターンの理解  
   - 展開要件と前提条件のレビュー

2. **展開フェーズ**（2時間）  
   - AZDを使ったAIアプリケーションの実践デプロイ  
   - Azure AIサービスとエンドポイントの構成  
   - セキュリティと認証パターンの実装

3. **カスタマイズフェーズ**（45分）  
   - 特定ユースケースに合わせたアプリケーションの修正  
   - 本番デプロイ向け最適化  
   - モニタリングとコスト管理の実装

#### 🚀 ワークショップ開始方法
```bash
# オプション1: GitHub Codespaces（推奨）
# リポジトリで「Code」→「mainでcodespaceを作成」をクリックしてください

# オプション2: ローカル開発
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# workshop/README.mdのセットアップ手順に従ってください
```

#### 🎯 ワークショップで得られる成果
完遂すると参加者は：
- **本番用AIアプリ開発展開**: AZDとMicrosoft Foundryサービスの利用  
- **マルチエージェントアーキテクチャ習得**: 協調したAIエージェントソリューションの実装  
- **セキュリティベストプラクティス実装**: 認証・アクセス制御設定  
- **スケール最適化設計**: コスト効率かつ高性能な展開設計  
- **デプロイのトラブルシューティング**: 共通問題の独力解決

#### 📖 ワークショップリソース
- **🎥 インタラクティブガイド**: [ワークショップ資料](workshop/README.md) - ブラウザベース学習環境  
- **📋 ステップバイステップ指導**: [ガイド付き演習](../../workshop/docs/instructions) - 詳細ウォークスルー  
- **🛠️ AIワークショップラボ**: [AIワークショップラボ](docs/microsoft-foundry/ai-workshop-lab.md) - AIに特化した演習  
- **💡 クイックスタート**: [ワークショップセットアップガイド](workshop/README.md#quick-start) - 環境構築手順  

**おすすめ利用シーン**：企業研修、大学講座、自己学習、開発者ブートキャンプ

---

## 📖 Azure Developer CLIとは？

Azure Developer CLI（azd）は、Azureへのアプリケーション構築とデプロイを加速する開発者向けコマンドラインインターフェイスです。以下を提供します：

- **テンプレートベースの展開** - 代表的なアプリケーションパターンの既成テンプレート利用  
- **Infrastructure as Code** - BicepやTerraformを用いたAzureリソース管理  
- **統合ワークフロー** - プロビジョニング、デプロイ、モニタリングをシームレスに  
- **開発者フレンドリー** - 生産性と開発体験を最適化

### **AZD + Microsoft Foundry：AIデプロイに最適**

**なぜAIソリューションにAZDなのか？** AZDはAI開発者が直面する主要課題を解決します：

- **AI対応済みテンプレート** - Azure OpenAI、認知サービス、MLワークロード用の事前設定テンプレート  
- **安全なAIデプロイ** - AIサービス、APIキー、モデルエンドポイントのセキュリティパターン内蔵  
- **本番AIパターン** - スケーラブルかつコスト効率の良いAIアプリ展開ベストプラクティス  
- **エンドツーエンドAIワークフロー** - モデル開発から本番展開・監視まで一貫サポート  
- **コスト最適化** - AIワークロード向けにスマートなリソース配分とスケーリング  
- **Microsoft Foundry連携** - モデルカタログ＆エンドポイントとのシームレス接続

---

## 🎯 テンプレート＆例ライブラリ

### 注目：Microsoft Foundryテンプレート
**AIアプリを展開するならまずここから！**

> **注意:** これらテンプレートは様々なAIパターンを示します。外部Azure Samplesもあれば、ローカル実装もあります。

| テンプレート | 対応章 | 難易度 | サービス | タイプ |
|----------|---------|------------|----------|------|
| [**AIチャット入門**](https://github.com/Azure-Samples/get-started-with-ai-chat) | 第2章 | ⭐⭐ | AzureOpenAI + Azure AI モデル推論API + Azure AI 検索 + Azure Container Apps + Application Insights | 外部 |
| [**AIエージェント入門**](https://github.com/Azure-Samples/get-started-with-ai-agents) | 第2章 | ⭐⭐ | Azure AI エージェントサービス + AzureOpenAI + Azure AI 検索 + Azure Container Apps + Application Insights | 外部 |
| [**Azure Search + OpenAI デモ**](https://github.com/Azure-Samples/azure-search-openai-demo) | 第2章 | ⭐⭐ | AzureOpenAI + Azure AI 検索 + App Service + ストレージ | 外部 |
| [**OpenAIチャットアプリ クイックスタート**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | 第2章 | ⭐ | AzureOpenAI + Container Apps + Application Insights | 外部 |
| [**Agent OpenAI Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | 第5章 | ⭐⭐⭐ | AzureOpenAI + Azure Functions + Prompty | 外部 |
| [**Contoso Chat RAG**](https://github.com/Azure-Samples/contoso-chat) | 第8章 | ⭐⭐⭐⭐ | AzureOpenAI + AI 検索 + Cosmos DB + Container Apps | 外部 |
| [**小売業向けマルチエージェントソリューション**](examples/retail-scenario.md) | 第5章 | ⭐⭐⭐⭐ | AzureOpenAI + AI 検索 + ストレージ + Container Apps + Cosmos DB | **ローカル** |

### 注目：完全学習シナリオ
**学習章に対応した本番対応アプリテンプレート**

| テンプレート | 学習章 | 難易度 | 主な学習内容 |
|----------|------------------|------------|--------------|
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | 第2章 | ⭐ | 基本的なAIデプロイパターン |
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | 第2章 | ⭐⭐ | Azure AI検索を用いたRAG実装 |
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | 第4章 | ⭐⭐ | ドキュメントインテリジェンス統合 |
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | 第5章 | ⭐⭐⭐ | エージェントフレームワークと関数呼び出し |
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | 第8章 | ⭐⭐⭐ | エンタープライズAIオーケストレーション |
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | 第5章 | ⭐⭐⭐⭐ | カスタマー・インベントリアージェントによるマルチエージェント構成 |

### タイプ別の学習例

> **📌 ローカルと外部の例について：**  
> **ローカル例**（本リポジトリ内）= すぐに利用可能  
> **外部例**（Azure Samples）= リンク先リポジトリからクローン

#### ローカル例（即利用可）
- [**小売業向けマルチエージェントソリューション**](examples/retail-scenario.md) - ARMテンプレート含む本番対応実装  
  - マルチエージェントアーキテクチャ（カスタマー＋インベントリアージェント）  
  - 総合的なモニタリングと評価  
  - ARMテンプレートによるワンクリック展開

#### ローカル例 - コンテナーアプリ（第2～5章）  
**本リポジトリの包括的コンテナデプロイ例：**  
- [**Container App例**](examples/container-app/README.md) - コンテナ展開完全ガイド  
  - [シンプルFlask API](../../examples/container-app/simple-flask-api) - スケールトゥゼロ対応基本REST API  
  - [マイクロサービスアーキテクチャ](../../examples/container-app/microservices) - 本番対応型マルチサービス展開  
  - クイックスタート～本番～上級パターン  
  - モニタリング、セキュリティ、コスト最適化ガイダンス

#### 外部例 - シンプルアプリ（第1～2章）  
**以下のAzure Samplesリポジトリをクローンして開始：**  
- [シンプルWebアプリ - Node.js + MongoDB](https://github.com/Azure-Samples/todo-nodejs-mongo) - 基本展開パターン  
- [静的サイト - React SPA](https://github.com/Azure-Samples/todo-csharp-sql-swa-func) - 静的コンテンツ展開  
- [Container App - Python Flask](https://github.com/Azure-Samples/container-apps-store-api-microservice) - REST API展開

#### 外部例 - データベース統合（第3～4章）  
- [データベースアプリ - C# + SQL](https://github.com/Azure-Samples/todo-csharp-sql) - DB接続パターン  
- [Functions + Cosmos DB](https://github.com/Azure-Samples/todo-python-mongo-swa-func) - サーバーレスデータワークフロー

#### 外部例 - 上級パターン（第4～8章）  
- [Javaマイクロサービス](https://github.com/Azure-Samples/java-microservices-aca-lab) - マルチサービスアーキテクチャ  
- [Container Appsジョブ](https://github.com/Azure-Samples/container-apps-jobs) - バックグラウンド処理  
- [エンタープライズMLパイプライン](https://github.com/Azure-Samples/mlops-v2) - 本番対応MLパターン

### 外部テンプレートコレクション
- [**公式 AZD テンプレート ギャラリー**](https://azure.github.io/awesome-azd/) - 公式およびコミュニティテンプレートのキュレーションコレクション
- [**Azure Developer CLI テンプレート**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - Microsoft Learn テンプレートドキュメント
- [**例ディレクトリ**](examples/README.md) - 詳細な説明付きのローカル学習例

---

## 📚 学習リソース & 参考資料

### クイックリファレンス
- [**コマンド チートシート**](resources/cheat-sheet.md) - 章ごとに整理された必須azdコマンド
- [**用語集**](resources/glossary.md) - Azureおよびazd用語集  
- [**FAQ**](resources/faq.md) - 学習章別のよくある質問
- [**学習ガイド**](resources/study-guide.md) - 包括的な練習問題集

### ハンズオンワークショップ
- [**AI ワークショップ ラボ**](docs/microsoft-foundry/ai-workshop-lab.md) - AIソリューションをAZDデプロイ可能にする（2〜3時間）
- [**インタラクティブ ワークショップ ガイド**](workshop/README.md) - MkDocsとDevContainer環境によるブラウザベースのワークショップ
- [**構造化学習パス**](../../workshop/docs/instructions) - 7ステップのガイド付き演習（発見 → デプロイ → カスタマイズ）
- [**AZD 初心者向けワークショップ**](workshop/README.md) - GitHub Codespaces統合の完全ハンズオンワークショップ資料

### 外部学習リソース
- [Azure Developer CLI ドキュメント](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)
- [Azure アーキテクチャ センター](https://learn.microsoft.com/en-us/azure/architecture/)
- [Azure 価格計算ツール](https://azure.microsoft.com/pricing/calculator/)
- [Azure サービス状況](https://status.azure.com/)

---

## 🔧 クイック トラブルシューティング ガイド

**初心者がよく直面する問題と即時解決策:**

### ❌ 「azd: command not found」

```bash
# まずAZDをインストールしてください
# Windows（PowerShell）：
winget install microsoft.azd

# macOS：
brew tap azure/azd && brew install azd

# Linux：
curl -fsSL https://aka.ms/install-azd.sh | bash

# インストールの確認
azd version
```

### ❌ 「サブスクリプションが見つかりません」または「サブスクリプションが設定されていません」

```bash
# 利用可能なサブスクリプションを一覧表示
az account list --output table

# デフォルトのサブスクリプションを設定
az account set --subscription "<subscription-id-or-name>"

# AZD環境用に設定
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# 検証する
az account show
```

### ❌ 「InsufficientQuota」または「クォータ超過」

```bash
# 異なる Azure リージョンを試してください
azd env set AZURE_LOCATION "westus2"
azd up

# 開発時にはより小さい SKU を使用してください
# infra/main.parameters.json を編集してください：
{
  "sku": "B1"  // Instead of "P1V2"
}
```

### ❌ 「azd up」が途中で失敗する

```bash
# オプション1: クリーンして再試行する
azd down --force --purge
azd up

# オプション2: インフラストラクチャだけを修正する
azd provision

# オプション3: 詳細なログを確認する
azd show
azd logs
```

### ❌ 「認証失敗」または「トークンの有効期限切れ」

```bash
# 再認証する
az logout
az login

azd auth logout
azd auth login

# 認証を確認する
az account show
```

### ❌ 「リソースは既に存在します」または名前の競合

```bash
# AZDは一意の名前を生成しますが、競合がある場合は：
azd down --force --purge

# その場合、新しい環境を使って再試行します
azd env new dev-v2
azd up
```

### ❌ テンプレートのデプロイが長時間かかる

**通常の待機時間:**
- シンプルなWebアプリ: 5〜10分
- データベース付きアプリ: 10〜15分
- AIアプリケーション: 15〜25分（OpenAIプロビジョニングは遅い）

```bash
# 進捗を確認してください
azd show

# 30分以上進まない場合は、Azureポータルを確認してください：
azd monitor
# 失敗したデプロイメントを探してください
```

### ❌ 「アクセス拒否」または「禁止されています」

```bash
# Azureのロールを確認してください
az role assignment list --assignee $(az account show --query user.name -o tsv)

# 少なくとも「Contributor」ロールが必要です
# Azure管理者に以下の付与を依頼してください:
# - Contributor（リソース用）
# - User Access Administrator（ロール割り当て用）
```

### ❌ デプロイしたアプリケーションのURLが見つからない

```bash
# すべてのサービスエンドポイントを表示
azd show

# またはAzureポータルを開く
azd monitor

# 特定のサービスを確認
azd env get-values
# *_URL変数を探す
```

### 📚 詳細なトラブルシューティングリソース

- **よくある問題ガイド:** [詳細な解決策](docs/troubleshooting/common-issues.md)
- **AI固有の問題:** [AI トラブルシューティング](docs/troubleshooting/ai-troubleshooting.md)
- **デバッグガイド:** [ステップバイステップデバッグ](docs/troubleshooting/debugging.md)
- **サポート取得:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🔧 クイック トラブルシューティング ガイド

**初心者がよく直面する問題と即時解決策:**

<details>
<summary><strong>❌ 「azd: command not found」</strong></summary>

```bash
# まずAZDをインストールしてください
# Windows（PowerShell）：
winget install microsoft.azd

# macOS：
brew tap azure/azd && brew install azd

# Linux：
curl -fsSL https://aka.ms/install-azd.sh | bash

# インストールを確認してください
azd version
```
</details>

<details>
<summary><strong>❌ 「サブスクリプションが見つかりません」または「サブスクリプションが設定されていません」</strong></summary>

```bash
# 利用可能なサブスクリプションを一覧表示
az account list --output table

# デフォルトのサブスクリプションを設定
az account set --subscription "<subscription-id-or-name>"

# AZD環境の設定
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# 確認する
az account show
```
</details>

<details>
<summary><strong>❌ 「InsufficientQuota」または「クォータ超過」</strong></summary>

```bash
# 別のAzureリージョンを試してください
azd env set AZURE_LOCATION "westus2"
azd up

# または開発中はより小さいSKUを使用してください
# infra/main.parameters.jsonを編集してください:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>

<details>
<summary><strong>❌ 「azd up」が途中で失敗する</strong></summary>

```bash
# オプション1: クリーンして再試行
azd down --force --purge
azd up

# オプション2: インフラだけを修正
azd provision

# オプション3: 詳細ログを確認する
azd show
azd logs
```
</details>

<details>
<summary><strong>❌ 「認証失敗」または「トークンの有効期限切れ」</strong></summary>

```bash
# 再認証
az logout
az login

azd auth logout
azd auth login

# 認証を確認する
az account show
```
</details>

<details>
<summary><strong>❌ 「リソースは既に存在します」または名前の競合</strong></summary>

```bash
# AZDはユニークな名前を生成しますが、競合が発生した場合：
azd down --force --purge

# その場合は新しい環境で再試行します
azd env new dev-v2
azd up
```
</details>

<details>
<summary><strong>❌ テンプレートのデプロイが長時間かかる</strong></summary>

**通常の待機時間:**
- シンプルなWebアプリ: 5〜10分
- データベース付きアプリ: 10〜15分
- AIアプリケーション: 15〜25分（OpenAIプロビジョニングは遅い）

```bash
# 進捗状況を確認する
azd show

# 30分以上進まない場合は、Azureポータルを確認してください:
azd monitor
# 失敗したデプロイメントを探す
```
</details>

<details>
<summary><strong>❌ 「アクセス拒否」または「禁止されています」</strong></summary>

```bash
# Azure のロールを確認してください
az role assignment list --assignee $(az account show --query user.name -o tsv)

# 少なくとも「Contributor」ロールが必要です
# Azure 管理者に次の権限を付与してもらってください:
# - Contributor（リソース用）
# - User Access Administrator（ロール割り当て用）
```
</details>

<details>
<summary><strong>❌ デプロイ済みアプリケーションのURLが見つからない</strong></summary>

```bash
# すべてのサービスエンドポイントを表示
azd show

# または Azure ポータルを開く
azd monitor

# 特定のサービスを確認
azd env get-values
# *_URL 変数を探す
```
</details>

### 📚 詳細なトラブルシューティングリソース

- **よくある問題ガイド:** [詳細な解決策](docs/troubleshooting/common-issues.md)
- **AI固有の問題:** [AI トラブルシューティング](docs/troubleshooting/ai-troubleshooting.md)
- **デバッグガイド:** [ステップバイステップデバッグ](docs/troubleshooting/debugging.md)
- **サポート取得:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🎓 コース修了 & 認証

### 進捗トラッキング
各章の学習進捗を追跡しましょう:

- [ ] **第1章**: 基礎 & クイックスタート ✅
- [ ] **第2章**: AIファースト開発 ✅  
- [ ] **第3章**: 構成 & 認証 ✅
- [ ] **第4章**: インフラストラクチャ・アズ・コード & デプロイ ✅
- [ ] **第5章**: マルチエージェントAIソリューション ✅
- [ ] **第6章**: デプロイ前検証 & 計画 ✅
- [ ] **第7章**: トラブルシューティング & デバッグ ✅
- [ ] **第8章**: 本番環境 & エンタープライズパターン ✅

### 学習確認
各章修了後に、以下を行って知識を確認します:
1. **実践演習**: 章のハンズオンデプロイを完了
2. **知識確認**: 章別FAQを確認
3. **コミュニティ議論**: Azure Discordで体験を共有
4. **次章へ**: 次の難易度に進む

### コース修了特典
全章修了後、以下の内容を習得できます:
- **本番経験**: 実際にAzureへAIアプリをデプロイ
- **プロスキル**: エンタープライズ対応のデプロイ力  
- **コミュニティ認知**: Azure開発者コミュニティの活発なメンバー
- **キャリアアップ**: 需要の高いAZDおよびAIデプロイスキル

---

## 🤝 コミュニティ & サポート

### サポートの取得
- **技術的問題**: [バグ報告と機能要望](https://github.com/microsoft/azd-for-beginners/issues)
- **学習質問**: [Microsoft Azure Discord コミュニティ](https://discord.gg/microsoft-azure) および [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **AI専用サポート**: [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG) に参加
- **ドキュメント**: [公式 Azure Developer CLI ドキュメント](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)

### Microsoft Foundry Discord からのコミュニティ知見

**#Azure チャンネル最新投票結果:**
- **45%** の開発者がAIワークロードにAZDを使いたい
- **主な課題**: マルチサービスデプロイ、認証情報管理、本番対応  
- **最も要望されたもの**: AI専用テンプレート、トラブルシューティングガイド、ベストプラクティス

**コミュニティに参加して:**
- AZD + AI経験を共有し支援を得る
- 新しいAIテンプレートの早期プレビューにアクセス
- AIデプロイのベストプラクティスに貢献
- 将来のAI + AZD機能開発に影響を与える

### コースへの貢献
貢献を歓迎します！詳しくは [Contributing Guide](CONTRIBUTING.md) をご覧ください:
- **コンテンツ改善**: 既存章や例を充実させる
- **新しい例追加**: 現実世界のシナリオやテンプレートの追加  
- **翻訳支援**: 多言語対応の維持
- **バグ報告**: 精度と明確さの向上
- **コミュニティ規範**: 包摂的なガイドラインの遵守

---

## 📄 コース情報

### ライセンス
このプロジェクトはMITライセンスのもとに提供されています。詳細は [LICENSE](../../LICENSE) ファイルを参照してください。

### 関連 Microsoft 学習リソース

当チームが提供するその他の包括的な学習コース:

<!-- CO-OP TRANSLATOR OTHER COURSES START -->
### LangChain
[![LangChain4j for Beginners](https://img.shields.io/badge/LangChain4j%20for%20Beginners-22C55E?style=for-the-badge&&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchain4j-for-beginners)
[![LangChain.js for Beginners](https://img.shields.io/badge/LangChain.js%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchainjs-for-beginners?WT.mc_id=m365-94501-dwahlin)

---

### Azure / Edge / MCP / エージェント
[![AZD for Beginners](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Edge AI for Beginners](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![MCP for Beginners](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)
[![AI Agents for Beginners](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### ジェネレーティブ AI シリーズ
[![Generative AI for Beginners](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Generative AI (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
[![Generative AI (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)
[![Generative AI (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---
 
### コアラーニング
[![ML for Beginners](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![Data Science for Beginners](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![AI for Beginners](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Cybersecurity for Beginners](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Web Dev for Beginners](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![IoT for Beginners](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![XR Development for Beginners](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Copilotシリーズ
[![Copilot for AI Paired Programming](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![Copilot for C#/.NET](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Copilot Adventure](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ コースナビゲーション

**🚀 学習を始める準備はできましたか？**

**初心者**：まずは[第1章: 基礎とクイックスタート](../..)から始めましょう  
**AI開発者**：[第2章: AIファースト開発](../..)へジャンプ  
**経験豊富な開発者**：[第3章: 設定と認証](../..)から始めてください

**次のステップ**：[第1章 - AZDの基本を始める](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**免責事項**：  
本書類はAI翻訳サービス「Co-op Translator」（https://github.com/Azure/co-op-translator）を利用して翻訳されています。正確性を期していますが、自動翻訳には誤りや不正確な部分が含まれる可能性があることをご承知ください。原文の言語によるオリジナル文書が正式な情報源とみなされるべきです。重要な情報に関しては、専門の人間による翻訳を推奨いたします。本翻訳の利用によって生じたいかなる誤解や解釈違いについても、当方は一切責任を負いかねます。
<!-- CO-OP TRANSLATOR DISCLAIMER END -->