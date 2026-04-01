# Planner: Aplikasi To-Do List (Flutter)

## 1. Ringkasan Proyek
Aplikasi simpel untuk mencatat tugas sehari-hari. Aplikasi ini tidak perlu menggunakan database eksternal. Agar mudah bagi pemula, penyimpanan data cukup menggunakan **JSON lokal** atau **SharedPreferences** di dalam memori smartphone.

## 2. Tech Stack & Aturan
- **Language/Framework:** Flutter
- **Penyimpanan:** Local Storage (SharedPreferences / file JSON)
- **UI/UX:** Tampilan sederhana, bersih, dan mudah dimengerti (*Clean UI*).

## 3. Fitur Utama
- Pengguna dapat menambahkan daftar tugas baru.
- Pengguna dapat mencentang tugas yang sudah selesai (akan ada coretan).
- Pengguna dapat menghapus tugas.

## 4. Tahapan Pengerjaan (Milestones)

✅ **Fase 1: Inisialisasi Project & Desain UI**
- Buat proyek Flutter baru bernama `todo_app`.
- Buat layar kerangka utama berupa daftar (List) tugas mentah (hardcoded).
- Sediakan tombol `+` besar di pojok untuk menambah tugas.

⚙️ **Fase 2: Logika & Local Storage**
- Buat model sederhana `Task` dengan atribut `nama` dan `isSelesai`.
- Buat fungsi simpan data ke file berformat JSON statis atau SharedPreferences agar daftarnya tidak hilang ketika aplikasi ditutup.

🚀 **Fase 3: Aksi Interaktif**
- Hubungkan tombol centang (*checkbox*) di UI dengan fungsi untuk mengubah status tugas.
- Tambahkan fungsi hapus, coba buat fitur sentuh-dan-geser (*swipe to delete*) agar terasa modern namun mudah.
