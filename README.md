# giaodientv

APK và manifest cập nhật OTA cho launcher TV gia đình (package `com.gathin.tvhome`).

## Cài đặt

- APK nằm trong `launcher/`, tên file có phiên bản.
- Cài lần đầu qua ADB: `adb install -r launcher/giaodientv-vX.Y.Z.apk`, hoặc dùng trình quản lý file trên TV.
- Nếu TV hỏi, bật **Cài đặt từ nguồn này** cho Launcher.

## Cập nhật OTA

- Trên TV: **Cài đặt → Kết nối → Cập nhật Launcher**.
- Launcher đọc `launcher/update.json`, so `versionCode`, tải APK và kiểm tra SHA-256 trước khi cài.
- APK cập nhật phải cùng chữ ký với bản đang cài.
