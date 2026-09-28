# 🎨 BẢN ĐẶC TẢ THIẾT KẾ GIAO DIỆN UI/UX TRÊN FIGMA

> 👤 **Học viên:** Đỗ Hoàng Sơn | **Mã SV:** PTIT-HCM-066
> 🏫 **Môn học:** IT105-K25-Phan-tich-thi-t-k-h-th-ng
> 📌 **Bài tập:** Bài 1 - Session 19
> 🏷️ **Dự án thiết kế:** RikkeiFastMart Order UI Design

---

## 🔗 LIÊN KẾT TRỰC TIẾP DỰ ÁN FIGMA

[![Figma Design Canvas](https://img.shields.io/badge/Figma-Design%20Canvas-F24E1E?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/design/Ky3qg5jiUdh9vxeehnIkBS/mini-project-phan-tich-thiet-ke-luo?node-id=0%3A1&m=dev)
[![Figma Live Prototype](https://img.shields.io/badge/Figma-Interactive%20Prototype-1ABCFE?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/proto/Ky3qg5jiUdh9vxeehnIkBS/mini-project-phan-tich-thiet-ke-luo?page-id=0%3A1&node-id=1%3A2&viewport=256%2C48%2C0.5&scaling=scale-down&starting-point-node-id=1%3A2)

- 🎨 **Figma Design Canvas (Artboards, Styles & Design Tokens):**  
  👉 [https://www.figma.com/design/Ky3qg5jiUdh9vxeehnIkBS/mini-project-phan-tich-thiet-ke-luo?node-id=0%3A1&m=dev](https://www.figma.com/design/Ky3qg5jiUdh9vxeehnIkBS/mini-project-phan-tich-thiet-ke-luo?node-id=0%3A1&m=dev)
- 🚀 **Figma Interactive Prototype (Trải nghiệm tương tác luồng người dùng):**  
  👉 [https://www.figma.com/proto/Ky3qg5jiUdh9vxeehnIkBS/mini-project-phan-tich-thiet-ke-luo?page-id=0%3A1&node-id=1%3A2&viewport=256%2C48%2C0.5&scaling=scale-down&starting-point-node-id=1%3A2](https://www.figma.com/proto/Ky3qg5jiUdh9vxeehnIkBS/mini-project-phan-tich-thiet-ke-luo?page-id=0%3A1&node-id=1%3A2&viewport=256%2C48%2C0.5&scaling=scale-down&starting-point-node-id=1%3A2)

---

## 🎯 1. HỆ THỐNG THIẾT KẾ (DESIGN SYSTEM & TOKENS)

### 🎨 Bảng mã màu chuẩn (Color Palette)

| Tên Token | Mã HEX | Vai trò & Ứng dụng |
| :--- | :---: | :--- |
| Primary | `#E11D48` | Nút đặt hàng |
| Background | `#F9FAFB` | Nền ứng dụng |
| Text | `#111827` | Văn bản chính |

### ✍️ Quy chuẩn Typography & Font chữ

- **Font Family:** `Inter`, `Roboto`, `system-ui` (Độ rõ nét cao trên mọi màn hình).
- **H1 (Header chính màn hình):** 24px - Bold (700) - Line height 32px.
- **H2 (Tiêu đề phân đoạn / Block header):** 18px - SemiBold (600) - Line height 24px.
- **Body Text (Nội dung văn bản):** 14px - Regular (400) - Line height 20px.
- **Caption & Footnote:** 12px - Medium (500) - Line height 16px.

### 📐 Hệ thống Lưới & Khoảng cách (Grid & Spacing)

- **Quy tắc 8-Point Grid:** Toàn bộ khoảng cách lề (margin), khoảng cách đệm (padding) tuân thủ bội số của 8 (8px, 16px, 24px, 32px, 48px).
- **Bố cục Layout Grid:** Mobile 4 cột (Margin 16px, Gutter 16px) hoặc Web Responsive 12 cột (Max-width 1200px, Gutter 24px).

---

## 📱 2. SƠ ĐỒ LUỒNG ĐIỀU HƯỚNG GIAO DIỆN (UI FLOW)

```mermaid
graph LR
  Login --> ProductList --> Cart --> OrderSuccess
```

---

## 📐 3. ĐẶC TẢ CHI TIẾT CÁC MÀN HÌNH WIREFRAME

### 📱 Màn hình Giỏ hàng

> 💡 **Mục đích:** Hiển thị danh sách sản phẩm đã chọn

**Các thành phần UI chính:**
- 🔹 Danh sách sản phẩm
- 🔹 Input mã giảm giá
- 🔹 Nút Đặt hàng

**Bố cục Wireframe & Phân vùng màn hình:**
```text
Header -> List Items -> Discount Section -> Checkout Button
```

---

## 🛠️ 4. HƯỚNG DẪN XEM VÀ KIỂM TRA TRÊN FIGMA

1. **Chế độ xem Thiết kế (Design Canvas):** Nhấp vào link [Figma Design Canvas](https://www.figma.com/design/Ky3qg5jiUdh9vxeehnIkBS/mini-project-phan-tich-thiet-ke-luo?node-id=0%3A1&m=dev) để xem toàn bộ hệ thống Artboard, phân lớp Layer, Auto-layout và các Components.
2. **Chế độ chạy thử nghiệm (Interactive Prototype):** Nhấp vào link [Figma Live Prototype](https://www.figma.com/proto/Ky3qg5jiUdh9vxeehnIkBS/mini-project-phan-tich-thiet-ke-luo?page-id=0%3A1&node-id=1%3A2&viewport=256%2C48%2C0.5&scaling=scale-down&starting-point-node-id=1%3A2) để trực tiếp click thử nghiệm các tương tác chuyển trang, hiệu ứng Smart Animate và luồng thao tác người dùng.
