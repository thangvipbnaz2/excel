# 📝 Hướng dẫn Deploy lên Vercel

## Cách 1: Deploy bằng Vercel GUI (đơn giản nhất) ✨

### Bước 1: Chuẩn bị tệp
- Tạo folder `chinese-dictionary` trên máy tính
- Copy file `thang.html` vào folder
- Rename thành `index.html`

### Bước 2: Upload lên GitHub
```bash
cd chinese-dictionary
git init
git add .
git commit -m "Initial commit"
git push origin main
```

### Bước 3: Deploy trên Vercel
1. Truy cập https://vercel.com
2. Login với GitHub account
3. Click "New Project"
4. Select repo vừa tạo
5. Click "Deploy"

✅ **Done!** Trang sẽ được deploy tự động

---

## Cách 2: Deploy trực tiếp file (không cần GitHub)

### Bước 1: Install Vercel CLI
```bash
npm install -g vercel
```

### Bước 2: Deploy
```bash
cd /path/to/your/folder
vercel
```

Làm theo hướng dẫn trên terminal

---

## Cách 3: Deploy bằng Drag & Drop

**Trên trang Vercel:**
1. Vào https://vercel.com
2. Hoặc https://vercel.com/import (import project)
3. Kéo thả folder hoặc file `index.html` vào

---

## ⚡ Các tính năng đã có

✅ **Giao diện bắt mắt**
- Nền gradient tím-xanh
- Animation mượt mà
- Responsive (mobile & desktop)

✅ **Nhân dạng giọng nói (Mic)**
- Bấm nút 🎤 để nói tiếng Trung
- Hỗ trợ đa trình duyệt
- Indicator sống động khi nghe

✅ **Phát âm nhanh**
- Sử dụng Web Speech API
- Cancel nhanh chóng nếu nhấn nhiều lần
- Rate tối ưu cho tiếng Trung (0.9)

✅ **Tính năng đầy đủ**
- Tra cứu từ Trung → Việt
- Hiển thị Pinyin
- Button copy clipboard
- Hỗ trợ Enter để tra cứu

✅ **Vercel-ready**
- Không cần backend
- Pure static HTML/CSS/JS
- CDN tự động
- Deploy một click

---

## 🌍 URL sau khi deploy

```
https://your-project-name.vercel.app
```

---

## Troubleshoot

**Mic không hoạt động?**
- Chỉ hoạt động trên HTTPS (Vercel tự hỗ trợ)
- Cần cấp quyền microphone

**Âm thanh bị delay?**
- Đã tối ưu với `speechSynthesis.cancel()`
- Thử reload trang

**Phiên âm sai?**
- Kiểm tra user đã nhập đúng chữ Trung chưa

---

Hành hạnh phúc! 🚀
