

![CI/CD Status](https://github.com/nam311220054819-sketch/luong-ma/actions/workflows/main.yml/badge.svg)

Đây là sản phẩm Demo tối ưu hóa quy trình phát triển phần mềm cho đội ngũ **CodeStream**, sử dụng các công nghệ hiện đại để tự động hóa việc kiểm tra và đóng gói ứng dụng.


* **GitHub Actions:** Tự động hóa quy trình (Pipeline).
* **Docker:** Đóng gói ứng dụng vào Container để chạy ổn định mọi nơi.
* **Node.js:** Nền t gian chạy ứng dụng demo.


1. **Kiểm tra mã nguồn:** Mỗi khi có thay đổi, hệ thống tự động chạy `npm test`.
2. **Đóng gói Docker:** Sau khi test thành công, hệ thống tự động Build Docker Image.
3. **Báo cáo:** Kết quả được hiển thị trực tiếp thông qua huy hiệu trạng thái ở trên.

