# Roblox BLUE — Releases

Đây là kho phát hành (release) của **Roblox BLUE** — ứng dụng hỗ trợ chơi Roblox
(giao diện terminal neon, C++/Win32 + GDI+), thuộc hệ sinh thái **BLUE LABS**.

> Mã nguồn được giữ riêng (private). Repo này **chỉ** chứa bản phát hành đã biên dịch.

## 📥 Tải về
Vào trang **[Releases](../../releases/latest)** và tải file `RobloxBLUE.exe` về chạy trực tiếp —
không cần cài đặt, không cần thư viện ngoài.

Mỗi bản có kèm:
- `RobloxBLUE.exe` — chương trình (x64, Windows 10/11)
- `sha256.txt` — mã hash SHA256 để kiểm tra file tải về có nguyên vẹn không.

Kiểm tra hash (PowerShell):
```powershell
(Get-FileHash .\RobloxBLUE.exe -Algorithm SHA256).Hash.ToLower()
# So với nội dung trong sha256.txt
```

## ⚠️ Lưu ý sử dụng
- Ứng dụng phục vụ mục đích **học tập, nghiên cứu kỹ thuật và tự động hóa cá nhân**.
- Chỉ sử dụng trên **tài khoản của chính bạn**.
- **Không** dùng để gian lận, phá game, quấy rối người chơi khác hoặc vi phạm Điều khoản dịch vụ của Roblox.
- **Bạn tự chịu trách nhiệm** với mọi rủi ro phát sinh từ việc sử dụng.

## 🔄 Tự động cập nhật
Ứng dụng tự kiểm tra bản mới tại repo này (qua GitHub Releases) mỗi khi khởi động.
Khi có bản mới, app sẽ hỏi bạn có muốn tải & cài đặt tự động không (có kiểm tra SHA256
trước khi thay thế).

<sub>Made with ❤️ by [bluemanhst](https://github.com/bluemanhst) · BLUE LABS Ecosystem</sub>
