# 🎮 Roblox BLUE — Tải ứng dụng

> **Roblox BLUE** (bởi [*bluemanhst*](https://github.com/bluemanhst)) là ứng dụng hỗ trợ chơi Roblox
> với giao diện đồ họa (GUI) thuần Win32/GDI+ phong cách **terminal neon**,
> thuộc hệ sinh thái **BLUE LABS**. Được xây dựng hoàn toàn bằng **C++ native** —
> **1 file `.exe` duy nhất, không cần cài đặt, không cần thư viện ngoài.**

---

## 📥 TẢI PHIÊN BẢN MỚI NHẤT

### 👉 [**TẢI TẠI ĐÂY — Releases](../../releases/latest)**

Tải file **`RobloxBLUE.exe`** về → double-click là chạy ngay.
*(Chạy được trên Desktop, USB, thư mục bất kỳ — vì mọi icon/ảnh đã tích hợp sẵn trong exe.)*

### 📦 Mỗi bản phát hành gồm 2 file

| File | Mô tả |
|------|-------|
| `RobloxBLUE.exe` | Chương trình (x64, Windows 10/11) — tải file này về dùng |
| `sha256.txt` | Mã hash SHA256 để kiểm tra file tải về có nguyên vẹn không |

### 🔍 Kiểm tra file sau khi tải (khuyên dùng)

Mở PowerShell tại thư mục chứa file, chạy:

```powershell
(Get-FileHash .\RobloxBLUE.exe -Algorithm SHA256).Hash.ToLower()
# So sánh với nội dung trong sha256.txt — phải KHỚP nhau 100%
```

---

## ✨ TÍNH NĂNG NỔI BẬT

### 🪟 1. Đa Cửa Sổ (Multi-Instance)
* Mở **nhiều cửa sổ Roblox** cùng lúc trên một máy — vượt qua giới hạn singleton mặc định.
* Bật/tắt ngay trong giao diện, hỗ trợ **phím tắt toàn cục** (kể cả khi đang chơi game).

### 🛡️ 2. Chống Kick (AFK Engine)
* Tự động thực hiện chuỗi hành động (nhấn/giữ phím, chờ) theo chu kỳ tùy chỉnh để tránh bị kick.
* Jitter ngẫu nhiên cho giống hành vi người thật + **phím tắt toàn cục** bật/tắt nhanh.

### ⚡ 3. Chuỗi Hành Động (Action Profiles)
* Tạo nhiều **chuỗi hành động** độc lập: nhấn phím, tổ hợp phím, **giữ phím** (ms), **chờ** (ms), Zoom.
* Gán chuỗi riêng cho từng client Roblox đang chạy.

### 🐉 4. Hỗ Trợ Game — Dragon Soul
* Tự động bấm thẻ bài + **Auto Macro** (ghi & phát lại thao tác thật: chuột, phím, camera).
* Xuất/nhập macro (`.json`) để chia sẻ hoặc sao lưu.

### 🛠️ 5. Công Cụ Hỗ Trợ
* **Grid Snap**: xếp mọi cửa sổ Roblox thành lưới gọn gàng.
* **FPS Capper**: giới hạn FPS khi AFK để tiết kiệm CPU/GPU, tự phục hồi khi focus.
* **Auto Mute**: tự tắt tiếng Roblox trong chu kỳ AFK.

### 🌐 6. Giao Diện & Tiện Ích
* Song ngữ **Tiếng Việt / English** — chuyển tức thì, nhớ lựa chọn.
* Ẩn vào **System Tray**, thông báo Windows + âm thanh nhẹ.
* Giao diện **neon terminal** thuần GDI+ — mượt, không phụ thuộc runtime ngoài.

---

## 🔄 TỰ ĐỘNG CẬP NHẬT

Ứng dụng **tự kiểm tra bản mới** tại repo này (qua GitHub Releases) mỗi khi khởi động
(1 lần/ngày) hoặc khi bạn bấm **Cài đặt → Kiểm tra cập nhật**.

Khi có bản mới, app hiện **hộp thoại đồng bộ theme** cho bạn chọn:
**[Tải & cài đặt]** hoặc **[Để sau]** — file tải về được **kiểm tra SHA256** trước khi thay thế.

---

## 💻 YÊU CẦU HỆ THỐNG

* **Windows 10/11** (64-bit)
* Không cần cài thêm bất kỳ thứ gì (C++ runtime đã tích hợp sẵn trong exe)

---

## ⚠️ LƯU Ý SỬ DỤNG (nên đọc trước khi dùng)

* Dự án phục vụ mục đích **học tập, nghiên cứu kỹ thuật và tự động hóa cá nhân**.
* Chỉ sử dụng trên **tài khoản của chính bạn**.
* Công cụ này **không** được dùng để gian lận, phá game, quấy rối người chơi khác
  hoặc vi phạm Điều khoản dịch vụ của Roblox.
* **Bạn tự chịu hoàn toàn trách nhiệm** đối với mọi rủi ro phát sinh từ việc sử dụng.

---

## 📄 GIẤY PHÉP

Dự án được phát hành theo giấy phép **MIT License**.

---

## 🌐 HỆ SINH THÁI BLUE LABS

**BLUE LABS** — bộ công cụ tự động hóa do *bluemanhst* phát triển:

| Dự án | Mô tả | Ngôn ngữ |
|-------|-------|----------|
| **Roblox BLUE** | Hỗ trợ chơi Roblox (repo này — bản phát hành) | C++ |
| [**Discord BLUE**](https://github.com/bluemanhst/Discord-BLUE) | Tự động hóa Discord | Python |

> 💻 **Lập trình viên?** Mã nguồn được giữ riêng (private).
> Repo này **chỉ** chứa bản phát hành đã biên dịch, sẵn sàng tải & chạy.

---

<div align="center">
  <sub>Made with ❤️ by <a href="https://github.com/bluemanhst">bluemanhst</a> · BLUE LABS Ecosystem</sub>
</div>

