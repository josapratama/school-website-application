# School Portal & CMS Web Application (CodeIgniter 4) 🏫

> Web Portal Profil Sekolah & Content Management System (CMS) Terintegrasi Berbasis CodeIgniter 4 & AdminLTE.

---

## ✨ Fitur & Modul Utama

- **Portal Publik Sekolah**:
  - Halaman beranda profil sekolah, visi, misi, dan struktur organisasi.
  - Berita terkini, agenda kegiatan, pengumuman, dan artikel sekolah.
  - Galeri dokumentasi kegiatan ekstrakurikuler & prestasi siswa.
- **Admin & CMS Dashboard**:
  - Panel administrasi modern berbasis AdminLTE.
  - Manajemen konten berita, artikel, dan pengumuman.
  - Pengelolaan data staf pengajar/guru dan sarana prasarana sekolah.

---

## 🛠️ Tech Stack

- **Framework**: [CodeIgniter 4](https://codeigniter.com/)
- **Bahasa**: PHP ^8.1 / 8.2 / 8.3
- **Database**: MySQL
- **Admin Dashboard**: AdminLTE 3 + Bootstrap

---

## 🚀 Panduan Instalasi Lokal

```bash
# 1. Clone repositori
git clone https://github.com/josapratama/school-website-application.git
cd school-website-application

# 2. Install dependensi composer
composer install

# 3. Salin file environment
copy env .env

# 4. Konfigurasi database di file .env

# 5. Salin aset AdminLTE ke public
php move-adminlte.php

# 6. Jalankan development server
php spark serve
```
Akses di browser: `http://localhost:8080`
