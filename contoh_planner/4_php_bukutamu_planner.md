# Project Name: Buku Tamu & Ulasan (PHP)

## 1. Ringkasan Proyek
Sebuah halaman "Buku Tamu" atau halaman ulasan *review* ringan bagi pengunjung website untuk menuliskan pesan dan impresi mereka. Tidak butuh konfigurasi *database* SQL yang sulit, melainkan menyimpan masukannya langsung ke isi file `.json`.
- **Target Pengguna:** Pengunjung Website / Umum

## 2. Tech Stack & Aturan
- **Framework Utama:** PHP (Native), HTML Statis, CSS
- **Target Platform:** Web
- **State Management:** Tidak perlu
- **Penyimpanan:** Local JSON (`reviews.json`)
- **Desain UI:** Ceria & Colorful (Soft color yang lembut)
- **Color Palette:** Warna-warna pastel lembut
- **Typography (Huruf):** Inter
- **Bahasa Aplikasi:** Bahasa Indonesia Formal
- **Icon / Gaya Animasi:** Animasi Melayang (Hover) premium pada tombol untuk interaksi

## 3. Struktur Menu (Navigasi)
- **Halaman Utam (Satu Halaman):** 
    - Bagian Atas: Formulir pengisian Nama dan Kolom Ulasan panjang.
    - Bagian Bawah: Daftar panjang ulasan dari pengunjung yang bisa langsung dibaca otomatis setelah pesan dikirim.
- **Aksi Khusus:** Tombol bergaya cerah bertuliskan "Kirim Ulasan".

## 4. Struktur Folder yang Diinginkan
```text
/
 ┣ reviews.json
 ┣ index.php
 ┗ style.css
```

## 5. Tahapan Pengerjaan (Milestones)

✅ **Fase 1: Layouting Tampilan Utama**
- Buat struktur HTML dengan dua irisan pandangan: Form Pengisian di atas dan Daftar Komentar di bawahnya.
- Berikan tombol bergaya cerah "Kirim Ulasan".

⚙️ **Fase 2: Proses Menerima Form (Menyimpan)**
- Buat logika PHP dengan tipe `POST` untuk menangkap pengisian pengunjung.
- Tarik dari file `reviews.json`, selipkan ulasan berbaru, dan *simpan kembali* ke dalam formasi JSON-nya menggunakan `file_put_contents`.

🚀 **Fase 3: Menampilkan Seluruh Komentar (Membaca)**
- Di bagian bawah HTML, telusuri (*loop*) riwayat ulasan lawas satu persatu dari file yang sama.
- Tambahkan tampilan berbentuk tanda kutip *quote* melengkung modern di setiap pesannya.
