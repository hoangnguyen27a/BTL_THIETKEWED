# AI_LOG – Nhật ký sử dụng AI trong dự án BTL_WED

> **Dự án:** Trang web CLB Kết Nối  
> **Sinh viên:** Nguyễn Huy Hoàng  
> **Công cụ AI sử dụng:** Google Antigravity (Gemini / Claude Sonnet)  
> **Mục đích ghi log:** Minh bạch về việc sử dụng AI trong quá trình làm bài tập lớn

---

## Tổng quan

| Mục | Chi tiết |
|---|---|
| Tỉ lệ code tự viết | ~20% (cấu trúc ban đầu, nội dung CLB) |
| Tỉ lệ AI hỗ trợ | ~80% (refactor CSS, thêm tính năng, giải thích code) |
| Mọi nội dung CLB | 100% thật (tên, email, SĐT, hoạt động) |

---

## Phiên 1 – 13/11/2026

**Yêu cầu gửi AI:**
> "Tôi muốn phần style.css code phải đơn giản dễ hiểu bằng những ngôn ngữ của người mới bắt đầu những vẫn có đầy đủ những phần của nó"

**AI đã làm:**
- Chia `style.css` thành 15 phần có tiêu đề rõ ràng bằng tiếng Việt
- Đổi tên biến CSS từ `--xanh`, `--vang` → `--mau-xanh`, `--mau-vang` (dễ hiểu hơn)
- Thêm comment tiếng Việt giải thích từng thuộc tính khó

**File thay đổi:** `style.css`  
**Sinh viên kiểm tra:** Đọc lại từng phần, xác nhận đúng giao diện không đổi ✅

---

## Phiên 2 – 13/11/2026

**Yêu cầu gửi AI:**
> "Tôi muốn phần index.html trong phần tuyển thành viên khi ấn vào đăng ký tham gia ngay thì mọi người có thể điền thông tin... và phần thêm một phần... tôi là người quản trị web này tôi là nguyễn huy hoàng... ở phần cơ cấu tổ chức sửa... tên chủ nhiệm và phó chủ nhiệm phải rõ ràng hơn nổi bật... viết lại phần index.html một cách cơ bản và dễ hiểu"

**AI đã làm:**
- Thêm form đăng ký HTML trực tiếp trong section `#tuyen-thanh-vien`
- Thêm JavaScript xử lý form (kiểm tra dữ liệu, hiện thông báo thành công)
- Thêm thông tin quản trị web (Nguyễn Huy Hoàng) vào footer
- Làm nổi bật tên Chủ nhiệm (nền vàng, 1.5rem) và Phó chủ nhiệm (nền xanh, 1.25rem)
- Viết lại `index.html` với comment tiếng Việt đầy đủ, chia section rõ ràng
- Cập nhật `style.css` thêm phần 11 (Form đăng ký), phần admin info

**File thay đổi:** `index.html`, `style.css`  
**Sinh viên kiểm tra:** Mở trình duyệt, thử điền form → thông báo thành công hiện đúng ✅

---

## Phiên 3 – 14/11/2026

**Yêu cầu gửi AI:**
> "Tôi muốn cho lên GitHub và commit... hướng làm tiếp theo cho phần 4, 5, 6, 7"

**AI đã làm:**
- Viết `README.md` hoàn chỉnh với hướng dẫn chạy, cấu trúc, tính năng, giới hạn
- Viết `AI_LOG.md` ghi lại toàn bộ quá trình dùng AI
- Tạo commit đầu tiên trên git
- Hướng dẫn push lên GitHub Pages

**File thay đổi:** `README.md`, `AI_LOG.md`

---

## Khai báo trách nhiệm

- **Nội dung CLB** (tên, email, hoạt động, lịch): Do sinh viên cung cấp từ thực tế
- **Logo:** Tài sản của CLB Kết Nối – VNUA
- **Code HTML/CSS/JS:** AI viết theo yêu cầu, sinh viên đọc hiểu và kiểm tra
- **Quyết định thiết kế** (màu xanh-vàng, bố cục, cơ cấu): Do sinh viên định hướng
- **AI không tự thêm nội dung** ngoài yêu cầu của sinh viên
