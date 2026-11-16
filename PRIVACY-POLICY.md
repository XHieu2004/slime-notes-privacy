# Privacy Policy — Slime Notes

**Publisher:** K.Shadow  
**Package Identity:** `K.Shadow.SlimeNotes` (Store ID: `9PN5RCMZRKWK`)  
**Effective Date:** 2026-11-16

---

## English

### 1. Offline-First & No Data Transmission
**Slime Notes** is designed to operate completely offline on your Windows PC. It requires no online account, collects no analytics or telemetry, displays no ads, and **does not transmit your notes or personal data over the Internet**.

### 2. Desktop & Window Imagery for Liquid Glass Effects
- To render real-time glass refraction and translucent gel physics behind floating desktop notes, Slime Notes reads desktop/window surfaces locally using standard Windows graphics APIs (`Desktop Duplication` / Direct3D 11, and optional `Windows.Graphics.Capture` when *Recording/Screenshot mode* is enabled by the user).
- Captured screen/window frames are processed locally in device memory (GPU/RAM) solely to compute glass refraction, blur, and preview rendering on your PC. The app never records your screen secretly and never uploads display images externally.
- Snapshot images (`.bmp`) are saved to `Pictures\SlimeNotes` only when the user manually triggers the `F12` snapshot action.

### 3. User-Selected Files & Local Data Storage
- **App Data Folder (`LocalState`):** In the Microsoft Store edition, your notes, edit history (`history`), deleted notes (`deleted-notes`), reminders, appearance settings, desktop collision paths, and imported backdrop/alarm copies are saved locally in the package's `LocalState` folder.
- **Files You Choose:** Slime Notes only accesses images (`.png`, `.jpg`, `.jpeg`, `.bmp`), `.mp4` videos, audio files, or backup folders explicitly selected by you through standard Windows file/folder dialogs.
- **Exports & Snapshots:** Manual `F12` snapshots use the Windows `Pictures` Known Folder (`Pictures\SlimeNotes`, working seamlessly even when redirected to OneDrive or another drive). Library backups are exported only to the folder you pick.

### 4. Startup & Uninstall
- Enabling *Start with Windows* registers a standard Windows `StartupTask` to restore pinned notes upon sign-in and fully respects Windows Settings / Task Manager (`DisabledByUser`).
- Uninstalling a Microsoft Store package deletes its isolated `LocalState` data directory. Use *Settings → Application → Manage data → Export library backup…* before uninstalling to keep a copy of your data.

### 5. Contact
Support contact: **K.Shadow** (`hieuxuan20041906@gmail.com`)

---

## Tiếng Việt

### 1. Xử lý cục bộ & Không gửi dữ liệu ra ngoài
**Slime Notes** được thiết kế hoạt động hoàn toàn ngoại tuyến trên máy tính Windows của bạn. Ứng dụng không cần tài khoản trực tuyến, không thu thập dữ liệu đo lường hành vi, không quảng cáo và **cam kết không truyền nội dung ghi chú hay dữ liệu cá nhân ra ngoài qua Internet**.

### 2. Lấy hình nền desktop và cửa sổ cho hiệu ứng kính
- Để hiển thị hiệu ứng khúc xạ Liquid Glass và thân gel trong suốt phía sau ghi chú nổi trên màn hình, Slime Notes đọc bề mặt desktop/cửa sổ cục bộ bằng các API đồ họa chuẩn của Windows (`Desktop Duplication` / Direct3D 11, và tùy chọn `Windows.Graphics.Capture` khi người dùng bật *Chế độ quay/chụp*).
- Dữ liệu hình ảnh bề mặt màn hình được xử lý cục bộ trong bộ nhớ của thiết bị (GPU/RAM) để tính toán khúc xạ, làm mờ và hiển thị xem trước ngay trên máy; ứng dụng không tự ý quay lén hay gửi hình ảnh ra ngoài.
- Ứng dụng chỉ xuất ảnh `.bmp` vào thư mục `Pictures\SlimeNotes` khi bạn chủ động bấm phím tắt `F12`.

### 3. Truy cập tệp người dùng chọn & Lưu dữ liệu
- **Thư mục dữ liệu (`LocalState`):** Bản Microsoft Store lưu toàn bộ ghi chú, lịch sử sửa đổi (`history`), ghi chú đã xóa (`deleted-notes`), lịch nhắc, cài đặt, đường va chạm desktop và bản sao hình nền/âm thanh vào thư mục `LocalState` riêng của ứng dụng trên máy.
- **Tệp do người dùng chọn:** Ứng dụng chỉ truy cập ảnh (`.png`, `.jpg`, `.jpeg`, `.bmp`), video `.mp4`, tệp âm thanh hoặc thư mục nhập bản sao do chính bạn chọn qua hộp thoại Windows.
- **Thư mục xuất:** Ảnh chụp `F12` lưu vào thư mục `Pictures\SlimeNotes` lấy qua Windows Known Folder (hoạt động bình thường ngay cả khi `Pictures` đã chuyển sang OneDrive hoặc ổ đĩa khác); bản sao thư viện chỉ xuất vào thư mục bạn chọn.

### 4. Khởi động cùng Windows & Gỡ cài đặt
- Tính năng *Khởi động cùng Windows* sử dụng `StartupTask` chuẩn của Windows và tôn trọng trạng thái bật/tắt trong Windows Settings hoặc Task Manager.
- Khi gỡ cài đặt ứng dụng Store, dữ liệu trong `LocalState` sẽ bị xóa theo gói; vui lòng dùng *Quản lý dữ liệu → Xuất bản sao thư viện…* trước khi gỡ ứng dụng.
