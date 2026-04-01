# Project Name: Katalog Produk Sederhana (PHP)

## 1. Ringkasan Proyek
Website sederhana berbasis PHP untuk menampilkan daftar produk jualan (misalnya sepatu atau tas). Katalog tidak menggunakan database MySQL/SQL yang rumit, melainkan mengambil data berupa daftar produk dari sebuah file `.json` lokal di dalam folder.
- **Target Pengguna:** Umum / Pemula

## 2. Tech Stack & Aturan
- **Framework Utama:** PHP (Native), HTML Statis, CSS
- **Target Platform:** Web
- **State Management:** Tidak perlu
- **Penyimpanan:** Local JSON (`data.json`)
- **Desain UI:** Modern Minimalis 
- **Color Palette:** Bebaskan AI (Auto)
- **Typography (Huruf):** Poppins
- **Bahasa Aplikasi:** Bahasa Indonesia Formal
- **Icon / Gaya Animasi:** Animasi Melayang (Hover) premium di setiap kotak produk

## 3. Struktur Menu (Navigasi)
- **Halaman Depan:** Halaman berisi susunan *card* atau kotak produk berjajar. Menampilkan gambar, nama, dan harga pada setiap produk tapa butuh loading pangkalan data (database).
- **Aksi Khusus:** Tidak ada interaksi kompleks, hanya untuk baca/katalog.

## 4. Struktur Folder yang Diinginkan
```text
/
 ┣ data.json
 ┣ index.php
 ┗ style.css
```

## 5. Tahapan Pengerjaan (Milestones)

✅ **Fase 1: Tampilan Teras (HTML/CSS)**
- Buat file bernama `index.php`.
- Buat desain grid kotak (CSS Flexbox) untuk menampilkan produk dalam bentuk memukau.
- Masukkan data percontohan secara manual (kodingan HTML) untuk mengecek apakah desainnya sudah pas.

⚙️ **Fase 2: Menyiapkan File Data JSON**
- Buat file `data.json` di direktori yang sama.
- Tuliskan daftar 5 barang (*array* yang berisi id barang, judul, harga, dan gambar *placeholder* internet).

🚀 **Fase 3: Integrasi Data dengan PHP**
- Gunakan perintah bawaan PHP `file_get_contents` di berkas `index.php` untuk membaca teks `data.json`.
- Ubah teks tersebut (menggunakan `json_decode`) lalu perulangkan data ke dalam desain kotak (*looping* HTML `<div>` ke sejumlah produk tadi).
