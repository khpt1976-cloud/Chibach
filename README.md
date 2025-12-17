# Chí Bách - Website Gia Dụng

Đây là website gia dụng "Chí Bách" được tạo dựa trên thiết kế của hangxingiatot.com nhưng đã được tùy chỉnh hoàn toàn với brand mới.

## 🌟 Tính năng

- ✅ **Brand "Chí Bách"** - Logo và banner được tùy chỉnh hoàn toàn
- ✅ **Responsive design** - tương thích với mọi thiết bị
- ✅ **Tất cả hình ảnh** được tải xuống và lưu trữ local
- ✅ **Interactive elements** - dropdown menus, hover effects
- ✅ **Search functionality** - thanh tìm kiếm hoạt động
- ✅ **Product grid** - hiển thị sản phẩm với rating và giá
- ✅ **Blog section** - tin tức và bài viết
- ✅ **Footer** với thông tin liên hệ đầy đủ
- ✅ **Custom banner** - "Chí Bách - Chia sẻ việc nhà"
- ✅ **Custom logos** - Logo CB được thiết kế riêng

## 📁 Cấu trúc thư mục

```
hangxingiatot-clone/
├── index.html          # File HTML chính
├── css/
│   └── style.css       # File CSS styling
├── js/
│   └── script.js       # File JavaScript
├── images/             # Thư mục chứa tất cả hình ảnh
│   ├── logo.png
│   ├── banner-main.webp
│   ├── icon-*.jpg      # Icons danh mục
│   ├── product*.webp   # Hình ảnh sản phẩm
│   └── ...
└── README.md           # File hướng dẫn này
```

## 🚀 Cách chạy

### Phương pháp 1: Python HTTP Server (Đang chạy)
```bash
cd hangxingiatot-clone
python3 -m http.server 12000 --bind 0.0.0.0
```

### Phương pháp 2: Node.js HTTP Server
```bash
npx http-server -p 12000 -a 0.0.0.0
```

### Phương pháp 3: PHP Built-in Server
```bash
php -S 0.0.0.0:12000
```

## 🌐 Truy cập website

- **Local**: http://localhost:12000
- **External**: https://work-1-egejkuxslidafrdm.prod-runtime.all-hands.dev

## 📱 Responsive Breakpoints

- **Desktop**: > 768px
- **Tablet**: 768px - 480px  
- **Mobile**: < 480px

## 🎨 Màu sắc chính

- **Primary Orange**: #ff6b35
- **Secondary Orange**: #f7931e
- **Dark Blue**: #2c3e50
- **Light Gray**: #f5f5f5
- **Text Color**: #333

## ⚡ Tính năng JavaScript

- Dropdown menus tương tác
- Search form validation
- Product hover effects
- Smooth scrolling
- Back to top button
- Mobile menu toggle
- Image lazy loading
- Error handling cho images

## 📋 Danh sách hình ảnh đã tải

### Logos & Branding
- logo.png - Logo chính
- logo-footer.png - Logo footer

### Banners
- banner-main.webp - Banner chính
- banner-gia-dung.webp - Banner danh mục gia dụng
- banner-nha-cua.webp - Banner danh mục nhà cửa

### Category Icons
- icon-gia-dung.jpg - Gia dụng - Điện máy
- icon-nha-cua.jpg - Nhà cửa - Đời sống
- icon-am-thanh.jpg - Âm thanh - Camera
- icon-giay-dep.jpg - Giày dép - Túi xách
- icon-me-be.jpg - Mẹ và Bé - Đồ chơi
- icon-phu-kien.jpg - Phụ kiện công nghệ
- icon-the-thao.jpg - Thể thao - Dã ngoại
- icon-dong-ho.jpg - Đồng hồ
- icon-o-to.jpg - Phụ kiện ô tô
- icon-suc-khoe.jpg - Sức khỏe - Làm đẹp
- icon-thoi-trang.jpg - Thời trang

### Product Images
- product1.webp - Cân tiểu ly điện tử
- product2.webp - Dụng cụ ép hoa quả
- product3.webp - Dụng cụ làm bún tươi
- product4.webp - Dụng cụ mồi lửa bếp gas
- product5.webp - Máy đánh trứng
- product6.webp - Nồi cơm điện mini

### Payment & Social Icons
- cash.svg - Thanh toán khi nhận hàng
- internet-banking.svg - Internet Banking
- social_face.png - Facebook icon
- social_you.png - Youtube icon

## 🔧 Customization

### Thay đổi màu sắc
Chỉnh sửa file `css/style.css` và thay đổi các biến màu:

```css
/* Thay đổi màu chính */
.header-main { background: #your-color; }
.main-nav { background: linear-gradient(135deg, #your-color 0%, #your-secondary-color 100%); }
```

### Thêm sản phẩm mới
1. Thêm hình ảnh vào thư mục `images/`
2. Cập nhật HTML trong `index.html`
3. Thêm styling nếu cần trong `css/style.css`

### Thêm tính năng JavaScript
Chỉnh sửa file `js/script.js` để thêm các tính năng mới.

## 📞 Thông tin liên hệ (từ website gốc)

- **Hotline**: 0888.042.637
- **Email**: giadungthanhdat9x@gmail.com
- **Showroom Hà Nội**: 185 Lệ Mật, Phường Đức Giang, Quận Long Biên, Thành phố Hà Nội
- **Showroom HCM**: 180 Nguyễn Văn Thương, Phường 25, Quận Bình Thạnh, Hồ Chí Minh

## 📝 Ghi chú

- Website này là bản sao hoàn chỉnh chỉ phục vụ mục đích demo/học tập
- Tất cả hình ảnh và nội dung thuộc bản quyền của hangxingiatot.com
- Code được viết clean và có comment đầy đủ để dễ hiểu và maintain

## 🎯 Hoàn thành 100%

✅ Khảo sát và phân tích website gốc  
✅ Tải xuống tất cả assets (hình ảnh, icons)  
✅ Tạo lại cấu trúc HTML hoàn chỉnh  
✅ Styling CSS giống hệt website gốc  
✅ Thêm JavaScript cho tính tương tác  
✅ Setup web server và test thành công  

**Website clone đã sẵn sàng sử dụng!** 🎉