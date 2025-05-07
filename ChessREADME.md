OOP chese game

ini adalah proyek permainan catur berbasis Object Oriented Programming dengan dukungan Ai dan sistem validasi gerakan lengkap. 
permainan dapat dimainkan antara dua pemain atau melawan AI, serta dilengkapi dengan fitur timer dan pengecekan kondisi akhir pemain.

# fitur-fitur utama
- Tampilan papan catur yang diperbarui setiap giliran
- Pewarnaan papan menggunakan ANSI Code
- validasi gerakan legal sesuai aturan catur
- Dukungan permainan dengan atau tanpa AI 
- sistem timer untuk mengatur batas waktu pemain
- Deteksi:
  Skak
  Skak mat
  Stalemate
  
# Alur permainan 
1. Inisialisasi papan dan bidak (Player memulai)
2. Pemain memasukan langkah sesuai bidak yang dipilih
3. Sistem memvalidasi langkah:
   - jika langkah/move tidak valid, maka diminta input ulang
   - jika valid, melanjutkan permainan
   - Jika valid dan timer aktif:
      * Dicek apakah waktu habis atau tidak
      * Jika habis, lawan menang
4. langkah yang valid akan mengubah posisi papan
5. sistem akan memerikas kondisi:
   - Skak / Skak / Stalemate
6. Jika game berakhir, tampilkan hasil
7. jika belum:
   - Jika lawan adalah AI, hitung langkah secara algoritmik
   - Jika bukan AI, giliran berpindah ke pemain berikutnya

# struktur Program (berbasis OOP)
   1. Bord = Menyimpan dan memperbarui posisi bidak
   2. Widget = Menampilkan cetak menu, tampilan papan, dan informasi
   3. GameStatus = Menangani status permainan seperti skak dan skakmat
   4. Player = entitas pemain manusia atau AI
   5. cheespiece = Kelas induk untuk semua buah catur
   6. Color = Pewarnaan teks dan latar sesuai kondisi sel/bidak

# Cara menjalankan
https://github.com/Renaiacl/Renaiacl/edit/main/ChessREADME.md

# catatan
1. AI yang digunakan dalam program ini masih ada kekurangan (Pemula)

