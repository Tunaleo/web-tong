# Trang Web Nhóm 1 - Sinh viên UTH

## Mô Tả
Trang web tổng hiện đại để giới thiệu và dẫn tới các trang CV của 4 thành viên trong nhóm 1 - Sinh viên năm 2 ngành Công nghệ thông tin tại Đại học Giao thông Vận tải TP.HCM (UTH). Thiết kế chuyên nghiệp với giao diện đẹp mắt và hiệu ứng mượt mà, phù hợp với sinh viên đang học tập và phát triển.

## Tính Năng Chính

### 🎨 Thiết Kế Hiện Đại & Chuyên Nghiệp
- Color scheme chuyên nghiệp với tông màu xanh (#007bff) tạo cảm giác tin cậy
- Responsive design hoạt động mượt mà trên mọi thiết bị
- Animations và transitions được tối ưu hóa
- Glass morphism effects cho header với backdrop blur
- Typography hierarchy rõ ràng với Inter và Poppins fonts

### 🚀 Hiệu Ứng Tương Tác Nâng Cao
- Loading screen với spinner animation 3 vòng tròn
- Parallax scrolling effects với floating shapes
- Hover effects tinh tế cho member cards với overlay
- Smooth scroll navigation với scroll indicator
- Counter animations cho statistics
- Floating label forms với focus states
- 3D transform effects cho code card

### 📱 Responsive Design Tối Ưu
- Mobile-first approach
- Breakpoints: 480px, 768px, 1024px
- Adaptive layouts cho tất cả screen sizes
- Touch-friendly interactions
- Hamburger menu cho mobile
- Optimized typography scaling

### ⚡ Performance & UX
- Optimized images và assets
- Smooth 60fps animations với hardware acceleration
- Lazy loading cho images
- Semantic HTML structure
- Accessibility features
- SEO optimized

## Nội Dung Phù Hợp Sinh Viên

### 🎓 Thông Tin Học Tập
- Giới thiệu về sinh viên năm 2 UTH
- Các lĩnh vực học tập: Lập trình cơ bản, Cấu trúc dữ liệu, Web development
- Thống kê phù hợp: 4 thành viên, 3 dự án nhỏ, 2 năm học, 100% nhiệt huyết
- Mô tả hành trình học tập và khám phá công nghệ

### 👥 Thành Viên Nhóm
- **Thành viên 1**: Lập trình Web (HTML, CSS, JavaScript)
- **Thành viên 2**: Lập trình Backend (Python, Java, SQL)
- **Thành viên 3**: Mạng máy tính (TCP/IP, Security, Linux)
- **Thành viên 4**: Phân tích dữ liệu (SQL, Thống kê, Excel)

## Cấu Trúc File

```
team-website/
├── index.html              # File HTML chính (đã cập nhật cho sinh viên UTH)
├── css/
│   └── style.css           # File CSS cải thiện (chuyên nghiệp hơn)
├── js/
│   └── main.js             # File JavaScript với tất cả interactions
├── images/
│   ├── members/            # Hình ảnh thành viên
│   │   ├── member1.jpg
│   │   ├── member2.jpg
│   │   ├── member3.jpg
│   │   └── member4.jpg
│   └── backgrounds/        # Background images (nếu có)
├── assets/
│   ├── icons/              # Icons và favicons
│   └── fonts/              # Custom fonts (nếu có)
└── README.md               # Hướng dẫn chi tiết
```

## Cải Tiến CSS Mới

### 🎨 Visual Improvements
- **Color Palette**: Chuyển sang #007bff (professional blue) thay vì #02a9f7
- **Typography**: Tăng font sizes và line heights cho dễ đọc hơn
- **Spacing**: Tăng padding và margins cho layout thoáng hơn
- **Border Radius**: Điều chỉnh để trông hiện đại hơn
- **Shadows**: Tối ưu hóa shadows cho depth tốt hơn

### ⚡ Animation Enhancements
- **Loading Spinner**: 3 vòng tròn với cubic-bezier easing
- **Hover Effects**: Lift effects mạnh hơn (translateY -12px)
- **Transitions**: Smooth ease-out transitions
- **3D Effects**: Enhanced perspective transforms
- **Floating Shapes**: Slower, more elegant animations

### 📱 Responsive Improvements
- **Mobile Navigation**: Improved hamburger menu
- **Grid Layouts**: Auto-fit grids cho flexibility
- **Typography Scaling**: Better clamp() functions
- **Touch Targets**: Larger interactive elements
- **Form Inputs**: Enhanced focus states

## Hướng Dẫn Sử Dụng

### 1. Mở Trang Web
- Mở file `index.html` trong trình duyệt web
- Hoặc host trên web server để truy cập online

### 2. Cập Nhật Thông Tin Thành Viên
Để thay đổi thông tin các thành viên, chỉnh sửa trong file `index.html`:

```html
<!-- Tìm section với class="members-grid" -->
<div class="member-card">
    <div class="member-image">
        <img src="images/members/member1.jpg" alt="Tên thành viên">
    </div>
    <div class="member-info">
        <h3 class="member-name">Tên Thành Viên</h3>
        <p class="member-role">Sinh viên năm 2 - Chuyên môn</p>
        <p class="member-description">Mô tả ngắn gọn về sở thích và học tập</p>
        <div class="member-skills">
            <span class="skill-tag">Skill 1</span>
            <span class="skill-tag">Skill 2</span>
        </div>
        <a href="LINK_TO_CV" class="member-cv-link btn btn-outline">
            <span>Xem CV</span>
            <i class="btn-icon">→</i>
        </a>
    </div>
</div>
```

### 3. Thêm Link CV
Thay thế `href="#"` trong các button "Xem CV" bằng link thực tế tới CV của từng thành viên:

```html
<a href="https://link-to-member-cv.com" class="member-cv-link btn btn-outline">
```

### 4. Cập Nhật Thông Tin Liên Hệ
Chỉnh sửa thông tin liên hệ trong section Contact:

```html
<!-- Email -->
<p>team1.uth@example.com</p>

<!-- Điện thoại -->
<p>+84 9xx xxx xxx</p>

<!-- Địa chỉ -->
<p>Đại học Giao thông Vận tải TP.HCM</p>
```

### 5. Thay Đổi Hình Ảnh
- Thay thế các file trong `images/members/` bằng hình ảnh thật của thành viên
- Đảm bảo tỷ lệ khung hình phù hợp (khuyến nghị: 1:1 hoặc 4:3)
- Format khuyến nghị: JPG hoặc WebP
- Kích thước khuyến nghị: 400x400px hoặc lớn hơn

## Tùy Chỉnh Màu Sắc

Để thay đổi color scheme, chỉnh sửa CSS variables trong file `css/style.css`:

```css
:root {
    --primary-color: #007bff;          /* Màu chính - Professional Blue */
    --primary-dark: #0056b3;           /* Màu tối */
    --primary-light: #66b2ff;          /* Màu sáng */
    --accent-dark: #2c3e50;            /* Màu accent - Dark Blue Gray */
    /* ... các màu khác */
}
```

## Browser Support
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- Mobile browsers (iOS Safari, Chrome Mobile)

## Deployment

### Option 1: Static Hosting
- Upload toàn bộ thư mục lên static hosting service
- Ví dụ: Netlify, Vercel, GitHub Pages

### Option 2: Web Server
- Upload files lên web server
- Đảm bảo server hỗ trợ static files

### Option 3: Local Development
- Sử dụng local server để test:
```bash
# Python
python -m http.server 8000

# Node.js
npx serve .

# PHP
php -S localhost:8000
```

## Troubleshooting

### Vấn Đề Thường Gặp

1. **Hình ảnh không hiển thị**
   - Kiểm tra đường dẫn file
   - Đảm bảo file tồn tại trong thư mục đúng

2. **Animations không mượt**
   - Kiểm tra performance của browser
   - Disable animations nếu cần thiết

3. **Layout bị lỗi trên mobile**
   - Kiểm tra viewport meta tag
   - Test trên nhiều thiết bị khác nhau

4. **Form không hoạt động**
   - Hiện tại form chỉ có demo functionality
   - Cần integrate với backend để xử lý form submission

## Customization Tips

### Thêm Thành Viên Mới
1. Copy một member card existing
2. Thay đổi thông tin và hình ảnh
3. Cập nhật CSS grid nếu cần (hiện tại: auto-fit)

### Thay Đổi Layout
- Chỉnh sửa CSS Grid trong `.members-grid`
- Responsive breakpoints có thể điều chỉnh

### Thêm Sections Mới
1. Thêm HTML structure
2. Thêm CSS styling
3. Cập nhật navigation menu
4. Thêm scroll animations nếu cần

## Performance Tips
- Optimize images trước khi upload
- Sử dụng WebP format cho images
- Minify CSS/JS cho production
- Enable gzip compression trên server

## Changelog

### Version 2.0 (Current)
- ✅ Cập nhật nội dung cho sinh viên năm 2 UTH
- ✅ Cải thiện CSS với color scheme chuyên nghiệp hơn
- ✅ Tối ưu hóa typography và spacing
- ✅ Enhanced animations và transitions
- ✅ Improved responsive design
- ✅ Better accessibility và UX

### Version 1.0
- ✅ Initial release với IT Professionals theme
- ✅ Basic responsive design
- ✅ Core animations và interactions

## Credits
- Fonts: Google Fonts (Inter, Poppins)
- Icons: Emoji icons (có thể thay bằng Font Awesome)
- Images: Professional stock photos (thay bằng hình thật)
- Design: Modern web design principles

## License
Free to use và customize theo nhu cầu của nhóm sinh viên UTH.

---

**Lưu ý**: Đây là phiên bản đã được cải thiện dành riêng cho sinh viên năm 2 UTH. Nội dung và thiết kế đã được điều chỉnh để phù hợp với bối cảnh học tập và phát triển của sinh viên.

