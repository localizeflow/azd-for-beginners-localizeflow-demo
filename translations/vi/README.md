<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T14:00:56+00:00",
  "source_file": "README.md",
  "language_code": "vi"
}
-->
> Note: Tài liệu này liên tục được cập nhật để phản ánh những thay đổi mới nhất.

> ⚠️ Kho lưu trữ này là một bản demo được tạo để trình diễn
> việc bản địa hóa tài liệu tự động sử dụng Localizeflow.
>
> Nội dung gốc dựa trên
> dự án “AZD dành cho Người mới bắt đầu” của Microsoft.


# AZD Dành cho Người Mới Bắt Đầu: Hành Trình Học Tập Cấu Trúc

![AZD-for-beginners](../../translated_images/azdbeginners.5527441dd9f74068.vi.png) 

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## Bắt Đầu Với Khoá Học Này

Thực hiện theo các bước sau để bắt đầu hành trình học AZD của bạn:

1. **Fork Kho Lưu Trữ**: Nhấp vào [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)
2. **Clone Kho Lưu Trữ**: `git clone https://github.com/microsoft/azd-for-beginners.git`
3. **Tham Gia Cộng Đồng**: [Các cộng đồng Azure Discord](https://discord.com/invite/ByRwuEEgH4) để nhận hỗ trợ chuyên gia
4. **Chọn Lộ Trình Học**: Chọn chương bên dưới phù hợp với trình độ kinh nghiệm của bạn

### Hỗ Trợ Đa Ngôn Ngữ

#### Dịch Tự Động (Luôn Cập Nhật)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](./README.md)

> **Ưa thích Clone Cục bộ?**

> Kho lưu trữ này bao gồm hơn 50 bản dịch ngôn ngữ làm tăng đáng kể kích thước tải về. Để clone không có bản dịch, hãy sử dụng sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Điều này cung cấp cho bạn tất cả những gì cần thiết để hoàn thành khoá học với tốc độ tải xuống nhanh hơn nhiều.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## Tổng Quan Khoá Học

Làm chủ Azure Developer CLI (azd) qua các chương có cấu trúc được thiết kế để học theo tiến trình. **Tập trung đặc biệt vào triển khai ứng dụng AI với tích hợp Microsoft Foundry.**

### Tại Sao Khoá Học Này Quan Trọng Với Các Nhà Phát Triển Hiện Đại

Dựa trên thông tin từ cộng đồng Microsoft Foundry Discord, **45% nhà phát triển muốn sử dụng AZD cho các khối lượng công việc AI** nhưng gặp phải các thách thức sau:
- Kiến trúc AI đa dịch vụ phức tạp
- Thực tiễn tốt nhất để triển khai AI sản xuất  
- Tích hợp và cấu hình dịch vụ AI trên Azure
- Tối ưu hóa chi phí cho các khối lượng công việc AI
- Khắc phục sự cố triển khai AI đặc thù

### Mục Tiêu Học Tập

Hoàn thành khoá học có cấu trúc này, bạn sẽ:
- **Thành thạo các Kiến Thức Cơ Bản AZD**: Khái niệm cốt lõi, cài đặt và cấu hình
- **Triển Khai Ứng Dụng AI**: Sử dụng AZD với dịch vụ Microsoft Foundry
- **Thực Thi Cơ Sở Hạ Tầng như Mã (IaC)**: Quản lý tài nguyên Azure với mẫu Bicep
- **Khắc Phục Sự Cố Triển Khai**: Giải quyết những vấn đề thường gặp và debug
- **Tối Ưu Cho Môi Trường Sản Xuất**: Bảo mật, mở rộng, giám sát và quản lý chi phí
- **Xây Dựng Giải Pháp Multi-Agent**: Triển khai kiến trúc AI phức tạp

## 📚 Các Chương Học

*Chọn lộ trình học dựa trên trình độ và mục tiêu của bạn*

### 🚀 Chương 1: Nền Tảng & Khởi Đầu Nhanh
**Điều Kiện Tiên Quyết**: Tài khoản Azure, kiến thức cơ bản về dòng lệnh  
**Thời Lượng**: 30-45 phút  
**Độ Phức Tạp**: ⭐

#### Những Gì Bạn Sẽ Học
- Hiểu các kiến thức cơ bản về Azure Developer CLI
- Cài đặt AZD trên nền tảng của bạn
- Triển khai thành công dự án đầu tiên của bạn

#### Tài Nguyên Học Tập
- **🎯 Bắt Đầu Tại Đây**: [Azure Developer CLI là gì?](../..)
- **📖 Lý Thuyết**: [Cơ bản về AZD](docs/getting-started/azd-basics.md) - Khái niệm và thuật ngữ cốt lõi
- **⚙️ Thiết Lập**: [Cài đặt & Thiết lập](docs/getting-started/installation.md) - Hướng dẫn theo nền tảng
- **🛠️ Thực Hành**: [Dự án Đầu Tiên](docs/getting-started/first-project.md) - Hướng dẫn từng bước
- **📋 Tham Khảo Nhanh**: [Bảng Lệnh Tắt](resources/cheat-sheet.md)

#### Bài Tập Thực Hành
```bash
# Kiểm tra cài đặt nhanh
azd version

# Triển khai ứng dụng đầu tiên của bạn
azd init --template todo-nodejs-mongo
azd up
```

**💡 Kết Quả Chương**: Triển khai thành công một ứng dụng web đơn giản lên Azure bằng AZD

**✅ Xác Nhận Thành Công:**
```bash
# Sau khi hoàn thành Chương 1, bạn nên có khả năng:
azd version              # Hiển thị phiên bản đã cài đặt
azd init --template todo-nodejs-mongo  # Khởi tạo dự án
azd up                  # Triển khai lên Azure
azd show                # Hiển thị URL ứng dụng đang chạy
# Ứng dụng mở trong trình duyệt và hoạt động
azd down --force --purge  # Dọn dẹp tài nguyên
```

**📊 Thời Gian Đầu Tư:** 30-45 phút  
**📈 Cấp Độ Kỹ Năng Sau:** Có thể triển khai các ứng dụng cơ bản một cách độc lập

**✅ Xác Nhận Thành Công:**
```bash
# Sau khi hoàn thành Chương 1, bạn sẽ có thể:
azd version              # Hiển thị phiên bản đã cài đặt
azd init --template todo-nodejs-mongo  # Khởi tạo dự án
azd up                  # Triển khai lên Azure
azd show                # Hiển thị URL ứng dụng đang chạy
# Ứng dụng mở trên trình duyệt và hoạt động
azd down --force --purge  # Dọn dẹp các tài nguyên
```

**📊 Thời Gian Đầu Tư:** 30-45 phút  
**📈 Cấp Độ Kỹ Năng Sau:** Có thể triển khai các ứng dụng cơ bản một cách độc lập

---

### 🤖 Chương 2: Phát Triển Ưu Tiên AI (Khuyến nghị cho nhà phát triển AI)
**Điều Kiện Tiên Quyết**: Hoàn thành Chương 1  
**Thời Lượng**: 1-2 giờ  
**Độ Phức Tạp**: ⭐⭐

#### Những Gì Bạn Sẽ Học
- Tích hợp Microsoft Foundry với AZD
- Triển khai các ứng dụng AI
- Hiểu cấu hình dịch vụ AI

#### Tài Nguyên Học Tập
- **🎯 Bắt Đầu Tại Đây**: [Tích hợp Microsoft Foundry](docs/microsoft-foundry/microsoft-foundry-integration.md)
- **📖 Mẫu & Mô Hình**: [Triển khai Mô hình AI](docs/microsoft-foundry/ai-model-deployment.md) - Triển khai và quản lý mô hình AI
- **🛠️ Workshop**: [Phòng thí nghiệm AI Workshop](docs/microsoft-foundry/ai-workshop-lab.md) - Chuẩn bị giải pháp AI để dùng với AZD
- **🎥 Hướng Dẫn Tương Tác**: [Tài liệu Workshop](workshop/README.md) - Học qua trình duyệt với MkDocs * Môi trường DevContainer
- **📋 Mẫu**: [Mẫu Microsoft Foundry](../..)
- **📝 Ví dụ**: [Ví dụ Triển khai AZD](examples/README.md)

#### Bài Tập Thực Hành
```bash
# Triển khai ứng dụng AI đầu tiên của bạn
azd init --template azure-search-openai-demo
azd up

# Thử các mẫu AI bổ sung
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```

**💡 Kết Quả Chương**: Triển khai và cấu hình ứng dụng chat AI với khả năng RAG

**✅ Xác Nhận Thành Công:**
```bash
# Sau Chương 2, bạn sẽ có thể:
azd init --template azure-search-openai-demo
azd up
# Kiểm tra giao diện trò chuyện AI
# Đặt câu hỏi và nhận phản hồi do AI hỗ trợ kèm nguồn
# Xác minh tích hợp tìm kiếm hoạt động
azd monitor  # Kiểm tra Application Insights hiển thị dữ liệu viễn thám
azd down --force --purge
```

**📊 Thời Gian Đầu Tư:** 1-2 giờ  
**📈 Cấp Độ Kỹ Năng Sau:** Có thể triển khai và cấu hình ứng dụng AI sẵn sàng cho sản xuất  
**💰 Nhận Thức Chi Phí:** Hiểu chi phí phát triển $80-150/tháng, chi phí sản xuất $300-3500/tháng

#### 💰 Xem Xét Chi Phí Triển Khai AI

**Môi Trường Phát Triển (Ước tính $80-150/tháng):**
- Azure OpenAI (trả theo mức dùng): $0-50/tháng (dựa trên số lượng token)
- AI Search (mức cơ bản): $75/tháng
- Container Apps (theo mức tiêu thụ): $0-20/tháng
- Storage (Chuẩn): $1-5/tháng

**Môi Trường Sản Xuất (Ước tính $300-3,500+/tháng):**
- Azure OpenAI (PTU để đảm bảo hiệu suất nhất quán): $3,000+/tháng HOẶC trả theo mức dùng với khối lượng lớn
- AI Search (mức chuẩn): $250/tháng
- Container Apps (dùng riêng): $50-100/tháng
- Application Insights: $5-50/tháng
- Storage (Cao cấp): $10-50/tháng

**💡 Mẹo Tối Ưu Chi Phí:**
- Sử dụng **mức miễn phí** Azure OpenAI để học tập (bao gồm 50,000 token/tháng)
- Chạy `azd down` để giải phóng tài nguyên khi không phát triển
- Bắt đầu với chi phí theo mức tiêu thụ, nâng cấp lên PTU chỉ cho sản xuất
- Dùng `azd provision --preview` để ước tính chi phí trước triển khai
- Bật tự động mở rộng: chỉ trả tiền cho phần sử dụng thực tế

**Giám Sát Chi Phí:**
```bash
# Kiểm tra chi phí hàng tháng ước tính
azd provision --preview

# Giám sát chi phí thực tế trong Cổng Azure
az consumption budget list --resource-group <your-rg>
```

---

### ⚙️ Chương 3: Cấu Hình & Xác Thực
**Điều Kiện Tiên Quyết**: Hoàn thành Chương 1  
**Thời Lượng**: 45-60 phút  
**Độ Phức Tạp**: ⭐⭐

#### Những Gì Bạn Sẽ Học
- Cấu hình và quản lý môi trường
- Xác thực và thực hành bảo mật tốt nhất
- Đặt tên và tổ chức tài nguyên

#### Tài Nguyên Học Tập
- **📖 Cấu Hình**: [Hướng dẫn Cấu hình](docs/getting-started/configuration.md) - Thiết lập môi trường
- **🔐 Bảo Mật**: [Mẫu xác thực và quản lý danh tính](docs/getting-started/authsecurity.md) - Mẫu xác thực
- **📝 Ví dụ**: [Ví dụ Ứng dụng Database](examples/database-app/README.md) - Ví dụ AZD Database

#### Bài Tập Thực Hành
- Cấu hình nhiều môi trường (dev, staging, prod)
- Thiết lập xác thực managed identity
- Thực thi cấu hình đặc thù cho từng môi trường

**💡 Kết Quả Chương**: Quản lý nhiều môi trường với xác thực và bảo mật hợp lý

---

### 🏗️ Chương 4: Hạ Tầng như Mã & Triển Khai
**Điều Kiện Tiên Quyết**: Hoàn thành Các Chương 1-3  
**Thời Lượng**: 1-1.5 giờ  
**Độ Phức Tạp**: ⭐⭐⭐

#### Những Gì Bạn Sẽ Học
- Mẫu triển khai nâng cao
- Hạ tầng như Mã với Bicep
- Chiến lược cung cấp tài nguyên

#### Tài Nguyên Học Tập
- **📖 Triển Khai**: [Hướng dẫn Triển khai](docs/deployment/deployment-guide.md) - Quy trình đầy đủ
- **🏗️ Cung Cấp Tài Nguyên**: [Quản lý tài nguyên](docs/deployment/provisioning.md) - Quản lý tài nguyên Azure
- **📝 Ví dụ**: [Ví dụ Container App](../../examples/container-app) - Triển khai theo container

#### Bài Tập Thực Hành
- Tạo mẫu Bicep tuỳ chỉnh
- Triển khai ứng dụng đa dịch vụ
- Thực hiện chiến lược triển khai xanh-lục (blue-green deployment)

**💡 Kết Quả Chương**: Triển khai các ứng dụng đa dịch vụ phức tạp sử dụng mẫu hạ tầng tuỳ chỉnh

---
### 🎯 Chương 5: Giải pháp AI đa tác nhân (Nâng cao)
**Yêu cầu trước**: Hoàn thành Chương 1-2  
**Thời lượng**: 2-3 giờ  
**Độ phức tạp**: ⭐⭐⭐⭐

#### Những gì bạn sẽ học
- Các mẫu kiến trúc đa tác nhân
- Điều phối và phối hợp tác nhân
- Triển khai AI chuẩn sẵn sàng cho môi trường sản xuất

#### Tài nguyên học tập
- **🤖 Dự án nổi bật**: [Giải pháp đa tác nhân cho bán lẻ](examples/retail-scenario.md) - Triển khai hoàn chỉnh
- **🛠️ Mẫu ARM**: [Gói mẫu ARM](../../examples/retail-multiagent-arm-template) - Triển khai một cú nhấp chuột
- **📖 Kiến trúc**: [Mẫu phối hợp đa tác nhân](/docs/pre-deployment/coordination-patterns.md) - Các mẫu phối hợp

#### Bài tập thực hành
```bash
# Triển khai giải pháp đa tác nhân bán lẻ hoàn chỉnh
cd examples/retail-multiagent-arm-template
./deploy.sh

# Khám phá cấu hình tác nhân
az deployment group show --resource-group <rg-name> --name <deployment-name>
```

**💡 Kết quả chương**: Triển khai và quản lý giải pháp AI đa tác nhân chuẩn sản xuất với các tác nhân Khách hàng và Kho hàng

---

### 🔍 Chương 6: Kiểm tra & Lập kế hoạch trước khi triển khai
**Yêu cầu trước**: Hoàn thành Chương 4  
**Thời lượng**: 1 giờ  
**Độ phức tạp**: ⭐⭐

#### Những gì bạn sẽ học
- Lập kế hoạch dung lượng và xác thực tài nguyên
- Chiến lược lựa chọn SKU
- Kiểm tra trước khi triển khai và tự động hóa

#### Tài nguyên học tập
- **📊 Lập kế hoạch**: [Lập kế hoạch dung lượng](docs/pre-deployment/capacity-planning.md) - Xác thực tài nguyên
- **💰 Lựa chọn**: [Lựa chọn SKU](docs/pre-deployment/sku-selection.md) - Các lựa chọn tiết kiệm chi phí
- **✅ Xác thực**: [Kiểm tra tiền bay](docs/pre-deployment/preflight-checks.md) - Kịch bản tự động

#### Bài tập thực hành
- Chạy các kịch bản xác thực dung lượng
- Tối ưu lựa chọn SKU để tiết kiệm chi phí
- Triển khai kiểm tra tự động trước khi triển khai

**💡 Kết quả chương**: Xác thực và tối ưu hóa triển khai trước khi thực thi

---

### 🚨 Chương 7: Xử lý sự cố & Gỡ lỗi
**Yêu cầu trước**: Hoàn thành bất kỳ chương triển khai nào  
**Thời lượng**: 1-1.5 giờ  
**Độ phức tạp**: ⭐⭐

#### Những gì bạn sẽ học
- Các phương pháp gỡ lỗi có hệ thống
- Các vấn đề phổ biến và cách giải quyết
- Xử lý sự cố đặc thù cho AI

#### Tài nguyên học tập
- **🔧 Vấn đề chung**: [Các vấn đề phổ biến](docs/troubleshooting/common-issues.md) - Câu hỏi thường gặp và cách giải quyết
- **🕵️ Gỡ lỗi**: [Hướng dẫn gỡ lỗi](docs/troubleshooting/debugging.md) - Chiến lược từng bước
- **🤖 Vấn đề AI**: [Xử lý sự cố AI](docs/troubleshooting/ai-troubleshooting.md) - Vấn đề dịch vụ AI

#### Bài tập thực hành
- Chẩn đoán lỗi triển khai
- Giải quyết vấn đề xác thực
- Gỡ lỗi kết nối dịch vụ AI

**💡 Kết quả chương**: Tự lập chẩn đoán và giải quyết các vấn đề triển khai phổ biến

---

### 🏢 Chương 8: Mẫu Sản xuất & Doanh nghiệp
**Yêu cầu trước**: Hoàn thành Chương 1-4  
**Thời lượng**: 2-3 giờ  
**Độ phức tạp**: ⭐⭐⭐⭐

#### Những gì bạn sẽ học
- Chiến lược triển khai sản xuất
- Mẫu bảo mật doanh nghiệp
- Giám sát và tối ưu chi phí

#### Tài nguyên học tập
- **🏭 Sản xuất**: [Thực hành AI sản xuất](docs/microsoft-foundry/production-ai-practices.md) - Mẫu doanh nghiệp
- **📝 Ví dụ**: [Ví dụ Microservices](../../examples/microservices) - Kiến trúc phức tạp
- **📊 Giám sát**: [Tích hợp Application Insights](docs/pre-deployment/application-insights.md) - Giám sát

#### Bài tập thực hành
- Triển khai mẫu bảo mật doanh nghiệp
- Thiết lập giám sát toàn diện
- Triển khai vào sản xuất với quản trị phù hợp

**💡 Kết quả chương**: Triển khai ứng dụng doanh nghiệp sẵn sàng sản xuất với đầy đủ chức năng

---

## 🎓 Tổng quan Workshop: Trải nghiệm học tập thực hành

> **⚠️ TÌNH TRẠNG WORKSHOP: Đang phát triển**  
> Tài liệu workshop đang được phát triển và hoàn thiện. Các module chính đã hoạt động, nhưng một số phần nâng cao chưa hoàn chỉnh. Chúng tôi đang tích cực hoàn thiện tất cả nội dung. [Theo dõi tiến độ →](workshop/README.md)

### Tài liệu workshop tương tác
**Trải nghiệm học tập thực hành toàn diện với công cụ trên trình duyệt và bài tập hướng dẫn**

Tài liệu workshop cung cấp một trải nghiệm học tập cấu trúc, tương tác bổ sung cho chương trình học dựa trên các chương ở trên. Workshop được thiết kế cho cả việc học tự động và học có hướng dẫn bởi giảng viên.

#### 🛠️ Đặc điểm Workshop
- **Giao diện trình duyệt**: Workshop đầy đủ được cung cấp bởi MkDocs với chức năng tìm kiếm, sao chép và chủ đề
- **Tích hợp GitHub Codespaces**: Thiết lập môi trường phát triển chỉ với một cú nhấp chuột
- **Lộ trình học tập có cấu trúc**: 7 bước bài tập hướng dẫn (tổng 3.5 giờ)
- **Phương pháp Tiêu điểm → Triển khai → Tùy chỉnh**: Quy trình tiến bộ
- **Môi trường DevContainer tương tác**: Công cụ và phụ thuộc cấu hình sẵn

#### 📚 Cấu trúc Workshop
Workshop theo phương pháp **Khám phá → Triển khai → Tùy chỉnh**:

1. **Giai đoạn Khám phá** (45 phút)
   - Khám phá mẫu và dịch vụ Microsoft Foundry
   - Hiểu các mẫu kiến trúc đa tác nhân
   - Xem xét yêu cầu và điều kiện triển khai

2. **Giai đoạn Triển khai** (2 giờ)
   - Thực hành triển khai ứng dụng AI với AZD
   - Cấu hình dịch vụ Azure AI và các điểm cuối
   - Triển khai mẫu bảo mật và xác thực

3. **Giai đoạn Tùy chỉnh** (45 phút)
   - Chỉnh sửa ứng dụng cho trường hợp sử dụng cụ thể
   - Tối ưu cho triển khai sản xuất
   - Triển khai giám sát và quản lý chi phí

#### 🚀 Bắt đầu với Workshop
```bash
# Lựa chọn 1: GitHub Codespaces (Khuyến nghị)
# Nhấn "Code" → "Create codespace on main" trong kho lưu trữ

# Lựa chọn 2: Phát triển cục bộ
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# Làm theo hướng dẫn cài đặt trong workshop/README.md
```

#### 🎯 Kết quả học tập Workshop
Sau khi hoàn thành workshop, người tham gia sẽ:
- **Triển khai ứng dụng AI sản xuất**: Sử dụng AZD với dịch vụ Microsoft Foundry
- **Thành thạo kiến trúc đa tác nhân**: Triển khai giải pháp tác nhân AI phối hợp
- **Thực hiện bảo mật tốt nhất**: Cấu hình xác thực và kiểm soát truy cập
- **Tối ưu hóa quy mô**: Thiết kế triển khai tiết kiệm chi phí và hiệu suất cao
- **Xử lý sự cố triển khai**: Tự giải quyết các vấn đề phổ biến

#### 📖 Tài nguyên Workshop
- **🎥 Hướng dẫn tương tác**: [Tài liệu Workshop](workshop/README.md) - Môi trường học tập trên trình duyệt
- **📋 Hướng dẫn chi tiết**: [Bài tập hướng dẫn](../../workshop/docs/instructions) - Các bước thực hiện cụ thể
- **🛠️ Phòng thí nghiệm AI**: [Phòng thí nghiệm AI Workshop](docs/microsoft-foundry/ai-workshop-lab.md) - Bài tập tập trung AI
- **💡 Khởi đầu nhanh**: [Hướng dẫn thiết lập Workshop](workshop/README.md#quick-start) - Cấu hình môi trường

**Phù hợp cho**: Đào tạo doanh nghiệp, khoá học đại học, học tự do, và bootcamp lập trình viên.

---

## 📖 Azure Developer CLI là gì?

Azure Developer CLI (azd) là giao diện dòng lệnh hướng tới nhà phát triển giúp tăng tốc quá trình xây dựng và triển khai ứng dụng trên Azure. Nó cung cấp:

- **Triển khai theo mẫu** - Sử dụng mẫu có sẵn cho các mẫu ứng dụng phổ biến
- **Hạ tầng dưới dạng mã** - Quản lý tài nguyên Azure bằng Bicep hoặc Terraform  
- **Quy trình tích hợp** - Cung cấp, triển khai và giám sát ứng dụng liền mạch
- **Thân thiện với nhà phát triển** - Tối ưu năng suất và trải nghiệm phát triển

### **AZD + Microsoft Foundry: Hoàn hảo cho triển khai AI**

**Tại sao chọn AZD cho Giải pháp AI?** AZD xử lý các thách thức hàng đầu dành cho nhà phát triển AI:

- **Mẫu sẵn sàng AI** - Mẫu cấu hình sẵn cho Azure OpenAI, Dịch vụ Nhận thức, và khối lượng công việc ML
- **Triển khai AI bảo mật** - Mẫu bảo mật tích hợp cho dịch vụ AI, khóa API và điểm cuối mô hình  
- **Mẫu AI sản xuất** - Thực hành tốt nhất cho triển khai ứng dụng AI có thể mở rộng và tiết kiệm chi phí
- **Quy trình AI đầu-cuối** - Từ phát triển mô hình tới triển khai sản xuất và giám sát đúng cách
- **Tối ưu chi phí** - Phân bổ tài nguyên thông minh và chiến lược mở rộng cho khối lượng AI
- **Tích hợp Microsoft Foundry** - Kết nối liền mạch với danh mục mẫu và điểm cuối của Microsoft Foundry

---

## 🎯 Thư viện Mẫu & Ví dụ

### Nổi bật: Mẫu Microsoft Foundry
**Bắt đầu tại đây nếu bạn triển khai ứng dụng AI!**

> **Lưu ý:** Những mẫu này minh họa các mẫu AI khác nhau. Một số thuộc Azure Samples bên ngoài, số khác là triển khai cục bộ.

| Mẫu | Chương | Độ phức tạp | Dịch vụ | Loại |
|----------|---------|------------|----------|------|
| [**Bắt đầu với AI chat**](https://github.com/Azure-Samples/get-started-with-ai-chat) | Chương 2 | ⭐⭐ | AzureOpenAI + Azure AI Model Inference API + Azure AI Search + Azure Container Apps + Application Insights | Ngoài |
| [**Bắt đầu với tác nhân AI**](https://github.com/Azure-Samples/get-started-with-ai-agents) | Chương 2 | ⭐⭐ | Azure AI Agent Service + AzureOpenAI + Azure AI Search + Azure Container Apps + Application Insights| Ngoài |
| [**Demo Azure Search + OpenAI**](https://github.com/Azure-Samples/azure-search-openai-demo) | Chương 2 | ⭐⭐ | AzureOpenAI + Azure AI Search + App Service + Storage | Ngoài |
| [**Ứng dụng Chat OpenAI Khởi động nhanh**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Chương 2 | ⭐ | AzureOpenAI + Container Apps + Application Insights | Ngoài |
| [**Agent OpenAI Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Chương 5 | ⭐⭐⭐ | AzureOpenAI + Azure Functions + Prompty | Ngoài |
| [**Contoso Chat RAG**](https://github.com/Azure-Samples/contoso-chat) | Chương 8 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Cosmos DB + Container Apps | Ngoài |
| [**Giải pháp đa tác nhân bán lẻ**](examples/retail-scenario.md) | Chương 5 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Storage + Container Apps + Cosmos DB | **Cục bộ** |

### Nổi bật: Kịch bản học tập hoàn chỉnh
**Mẫu ứng dụng chuẩn sản xuất được sắp xếp theo chương học**

| Mẫu | Chương học | Độ phức tạp | Học chính |
|----------|------------------|------------|--------------|
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Chương 2 | ⭐ | Mẫu triển khai AI cơ bản |
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Chương 2 | ⭐⭐ | Triển khai RAG với Azure AI Search |
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | Chương 4 | ⭐⭐ | Tích hợp Trí tuệ Tài liệu |
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Chương 5 | ⭐⭐⭐ | Khung tác nhân và gọi hàm |
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | Chương 8 | ⭐⭐⭐ | Điều phối AI doanh nghiệp |
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | Chương 5 | ⭐⭐⭐⭐ | Kiến trúc đa tác nhân với tác nhân Khách hàng và Kho hàng |

### Học theo loại ví dụ

> **📌 Ví dụ cục bộ vs. bên ngoài:**  
> **Ví dụ cục bộ** (trong repo này) = Sẵn sàng sử dụng ngay  
> **Ví dụ bên ngoài** (Azure Samples) = Clone từ repo liên kết

#### Ví dụ cục bộ (Sẵn sàng sử dụng)
- [**Giải pháp đa tác nhân bán lẻ**](examples/retail-scenario.md) - Triển khai sản xuất hoàn chỉnh với mẫu ARM
  - Kiến trúc đa tác nhân (Khách hàng + Kho hàng)
  - Giám sát và đánh giá toàn diện
  - Triển khai một cú nhấp chuột qua mẫu ARM

#### Ví dụ cục bộ - Ứng dụng Container (Chương 2-5)
**Ví dụ triển khai container toàn diện trong repo này:**
- [**Ví dụ Ứng dụng Container**](examples/container-app/README.md) - Hướng dẫn đầy đủ triển khai container hóa
  - [API Flask đơn giản](../../examples/container-app/simple-flask-api) - API REST cơ bản với khả năng scale-to-zero
  - [Kiến trúc Microservices](../../examples/container-app/microservices) - Triển khai đa dịch vụ chuẩn sản xuất
  - Mẫu Khởi đầu nhanh, Sản xuất và Nâng cao
  - Hướng dẫn giám sát, bảo mật và tối ưu chi phí

#### Ví dụ bên ngoài - Ứng dụng đơn giản (Chương 1-2)
**Clone các repo Azure Samples để bắt đầu:**
- [Ứng dụng Web đơn giản - Node.js + MongoDB](https://github.com/Azure-Samples/todo-nodejs-mongo) - Mẫu triển khai cơ bản
- [Website tĩnh - React SPA](https://github.com/Azure-Samples/todo-csharp-sql-swa-func) - Triển khai nội dung tĩnh
- [Ứng dụng Container - Python Flask](https://github.com/Azure-Samples/container-apps-store-api-microservice) - Triển khai API REST

#### Ví dụ bên ngoài - Tích hợp Cơ sở dữ liệu (Chương 3-4)  
- [Ứng dụng Cơ sở dữ liệu - C# + SQL](https://github.com/Azure-Samples/todo-csharp-sql) - Mẫu kết nối cơ sở dữ liệu
- [Functions + Cosmos DB](https://github.com/Azure-Samples/todo-python-mongo-swa-func) - Quy trình dữ liệu serverless

#### Ví dụ bên ngoài - Mẫu nâng cao (Chương 4-8)
- [Microservices Java](https://github.com/Azure-Samples/java-microservices-aca-lab) - Kiến trúc đa dịch vụ
- [Container Apps Jobs](https://github.com/Azure-Samples/container-apps-jobs) - Xử lý tác vụ nền  
- [ML doanh nghiệp](https://github.com/Azure-Samples/mlops-v2) - Mẫu ML chuẩn sản xuất

### Bộ sưu tập mẫu bên ngoài
- [**Thư viện Mẫu AZD Chính Thức**](https://azure.github.io/awesome-azd/) - Bộ sưu tập tuyển chọn các mẫu chính thức và cộng đồng
- [**Mẫu Azure Developer CLI**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - Tài liệu mẫu Microsoft Learn
- [**Thư mục Ví dụ**](examples/README.md) - Ví dụ học tập tại chỗ với giải thích chi tiết

---

## 📚 Tài Nguyên Học Tập & Tham Khảo

### Tài liệu Tham Khảo Nhanh
- [**Bảng Tổng Hợp Lệnh**](resources/cheat-sheet.md) - Các lệnh azd thiết yếu được tổ chức theo chương
- [**Thuật Ngữ**](resources/glossary.md) - Thuật ngữ Azure và azd  
- [**Câu hỏi Thường Gặp**](resources/faq.md) - Các câu hỏi phổ biến được tổ chức theo chương học
- [**Hướng Dẫn Học Tập**](resources/study-guide.md) - Bài tập thực hành toàn diện

### Hội Thảo Thực Hành
- [**Phòng Thí Nghiệm Hội Thảo AI**](docs/microsoft-foundry/ai-workshop-lab.md) - Biến giải pháp AI của bạn thành có thể triển khai bằng AZD (2-3 giờ)
- [**Hướng Dẫn Hội Thảo Tương Tác**](workshop/README.md) - Hội thảo trên trình duyệt với MkDocs và môi trường DevContainer
- [**Lộ Trình Học Tập Có Cấu Trúc**](../../workshop/docs/instructions) - Bài tập được hướng dẫn 7 bước (Khám phá → Triển khai → Tùy chỉnh)
- [**Hội Thảo AZD Cho Người Mới Bắt Đầu**](workshop/README.md) - Tài liệu hội thảo thực hành đầy đủ tích hợp GitHub Codespaces

### Tài Nguyên Học Tập Bên Ngoài
- [Tài liệu Azure Developer CLI](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)
- [Trung Tâm Kiến Trúc Azure](https://learn.microsoft.com/en-us/azure/architecture/)
- [Máy Tính Giá Azure](https://azure.microsoft.com/pricing/calculator/)
- [Tình Trạng Azure](https://status.azure.com/)

---

## 🔧 Hướng Dẫn Khắc Phục Sự Cố Nhanh

**Các sự cố phổ biến người mới gặp phải và giải pháp ngay lập tức:**

### ❌ "azd: command not found"

```bash
# Cài đặt AZD trước
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Xác minh cài đặt
azd version
```

### ❌ "No subscription found" hoặc "Subscription not set"

```bash
# Liệt kê các đăng ký có sẵn
az account list --output table

# Đặt đăng ký mặc định
az account set --subscription "<subscription-id-or-name>"

# Thiết lập cho môi trường AZD
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Xác minh
az account show
```

### ❌ "InsufficientQuota" hoặc "Quota exceeded"

```bash
# Thử các vùng Azure khác nhau
azd env set AZURE_LOCATION "westus2"
azd up

# Hoặc sử dụng SKU nhỏ hơn trong phát triển
# Chỉnh sửa infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```

### ❌ "azd up" thất bại giữa chừng

```bash
# Lựa chọn 1: Làm sạch và thử lại
azd down --force --purge
azd up

# Lựa chọn 2: Chỉ sửa hạ tầng
azd provision

# Lựa chọn 3: Kiểm tra nhật ký chi tiết
azd show
azd logs
```

### ❌ "Authentication failed" hoặc "Token expired"

```bash
# Xác thực lại
az logout
az login

azd auth logout
azd auth login

# Xác minh xác thực
az account show
```

### ❌ "Resource already exists" hoặc xung đột tên đặt

```bash
# AZD tạo tên duy nhất, nhưng nếu bị trùng:
azd down --force --purge

# Sau đó thử lại với môi trường mới
azd env new dev-v2
azd up
```

### ❌ Triển khai mẫu mất quá nhiều thời gian

**Thời gian chờ bình thường:**
- Ứng dụng web đơn giản: 5-10 phút
- Ứng dụng có cơ sở dữ liệu: 10-15 phút
- Ứng dụng AI: 15-25 phút (Cung cấp OpenAI chậm)

```bash
# Kiểm tra tiến độ
azd show

# Nếu bị kẹt >30 phút, kiểm tra Azure Portal:
azd monitor
# Tìm các triển khai thất bại
```

### ❌ "Permission denied" hoặc "Forbidden"

```bash
# Kiểm tra vai trò Azure của bạn
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Bạn cần ít nhất vai trò "Contributor"
# Yêu cầu quản trị viên Azure của bạn cấp:
# - Contributor (cho các tài nguyên)
# - User Access Administrator (cho các cấp phát vai trò)
```

### ❌ Không thể tìm URL ứng dụng đã triển khai

```bash
# Hiển thị tất cả các điểm cuối dịch vụ
azd show

# Hoặc mở Azure Portal
azd monitor

# Kiểm tra dịch vụ cụ thể
azd env get-values
# Tìm các biến *_URL
```

### 📚 Tài Nguyên Khắc Phục Sự Cố Toàn Diện

- **Hướng Dẫn Các Sự Cố Phổ Biến:** [Giải pháp Chi Tiết](docs/troubleshooting/common-issues.md)
- **Sự Cố Riêng Cho AI:** [Khắc Phục Ai](docs/troubleshooting/ai-troubleshooting.md)
- **Hướng Dẫn Gỡ Lỗi:** [Gỡ Lỗi Từng Bước](docs/troubleshooting/debugging.md)
- **Nhận Trợ Giúp:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🔧 Hướng Dẫn Khắc Phục Sự Cố Nhanh

**Các sự cố phổ biến người mới gặp phải và giải pháp ngay lập tức:**

<details>
<summary><strong>❌ "azd: command not found"</strong></summary>

```bash
# Cài đặt AZD trước
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Xác minh cài đặt
azd version
```
</details>

<details>
<summary><strong>❌ "No subscription found" hoặc "Subscription not set"</strong></summary>

```bash
# Liệt kê các đăng ký có sẵn
az account list --output table

# Đặt đăng ký mặc định
az account set --subscription "<subscription-id-or-name>"

# Đặt cho môi trường AZD
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Xác minh
az account show
```
</details>

<details>
<summary><strong>❌ "InsufficientQuota" hoặc "Quota exceeded"</strong></summary>

```bash
# Thử các khu vực Azure khác nhau
azd env set AZURE_LOCATION "westus2"
azd up

# Hoặc sử dụng các SKU nhỏ hơn trong phát triển
# Chỉnh sửa infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>

<details>
<summary><strong>❌ "azd up" thất bại giữa chừng</strong></summary>

```bash
# Lựa chọn 1: Dọn dẹp và thử lại
azd down --force --purge
azd up

# Lựa chọn 2: Chỉ sửa hạ tầng
azd provision

# Lựa chọn 3: Kiểm tra nhật ký chi tiết
azd show
azd logs
```
</details>

<details>
<summary><strong>❌ "Authentication failed" hoặc "Token expired"</strong></summary>

```bash
# Xác thực lại
az logout
az login

azd auth logout
azd auth login

# Xác minh xác thực
az account show
```
</details>

<details>
<summary><strong>❌ "Resource already exists" hoặc xung đột tên đặt</strong></summary>

```bash
# AZD tạo ra các tên duy nhất, nhưng nếu có xung đột:
azd down --force --purge

# Sau đó thử lại với môi trường mới
azd env new dev-v2
azd up
```
</details>

<details>
<summary><strong>❌ Triển khai mẫu mất quá nhiều thời gian</strong></summary>

**Thời gian chờ bình thường:**
- Ứng dụng web đơn giản: 5-10 phút
- Ứng dụng có cơ sở dữ liệu: 10-15 phút
- Ứng dụng AI: 15-25 phút (Cung cấp OpenAI chậm)

```bash
# Kiểm tra tiến trình
azd show

# Nếu bị kẹt >30 phút, kiểm tra Azure Portal:
azd monitor
# Tìm các triển khai thất bại
```
</details>

<details>
<summary><strong>❌ "Permission denied" hoặc "Forbidden"</strong></summary>

```bash
# Kiểm tra vai trò Azure của bạn
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Bạn cần ít nhất vai trò "Người đóng góp"
# Yêu cầu quản trị viên Azure của bạn cấp:
# - Người đóng góp (cho các tài nguyên)
# - Quản trị viên truy cập người dùng (cho các phân bổ vai trò)
```
</details>

<details>
<summary><strong>❌ Không thể tìm URL ứng dụng đã triển khai</strong></summary>

```bash
# Hiển thị tất cả các điểm kết dịch vụ
azd show

# Hoặc mở Cổng thông tin Azure
azd monitor

# Kiểm tra dịch vụ cụ thể
azd env get-values
# Tìm các biến *_URL
```
</details>

### 📚 Tài Nguyên Khắc Phục Sự Cố Toàn Diện

- **Hướng Dẫn Các Sự Cố Phổ Biến:** [Giải pháp Chi Tiết](docs/troubleshooting/common-issues.md)
- **Sự Cố Riêng Cho AI:** [Khắc Phục Ai](docs/troubleshooting/ai-troubleshooting.md)
- **Hướng Dẫn Gỡ Lỗi:** [Gỡ Lỗi Từng Bước](docs/troubleshooting/debugging.md)
- **Nhận Trợ Giúp:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🎓 Hoàn Thành Khóa Học & Chứng Nhận

### Theo Dõi Tiến Độ
Theo dõi tiến độ học qua từng chương:

- [ ] **Chương 1**: Nền Tảng & Bắt Đầu Nhanh ✅
- [ ] **Chương 2**: Phát Triển AI-Đầu Tiên ✅  
- [ ] **Chương 3**: Cấu Hình & Xác Thực ✅
- [ ] **Chương 4**: Hạ Tầng như Mã & Triển Khai ✅
- [ ] **Chương 5**: Giải Pháp AI Đa Tác Nhân ✅
- [ ] **Chương 6**: Xác Thực & Lập Kế Hoạch Trước Triển Khai ✅
- [ ] **Chương 7**: Khắc Phục Sự Cố & Gỡ Lỗi ✅
- [ ] **Chương 8**: Mẫu Ứng Dụng Sản Xuất & Doanh Nghiệp ✅

### Xác Minh Học Tập
Sau khi hoàn thành mỗi chương, xác minh kiến thức của bạn bằng cách:
1. **Bài Tập Thực Hành**: Hoàn thành triển khai thực hành của chương
2. **Kiểm Tra Kiến Thức**: Xem lại phần FAQ của chương bạn học
3. **Thảo Luận Cộng Đồng**: Chia sẻ trải nghiệm trên Azure Discord
4. **Chương Tiếp Theo**: Tiếp tục đến trình độ phức tạp kế tiếp

### Lợi Ích Khi Hoàn Thành Khóa Học
Khi hoàn tất tất cả các chương, bạn sẽ có:
- **Kinh Nghiệm Sản Xuất**: Triển khai các ứng dụng AI thực tế lên Azure
- **Kỹ Năng Chuyên Nghiệp**: Khả năng triển khai doanh nghiệp sẵn sàng  
- **Sự Công Nhận Cộng Đồng**: Thành viên tích cực trong cộng đồng nhà phát triển Azure
- **Thăng Tiến Nghề Nghiệp**: Chuyên môn AZD và triển khai AI được săn đón

---

## 🤝 Cộng Đồng & Hỗ Trợ

### Nhận Trợ Giúp & Hỗ Trợ
- **Vấn đề Kỹ Thuật**: [Báo lỗi và đề xuất tính năng](https://github.com/microsoft/azd-for-beginners/issues)
- **Câu hỏi Học Tập**: [Cộng đồng Microsoft Azure Discord](https://discord.gg/microsoft-azure) và [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **Trợ Giúp Riêng Cho AI**: Tham gia [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **Tài Liệu**: [Tài liệu Azure Developer CLI chính thức](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)

### Thông Tin Cộng Đồng từ Microsoft Foundry Discord

**Kết quả Bình Chọn Gần Đây từ kênh #Azure:**
- **45%** nhà phát triển muốn sử dụng AZD cho khối lượng công việc AI
- **Thách thức hàng đầu**: Triển khai đa dịch vụ, quản lý thông tin xác thực, sẵn sàng sản xuất  
- **Yêu cầu nhiều nhất**: Mẫu riêng AI, hướng dẫn khắc phục sự cố, thực hành tốt nhất

**Tham gia cộng đồng chúng tôi để:**
- Chia sẻ trải nghiệm AZD + AI và nhận trợ giúp
- Truy cập bản xem trước sớm các mẫu AI mới
- Góp phần vào thực hành tốt nhất về triển khai AI
- Tác động đến phát triển tính năng AI + AZD trong tương lai

### Đóng Góp Cho Khóa Học
Chúng tôi hoan nghênh đóng góp! Vui lòng đọc [Hướng dẫn Đóng Góp](CONTRIBUTING.md) để biết chi tiết về:
- **Cải Thiện Nội Dung**: Nâng cấp các chương và ví dụ hiện có
- **Ví Dụ Mới**: Thêm các kịch bản thực tế và mẫu  
- **Phiên Dịch**: Hỗ trợ duy trì hỗ trợ đa ngôn ngữ
- **Báo Cáo Lỗi**: Cải thiện độ chính xác và rõ ràng
- **Tiêu Chuẩn Cộng Đồng**: Tuân theo các hướng dẫn cộng đồng bao gồm

---

## 📄 Thông Tin Khóa Học

### Giấy Phép
Dự án này được cấp phép theo Giấy phép MIT - xem file [LICENSE](../../LICENSE) để biết chi tiết.

### Tài Nguyên Học Tập Liên Quan của Microsoft

Nhóm của chúng tôi sản xuất các khóa học học tập toàn diện khác:

<!-- CO-OP TRANSLATOR OTHER COURSES START -->
### LangChain
[![LangChain4j dành cho Người Mới](https://img.shields.io/badge/LangChain4j%20for%20Beginners-22C55E?style=for-the-badge&&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchain4j-for-beginners)
[![LangChain.js dành cho Người Mới](https://img.shields.io/badge/LangChain.js%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchainjs-for-beginners?WT.mc_id=m365-94501-dwahlin)

---

### Azure / Edge / MCP / Agents
[![AZD cho Người Mới](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Edge AI cho Người Mới](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![MCP cho Người Mới](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)
[![AI Agents cho Người Mới](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Series AI Tạo Sinh
[![AI Tạo Sinh cho Người Mới](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![AI Tạo Sinh (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
[![AI Tạo Sinh (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)
[![AI Tạo Sinh (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---
 
### Học Tập Cốt Lõi
[![ML cho Người Mới](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![Data Science for Beginners](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![AI for Beginners](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Cybersecurity for Beginners](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Web Dev for Beginners](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![IoT for Beginners](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![XR Development for Beginners](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Copilot Series
[![Copilot for AI Paired Programming](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![Copilot for C#/.NET](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Copilot Adventure](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ Điều Hướng Khóa Học

**🚀 Sẵn sàng Bắt Đầu Học?**

**Người mới bắt đầu**: Bắt đầu với [Chương 1: Nền tảng & Bắt đầu nhanh](../..)  
**Nhà phát triển AI**: Chuyển đến [Chương 2: Phát triển AI-First](../..)  
**Nhà phát triển kinh nghiệm**: Bắt đầu với [Chương 3: Cấu hình & Xác thực](../..)

**Bước tiếp theo**: [Bắt đầu Chương 1 - AZD Cơ bản](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Tuyên bố từ chối trách nhiệm**:
Tài liệu này đã được dịch bằng dịch vụ dịch thuật AI [Co-op Translator](https://github.com/Azure/co-op-translator). Mặc dù chúng tôi cố gắng đảm bảo độ chính xác, xin lưu ý rằng bản dịch tự động có thể chứa lỗi hoặc thiếu chính xác. Tài liệu gốc bằng ngôn ngữ gốc nên được coi là nguồn tham khảo chính thức. Đối với các thông tin quan trọng, nên sử dụng dịch vụ dịch thuật chuyên nghiệp do con người thực hiện. Chúng tôi không chịu trách nhiệm về bất kỳ hiểu lầm hay giải thích sai nào phát sinh từ việc sử dụng bản dịch này.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->