# DUONG VIET TRUNG — Developer Portfolio & Game Portal

Website cá nhân và cổng thông tin nhà phát triển của **DUONG VIET TRUNG**, đạt chuẩn phê duyệt **Google AdSense** và đáp ứng chính sách quyền riêng tư của **Google Play Console & Google AdMob**.

## 🌐 Các trang chính

- **Trang chủ (`index.html`)**: Giới thiệu về DUONG VIET TRUNG, danh mục game độc lập, triết lý phát triển, vị trí quảng cáo AdSense.
- **Chính sách ZicZac, Offline Mini Games (`ziczac/privacy_policy.html`)**: Chính sách quyền riêng tư chính thức chuẩn Google Play Console cho game `com.trung.vi.game.menu`.
- **Chính sách chung (`privacy_policy.html`)**: Chính sách website & Google AdSense cookies.
- **Điều khoản sử dụng (`terms.html`)**: Điều khoản dịch vụ.
- **Xác thực AdSense / AdMob (`ads.txt`, `app-ads.txt`)**:
  ```
  google.com, pub-3367369898480591, DIRECT, f08c47fec0942fa0
  ```

## 🚀 Hướng dẫn kích hoạt GitHub Pages để truy cập như website

1. **Tạo repository mới trên GitHub**:
   - Truy cập: [https://github.com/new](https://github.com/new)
   - Đặt tên repository: `trungprofile` (hoặc `duongtrungg.github.io` nếu muốn làm trang gốc).
   - Chọn chế độ: **Public**.
   - Bấm **Create repository**.

2. **Đẩy mã nguồn từ máy lên GitHub**:
   ```bash
   cd "/home/trung/Tài liệu/project/trunggprofile"
   git remote add origin https://github.com/duongtrungg/trungprofile.git
   git push -u origin main
   ```

3. **Bật GitHub Pages**:
   - Vào mục **Settings** của repository trên GitHub.
   - Chọn menu **Pages** (bên trái).
   - Tại mục **Build and deployment** -> **Source**: Chọn `Deploy from a branch`.
   - Branch: Chọn `main`, thư mục `/ (root)`.
   - Bấm **Save**.
   - Sau 1 - 2 phút, website sẽ hoạt động trực tiếp tại địa chỉ:
     `https://duongtrungg.github.io/trungprofile/`
     (hoặc `https://duongtrungg.github.io/` nếu đặt tên repo là `duongtrungg.github.io`).

4. **Liên kết vào Google Play Console & Google AdMob**:
   - **Google Play Console (Privacy Policy URL)**:
     `https://duongtrungg.github.io/trungprofile/ziczac/privacy_policy.html`
   - **Google AdMob (App-ads.txt URL)**:
     `https://duongtrungg.github.io/trungprofile/` (AdMob sẽ tự tìm `/app-ads.txt`).
