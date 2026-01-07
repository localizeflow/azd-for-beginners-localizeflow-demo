<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T12:59:53+00:00",
  "source_file": "README.md",
  "language_code": "ko"
}
-->
> 참고: 이 문서는 최신 변경 사항을 반영하기 위해 지속적으로 업데이트됩니다.

> ⚠️ 이 저장소는 Localizeflow를 사용한 자동화 문서 현지화 기능을 보여주기 위해 만든 데모입니다.
>
> 원본 콘텐츠는 Microsoft의 “AZD for Beginners” 프로젝트를 기반으로 합니다.


# AZD 초보자용: 체계적인 학습 여정

![AZD-for-beginners](../../translated_images/azdbeginners.5527441dd9f74068.ko.png) 

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## 이 강좌 시작하기

아래 절차를 따라 AZD 학습 여정을 시작하세요:

1. **저장소 포크하기**: 클릭 [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)
2. **저장소 클론하기**: `git clone https://github.com/microsoft/azd-for-beginners.git`
3. **커뮤니티 참여하기**: 전문가 지원을 위한 [Azure Discord 커뮤니티](https://discord.com/invite/ByRwuEEgH4)
4. **학습 경로 선택하기**: 아래에서 경험 수준에 맞는 챕터 선택

### 다국어 지원

#### 자동 번역 (항상 최신 상태 유지)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](./README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **로컬로 클론하는 것을 선호하시나요?**

> 이 저장소는 50개 이상의 언어 번역을 포함하여 다운로드 크기가 크게 증가합니다. 번역 없이 클론하려면 sparse checkout을 사용하세요:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> 이렇게 하면 강좌를 완료하는 데 꼭 필요한 모든 파일을 훨씬 빠르게 다운로드할 수 있습니다.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## 강좌 개요

점진적인 학습을 위해 설계된 체계적인 챕터를 통해 Azure Developer CLI(azd)를 숙달하세요. **Microsoft Foundry 통합과 함께 AI 애플리케이션 배포에 특별히 중점을 둡니다.**

### 이 강좌가 현대 개발자에게 필수적인 이유

Microsoft Foundry Discord 커뮤니티의 인사이트를 기반으로, **개발자의 45%가 AI 워크로드에 AZD를 활용하고 싶어하지만** 다음과 같은 어려움을 겪고 있습니다:
- 복잡한 다중 서비스 AI 아키텍처
- 생산 환경 AI 배포 모범 사례
- Azure AI 서비스 통합 및 구성
- AI 워크로드 비용 최적화
- AI 특화 배포 문제 해결

### 학습 목표

이 체계적인 강좌를 완료함으로써 다음을 달성할 수 있습니다:
- **AZD 기본기 숙달**: 핵심 개념, 설치 및 구성
- **AI 애플리케이션 배포**: Microsoft Foundry 서비스와 함께 AZD 활용
- **인프라스트럭처 코드 관리**: Bicep 템플릿으로 Azure 리소스 관리
- **배포 문제 해결**: 일반 문제 해결 및 디버깅
- **생산 환경 최적화**: 보안, 확장성, 모니터링, 비용 관리
- **다중 에이전트 솔루션 구축**: 복잡한 AI 아키텍처 배포

## 📚 학습 챕터

*경험 수준과 목표에 따라 학습 경로 선택*

### 🚀 챕터 1: 기초 및 빠른 시작
**필수 조건**: Azure 구독, 기본 명령어 지식  
**소요 시간**: 30-45분  
**난이도**: ⭐

#### 학습 내용
- Azure Developer CLI 기본 이해
- 플랫폼별 AZD 설치
- 첫 성공적 배포 경험

#### 학습 자료
- **🎯 시작하기**: [Azure Developer CLI란?](../..)
- **📖 이론**: [AZD 기본](docs/getting-started/azd-basics.md) - 핵심 개념 및 용어
- **⚙️ 설치**: [설치 및 설정](docs/getting-started/installation.md) - 플랫폼별 가이드
- **🛠️ 실습**: [첫 프로젝트](docs/getting-started/first-project.md) - 단계별 튜토리얼
- **📋 빠른 참조**: [명령어 치트 시트](resources/cheat-sheet.md)

#### 실습 과제
```bash
# 빠른 설치 확인
azd version

# 첫 번째 애플리케이션 배포
azd init --template todo-nodejs-mongo
azd up
```

**💡 챕터 결과:** AZD를 사용해 간단한 웹 애플리케이션을 Azure에 성공적으로 배포

**✅ 성공 검증:**
```bash
# 1장을 완료한 후에 할 수 있어야 합니다:
azd version              # 설치된 버전을 표시합니다
azd init --template todo-nodejs-mongo  # 프로젝트를 초기화합니다
azd up                  # Azure에 배포합니다
azd show                # 실행 중인 앱 URL을 표시합니다
# 애플리케이션이 브라우저에서 열리고 작동합니다
azd down --force --purge  # 리소스를 정리합니다
```

**📊 시간 투자:** 30-45분  
**📈 완료 후 기술 수준:** 기본 애플리케이션을 독립적으로 배포 가능

**✅ 성공 검증:**
```bash
# 1장을 완료한 후, 다음을 할 수 있어야 합니다:
azd version              # 설치된 버전을 표시합니다
azd init --template todo-nodejs-mongo  # 프로젝트를 초기화합니다
azd up                  # Azure에 배포합니다
azd show                # 실행 중인 앱 URL을 표시합니다
# 애플리케이션이 브라우저에서 열리고 작동합니다
azd down --force --purge  # 리소스를 정리합니다
```

**📊 시간 투자:** 30-45분  
**📈 완료 후 기술 수준:** 기본 애플리케이션을 독립적으로 배포 가능

---

### 🤖 챕터 2: AI 우선 개발 (AI 개발자 추천)
**필수 조건**: 챕터 1 완료  
**소요 시간**: 1-2시간  
**난이도**: ⭐⭐

#### 학습 내용
- Microsoft Foundry와 AZD 통합
- AI 기반 애플리케이션 배포
- AI 서비스 구성 이해

#### 학습 자료
- **🎯 시작하기**: [Microsoft Foundry 통합](docs/microsoft-foundry/microsoft-foundry-integration.md)
- **📖 패턴**: [AI 모델 배포](docs/microsoft-foundry/ai-model-deployment.md) - AI 모델 배포 및 관리
- **🛠️ 워크숍**: [AI 워크숍 실습](docs/microsoft-foundry/ai-workshop-lab.md) - AI 솔루션 AZD 준비
- **🎥 인터랙티브 가이드**: [워크숍 자료](workshop/README.md) - MkDocs 및 DevContainer 환경 기반 브라우저 학습
- **📋 템플릿**: [Microsoft Foundry 템플릿](../..)
- **📝 예제**: [AZD 배포 예제](examples/README.md)

#### 실습 과제
```bash
# 첫 번째 AI 애플리케이션 배포하기
azd init --template azure-search-openai-demo
azd up

# 추가 AI 템플릿 시도하기
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```

**💡 챕터 결과:** RAG 기능이 포함된 AI 기반 채팅 애플리케이션 배포 및 구성

**✅ 성공 검증:**
```bash
# 2장을 마친 후, 다음을 할 수 있어야 합니다:
azd init --template azure-search-openai-demo
azd up
# AI 채팅 인터페이스를 테스트하세요
# 질문을 하고 출처가 있는 AI 기반 응답을 받으세요
# 검색 통합이 작동하는지 확인하세요
azd monitor  # Application Insights가 원격 측정을 표시하는지 확인하세요
azd down --force --purge
```

**📊 시간 투자:** 1-2시간  
**📈 완료 후 기술 수준:** 생산용 AI 애플리케이션 배포 및 구성 가능  
**💰 비용 인식:** 월 $80-150 개발 비용, 월 $300-3500 생산 비용 이해

#### 💰 AI 배포를 위한 비용 고려 사항

**개발 환경 (예상 월 $80-150):**
- Azure OpenAI (종량제): 월 $0-50 (토큰 사용량 기준)
- AI 검색 (기본 계층): 월 $75
- 컨테이너 앱 (소비 기반): 월 $0-20
- 스토리지 (표준): 월 $1-5

**생산 환경 (예상 월 $300-3500+):**
- Azure OpenAI (일관된 성능 위한 PTU): 월 $3,000 이상 또는 대량 사용 시 종량제
- AI 검색 (표준 계층): 월 $250
- 컨테이너 앱 (전용): 월 $50-100
- Application Insights: 월 $5-50
- 스토리지 (프리미엄): 월 $10-50

**💡 비용 최적화 팁:**
- 무료 계층 Azure OpenAI 사용 권장 (월 50,000 토큰 포함)
- 활성 개발이 아닐 때 `azd down`으로 리소스 할당 해제
- 초기에는 종량제 사용, 생산 환경에서만 PTU 업그레이드
- 배포 전 `azd provision --preview` 실행하여 비용 예측
- 자동 확장 활성화: 실제 사용량에 대해서만 비용 지불

**비용 모니터링:**
```bash
# 예상 월간 비용 확인
azd provision --preview

# Azure 포털에서 실제 비용 모니터링
az consumption budget list --resource-group <your-rg>
```

---

### ⚙️ 챕터 3: 구성 및 인증
**필수 조건**: 챕터 1 완료  
**소요 시간**: 45-60분  
**난이도**: ⭐⭐

#### 학습 내용
- 환경 구성 및 관리
- 인증 및 보안 모범 사례
- 리소스 명명 및 조직화

#### 학습 자료
- **📖 구성**: [구성 가이드](docs/getting-started/configuration.md) - 환경 설정
- **🔐 보안**: [인증 패턴 및 관리형 아이덴티티](docs/getting-started/authsecurity.md) - 인증 패턴
- **📝 예제**: [데이터베이스 앱 예제](examples/database-app/README.md) - AZD 데이터베이스 예제

#### 실습 과제
- 다중 환경 구성(dev, staging, prod)
- 관리형 아이덴티티 인증 설정
- 환경별 구성 구현

**💡 챕터 결과:** 적절한 인증 및 보안으로 다중 환경 관리

---

### 🏗️ 챕터 4: 인프라 코드 및 배포
**필수 조건**: 챕터 1-3 완료  
**소요 시간**: 1-1.5시간  
**난이도**: ⭐⭐⭐

#### 학습 내용
- 고급 배포 패턴
- Bicep을 활용한 인프라 코드
- 리소스 프로비저닝 전략

#### 학습 자료
- **📖 배포**: [배포 가이드](docs/deployment/deployment-guide.md) - 전체 워크플로우
- **🏗️ 프로비저닝**: [리소스 프로비저닝](docs/deployment/provisioning.md) - Azure 리소스 관리
- **📝 예제**: [컨테이너 앱 예제](../../examples/container-app) - 컨테이너화 배포

#### 실습 과제
- 맞춤형 Bicep 템플릿 생성
- 다중 서비스 애플리케이션 배포
- 블루-그린 배포 전략 구현

**💡 챕터 결과:** 맞춤형 인프라 템플릿을 활용한 복잡한 다중 서비스 애플리케이션 배포

---
### 🎯 5장: 다중 에이전트 AI 솔루션 (고급)  
**전제 조건**: 1-2장 완료  
**소요 시간**: 2-3시간  
**난이도**: ⭐⭐⭐⭐

#### 학습 내용  
- 다중 에이전트 아키텍처 패턴  
- 에이전트 오케스트레이션 및 조정  
- 프로덕션 준비 AI 배포  

#### 학습 자료  
- **🤖 대표 프로젝트**: [리테일 다중 에이전트 솔루션](examples/retail-scenario.md) - 완성된 구현  
- **🛠️ ARM 템플릿**: [ARM 템플릿 패키지](../../examples/retail-multiagent-arm-template) - 원클릭 배포  
- **📖 아키텍처**: [다중 에이전트 조정 패턴](/docs/pre-deployment/coordination-patterns.md) - 패턴  

#### 실습 과제  
```bash
# 완전한 소매 다중 에이전트 솔루션 배포
cd examples/retail-multiagent-arm-template
./deploy.sh

# 에이전트 구성 탐색
az deployment group show --resource-group <rg-name> --name <deployment-name>
```
  
**💡 장 결과**: 고객 에이전트와 재고 에이전트를 포함한 프로덕션 준비 다중 에이전트 AI 솔루션 배포 및 관리

---

### 🔍 6장: 배포 전 검증 및 계획  
**전제 조건**: 4장 완료  
**소요 시간**: 1시간  
**난이도**: ⭐⭐

#### 학습 내용  
- 용량 계획 및 리소스 검증  
- SKU 선택 전략  
- 사전 점검 및 자동화  

#### 학습 자료  
- **📊 계획**: [용량 계획](docs/pre-deployment/capacity-planning.md) - 리소스 검증  
- **💰 선택**: [SKU 선택](docs/pre-deployment/sku-selection.md) - 비용 효율적 선택  
- **✅ 검증**: [사전 점검](docs/pre-deployment/preflight-checks.md) - 자동화 스크립트  

#### 실습 과제  
- 용량 검증 스크립트 실행  
- 비용 최적화를 위한 SKU 선택  
- 자동화된 배포 전 점검 구현  

**💡 장 결과**: 실행 전 배포 검증 및 최적화

---

### 🚨 7장: 문제 해결 및 디버깅  
**전제 조건**: 배포 장 중 하나 완료  
**소요 시간**: 1-1.5시간  
**난이도**: ⭐⭐

#### 학습 내용  
- 체계적 디버깅 방법론  
- 일반적인 문제 및 해결책  
- AI 특화 문제 해결  

#### 학습 자료  
- **🔧 일반 문제**: [일반 문제](docs/troubleshooting/common-issues.md) - FAQ 및 해결책  
- **🕵️ 디버깅**: [디버깅 가이드](docs/troubleshooting/debugging.md) - 단계별 전략  
- **🤖 AI 문제**: [AI 특화 문제 해결](docs/troubleshooting/ai-troubleshooting.md) - AI 서비스 문제  

#### 실습 과제  
- 배포 실패 진단  
- 인증 문제 해결  
- AI 서비스 연결 문제 디버깅  

**💡 장 결과**: 일반 배포 문제를 독립적으로 진단 및 해결

---

### 🏢 8장: 프로덕션 및 엔터프라이즈 패턴  
**전제 조건**: 1-4장 완료  
**소요 시간**: 2-3시간  
**난이도**: ⭐⭐⭐⭐

#### 학습 내용  
- 프로덕션 배포 전략  
- 엔터프라이즈 보안 패턴  
- 모니터링 및 비용 최적화  

#### 학습 자료  
- **🏭 프로덕션**: [프로덕션 AI 모범 사례](docs/microsoft-foundry/production-ai-practices.md) - 엔터프라이즈 패턴  
- **📝 예제**: [마이크로서비스 예제](../../examples/microservices) - 복잡한 아키텍처  
- **📊 모니터링**: [애플리케이션 인사이트 통합](docs/pre-deployment/application-insights.md) - 모니터링  

#### 실습 과제  
- 엔터프라이즈 보안 패턴 구현  
- 종합 모니터링 설정  
- 적절한 거버넌스와 함께 프로덕션 배포  

**💡 장 결과**: 완전한 프로덕션 기능을 갖춘 엔터프라이즈 지원 애플리케이션 배포

---

## 🎓 워크숍 개요: 실습 학습 경험

> **⚠️ 워크숍 상태: 개발 중**  
> 워크숍 자료는 현재 개발 및 개선 중입니다. 핵심 모듈은 작동 중이지만 일부 고급 섹션은 미완성입니다. 모든 콘텐츠 완성을 위해 적극 작업 중입니다. [진행 상황 확인 →](workshop/README.md)

### 인터랙티브 워크숍 자료  
**브라우저 기반 도구와 가이드 실습을 통한 종합적인 실습 학습**

워크숍 자료는 위의 장별 커리큘럼을 보완하는 구조화된 인터랙티브 학습 경험을 제공합니다. 워크숍은 자율 학습 및 강사 주도 학습 모두에 적합합니다.

#### 🛠️ 워크숍 특징  
- **브라우저 기반 인터페이스**: 검색, 복사, 테마 기능을 포함한 완전한 MkDocs 지원  
- **GitHub Codespaces 통합**: 원클릭 개발 환경 설정  
- **구조화된 학습 경로**: 7단계 가이드 실습 (총 3.5시간)  
- **탐색 → 배포 → 맞춤화**: 점진적 방법론  
- **인터랙티브 DevContainer 환경**: 사전 구성된 도구 및 종속성  

#### 📚 워크숍 구성  
워크숍은 **탐색 → 배포 → 맞춤화** 방법론을 따릅니다:

1. **탐색 단계** (45분)  
   - Microsoft Foundry 템플릿 및 서비스 탐색  
   - 다중 에이전트 아키텍처 패턴 이해  
   - 배포 요구사항 및 전제 조건 검토  

2. **배포 단계** (2시간)  
   - AZD를 사용한 AI 애플리케이션 실습 배포  
   - Azure AI 서비스 및 엔드포인트 구성  
   - 보안 및 인증 패턴 구현  

3. **맞춤화 단계** (45분)  
   - 특정 사용 사례 맞춤 애플리케이션 수정  
   - 프로덕션 배포 최적화  
   - 모니터링 및 비용 관리 구현  

#### 🚀 워크숍 시작하기  
```bash
# 옵션 1: GitHub Codespaces (권장)
# 리포지토리에서 "Code" → "Create codespace on main"을 클릭하세요

# 옵션 2: 로컬 개발
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# workshop/README.md의 설정 지침을 따르세요
```
  
#### 🎯 워크숍 학습 결과  
워크숍을 완료하면 참가자는:  
- **프로덕션 AI 애플리케이션 배포**: Microsoft Foundry 서비스와 AZD 활용  
- **다중 에이전트 아키텍처 마스터**: 조정된 AI 에이전트 솔루션 구현  
- **보안 모범 사례 구현**: 인증 및 액세스 제어 구성  
- **규모 최적화**: 비용 효율적이고 성능 좋은 배포 설계  
- **배포 문제 해결**: 일반 문제 독립 해결  

#### 📖 워크숍 자료  
- **🎥 인터랙티브 가이드**: [워크숍 자료](workshop/README.md) - 브라우저 기반 학습 환경  
- **📋 단계별 안내**: [가이드 실습](../../workshop/docs/instructions) - 상세 핸즈온  
- **🛠️ AI 워크숍 실습실**: [AI 워크숍 실습실](docs/microsoft-foundry/ai-workshop-lab.md) - AI 중심 실습  
- **💡 빠른 시작**: [워크숍 설정 가이드](workshop/README.md#quick-start) - 환경 구성  

**적합 대상**: 기업 교육, 대학 강좌, 자율 학습, 개발자 부트캠프

---

## 📖 Azure Developer CLI란?

Azure Developer CLI (azd)는 개발자 중심의 커맨드라인 인터페이스로, Azure로의 애플리케이션 구축 및 배포 과정을 가속화합니다. 다음을 제공합니다:

- **템플릿 기반 배포** - 일반 애플리케이션 패턴에 대해 미리 만들어진 템플릿 사용  
- **코드로서의 인프라** - Bicep 또는 Terraform을 사용한 Azure 리소스 관리  
- **통합 워크플로우** - 애플리케이션 프로비저닝, 배포 및 모니터링의 원활한 수행  
- **개발자 친화적** - 개발 생산성과 경험에 최적화  

### **AZD + Microsoft Foundry: AI 배포에 최적**

**왜 AZD가 AI 솔루션에 적합한가?** AZD는 AI 개발자가 직면하는 주요 문제를 해결합니다:

- **AI 준비 템플릿** - Azure OpenAI, Cognitive Services, ML 워크로드용 사전 구성 템플릿  
- **안전한 AI 배포** - AI 서비스, API 키, 모델 엔드포인트에 대한 내장 보안 패턴  
- **프로덕션 AI 패턴** - 확장 가능하고 비용 효율적인 AI 애플리케이션 배포 모범 사례  
- **엔드 투 엔드 AI 워크플로우** - 모델 개발부터 프로덕션 배포 및 적절한 모니터링  
- **비용 최적화** - AI 워크로드를 위한 스마트 리소스 할당 및 스케일링  
- **Microsoft Foundry 통합** - Microsoft Foundry 모델 카탈로그 및 엔드포인트와 원활 연결  

---

## 🎯 템플릿 및 예제 라이브러리

### 추천: Microsoft Foundry 템플릿  
**AI 애플리케이션 배포를 시작하는 분께 추천!**

> **참고:** 이 템플릿들은 다양한 AI 패턴을 시연합니다. 일부는 외부 Azure 샘플, 나머지는 로컬 구현입니다.

| 템플릿 | 장 | 난이도 | 서비스 | 유형 |
|----------|---------|------------|----------|------|
| [**AI 챗 시작하기**](https://github.com/Azure-Samples/get-started-with-ai-chat) | 2장 | ⭐⭐ | AzureOpenAI + Azure AI 모델 추론 API + Azure AI 검색 + Azure Container Apps + Application Insights | 외부 |
| [**AI 에이전트 시작하기**](https://github.com/Azure-Samples/get-started-with-ai-agents) | 2장 | ⭐⭐ | Azure AI 에이전트 서비스 + AzureOpenAI + Azure AI 검색 + Azure Container Apps + Application Insights | 외부 |
| [**Azure 검색 + OpenAI 데모**](https://github.com/Azure-Samples/azure-search-openai-demo) | 2장 | ⭐⭐ | AzureOpenAI + Azure AI 검색 + 앱 서비스 + 스토리지 | 외부 |
| [**OpenAI 채팅 앱 빠른 시작**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | 2장 | ⭐ | AzureOpenAI + 컨테이너 앱 + Application Insights | 외부 |
| [**Agent OpenAI Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | 5장 | ⭐⭐⭐ | AzureOpenAI + Azure Functions + Prompty | 외부 |
| [**Contoso 채팅 RAG**](https://github.com/Azure-Samples/contoso-chat) | 8장 | ⭐⭐⭐⭐ | AzureOpenAI + AI 검색 + Cosmos DB + 컨테이너 앱 | 외부 |
| [**리테일 다중 에이전트 솔루션**](examples/retail-scenario.md) | 5장 | ⭐⭐⭐⭐ | AzureOpenAI + AI 검색 + 스토리지 + 컨테이너 앱 + Cosmos DB | **로컬** |

### 추천: 완성형 학습 시나리오  
**학습 장에 매핑된 프로덕션 준비 애플리케이션 템플릿**

| 템플릿 | 학습 장 | 난이도 | 주요 학습 내용 |
|----------|------------------|------------|--------------|
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | 2장 | ⭐ | 기본 AI 배포 패턴 |
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | 2장 | ⭐⭐ | Azure AI 검색을 활용한 RAG 구현 |
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | 4장 | ⭐⭐ | 문서 인텔리전스 통합 |
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | 5장 | ⭐⭐⭐ | 에이전트 프레임워크 및 함수 호출 |
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | 8장 | ⭐⭐⭐ | 엔터프라이즈 AI 오케스트레이션 |
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | 5장 | ⭐⭐⭐⭐ | 고객 및 재고 에이전트를 포함한 다중 에이전트 아키텍처 |

### 유형별 학습 예제

> **📌 로컬 vs 외부 예제:**  
> **로컬 예제** (이 저장소 내) = 즉시 사용 가능  
> **외부 예제** (Azure 샘플) = 연결된 저장소에서 클론 가능

#### 로컬 예제 (즉시 사용 가능)  
- [**리테일 다중 에이전트 솔루션**](examples/retail-scenario.md) - ARM 템플릿 포함 완전한 프로덕션 준비 구현  
  - 다중 에이전트 아키텍처 (고객 + 재고 에이전트)  
  - 종합 모니터링 및 평가  
  - ARM 템플릿을 통한 원클릭 배포  

#### 로컬 예제 - 컨테이너 애플리케이션 (2-5장)  
**이 저장소 내 종합적인 컨테이너 배포 예제:**  
- [**컨테이너 앱 예제**](examples/container-app/README.md) - 컨테이너 배포 완벽 안내  
  - [간단한 Flask API](../../examples/container-app/simple-flask-api) - Scale-to-zero 지원 기본 REST API  
  - [마이크로서비스 아키텍처](../../examples/container-app/microservices) - 프로덕션 준비 다중 서비스 배포  
  - 빠른 시작, 프로덕션, 고급 배포 패턴  
  - 모니터링, 보안, 비용 최적화 안내  

#### 외부 예제 - 단순 애플리케이션 (1-2장)  
**시작하려면 이 Azure 샘플 저장소를 클론하세요:**  
- [간단한 웹 앱 - Node.js + MongoDB](https://github.com/Azure-Samples/todo-nodejs-mongo) - 기본 배포 패턴  
- [정적 웹사이트 - React SPA](https://github.com/Azure-Samples/todo-csharp-sql-swa-func) - 정적 콘텐츠 배포  
- [컨테이너 앱 - Python Flask](https://github.com/Azure-Samples/container-apps-store-api-microservice) - REST API 배포  

#### 외부 예제 - 데이터베이스 통합 (3-4장)  
- [데이터베이스 앱 - C# + SQL](https://github.com/Azure-Samples/todo-csharp-sql) - 데이터베이스 연결 패턴  
- [Functions + Cosmos DB](https://github.com/Azure-Samples/todo-python-mongo-swa-func) - 서버리스 데이터 워크플로우  

#### 외부 예제 - 고급 패턴 (4-8장)  
- [Java 마이크로서비스](https://github.com/Azure-Samples/java-microservices-aca-lab) - 다중 서비스 아키텍처  
- [컨테이너 앱 작업](https://github.com/Azure-Samples/container-apps-jobs) - 백그라운드 처리  
- [엔터프라이즈 ML 파이프라인](https://github.com/Azure-Samples/mlops-v2) - 프로덕션 준비 ML 패턴  

### 외부 템플릿 컬렉션
- [**공식 AZD 템플릿 갤러리**](https://azure.github.io/awesome-azd/) - 공식 및 커뮤니티 템플릿 엄선 모음
- [**Azure 개발자 CLI 템플릿**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - Microsoft Learn 템플릿 문서
- [**예제 디렉터리**](examples/README.md) - 자세한 설명이 포함된 로컬 학습 예제

---

## 📚 학습 자료 및 참고 문서

### 빠른 참고 자료
- [**명령어 치트 시트**](resources/cheat-sheet.md) - 챕터별로 정리된 필수 azd 명령어
- [**용어집**](resources/glossary.md) - Azure 및 azd 용어
- [**자주 묻는 질문(FAQ)**](resources/faq.md) - 학습 챕터별 일반 질문
- [**학습 가이드**](resources/study-guide.md) - 종합 연습 문제

### 실습 워크숍
- [**AI 워크숍 랩**](docs/microsoft-foundry/ai-workshop-lab.md) - AI 솔루션을 AZD 배포 가능하게 만들기 (2-3시간)
- [**인터랙티브 워크숍 가이드**](workshop/README.md) - MkDocs 및 DevContainer 환경을 이용한 브라우저 기반 워크숍
- [**구조화된 학습 경로**](../../workshop/docs/instructions) - 7단계 안내 연습(발견 → 배포 → 맞춤화)
- [**AZD 초보자 워크숍**](workshop/README.md) - GitHub Codespaces 통합이 포함된 완전한 실습 자료

### 외부 학습 자료
- [Azure 개발자 CLI 문서](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)
- [Azure 아키텍처 센터](https://learn.microsoft.com/en-us/azure/architecture/)
- [Azure 가격 계산기](https://azure.microsoft.com/pricing/calculator/)
- [Azure 상태](https://status.azure.com/)

---

## 🔧 빠른 문제 해결 가이드

**초보자가 자주 겪는 문제 및 즉시 해결 방법:**

### ❌ "azd: command not found"

```bash
# 먼저 AZD를 설치하세요
# 윈도우 (PowerShell):
winget install microsoft.azd

# 맥OS:
brew tap azure/azd && brew install azd

# 리눅스:
curl -fsSL https://aka.ms/install-azd.sh | bash

# 설치 확인
azd version
```

### ❌ "구독을 찾을 수 없음" 또는 "구독이 설정되지 않음"

```bash
# 사용 가능한 구독 목록
az account list --output table

# 기본 구독 설정
az account set --subscription "<subscription-id-or-name>"

# AZD 환경 설정
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# 확인
az account show
```

### ❌ "InsufficientQuota" 또는 "쿼터 초과"

```bash
# 다른 Azure 지역을 시도해 보십시오
azd env set AZURE_LOCATION "westus2"
azd up

# 또는 개발 시 더 작은 SKU를 사용하십시오
# infra/main.parameters.json을 편집하십시오:
{
  "sku": "B1"  // Instead of "P1V2"
}
```

### ❌ "azd up" 중간에 실패함

```bash
# 옵션 1: 정리하고 다시 시도
azd down --force --purge
azd up

# 옵션 2: 인프라만 수정
azd provision

# 옵션 3: 자세한 로그 확인
azd show
azd logs
```

### ❌ "인증 실패" 또는 "토큰 만료"

```bash
# 다시 인증하기
az logout
az login

azd auth logout
azd auth login

# 인증 확인하기
az account show
```

### ❌ "리소스가 이미 존재함" 또는 이름 충돌 문제

```bash
# AZD는 고유한 이름을 생성하지만, 충돌이 발생하면:
azd down --force --purge

# 새 환경으로 다시 시도합니다
azd env new dev-v2
azd up
```

### ❌ 템플릿 배포가 너무 오래 걸림

**일반적인 대기 시간:**
- 간단한 웹 앱: 5-10분
- 데이터베이스가 포함된 앱: 10-15분
- AI 애플리케이션: 15-25분 (OpenAI 프로비저닝이 느림)

```bash
# 진행 상황 확인
azd show

# 30분 이상 멈춘 경우, Azure 포털 확인:
azd monitor
# 실패한 배포를 찾으세요
```

### ❌ "권한 거부" 또는 "금지됨"

```bash
# Azure 역할을 확인하세요
az role assignment list --assignee $(az account show --query user.name -o tsv)

# 최소한 "기여자" 역할이 필요합니다
# Azure 관리자에게 요청하세요:
# - 기여자 (리소스용)
# - 사용자 액세스 관리자 (역할 할당용)
```

### ❌ 배포된 애플리케이션 URL을 찾을 수 없음

```bash
# 모든 서비스 엔드포인트 표시
azd show

# 또는 Azure 포털 열기
azd monitor

# 특정 서비스 확인
azd env get-values
# *_URL 변수 찾기
```

### 📚 전체 문제 해결 자료

- **일반 문제 가이드:** [자세한 해결책](docs/troubleshooting/common-issues.md)
- **AI 관련 문제:** [AI 문제 해결](docs/troubleshooting/ai-troubleshooting.md)
- **디버깅 가이드:** [단계별 디버깅](docs/troubleshooting/debugging.md)
- **도움 받기:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🔧 빠른 문제 해결 가이드

**초보자가 자주 겪는 문제 및 즉시 해결 방법:**

<details>
<summary><strong>❌ "azd: command not found"</strong></summary>

```bash
# 먼저 AZD를 설치하세요
# 윈도우 (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# 리눅스:
curl -fsSL https://aka.ms/install-azd.sh | bash

# 설치 확인
azd version
```
</details>

<details>
<summary><strong>❌ "구독을 찾을 수 없음" 또는 "구독이 설정되지 않음"</strong></summary>

```bash
# 사용 가능한 구독 목록
az account list --output table

# 기본 구독 설정
az account set --subscription "<subscription-id-or-name>"

# AZD 환경 설정
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# 확인
az account show
```
</details>

<details>
<summary><strong>❌ "InsufficientQuota" 또는 "쿼터 초과"</strong></summary>

```bash
# 다른 Azure 지역을 시도하세요
azd env set AZURE_LOCATION "westus2"
azd up

# 또는 개발 시 더 작은 SKU를 사용하세요
# infra/main.parameters.json을 편집하세요:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>

<details>
<summary><strong>❌ "azd up" 중간에 실패함</strong></summary>

```bash
# 옵션 1: 정리하고 다시 시도
azd down --force --purge
azd up

# 옵션 2: 인프라만 수정
azd provision

# 옵션 3: 자세한 로그 확인
azd show
azd logs
```
</details>

<details>
<summary><strong>❌ "인증 실패" 또는 "토큰 만료"</strong></summary>

```bash
# 재인증
az logout
az login

azd auth logout
azd auth login

# 인증 확인
az account show
```
</details>

<details>
<summary><strong>❌ "리소스가 이미 존재함" 또는 이름 충돌 문제</strong></summary>

```bash
# AZD는 고유한 이름을 생성하지만, 충돌이 발생하면:
azd down --force --purge

# 새 환경으로 다시 시도합니다
azd env new dev-v2
azd up
```
</details>

<details>
<summary><strong>❌ 템플릿 배포가 너무 오래 걸림</strong></summary>

**일반적인 대기 시간:**
- 간단한 웹 앱: 5-10분
- 데이터베이스가 포함된 앱: 10-15분
- AI 애플리케이션: 15-25분 (OpenAI 프로비저닝이 느림)

```bash
# 진행 상황 확인
azd show

# 30분 이상 멈춰 있으면 Azure 포털을 확인하세요:
azd monitor
# 실패한 배포를 찾으세요
```
</details>

<details>
<summary><strong>❌ "권한 거부" 또는 "금지됨"</strong></summary>

```bash
# Azure 역할을 확인하세요
az role assignment list --assignee $(az account show --query user.name -o tsv)

# 최소 "기여자(Contributor)" 역할이 필요합니다
# Azure 관리자에게 권한 부여를 요청하세요:
# - 기여자(Contributor) (리소스용)
# - 사용자 액세스 관리자(User Access Administrator) (역할 할당용)
```
</details>

<details>
<summary><strong>❌ 배포된 애플리케이션 URL을 찾을 수 없음</strong></summary>

```bash
# 모든 서비스 엔드포인트 표시
azd show

# 또는 Azure 포털 열기
azd monitor

# 특정 서비스 확인
azd env get-values
# *_URL 변수 찾기
```
</details>

### 📚 전체 문제 해결 자료

- **일반 문제 가이드:** [자세한 해결책](docs/troubleshooting/common-issues.md)
- **AI 관련 문제:** [AI 문제 해결](docs/troubleshooting/ai-troubleshooting.md)
- **디버깅 가이드:** [단계별 디버깅](docs/troubleshooting/debugging.md)
- **도움 받기:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🎓 과정 완료 및 인증

### 진행 상황 추적
각 챕터별 학습 진행 상황을 확인하세요:

- [ ] **챕터 1**: 기초 및 빠른 시작 ✅
- [ ] **챕터 2**: AI-퍼스트 개발 ✅  
- [ ] **챕터 3**: 구성 및 인증 ✅
- [ ] **챕터 4**: 코드형 인프라 및 배포 ✅
- [ ] **챕터 5**: 다중 에이전트 AI 솔루션 ✅
- [ ] **챕터 6**: 사전 배포 검증 및 계획 ✅
- [ ] **챕터 7**: 문제 해결 및 디버깅 ✅
- [ ] **챕터 8**: 프로덕션 및 엔터프라이즈 패턴 ✅

### 학습 검증
각 챕터를 완료한 후 지식을 확인하는 방법:
1. **실습 연습**: 챕터별 실습 배포 완료
2. **지식 점검**: 챕터별 FAQ 섹션 검토
3. **커뮤니티 토론**: Azure Discord에서 경험 공유
4. **다음 챕터**: 다음 난이도 단계로 이동

### 과정 완료 혜택
모든 챕터를 완료하면 다음을 얻을 수 있습니다:
- **실제 운영 경험**: Azure에 실제 AI 애플리케이션 배포
- **전문 기술**: 엔터프라이즈급 배포 역량  
- **커뮤니티 인지도**: Azure 개발자 커뮤니티의 활발한 구성원
- **경력 발전**: 수요 많은 AZD 및 AI 배포 전문성

---

## 🤝 커뮤니티 및 지원

### 도움말 및 지원 받기
- **기술 문제**: [버그 신고 및 기능 요청](https://github.com/microsoft/azd-for-beginners/issues)
- **학습 질문**: [Microsoft Azure Discord 커뮤니티](https://discord.gg/microsoft-azure) 및 [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **AI 관련 도움**: [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG) 참여
- **문서**: [공식 Azure 개발자 CLI 문서](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)

### Microsoft Foundry Discord 커뮤니티 인사이트

**최근 #Azure 채널 설문 결과:**
- **45%** 개발자들이 AI 워크로드에 AZD 사용 희망
- **주요 도전 과제**: 다중 서비스 배포, 자격 증명 관리, 운영 준비  
- **가장 요청 많은 것**: AI 전용 템플릿, 문제 해결 가이드, 모범 사례

**커뮤니티에 참여하여:**
- AZD + AI 경험 공유 및 도움 받기
- 새로운 AI 템플릿 조기 공개 이용
- AI 배포 모범 사례 기여
- 미래 AI + AZD 기능 개발 영향력 행사

### 과정에 기여하기
기여를 환영합니다! 자세한 내용은 [기여 가이드](CONTRIBUTING.md)를 읽어주세요:
- **콘텐츠 개선**: 기존 챕터 및 예제 강화
- **새로운 예제**: 실제 시나리오 및 템플릿 추가  
- **번역**: 다국어 지원 유지 도움
- **버그 보고**: 정확성 및 명확성 향상
- **커뮤니티 기준**: 포용적 커뮤니티 가이드라인 준수

---

## 📄 과정 정보

### 라이선스
이 프로젝트는 MIT 라이선스 하에 제공됩니다 - 자세한 내용은 [LICENSE](../../LICENSE) 파일 참조.

### 관련 Microsoft 학습 자료

저희 팀은 다른 종합 학습 과정을 제작합니다:

<!-- CO-OP TRANSLATOR OTHER COURSES START -->
### LangChain
[![LangChain4j for Beginners](https://img.shields.io/badge/LangChain4j%20for%20Beginners-22C55E?style=for-the-badge&&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchain4j-for-beginners)
[![LangChain.js for Beginners](https://img.shields.io/badge/LangChain.js%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchainjs-for-beginners?WT.mc_id=m365-94501-dwahlin)

---

### Azure / Edge / MCP / 에이전트
[![AZD for Beginners](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Edge AI for Beginners](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![MCP for Beginners](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)
[![AI Agents for Beginners](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### 생성 AI 시리즈
[![Generative AI for Beginners](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Generative AI (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
[![Generative AI (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)
[![Generative AI (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---
 
### 핵심 학습
[![ML for Beginners](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![Data Science for Beginners](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![AI for Beginners](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Cybersecurity for Beginners](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Web Dev for Beginners](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![IoT for Beginners](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![XR Development for Beginners](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Copilot 시리즈
[![Copilot for AI Paired Programming](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![Copilot for C#/.NET](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Copilot Adventure](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ 강좌 안내

**🚀 학습을 시작할 준비가 되셨나요?**

**초보자**: [1장: 기초 및 빠른 시작](../..)에서 시작하세요  
**AI 개발자**: [2장: AI 우선 개발](../..)로 바로 이동하세요  
**경험 많은 개발자**: [3장: 구성 및 인증](../..)에서 시작하세요

**다음 단계**: [1장 시작 - AZD 기본](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**면책 조항**:  
이 문서는 AI 번역 서비스 [Co-op Translator](https://github.com/Azure/co-op-translator)를 사용하여 번역되었습니다. 정확성을 위해 최선을 다했으나, 자동 번역에는 오류나 부정확한 내용이 포함될 수 있음을 양지해 주시기 바랍니다. 원문 문서가 권위 있는 출처로 간주되어야 합니다. 중요한 정보의 경우 전문적인 사람 번역을 권장합니다. 본 번역 사용으로 인한 어떠한 오해나 잘못된 해석에 대해서도 당사는 책임지지 않습니다.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->