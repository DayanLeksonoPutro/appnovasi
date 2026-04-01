# Project Name: [Isi Nama Proyek Anda]

## 1. Ringkasan Proyek
*[Tuliskan 1-3 kalimat simpel tentang aplikasi apa yang ingin Anda buat dan tujuan utamanya.]*
**Contoh:** Aplikasi pencatatan jadwal olahraga harian (*Fitness Tracker*) sederhana, untuk membantu pengguna mengingat latihan yang sudah dan belum dikerjakan.
- **Target Pengguna:** [Anak-anak / Remaja / Profesional / Umum] *(Opsional: Membantu AI menyesuaikan gaya bahasa dan ukuran tombol UI yang pas)*

## 2. Tech Stack & Aturan
*(Pilih opsi yang sesuai dengan proyek Anda, atau tulis opsi Anda sendiri. Hapus yang tidak dipakai)*
- **Framework Utama:** [Flutter / PHP / HTML Statis / React Native]
- **Target Platform:** [Android / iOS / Web / Desktop]
- **State Management:** [Riverpod / Provider / BLoC / Tidak perlu (Bawaan saja)]
- **Penyimpanan:** [Local JSON / SharedPreferences / Tanpa Database / MySQL]
- **Desain UI:** [Modern Minimalis / Clean UI / Dark Mode Elegan / Ceria & Colorful]
- **Color Palette:** [Biru Laut & Putih / Hitam & Emas / Bebaskan AI (Auto)]
- **Typography (Huruf):** [Inter / Poppins / Roboto / Comic Sans (untuk anak)] *(Direkomendasikan dari Google Fonts)*
- **Bahasa Aplikasi:** [Bahasa Indonesia Formal / Bahasa Gaul / English] *(Agar AI tidak menggunakan bahasa campur aduk di tampilan aplikasi Anda)*
- **Icon / Gaya Animasi:** [Gunakan Material Icons dengan Ripple Effects yang lembut / Animasi Melayang (Hover) premium]

## 3. Struktur Menu (Navigasi)
*(Tentukan bagaimana letak menu ditaruh, misal di bawah layaknya menu HP atau disebelah)*
- **Bottom Navigation Bar (Menu Bawah):**
    - [Menu 1: misal Beranda]
    - [Menu 2: misal List Data]
    - [Menu 3: misal Pengaturan]
- **Aksi Khusus (Floating Button):** [Misal: Tombol Tambah (+) melayang di kanan bawah layar]

## 4. Struktur Folder yang Diinginkan
*(Biarkan kosongan jika Anda membebaskan AI berkreasi, atau beri patokan seperti di bawah)*
```text
lib/
 ┣ core/ (warna, teks, ukuran standar)
 ┣ features/
 ┃ ┣ [fitur_a]/ (misal: home)
 ┃ ┗ [fitur_b]/ (misal: settings)
 ┣ models/ (skema penyimpanan data)
 ┗ main.dart
```

## 5. Tahapan Pengerjaan (Milestones)
*(Pecah proyek menjadi tugas-tugas kecil agar AI asisten lebih fokus dan minim error)*

✅ **Fase 1: Inisialisasi & Rangka Utama**
- Buat proyek kosong bernama `[nama_proyek]`.
- Atur pewarnaan dasar dan jenis *font* (huruf) ke seluruh kerangka aplikasi.
- Buat kerangka menu navigasi utama yang kosong tapi bisa diklik.

📝 **Fase 2: Pembuatan Tampilan (UI) Mentah**
- Buat layar halaman `[Nama Halaman Utama]`. Gunakan data simulasi (palsu/sementara) saja dulu.
- Buat form input/tombol di halaman `[Nama Halaman Kedua]`.

⚙️ **Fase 3: Logika dan Data Nyata**
- Buat mekanisme penyimpan data sementara (misal membuat dan membaca ke file [JSON/SharedPreferences]).
- Sambungkan tombol di UI agar bisa menghapus/menambah data aslinya.

🚀 **Fase 4: Sentuhan Akhir (Finishing)**
- Poles dengan *micro-animations* / transisi perpindahan halaman yang memukau.
- Bereskan *error* gaya (lint errors) dan pastikan kodenya terlihat rapi *(Clean Code)*.
