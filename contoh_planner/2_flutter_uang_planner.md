# Planner: Pencatat Pengeluaran Harian (Flutter)

## 1. Ringkasan Proyek
Aplikasi pencatat pengeluaran uang saku sehari-hari yang sangat mudah dipahami. Sama sekali tidak menggunakan backend/API, hanya mengandalkan file JSON lokal. Sangat cocok sebagai batu loncatan awal bagi developer pemula.

## 2. Tech Stack & Aturan
- **Language/Framework:** Flutter
- **Penyimpanan:** JSON Local di penyimpanan HP (tanpa kuota internet).
- **UI/UX:** Tampilan cerah, fokus pada jumlah angka pengeluaran (misalnya angka berwarna merah).

## 3. Fitur Utama
- Menambahkan data pengeluaran (berisi: Nama Barang & Harga).
- Melihat daftar semua pengeluaran.
- Menampilkan Total Pengeluaran di layar teratas.

## 4. Tahapan Pengerjaan (Milestones)

✅ **Fase 1: Desain Tampilan Dasar**
- Buat proyek baru dengan nama `catat_uang`.
- Buat kotak warna-warni cantik di atas untuk wadah tulisan "Total Pengeluaran".
- Di bawahnya, sediakan list kosong panjang. 

⚙️ **Fase 2: Logika Penyimpanan JSON**
- Buat file `.json` lokal lewat kode Dart atau penyimpanan sederhana di state.
- Hubungkan proses ini ketika user memencet tombol "Simpan Pengeluaran Baru" dari formulir pengisian.

🛠️ **Fase 3: Perhitungan Total**
- Buat fungsi otomatis yang menghitung (menjumlahkan) seruruh harga pengeluaran dari file json.
- Tampilkan total angkanya ke layar atas (*header*), pastikan ada simbol "Rp" agar terlihat nyata.
