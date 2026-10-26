# #25 — Sửa chính sách sau soát vòng1/2, 26/10/2026
Trạng thái: **Chờ Claude soát vòng2**; nhánh `codex/thanh-toan-web`.
- Chỉ sửa mục5 theo phiếu `sua-sau-soat-26-10.md`: giới hạn câu “ngoàiGoogle” cho ứng dụngAndroid.
- Thêm rõ SePay (nhận báo chuyển khoản), Cloudflare (máy chủ), Supabase (DBđơn) cho thanh toánweb và dẫn mục4c.
- Đối chiếu với3cd8c30 sau khi bỏ đúng hai thay đổi trên, chuẩn hoáCRLF/LF: toàn bộ phần khác giống nguyên văn.
- Ảnh mục5/ cuối trang ở360×640 và1280×900 tại `vong-2/`; không tràn ngang, console không lỗi.
- Nội dung app/thanh toánGoogle không đổi ý nghĩa; không sửa code game/app.
- `git diff --check` đạt; chỉ commit cục bộ, chưa push/đăng.
## Giải thích cho Thảo
`day-tro-cua-toi.html` (chính sách): phân biệt nhà cung cấp của app và web, hết mâu thuẫn giữa mục5và4c.
Các ảnh/báo cáo kiểm tra: bằng chứng đọc trên điện thoại/máy tính.
Rủi ro nếu có lỗi: người mua hiểu sai bên xử lý dữ liệu; Claude cần đọc lần cuối trước khi Thảo đăng.