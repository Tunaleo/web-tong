# Concept Thiết Kế - Trang Web Nhóm 1

## Tổng Quan Dự Án
**Mục tiêu**: Tạo trang web tổng hiện đại để dẫn tới các trang CV của 4 thành viên trong nhóm 1
**Đối tượng**: Nhà tuyển dụng, đối tác, khách hàng tiềm năng trong lĩnh vực IT
**Phong cách**: Hiện đại, chuyên nghiệp, tương tác cao

## Xu Hướng Thiết Kế 2024-2025

### 1. Denser, Richer Graphics
- Sử dụng graphics phức tạp và phong phú hơn
- Tích hợp nhiều màu sắc, texture và patterns
- Tạo trải nghiệm immersive cho người dùng

### 2. Parallax Scrolling với Video Content
- Áp dụng parallax scrolling với nội dung động
- Tích hợp video background hoặc animated elements
- Tạo depth và dynamic visual experience

### 3. Skeuomorphism Revival
- Sử dụng các element giống thế giới thực
- Buttons, switches, dials có texture và shadow
- Tạo cảm giác familiar và intuitive

### 4. Interactive Elements
- Hover effects mượt mà
- Micro-interactions
- Smooth transitions

## Color Palette Chuyên Nghiệp IT

### Primary Palette: "Tech Innovation"
- **Primary Blue**: #02a9f7 (Bright tech blue - tin cậy, chuyên nghiệp)
- **Dark Blue**: #02577a (Deep tech blue - ổn định, bảo mật)
- **Accent Blue**: #89d6fb (Light blue - hiện đại, sáng tạo)
- **Background**: #d4f0fc (Very light blue - sạch sẽ, thoáng đãng)
- **Dark Accent**: #01303f (Navy - chuyên nghiệp, nghiêm túc)

### Secondary Colors
- **Success Green**: #00d084 (Thành công, tích cực)
- **Warning Orange**: #ff6b35 (Năng động, sáng tạo)
- **Neutral Gray**: #6c757d (Cân bằng, chuyên nghiệp)
- **White**: #ffffff (Sạch sẽ, tối giản)
- **Dark**: #212529 (Text, contrast)

## Layout & Structure

### Header Section
- Logo/Title nhóm ở trái
- Navigation menu ở phải (Home, About, Members, Contact)
- Sticky header với glass morphism effect
- Smooth scroll navigation

### Hero Section
- Large heading: "Nhóm 1 - IT Professionals"
- Subtitle mô tả ngắn gọn về nhóm
- Animated background với geometric shapes
- Call-to-action button: "Khám Phá Thành Viên"
- Parallax scrolling effect

### Members Section
- Grid layout 2x2 cho 4 thành viên
- Member cards với hover effects:
  - Card lift animation
  - Image overlay với thông tin
  - Smooth transitions
  - Link button to individual CV
- Responsive design: mobile sẽ là 1 column

### About Section (Optional)
- Thông tin về nhóm
- Skills/Technologies sử dụng
- Animated progress bars hoặc skill icons

### Footer
- Contact information
- Social links
- Copyright

## Hiệu Ứng và Animations

### 1. Loading Animation
- Custom loading spinner với brand colors
- Smooth fade-in khi trang load xong

### 2. Scroll Animations
- Elements fade in khi scroll vào view
- Parallax background movement
- Progress indicator khi scroll

### 3. Hover Effects
- Member cards: lift + shadow increase
- Buttons: color transition + scale
- Links: underline animation

### 4. Micro-interactions
- Button press feedback
- Form input focus states
- Icon hover animations

## Typography
- **Headings**: Inter hoặc Poppins (Modern, clean)
- **Body**: Open Sans hoặc Roboto (Readable, professional)
- **Accent**: Fira Code (For tech elements)

## Technical Implementation

### Technologies
- HTML5 semantic markup
- CSS3 với Flexbox/Grid
- JavaScript ES6+ cho interactions
- CSS animations và transitions
- Responsive design (Mobile-first)

### Performance
- Optimized images (WebP format)
- Minified CSS/JS
- Lazy loading cho images
- Smooth 60fps animations

### Accessibility
- Proper heading hierarchy
- Alt text cho images
- Keyboard navigation support
- Color contrast compliance (WCAG 2.1)

## Responsive Breakpoints
- Mobile: 320px - 768px
- Tablet: 768px - 1024px  
- Desktop: 1024px+

## File Structure
```
team-website/
├── index.html
├── css/
│   ├── style.css
│   └── responsive.css
├── js/
│   ├── main.js
│   └── animations.js
├── images/
│   ├── members/
│   └── backgrounds/
└── assets/
    ├── icons/
    └── fonts/
```

## Next Steps
1. Tạo wireframe chi tiết
2. Implement HTML structure
3. Style với CSS
4. Add JavaScript interactions
5. Test và optimize
6. Deploy

