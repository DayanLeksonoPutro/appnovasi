# Planner: Katalog Produk Sederhana (PHP)

## 1. Ringkasan Proyek
Website sederhana berbasis PHP untuk menampilkan daftar produk jualan (misalnya sepatu atau tas). Katalog tidak menggunakan database MySQL/SQL yang rumit, melainkan mengambil data berupa daftar produk dari sebuah file `.json` lokal di dalam folder.

## 2. Tech Stack & Aturan
- **Bahasa Server:** PHP murni (Native)
- **Tampilan:** HTML & CSS (Framework ditiadakan agar paham dasar)
- **Sumber Data:** File `data.json`

## 3. Fitur Utama
- Halaman depan berisikan susunan *card* atau kotak produk berjajar.
- Menampilkan gambar, nama, dan harga pada setiap produk tanpa butuh loading pangkalan data (database).

## 4. Tahapan Pengerjaan (Milestones)

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
