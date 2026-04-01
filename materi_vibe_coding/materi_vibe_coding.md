# Materi Vibe Coding Menggunakan Gemini CLI dan Antigravity

## 1. Apa Itu Vibe Coding?
**Vibe Coding** adalah istilah pengembangan perangkat lunak modern di mana pengembang (atau *creator*) tidak lagi harus menulis setiap baris kode secara manual (mengetik baris demi baris). Alih-alih, Anda bertindak sebagai seorang "Sutradara" atau "Arsitek", sementara AI Agents—dalam hal ini **Gemini CLI dan Antigravity**—bertindak sebagai programmer yang menulis, membongkar, dan menjalankan kode berdasarkan instruksi Anda. Anda cukup memberikan arahan (*vibe/prompt*) yang jelas, dan AI akan mengeksekusinya.

## 2. Mengenal Tools Kita: Gemini CLI dan Antigravity
* **Gemini CLI (Command Line Interface):** Antarmuka yang memungkinkan interaksi langsung dengan model AI Google Gemini melalui terminal. Ini memberikan akses cepat ke kemampuan penalaran dan *code generation* yang sangat kuat.
* **Antigravity:** Agentik AI asisten *(AI Agent)* tingkat lanjut. Antigravity tidak hanya bisa mengobrol atau menulis kode, tetapi juga memiliki **kemampuan untuk bertindak** (*Agentic Ability*). Ia bisa:
  * Membaca dan mengedit file secara otomatis.
  * Menjalankan perintah terminal (seperti `npm run dev` atau `flutter run`).
  * Mengecek error (debugging) dan memperbaikinya secara langsung.
  * Berinteraksi dengan sistem secara berkesinambungan.

## 3. Cara Kerja / Siklus Vibe Coding
1. **Brainstorming & Planning:** Anda merencanakan apa yang ingin dibuat (membuat dokumen Planner).
2. **Prompting (Giving the Vibe):** Anda memberikan instruksi awal kepada Antigravity mengenai proyek, struktur, atau fitur.
3. **Execution & Steering:** Antigravity akan mulai membuat file, menulis kode, dan mengeksekusinya di workspace. Anda mengawasi, memberikan koreksi ("steer"), menyetujui perintah terminal yang dijalankan, atau meminta perubahan.
4. **Review & Refine:** Setelah kode berjalan, Anda memberikan masukan visual atau fungional agar Antigravity bisa melakukan *finishing* (Micro-animations, UI styling yang premium, dll).

## 4. Praktik Terbaik (Best Practices)
* **Pecah Menjadi Langkah Kecil:** Jangan meminta AI membuat aplikasi raksasa dalam 1 prompt. Mintalah dalam tahapan: "Buat kerangka strukturnya dulu", lalu "Implementasi UI", dan "Sambungkan API".
* **Gunakan Dokumen Perencanaan (Planner):** Sediakan file seperti `plan.md` yang merinci fitur agar AI selalu memiliki pedoman yang solid.
* **Review Perintah Terminal:** Karena Antigravity bisa mengeksekusi perintah (*command*), selalu baca perintah apa yang ingin dijalankannya sebelum Anda setujui (*approve*).
* **Beri Konteks yang Jelas:** Selalu sebutkan bahasa pemrograman, framework, arsitektur, atau gaya UI *(misal: Modern, Dark Mode, Minimalis)* yang dinginkan.
