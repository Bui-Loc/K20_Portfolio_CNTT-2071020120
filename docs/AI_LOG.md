# Nhật ký sử dụng AI

## Khai báo

Có dùng AI để kiểm tra website,gợi ý và thực hiện một số chỉnh sửa,quét lại code để điền báo cáo vào README.md và RELEASE_NOTES.md
Còn tôi thì phản biện chọn lọc,kiểm tra lại các lỗi đã sửa

## Vấn đề và cách xử lý

| Vấn đề | Gợi ý | Việc đã làm |
|---|---|---|
| Trang kết quả dẫn sai đường dẫn CSS | Sửa đường dẫn cho đúng | Đổi thành `style.css`,đã kiểm tra tải được |
| Giao diện hai trang chưa đồng bộ | Làm đẹp và thống nhất giao diện | Tạo điểm nhấn cho portfolio,trang kết quả và nút quay lại |
| Cần hỗ trợ màn hình nhỏ và giảm hiệu ứng | Thêm điều chỉnh responsive và giảm chuyển động | Đã thêm breakpoint,`prefers-reduced-motion`,giữ viền focus bàn phím |
| README thiếu hướng dẫn sử dụng | Bổ sung cấu trúc,cách chạy và cách thử | Đã cập nhật `README.md` |
| Form GET đưa dữ liệu lên URL,không có máy chủ xử lý | Nêu rõ giới hạn của form | Giữ form mô phỏng,không gửi email hoặc lưu dữ liệu |

## Kiểm tra

- Đường dẫn CSS,liên kết trong trang và nhãn hỗ trợ form đều hợp lệ
- Trang kết quả hiển thị đúng,không tràn ngang ở chiều rộng 375 px
- Chưa xem được `index.html` trên trình duyệt tích hợp (`ERR_FAILED`),đã kiểm tra tĩnh
- Chỉ dùng dữ liệu giả khi thử form

ngày 11/5/2026
cải tiến thêm nút đổi màu cho trang web

