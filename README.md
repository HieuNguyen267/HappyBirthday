# 🎉 Birthday Celebration Website

Một trang web sinh nhật đặc biệt với hiệu ứng animation và nhạc tự động.

## ✨ Tính năng

- 🎂 Animation chữ sinh nhật với hiệu ứng particle
- 🎵 Nhạc tự động phát với bypass auto-play
- 💝 Box chúc mừng với hiệu ứng Typewriter
- 📱 Responsive design
- 🎨 Giao diện đẹp mắt với gradient màu hồng

## 🚀 Deploy lên Vercel

### Cách 1: Deploy qua GitHub

1. **Push code lên GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/railoves.git
   git push -u origin main
   ```

2. **Deploy trên Vercel:**
   - Truy cập [vercel.com](https://vercel.com)
   - Đăng nhập với GitHub
   - Click "New Project"
   - Import repository từ GitHub
   - Click "Deploy"

### Cách 2: Deploy trực tiếp

1. **Cài đặt Vercel CLI:**
   ```bash
   npm i -g vercel
   ```

2. **Deploy:**
   ```bash
   vercel
   ```

3. **Làm theo hướng dẫn:**
   - Chọn "Y" để link với project hiện tại
   - Chọn "Y" để override settings
   - Đợi deploy hoàn thành

## 📁 Cấu trúc file

```
Railoves/
├── index.html          # Trang chính
├── 1.mp3              # File nhạc
├── acs.jpeg           # Hình ảnh
├── download.gif       # GIF animation
├── Donate.html        # Trang donate
├── note.txt           # Ghi chú
├── vercel.json        # Cấu hình Vercel
└── README.md          # Hướng dẫn
```

## 🎵 Audio

- File: `1.mp3`
- Tự động phát khi mở trang
- Bypass auto-play restrictions
- Loop vô hạn

## 🎨 Animation

- Particle animation cho text
- Countdown 3 giây
- Birthday box với Typewriter effect
- Gradient background

## 🔧 Cấu hình

File `vercel.json` đã được cấu hình để:
- Serve static files
- Handle audio files
- Set cache headers
- Route tất cả requests

## 🌐 Truy cập

Sau khi deploy, website sẽ có URL dạng:
`https://your-project-name.vercel.app`

## 📱 Tương thích

- ✅ Desktop browsers
- ✅ Mobile browsers
- ✅ Tablet browsers
- ✅ Modern browsers (Chrome, Firefox, Safari, Edge)

## 🎉 Kết quả

Website sẽ hiển thị:
1. Animation chữ "HAPPY BIRTHDAY TO NGƯỜI EM CỦA TÔI ĐINH PHƯƠNG ANH"
2. Countdown 3 giây
3. Birthday box với lời chúc Typewriter
4. Nhạc tự động phát

---

**Lưu ý:** Đảm bảo file `1.mp3` có trong thư mục để audio hoạt động! 