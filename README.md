# Kalkulator Al-Mirats (Android App)
Kalkulator Al-Mirats adalah aplikasi Android native yang dibangun dengan Kotlin untuk mempermudah perhitungan pembagian waris berdasarkan syariat Islam (Ilmu Faraid). Proyek ini memadukan kompleksitas matematika hukum waris dengan pengalaman pengguna (UX) yang modern dan bersih.
## Fitur Utama
- **Kalkulator Faraid**: Perhitungan dinamis bagian masing-masing ahli waris secara presisi.
- **Fikih Faraid Engine**: Mendukung konsep pembagian waris yang kompleks seperti *Ashobah*, *Ashobah bil-Ghair* (rasio 2:1), *Radd*, dan *Aul*.
- **Harta Bersih**: Pengurangan otomatis untuk hutang, wasiat, dan biaya pengurusan jenazah sebelum pembagian harta waris dilakukan.
- **Auto-Save State**: Menggunakan Room database untuk menyimpan input terakhir pengguna.
- **Modul Edukasi**: Menyediakan artikel dan tutorial untuk mempelajari ilmu Faraid.
- **Feedback Firestore**: Kirim masukan/saran langsung ke Firebase cloud database.
## Tech Stack
- **Language**: Kotlin
- **Database**: Room Database (Local) & Firebase Firestore (Cloud)
- **UI & Layout**: XML, ViewBinding, ConstraintLayout, Material Components
- **Concurrency**: Kotlin Coroutines
