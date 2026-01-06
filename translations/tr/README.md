<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T13:31:09+00:00",
  "source_file": "README.md",
  "language_code": "tr"
}
-->
> Not: Bu dokümantasyon en son değişiklikleri yansıtmak için sürekli güncellenmektedir.

> ⚠️ Bu depo, Localizeflow kullanarak otomatik dokümantasyon yerelleştirmesini göstermek için oluşturulmuş bir demodur.
>
> Orijinal içerik, Microsoft’un “Yeni Başlayanlar için AZD” projesine dayanmaktadır.


# Yeni Başlayanlar için AZD: Yapılandırılmış Bir Öğrenme Yolculuğu

![AZD-for-beginners](../../translated_images/azdbeginners.5527441dd9f74068.tr.png) 

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## Bu Kursa Başlarken

AZD öğrenme yolculuğunuza başlamak için şu adımları izleyin:

1. **Depoyu Forklayın**: Tıklayın [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)
2. **Depoyu Klonlayın**: `git clone https://github.com/microsoft/azd-for-beginners.git`
3. **Topluluğa Katılın**: Uzman desteği için [Azure Discord Toplulukları](https://discord.com/invite/ByRwuEEgH4)
4. **Öğrenme Yolunuzu Seçin**: Deneyim seviyenize uygun aşağıdaki bir bölümü seçin

### Çok Dilli Destek

#### Otomatik Çeviriler (Her Zaman Güncel)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](./README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Yerel Olarak Klonlamayı mı Tercih Ediyorsunuz?**

> Bu depo 50+ dil çevirisi içerdiğinden indirme boyutunu önemli ölçüde artırır. Çeviriler olmadan klonlamak için sparse checkout kullanın:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Bu size kursu tamamlamak için ihtiyacınız olan her şeyi çok daha hızlı indirme ile sağlar.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## Kurs Genel Bakışı

Azure Developer CLI (azd)’yi yapılandırılmış bölümler aracılığıyla kademeli öğrenme için ustalaşın. **Microsoft Foundry entegrasyonu ile AI uygulama dağıtımına özel vurgu.**

### Modern Geliştiriciler İçin Bu Kurs Neden Önemli?

Microsoft Foundry Discord topluluk analizlerine göre, **geliştiricilerin %45’i AI iş yükleri için AZD kullanmak istiyor** ancak şu zorluklarla karşılaşıyorlar:
- Karmaşık çok servisli AI mimarileri
- Üretimde AI dağıtımı en iyi uygulamaları  
- Azure AI hizmet entegrasyonu ve yapılandırması
- AI iş yükleri için maliyet optimizasyonu
- AI spesifik dağıtım sorunlarının giderilmesi

### Öğrenme Hedefleri

Bu yapılandırılmış kursu tamamladığınızda:
- **AZD Temellerini Öğrenin**: Temel kavramlar, kurulum ve yapılandırma
- **AI Uygulamaları Dağıtın**: Microsoft Foundry servisleriyle AZD kullanımı
- **Kod olarak Altyapı Uygulayın**: Bicep şablonları ile Azure kaynak yönetimi
- **Dağıtım Sorunlarını Giderin**: Yaygın sorunlar ve hata ayıklama
- **Üretim için Optimizasyon**: Güvenlik, ölçeklendirme, izleme ve maliyet yönetimi
- **Çok Ajanlı Çözümler Oluşturun**: Karmaşık AI mimarileri dağıtımı

## 📚 Öğrenme Bölümleri

*Deneyim seviyenize ve hedeflerinize göre öğrenme yolunuzu seçin*

### 🚀 Bölüm 1: Temel & Hızlı Başlangıç
**Önkoşullar**: Azure aboneliği, temel komut satırı bilgisi  
**Süre**: 30-45 dakika  
**Zorluk Seviyesi**: ⭐

#### Öğrenecekleriniz
- Azure Developer CLI temellerinin anlaşılması
- Platformunuzda AZD kurulumu
- İlk başarılı dağıtımınız

#### Öğrenme Kaynakları
- **🎯 Başlangıç**: [Azure Developer CLI Nedir?](../..)
- **📖 Teori**: [AZD Temelleri](docs/getting-started/azd-basics.md) - Temel kavramlar ve terminoloji
- **⚙️ Kurulum**: [Kurulum ve Ayarlama](docs/getting-started/installation.md) - Platforma özel kılavuzlar
- **🛠️ Uygulama**: [İlk Projeniz](docs/getting-started/first-project.md) - Adım adım öğretici
- **📋 Hızlı Referans**: [Komut Hilesi](resources/cheat-sheet.md)

#### Pratik Egzersizler
```bash
# Hızlı kurulum kontrolü
azd version

# İlk uygulamanızı dağıtın
azd init --template todo-nodejs-mongo
azd up
```

**💡 Bölüm Sonucu**: AZD kullanarak Azure’a basit bir web uygulaması başarıyla dağıtın

**✅ Başarı Doğrulama:**
```bash
# Bölüm 1'i tamamladıktan sonra şunları yapabilmelisiniz:
azd version              # Yüklü sürümü gösterir
azd init --template todo-nodejs-mongo  # Projeyi başlatır
azd up                  # Azure'a dağıtır
azd show                # Çalışan uygulamanın URL'sini gösterir
# Uygulama tarayıcıda açılır ve çalışır
azd down --force --purge  # Kaynakları temizler
```

**📊 Zaman Yatırımı:** 30-45 dakika  
**📈 Sonraki Beceri Seviyesi:** Temel uygulamaları bağımsız olarak dağıtabilir

**✅ Başarı Doğrulama:**
```bash
# 1. Bölümü tamamladıktan sonra şunları yapabilmelisiniz:
azd version              # Yüklü sürümü gösterir
azd init --template todo-nodejs-mongo  # Projeyi başlatır
azd up                  # Azure'a dağıtır
azd show                # Çalışan uygulamanın URL'sini gösterir
# Uygulama tarayıcıda açılır ve çalışır
azd down --force --purge  # Kaynakları temizler
```

**📊 Zaman Yatırımı:** 30-45 dakika  
**📈 Sonraki Beceri Seviyesi:** Temel uygulamaları bağımsız olarak dağıtabilir

---

### 🤖 Bölüm 2: AI-Öncelikli Geliştirme (AI Geliştiricileri İçin Tavsiye Edilir)
**Önkoşullar**: Bölüm 1 tamamlandı  
**Süre**: 1-2 saat  
**Zorluk Seviyesi**: ⭐⭐

#### Öğrenecekleriniz
- AZD ile Microsoft Foundry entegrasyonu
- AI güdümlü uygulama dağıtımı
- AI servis yapılandırmalarının anlaşılması

#### Öğrenme Kaynakları
- **🎯 Başlangıç**: [Microsoft Foundry Entegrasyonu](docs/microsoft-foundry/microsoft-foundry-integration.md)
- **📖 Kalıplar**: [AI Model Dağıtımı](docs/microsoft-foundry/ai-model-deployment.md) - AI modellerinin dağıtımı ve yönetimi
- **🛠️ Atölye**: [AI Atölye Lab](docs/microsoft-foundry/ai-workshop-lab.md) - AI çözümlerinizi AZD uyumlu yapın
- **🎥 İnteraktif Kılavuz**: [Atölye Materyalleri](workshop/README.md) - MkDocs * DevContainer ortamında tarayıcı tabanlı öğrenme
- **📋 Şablonlar**: [Microsoft Foundry Şablonları](../..)
- **📝 Örnekler**: [AZD Dağıtım Örnekleri](examples/README.md)

#### Pratik Egzersizler
```bash
# İlk yapay zeka uygulamanızı dağıtın
azd init --template azure-search-openai-demo
azd up

# Ek yapay zeka şablonlarını deneyin
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```

**💡 Bölüm Sonucu**: RAG özellikli AI destekli bir sohbet uygulaması dağıtımı ve yapılandırması

**✅ Başarı Doğrulama:**
```bash
# Bölüm 2'den sonra şunları yapabilmelisiniz:
azd init --template azure-search-openai-demo
azd up
# AI sohbet arayüzünü test edin
# Sorular sorun ve kaynaklarla AI destekli yanıtlar alın
# Arama entegrasyonunun çalıştığını doğrulayın
azd monitor  # Application Insights'ın telemetri gösterdiğini kontrol edin
azd down --force --purge
```

**📊 Zaman Yatırımı:** 1-2 saat  
**📈 Sonraki Beceri Seviyesi:** Üretime hazır AI uygulamalarını dağıtabilir ve yapılandırabilir  
**💰 Maliyet Bilinçliliği:** Aylık 80-150 $ geliştirme, 300-3500 $ üretim maliyetlerini anlayabilir

#### 💰 AI Dağıtımları için Maliyet Hususları

**Geliştirme Ortamı (Tahmini 80-150 $/ay):**
- Azure OpenAI (Kullanılan kadar öde): Token kullanımına bağlı olarak 0-50 $/ay
- AI Arama (Temel seviye): 75 $/ay
- Container Apps (Tüketim): 0-20 $/ay
- Depolama (Standart): 1-5 $/ay

**Üretim Ortamı (Tahmini 300-3.500+ $/ay):**
- Azure OpenAI (Sabit Performans İçin PTU): 3.000+ $/ay VEYA Yüksek hacimle Kullanılan kadar öde
- AI Arama (Standart seviye): 250 $/ay
- Container Apps (Ayrılmış): 50-100 $/ay
- Application Insights: 5-50 $/ay
- Depolama (Premium): 10-50 $/ay

**💡 Maliyet Optimizasyonu İpuçları:**
- Öğrenme için Azure OpenAI **Ücretsiz Katmanı** kullanın (aylık 50.000 token dahil)
- Aktif geliştirme yapmadığınızda `azd down` ile kaynakları boşaltın
- Önce tüketim bazlı faturalama ile başlayın, sadece üretim için PTU’ya geçin
- Dağıtmadan önce maliyetleri tahmin etmek için `azd provision --preview` çalıştırın
- Otomatik ölçeklendirmeyi etkinleştirin: sadece gerçek kullanım için ödeme yapın

**Maliyet İzleme:**
```bash
# Tahmini aylık maliyetleri kontrol edin
azd provision --preview

# Azure Portal'daki gerçek maliyetleri izleyin
az consumption budget list --resource-group <your-rg>
```

---

### ⚙️ Bölüm 3: Yapılandırma & Kimlik Doğrulama
**Önkoşullar**: Bölüm 1 tamamlandı  
**Süre**: 45-60 dakika  
**Zorluk Seviyesi**: ⭐⭐

#### Öğrenecekleriniz
- Ortam yapılandırması ve yönetimi
- Kimlik doğrulama ve güvenlik en iyi uygulamaları
- Kaynak isimlendirme ve organizasyon

#### Öğrenme Kaynakları
- **📖 Yapılandırma**: [Yapılandırma Kılavuzu](docs/getting-started/configuration.md) - Ortam kurulumu
- **🔐 Güvenlik**: [Kimlik doğrulama kalıpları ve yönetilen kimlik](docs/getting-started/authsecurity.md) - Kimlik doğrulama kalıpları
- **📝 Örnekler**: [Veritabanı Uygulaması Örneği](examples/database-app/README.md) - AZD Veritabanı örnekleri

#### Pratik Egzersizler
- Birden çok ortam yapılandırması (geliştirme, test, üretim)
- Yönetilen kimlik kimlik doğrulamasını ayarlama
- Ortama özgü yapılandırmaları uygulama

**💡 Bölüm Sonucu**: Birden fazla ortamı doğru kimlik doğrulama ve güvenlik ile yönetin

---

### 🏗️ Bölüm 4: Kod Olarak Altyapı & Dağıtım
**Önkoşullar**: Bölümler 1-3 tamamlandı  
**Süre**: 1-1.5 saat  
**Zorluk Seviyesi**: ⭐⭐⭐

#### Öğrenecekleriniz
- Gelişmiş dağıtım kalıpları
- Bicep ile Kod olarak Altyapı
- Kaynak sağlama stratejileri

#### Öğrenme Kaynakları
- **📖 Dağıtım**: [Dağıtım Kılavuzu](docs/deployment/deployment-guide.md) - Tam iş akışları
- **🏗️ Sağlama**: [Kaynak Sağlama](docs/deployment/provisioning.md) - Azure kaynak yönetimi
- **📝 Örnekler**: [Container App Örneği](../../examples/container-app) - Container tabanlı dağıtımlar

#### Pratik Egzersizler
- Özel Bicep şablonları oluşturma
- Çok servisli uygulamalar dağıtma
- Mavi-yeşil dağıtım stratejilerini uygulama

**💡 Bölüm Sonucu**: Özel altyapı şablonları kullanarak karmaşık çok servisli uygulamalar dağıtın

---
### 🎯 Bölüm 5: Çoklu Ajan AI Çözümleri (Gelişmiş)
**Önkoşullar**: Bölümler 1-2 tamamlandı  
**Süre**: 2-3 saat  
**Zorluk Seviyesi**: ⭐⭐⭐⭐

#### Öğrenecekleriniz
- Çoklu ajan mimari kalıpları
- Ajan orkestrasyonu ve koordinasyonu
- Üretim hazır AI dağıtımları

#### Öğrenme Kaynakları
- **🤖 Öne Çıkan Proje**: [Perakende Çoklu Ajan Çözümü](examples/retail-scenario.md) - Tam uygulama
- **🛠️ ARM Şablonları**: [ARM Şablon Paketi](../../examples/retail-multiagent-arm-template) - Tek tıkla dağıtım
- **📖 Mimari**: [Çoklu ajan koordinasyon kalıpları](/docs/pre-deployment/coordination-patterns.md) - Kalıplar

#### Pratik Egzersizler
```bash
# Tam perakende çoklu ajan çözümünü konuşlandırın
cd examples/retail-multiagent-arm-template
./deploy.sh

# Ajan yapılandırmalarını keşfedin
az deployment group show --resource-group <rg-name> --name <deployment-name>
```

**💡 Bölüm Sonucu**: Müşteri ve Stok ajanları ile üretim hazır çoklu ajan AI çözümü dağıtın ve yönetin

---

### 🔍 Bölüm 6: Dağıtımdan Önce Doğrulama & Planlama
**Önkoşullar**: Bölüm 4 tamamlandı  
**Süre**: 1 saat  
**Zorluk Seviyesi**: ⭐⭐

#### Öğrenecekleriniz
- Kapasite planlaması ve kaynak doğrulaması
- SKU seçim stratejileri
- Uçuş öncesi kontroller ve otomasyon

#### Öğrenme Kaynakları
- **📊 Planlama**: [Kapasite Planlaması](docs/pre-deployment/capacity-planning.md) - Kaynak doğrulama
- **💰 Seçim**: [SKU Seçimi](docs/pre-deployment/sku-selection.md) - Maliyet etkin seçimler
- **✅ Doğrulama**: [Uçuş Öncesi Kontroller](docs/pre-deployment/preflight-checks.md) - Otomatik betikler

#### Pratik Egzersizler
- Kapasite doğrulama betiklerini çalıştırın
- Maliyet için SKU seçimlerini optimize edin
- Otomatik dağıtımdan önceki kontrolleri uygulayın

**💡 Bölüm Sonucu**: Dağıtımları uygulamadan önce doğrulayın ve optimize edin

---

### 🚨 Bölüm 7: Sorun Giderme & Hata Ayıklama
**Önkoşullar**: Herhangi bir dağıtım bölümü tamamlandı  
**Süre**: 1-1.5 saat  
**Zorluk Seviyesi**: ⭐⭐

#### Öğrenecekleriniz
- Sistematik hata ayıklama yöntemleri
- Yaygın sorunlar ve çözümleri
- AI'ya özgü sorun giderme

#### Öğrenme Kaynakları
- **🔧 Yaygın Sorunlar**: [Yaygın Sorunlar](docs/troubleshooting/common-issues.md) - SSS ve çözümler
- **🕵️ Hata Ayıklama**: [Hata Ayıklama Kılavuzu](docs/troubleshooting/debugging.md) - Adım adım stratejiler
- **🤖 AI Sorunları**: [AI'ya Özgü Sorun Giderme](docs/troubleshooting/ai-troubleshooting.md) - AI servis sorunları

#### Pratik Egzersizler
- Dağıtım hatalarını teşhis edin
- Kimlik doğrulama sorunlarını çözün
- AI servis bağlantısını hata ayıklayın

**💡 Bölüm Sonucu**: Yaygın dağıtım sorunlarını bağımsız olarak teşhis edip çözün

---

### 🏢 Bölüm 8: Üretim & Kurumsal Kalıplar
**Önkoşullar**: Bölümler 1-4 tamamlandı  
**Süre**: 2-3 saat  
**Zorluk Seviyesi**: ⭐⭐⭐⭐

#### Öğrenecekleriniz
- Üretim dağıtım stratejileri
- Kurumsal güvenlik kalıpları
- İzleme ve maliyet optimizasyonu

#### Öğrenme Kaynakları
- **🏭 Üretim**: [Üretim AI En İyi Uygulamaları](docs/microsoft-foundry/production-ai-practices.md) - Kurumsal kalıplar
- **📝 Örnekler**: [Mikroservis Örneği](../../examples/microservices) - Karmaşık mimariler
- **📊 İzleme**: [Application Insights entegrasyonu](docs/pre-deployment/application-insights.md) - İzleme

#### Pratik Egzersizler
- Kurumsal güvenlik kalıplarını uygulayın
- Kapsamlı izleme kurun
- Uygun yönetişim ile üretime dağıtım yapın

**💡 Bölüm Sonucu**: Tam üretim özellikli kurumsal hazır uygulamalar dağıtın

---

## 🎓 Atölye Genel Bakış: Uygulamalı Öğrenme Deneyimi

> **⚠️ ATÖLYE DURUMU: Geliştirme Aşamasında**  
> Atölye materyalleri şu anda geliştirilmekte ve iyileştirilmektedir. Ana modüller çalışır durumdadır ancak bazı gelişmiş bölümler tamamlanmamıştır. Bütün içeriğin tamamlanması için aktif çalışıyoruz. [İlerlemeyi takip et →](workshop/README.md)

### Etkileşimli Atölye Materyalleri
**Tarayıcı tabanlı araçlar ve rehberli egzersizlerle kapsamlı uygulamalı öğrenme**

Atölye materyallerimiz yukarıdaki bölüm bazlı müfredata tamamlayıcı, yapılandırılmış ve interaktif bir öğrenme deneyimi sunar. Atölye hem kendi hızınızda öğrenme hem de eğitmen liderliğinde dersler için tasarlanmıştır.

#### 🛠️ Atölye Özellikleri
- **Tarayıcı Tabanlı Arayüz**: MkDocs destekli tam atölye, arama, kopyalama ve tema özellikleriyle
- **GitHub Codespaces Entegrasyonu**: Tek tıkla geliştirme ortamı kurulumu
- **Yapılandırılmış Öğrenme Yolu**: 7 adımlı rehber egzersizler (toplam 3.5 saat)
- **Keşif → Dağıtım → Özelleştirme**: Kademeli metodoloji
- **Etkileşimli DevContainer Ortamı**: Ön yapılandırılmış araçlar ve bağımlılıklar

#### 📚 Atölye Yapısı
Atölye, **Keşif → Dağıtım → Özelleştirme** metodolojisini takip eder:

1. **Keşif Aşaması** (45 dk)
   - Microsoft Foundry şablonlarını ve servislerini keşfedin
   - Çoklu ajan mimari kalıplarını anlayın
   - Dağıtım gereksinimleri ve önkoşullarını gözden geçirin

2. **Dağıtım Aşaması** (2 saat)
   - AZD ile AI uygulamalarını uygulamalı dağıtım
   - Azure AI servisleri ve uç noktalarını yapılandırma
   - Güvenlik ve kimlik doğrulama kalıplarını uygulama

3. **Özelleştirme Aşaması** (45 dk)
   - Uygulamaları özel kullanım durumları için değiştirme
   - Üretim dağıtımı için optimizasyon
   - İzleme ve maliyet yönetimini uygulama

#### 🚀 Atölyeye Başlama
```bash
# Seçenek 1: GitHub Codespaces (Önerilen)
# Depoda "Code" → "main üzerinde codespace oluştur" seçeneğine tıklayın

# Seçenek 2: Yerel Geliştirme
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# workshop/README.md dosyasındaki kurulum talimatlarını izleyin
```

#### 🎯 Atölye Öğrenme Sonuçları
Atölyeyi tamamlayarak katılımcılar:
- **Üretim AI Uygulamaları Dağıtabilir**: Microsoft Foundry servisleri ile AZD kullanarak
- **Çoklu Ajan Mimarilerinde Uzmanlaşır**: Koordine AI ajan çözümleri uygular
- **Güvenlik En İyi Uygulamalarını Uygular**: Kimlik doğrulama ve erişim kontrolu yapılandırır
- **Ölçek için Optimizasyon Yapar**: Maliyet etkin ve performanslı dağıtımlar tasarlar
- **Dağıtımlarda Sorun Giderir**: Yaygın sorunları bağımsız olarak çözer

#### 📖 Atölye Kaynakları
- **🎥 Etkileşimli Rehber**: [Atölye Materyalleri](workshop/README.md) - Tarayıcı tabanlı öğrenme ortamı
- **📋 Adım Adım Talimatlar**: [Rehberli Egzersizler](../../workshop/docs/instructions) - Detaylı anlatımlar
- **🛠️ AI Atölyesi Laboratuvarı**: [AI Atölyesi Lab](docs/microsoft-foundry/ai-workshop-lab.md) - AI odaklı egzersizler
- **💡 Hızlı Başlangıç**: [Atölye Kurulum Kılavuzu](workshop/README.md#quick-start) - Ortam yapılandırması

**Mükemmel kullanım alanları**: Kurumsal eğitimler, üniversite dersleri, kendi hızınızda öğrenme ve geliştirici kampları.

---

## 📖 Azure Developer CLI Nedir?

Azure Developer CLI (azd), uygulamaların Azure’a oluşturulması ve dağıtımını hızlandıran geliştirici odaklı bir komut satırı aracıdır. Sunar:

- **Şablon tabanlı dağıtımlar** - Yaygın uygulama kalıpları için önceden hazırlanmış şablonlar kullanın
- **Kod olarak altyapı** - Azure kaynaklarını Bicep veya Terraform ile yönetin  
- **Entegre iş akışları** - Uygulamaları kusursuzca sağlama, dağıtma ve izleme
- **Geliştirici dostu** - Geliştirici verimliliği ve deneyimi için optimize edilmiş

### **AZD + Microsoft Foundry: AI Dağıtımları İçin Mükemmel**

**AI Çözümleri için neden AZD?** AZD, AI geliştiricilerinin en büyük zorluklarını çözer:

- **AI Hazır Şablonlar** - Azure OpenAI, Cognitive Services ve ML iş yükleri için ön yapılandırılmış şablonlar
- **Güvenli AI Dağıtımları** - AI servisleri, API anahtarları ve model uç noktaları için yerleşik güvenlik kalıpları  
- **Üretim AI Kalıpları** - Ölçeklenebilir, maliyet etkin AI uygulama dağıtımları için en iyi uygulamalar
- **Uçtan Uca AI İş Akışları** - Model geliştirmeden üretim dağıtımına, uygun izlemeyle
- **Maliyet Optimizasyonu** - AI iş yükleri için akıllı kaynak tahsisi ve ölçeklendirme stratejileri
- **Microsoft Foundry Entegrasyonu** - Microsoft Foundry model kataloğu ve uç noktalarına sorunsuz bağlantı

---

## 🎯 Şablonlar & Örnekler Kütüphanesi

### Öne Çıkan: Microsoft Foundry Şablonları
**AI uygulamaları dağıtıyorsanız buradan başlayın!**

> **Not:** Bu şablonlar çeşitli AI kalıplarını gösterir. Bazıları dış Azure Örnekleridir, diğerleri yerel uygulamalardır.

| Şablon | Bölüm | Zorluk Seviyesi | Servisler | Tür |
|----------|---------|------------|----------|------|
| [**Chat AI’ya Başlangıç**](https://github.com/Azure-Samples/get-started-with-ai-chat) | Bölüm 2 | ⭐⭐ | AzureOpenAI + Azure AI Model İnferansı API + Azure AI Arama + Azure Container Apps + Application Insights | Dış |
| [**AI Ajanlarıyla Başlangıç**](https://github.com/Azure-Samples/get-started-with-ai-agents) | Bölüm 2 | ⭐⭐ | Azure AI Ajan Servisi + AzureOpenAI + Azure AI Arama + Azure Container Apps + Application Insights| Dış |
| [**Azure Search + OpenAI Demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Bölüm 2 | ⭐⭐ | AzureOpenAI + Azure AI Arama + App Service + Depolama | Dış |
| [**OpenAI Chat Uygulaması Hızlı Başlangıç**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Bölüm 2 | ⭐ | AzureOpenAI + Container Apps + Application Insights | Dış |
| [**Agent OpenAI Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Bölüm 5 | ⭐⭐⭐ | AzureOpenAI + Azure Functions + Prompty | Dış |
| [**Contoso Chat RAG**](https://github.com/Azure-Samples/contoso-chat) | Bölüm 8 | ⭐⭐⭐⭐ | AzureOpenAI + AI Arama + Cosmos DB + Container Apps | Dış |
| [**Perakende Çoklu Ajan Çözümü**](examples/retail-scenario.md) | Bölüm 5 | ⭐⭐⭐⭐ | AzureOpenAI + AI Arama + Depolama + Container Apps + Cosmos DB | **Yerel** |

### Öne Çıkan: Tam Öğrenme Senaryoları
**Üretim hazır uygulama şablonları öğrenme bölümlerine göre eşlenmiştir**

| Şablon | Öğrenme Bölümü | Zorluk Seviyesi | Ana Öğrenim |
|----------|------------------|------------|--------------|
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Bölüm 2 | ⭐ | Temel AI dağıtım kalıpları |
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Bölüm 2 | ⭐⭐ | Azure AI Arama ile RAG uygulaması |
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | Bölüm 4 | ⭐⭐ | Belge Zekası entegrasyonu |
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Bölüm 5 | ⭐⭐⭐ | Ajan çerçevesi ve fonksiyon çağırma |
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | Bölüm 8 | ⭐⭐⭐ | Kurumsal AI orkestrasyonu |
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | Bölüm 5 | ⭐⭐⭐⭐ | Müşteri ve Stok ajanları ile çoklu ajan mimarisi |

### Örnek Türüne Göre Öğrenme

> **📌 Yerel ve Dış Örnekler:**  
> **Yerel Örnekler** (bu depoda) = Hemen kullanıma hazır  
> **Dış Örnekler** (Azure Örnekleri) = Bağlantılı depolardan klonlanabilir

#### Yerel Örnekler (Kullanıma Hazır)
- [**Perakende Çoklu Ajan Çözümü**](examples/retail-scenario.md) - ARM şablonlarıyla tam üretim hazır uygulama
  - Çoklu ajan mimarisi (Müşteri + Stok ajanları)
  - Kapsamlı izleme ve değerlendirme
  - ARM şablonu ile tek tık dağıtım

#### Yerel Örnekler - Konteyner Uygulamaları (Bölümler 2-5)
**Bu depoda kapsamlı konteyner dağıtım örnekleri:**
- [**Konteyner Uygulama Örnekleri**](examples/container-app/README.md) - Konteyner tabanlı dağıtımlar için kapsamlı rehber
  - [Basit Flask API](../../examples/container-app/simple-flask-api) - Ölçeklendirme destekli basit REST API
  - [Mikroservis Mimarisi](../../examples/container-app/microservices) - Üretim hazır çok servisli dağıtım
  - Hızlı Başlangıç, Üretim ve Gelişmiş dağıtım kalıpları
  - İzleme, güvenlik ve maliyet optimizasyonu rehberi

#### Dış Örnekler - Basit Uygulamalar (Bölümler 1-2)
**Başlamak için şu Azure Örnekleri depolarını klonlayın:**
- [Basit Web Uygulaması - Node.js + MongoDB](https://github.com/Azure-Samples/todo-nodejs-mongo) - Temel dağıtım kalıpları
- [Statik Web Sitesi - React SPA](https://github.com/Azure-Samples/todo-csharp-sql-swa-func) - Statik içerik dağıtımı
- [Konteyner Uygulaması - Python Flask](https://github.com/Azure-Samples/container-apps-store-api-microservice) - REST API dağıtımı

#### Dış Örnekler - Veritabanı Entegrasyonu (Bölümler 3-4)  
- [Veritabanı Uygulaması - C# + SQL](https://github.com/Azure-Samples/todo-csharp-sql) - Veritabanı bağlantı kalıpları
- [Functions + Cosmos DB](https://github.com/Azure-Samples/todo-python-mongo-swa-func) - Sunucusuz veri iş akışı

#### Dış Örnekler - Gelişmiş Kalıplar (Bölümler 4-8)
- [Java Mikroservisler](https://github.com/Azure-Samples/java-microservices-aca-lab) - Çok servisli mimariler
- [Konteyner Uygulamaları İşleri](https://github.com/Azure-Samples/container-apps-jobs) - Arka plan işleme  
- [Kurumsal ML Boru Hattı](https://github.com/Azure-Samples/mlops-v2) - Üretim hazır ML kalıpları

### Dış Şablon Koleksiyonları
- [**Resmi AZD Şablon Galerisi**](https://azure.github.io/awesome-azd/) - Resmi ve topluluk şablonlarının seçilmiş koleksiyonu
- [**Azure Developer CLI Şablonları**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - Microsoft Learn şablon dokümantasyonu
- [**Örnekler Dizini**](examples/README.md) - Detaylı açıklamalarla yerel öğrenme örnekleri

---

## 📚 Öğrenme Kaynakları ve Referanslar

### Hızlı Referanslar
- [**Komut Hile Sayfası**](resources/cheat-sheet.md) - Bölümlere göre düzenlenmiş temel azd komutları
- [**Terimler Sözlüğü**](resources/glossary.md) - Azure ve azd terimleri  
- [**SSS**](resources/faq.md) - Öğrenme bölümlerine göre düzenlenmiş sık sorulan sorular
- [**Çalışma Rehberi**](resources/study-guide.md) - Kapsamlı uygulama alıştırmaları

### Uygulamalı Atölyeler
- [**AI Atölyesi Laboratuvarı**](docs/microsoft-foundry/ai-workshop-lab.md) - AI çözümlerinizi AZD ile dağıtılabilir hale getirin (2-3 saat)
- [**Etkileşimli Atölye Rehberi**](workshop/README.md) - MkDocs ve DevContainer ortamıyla tarayıcı tabanlı atölye
- [**Yapılandırılmış Öğrenme Yolu**](../../workshop/docs/instructions) - 7 adımlı yönlendirilmiş alıştırmalar (Keşif → Dağıtım → Özelleştirme)
- [**AZD Yeni Başlayanlar Atölyesi**](workshop/README.md) - GitHub Codespaces entegrasyonlu eksiksiz uygulamalı atölye materyalleri

### Dış Öğrenme Kaynakları
- [Azure Developer CLI Dokümantasyonu](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)
- [Azure Mimari Merkezi](https://learn.microsoft.com/en-us/azure/architecture/)
- [Azure Fiyatlandırma Hesaplayıcısı](https://azure.microsoft.com/pricing/calculator/)
- [Azure Durumu](https://status.azure.com/)

---

## 🔧 Hızlı Sorun Giderme Rehberi

**Yeni başlayanların karşılaştığı yaygın sorunlar ve hızlı çözümler:**

### ❌ "azd: komut bulunamadı"

```bash
# Önce AZD'yi yükleyin
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Yüklemeyi doğrulayın
azd version
```

### ❌ "Abonelik bulunamadı" veya "Abonelik ayarlanmadı"

```bash
# Mevcut abonelikleri listele
az account list --output table

# Varsayılan aboneliği ayarla
az account set --subscription "<subscription-id-or-name>"

# AZD ortamı için ayarla
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Doğrula
az account show
```

### ❌ "Yetersiz Kota" veya "Kota aşıldı"

```bash
# Farklı bir Azure bölgesi deneyin
azd env set AZURE_LOCATION "westus2"
azd up

# Veya geliştirmede daha küçük SKU'lar kullanın
# infra/main.parameters.json dosyasını düzenleyin:
{
  "sku": "B1"  // Instead of "P1V2"
}
```

### ❌ "azd up" yarıda başarısız oldu

```bash
# Seçenek 1: Temizle ve yeniden dene
azd down --force --purge
azd up

# Seçenek 2: Sadece altyapıyı düzelt
azd provision

# Seçenek 3: Detaylı günlükleri kontrol et
azd show
azd logs
```

### ❌ "Kimlik doğrulama başarısız" veya "Token süresi doldu"

```bash
# Yeniden kimlik doğrulama
az logout
az login

azd auth logout
azd auth login

# Kimlik doğrulamasını doğrula
az account show
```

### ❌ "Kaynak zaten mevcut" veya adlandırma çakışmaları

```bash
# AZD benzersiz isimler oluşturur, ancak çakışma olursa:
azd down --force --purge

# Sonra yeni ortam ile tekrar dene
azd env new dev-v2
azd up
```

### ❌ Şablon dağıtımı çok uzun sürüyor

**Normal bekleme süreleri:**
- Basit web uygulaması: 5-10 dakika
- Veritabanlı uygulama: 10-15 dakika
- AI uygulamaları: 15-25 dakika (OpenAI sağlama yavaştır)

```bash
# İlerlemi kontrol et
azd show

# 30 dakikadan fazla takılı kalırsa, Azure Portal'ı kontrol et:
azd monitor
# Başarısız dağıtımları ara
```

### ❌ "İzin reddedildi" veya "Yasaklandı"

```bash
# Azure rolünüzü kontrol edin
az role assignment list --assignee $(az account show --query user.name -o tsv)

# En az "Katkıda Bulunan" rolüne ihtiyacınız var
# Azure yöneticinizden şunu vermesini isteyin:
# - Katkıda Bulunan (kaynaklar için)
# - Kullanıcı Erişim Yöneticisi (rol atamaları için)
```

### ❌ Dağıtılan uygulama URL'si bulunamıyor

```bash
# Tüm servis uç noktalarını göster
azd show

# Ya da Azure Portalı aç
azd monitor

# Belirli servisi kontrol et
azd env get-values
# *_URL değişkenlerini ara
```

### 📚 Tam Sorun Giderme Kaynakları

- **Yaygın Sorunlar Kılavuzu:** [Detaylı Çözümler](docs/troubleshooting/common-issues.md)
- **AI Özel Sorunlar:** [AI Sorun Giderme](docs/troubleshooting/ai-troubleshooting.md)
- **Hata Ayıklama Rehberi:** [Adım Adım Hata Ayıklama](docs/troubleshooting/debugging.md)
- **Yardım Al:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🔧 Hızlı Sorun Giderme Rehberi

**Yeni başlayanların karşılaştığı yaygın sorunlar ve hızlı çözümler:**

<details>
<summary><strong>❌ "azd: komut bulunamadı"</strong></summary>

```bash
# Öncelikle AZD'yi kurun
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Kurulumu doğrulayın
azd version
```
</details>

<details>
<summary><strong>❌ "Abonelik bulunamadı" veya "Abonelik ayarlanmadı"</strong></summary>

```bash
# Mevcut abonelikleri listele
az account list --output table

# Varsayılan aboneliği ayarla
az account set --subscription "<subscription-id-or-name>"

# AZD ortamı için ayarla
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Doğrula
az account show
```
</details>

<details>
<summary><strong>❌ "Yetersiz Kota" veya "Kota aşıldı"</strong></summary>

```bash
# Farklı bir Azure bölgesi deneyin
azd env set AZURE_LOCATION "westus2"
azd up

# Ya da geliştirmede daha küçük SKU'lar kullanın
# infra/main.parameters.json dosyasını düzenleyin:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>

<details>
<summary><strong>❌ "azd up" yarıda başarısız oldu</strong></summary>

```bash
# Seçenek 1: Temizle ve tekrar dene
azd down --force --purge
azd up

# Seçenek 2: Sadece altyapıyı düzelt
azd provision

# Seçenek 3: Detaylı günlükleri kontrol et
azd show
azd logs
```
</details>

<details>
<summary><strong>❌ "Kimlik doğrulama başarısız" veya "Token süresi doldu"</strong></summary>

```bash
# Yeniden kimlik doğrulama
az logout
az login

azd auth logout
azd auth login

# Kimlik doğrulamayı doğrula
az account show
```
</details>

<details>
<summary><strong>❌ "Kaynak zaten mevcut" veya adlandırma çakışmaları</strong></summary>

```bash
# AZD benzersiz isimler üretir, ancak çakışma olursa:
azd down --force --purge

# O zaman yeni bir ortamla tekrar deneyin
azd env new dev-v2
azd up
```
</details>

<details>
<summary><strong>❌ Şablon dağıtımı çok uzun sürüyor</strong></summary>

**Normal bekleme süreleri:**
- Basit web uygulaması: 5-10 dakika
- Veritabanlı uygulama: 10-15 dakika
- AI uygulamaları: 15-25 dakika (OpenAI sağlama yavaştır)

```bash
# İlerlemeni kontrol et
azd show

# 30 dakikadan uzun takılı kalındıysa, Azure Portal'ı kontrol et:
azd monitor
# Başarısız dağıtımları ara
```
</details>

<details>
<summary><strong>❌ "İzin reddedildi" veya "Yasaklandı"</strong></summary>

```bash
# Azure rolünüzü kontrol edin
az role assignment list --assignee $(az account show --query user.name -o tsv)

# En az "Katkıda Bulunan" rolüne ihtiyacınız var
# Azure yöneticinizden şu yetkileri vermesini isteyin:
# - Katkıda Bulunan (kaynaklar için)
# - Kullanıcı Erişim Yöneticisi (rol atamaları için)
```
</details>

<details>
<summary><strong>❌ Dağıtılan uygulama URL'si bulunamıyor</strong></summary>

```bash
# Tüm servis uç noktalarını göster
azd show

# Ya da Azure Portalı aç
azd monitor

# Belirli servisi kontrol et
azd env get-values
# *_URL değişkenlerini ara
```
</details>

### 📚 Tam Sorun Giderme Kaynakları

- **Yaygın Sorunlar Kılavuzu:** [Detaylı Çözümler](docs/troubleshooting/common-issues.md)
- **AI Özel Sorunlar:** [AI Sorun Giderme](docs/troubleshooting/ai-troubleshooting.md)
- **Hata Ayıklama Rehberi:** [Adım Adım Hata Ayıklama](docs/troubleshooting/debugging.md)
- **Yardım Al:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🎓 Kurs Tamamlama & Sertifikasyon

### İlerleme Takibi
Her bölümde öğrenme ilerlemenizi takip edin:

- [ ] **Bölüm 1**: Temel & Hızlı Başlangıç ✅
- [ ] **Bölüm 2**: AI-Öncelikli Geliştirme ✅  
- [ ] **Bölüm 3**: Yapılandırma & Kimlik Doğrulama ✅
- [ ] **Bölüm 4**: Kod Olarak Altyapı & Dağıtım ✅
- [ ] **Bölüm 5**: Çok Ajanlı AI Çözümleri ✅
- [ ] **Bölüm 6**: Dağıtım Öncesi Doğrulama & Planlama ✅
- [ ] **Bölüm 7**: Sorun Giderme & Hata Ayıklama ✅
- [ ] **Bölüm 8**: Üretim & Kurumsal Desenler ✅

### Öğrenme Doğrulama
Her bölümü tamamladıktan sonra bilginizi doğrulayın:
1. **Pratik Egzersiz**: Bölümün uygulamalı dağıtımını tamamlayın
2. **Bilgi Kontrolü**: Bölümün SSS bölümünü inceleyin
3. **Topluluk Tartışması**: Azure Discord'da deneyiminizi paylaşın
4. **Sonraki Bölüm**: Sonraki karmaşıklık seviyesine geçin

### Kurs Tamamlama Avantajları
Tüm bölümleri tamamladığınızda elde edeceksiniz:
- **Üretim Deneyimi**: Gerçek AI uygulamalarını Azure’a dağıttınız
- **Profesyonel Beceriler**: Kurumsal düzeye hazır dağıtım yetenekleri  
- **Topluluk Tanınırlığı**: Azure geliştirici topluluğunun aktif üyesi
- **Kariyer İlerlemesi**: Talep gören AZD ve AI dağıtım uzmanlığı

---

## 🤝 Topluluk & Destek

### Yardım & Destek Alın
- **Teknik Sorunlar**: [Hata raporlayın ve özellik isteyin](https://github.com/microsoft/azd-for-beginners/issues)
- **Öğrenme Soruları**: [Microsoft Azure Discord Topluluğu](https://discord.gg/microsoft-azure) ve [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **AI Özel Yardım**: Katılın [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **Dokümantasyon**: [Resmi Azure Developer CLI dokümantasyonu](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)

### Microsoft Foundry Discord’dan Topluluk İçgörüleri

**#Azure Kanalında Son Anket Sonuçları:**
- Geliştiricilerin **%45'i** AI iş yükleri için AZD kullanmak istiyor
- **Başlıca zorluklar**: Çoklu servis dağıtımları, kimlik yönetimi, üretim hazır olma  
- **En çok talep edilenler**: AI-özel şablonlar, sorun giderme rehberleri, en iyi uygulamalar

**Topluluğumuza katılın ve:**
- AZD + AI deneyimlerinizi paylaşın ve yardım alın
- Yeni AI şablonlarının erken sürümlerine erişin
- AI dağıtım en iyi uygulamalarına katkıda bulunun
- Gelecekteki AI + AZD özellik geliştirmelerine yön verin

### Kursa Katkıda Bulunma
Katkılarınızı bekliyoruz! Detaylar için lütfen [Katkıda Bulunma Kılavuzu](CONTRIBUTING.md)’nu okuyun:
- **İçerik İyileştirmeleri**: Mevcut bölümler ve örnekleri geliştirin
- **Yeni Örnekler**: Gerçek dünya senaryoları ve şablonlar ekleyin  
- **Çeviri**: Çoklu dil desteğinin sürdürülmesine yardımcı olun
- **Hata Bildirimleri**: Doğruluk ve anlaşılırlığı artırın
- **Topluluk Standartları**: Kapsayıcı topluluk kurallarımıza uyun

---

## 📄 Kurs Bilgileri

### Lisans
Bu proje MIT Lisansı altında lisanslanmıştır - ayrıntılar için [LICENSE](../../LICENSE) dosyasına bakınız.

### İlgili Microsoft Öğrenme Kaynakları

Ekibimiz diğer kapsamlı öğrenme kursları da üretmektedir:

<!-- CO-OP TRANSLATOR OTHER COURSES START -->
### LangChain
[![LangChain4j for Beginners](https://img.shields.io/badge/LangChain4j%20for%20Beginners-22C55E?style=for-the-badge&&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchain4j-for-beginners)
[![LangChain.js for Beginners](https://img.shields.io/badge/LangChain.js%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchainjs-for-beginners?WT.mc_id=m365-94501-dwahlin)

---

### Azure / Edge / MCP / Ajanlar
[![AZD for Beginners](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Edge AI for Beginners](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![MCP for Beginners](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)
[![AI Agents for Beginners](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Üretken AI Serisi
[![Generative AI for Beginners](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Generative AI (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
[![Generative AI (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)
[![Generative AI (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---
 
### Temel Öğrenme
[![ML for Beginners](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![Yeni Başlayanlar için Veri Bilimi](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![Yeni Başlayanlar için Yapay Zeka](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Yeni Başlayanlar için Siber Güvenlik](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Yeni Başlayanlar için Web Geliştirme](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![Yeni Başlayanlar için IoT](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![Yeni Başlayanlar için XR Geliştirme](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---

### Copilot Serisi
[![Yapay Zeka ile Eş Programlama için Copilot](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![C#/.NET için Copilot](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Copilot Macerası](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ Kurs Navigasyonu

**🚀 Öğrenmeye Başlamaya Hazır mısınız?**

**Yeni Başlayanlar**: [Bölüm 1: Temel ve Hızlı Başlangıç](../..) ile başlayın  
**Yapay Zeka Geliştiricileri**: [Bölüm 2: Yapay Zeka Öncelikli Geliştirme](../..) kısmına atlayın  
**Deneyimli Geliştiriciler**: [Bölüm 3: Konfigürasyon ve Kimlik Doğrulama](../..) ile başlayın

**Sonraki Adımlar**: [1. Bölüme Başlayın - AZD Temelleri](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Feragatname**:  
Bu belge, AI çeviri servisi [Co-op Translator](https://github.com/Azure/co-op-translator) kullanılarak çevrilmiştir. Doğruluk için çaba göstersek de, otomatik çevirilerin hata veya yanlışlık içerebileceğini lütfen unutmayınız. Orijinal belge, ana dilindeki haliyle yetkili kaynak olarak kabul edilmelidir. Kritik bilgiler için profesyonel insan çevirisi önerilir. Bu çevirinin kullanımı nedeniyle oluşabilecek yanlış anlamalar veya yanlış yorumlamalar için sorumluluk kabul edilmemektedir.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->