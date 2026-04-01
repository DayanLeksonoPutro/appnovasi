# Project Name: Landing Page Portofolio (HTML Statis)

## 1. Ringkasan Proyek
Halaman situs web satu laman (One-Page) untuk memperkenalkan sosok developer, keahlian yang dimilikinya, dan tempat unjuk diri keahlian (*portofolio*). Disengaja dibangun sangat mentah dan statis, sehingga sangat mudah dieksplorasi pemula tanpa perlu mengatur interaksi server atau *database*.
- **Target Pengguna:** Umum / Perekrut

## 2. Tech Stack & Aturan
- **Framework Utama:** HTML Statis
- **Target Platform:** Web (Harus responsif di HP)
- **State Management:** Tidak perlu
- **Penyimpanan:** Tanpa Database (Semua tulisan diketik langsung di file HTML)
- **Desain UI:** Modern Minimalis (memukau mata dan menarik)
- **Color Palette:** Bebaskan AI (Auto)
- **Typography (Huruf):** Roboto / Inter
- **Bahasa Aplikasi:** Bahasa Indonesia Formal
- **Icon / Gaya Animasi:** Animasi Melayang (Hover) premium. Manakala kursor menyentuh ikon maka dia sedikit melonjak

## 3. Struktur Menu (Navigasi)
- **Halaman Gulir (Sections):**
    - Puncak Halaman (*Hero Banner*) dengan foto wajah bundar dan perkenalan tajam.
    - Bagian "Sisi Kemampuan / Keahlianku".
- **Aksi Khusus:** Pintasan Media Sosial (ikon mengapung sederhana).

## 4. Struktur Folder yang Diinginkan
```text
/
 ┣ index.html
 ┗ style.css
```

## 5. Tahapan Pengerjaan (Milestones)

✅ **Fase 1: Kerangka Tulang Dasar (HTML5)**
- Buat satu folder serta berkas `index.html`.
- Ciptakan *Semantic tags* bersih semisal `<header>`, `<section id="about">`, dsb.
- Sematkan tulisan placeholder semacam "Hai! Namaku..." di pucuk muka.

🎨 **Fase 2: Gaya Warnaan Moderen (CSS)**
- Padankan dengan file `style.css` terpisah.
- Gunakan gaya *Flexbox* (tampilan lentur) untuk menitikberatkan teks atau gambar di tengah.
- Ubah jenis huruf (*font*) usang menjadi huruf tegak premium dari Google (seperti Roboto / Inter).

🚀 **Fase 3: Responsif Beres dan Hidup Lincah**
- Hadirkan sedikit gerakan pemanis misalnya, manakala kursor tetikus menyentuh ikon (*Hover*) maka dia sedikit melonjak.
- Tata sedemikian rupa tata riasnya saat ia menyusut lebar layar HP (*Media Query*) agar layar fotonya tidak kelewat batasan.
