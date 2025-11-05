# Indo Travel - Landing Page Umroh & Haji

Landing page modern untuk travel umroh dan haji dengan desain responsive dan interactive.

## 👨‍🎓 Informasi Pembuat
- **Nama:** Mohamad Firman Imanudin Akbar
- **NIM:** 202351195
- **Kelas:** A

## ✨ Fitur
- ✅ Responsive Design (Mobile & Desktop)
- ✅ Modern UI dengan Shadow Effects
- ✅ Smooth Animations & Hover Effects
- ✅ Interactive FAQ Accordion
- ✅ WhatsApp Integration
- ✅ SEO Friendly
- ✅ Fast Loading (Single HTML File)

## 🛠️ Teknologi
- HTML5
- Tailwind CSS (via CDN)
- Vanilla JavaScript
- Heroicons (SVG Icons)

## 🚀 Cara Deploy ke Vercel

### Metode 1: Deploy via Web (Paling Mudah)

1. **Buka Vercel**
   - Kunjungi [vercel.com](https://vercel.com)
   - Klik "Sign Up" atau "Login"
   - Login dengan GitHub, GitLab, atau Bitbucket (recommended GitHub)

2. **Create New Project**
   - Setelah login, klik tombol **"Add New..."** di dashboard
   - Pilih **"Project"**

3. **Upload Files**
   - Pilih tab **"Upload"** atau **"Import Git Repository"**
   - **Jika Upload Manual:**
     - Drag & drop folder `landing` yang berisi:
       - `index.html`
       - `vercel.json`
       - `README.md`
     - Atau klik "Browse" untuk select folder
   
4. **Configure Project**
   - **Project Name:** Beri nama (misal: `indo-travel-landing`)
   - **Framework Preset:** Pilih "Other" atau biarkan auto-detect
   - **Root Directory:** Biarkan default `./`
   - Klik **"Deploy"**

5. **Tunggu Deploy Selesai**
   - Proses deploy sekitar 30-60 detik
   - Setelah selesai, akan muncul confetti 🎉
   - Copy link website Anda (format: `indo-travel-landing.vercel.app`)

6. **Selesai!**
   - Website sudah live dan bisa diakses
   - SSL otomatis aktif (HTTPS)
   - Gratis selamanya!

### Metode 2: Deploy via GitHub (Recommended untuk Update)

1. **Push ke GitHub**
   ```bash
   cd C:\firman\project\landing
   git init
   git add .
   git commit -m "Initial commit: Indo Travel Landing Page"
   git branch -M main
   git remote add origin https://github.com/username/indo-travel.git
   git push -u origin main
   ```

2. **Import di Vercel**
   - Login ke [vercel.com](https://vercel.com)
   - Klik **"Add New..."** → **"Project"**
   - Pilih **"Import Git Repository"**
   - Authorize GitHub dan pilih repository `indo-travel`
   - Klik **"Import"**
   - Klik **"Deploy"**

3. **Auto Deploy**
   - Setiap kali push ke GitHub, otomatis deploy ulang
   - Tidak perlu upload manual lagi

### Metode 3: Deploy via Vercel CLI (Advanced)

1. **Install Vercel CLI**
   ```bash
   npm install -g vercel
   ```

2. **Login**
   ```bash
   vercel login
   ```

3. **Deploy**
   ```bash
   cd C:\firman\project\landing
   vercel
   ```
   - Ikuti instruksi di terminal
   - Tekan Enter untuk menggunakan default settings
   - Deploy selesai dalam hitungan detik!

4. **Deploy Production**
   ```bash
   vercel --prod
   ```

## 🔧 Update Website

### Jika Deploy Manual:
1. Edit file `index.html`
2. Kembali ke Vercel dashboard
3. Pilih project Anda
4. Klik **"Deployments"** tab
5. Klik **"..."** → **"Redeploy"**
6. Atau upload ulang via drag & drop

### Jika Deploy via GitHub:
1. Edit file `index.html`
2. Commit & push:
   ```bash
   git add .
   git commit -m "Update content"
   git push
   ```
3. Vercel otomatis deploy ulang dalam 1 menit

## 🌐 Custom Domain (Opsional)

1. Beli domain di Namecheap, GoDaddy, atau Niagahoster
2. Di Vercel dashboard, pilih project
3. Klik tab **"Settings"** → **"Domains"**
4. Tambahkan domain Anda (misal: `indotravel.com`)
5. Update DNS di provider domain Anda:
   - Type: `A`, Value: `76.76.21.21`
   - Type: `CNAME`, Name: `www`, Value: `cname.vercel-dns.com`
6. Tunggu propagasi DNS (5-48 jam)
7. Domain custom siap digunakan!

## 📱 Preview

### Desktop View
- Header dengan glassmorphism effect
- Hero section dengan gradient background
- Feature cards dengan hover animation
- Pricing cards dengan shadow effects
- Testimonial dengan border accent

### Mobile View
- Hamburger menu
- Single column layout
- Touch-friendly buttons
- Optimized spacing

## 📝 Struktur File

```
landing/
├── index.html        # File utama landing page
├── vercel.json       # Konfigurasi Vercel
└── README.md         # Dokumentasi
```

## 🎨 Customization

### Ubah Warna Brand
Edit di section `<style>` dalam `index.html`:
```css
.gradient-hero {
    background: linear-gradient(135deg, #059669 0%, #047857 100%);
}
```

### Ubah Konten
Edit langsung di `index.html` pada section yang diinginkan:
- Hero Section (line ~221)
- Paket Umroh (line ~308)
- Paket Haji (line ~531)
- Testimoni (line ~707)
- FAQ (line ~786)

### Ubah WhatsApp Number
Find & Replace:
- Ganti `6281234567890` dengan nomor WhatsApp Anda
- Format: `62` + nomor (tanpa 0 di depan)
- Contoh: `628123456789`

## 🐛 Troubleshooting

### Website Tidak Muncul di Vercel
- Pastikan file bernama `index.html` (lowercase)
- Pastikan `vercel.json` ada di root folder
- Cek di Vercel dashboard → Deployments → Logs

### CSS Tidak Load
- Cek koneksi internet (Tailwind via CDN)
- Clear browser cache (Ctrl + Shift + R)

### Mobile Menu Tidak Berfungsi
- Pastikan JavaScript di bagian bawah file aktif
- Cek browser console (F12) untuk error

## 📞 Support

Jika ada pertanyaan atau issue, silakan kontak:
- Email: firman@example.com
- WhatsApp: +62 812-3456-7890

## 📄 License

© 2025 Mohamad Firman Imanudin Akbar. All rights reserved.

---

**Dibuat dengan ❤️ untuk tugas kuliah**
