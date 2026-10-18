# NET HY VỌNG — Mười Đêm Cuối

Game kinh dị 3D góc nhìn thứ nhất chạy trên trình duyệt, viết bằng HTML/CSS/JavaScript và Three.js. Các nhân vật được dựng trực tiếp từ các khối hình học 3D trong mã nguồn; không cần tải bộ model nặng.

## Chơi game

- Mở [index.html](./index.html) bằng trình duyệt khi có kết nối Internet để tải Three.js từ CDN.
- Máy tính: **WASD** di chuyển, **Shift** chạy, **E** tương tác, chuột để nhìn, **Esc** tạm dừng.
- Điện thoại: kéo nửa trái màn hình để di chuyển, kéo nửa phải để nhìn, chạm nút **E** để tương tác.

## Mục tiêu và kết thúc

- **Good Ending:** kiếm tiền và trả hết khoản nợ trước hạn.
- **Bad Ending:** hết tiền, cạn sức khỏe hoặc hết 10 đêm mà chưa trả xong nợ.
- **Secret Ending:** tìm đủ ba manh mối trong quán, sau đó tương tác với cửa hậu.

Thu tiền tại các máy có khách; mua máy mới hoặc nâng cấp để tăng doanh thu. Dùng mì gói và nước để hồi đói, khát và sức khỏe. Chủ nợ có thể xuất hiện khi đêm xuống.

## Xuất bản miễn phí bằng GitHub Pages

1. Mở **Settings → Pages** trong repository.
2. Ở phần **Build and deployment**, chọn **Deploy from a branch**.
3. Chọn branch **main**, thư mục **/(root)** rồi bấm **Save**.
4. Khi GitHub Pages hoàn tất triển khai, trang game sẽ có địa chỉ dạng `https://phucdepzai2012.github.io/netscary/`.

## Hiệu năng

Game giới hạn pixel ratio, tái sử dụng hình học và vật liệu, giới hạn ánh sáng đổ bóng và giữ mọi thành phần trong một file để triển khai đơn giản.
