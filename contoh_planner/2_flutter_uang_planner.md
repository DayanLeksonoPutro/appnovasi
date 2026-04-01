# Project Name: Pencatat Pengeluaran Harian (Flutter)

## 1. Ringkasan Proyek
Aplikasi pencatat pengeluaran uang saku sehari-hari yang sangat mudah dipahami. Sama sekali tidak menggunakan backend/API, hanya mengandalkan file JSON lokal. Sangat cocok sebagai batu loncatan awal bagi developer pemula.
- **Target Pengguna:** Umum / Remaja

## 2. Tech Stack & Aturan
- **Framework Utama:** Flutter
- **Target Platform:** Android / iOS
- **State Management:** Tidak perlu (Bawaan saja)
- **Penyimpanan:** Local JSON di penyimpanan HP (tanpa kuota internet)
- **Desain UI:** Tampilan cerah, fokus pada jumlah angka pengeluaran (misalnya angka berwarna merah)
- **Color Palette:** Bebaskan AI (Auto)
- **Typography (Huruf):** Roboto
- **Bahasa Aplikasi:** Bahasa Indonesia Formal
- **Icon / Gaya Animasi:** Gunakan Material Icons dengan Ripple Effects yang lembut

## 3. Struktur Menu (Navigasi)
- **Halaman Utama:**
    - Kotak warna-warni cantik di atas untuk wadah tulisan "Total Pengeluaran"
    - List kosong panjang di bawahnya untuk daftar pengeluaran
- **Aksi Khusus (Floating Button):** Tombol "Simpan Pengeluaran Baru" untuk membuka formulir pengisian data.

## 4. Struktur Folder yang Diinginkan
```text
lib/
 ┣ models/
 ┃ ┗ pengeluaran.dart (atribut: Nama Barang & Harga)
 ┣ screens/
 ┃ ┗ home_screen.dart
 ┗ main.dart
```

## 5. Tahapan Pengerjaan (Milestones)

✅ **Fase 1: Desain Tampilan Dasar**
- Buat proyek baru dengan nama `catat_uang`.
- Buat kotak warna-warni cantik di atas untuk wadah tulisan "Total Pengeluaran".
- Di bawahnya, sediakan list kosong panjang. 

⚙️ **Fase 2: Logika Penyimpanan JSON**
- Buat file `.json` lokal lewat kode Dart atau penyimpanan sederhana di state.
- Hubungkan proses ini ketika user memencet tombol "Simpan Pengeluaran Baru" dari formulir pengisian.

🛠️ **Fase 3: Perhitungan Total**
- Buat fungsi otomatis yang menghitung (menjumlahkan) seluruh harga pengeluaran dari file json.
- Tampilkan total angkanya ke layar atas (*header*), pastikan ada simbol "Rp" agar terlihat nyata.
- Tampilkan daftar semua pengeluaran.
