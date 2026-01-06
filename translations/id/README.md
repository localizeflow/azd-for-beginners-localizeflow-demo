<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T14:04:14+00:00",
  "source_file": "README.md",
  "language_code": "id"
}
-->
> Catatan: Dokumentasi ini terus diperbarui untuk mencerminkan perubahan terbaru.

> ⚠️ Repositori ini adalah demo yang dibuat untuk menampilkan
> lokalisasi dokumentasi otomatis menggunakan Localizeflow.
>
> Konten asli didasarkan pada
> proyek “AZD for Beginners” dari Microsoft.


# AZD Untuk Pemula: Perjalanan Pembelajaran Terstruktur

![AZD-for-beginners](../../translated_images/azdbeginners.5527441dd9f74068.id.png) 

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## Memulai Dengan Kursus Ini

Ikuti langkah-langkah berikut untuk memulai perjalanan pembelajaran AZD Anda:

1. **Fork Repositori**: Klik [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)
2. **Clone Repositori**: `git clone https://github.com/microsoft/azd-for-beginners.git`
3. **Bergabung dengan Komunitas**: [Komunitas Azure Discord](https://discord.com/invite/ByRwuEEgH4) untuk dukungan ahli
4. **Pilih Jalur Pembelajaran Anda**: Pilih bab di bawah ini yang sesuai dengan tingkat pengalaman Anda

### Dukungan Multi-Bahasa

#### Terjemahan Otomatis (Selalu Terbaru)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](./README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Lebih Suka Clone Secara Lokal?**

> Repositori ini mencakup lebih dari 50 terjemahan bahasa yang secara signifikan meningkatkan ukuran unduhan. Untuk clone tanpa terjemahan, gunakan sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Ini memberikan Anda semua yang diperlukan untuk menyelesaikan kursus dengan unduhan lebih cepat.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## Ikhtisar Kursus

Kuasi Azure Developer CLI (azd) melalui bab terstruktur yang dirancang untuk pembelajaran progresif. **Fokus khusus pada penerapan aplikasi AI dengan integrasi Microsoft Foundry.**

### Mengapa Kursus Ini Penting untuk Pengembang Modern

Berdasarkan wawasan komunitas Microsoft Foundry Discord, **45% pengembang ingin menggunakan AZD untuk beban kerja AI** tetapi menghadapi tantangan dengan:
- Arsitektur AI multi-layanan yang kompleks
- Praktik terbaik penerapan AI di produksi  
- Integrasi dan konfigurasi layanan Azure AI
- Optimasi biaya beban kerja AI
- Pemecahan masalah penerapan AI khusus

### Tujuan Pembelajaran

Dengan menyelesaikan kursus terstruktur ini, Anda akan:
- **Menguasai Dasar-Dasar AZD**: Konsep inti, instalasi, dan konfigurasi
- **Menerapkan Aplikasi AI**: Gunakan AZD dengan layanan Microsoft Foundry
- **Mengimplementasikan Infrastructure as Code**: Kelola sumber daya Azure dengan template Bicep
- **Memecahkan Masalah Penerapan**: Menyelesaikan masalah umum dan debug
- **Optimalkan untuk Produksi**: Keamanan, penskalaan, pemantauan, dan pengelolaan biaya
- **Membangun Solusi Multi-Agen**: Terapkan arsitektur AI kompleks

## 📚 Bab Pembelajaran

*Pilih jalur pembelajaran Anda berdasarkan tingkat pengalaman dan tujuan*

### 🚀 Bab 1: Dasar & Mulai Cepat
**Prasyarat**: Langganan Azure, pengetahuan dasar command line  
**Durasi**: 30-45 menit  
**Kompleksitas**: ⭐

#### Apa yang Akan Anda Pelajari
- Memahami dasar Azure Developer CLI
- Instalasi AZD pada platform Anda
- Penerapan pertama yang berhasil

#### Sumber Pembelajaran
- **🎯 Mulai Di Sini**: [Apa itu Azure Developer CLI?](../..)
- **📖 Teori**: [Dasar-dasar AZD](docs/getting-started/azd-basics.md) - Konsep inti dan terminologi
- **⚙️ Setup**: [Instalasi & Pengaturan](docs/getting-started/installation.md) - Panduan per platform
- **🛠️ Praktik Langsung**: [Proyek Pertama Anda](docs/getting-started/first-project.md) - Tutorial langkah demi langkah
- **📋 Referensi Cepat**: [Daftar Perintah Singkat](resources/cheat-sheet.md)

#### Latihan Praktis
```bash
# Pemeriksaan instalasi cepat
azd version

# Terapkan aplikasi pertama Anda
azd init --template todo-nodejs-mongo
azd up
```

**💡 Hasil Bab**: Berhasil menerapkan aplikasi web sederhana ke Azure menggunakan AZD

**✅ Validasi Keberhasilan:**
```bash
# Setelah menyelesaikan Bab 1, Anda harus dapat:
azd version              # Menampilkan versi yang terpasang
azd init --template todo-nodejs-mongo  # Menginisialisasi proyek
azd up                  # Melakukan deployment ke Azure
azd show                # Menampilkan URL aplikasi yang berjalan
# Aplikasi terbuka di browser dan berfungsi
azd down --force --purge  # Membersihkan sumber daya
```

**📊 Waktu yang Dihabiskan:** 30-45 menit  
**📈 Tingkat Kemampuan Setelah:** Dapat menerapkan aplikasi dasar secara mandiri

**✅ Validasi Keberhasilan:**
```bash
# Setelah menyelesaikan Bab 1, Anda harus bisa:
azd version              # Menampilkan versi yang terpasang
azd init --template todo-nodejs-mongo  # Menginisialisasi proyek
azd up                  # Menyebarkan ke Azure
azd show                # Menampilkan URL aplikasi yang berjalan
# Aplikasi terbuka di browser dan bekerja
azd down --force --purge  # Membersihkan sumber daya
```

**📊 Waktu yang Dihabiskan:** 30-45 menit  
**📈 Tingkat Kemampuan Setelah:** Dapat menerapkan aplikasi dasar secara mandiri

---

### 🤖 Bab 2: Pengembangan AI-First (Direkomendasikan untuk Pengembang AI)
**Prasyarat**: Bab 1 selesai  
**Durasi**: 1-2 jam  
**Kompleksitas**: ⭐⭐

#### Apa yang Akan Anda Pelajari
- Integrasi Microsoft Foundry dengan AZD
- Menerapkan aplikasi bertenaga AI
- Memahami konfigurasi layanan AI

#### Sumber Pembelajaran
- **🎯 Mulai Di Sini**: [Integrasi Microsoft Foundry](docs/microsoft-foundry/microsoft-foundry-integration.md)
- **📖 Pola**: [Penerapan Model AI](docs/microsoft-foundry/ai-model-deployment.md) - Menerapkan dan mengelola model AI
- **🛠️ Workshop**: [Laboratorium Workshop AI](docs/microsoft-foundry/ai-workshop-lab.md) - Membuat solusi AI Anda siap AZD
- **🎥 Panduan Interaktif**: [Materi Workshop](workshop/README.md) - Pembelajaran berbasis browser dengan MkDocs * Lingkungan DevContainer
- **📋 Template**: [Template Microsoft Foundry](../..)
- **📝 Contoh**: [Contoh Penerapan AZD](examples/README.md)

#### Latihan Praktis
```bash
# Terapkan aplikasi AI pertama Anda
azd init --template azure-search-openai-demo
azd up

# Coba template AI tambahan
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```

**💡 Hasil Bab**: Menerapkan dan mengonfigurasi aplikasi chat bertenaga AI dengan kemampuan RAG

**✅ Validasi Keberhasilan:**
```bash
# Setelah Bab 2, Anda harus dapat:
azd init --template azure-search-openai-demo
azd up
# Menguji antarmuka obrolan AI
# Mengajukan pertanyaan dan mendapatkan jawaban bertenaga AI dengan sumber
# Memverifikasi integrasi pencarian berfungsi
azd monitor  # Memeriksa Application Insights menampilkan telemetri
azd down --force --purge
```

**📊 Waktu yang Dihabiskan:** 1-2 jam  
**📈 Tingkat Kemampuan Setelah:** Dapat menerapkan dan mengonfigurasi aplikasi AI siap produksi  
**💰 Kesadaran Biaya:** Memahami biaya pengembangan $80-150/bulan, biaya produksi $300-3500/bulan

#### 💰 Pertimbangan Biaya untuk Penerapan AI

**Lingkungan Pengembangan (Perkiraan $80-150/bulan):**
- Azure OpenAI (Bayar sesuai penggunaan): $0-50/bulan (berdasarkan penggunaan token)
- AI Search (Tingkat dasar): $75/bulan
- Container Apps (Konsumsi): $0-20/bulan
- Penyimpanan (Standar): $1-5/bulan

**Lingkungan Produksi (Perkiraan $300-3,500+/bulan):**
- Azure OpenAI (PTU untuk performa konsisten): $3,000+/bulan ATAU Bayar sesuai penggunaan dengan volume tinggi
- AI Search (Tingkat standar): $250/bulan
- Container Apps (Dedicated): $50-100/bulan
- Application Insights: $5-50/bulan
- Penyimpanan (Premium): $10-50/bulan

**💡 Tips Optimasi Biaya:**
- Gunakan **Tingkat Gratis** Azure OpenAI untuk belajar (termasuk 50.000 token/bulan)
- Jalankan `azd down` untuk melepaskan sumber daya saat tidak aktif mengembangkan
- Mulai dengan tagihan berbasis konsumsi, tingkatkan ke PTU hanya untuk produksi
- Gunakan `azd provision --preview` untuk memperkirakan biaya sebelum penerapan
- Aktifkan auto-scaling: bayar hanya untuk penggunaan aktual

**Pemantauan Biaya:**
```bash
# Periksa estimasi biaya bulanan
azd provision --preview

# Pantau biaya aktual di Azure Portal
az consumption budget list --resource-group <your-rg>
```

---

### ⚙️ Bab 3: Konfigurasi & Otentikasi
**Prasyarat**: Bab 1 selesai  
**Durasi**: 45-60 menit  
**Kompleksitas**: ⭐⭐

#### Apa yang Akan Anda Pelajari
- Konfigurasi dan pengelolaan lingkungan
- Praktik terbaik otentikasi dan keamanan
- Penamaan dan pengorganisasian sumber daya

#### Sumber Pembelajaran
- **📖 Konfigurasi**: [Panduan Konfigurasi](docs/getting-started/configuration.md) - Pengaturan lingkungan
- **🔐 Keamanan**: [Pola Otentikasi dan identitas terkelola](docs/getting-started/authsecurity.md) - Pola otentikasi
- **📝 Contoh**: [Contoh Aplikasi Database](examples/database-app/README.md) - Contoh Database AZD

#### Latihan Praktis
- Konfigurasikan beberapa lingkungan (dev, staging, prod)
- Atur otentikasi identitas terkelola
- Terapkan konfigurasi khusus lingkungan

**💡 Hasil Bab**: Mengelola beberapa lingkungan dengan otentikasi dan keamanan yang tepat

---

### 🏗️ Bab 4: Infrastructure as Code & Penerapan
**Prasyarat**: Bab 1-3 selesai  
**Durasi**: 1-1.5 jam  
**Kompleksitas**: ⭐⭐⭐

#### Apa yang Akan Anda Pelajari
- Pola penerapan lanjutan
- Infrastructure as Code dengan Bicep
- Strategi penyediaan sumber daya

#### Sumber Pembelajaran
- **📖 Penerapan**: [Panduan Penerapan](docs/deployment/deployment-guide.md) - Alur kerja lengkap
- **🏗️ Penyediaan**: [Penyediaan Sumber Daya](docs/deployment/provisioning.md) - Manajemen sumber daya Azure
- **📝 Contoh**: [Contoh Container App](../../examples/container-app) - Penerapan dengan containerisasi

#### Latihan Praktis
- Buat template Bicep kustom
- Terapkan aplikasi multi-layanan
- Terapkan strategi penerapan blue-green

**💡 Hasil Bab**: Menerapkan aplikasi multi-layanan kompleks menggunakan template infrastruktur kustom

---
### 🎯 Bab 5: Solusi AI Multi-Agen (Lanjutan)  
**Prasyarat**: Bab 1-2 selesai  
**Durasi**: 2-3 jam  
**Kompleksitas**: ⭐⭐⭐⭐

#### Apa yang Akan Anda Pelajari
- Pola arsitektur multi-agen  
- Orkestrasi dan koordinasi agen  
- Penyebaran AI siap produksi  

#### Sumber Belajar  
- **🤖 Proyek Unggulan**: [Solusi Multi-Agen Ritel](examples/retail-scenario.md) - Implementasi lengkap  
- **🛠️ Template ARM**: [Paket Template ARM](../../examples/retail-multiagent-arm-template) - Penyebaran sekali klik  
- **📖 Arsitektur**: [Pola koordinasi multi-agen](/docs/pre-deployment/coordination-patterns.md) - Pola  

#### Latihan Praktis  
```bash
# Deploy solusi multi-agen ritel lengkap
cd examples/retail-multiagent-arm-template
./deploy.sh

# Jelajahi konfigurasi agen
az deployment group show --resource-group <rg-name> --name <deployment-name>
```
  
**💡 Hasil Bab**: Menyebarkan dan mengelola solusi AI multi-agen siap produksi dengan agen Customer dan Inventory

---

### 🔍 Bab 6: Validasi & Perencanaan Pra-Penyebaran  
**Prasyarat**: Bab 4 selesai  
**Durasi**: 1 jam  
**Kompleksitas**: ⭐⭐

#### Apa yang Akan Anda Pelajari  
- Perencanaan kapasitas dan validasi sumber daya  
- Strategi pemilihan SKU  
- Pemeriksaan pra-penerbangan dan otomasi  

#### Sumber Belajar  
- **📊 Perencanaan**: [Perencanaan Kapasitas](docs/pre-deployment/capacity-planning.md) - Validasi sumber daya  
- **💰 Pemilihan**: [Pemilihan SKU](docs/pre-deployment/sku-selection.md) - Pilihan biaya efektif  
- **✅ Validasi**: [Pemeriksaan Pra-Penerbangan](docs/pre-deployment/preflight-checks.md) - Skrip otomatis  

#### Latihan Praktis  
- Jalankan skrip validasi kapasitas  
- Optimalkan pilihan SKU untuk biaya  
- Implementasikan pemeriksaan otomatis pra-penyebaran  

**💡 Hasil Bab**: Validasi dan optimalkan penyebaran sebelum eksekusi

---

### 🚨 Bab 7: Pemecahan Masalah & Debugging  
**Prasyarat**: Bab penyebaran apa pun selesai  
**Durasi**: 1-1.5 jam  
**Kompleksitas**: ⭐⭐

#### Apa yang Akan Anda Pelajari  
- Pendekatan debugging sistematis  
- Masalah umum dan solusinya  
- Pemecahan masalah khusus AI  

#### Sumber Belajar  
- **🔧 Masalah Umum**: [Masalah Umum](docs/troubleshooting/common-issues.md) - FAQ dan solusi  
- **🕵️ Debugging**: [Panduan Debugging](docs/troubleshooting/debugging.md) - Strategi langkah demi langkah  
- **🤖 Masalah AI**: [Pemecahan Masalah Khusus AI](docs/troubleshooting/ai-troubleshooting.md) - Masalah layanan AI  

#### Latihan Praktis  
- Diagnosa kegagalan penyebaran  
- Selesaikan masalah autentikasi  
- Debug konektivitas layanan AI  

**💡 Hasil Bab**: Diagnosa mandiri dan selesaikan masalah penyebaran umum

---

### 🏢 Bab 8: Pola Produksi & Enterprise  
**Prasyarat**: Bab 1-4 selesai  
**Durasi**: 2-3 jam  
**Kompleksitas**: ⭐⭐⭐⭐

#### Apa yang Akan Anda Pelajari  
- Strategi penyebaran produksi  
- Pola keamanan enterprise  
- Monitoring dan optimasi biaya  

#### Sumber Belajar  
- **🏭 Produksi**: [Praktik Terbaik AI Produksi](docs/microsoft-foundry/production-ai-practices.md) - Pola enterprise  
- **📝 Contoh**: [Contoh Microservices](../../examples/microservices) - Arsitektur kompleks  
- **📊 Monitoring**: [Integrasi Application Insights](docs/pre-deployment/application-insights.md) - Monitoring  

#### Latihan Praktis  
- Implementasikan pola keamanan enterprise  
- Atur monitoring komprehensif  
- Sebarkan ke produksi dengan tata kelola tepat  

**💡 Hasil Bab**: Menyebarkan aplikasi siap enterprise dengan kapabilitas produksi penuh

---

## 🎓 Ikhtisar Workshop: Pengalaman Pembelajaran Praktis

> **⚠️ STATUS WORKSHOP: Pengembangan Aktif**  
> Materi workshop saat ini sedang dikembangkan dan disempurnakan. Modul inti berfungsi, tapi beberapa bagian lanjutan belum lengkap. Kami aktif bekerja menyelesaikan seluruh konten. [Lacak kemajuan →](workshop/README.md)

### Materi Workshop Interaktif  
**Pembelajaran praktis menyeluruh dengan alat berbasis browser dan latihan terpandu**

Materi workshop kami menyediakan pengalaman pembelajaran terstruktur dan interaktif yang melengkapi kurikulum berbasis bab di atas. Workshop dirancang untuk pembelajaran mandiri maupun sesi bimbingan instruktur.

#### 🛠️ Fitur Workshop  
- **Antarmuka Berbasis Browser**: Workshop lengkap berbasis MkDocs dengan fitur pencarian, salin, dan tema  
- **Integrasi GitHub Codespaces**: Setup lingkungan pengembangan sekali klik  
- **Jalur Pembelajaran Terstruktur**: 7 langkah latihan terpandu (total 3.5 jam)  
- **Metodologi Discovery → Deployment → Customization**  
- **Lingkungan DevContainer Interaktif**: Alat dan dependensi yang sudah dikonfigurasi sebelumnya  

#### 📚 Struktur Workshop  
Workshop mengikuti metodologi **Discovery → Deployment → Customization**:

1. **Fase Discovery** (45 menit)  
   - Menjelajahi template dan layanan Microsoft Foundry  
   - Memahami pola arsitektur multi-agen  
   - Mengulas persyaratan dan prasyarat penyebaran  

2. **Fase Deployment** (2 jam)  
   - Penyebaran aplikasi AI langsung dengan AZD  
   - Konfigurasi layanan dan endpoint Azure AI  
   - Implementasi pola keamanan dan autentikasi  

3. **Fase Customization** (45 menit)  
   - Modifikasi aplikasi untuk kasus penggunaan spesifik  
   - Optimalisasi untuk penyebaran produksi  
   - Implementasi monitoring dan pengelolaan biaya  

#### 🚀 Memulai Workshop  
```bash
# Opsi 1: GitHub Codespaces (Disarankan)
# Klik "Code" → "Create codespace on main" di repositori

# Opsi 2: Pengembangan Lokal
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# Ikuti instruksi setup di workshop/README.md
```
  
#### 🎯 Hasil Pembelajaran Workshop  
Dengan menyelesaikan workshop, peserta akan:  
- **Menyebarkan Aplikasi AI Produksi**: Gunakan AZD dengan layanan Microsoft Foundry  
- **Menguasai Arsitektur Multi-Agen**: Implementasi solusi agen AI terkoordinasi  
- **Menerapkan Praktik Keamanan Terbaik**: Konfigurasi autentikasi dan kontrol akses  
- **Optimalkan untuk Skala**: Rancang penyebaran hemat biaya dan performa  
- **Pemecahan Masalah Penyebaran**: Selesaikan masalah umum secara mandiri  

#### 📖 Sumber Workshop  
- **🎥 Panduan Interaktif**: [Materi Workshop](workshop/README.md) - Lingkungan belajar berbasis browser  
- **📋 Instruksi Langkah-demi-Langkah**: [Latihan Terpandu](../../workshop/docs/instructions) - Panduan detail  
- **🛠️ Lab Workshop AI**: [AI Workshop Lab](docs/microsoft-foundry/ai-workshop-lab.md) - Latihan berfokus AI  
- **💡 Mulai Cepat**: [Panduan Setup Workshop](workshop/README.md#quick-start) - Konfigurasi lingkungan  

**Cocok untuk**: Pelatihan korporat, kursus universitas, pembelajaran mandiri, dan bootcamp pengembang.  

---

## 📖 Apa itu Azure Developer CLI?

Azure Developer CLI (azd) adalah antarmuka baris perintah yang berfokus pada pengembang untuk mempercepat proses membangun dan menyebarkan aplikasi ke Azure. Ini menyediakan:

- **Penyebaran berbasis template** - Gunakan template siap pakai untuk pola aplikasi umum  
- **Infrastruktur sebagai Kode** - Kelola sumber daya Azure menggunakan Bicep atau Terraform  
- **Alur kerja terintegrasi** - Proses provisioning, penyebaran, dan monitoring aplikasi secara mulus  
- **Ramah Pengembang** - Dioptimalkan untuk produktivitas dan pengalaman pengembang  

### **AZD + Microsoft Foundry: Pas untuk Penyebaran AI**

**Mengapa AZD untuk Solusi AI?** AZD menyelesaikan tantangan utama yang dihadapi pengembang AI:

- **Template AI Siap Pakai** - Template pra-konfigurasi untuk Azure OpenAI, Cognitive Services, dan beban kerja ML  
- **Penyebaran AI Aman** - Pola keamanan bawaan untuk layanan AI, kunci API, dan endpoint model  
- **Pola AI Produksi** - Praktik terbaik untuk penyebaran aplikasi AI yang skalabel dan hemat biaya  
- **Alur Kerja AI End-to-End** - Dari pengembangan model hingga penyebaran produksi dengan monitoring yang tepat  
- **Optimalisasi Biaya** - Alokasi sumber daya cerdas dan strategi penskalaan untuk beban kerja AI  
- **Integrasi Microsoft Foundry** - Koneksi mulus ke katalog model dan endpoint Microsoft Foundry  

---

## 🎯 Perpustakaan Template & Contoh

### Unggulan: Template Microsoft Foundry  
**Mulai di sini jika Anda menyebarkan aplikasi AI!**

> **Catatan:** Template ini menampilkan berbagai pola AI. Beberapa adalah Azure Samples eksternal, lainnya implementasi lokal.

| Template | Bab | Kompleksitas | Layanan | Tipe |
|----------|-----|--------------|---------|------|
| [**Get started with AI chat**](https://github.com/Azure-Samples/get-started-with-ai-chat) | Bab 2 | ⭐⭐ | AzureOpenAI + Azure AI Model Inference API + Azure AI Search + Azure Container Apps + Application Insights | Eksternal |
| [**Get started with AI agents**](https://github.com/Azure-Samples/get-started-with-ai-agents) | Bab 2 | ⭐⭐ | Azure AI Agent Service + AzureOpenAI + Azure AI Search + Azure Container Apps + Application Insights| Eksternal |
| [**Azure Search + OpenAI Demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Bab 2 | ⭐⭐ | AzureOpenAI + Azure AI Search + App Service + Storage | Eksternal |
| [**OpenAI Chat App Quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Bab 2 | ⭐ | AzureOpenAI + Container Apps + Application Insights | Eksternal |
| [**Agent OpenAI Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Bab 5 | ⭐⭐⭐ | AzureOpenAI + Azure Functions + Prompty | Eksternal |
| [**Contoso Chat RAG**](https://github.com/Azure-Samples/contoso-chat) | Bab 8 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Cosmos DB + Container Apps | Eksternal |
| [**Retail Multi-Agent Solution**](examples/retail-scenario.md) | Bab 5 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Storage + Container Apps + Cosmos DB | **Lokal** |

### Unggulan: Skenario Pembelajaran Lengkap  
**Template aplikasi siap produksi yang dipetakan ke bab pembelajaran**

| Template | Bab Pembelajaran | Kompleksitas | Pembelajaran Utama |
|----------|------------------|--------------|--------------------|
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Bab 2 | ⭐ | Pola penyebaran AI dasar |
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Bab 2 | ⭐⭐ | Implementasi RAG dengan Azure AI Search |
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | Bab 4 | ⭐⭐ | Integrasi Document Intelligence |
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Bab 5 | ⭐⭐⭐ | Kerangka kerja agen dan pemanggilan fungsi |
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | Bab 8 | ⭐⭐⭐ | Orkestrasi AI enterprise |
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | Bab 5 | ⭐⭐⭐⭐ | Arsitektur multi-agen dengan agen Customer dan Inventory |

### Pembelajaran Berdasarkan Jenis Contoh

> **📌 Contoh Lokal vs. Eksternal:**  
> **Contoh Lokal** (di repo ini) = Siap digunakan langsung  
> **Contoh Eksternal** (Azure Samples) = Clone dari repositori terkait  

#### Contoh Lokal (Siap Pakai)  
- [**Retail Multi-Agent Solution**](examples/retail-scenario.md) - Implementasi lengkap siap produksi dengan template ARM  
  - Arsitektur multi-agen (Customer + Inventory)  
  - Monitoring dan evaluasi komprehensif  
  - Penyebaran sekali klik via template ARM  

#### Contoh Lokal - Aplikasi Container (Bab 2-5)  
**Contoh penyebaran container lengkap dalam repositori ini:**  
- [**Contoh Container App**](examples/container-app/README.md) - Panduan lengkap penyebaran container  
  - [Simple Flask API](../../examples/container-app/simple-flask-api) - API REST dasar dengan scale-to-zero  
  - [Arsitektur Microservices](../../examples/container-app/microservices) - Penyebaran multi-layanan siap produksi  
  - Pola Penyebaran Quick Start, Produksi, dan Lanjutan  
  - Panduan monitoring, keamanan, dan optimasi biaya  

#### Contoh Eksternal - Aplikasi Sederhana (Bab 1-2)  
**Clone repositori Azure Samples berikut untuk memulai:**  
- [Simple Web App - Node.js + MongoDB](https://github.com/Azure-Samples/todo-nodejs-mongo) - Pola penyebaran dasar  
- [Static Website - React SPA](https://github.com/Azure-Samples/todo-csharp-sql-swa-func) - Penyebaran konten statis  
- [Container App - Python Flask](https://github.com/Azure-Samples/container-apps-store-api-microservice) - Penyebaran API REST  

#### Contoh Eksternal - Integrasi Database (Bab 3-4)  
- [Database App - C# + SQL](https://github.com/Azure-Samples/todo-csharp-sql) - Pola konektivitas database  
- [Functions + Cosmos DB](https://github.com/Azure-Samples/todo-python-mongo-swa-func) - Alur data serverless  

#### Contoh Eksternal - Pola Lanjutan (Bab 4-8)  
- [Java Microservices](https://github.com/Azure-Samples/java-microservices-aca-lab) - Arsitektur multi-layanan  
- [Container Apps Jobs](https://github.com/Azure-Samples/container-apps-jobs) - Pemrosesan latar belakang  
- [Enterprise ML Pipeline](https://github.com/Azure-Samples/mlops-v2) - Pola ML siap produksi  

### Koleksi Template Eksternal
- [**Galeri Template Resmi AZD**](https://azure.github.io/awesome-azd/) - Koleksi template resmi dan komunitas yang dikurasi
- [**Template Azure Developer CLI**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - Dokumentasi template Microsoft Learn
- [**Direktori Contoh**](examples/README.md) - Contoh pembelajaran lokal dengan penjelasan rinci

---

## 📚 Sumber Belajar & Referensi

### Referensi Cepat
- [**Daftar Perintah Ringkas**](resources/cheat-sheet.md) - Perintah azd penting yang diorganisasi berdasarkan bab
- [**Glosarium**](resources/glossary.md) - Istilah Azure dan azd  
- [**FAQ**](resources/faq.md) - Pertanyaan umum yang diatur berdasarkan bab pembelajaran
- [**Panduan Studi**](resources/study-guide.md) - Latihan praktek yang komprehensif

### Workshop Praktis
- [**Laboratorium Workshop AI**](docs/microsoft-foundry/ai-workshop-lab.md) - Membuat solusi AI Anda dapat dideploy dengan AZD (2-3 jam)
- [**Panduan Workshop Interaktif**](workshop/README.md) - Workshop berbasis browser dengan MkDocs dan Lingkungan DevContainer
- [**Jalur Pembelajaran Terstruktur**](../../workshop/docs/instructions) - Latihan panduan 7 langkah (Penemuan → Deployment → Kustomisasi)
- [**Workshop AZD Untuk Pemula**](workshop/README.md) - Materi workshop praktis lengkap dengan integrasi GitHub Codespaces

### Sumber Belajar Eksternal
- Dokumentasi Azure Developer CLI (https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)
- Pusat Arsitektur Azure (https://learn.microsoft.com/en-us/azure/architecture/)
- Kalkulator Harga Azure (https://azure.microsoft.com/pricing/calculator/)
- Status Azure (https://status.azure.com/)

---

## 🔧 Panduan Pemecahan Masalah Cepat

**Masalah umum yang dihadapi pemula dan solusi segera:**

### ❌ "azd: command not found"

```bash
# Instal AZD terlebih dahulu
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Verifikasi instalasi
azd version
```

### ❌ "Tidak ditemukan langganan" atau "Langganan tidak disetel"

```bash
# Daftar langganan yang tersedia
az account list --output table

# Atur langganan default
az account set --subscription "<subscription-id-or-name>"

# Atur untuk lingkungan AZD
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Verifikasi
az account show
```

### ❌ "InsufficientQuota" atau "Kuota terlampaui"

```bash
# Coba wilayah Azure yang berbeda
azd env set AZURE_LOCATION "westus2"
azd up

# Atau gunakan SKU yang lebih kecil dalam pengembangan
# Edit infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```

### ❌ "azd up" gagal di tengah jalan

```bash
# Opsi 1: Bersihkan dan coba lagi
azd down --force --purge
azd up

# Opsi 2: Perbaiki infrastruktur saja
azd provision

# Opsi 3: Periksa log rinci
azd show
azd logs
```

### ❌ "Otentikasi gagal" atau "Token kedaluwarsa"

```bash
# Autentikasi ulang
az logout
az login

azd auth logout
azd auth login

# Verifikasi otentikasi
az account show
```

### ❌ "Sumber daya sudah ada" atau konflik penamaan

```bash
# AZD menghasilkan nama unik, tetapi jika ada konflik:
azd down --force --purge

# Kemudian coba lagi dengan lingkungan baru
azd env new dev-v2
azd up
```

### ❌ Deployment template memakan waktu terlalu lama

**Perkiraan waktu tunggu normal:**
- Aplikasi web sederhana: 5-10 menit
- Aplikasi dengan basis data: 10-15 menit
- Aplikasi AI: 15-25 menit (Provisioning OpenAI lambat)

```bash
# Periksa kemajuan
azd show

# Jika terjebak >30 menit, periksa Portal Azure:
azd monitor
# Cari deployment yang gagal
```

### ❌ "Izin ditolak" atau "Terlarang"

```bash
# Periksa peran Azure Anda
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Anda memerlukan setidaknya peran "Kontributor"
# Minta admin Azure Anda untuk memberikan:
# - Kontributor (untuk sumber daya)
# - Administrator Akses Pengguna (untuk penugasan peran)
```

### ❌ Tidak dapat menemukan URL aplikasi yang dideploy

```bash
# Tampilkan semua endpoint layanan
azd show

# Atau buka Azure Portal
azd monitor

# Periksa layanan tertentu
azd env get-values
# Cari variabel *_URL
```

### 📚 Sumber Pemecahan Masalah Lengkap

- **Panduan Masalah Umum:** [Solusi Terperinci](docs/troubleshooting/common-issues.md)
- **Masalah Khusus AI:** [Pemecahan Masalah AI](docs/troubleshooting/ai-troubleshooting.md)
- **Panduan Debugging:** [Debugging Langkah-demi-Langkah](docs/troubleshooting/debugging.md)
- **Dapatkan Bantuan:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🔧 Panduan Pemecahan Masalah Cepat

**Masalah umum yang dihadapi pemula dan solusi segera:**

<details>
<summary><strong>❌ "azd: command not found"</strong></summary>

```bash
# Pasang AZD terlebih dahulu
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Verifikasi pemasangan
azd version
```
</details>

<details>
<summary><strong>❌ "Tidak ditemukan langganan" atau "Langganan tidak disetel"</strong></summary>

```bash
# Daftar langganan yang tersedia
az account list --output table

# Atur langganan default
az account set --subscription "<subscription-id-or-name>"

# Atur untuk lingkungan AZD
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Verifikasi
az account show
```
</details>

<details>
<summary><strong>❌ "InsufficientQuota" atau "Kuota terlampaui"</strong></summary>

```bash
# Coba wilayah Azure yang berbeda
azd env set AZURE_LOCATION "westus2"
azd up

# Atau gunakan SKU yang lebih kecil dalam pengembangan
# Edit infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>

<details>
<summary><strong>❌ "azd up" gagal di tengah jalan</strong></summary>

```bash
# Pilihan 1: Bersihkan dan coba lagi
azd down --force --purge
azd up

# Pilihan 2: Perbaiki infrastruktur saja
azd provision

# Pilihan 3: Periksa log secara rinci
azd show
azd logs
```
</details>

<details>
<summary><strong>❌ "Otentikasi gagal" atau "Token kedaluwarsa"</strong></summary>

```bash
# Autentikasi ulang
az logout
az login

azd auth logout
azd auth login

# Verifikasi autentikasi
az account show
```
</details>

<details>
<summary><strong>❌ "Sumber daya sudah ada" atau konflik penamaan</strong></summary>

```bash
# AZD menghasilkan nama unik, tetapi jika terjadi konflik:
azd down --force --purge

# Kemudian coba lagi dengan lingkungan baru
azd env new dev-v2
azd up
```
</details>

<details>
<summary><strong>❌ Deployment template memakan waktu terlalu lama</strong></summary>

**Perkiraan waktu tunggu normal:**
- Aplikasi web sederhana: 5-10 menit
- Aplikasi dengan basis data: 10-15 menit
- Aplikasi AI: 15-25 menit (Provisioning OpenAI lambat)

```bash
# Periksa kemajuan
azd show

# Jika terhenti >30 menit, periksa Azure Portal:
azd monitor
# Cari penyebaran yang gagal
```
</details>

<details>
<summary><strong>❌ "Izin ditolak" atau "Terlarang"</strong></summary>

```bash
# Periksa peran Azure Anda
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Anda memerlukan setidaknya peran "Contributor"
# Minta admin Azure Anda untuk memberikan:
# - Contributor (untuk sumber daya)
# - User Access Administrator (untuk penugasan peran)
```
</details>

<details>
<summary><strong>❌ Tidak dapat menemukan URL aplikasi yang dideploy</strong></summary>

```bash
# Tampilkan semua titik akhir layanan
azd show

# Atau buka Portal Azure
azd monitor

# Periksa layanan tertentu
azd env get-values
# Cari variabel *_URL
```
</details>

### 📚 Sumber Pemecahan Masalah Lengkap

- **Panduan Masalah Umum:** [Solusi Terperinci](docs/troubleshooting/common-issues.md)
- **Masalah Khusus AI:** [Pemecahan Masalah AI](docs/troubleshooting/ai-troubleshooting.md)
- **Panduan Debugging:** [Debugging Langkah-demi-Langkah](docs/troubleshooting/debugging.md)
- **Dapatkan Bantuan:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🎓 Penyelesaian Kursus & Sertifikasi

### Pelacakan Kemajuan
Lacak kemajuan pembelajaran Anda di setiap bab:

- [ ] **Bab 1**: Dasar & Mulai Cepat ✅
- [ ] **Bab 2**: Pengembangan Berbasis AI Pertama ✅  
- [ ] **Bab 3**: Konfigurasi & Otentikasi ✅
- [ ] **Bab 4**: Infrastruktur sebagai Kode & Deployment ✅
- [ ] **Bab 5**: Solusi AI Multi-Agen ✅
- [ ] **Bab 6**: Validasi & Perencanaan Pra-Deployment ✅
- [ ] **Bab 7**: Pemecahan Masalah & Debugging ✅
- [ ] **Bab 8**: Pola Produksi & Enterprise ✅

### Verifikasi Pembelajaran
Setelah menyelesaikan setiap bab, verifikasi pengetahuan Anda dengan:
1. **Latihan Praktis**: Selesaikan deployment praktis bab tersebut
2. **Cek Pengetahuan**: Tinjau bagian FAQ untuk bab Anda
3. **Diskusi Komunitas**: Bagikan pengalaman Anda di Azure Discord
4. **Bab Selanjutnya**: Lanjutkan ke tingkat kompleksitas berikutnya

### Manfaat Penyelesaian Kursus
Setelah menyelesaikan semua bab, Anda akan memiliki:
- **Pengalaman Produksi**: Mendeploy aplikasi AI nyata ke Azure
- **Keterampilan Profesional**: Kemampuan deployment siap enterprise  
- **Pengakuan Komunitas**: Anggota aktif komunitas pengembang Azure
- **Pengembangan Karir**: Keahlian AZD dan deployment AI yang diminati

---

## 🤝 Komunitas & Dukungan

### Dapatkan Bantuan & Dukungan
- **Masalah Teknis**: [Laporkan bug dan minta fitur](https://github.com/microsoft/azd-for-beginners/issues)
- **Pertanyaan Pembelajaran**: [Komunitas Discord Microsoft Azure](https://discord.gg/microsoft-azure) dan [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **Bantuan Khusus AI**: Bergabung dengan [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **Dokumentasi**: [Dokumentasi Resmi Azure Developer CLI](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)

### Wawasan Komunitas dari Microsoft Foundry Discord

**Hasil Polling Terbaru dari Saluran #Azure:**
- **45%** pengembang ingin menggunakan AZD untuk beban kerja AI
- **Tantangan utama**: Deployment multi-layanan, manajemen kredensial, kesiapan produksi  
- **Permintaan terbanyak**: Template khusus AI, panduan troubleshooting, praktik terbaik

**Bergabung dengan komunitas kami untuk:**
- Berbagi pengalaman AZD + AI dan mendapatkan bantuan
- Mengakses pratinjau awal template AI baru
- Berkontribusi pada praktik terbaik deployment AI
- Mempengaruhi pengembangan fitur AI + AZD di masa depan

### Kontribusi untuk Kursus
Kami menyambut kontribusi! Harap baca [Panduan Kontribusi](CONTRIBUTING.md) untuk detail tentang:
- **Peningkatan Konten**: Perbaiki bab dan contoh yang ada
- **Contoh Baru**: Tambahkan skenario dan template dunia nyata  
- **Terjemahan**: Bantu mempertahankan dukungan multi-bahasa
- **Laporan Bug**: Tingkatkan akurasi dan kejelasan
- **Standar Komunitas**: Ikuti pedoman komunitas inklusif kami

---

## 📄 Informasi Kursus

### Lisensi
Proyek ini dilisensikan di bawah Lisensi MIT - lihat file [LICENSE](../../LICENSE) untuk detail.

### Sumber Belajar Microsoft Terkait

Tim kami juga membuat kursus pembelajaran komprehensif lainnya:

<!-- CO-OP TRANSLATOR OTHER COURSES START -->
### LangChain
[![LangChain4j untuk Pemula](https://img.shields.io/badge/LangChain4j%20for%20Beginners-22C55E?style=for-the-badge&&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchain4j-for-beginners)
[![LangChain.js untuk Pemula](https://img.shields.io/badge/LangChain.js%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchainjs-for-beginners?WT.mc_id=m365-94501-dwahlin)

---

### Azure / Edge / MCP / Agen
[![AZD untuk Pemula](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Edge AI untuk Pemula](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![MCP untuk Pemula](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Agen AI untuk Pemula](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Seri AI Generatif
[![AI Generatif untuk Pemula](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![AI Generatif (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
[![AI Generatif (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)
[![AI Generatif (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---
 
### Pembelajaran Inti
[![ML untuk Pemula](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![Data Science untuk Pemula](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![AI untuk Pemula](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Keamanan Siber untuk Pemula](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Pengembangan Web untuk Pemula](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![IoT untuk Pemula](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![Pengembangan XR untuk Pemula](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Seri Copilot
[![Copilot untuk Pemrograman Pasangan AI](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![Copilot untuk C#/.NET](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Petualangan Copilot](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ Navigasi Kursus

**🚀 Siap Memulai Belajar?**

**Pemula**: Mulai dengan [Bab 1: Dasar & Mulai Cepat](../..)  
**Pengembang AI**: Langsung ke [Bab 2: Pengembangan AI-First](../..)  
**Pengembang Berpengalaman**: Mulai dengan [Bab 3: Konfigurasi & Autentikasi](../..)

**Langkah Selanjutnya**: [Mulai Bab 1 - Dasar AZD](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Penafian**:  
Dokumen ini telah diterjemahkan menggunakan layanan terjemahan AI [Co-op Translator](https://github.com/Azure/co-op-translator). Meskipun kami berupaya untuk mencapai akurasi, harap diketahui bahwa terjemahan otomatis mungkin mengandung kesalahan atau ketidakakuratan. Dokumen asli dalam bahasa aslinya harus dianggap sebagai sumber yang sahih. Untuk informasi penting, kami menyarankan menggunakan jasa terjemahan profesional oleh manusia. Kami tidak bertanggung jawab atas kesalahpahaman atau kesalahan tafsir yang timbul dari penggunaan terjemahan ini.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->