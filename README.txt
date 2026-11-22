GÓC SOI CHIẾU · SHADOW WORK (PHIÊN BẢN APP WEB / PWA CHO ANDROID)
Sáng tạo bởi: CÁ HỀ DIEU AN

1. CẤU TRÚC GÓI ỨNG DỤNG:
- index.html      : Toàn bộ giao diện, logic 78 Thẻ Thấu Suốt, Gương Soi Cảm Xúc, Self-Care, Nhạc Web Audio & nút cài đặt App.
- manifest.json   : Cấu hình Web App Manifest chuẩn Android (chế độ standalone không thanh địa chỉ, khóa hướng dọc, theme màu tối).
- sw.js           : Service Worker giúp ứng dụng chạy mượt cả khi mất mạng (Offline-first cho tài nguyên tĩnh).
- icons/          : Bộ biểu tượng chuẩn Android (192x192, 512x512 và maskable 512x512 cho icon tròn/bo góc trên Android).

2. CÁCH ĐƯA LÊN MẠNG (ĐỂ CÀI VỀ ĐIỆN THOẠI ANDROID):
- Bước 1: Giải nén toàn bộ thư mục này và tải lên GitHub Pages, Vercel hoặc Netlify (bắt buộc chạy qua HTTPS để Android nhận diện App).
- Bước 2: Mở đường link trang web bằng trình duyệt Google Chrome trên điện thoại Android.
- Bước 3: Bấm nút "📲 Cài App" trên màn hình hoặc bấm menu ⋮ (góc trên bên phải Chrome) -> chọn "Cài đặt ứng dụng" (Install app).
- Bước 4: Biểu tượng "Góc Soi Chiếu" sẽ xuất hiện trên màn hình chính Android, mở lên toàn màn hình như ứng dụng gốc và dùng được cả khi ngoại tuyến.

3. CẬP NHẬT PHIÊN BẢN SAU NÀY:
- Khi chỉnh sửa index.html, hãy đổi 'goc-soi-chieu-v1' thành 'goc-soi-chieu-v2' trong file sw.js để điện thoại tự cập nhật bản mới.
