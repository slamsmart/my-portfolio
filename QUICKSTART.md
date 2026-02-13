# 🚀 Quick Start Guide

## Step 1: Download & Extract
Download semua file dan extract ke folder `portfolio`

## Step 2: Edit Informasi Anda

### ✏️ Edit index.html

1. **Ganti Nama & Title** (Line 241-243):
```html
<h1>Nama Anda</h1>
<p class="subtitle">Web Developer & Software Engineer</p>
```

2. **Ganti Nomor WhatsApp** (Line 581):
```javascript
const WHATSAPP_NUMBER = '6281234567890'; // Ganti dengan nomor Anda
```

3. **Upload Foto Profile:**

   **Opsi 1: Upload Langsung (Termudah!)**
   - Buka website Anda di browser
   - Klik tombol kamera (⚪ icon) di pojok foto profil
   - Pilih foto dari komputer
   - Done! Foto otomatis tersimpan
   
   **Opsi 2: Edit Manual**
   - Upload foto ke [imgur.com](https://imgur.com) atau [cloudinary.com](https://cloudinary.com)
   - Copy link foto
   - Paste di line 237:
```html
<img src="LINK_FOTO_ANDA" alt="Profile Photo">
```

4. **Update Social Media** (Line 250-315):
   - Ganti semua `yourusername` dengan username Anda
   - Ganti `your.email@gmail.com` dengan email Anda

5. **Update Projects** (Line 386-436):
   - Edit nama project
   - Edit deskripsi
   - Update link GitHub dan Live Demo

## Step 3: Test Lokal (Optional)

### Cara 1: Double click `index.html`
Buka langsung di browser

### Cara 2: Live Server (Recommended)
```bash
# Install live server globally
npm install -g live-server

# Run
live-server
```

### Cara 3: Python Server
```bash
# Python 3
python -m http.server 8000

# Buka: http://localhost:8000
```

## Step 4: Deploy ke Vercel

### 🎯 Cara Tercepat (3 Menit)

1. **Buka [vercel.com](https://vercel.com)**
2. **Sign up dengan GitHub**
3. **Upload ke GitHub:**
   ```bash
   # Di folder project
   git init
   git add .
   git commit -m "First commit"
   git branch -M main
   
   # Buat repo baru di github.com
   # Copy URL repo, lalu:
   git remote add origin https://github.com/username/portfolio.git
   git push -u origin main
   ```

4. **Di Vercel:**
   - Klik "New Project"
   - Import repository
   - Klik "Deploy"
   - **DONE!** 🎉

### 📱 Test WhatsApp

1. Buka website Anda di Vercel
2. Klik tombol WhatsApp hijau di kanan bawah
3. Pastikan terbuka ke nomor WhatsApp Anda
4. Jika tidak, cek nomor di `WHATSAPP_NUMBER`

## Step 5: Custom Domain (Optional)

Di Vercel Dashboard:
1. Pilih project Anda
2. Settings → Domains
3. Add domain Anda
4. Follow petunjuk untuk update DNS

## 📋 Checklist

Sebelum deploy, pastikan sudah:

- [ ] Ganti nama dan title
- [ ] Upload dan update foto profile
- [ ] Update semua social media links
- [ ] Ganti nomor WhatsApp
- [ ] Update email
- [ ] Edit projects dengan link yang benar
- [ ] Test WhatsApp integration
- [ ] Test dark/light mode
- [ ] Check responsive di mobile

## 🎨 Tips Customization Cepat

### Ganti Warna Accent
Edit line 18 di `index.html`:
```css
--accent: #00ff88;  /* Ganti dengan warna favorit */
```

### Ganti Font
1. Pilih font di [fonts.google.com](https://fonts.google.com)
2. Copy link nya
3. Ganti di line 9-10
4. Update `font-family` di CSS

### Tambah Project
Copy block `project-card` dan paste, lalu edit:
```html
<div class="project-card">
    <h3 class="project-title">Project Baru</h3>
    <p class="project-description">Deskripsi...</p>
    <div class="project-links">
        <a href="GITHUB">GitHub</a>
        <a href="DEMO">Live Demo</a>
    </div>
</div>
```

## 🆘 Butuh Bantuan?

### WhatsApp tidak jalan?
```javascript
// Pastikan format nomor benar:
✅ '6281234567890'
❌ '+62 812-3456-7890'
❌ '081234567890'
```

### Foto tidak muncul?
**Jika upload langsung:**
- Check ukuran foto tidak lebih dari 5MB
- Pastikan format foto valid (JPG, PNG, WebP)
- Clear localStorage browser dan upload ulang
- Coba browser berbeda

**Jika pakai link eksternal:**
- Check link foto valid (coba buka di browser baru)
- Pastikan foto public/accessible
- Format supported: JPG, PNG, WebP

### Deploy gagal?
- Check semua file ada (index.html, vercel.json)
- Pastikan tidak ada error di console browser
- Clear cache Vercel dan deploy ulang

## 🚀 Next Steps

Setelah deploy:
1. Share link portfolio Anda!
2. Tambahkan ke LinkedIn
3. Update di resume
4. Share di social media

## 💡 Pro Tips

1. **Gunakan foto profesional** - First impression matters!
2. **Update projects regularly** - Show your latest work
3. **Add analytics** - Track your visitors
4. **SEO optimize** - Add meta tags untuk better Google ranking
5. **Keep it updated** - Update skills dan achievements

---

**Selamat! Website portfolio Anda siap! 🎉**

Need help? Contact me via WhatsApp button! 😊
