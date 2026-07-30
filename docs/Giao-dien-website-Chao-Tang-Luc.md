# SPEC GIAO DIỆN WEBSITE — CHÁO TĂNG LỰC "ĂN LÀ KHOẺ"
*File này tổ chức nội dung theo từng trang (page) → từng khối (section) → loại component gợi ý, để designer/dev dựng giao diện trực tiếp. Nội dung copy đầy đủ, chi tiết (toàn bộ bảng chi phí, FAQ...) tham khảo thêm file "Nội dung website Cháo Tăng Lực".*

---

## SITEMAP

| Trang | Đường dẫn gợi ý |
|---|---|
| Trang chủ | `/` |
| Giới thiệu | `/gioi-thieu` |
| Nhượng quyền | `/nhuong-quyen` |
| Menu | `/menu` |
| Blog | `/blog` |
| Liên hệ | `/lien-he` |
| Tuyển dụng | `/tuyen-dung` |
| Đặt đơn hàng lớn | `/dat-hang-lon` |

---

## COMPONENT TOÀN CỤC (GLOBAL)

### Header — Main Navigation
Component: `Sticky top navbar` (logo trái, menu giữa/phải, nút CTA nổi bật bên phải)

- Logo: CHÁO TĂNG LỰC
- Menu chính:
  1. **Về Cháo Tăng Lực** *(dropdown)* → Giới thiệu, Câu chuyện thương hiệu, Đội ngũ/Nhà sáng lập, Giải thưởng, Hình ảnh & video, Kinh tế vỉa hè, Bài viết chia sẻ, Bài viết từ AI
  2. **Cửa hàng Cháo Tăng Lực** *(dropdown)* → Trọn gói cửa hàng, Combo nguyên liệu, Các loại cháo tăng lực, Lẩu cháo
  3. **Hợp tác nhượng quyền** *(dropdown)* → Các gói đầu tư, Quyền lợi đối tác, Quy trình hợp tác, Chính sách bảo chứng, Bằng chứng xã hội, FAQ, Pháp lý & uy tín, Ưu đãi
  4. **Menu** (link thẳng đến `/menu`)
  5. **Liên hệ**
  6. **Tuyển dụng**
  7. **Đặt đơn hàng lớn**
- Nút CTA: `Đăng ký tư vấn` (màu nổi bật, luôn hiển thị)

### Top bar (Utility Menu)
Component: `Thin bar phía trên header`
- Trái: Hotline `[SĐT]` — Giờ làm việc `[08:00–21:00]`
- Phải: Icon giỏ hàng *(nếu có bán online)*, icon mạng xã hội (Facebook/Zalo)

### Footer
Component: `4-column footer + bottom bar`
- Cột 1: Logo + mô tả ngắn thương hiệu + mạng xã hội
- Cột 2 (Về chúng tôi): Giới thiệu, Câu chuyện thương hiệu, Đội ngũ, Tuyển dụng
- Cột 3 (Chính sách): Chính sách nhượng quyền, Chính sách & quy định chung, Chính sách bảo mật, Chính sách giao hàng, Chính sách thanh toán
- Cột 4 (Liên hệ nhanh): Địa chỉ, Hotline, Email, Form mini đăng ký tư vấn
- Bottom bar: © CHÁO TĂNG LỰC — [Năm]. Giấy phép kinh doanh số [...]

### Floating / Sticky buttons
Component: `Floating action buttons, góc dưới phải`
- Chat Zalo · Gọi điện · Messenger · SMS

---

## TRANG 1 — TRANG CHỦ (`/`)

### Section 1: Hero banner
Component: `Full-width hero image/video + headline + CTA`
- Headline: **CHÁO TĂNG LỰC — ĂN LÀ KHOẺ**
- Subheadline: *Một bát cháo nóng, một ngày tràn năng lượng.*
- CTA button: `Đăng ký tư vấn nhượng quyền` + `Xem thực đơn`

### Section 2: Giới thiệu ngắn / Câu chuyện thương hiệu
Component: `2-column: ảnh trái - text phải`
- Nội dung: đoạn giới thiệu ngắn (rút gọn từ câu chuyện thương hiệu), kèm nút "Tìm hiểu thêm" → `/gioi-thieu`

### Section 3: Giá trị cốt lõi
Component: `3-column icon cards`
1. Dinh dưỡng thật
2. Tăng lực tức thì
3. Gần gũi, dân dã

### Section 4: 2 gói nhượng quyền (tóm tắt)
Component: `2 pricing cards side-by-side`
- Card 1 — Gói CƠ BẢN: dưới 50tr, dưới 50m², cháo tăng lực
- Card 2 — Gói TIÊU CHUẨN: dưới 100tr, 50–100m², cháo tăng lực + lẩu cháo
- Mỗi card có nút `Xem chi tiết` → `/nhuong-quyen`

### Section 5: Thực đơn nổi bật
Component: `Card slider/carousel` (ảnh món + tên + giá), kéo ngang trên mobile
- Lấy 4–6 món tiêu biểu từ menu (cháo thập cẩm, lẩu cháo, v.v.)
- Nút `Xem toàn bộ menu` → `/menu`

### Section 6: Bằng chứng xã hội (số liệu nhanh)
Component: `Stat counter row` (4 số liệu chạy số)
- Số cửa hàng đang hoạt động: `[X]`
- Số năm thành lập: `[X]`
- Số đối tác nhượng quyền: `[X]`
- Tỷ lệ đối tác hài lòng: `[X]%`

### Section 7: Feedback đối tác
Component: `Testimonial carousel` (avatar, tên, khu vực, trích dẫn ngắn, video nếu có)

### Section 8: Blog / Bài viết mới nhất
Component: `3-column blog cards` (ảnh, tiêu đề, ngày đăng)

### Section 9: CTA cuối trang
Component: `Full-width banner CTA`
- "Ăn là khoẻ, bán là lời — Đăng ký tư vấn miễn phí ngay hôm nay!"
- Form mini: Họ tên / SĐT / Nút gửi

---

## TRANG 2 — GIỚI THIỆU (`/gioi-thieu`)

### Section 1: Câu chuyện thương hiệu
Component: `Long-form text + ảnh minh hoạ xen kẽ`
Nội dung đầy đủ câu chuyện thương hiệu (xem file nội dung gốc, mục 1)

### Section 2: Đội ngũ / Nhà sáng lập
Component: `Profile card` (ảnh chân dung + tên + vai trò + trích dẫn cá nhân)

### Section 3: Giải thưởng / Chứng nhận
Component: `Logo/badge grid`

### Section 4: Gallery hình ảnh & video
Component: `Masonry image grid` + `Video embed`

### Section 5: Kinh tế vỉa hè & mặt bằng nhỏ
Component: `Text block + infographic`

---

## TRANG 3 — NHƯỢNG QUYỀN (`/nhuong-quyen`)

### Section 1: Hero mini
Component: `Banner ngắn` — "Đầu tư nhỏ — Vận hành dễ — Thu hồi vốn nhanh"

### Section 2: So sánh 2 gói đầu tư
Component: `Comparison table` (responsive → chuyển thành card trên mobile)
Cột: Vốn / Diện tích / Loại hình / Thực đơn / Lợi nhuận / Hoàn vốn / Triển khai
*(dữ liệu đầy đủ: xem file nội dung gốc, mục 2)*

### Section 3: Chi phí chi tiết từng gói
Component: `Tabs hoặc Accordion` (Tab 1: Gói Cơ Bản — Tab 2: Gói Tiêu Chuẩn), mỗi tab là 1 bảng chi phí hạng mục
⚠️ Kèm lưu ý: chi phí chưa gồm tiền thuê mặt bằng

### Section 4: 8 quyền lợi đối tác
Component: `Icon grid 4x2` (mỗi ô: icon + tiêu đề + mô tả ngắn)

### Section 5: Quy trình hợp tác
Component: `Horizontal step timeline (3 bước)` — Tìm hiểu → Ký hợp đồng → Triển khai

### Section 6: Chính sách bảo chứng
Component: `Highlight box màu nhấn` (icon shield + nội dung cam kết)

### Section 7: Bằng chứng xã hội
Component: `Case study cards` + `Map hệ thống cửa hàng` (Google Maps embed)

### Section 8: FAQ
Component: `Accordion FAQ` (6 câu hỏi, mở rộng/thu gọn)

### Section 9: Pháp lý & uy tín
Component: `List + download button` (giấy phép, VSATTP, chính sách nhượng quyền PDF, hợp đồng mẫu)

### Section 10: Ưu đãi hiện có
Component: `Promo banner`

### Section 11: Form đăng ký tư vấn (chốt trang)
Component: `Form full-width, nổi bật`
Trường: Họ tên · Số điện thoại · Khu vực dự kiến · Nguồn vốn dự kiến · Tình trạng mặt bằng (dropdown: đã có/đang tìm) · Nút gửi

---

## TRANG 4 — MENU (`/menu`)

### Section 1: Tabs thực đơn
Component: `Tab switcher` — Cháo tăng lực | Lẩu cháo | Món ăn kèm | Thức uống
Mỗi tab: `Grid card` (ảnh món, tên, mô tả ngắn, giá)
*(dữ liệu đầy đủ: xem file nội dung gốc, mục 6)*

### Section 2: Ghi chú
Component: `Text nhỏ dưới trang`
- Giá tham khảo, có thể thay đổi theo khu vực
- Lẩu cháo chỉ có tại điểm bán Gói Tiêu Chuẩn

---

## TRANG 5 — BLOG (`/blog`)

### Section 1: Danh sách bài viết
Component: `Grid card list + phân trang` (ảnh, chuyên mục, tiêu đề, ngày, mô tả ngắn)

### Chuyên mục gợi ý
- Kinh tế vỉa hè
- Kinh nghiệm nhượng quyền
- Chia sẻ từ đối tác
- Bài viết từ AI

---

## TRANG 6 — LIÊN HỆ (`/lien-he`)

### Section 1: Thông tin liên hệ + Bản đồ
Component: `2-column: thông tin trái - Google Map phải`
- Địa chỉ, Hotline, Email, Giờ làm việc, Mạng xã hội

### Section 2: Form liên hệ
Component: `Form` — Họ tên · SĐT · Email · Nội dung · Nút gửi

---

## TRANG 7 — TUYỂN DỤNG (`/tuyen-dung`)

### Section 1: Danh sách vị trí đang tuyển
Component: `Job listing cards` (nhóm theo Cửa hàng / Văn phòng thương hiệu)
Mỗi card: Tên vị trí, mô tả ngắn, mức lương tham khảo, nút `Ứng tuyển ngay`

### Section 2: Form ứng tuyển
Component: `Form` — Họ tên · SĐT · Vị trí ứng tuyển (dropdown) · Upload CV · Nút gửi

---

## TRANG 8 — ĐẶT ĐƠN HÀNG LỚN (`/dat-hang-lon`)

### Section 1: Giới thiệu dịch vụ
Component: `Banner + text` — Đặt tiệc/sự kiện, đặt lẩu cháo theo nhóm, giá sỉ

### Section 2: Form đặt hàng
Component: `Form` — Họ tên · SĐT · Số lượng · Thời gian giao/phục vụ · Địa điểm · Ghi chú

---

## GHI CHÚ CHO DEV/DESIGNER

- Responsive: tất cả bảng (comparison table, cost table) cần có phiên bản **card/accordion** khi hiển thị trên mobile.
- Màu sắc chủ đạo & typography: chưa quy định trong tài liệu này — cần bổ sung theo bộ nhận diện thương hiệu (logo, màu, font) khi có.
- Toàn bộ nội dung copy chi tiết (bảng giá đầy đủ, FAQ, nội dung từng section) tham khảo file **"Nội dung website Cháo Tăng Lực"** đã cung cấp trước đó — file này chỉ mô tả cấu trúc & loại component để dựng UI.
