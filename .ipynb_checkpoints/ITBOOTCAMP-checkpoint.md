# Pembukaan

# Materi 1 - GitHub

Connect, commit, create

> "Tergesa-gesa dapat berarti kurang persiapan, jadi saya kurang suka tergesa-gesa" - Pak Hendra Sigma

## Fondasi developer

- Logic & Problem Solving - Cara Berpkir
- CLI / Terminal - Tools paling powerful untuk server
- Version Control - Kerjasama tim

# Fase SDLC - Software Development Life Cycle

- Logic & Problem solving - Analysis & Design
- VCS - Development to Mainternance
- CLI - Deployment & Mainternance

# Logic & Problem solving

Algoritma adalah serangkaian langkah yang disusun secara teratur untuk mencapai tujuan atau menyelesaikan masalah. Make sure menyelesaikan suatu permasalahan dan efisiensikan algoritma tersebut. 

### TIga Fondasi Algoritma

1. Sequence
   Urutan Instruksi
   
3. Selection
   Pengambilan Keputusan. Pengambilan keputusan (Percabangan)
   
4. Iteration
   Pengulangan. For looping

# Pseudocode & Flowchart

1. Pseudocode
   Menuliskan langkahlangkah algoritma menggunakan bahasa sederhana yang menyerupai instruksi program tapi tidak terkiat pada aturan bahasa pemrograman tersebut

   ```
   MULAI 
       BACA angka
       
       JIKA angka MOD 2 = 0
           TAMPILKAN "GENAP"
        SELAIN ITU
            TAMPILKAN "Ganjil"
    SELESAI
   ```

2. Flowchart
   Menuliskan


Kapan Menggunakan Flowchart & Pseudocode

1. Gunakan Pseudocode - Ingin menggambarkan gambaran besar alur
2. Gunakan Flowchart - Ketinga ingin merinci langkah dan aturan logika sebelum diterjemahkan menjadi kode

### Pola Pikir SWE

- Problem Understanding
  Pahami dulu masalah yang terjadi. Ini penting. "dari Permasalahan ini aku bisa buat sistem ini untuk menyelesaikan masalah tersebut. 
  
- Logical Thinking
  Menentukan hubungan sebab-akibat, kondisi, aturan, batasan, dan kemungkinan yang harus ditangani sistem. Harus pinter-pinter apakah permasalahan harus diselesaikan sistem atau di luar sistem. 

- Problem Solving
  Pemecahan masalah besar menjadi bagian kecil, memilih algoritma, atau pendekatan, kemudian menguji apakah soluis tersebut benar.

- Implementation
  Mengimplementasikan solusi dengan struktur yang jelas, aman, efisien, dan mudah dikembangkan. 



### Kesalahan problem solving 

1. Langsung Coding
2. Hanya Obati Gejala: Jangan asal hapus / comment. Caritau akar masalahnya di mana.
3. Solusi Over-Engineering: Sistem over-engineering sayang kalau tidak dipakai. 
4. Tanpa Pengujian Lengkap: Make sure dulu, sistemnya sudah ditestig secara keseluruhan sebelum di deliver ke user.
5. Akibat Dampak Perubahan: Make sure pas coding jangan sampai merusak fitur ketika melakukan perbaikan kode.

# VCS - GitHub

Satu file, seluruh riwayat tersebut

Sistem yang mencatat setiap perubahan file: bisa dilihat, dibandingkan, dan dikembalikan. 

- Riwayat Perubahan
- Kolaborasi
- BackUp
- Rollback

Pentingnya version control

Tanpa mengelolaan versi yang baik, perubahan ketiga perkembanganan dapat saling menimpa atau sulit ditelusuri. Dengan Git dan GitHub.

- Conflict: Kondisi ketika perubahan yang berbeda pada bagian yang sama tidak dapat digabungkan secara otomatis. Misal ada 2 versi, itu jangan panik. Github hanya bilang "Kamu mau pakai versi mana? Yang atas atau bawah?"
- Merge: Proses menggabungkan riwayat komit atau perubahan dari satu branch ke branch lainnya.

Alr kerja git 

Make sure ambil di source main dulu untuk mengambil update terbaru -> buat branch fitur (Boleh nama berdasarkan nama anggota tim / branch berdasarkan fitur) ->  git add & git commit -> Sebelum pr jangan lupa merge dari main dulu -> PR

### Conventional commit

`<tipe>: <deskripsi singkat>`
contoh 

```md
feat: tambah fitur login
fix: perbaiki bug hitung rata-rata
docs: update cara instalasi
```

| tipe | Kegunaan |
|---|---|
| feat | Menambah fitur baru |
| fix | Memperbaiki bug |
| docs | Perubahan dokumentasi saja |
| style | format / tampilan kode, bukan logika |
| refactor | Merapikan kode tanpa ubah fungsi |
| test | Menambah atau mengubah teks | 
| chore | Tugas rutin | 

# Kesalahan GitHub

Konflik itu simpel: "Manasih kodingnan yang bener? Yg versinya si Gilang atau Arif?"

Menganggap Push itu berarti kode benar: "Selalu Pull Request dulu, jangan langsung di push. Tunggu "

# Aturan Kolaborasi

1. Bagi Tugas dengan Jelas
2. Gunakan branch Terpisah
3. Koordinasikan Perubhana
4. Commit Secara Terfokus: Simpan perubahan dengan pesan yang jelas dan spesifik
5. Review Sebelum Merge
6. Jaga Keamanan dan Perubahan

# Public & Private

Kalau Public itu nggak perlu menggunakan token buat ngepull. 