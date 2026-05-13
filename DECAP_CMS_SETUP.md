Panduan Setup Decap CMS untuk Ditta Story
=========================================

## ✅ Apa yang Sudah Disetup

File-file berikut sudah dibuat:
- `admin/index.html` - Interface Decap CMS
- `admin/config.yml` - Konfigurasi CMS

## 🚀 Langkah Setup (One-time only)

### 1. Persiapan di GitHub
- Push semua file ke GitHub (sudah done!)
- Buka Settings Repository → Developer Settings → OAuth Apps
- Atau gunakan Decap CMS OAuth Provider (lebih mudah)

### 2. Setup Decap CMS OAuth (REKOMENDASI - Paling Mudah)

Ikuti langkah ini:

**A. Pergi ke Decap CMS Official Site**
- Buka: https://app.decapcms.org/

**B. Login/Daftar**
- Gunakan GitHub account kamu
- Accept permissions

**C. Connect Repository**
- Klik "New Site"
- Pilih repository: `dittalyona/Ditta-Story`
- Pilih branch: `main`
- Selesai! ✅

### 3. Akses Dashboard CMS

Setelah setup, kamu bisa akses CMS di:
```
https://app.decapcms.org/
```

ATAU langsung di website kamu:
```
https://dittalyona.github.io/Ditta-Story/admin/
```
(Setelah deploy ke GitHub Pages)

---

## 📝 Cara Membuat Cerpen Baru

1. **Login ke Decap CMS**
   - Buka https://app.decapcms.org/
   - Login dengan GitHub

2. **Klik "Cerita" di sidebar**

3. **Klik "+ New Cerita"**

4. **Isi form:**
   - **Judul**: Nama cerpen kamu
   - **Deskripsi**: Ringkasan singkat
   - **Tanggal Publikasi**: Kapan dipublikasikan
   - **Draft**: Centang jika masih draft
   - **Konten**: Tulis cerpen di editor markdown
   - **Kategori**: Tambah kategori (cinta, horor, dll)
   - **Tag**: Tambah tag (opsional)

5. **Klik "Publish"**
   - File akan auto-commit ke GitHub
   - Website akan otomatis update!

---

## 🎨 Mengedit Halaman Lain

Kamu juga bisa edit halaman di CMS:

**Halaman → Pilih:**
- Tentang Kami
- Kontak  
- Halaman Utama

Tinggal edit dan publish, semudah itu!

---

## ⚡ Fitur-fitur yang Tersedia

✅ **Membuat Cerita Baru** - Tanpa perlu GitHub
✅ **Edit Konten** - Langsung dari dashboard
✅ **Preview** - Lihat preview sebelum publish
✅ **Auto-commit** - Perubahan langsung ke GitHub
✅ **Markdown Editor** - Editor yang user-friendly
✅ **Media Manager** - Upload gambar untuk cerita
✅ **Kategori & Tag** - Organize cerita kamu

---

## 🔧 Troubleshooting

**"Error: Repository not found"**
- Pastikan repository adalah public
- Pastikan URL repository benar di config.yml

**"Authentication failed"**
- Re-login dengan GitHub account
- Pastikan akun GitHub punya akses ke repo

**"Changes tidak muncul"**
- Tunggu beberapa menit untuk build GitHub Pages
- Cek status di GitHub Actions

---

## 📚 Resource Tambahan

- Decap CMS Docs: https://decapcms.org/docs/
- Hugo + Decap CMS: https://decapcms.org/docs/quick-start/#hugo
- GitHub Pages Setup: https://pages.github.com/

---

Selamat! Sekarang kamu bisa membuat cerpen tanpa perlu edit file! 🎉✨

Ada pertanyaan atau masalah? Tanyakan saja! 😊
