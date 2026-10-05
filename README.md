# 📌 Nhiệm Vụ & Lộ Trình - ESP32-S3 Upgrade

Hệ thống quản lý mục tiêu, nhiệm vụ và theo dõi tiến độ chi tiết cho lộ trình nâng cấp hệ thống phần cứng & firmware vi điều khiển **ESP32-S3**.

> 🌿 **Nhánh phát triển**: `ESP32S3_Dat_upgrade`  
> 👤 **Người thực hiện**: QuangDat ([@hjsdhsjdsdds-ship-it](https://github.com/hjsdhsjdsdds-ship-it))

---

## 🌟 Các Giai Đoạn Lộ Trình (Roadmap Milestones)
1. **Giai đoạn 1: Phần Cứng & Môi Trường ESP32-S3**  
   - Thiết lập môi trường biên dịch (ESP-IDF / PlatformIO).
   - Kiểm tra cấu hình chip ESP32-S3 (Dual-core Xtensa LX7, Flash, PSRAM).
   - Định nghĩa sơ đồ chân (Pinout) và cấu hình ngoại vi.

2. **Giai đoạn 2: Firmware & Tính Năng Nâng Cấp**  
   - Xây dựng kiến trúc đa nhiệm với FreeRTOS.
   - Triển khai kết nối không dây: Wi-Fi và Bluetooth Low Energy (BLE 5.0).
   - Tích hợp nâng cấp từ xa OTA (Over-The-Air Firmware Update).

3. **Giai đoạn 3: Kiểm Thử, Tối Ưu & Bàn Giao**  
   - Kiểm thử độ ổn định (Stress testing) dưới tải cao.
   - Tối ưu hóa mức tiêu thụ năng lượng (Deep Sleep / Light Sleep).
   - Đóng gói tài liệu kỹ thuật và bàn giao.

---

## 🚀 Cách Mở Ứng Dụng Quản Lý
Mở trực tiếp file `index.html` bằng trình duyệt web:
```bash
open index.html
```

---

## 📁 Cấu Trúc Mã Nguồn
```text
nhiemvulotrinh/
├── index.html        # Giao diện bảng Kanban & tiến độ lộ trình tương tác
├── README.md         # Tài liệu dự án và lộ trình nâng cấp ESP32-S3
└── .gitignore        # Danh sách các tệp bỏ qua khi commit Git
```
