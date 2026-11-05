## Liên kết

- **Tác giả:** Bùi Văn Lộc
- **Hồ sơ GitHub:** https://github.com/Bui-Loc
- **Trang GitHub Pages:** https://bui-loc.github.io/K20_Portfolio_CNTT-2071020120/

# K20_Portfolio_CNTT-2071020120
Trang portfolio cá nhân giới thiệu tác giả, kỹ năng, dự án, quá trình học tập
và thông tin liên hệ. Sản phẩm là website tĩnh được xây dựng bằng HTML và CSS.

## Cấu trúc thư mục

```text
K20_Portfolio_CNTT-2071020120/
├── index.html          # Trang portfolio chính
├── ket-qua.html        # Trang kết quả mô phỏng khi gửi form
├── style.css           # Giao diện, responsive và trạng thái tương tác
├── README.md           # Mô tả và hướng dẫn sử dụng dự án
├── AI_LOG.md           # Nhật ký kiểm tra và cải thiện
└── kiem-tra-lab5.txt   # Ghi chú/biểu mẫu kiểm tra bài Lab 5
```
## Chạy trên máy local
Đây là website tĩnh, không cần cài thư viện hay cơ sở dữ liệu.
**Cách 1 — Mở trực tiếp:** mở `index.html` bằng trình duyệt.
**Cách 2 — Dùng máy chủ HTTP local (khuyến nghị):**
1. Mở PowerShell hoặc Terminal tại thư mục dự án.
2. Chạy:
   ```powershell
   python -m http.server 8000
   ```
   Nếu lệnh `python` không có trên Windows, thử `py -m http.server 8000`.
3. Mở <http://localhost:8000> trong trình duyệt. Dừng máy chủ bằng `Ctrl+C`.
## Kiểm tra các tính năng chính
1. **Điều hướng:** nhấn các mục Giới thiệu, Kỹ năng, Dự án, Lộ trình và Liên hệ trên thanh menu; kiểm tra các liên kết trong thẻ dự án và nút “Liên hệ với tôi”.
2. **Tương tác và bàn phím:** rê chuột lên nút, liên kết và thẻ dự án; nhấn `Tab` để đi qua các điều khiển và quan sát viền focus.
3. **Responsive:** thu nhỏ cửa sổ hoặc dùng chế độ thiết bị trong DevTools (ví dụ chiều rộng 375 px); kiểm tra menu, thẻ dự án và form không tràn ngang.
4. **Kiểm tra form:** đến mục Liên hệ, thử gửi form trống để thấy xác thực trường bắt buộc. Thử email sai định dạng, họ tên dưới 2 ký tự, nội dung dưới 10 ký tự hoặc trên 500 ký tự; sau đó nhập dữ liệu giả hợp lệ để gửi.
5. **Kết quả mô phỏng:** sau khi gửi hợp lệ, trình duyệt mở `ket-qua.html` và các giá trị của form được thêm vào URL vì form dùng phương thức GET. Nhấn “Quay lại Portfolio” để trở về mục Liên hệ.

> Form chỉ minh họa xác thực phía trình duyệt: không gửi email, không lưu dữ liệu và không có xử lý phía máy chủ. Chỉ dùng dữ liệu giả khi thử nghiệm.




