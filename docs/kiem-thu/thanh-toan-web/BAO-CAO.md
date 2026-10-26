# #25 — Chính sách thanh toán web, 26/10/2026
Trạng thái: **Chờ Claude soát**; nhánh `codex/thanh-toan-web` từ master `92d504a`.
- Chỉ thêm mục4c Thanh toán trên web và ngày cập nhật trong `day-tro-cua-toi.html`.
- Đối chiếu với master sau khi bỏ hai phần thêm (chuẩn hoá CRLF/LF): nội dung về app giống hệt.
- Mục mới ghi dữ liệu đơn/giao dịch, mã máy băm, mã băm hạn tần suất; không hứa không lưu dữ liệu kỹ thuật mà máy chủ thực tế có lưu.
- Không lưu tên/số tài khoản người chuyển trong game/DB đơn; ngân hàng/SePay xử lý giao dịch.
- Link điều khoản đúng `https://banhmi-collab.github.io/daytro/dieu-khoan.html`; liên hệ web đúng emailWarmJar.
- Đã chụp mục4c và cuối trang ở360×640/1280×900; không tràn ngang (360/360 và1265/1280); console không lỗi.
- `git diff --check` đạt. Chỉ commit cục bộ; chưa push/đăng.
## Giải thích cho Thảo
`day-tro-cua-toi.html` (chính sách): bổ sung phần mua web đúng dữ liệu hệ thống, người mua có thể đọc cách dùng/khôi phục thông tin đơn.
Các ảnh/báo cáo kiểm tra: ghi bằng chứng đọc trên điện thoại và máy tính.
Rủi ro nếu có lỗi: người mua hiểu nhầm dữ liệu/quyền mua; Claude đọc nội dung trước khi đăng. Phần app cũ không sửa.