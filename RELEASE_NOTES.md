--bản v1:
lỗi sai cú pháp liên kết html với css
đã sửa vào 30 tháng 10 2026
thay đổi đường dẫn css đến index không hiện trang trí
--bản v2
lỗi cú pháp liên kết ket qua với css
ngày chỉnh sửa 30 tháng 10 2026
 Đường dẫn CSS đã đúng: style.css.
Thuộc tính aria-describedby của textarea đã sửa thành message-help.
Trang portfolio và form hoạt động đúng hơn về giao diện và accessibility. 
--bản v3
v3 — 04/11/2026
- **Thay đổi chính:** làm mới giao diện portfolio và trang kết quả,thêm điều chỉnh cho màn hình nhỏ để nhập ảnh đại diện và giảm chuyển động,bổ sung hướng dẫn chạy và kiểm tra trong `README.md`
- **Lỗi đã sửa:** đổi đường dẫn CSS trang kết quả sang `style.css`
- **Commit liên quan:** chưa có commit trong kho Git nên chưa có mã hash
- **Hạn chế:** form chỉ kiểm tra dữ liệu trên trình duyệt,dùng GET nên dữ liệu xuất hiện trên URL,không gửi email hoặc lưu dữ liệu; trang chính chưa kiểm tra trực quan được trong trình duyệt tích hợp
v4 - 11/5/2026
đổi màu các nút và một số vùng trong web

## v8 — 05/11/2026
- **Thay đổi chính:** thêm bộ chọn màu giao diện tím, xanh lá và xanh nước biển trên trang portfolio và trang kết quả.
- **Triển khai:** dùng HTML và CSS thuần, không sử dụng Java hoặc JavaScript; CSS `:has(:checked)` cập nhật màu nền, chữ, nút và các chi tiết giao diện theo lựa chọn.
- **Hạn chế:** màu đã chọn chỉ có hiệu lực trên trang hiện tại; tải lại hoặc chuyển trang sẽ trở về tím.
- **Tag GitHub:** `v8` — commit `8c0fb37` (`v8 thêm nút đổi các màu của giao diện`).