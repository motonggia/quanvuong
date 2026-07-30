````markdown
# PROJECT.md
# Kiến trúc hệ thống Website Quán Vuông

> Dự án: **CHÁO SỨC KHOẺ - ĂN LÀ KHOẺ**
>
> Mục tiêu:
> Website giới thiệu thương hiệu, menu, nhượng quyền và chuyển đổi khách hàng thành người mua hoặc đối tác.

---

# 1. Kiến trúc tổng thể

```
Internet
     │
     ▼
index.html
     │
 ┌───┼───────────────┬──────────────┬──────────────┐
 ▼   ▼               ▼              ▼              ▼
menu.html    gioi-thieu.html   nhuong-quyen.html  lien-he.html
```

Toàn bộ website sử dụng:

- HTML5
- CSS thuần
- JavaScript thuần
- Không dùng framework
- Không dùng database
- Không cần Backend

Website hoạt động như một Landing Website đa trang (Multi Page Website).

---

# 2. Cấu trúc thư mục

```
/
│
├── index.html
├── menu.html
├── gioi-thieu.html
├── nhuong-quyen.html
├── lien-he.html
│
├── assets/
│   ├── css/
│   ├── js/
│   ├── img/
│   ├── icons/
│   └── fonts/
│
├── README.md
├── PROJECT.md
└── LICENSE
```

---

# 3. Vai trò từng trang

## Trang chủ

```
index.html
```

Chức năng

- Giới thiệu thương hiệu
- Hero Banner
- USP
- Menu nổi bật
- Câu chuyện thương hiệu
- CTA
- Điều hướng toàn website

Đây là trang quan trọng nhất.

---

## Menu

```
menu.html
```

Hiển thị

- Danh sách món ăn
- Giá bán
- Hình ảnh
- Mô tả
- Combo

Có thể mở rộng sau này thành Menu Online.

---

## Giới thiệu

```
gioi-thieu.html
```

Hiển thị

- Lịch sử thương hiệu
- Giá trị cốt lõi
- Sứ mệnh
- Tầm nhìn
- Đội ngũ
- Hành trình phát triển

---

## Nhượng quyền

```
nhuong-quyen.html
```

Trang chuyển đổi đối tác.

Bao gồm

- Lợi ích
- Quy trình
- Chi phí
- Chính sách
- Form đăng ký

---

## Liên hệ

```
lien-he.html
```

Bao gồm

- Thông tin liên hệ
- Google Map
- Hotline
- Email
- Form liên hệ

---

# 4. Header

Header xuất hiện trên toàn bộ website.

```
Logo

Trang chủ

Menu

Giới thiệu

Nhượng quyền

Liên hệ

Đặt món

Đăng ký nhượng quyền
```

Header:

- Sticky
- Responsive
- Mobile Menu

---

# 5. Footer

Footer dùng chung.

Bao gồm

- Logo
- Thông tin công ty
- Hotline
- Email
- Facebook
- Zalo
- Copyright
- Menu nhanh

---

# 6. Thiết kế

Toàn bộ website sử dụng chung:

## Font

Montserrat

Saira

---

## Màu sắc

Primary

```
#C79A4B
```

Primary Hover

```
#A67C3D
```

Accent

```
#D6191F
```

Text

```
#4A4A4A
```

Background

```
#F2F1ED
```

---

# 7. Responsive

Website hỗ trợ

Desktop

```
>=1200px
```

Laptop

```
992px
```

Tablet

```
768px
```

Mobile

```
480px
```

---

# 8. Thành phần dùng chung

Website tái sử dụng các Component sau:

- Header
- Footer
- Hero
- Button
- Card
- Badge
- Food Card
- Form
- CTA
- Navigation
- Statistics
- Gallery
- Timeline

---

# 9. Hệ thống điều hướng

```
Trang chủ
     │
     ├────────► Menu
     │
     ├────────► Giới thiệu
     │
     ├────────► Nhượng quyền
     │
     └────────► Liên hệ
```

Người dùng luôn có thể quay về Trang chủ.

---

# 10. Luồng khách hàng

## Khách mua cháo

```
Google

↓

Trang chủ

↓

Menu

↓

Liên hệ

↓

Đặt món
```

---

## Đối tác

```
Google

↓

Trang chủ

↓

Nhượng quyền

↓

Điền Form

↓

Tư vấn

↓

Ký hợp đồng
```

---

# 11. Mở rộng tương lai

Có thể bổ sung:

- Blog
- Tin tức
- Tuyển dụng
- Cửa hàng
- Đặt hàng Online
- Thanh toán Online
- Đăng nhập thành viên
- Quản trị Menu
- CMS
- API
- Chat AI
- CRM
- Dashboard

---

# 12. Kiến trúc phát triển

Giai đoạn 1

Website giới thiệu.

↓

Giai đoạn 2

Website bán hàng.

↓

Giai đoạn 3

Hệ thống nhượng quyền.

↓

Giai đoạn 4

Quản trị chuỗi cửa hàng.

↓

Giai đoạn 5

Hệ sinh thái Quán Vuông.

---

# 13. Nguyên tắc phát triển

- Giao diện đồng nhất.
- Mã nguồn đơn giản.
- Dễ bảo trì.
- Dễ mở rộng.
- Chuẩn SEO.
- Responsive.
- Tối ưu tốc độ tải.
- Ưu tiên trải nghiệm người dùng.
````
