<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T14:07:10+00:00",
  "source_file": "README.md",
  "language_code": "ms"
}
-->
> Nota: Dokumentasi ini sentiasa dikemas kini untuk mencerminkan perubahan terkini.

> ⚠️ Repositori ini adalah demo yang dibuat untuk mempamerkan
> pelokalan dokumentasi automatik menggunakan Localizeflow.
>
> Kandungan asal adalah berdasarkan proyek
> “AZD untuk Pemula” Microsoft.


# AZD Untuk Pemula: Perjalanan Pembelajaran Berstruktur

![AZD-for-beginners](../../translated_images/azdbeginners.5527441dd9f74068.ms.png) 

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## Memulakan Kursus Ini

Ikuti langkah-langkah ini untuk memulakan perjalanan pembelajaran AZD anda:

1. **Fork Repositori**: Klik [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)
2. **Clone Repositori**: `git clone https://github.com/microsoft/azd-for-beginners.git`
3. **Sertai Komuniti**: [Komuniti Discord Azure](https://discord.com/invite/ByRwuEEgH4) untuk sokongan pakar
4. **Pilih Laluan Pembelajaran Anda**: Pilih bab di bawah yang sepadan dengan tahap pengalaman anda

### Sokongan Pelbagai Bahasa

#### Terjemahan Automatik (Sentiasa Dikemas Kini)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](./README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Lebih Suka Clone Secara Tempatan?**

> Repositori ini termasuk lebih 50+ terjemahan bahasa yang meningkatkan saiz muat turun dengan ketara. Untuk clone tanpa terjemahan, gunakan sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Ini memberi anda segala yang anda perlukan untuk menamatkan kursus dengan muat turun yang jauh lebih pantas.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## Gambaran Keseluruhan Kursus

Kuasi Azure Developer CLI (azd) melalui bab berstruktur yang direka untuk pembelajaran berperingkat. **Fokus khas kepada penyebaran aplikasi AI dengan integrasi Microsoft Foundry.**

### Mengapa Kursus Ini Penting untuk Pembangun Moden

Berdasarkan pandangan komuniti Discord Microsoft Foundry, **45% pembangun mahu menggunakan AZD untuk beban kerja AI** tetapi menghadapi cabaran dengan:
- Seni bina AI multi-perkhidmatan yang kompleks
- Amalan terbaik penyebaran AI dalam produksi  
- Integrasi dan konfigurasi perkhidmatan Azure AI
- Pengoptimuman kos untuk beban kerja AI
- Menyelesaikan masalah penyebaran AI khusus

### Objektif Pembelajaran

Dengan menamatkan kursus berstruktur ini, anda akan:
- **Menguasai Asas AZD**: Konsep teras, pemasangan, dan konfigurasi
- **Menyebarkan Aplikasi AI**: Gunakan AZD dengan perkhidmatan Microsoft Foundry
- **Melaksanakan Infrastruktur sebagai Kod**: Urus sumber Azure dengan templat Bicep
- **Menyelesaikan Masalah Penyebaran**: Atasi isu biasa dan debug masalah
- **Mengoptimumkan untuk Produksi**: Keselamatan, penskalaan, pemantauan, dan pengurusan kos
- **Membina Penyelesaian Multi-Ejen**: Sebarkan seni bina AI kompleks

## 📚 Bab Pembelajaran

*Pilih laluan pembelajaran berdasarkan tahap pengalaman dan matlamat*

### 🚀 Bab 1: Asas & Mula Cepat
**Prasyarat**: Langganan Azure, pengetahuan asas baris perintah  
**Tempoh**: 30-45 minit  
**Kerumitan**: ⭐

#### Apa Yang Anda Akan Belajar
- Memahami asas Azure Developer CLI
- Memasang AZD pada platform anda
- Penyebaran pertama anda yang berjaya

#### Sumber Pembelajaran
- **🎯 Mula Di Sini**: [Apa Itu Azure Developer CLI?](../..)
- **📖 Teori**: [Asas AZD](docs/getting-started/azd-basics.md) - Konsep teras dan terminologi
- **⚙️ Penyediaan**: [Pemasangan & Persediaan](docs/getting-started/installation.md) - Panduan khusus platform
- **🛠️ Praktikal**: [Projek Pertama Anda](docs/getting-started/first-project.md) - Tutorial langkah demi langkah
- **📋 Rujukan Pantas**: [Lembaran Cheat Perintah](resources/cheat-sheet.md)

#### Latihan Praktikal
```bash
# Semakan pemasangan pantas
azd version

# Sebarkan aplikasi pertama anda
azd init --template todo-nodejs-mongo
azd up
```

**💡 Hasil Bab**: Berjaya menyebarkan aplikasi web mudah ke Azure menggunakan AZD

**✅ Pengesahan Kejayaan:**
```bash
# Selepas menyelesaikan Bab 1, anda sepatutnya dapat:
azd version              # Menunjukkan versi yang dipasang
azd init --template todo-nodejs-mongo  # Memulakan projek
azd up                  # Menggunakan ke Azure
azd show                # Memaparkan URL aplikasi yang berjalan
# Aplikasi dibuka dalam pelayar dan berfungsi
azd down --force --purge  # Membersihkan sumber
```

**📊 Pelaburan Masa:** 30-45 minit  
**📈 Tahap Kemahiran Selepas:** Boleh menyebarkan aplikasi asas secara berdikari

**✅ Pengesahan Kejayaan:**
```bash
# Selepas menyiapkan Bab 1, anda sepatutnya boleh:
azd version              # Menunjukkan versi yang dipasang
azd init --template todo-nodejs-mongo  # Memulakan projek
azd up                  # Menghantar ke Azure
azd show                # Memaparkan URL aplikasi yang sedang berjalan
# Aplikasi dibuka dalam pelayar dan berfungsi
azd down --force --purge  # Membersihkan sumber
```

**📊 Pelaburan Masa:** 30-45 minit  
**📈 Tahap Kemahiran Selepas:** Boleh menyebarkan aplikasi asas secara berdikari

---

### 🤖 Bab 2: Pembangunan Utama AI (Disyorkan untuk Pembangun AI)
**Prasyarat**: Bab 1 selesai  
**Tempoh**: 1-2 jam  
**Kerumitan**: ⭐⭐

#### Apa Yang Anda Akan Belajar
- Integrasi Microsoft Foundry dengan AZD
- Menyebarkan aplikasi bertenaga AI
- Memahami konfigurasi perkhidmatan AI

#### Sumber Pembelajaran
- **🎯 Mula Di Sini**: [Integrasi Microsoft Foundry](docs/microsoft-foundry/microsoft-foundry-integration.md)
- **📖 Corak**: [Penyebaran Model AI](docs/microsoft-foundry/ai-model-deployment.md) - Menyebar dan mengurus model AI
- **🛠️ Bengkel**: [Makmal Bengkel AI](docs/microsoft-foundry/ai-workshop-lab.md) - Jadikan penyelesaian AI anda sedia AZD
- **🎥 Panduan Interaktif**: [Bahan Bengkel](workshop/README.md) - Pembelajaran berasaskan pelayar dengan MkDocs * Persekitaran DevContainer
- **📋 Templat**: [Templat Microsoft Foundry](../..)
- **📝 Contoh**: [Contoh Penyebaran AZD](examples/README.md)

#### Latihan Praktikal
```bash
# Sebarkan aplikasi AI pertama anda
azd init --template azure-search-openai-demo
azd up

# Cuba templat AI tambahan
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```

**💡 Hasil Bab**: Menyebar dan mengkonfigurasi aplikasi sembang bertenaga AI dengan keupayaan RAG

**✅ Pengesahan Kejayaan:**
```bash
# Selepas Bab 2, anda harus boleh:
azd init --template azure-search-openai-demo
azd up
# Uji antara muka sembang AI
# Tanyakan soalan dan dapatkan jawapan dikuasakan AI dengan sumber
# Sahkan integrasi carian berfungsi
azd monitor  # Semak Application Insights menunjukkan telemetri
azd down --force --purge
```

**📊 Pelaburan Masa:** 1-2 jam  
**📈 Tahap Kemahiran Selepas:** Boleh menyebar dan mengkonfigurasi aplikasi AI sedia produksi  
**💰 Kesedaran Kos:** Fahami kos pembangunan $80-150/bulan, kos produksi $300-3500/bulan

#### 💰 Pertimbangan Kos untuk Penyebaran AI

**Persekitaran Pembangunan (Anggaran $80-150/bulan):**
- Azure OpenAI (Bayar ikut guna): $0-50/bulan (berdasarkan penggunaan token)
- AI Search (tahap asas): $75/bulan
- Container Apps (Penggunaan): $0-20/bulan
- Penyimpanan (Standard): $1-5/bulan

**Persekitaran Produksi (Anggaran $300-3,500+/bulan):**
- Azure OpenAI (PTU untuk prestasi konsisten): $3,000+/bulan ATAU Bayar ikut guna dengan volum tinggi
- AI Search (tahap standard): $250/bulan
- Container Apps (Didedikasikan): $50-100/bulan
- Application Insights: $5-50/bulan
- Penyimpanan (Premium): $10-50/bulan

**💡 Petua Pengoptimuman Kos:**
- Gunakan **Tahap Percuma** Azure OpenAI untuk pembelajaran (termasuk 50,000 token/bulan)
- Jalankan `azd down` untuk membebaskan sumber apabila tidak membangun secara aktif
- Mulakan dengan pengebilan berasaskan penggunaan, naik taraf ke PTU hanya untuk produksi
- Gunakan `azd provision --preview` untuk menganggarkan kos sebelum penyebaran
- Aktifkan auto-scaling: bayar hanya untuk penggunaan sebenar

**Pemantauan Kos:**
```bash
# Semak anggaran kos bulanan
azd provision --preview

# Pantau kos sebenar di Portal Azure
az consumption budget list --resource-group <your-rg>
```

---

### ⚙️ Bab 3: Konfigurasi & Pengesahan
**Prasyarat**: Bab 1 selesai  
**Tempoh**: 45-60 minit  
**Kerumitan**: ⭐⭐

#### Apa Yang Anda Akan Belajar
- Konfigurasi dan pengurusan persekitaran
- Pengesahan dan amalan terbaik keselamatan
- Penamaan dan organisasi sumber

#### Sumber Pembelajaran
- **📖 Konfigurasi**: [Panduan Konfigurasi](docs/getting-started/configuration.md) - Persediaan persekitaran
- **🔐 Keselamatan**: [Corak pengesahan dan identiti terurus](docs/getting-started/authsecurity.md) - Corak pengesahan
- **📝 Contoh**: [Contoh Aplikasi Pangkalan Data](examples/database-app/README.md) - Contoh Pangkalan Data AZD

#### Latihan Praktikal
- Konfigurasi pelbagai persekitaran (dev, staging, prod)
- Sediakan pengesahan identiti terurus
- Laksanakan konfigurasi khusus persekitaran

**💡 Hasil Bab**: Mengurus pelbagai persekitaran dengan pengesahan dan keselamatan yang betul

---

### 🏗️ Bab 4: Infrastruktur sebagai Kod & Penyebaran
**Prasyarat**: Bab 1-3 selesai  
**Tempoh**: 1-1.5 jam  
**Kerumitan**: ⭐⭐⭐

#### Apa Yang Anda Akan Belajar
- Corak penyebaran lanjutan
- Infrastruktur sebagai Kod dengan Bicep
- Strategi penyediaan sumber

#### Sumber Pembelajaran
- **📖 Penyebaran**: [Panduan Penyebaran](docs/deployment/deployment-guide.md) - Aliran kerja lengkap
- **🏗️ Penyediaan**: [Penyediaan Sumber](docs/deployment/provisioning.md) - Pengurusan sumber Azure
- **📝 Contoh**: [Contoh Aplikasi Kontena](../../examples/container-app) - Penyebaran berasaskan kontena

#### Latihan Praktikal
- Cipta templat Bicep khusus
- Sebarkan aplikasi multi-perkhidmatan
- Laksanakan strategi penyebaran blue-green

**💡 Hasil Bab**: Menyebarkan aplikasi multi-perkhidmatan kompleks menggunakan templat infrastruktur khusus

---
### 🎯 Bab 5: Penyelesaian AI Berbilang Ejen (Lanjutan)
**Prasyarat**: Bab 1-2 selesai  
**Tempoh**: 2-3 jam  
**Kerumitan**: ⭐⭐⭐⭐

#### Apa Yang Akan Anda Pelajari
- Corak seni bina berbilang ejen
- Orkestrasi dan koordinasi ejen
- Penempatan AI sedia untuk produksi

#### Sumber Pembelajaran
- **🤖 Projek Pilihan**: [Penyelesaian Berbilang Ejen Runcit](examples/retail-scenario.md) - Pelaksanaan lengkap
- **🛠️ Templat ARM**: [Pakej Templat ARM](../../examples/retail-multiagent-arm-template) - Penempatan satu klik
- **📖 Seni Bina**: [Corak koordinasi berbilang ejen](/docs/pre-deployment/coordination-patterns.md) - Corak

#### Latihan Praktikal
```bash
# Menggunakan penyelesaian ejen berganda runcit yang lengkap
cd examples/retail-multiagent-arm-template
./deploy.sh

# Terokai konfigurasi ejen
az deployment group show --resource-group <rg-name> --name <deployment-name>
```

**💡 Hasil Bab**: Menempatkan dan mengurus penyelesaian AI berbilang ejen sedia produksi dengan ejen Pelanggan dan Inventori

---

### 🔍 Bab 6: Pengesahan & Perancangan Pra-Penempatan
**Prasyarat**: Bab 4 selesai  
**Tempoh**: 1 jam  
**Kerumitan**: ⭐⭐

#### Apa Yang Akan Anda Pelajari
- Perancangan kapasiti dan pengesahan sumber
- Strategi pemilihan SKU
- Pemeriksaan pra-penerbangan dan automasi

#### Sumber Pembelajaran
- **📊 Perancangan**: [Perancangan Kapasiti](docs/pre-deployment/capacity-planning.md) - Pengesahan sumber
- **💰 Pemilihan**: [Pemilihan SKU](docs/pre-deployment/sku-selection.md) - Pilihan kos efektif
- **✅ Pengesahan**: [Pemeriksaan Pra-penerbangan](docs/pre-deployment/preflight-checks.md) - Skrip automatik

#### Latihan Praktikal
- Jalankan skrip pengesahan kapasiti
- Optimumkan pemilihan SKU untuk kos
- Laksanakan pemeriksaan pra-penempatan automatik

**💡 Hasil Bab**: Mengesahkan dan mengoptimumkan penempatan sebelum pelaksanaan

---

### 🚨 Bab 7: Penyelesaian Masalah & Pengubahsuaian
**Prasyarat**: Sebarang bab penempatan selesai  
**Tempoh**: 1-1.5 jam  
**Kerumitan**: ⭐⭐

#### Apa Yang Akan Anda Pelajari
- Pendekatan pengubahsuaian berstruktur
- Isu dan penyelesaian biasa
- Penyelesaian masalah khusus AI

#### Sumber Pembelajaran
- **🔧 Isu Biasa**: [Isu Biasa](docs/troubleshooting/common-issues.md) - FAQ dan penyelesaian
- **🕵️ Pengubahsuaian**: [Panduan Pengubahsuaian](docs/troubleshooting/debugging.md) - Strategi langkah demi langkah
- **🤖 Isu AI**: [Penyelesaian Masalah Khusus AI](docs/troubleshooting/ai-troubleshooting.md) - Masalah perkhidmatan AI

#### Latihan Praktikal
- Mendiagnosis kegagalan penempatan
- Menyelesaikan masalah pengesahan
- Mengubah suai sambungan perkhidmatan AI

**💡 Hasil Bab**: Mendiagnosis dan menyelesaikan isu penempatan biasa secara berdikari

---

### 🏢 Bab 8: Corak Produksi & Perusahaan
**Prasyarat**: Bab 1-4 selesai  
**Tempoh**: 2-3 jam  
**Kerumitan**: ⭐⭐⭐⭐

#### Apa Yang Akan Anda Pelajari
- Strategi penempatan produksi
- Corak keselamatan perusahaan
- Pemantauan dan pengoptimuman kos

#### Sumber Pembelajaran
- **🏭 Produksi**: [Amalan Terbaik AI Produksi](docs/microsoft-foundry/production-ai-practices.md) - Corak perusahaan
- **📝 Contoh**: [Contoh Mikroservis](../../examples/microservices) - Seni bina kompleks
- **📊 Pemantauan**: [Integrasi Application Insights](docs/pre-deployment/application-insights.md) - Pemantauan

#### Latihan Praktikal
- Laksanakan corak keselamatan perusahaan
- Sediakan pemantauan komprehensif
- Tempatkan ke produksi dengan tadbir urus yang betul

**💡 Hasil Bab**: Menempatkan aplikasi sedia perusahaan dengan keupayaan produksi penuh

---

## 🎓 Gambaran Keseluruhan Bengkel: Pengalaman Pembelajaran Hands-On

> **⚠️ STATUS BENGKEL: Pembangunan Aktif**  
> Bahan bengkel sedang dibangunkan dan diperhalusi. Modul teras berfungsi, tetapi beberapa bahagian lanjutan belum lengkap. Kami sedang berusaha keras untuk menyiapkan semua kandungan. [Jejaki kemajuan →](workshop/README.md)

### Bahan Bengkel Interaktif
**Pembelajaran hands-on menyeluruh dengan alat berasaskan pelayar dan latihan terarah**

Bahan bengkel kami menyediakan pengalaman pembelajaran interaktif yang tersusun dan melengkapi kurikulum berasaskan bab di atas. Bengkel ini direka untuk pembelajaran kendiri dan sesi dikendalikan pengajar.

#### 🛠️ Ciri-ciri Bengkel
- **Antara Muka Berasaskan Pelayar**: Bengkel lengkap berkuasa MkDocs dengan ciri carian, salin, dan tema
- **Integrasi GitHub Codespaces**: Satu klik untuk setup persekitaran pembangunan
- **Laluan Pembelajaran Berstruktur**: 7 langkah latihan terarah (3.5 jam keseluruhan)
- **Penemuan → Penempatan → Penyesuaian**: Metodologi progresif
- **Persekitaran DevContainer Interaktif**: Alat dan pergantungan telah dikonfigurasi terlebih dahulu

#### 📚 Struktur Bengkel
Bengkel mengikuti metodologi **Penemuan → Penempatan → Penyesuaian**:

1. **Fasa Penemuan** (45 minit)
   - Teroka templat dan perkhidmatan Microsoft Foundry
   - Fahami corak seni bina berbilang ejen
   - Semak keperluan penempatan dan prasyarat

2. **Fasa Penempatan** (2 jam)
   - Penempatan hands-on aplikasi AI dengan AZD
   - Konfigurasi perkhidmatan dan titik akhir Azure AI
   - Laksanakan corak keselamatan dan pengesahan

3. **Fasa Penyesuaian** (45 minit)
   - Ubah suai aplikasi untuk kes penggunaan tertentu
   - Optimumkan untuk penempatan produksi
   - Laksanakan pemantauan dan pengurusan kos

#### 🚀 Memulakan Bengkel
```bash
# Pilihan 1: GitHub Codespaces (Disyorkan)
# Klik "Code" → "Create codespace on main" dalam repositori

# Pilihan 2: Pembangunan Tempatan
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# Ikuti arahan penyediaan dalam workshop/README.md
```

#### 🎯 Hasil Pembelajaran Bengkel
Dengan menamatkan bengkel, peserta akan:
- **Menempatkan Aplikasi AI Produksi**: Gunakan AZD dengan perkhidmatan Microsoft Foundry
- **Menguasai Seni Bina Berbilang Ejen**: Laksanakan penyelesaian AI ejen terkoordinasi
- **Melaksanakan Amalan Keselamatan Terbaik**: Konfigurasi pengesahan dan kawalan capaian
- **Mengoptimumkan untuk Skala**: Reka bentuk penempatan kos efektif dan berprestasi
- **Menyelesaikan Masalah Penempatan**: Selesaikan isu biasa secara berdikari

#### 📖 Sumber Bengkel
- **🎥 Panduan Interaktif**: [Bahan Bengkel](workshop/README.md) - Persekitaran pembelajaran berasaskan pelayar
- **📋 Arahan Langkah demi Langkah**: [Latihan Terarah](../../workshop/docs/instructions) - Panduan terperinci
- **🛠️ Makmal Bengkel AI**: [Makmal Bengkel AI](docs/microsoft-foundry/ai-workshop-lab.md) - Latihan berfokus AI
- **💡 Mula Pantas**: [Panduan Setup Bengkel](workshop/README.md#quick-start) - Konfigurasi persekitaran

**Sesuai untuk**: Latihan korporat, kursus universiti, pembelajaran kendiri, dan kem bootcamp pembangun.

---

## 📖 Apa Itu Azure Developer CLI?

Azure Developer CLI (azd) adalah antara muka baris perintah berfokus pembangun yang mempercepatkan proses membina dan menempatkan aplikasi ke Azure. Ia menyediakan:

- **Penempatan berasaskan templat** - Gunakan templat pra-bina untuk corak aplikasi biasa
- **Infrastruktur sebagai Kod** - Urus sumber Azure menggunakan Bicep atau Terraform  
- **Aliran kerja bersepadu** - Penyediaan, penempatan, dan pemantauan aplikasi tanpa gangguan
- **Mesra pembangun** - Dioptimumkan untuk produktiviti dan pengalaman pembangun

### **AZD + Microsoft Foundry: Sesuai untuk Penempatan AI**

**Mengapa AZD untuk Penyelesaian AI?** AZD menangani cabaran utama yang dihadapi oleh pembangun AI:

- **Templat Sedia AI** - Templat yang telah dikonfigurasikan untuk Azure OpenAI, Perkhidmatan Kognitif, dan beban kerja ML
- **Penempatan AI Selamat** - Corak keselamatan terbina dalam untuk perkhidmatan AI, kekunci API, dan titik akhir model  
- **Corak AI Produksi** - Amalan terbaik untuk penempatan aplikasi AI yang boleh diskalakan dan kos efektif
- **Aliran Kerja AI Sepenuhnya** - Dari pembangunan model ke penempatan produksi dengan pemantauan yang betul
- **Pengoptimuman Kos** - Strategi agihan sumber dan penyesuaian pintar untuk beban kerja AI
- **Integrasi Microsoft Foundry** - Sambungan lancar ke katalog model dan titik akhir Microsoft Foundry

---

## 🎯 Pustaka Templat & Contoh

### Pilihan: Templat Microsoft Foundry
**Mulakan di sini jika anda menempatkan aplikasi AI!**

> **Nota:** Templat ini memaparkan pelbagai corak AI. Sesetengahnya ialah Contoh Azure luaran, yang lain pelaksanaan tempatan.

| Templat | Bab | Kerumitan | Perkhidmatan | Jenis |
|----------|---------|------------|----------|------|
| [**Mulakan dengan sembang AI**](https://github.com/Azure-Samples/get-started-with-ai-chat) | Bab 2 | ⭐⭐ | AzureOpenAI + API Inferens Model Azure AI + Azure AI Search + Azure Container Apps + Application Insights | Luaran |
| [**Mulakan dengan ejen AI**](https://github.com/Azure-Samples/get-started-with-ai-agents) | Bab 2 | ⭐⭐ | Azure AI Agent Service + AzureOpenAI + Azure AI Search + Azure Container Apps + Application Insights| Luaran |
| [**Demo Azure Search + OpenAI**](https://github.com/Azure-Samples/azure-search-openai-demo) | Bab 2 | ⭐⭐ | AzureOpenAI + Azure AI Search + App Service + Storage | Luaran |
| [**Mula Pantas Aplikasi Sembang OpenAI**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Bab 2 | ⭐ | AzureOpenAI + Container Apps + Application Insights | Luaran |
| [**Agent OpenAI Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Bab 5 | ⭐⭐⭐ | AzureOpenAI + Azure Functions + Prompty | Luaran |
| [**Contoso Chat RAG**](https://github.com/Azure-Samples/contoso-chat) | Bab 8 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Cosmos DB + Container Apps | Luaran |
| [**Penyelesaian Berbilang Ejen Runcit**](examples/retail-scenario.md) | Bab 5 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Storage + Container Apps + Cosmos DB | **Tempatan** |

### Pilihan: Senario Pembelajaran Lengkap
**Templat aplikasi sedia produksi dipetakan kepada bab pembelajaran**

| Templat | Bab Pembelajaran | Kerumitan | Pembelajaran Utama |
|----------|------------------|------------|--------------|
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Bab 2 | ⭐ | Corak penempatan AI asas |
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Bab 2 | ⭐⭐ | Pelaksanaan RAG dengan Azure AI Search |
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | Bab 4 | ⭐⭐ | Integrasi Kecerdasan Dokumen |
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Bab 5 | ⭐⭐⭐ | Rangka kerja ejen dan panggilan fungsi |
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | Bab 8 | ⭐⭐⭐ | Orkestrasi AI perusahaan |
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | Bab 5 | ⭐⭐⭐⭐ | Seni bina berbilang ejen dengan ejen Pelanggan dan Inventori |

### Pembelajaran Mengikut Jenis Contoh

> **📌 Contoh Tempatan vs. Luaran:**  
> **Contoh Tempatan** (dalam repo ini) = Sedia digunakan segera  
> **Contoh Luaran** (Contoh Azure) = Klon dari repositori berkaitan

#### Contoh Tempatan (Sedia Digunakan)
- [**Penyelesaian Berbilang Ejen Runcit**](examples/retail-scenario.md) - Pelaksanaan lengkap sedia produksi dengan templat ARM
  - Seni bina berbilang ejen (Ejen Pelanggan + Inventori)
  - Pemantauan dan penilaian menyeluruh
  - Penempatan satu klik melalui templat ARM

#### Contoh Tempatan - Aplikasi Kontena (Bab 2-5)
**Contoh penempatan kontena lengkap dalam repositori ini:**
- [**Contoh Aplikasi Kontena**](examples/container-app/README.md) - Panduan lengkap penempatan berasaskan kontena
  - [API Flask Mudah](../../examples/container-app/simple-flask-api) - API REST asas dengan skala ke sifar
  - [Seni Bina Mikroservis](../../examples/container-app/microservices) - Penempatan multi-perkhidmatan sedia produksi
  - Corak Mula Pantas, Produksi, dan Lanjutan
  - Panduan pemantauan, keselamatan, dan pengoptimuman kos

#### Contoh Luaran - Aplikasi Mudah (Bab 1-2)
**Klon repositori Contoh Azure ini untuk bermula:**
- [Aplikasi Web Mudah - Node.js + MongoDB](https://github.com/Azure-Samples/todo-nodejs-mongo) - Corak penempatan asas
- [Laman Web Statik - React SPA](https://github.com/Azure-Samples/todo-csharp-sql-swa-func) - Penempatan kandungan statik
- [Aplikasi Kontena - Python Flask](https://github.com/Azure-Samples/container-apps-store-api-microservice) - Penempatan API REST

#### Contoh Luaran - Integrasi Pangkalan Data (Bab 3-4)  
- [Aplikasi Pangkalan Data - C# + SQL](https://github.com/Azure-Samples/todo-csharp-sql) - Corak sambungan pangkalan data
- [Fungsi + Cosmos DB](https://github.com/Azure-Samples/todo-python-mongo-swa-func) - Aliran kerja data tanpa pelayan

#### Contoh Luaran - Corak Lanjutan (Bab 4-8)
- [Mikroservis Java](https://github.com/Azure-Samples/java-microservices-aca-lab) - Seni bina multi-perkhidmatan
- [Kerja Aplikasi Kontena](https://github.com/Azure-Samples/container-apps-jobs) - Pemprosesan latar belakang  
- [Saluran ML Perusahaan](https://github.com/Azure-Samples/mlops-v2) - Corak ML sedia produksi

### Koleksi Templat Luaran
- [**Galeri Templat Rasmi AZD**](https://azure.github.io/awesome-azd/) - Koleksi templat rasmi dan komuniti yang disusun
- [**Templat Azure Developer CLI**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - Dokumentasi templat Microsoft Learn
- [**Direktori Contoh**](examples/README.md) - Contoh pembelajaran tempatan dengan penjelasan terperinci

---

## 📚 Sumber Pembelajaran & Rujukan

### Rujukan Pantas
- [**Lembaran Petua Perintah**](resources/cheat-sheet.md) - Perintah azd penting yang disusun mengikut bab
- [**Glosari**](resources/glossary.md) - Istilah Azure dan azd  
- [**Soalan Lazim**](resources/faq.md) - Soalan biasa yang disusun mengikut bab pembelajaran
- [**Panduan Kajian**](resources/study-guide.md) - Latihan praktikal menyeluruh

### Bengkel Hands-On
- [**Makmal Bengkel AI**](docs/microsoft-foundry/ai-workshop-lab.md) - Jadikan penyelesaian AI anda boleh dideploy dengan AZD (2-3 jam)
- [**Panduan Bengkel Interaktif**](workshop/README.md) - Bengkel berasaskan pelayar dengan MkDocs dan Persekitaran DevContainer
- [**Laluan Pembelajaran Berstruktur**](../../workshop/docs/instructions) - Latihan berpandu 7 langkah (Penemuan → Penempatan → Penyesuaian)
- [**Bengkel AZD Untuk Pemula**](workshop/README.md) - Bahan bengkel praktikal lengkap dengan integrasi GitHub Codespaces

### Sumber Pembelajaran Luar
- [Dokumentasi Azure Developer CLI](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)
- [Pusat Seni Bina Azure](https://learn.microsoft.com/en-us/azure/architecture/)
- [Kalkulator Harga Azure](https://azure.microsoft.com/pricing/calculator/)
- [Status Azure](https://status.azure.com/)

---

## 🔧 Panduan Penyelesaian Masalah Pantas

**Isu biasa yang dihadapi pemula dan penyelesaian segera:**

### ❌ "azd: command not found"

```bash
# Pasang AZD terlebih dahulu
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Sahkan pemasangan
azd version
```

### ❌ "No subscription found" atau "Subscription not set"

```bash
# Senaraikan langganan yang tersedia
az account list --output table

# Tetapkan langganan lalai
az account set --subscription "<subscription-id-or-name>"

# Tetapkan untuk persekitaran AZD
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Sahkan
az account show
```

### ❌ "InsufficientQuota" atau "Quota exceeded"

```bash
# Cuba wilayah Azure yang berbeza
azd env set AZURE_LOCATION "westus2"
azd up

# Atau gunakan SKU yang lebih kecil dalam pembangunan
# Edit infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```

### ❌ "azd up" gagal separuh jalan

```bash
# Pilihan 1: Bersihkan dan cuba semula
azd down --force --purge
azd up

# Pilihan 2: Betulkan hanya infrastruktur
azd provision

# Pilihan 3: Semak log terperinci
azd show
azd logs
```

### ❌ "Authentication failed" atau "Token expired"

```bash
# Sahkan semula
az logout
az login

azd auth logout
azd auth login

# Sahkan pengesahan
az account show
```

### ❌ "Resource already exists" atau konflik penamaan

```bash
# AZD menjana nama unik, tetapi jika berlaku konflik:
azd down --force --purge

# Kemudian cuba semula dengan persekitaran baru
azd env new dev-v2
azd up
```

### ❌ Penempatan templat mengambil masa terlalu lama

**Masa menunggu biasa:**
- Aplikasi web mudah: 5-10 minit
- Aplikasi dengan pangkalan data: 10-15 minit
- Aplikasi AI: 15-25 minit (penyediaan OpenAI lambat)

```bash
# Semak kemajuan
azd show

# Jika tersekat >30 minit, semak Portal Azure:
azd monitor
# Cari penempatan yang gagal
```

### ❌ "Permission denied" atau "Forbidden"

```bash
# Semak peranan Azure anda
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Anda memerlukan sekurang-kurangnya peranan "Contributor"
# Minta pentadbir Azure anda untuk memberi kebenaran:
# - Contributor (untuk sumber)
# - User Access Administrator (untuk penugasan peranan)
```

### ❌ Tidak dapat mencari URL aplikasi yang telah dideploy

```bash
# Papar semua titik akhir perkhidmatan
azd show

# Atau buka Portal Azure
azd monitor

# Semak perkhidmatan tertentu
azd env get-values
# Cari pembolehubah *_URL
```

### 📚 Sumber Penyelesaian Masalah Lengkap

- **Panduan Isu Biasa:** [Penyelesaian Terperinci](docs/troubleshooting/common-issues.md)
- **Isu Spesifik AI:** [Penyelesaian Masalah AI](docs/troubleshooting/ai-troubleshooting.md)
- **Panduan Debugging:** [Debugging langkah demi langkah](docs/troubleshooting/debugging.md)
- **Dapatkan Bantuan:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🔧 Panduan Penyelesaian Masalah Pantas

**Isu biasa yang dihadapi pemula dan penyelesaian segera:**

<details>
<summary><strong>❌ "azd: command not found"</strong></summary>

```bash
# Pasang AZD dahulu
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Sahkan pemasangan
azd version
```
</details>

<details>
<summary><strong>❌ "No subscription found" atau "Subscription not set"</strong></summary>

```bash
# Senaraikan langganan yang tersedia
az account list --output table

# Tetapkan langganan lalai
az account set --subscription "<subscription-id-or-name>"

# Tetapkan untuk persekitaran AZD
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Sahkan
az account show
```
</details>

<details>
<summary><strong>❌ "InsufficientQuota" atau "Quota exceeded"</strong></summary>

```bash
# Cuba rantau Azure yang berbeza
azd env set AZURE_LOCATION "westus2"
azd up

# Atau guna SKU yang lebih kecil dalam pembangunan
# Sunting infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>

<details>
<summary><strong>❌ "azd up" gagal separuh jalan</strong></summary>

```bash
# Pilihan 1: Bersihkan dan cuba semula
azd down --force --purge
azd up

# Pilihan 2: Betulkan infrastruktur sahaja
azd provision

# Pilihan 3: Semak log terperinci
azd show
azd logs
```
</details>

<details>
<summary><strong>❌ "Authentication failed" atau "Token expired"</strong></summary>

```bash
# Sahkan semula
az logout
az login

azd auth logout
azd auth login

# Sahkan pengesahan
az account show
```
</details>

<details>
<summary><strong>❌ "Resource already exists" atau konflik penamaan</strong></summary>

```bash
# AZD menghasilkan nama unik, tetapi jika berlaku konflik:
azd down --force --purge

# Kemudian cuba semula dengan persekitaran baru
azd env new dev-v2
azd up
```
</details>

<details>
<summary><strong>❌ Penempatan templat mengambil masa terlalu lama</strong></summary>

**Masa menunggu biasa:**
- Aplikasi web mudah: 5-10 minit
- Aplikasi dengan pangkalan data: 10-15 minit
- Aplikasi AI: 15-25 minit (penyediaan OpenAI lambat)

```bash
# Semak kemajuan
azd show

# Jika tersekat >30 minit, semak Portal Azure:
azd monitor
# Cari penyebaran yang gagal
```
</details>

<details>
<summary><strong>❌ "Permission denied" atau "Forbidden"</strong></summary>

```bash
# Semak peranan Azure anda
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Anda memerlukan sekurang-kurangnya peranan "Penolong"
# Minta pentadbir Azure anda untuk memberi:
# - Penolong (untuk sumber)
# - Pentadbir Akses Pengguna (untuk tugasan peranan)
```
</details>

<details>
<summary><strong>❌ Tidak dapat mencari URL aplikasi yang telah dideploy</strong></summary>

```bash
# Tunjukkan semua titik akhir perkhidmatan
azd show

# Atau buka Portal Azure
azd monitor

# Semak perkhidmatan tertentu
azd env get-values
# Cari pemboleh ubah *_URL
```
</details>

### 📚 Sumber Penyelesaian Masalah Lengkap

- **Panduan Isu Biasa:** [Penyelesaian Terperinci](docs/troubleshooting/common-issues.md)
- **Isu Spesifik AI:** [Penyelesaian Masalah AI](docs/troubleshooting/ai-troubleshooting.md)
- **Panduan Debugging:** [Debugging langkah demi langkah](docs/troubleshooting/debugging.md)
- **Dapatkan Bantuan:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🎓 Penyelesaian Kursus & Pensijilan

### Penjejakan Kemajuan
Jejaki kemajuan pembelajaran anda melalui setiap bab:

- [ ] **Bab 1**: Asas & Permulaan Pantas ✅
- [ ] **Bab 2**: Pembangunan AI-Pertama ✅  
- [ ] **Bab 3**: Konfigurasi & Pengesahan ✅
- [ ] **Bab 4**: Infrastruktur sebagai Kod & Penempatan ✅
- [ ] **Bab 5**: Penyelesaian AI Berbilang Ejen ✅
- [ ] **Bab 6**: Pengesahan Pra-Penempatan & Perancangan ✅
- [ ] **Bab 7**: Penyelesaian Masalah & Debugging ✅
- [ ] **Bab 8**: Corak Pengeluaran & Perusahaan ✅

### Pengesahan Pembelajaran
Selepas menamatkan setiap bab, sahkan pengetahuan anda dengan:
1. **Latihan Praktikal**: Lengkapkan penempatan praktikal bab tersebut
2. **Semakan Pengetahuan**: Tinjau bahagian FAQ untuk bab anda
3. **Perbincangan Komuniti**: Kongsi pengalaman anda dalam Azure Discord
4. **Bab Seterusnya**: Beralih ke tahap kerumitan seterusnya

### Manfaat Penyelesaian Kursus
Setelah menamatkan semua bab, anda akan mempunyai:
- **Pengalaman Pengeluaran**: Telah menempatkan aplikasi AI sebenar ke Azure
- **Kemahiran Profesional**: Kebolehan penempatan bersedia perusahaan  
- **Pengiktirafan Komuniti**: Ahli aktif komuniti pembangun Azure
- **Kemajuan Kerjaya**: Kepakaran AZD dan AI yang tinggi permintaan

---

## 🤝 Komuniti & Sokongan

### Dapatkan Bantuan & Sokongan
- **Isu Teknikal:** [Lapor pepijat dan minta ciri](https://github.com/microsoft/azd-for-beginners/issues)
- **Soalan Pembelajaran:** [Komuniti Discord Microsoft Azure](https://discord.gg/microsoft-azure) dan [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **Bantuan Khusus AI:** Sertai [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **Dokumentasi:** [Dokumentasi Azure Developer CLI rasmi](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)

### Wawasan Komuniti dari Microsoft Foundry Discord

**Keputusan Tinjauan Terkini dari Saluran #Azure:**
- **45%** pembangun ingin menggunakan AZD untuk beban kerja AI
- **Cabaran utama**: Penempatan pelbagai perkhidmatan, pengurusan kelayakan, kesediaan pengeluaran  
- **Permintaan terbanyak**: Templat khusus AI, panduan penyelesaian masalah, amalan terbaik

**Sertai komuniti kami untuk:**
- Kongsi pengalaman AZD + AI dan dapatkan bantuan
- Akses pratonton awal templat AI baru
- Menyumbang kepada amalan terbaik penempatan AI
- Mempengaruhi pembangunan ciri AI + AZD masa depan

### Menyumbang kepada Kursus
Kami mengalu-alukan sumbangan! Sila baca [Panduan Menyumbang](CONTRIBUTING.md) kami untuk maklumat lanjut mengenai:
- **Penambahbaikan Kandungan**: Memperbaiki bab dan contoh sedia ada
- **Contoh Baru**: Tambah senario dan templat dunia sebenar  
- **Terjemahan**: Bantu mengekalkan sokongan pelbagai bahasa
- **Laporan Pepijat**: Tingkatkan ketepatan dan kejelasan
- **Standard Komuniti**: Ikuti garis panduan komuniti inklusif kami

---

## 📄 Maklumat Kursus

### Lesen
Projek ini dilesenkan di bawah Lesen MIT - lihat fail [LICENSE](../../LICENSE) untuk butiran.

### Sumber Pembelajaran Berkaitan Microsoft

Pasukan kami menghasilkan kursus pembelajaran komprehensif lain:

<!-- CO-OP TRANSLATOR OTHER COURSES START -->
### LangChain
[![LangChain4j for Beginners](https://img.shields.io/badge/LangChain4j%20for%20Beginners-22C55E?style=for-the-badge&&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchain4j-for-beginners)
[![LangChain.js for Beginners](https://img.shields.io/badge/LangChain.js%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchainjs-for-beginners?WT.mc_id=m365-94501-dwahlin)

---

### Azure / Edge / MCP / Ejen
[![AZD for Beginners](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Edge AI for Beginners](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![MCP for Beginners](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)
[![AI Agents for Beginners](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Siri AI Generatif
[![Generative AI for Beginners](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Generative AI (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
[![Generative AI (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)
[![Generative AI (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---
 
### Pembelajaran Teras
[![ML for Beginners](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![Sains Data untuk Pemula](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![AI untuk Pemula](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Keselamatan Siber untuk Pemula](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Pembangunan Web untuk Pemula](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![IoT untuk Pemula](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![Pembangunan XR untuk Pemula](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Siri Copilot
[![Copilot untuk Pengaturcaraan Berpasangan AI](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![Copilot untuk C#/.NET](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Pengembaraan Copilot](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ Navigasi Kursus

**🚀 Sedia Untuk Mula Belajar?**

**Pemula**: Mula dengan [Bab 1: Asas & Permulaan Pantas](../..)  
**Pemaju AI**: Teruskan ke [Bab 2: Pembangunan AI-Pertama](../..)  
**Pemaju Berpengalaman**: Mulakan dengan [Bab 3: Konfigurasi & Pengesahan](../..)

**Langkah Seterusnya**: [Mulakan Bab 1 - Asas AZD](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Penafian**:  
Dokumen ini telah diterjemahkan menggunakan perkhidmatan terjemahan AI [Co-op Translator](https://github.com/Azure/co-op-translator). Walaupun kami berusaha untuk memastikan ketepatan, sila maklum bahawa terjemahan automatik mungkin mengandungi kesilapan atau ketidaktepatan. Dokumen asal dalam bahasa asalnya harus dianggap sebagai sumber yang sahih. Untuk maklumat yang penting, terjemahan profesional oleh manusia adalah disyorkan. Kami tidak bertanggungjawab terhadap sebarang salah faham atau salah tafsir yang timbul daripada penggunaan terjemahan ini.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->