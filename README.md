# SnapPaper — Ứng dụng quét tài liệu

Ứng dụng web quét giấy tờ, hóa đơn, bài tập và tài liệu bằng camera điện thoại.

## Tính năng
- Mở camera sau để chụp tài liệu hoặc chọn ảnh có sẵn.
- Nhận diện bốn góc giấy tự động khi bộ OpenCV.js tải được.
- Căn chỉnh phối cảnh, kéo từng góc để chỉnh thủ công, xoay ảnh 90°.
- Bộ lọc màu gốc, thang xám và đen trắng.
- Tải từng trang về dưới dạng JPG; ghép nhiều trang thành một file PDF.
- Thư viện lưu cục bộ trong trình duyệt bằng IndexedDB.
- Có manifest và service worker để thêm lên màn hình chính; giao diện hỗ trợ sử dụng ngoại tuyến sau khi tải vỏ ứng dụng.
- Không gửi ảnh hoặc tài liệu lên máy chủ.

## Chạy trên GitHub Pages
1. Mở **Settings → Pages** trong repository.
2. Chọn triển khai từ nhánh \`main\`, thư mục \`/\` (root).
3. Mở trang bằng URL HTTPS, ví dụ \`https://phucdepzai2012.github.io/netscary/\`.
4. Trên điện thoại, cho phép quyền camera. Dùng menu của trình duyệt để chọn **Thêm vào màn hình chính / Install app** nếu được hỗ trợ.

## Lưu ý
- Camera yêu cầu HTTPS (GitHub Pages đã dùng HTTPS) và quyền camera.
- Tự nhận diện mép giấy cần tải thư viện OpenCV.js từ máy chủ bên ngoài. Nếu thư viện không tải được hoặc không nhận ra giấy, vẫn có thể kéo bốn điểm góc để căn thủ công.
- Ảnh trong thư viện được lưu trong bộ nhớ của trình duyệt trên thiết bị hiện tại. Tệp JPG/PDF tải xuống là bản lưu riêng trong thư mục tải xuống; xóa dữ liệu trình duyệt có thể xóa thư viện cục bộ.
- Ứng dụng không có đăng nhập, backend hoặc đồng bộ đám mây.
