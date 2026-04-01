# Project Name: Aplikasi To-Do List (Flutter)

## 1. Ringkasan Proyek
Aplikasi simpel untuk mencatat tugas sehari-hari. Aplikasi ini tidak perlu menggunakan database eksternal. Agar mudah bagi pemula, penyimpanan data cukup menggunakan JSON lokal atau SharedPreferences di dalam memori smartphone.
- **Target Pengguna:** Umum

## 2. Tech Stack & Aturan
- **Framework Utama:** Flutter
- **Target Platform:** Android / iOS
- **State Management:** Tidak perlu (Bawaan saja)
- **Penyimpanan:** Local JSON / SharedPreferences
- **Desain UI:** Clean UI (sederhana, bersih, dan mudah dimengerti)
- **Color Palette:** Bebaskan AI (Auto)
- **Typography (Huruf):** Inter
- **Bahasa Aplikasi:** Bahasa Indonesia Formal
- **Icon / Gaya Animasi:** Gunakan Material Icons dengan Ripple Effects yang lembut

## 3. Struktur Menu (Navigasi)
- **Halaman Utama:**
    - Daftar (List) tugas mentah (hardcoded)
- **Aksi Khusus (Floating Button):** Tombol Tambah (+) besar di pojok untuk menambah tugas.

## 4. Struktur Folder yang Diinginkan
```text
lib/
 ┣ models/
 ┃ ┗ task.dart (atribut: nama dan isSelesai)
 ┣ screens/
 ┃ ┗ home_screen.dart
 ┗ main.dart
```

## 5. Tahapan Pengerjaan (Milestones)

✅ **Fase 1: Inisialisasi Project & Desain UI**
- Buat proyek Flutter baru bernama `todo_app`.
- Buat layar kerangka utama berupa daftar (List) tugas mentah (hardcoded).
- Sediakan tombol `+` besar di pojok untuk menambah tugas.

⚙️ **Fase 2: Logika & Local Storage**
- Buat model sederhana `Task` dengan atribut `nama` dan `isSelesai`.
- Buat fungsi simpan data ke file berformat JSON statis atau SharedPreferences agar daftarnya tidak hilang ketika aplikasi ditutup.

🚀 **Fase 3: Aksi Interaktif**
- Hubungkan tombol centang (*checkbox*) di UI dengan fungsi untuk mengubah status tugas (coretan saat selesai).
- Tambahkan fungsi hapus, coba buat fitur sentuh-dan-geser (*swipe to delete*) agar terasa modern namun mudah.
