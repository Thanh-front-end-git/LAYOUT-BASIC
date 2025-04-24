# 🌐 Layout Basic - HTML & CSS

## 📝 Giới thiệu
Dự án xây dựng giao diện tĩnh sử dụng **HTML** và **CSS cơ bản**, nhằm rèn luyện kỹ năng bố cục với kỹ thuật **float layout**.

> 🎯 Mục tiêu: Làm quen với thẻ HTML cơ bản, định dạng CSS, và kỹ thuật `float` trong bố cục giao diện.

---

## 🧱 Công nghệ sử dụng

- HTML5
- CSS3

---

## 🧠 Kiến thức áp dụng

### 🔸 HTML
- Thẻ tiêu đề: `h1`, `h2`, `h3`
- Thẻ liên kết: `<a href="">`
- Thẻ phân vùng: `<div>`
- Thẻ gạch ngang: `<hr>`
- Hình ảnh: `<img src="" alt="">`
- Danh sách không thứ tự: `<ul>`, `<li>`
- Đoạn văn: `<p>`

### 🔹 CSS
- **Text:** `text-decoration`, `color`, `text-align`
- **Font:** `font-size`, `font-weight`
- **Hiển thị:** `display: block`, `inline`, `inline-block`
- **Nền:** `background-color`, `background-image`

---

## 📐 Kỹ thuật Float

### 🔧 Float là gì?
`float` giúp đẩy phần tử sang trái (`left`) hoặc phải (`right`), từ đó sắp xếp các phần tử nằm ngang nhau.

### ⚠️ Lưu ý khi dùng float
- Các phần tử sau phần tử `float` có thể bị trôi theo nếu không xử lý đúng.
- Khi chiều cao các phần tử khác nhau, bố cục dễ bị lệch.

### ✅ Cách xử lý (Clear Float)
Đặt một phần tử có `clear: both;` sau cùng để "dọn dẹp" bố cục.

```html
<div style="clear: both;"></div>
