# My Diary Adel 
# Project UTS Pemrograman Mobile 2
**Nama:** Adellia Rezqi Salmabillah
**NIM:** 312410395
**Kelas:** TI.24.A4/I241D
**My Diary Adel** adalah aplikasi buku harian digital berbasis Android yang dirancang sebagai sahabat emosional pengguna. Aplikasi ini menggabungkan fitur *journaling* tradisional dengan **Adel AI**, sebuah chatbot cerdas yang bekerja secara luring (offline) untuk mendengarkan curhatan pengguna kapan saja tanpa memerlukan koneksi internet.

---

## Fitur Utama

- **Journaling with Prompts**: Membantu pengguna mengatasi *writer's block* dengan memberikan pertanyaan reflektif setiap kali ingin menulis.
- **Adel AI (Offline Chatbot)**: Chatbot interaktif yang menggunakan logika *Keyword Grouping* untuk memberikan respon emosional yang relevan (Senang, Sedih, Marah, Capek, dll).
- **Daily Reminders**: Pengingat otomatis pagi dan malam agar pengguna konsisten melakukan refleksi diri.
- **Privacy Focused**: Semua catatan dan percakapan disimpan secara lokal di perangkat pengguna menggunakan database SQLite, menjamin kerahasiaan 100%.
- **Minimalist UI/UX**: Desain antarmuka dengan tema *soft pink* yang menenangkan untuk memberikan kenyamanan saat menulis.

---

## Detail Teknis (Tech Stack)

Aplikasi ini dikembangkan dengan spesifikasi teknis sebagai berikut:

- **Bahasa Pemrograman**: Java
- **IDE**: Android Studio (Ladybug/Flamingo+)
- **Min SDK**: API 24 (Android 7.0 Nougat)
- **Target SDK**: API 34 (Android 14)
- **Database**: SQLite (Local Storage)
- **Logika AI**: Pattern Matching & Keyword Grouping (100+ Logika Respon)
- **Library**: 
    - Google Material Design Components
    - AppCompat & ConstraintLayout

---

## Alur Aplikasi (User Journey)

1. **Splash Screen**: Sambutan hangat dari Adel AI saat aplikasi dibuka.
2. **Daily Prompt**: User diberikan satu pertanyaan inspiratif sebelum masuk ke dashboard.
3. **Dashboard**: Menampilkan daftar catatan diary yang sudah dibuat.
4. **Writing Mode**: User menulis cerita, perasaan, atau kejadian hari ini.
5. **AI Chat Mode**: User dapat mengobrol dengan Adel jika butuh teman bicara atau motivasi instan.

---

## Struktur Folder Penting

- `app/src/main/java/.../AiChatActivity.java`: Logika utama chatbot Adel AI.
- `app/src/main/java/.../WriteDiaryActivity.java`: Logika pengolahan dan penyimpanan catatan.
- `app/src/main/res/layout/`: Kumpulan desain antarmuka XML.
- `app/src/main/res/drawable/`: Kumpulan aset visual dan desain tombol kustom.

---

## Logika Adel AI
Adel AI bekerja dengan memindai kata kunci (keywords) dari input pengguna. 
Contoh:
- Input: *"Aku merasa **sedih** hari ini."*
- Logika: Mencocokkan kata kunci `sedih` -> Mengambil respon acak dari kategori **Empati**.
- Respon: *"Sini Adel peluk... 🤗 Menangis itu nggak papa kok, Adel ada di sini buat kamu."*

---

##  Tentang Pengembang
Aplikasi ini dikembangkan sebagai solusi digital untuk kesehatan mental, memberikan ruang aman bagi siapa saja untuk bercerita tanpa takut dihakimi.

> "Karena setiap cerita layak untuk didengarkan." — **Adel**