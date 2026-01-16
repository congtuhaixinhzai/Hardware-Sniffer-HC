<div align="center">

# 🔍 Hardware Sniffer
**The Core Component of OpCore Simplify Project**

[![GitHub Stars](https://img.shields.io/github/stars/lzhoang2801/Hardware-Sniffer?style=for-the-badge&color=ffd700)](https://github.com/lzhoang2801/Hardware-Sniffer/stargazers)
[![License](https://img.shields.io/github/license/lzhoang2801/Hardware-Sniffer?style=for-the-badge&color=007bff)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Windows-0078d7?style=for-the-badge&logo=windows)](https://github.com/lzhoang2801/Hardware-Sniffer)
[![Status](https://img.shields.io/badge/Security-Signed-success?style=for-the-badge&logo=powershell)](https://github.com/lzhoang2801/Hardware-Sniffer)

---

**Hardware Sniffer** đóng vai trò thiết yếu trong việc đơn giản hóa và tự động hóa quá trình thu thập, phân tích dữ liệu phần cứng. Đúng như cái tên "Sniffer", công cụ này sẽ "đánh hơi" mọi ngóc ngách hệ thống để cung cấp cái nhìn toàn diện nhất cho hành trình Hackintosh của bạn.

[✨ Features](#-features) • [❓ Q&A](#-qa) • [🚀 How To Use](#-how-to-use) • [📞 Contact](#-contact)

</div>

> [!NOTE]
> Dự án này đã được ký số (Digitally Signed) để đảm bảo tính an toàn và tin cậy cho người dùng.

---

## ✨ Features Highlights

| | Tính năng | Chi tiết |
| :--- | :--- | :--- |
| 📊 | **Dữ liệu Toàn diện** | Trích xuất thông tin Motherboard, CPU, GPU, Network, Audio, USB, Storage, Biometric, Bluetooth thông qua WMIC. |
| 🧠 | **Nhận diện Chipset** | Sử dụng PCI Device ID để xác định chính xác Chipset Intel/AMD. |
| 🔢 | **CPU Codename** | Nhận diện Codename thông qua công thức `Family x Model x Stepping` (Không cần Internet/ARK). |
| 🔌 | **Input Detection** | Tự động phân loại kiểu kết nối của Touchpad/Touchscreen (I2C, PS2, SMBus, USB). |

---

## ❓ Q&A

- **Hỗ trợ macOS và Linux không?**
  - **macOS**: ❌ Không. Để tránh sai lệch dữ liệu do các bản vá Hackintosh trước đó, chúng tôi chỉ khuyên dùng trên Windows sạch.
  - **Linux**: 🔄 Đang phát triển tại branch `add-linux-support`.

---

## 🚀 How To Use

### 1️⃣ Download
Truy cập tab [Releases](https://github.com/lzhoang2801/Hardware-Sniffer/releases) và tải về phiên bản `.exe` mới nhất.

### 2️⃣ Khởi chạy
Chạy `Hardware-Sniffer.exe`. Quá trình "sniffing" có thể mất vài giây tùy vào độ phức tạp của hệ thống.

### 3️⃣ Menu điều khiển
Sau khi quét xong, bạn có 3 lựa chọn chính:
* **`T`**: Chế độ xem rút gọn hoặc đầy đủ.
* **`H`**: Xuất báo cáo ra định dạng **JSON** (Dùng cho OpCore Simplify).
* **`A`**: Dump bảng **ACPI** trực tiếp từ hệ thống.

### 4️⃣ Kết quả
Mọi tệp tin xuất ra sẽ nằm gọn trong thư mục `Results` tại nơi bạn chạy chương trình.

---

## 🤝 Contributing

Mọi đóng góp cho dự án đều được trân trọng! Nếu bạn có ý tưởng mới, đừng ngần ngại:
1. **Fork** dự án.
2. Tạo bản cập nhật.
3. Mở một **Pull Request** hoặc **Issue** với tag "enhancement".

---

## 🙌 Credits

Dự án sử dụng và kế thừa tinh hoa từ:
- **WMI**: Microsoft WMIC & Python WMI Module.
- **cpuid.py**: Thư viện thuần Python truy cập x86 processor details.
- **PCI/USB ID Repository**: Cơ sở dữ liệu định danh thiết bị toàn cầu.
- **Subprocess wrapper**: Từ mã nguồn của **CorpNewt**.

---

## 📞 Contact

<div align="center">

**Congtuhaixinhzai**

[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://facebook.com/macforce2601)
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/lzhoang2601)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lzhoang2601@gmail.com)

</div>

## 🌟 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=lzhoang2801/Hardware-Sniffer&type=Date)](https://star-history.com/#lzhoang2801/Hardware-Sniffer&Date)
