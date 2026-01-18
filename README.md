# Sistem Informasi Perpustakaan

Sistem Informasi Perpustakaan adalah aplikasi berbasis web yang digunakan untuk mengelola data buku, anggota, peminjaman, dan pengembalian buku secara terkomputerisasi.

Proyek ini dibuat untuk memenuhi tugas UAS dengan penerapan konsep frontend dan backend yang dipisahkan.

---

## 🎯 Tujuan Sistem
- Mempermudah pengelolaan data perpustakaan
- Meningkatkan efisiensi proses peminjaman dan pengembalian buku
- Menyediakan laporan bagi kepala perpustakaan

---

## 👥 Pembagian Peran Pengguna
- **Admin**: Mengelola data pengguna dan buku
- **Pustakawan**: Mengelola transaksi peminjaman dan pengembalian
- **Anggota**: Melihat dan mencari buku, melihat riwayat peminjaman
- **Kepala Perpustakaan**: Melihat laporan

---

## 🛠️ Teknologi yang Digunakan
### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Node.js
- Express.js
- REST API

### Database
- MySQL

---

## 📂 Struktur Folder Proyek

Struktur folder pada proyek Sistem Informasi Perpustakaan dibagi menjadi dua bagian utama, yaitu frontend dan backend, untuk memisahkan antara tampilan pengguna dan logika sistem.

```text
sistem-informasi-perpustakaan/
│
├── frontend/                         # Tampilan (HTML, CSS, JavaScript)
│   │
│   ├── index.html                    # Halaman login (semua user)
│   │
│   ├── admin/                        # Halaman Admin
│   │   ├── dashboard.html
│   │   ├── buku.html
│   │   ├── anggota.html
│   │   └── pustakawan.html
│   │
│   ├── pustakawan/                   # Halaman Pustakawan
│   │   ├── dashboard.html
│   │   ├── peminjaman.html
│   │   └── pengembalian.html
│   │
│   ├── anggota/                      # Halaman Anggota
│   │   ├── dashboard.html
│   │   ├── cari-buku.html
│   │   └── riwayat.html
│   │
│   ├── kepala/                       # Halaman Kepala Perpustakaan
│   │   ├── dashboard.html
│   │   └── laporan.html
│   │
│   ├── css/                          # File CSS
│   │   └── style.css
│   │
│   └── js/                           # JavaScript frontend
│       ├── auth.js
│       ├── admin.js
│       ├── pustakawan.js
│       ├── anggota.js
│       └── kepala.js
│
└── backend/                          # Server dan database
    │
    ├── app.js                        # Server Express
    ├── package.json                  # Konfigurasi backend
    │
    ├── config/                       # Konfigurasi database
    │   └── db.js
    │
    ├── routes/                       # E



---

## 🤝 Metode Kolaborasi
Pengembangan dilakukan secara kolaboratif menggunakan GitHub dengan pembagian tugas:
- Frontend dan backend dikerjakan secara terpisah
- Setiap perubahan dicatat menggunakan commit

---

## 📌 Catatan
Proyek ini masih dalam tahap pengembangan dan akan terus diperbarui sesuai kebutuhan sistem.


