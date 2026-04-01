# Planner: Buku Tamu & Ulasan (PHP)

## 1. Ringkasan Proyek
Sebuah halaman "Buku Tamu" atau halaman ulasan *review* ringan bagi pengunjung website untuk menuliskan pesan dan impresi mereka. Tidak butuh konfigurasi *database* SQL yang sulit, melainkan menyimpan masukannya langsung ke isi file `.json`.

## 2. Tech Stack & Aturan
- **Bahasa Engine:** PHP (Native)
- **Tampilan:** HTML murni dan CSS sederhana yang lembut (*soft color*).
- **Penyimpanan:** Menyimpan hasil input ke file berbasis teks secara lokal (misal `reviews.json`).

## 3. Fitur Utama
- Formulir pengisian Nama dan Kolom Ulasan panjang.
- Daftar panjang ulasan dari pengunjung yang bisa langsung dibaca otomatis di bagian bawah setelah pesan dikirim.

## 4. Tahapan Pengerjaan (Milestones)

✅ **Fase 1: Layouting Tampilan Utama**
- Buat struktur HTML dengan dua irisan pandangan: Form Pengisian di atas dan Daftar Komentar di bawahnya.
- Berikan tombol bergaya cerah "Kirim Ulasan".

⚙️ **Fase 2: Proses Menerima Form (Menyimpan)**
- Buat logika PHP dengan tipe `POST` untuk menangkap pengisian pengunjung.
- Tarik dari file `reviews.json`, selipkan ulasan berbaru, dan *simpan kembali* ke dalam formasi JSON-nya menggunakan `file_put_contents`.

🚀 **Fase 3: Menampilkan Seluruh Komentar (Membaca)**
- Di bagian bawah HTML, telusuri (*loop*) riwayat ulasan lawas satu persatu dari file yang sama.
- Tambahkan tampilan berbentuk tanda kutip *quote* melengkung modern di setiap pesannya.
