# TaskFlow — To Do List App

Aplikasi **To Do List** berbasis web yang responsif dan fungsional, dibangun menggunakan **HTML**, **CSS**, dan **JavaScript** murni (tanpa framework).

---

## 📋 Fitur Utama

| Fitur | Keterangan |
|---|---|
| 👤 Profile | Menampilkan nama, jabatan, hari, tanggal, dan jam real-time |
| ✏️ Text Area | Kolom untuk menuliskan deskripsi tugas |
| 🎯 Level Prioritas | Tiga tingkatan: **Low**, **Medium**, **High** |
| ➕ Button Submit | Menambahkan tugas ke daftar To Do |
| ☑️ Checkbox | Klik untuk menandai tugas selesai |
| 📋 Kolom To Do | Daftar tugas yang akan/sedang dikerjakan |
| ✅ Kolom Done | Daftar tugas yang sudah diselesaikan |
| 🗑️ Button Delete | Menghapus satu tugas |
| 🗑️ Button Delete All | Menghapus semua tugas aktif sekaligus |
| ⏰ Overdue | Tugas yang belum selesai lebih dari 24 jam otomatis ditandai *Overdue* |
| 💾 Penyimpanan | Data tersimpan di `localStorage` — tidak hilang saat refresh |

---

## 🗂️ Struktur File

```
taskflow/
├── index.html   → Struktur halaman (HTML)
├── style.css    → Tampilan & desain (CSS)
├── script.js    → Logika aplikasi (JavaScript)
└── README.md    → Dokumentasi proyek
```

---

## 🚀 Cara Menjalankan

1. Clone atau download repository ini
2. Buka file `index.html` di browser (tidak perlu server)
3. Masukkan **nama** dan **jabatan** di halaman setup
4. Mulai tambahkan tugas!

```bash
# Clone repository
git clone https://github.com/username/taskflow.git

# Buka di browser
cd taskflow
open index.html
```

---

## 🎮 Cara Penggunaan

1. **Tambah Tugas** — Ketik deskripsi tugas di Text Area, pilih level prioritas, klik **Submit Tugas** (atau `Ctrl + Enter`)
2. **Tandai Selesai** — Klik checkbox di samping tugas; tugas akan pindah ke kolom **Done**
3. **Hapus Satu Tugas** — Klik tombol **✕** di sisi kanan tugas
4. **Hapus Semua** — Klik tombol **🗑 Hapus Semua** untuk menghapus seluruh tugas aktif
5. **Overdue** — Tugas yang belum selesai lebih dari 24 jam otomatis mendapat label ⏰ Overdue

---

## 🛠️ Teknologi

- **HTML5** — Struktur halaman
- **CSS3** — Styling, animasi, responsive layout
- **JavaScript (Vanilla)** — Logika aplikasi, DOM manipulation, localStorage
- **Google Fonts** — Syne & DM Sans

---

## 📱 Responsive

Aplikasi mendukung tampilan **mobile** dan **desktop** secara otomatis.

---

*Dibuat sebagai bagian dari tugas pengembangan aplikasi karyawan.*
