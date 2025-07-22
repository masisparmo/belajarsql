Mudah Belajar SQL - Live SQL Query Runner
=========================================

Ini adalah aplikasi web interaktif yang dirancang untuk membantu pengguna belajar dan berlatih SQL langsung di browser. Aplikasi ini menyediakan lingkungan yang aman untuk menjalankan kueri SQL pada dataset sampel tanpa memerlukan pengaturan database yang rumit. Fokus utamanya adalah pada kasus penggunaan praktis seperti pembersihan data (_data cleaning_) dan manipulasi data.

Akses ke aplikasi ini kunjungi [https://belajarsql.isparmo.com/](https://belajarsql.isparmo.com/)

Deskripsi
---------

Aplikasi "Mudah Belajar SQL" adalah alat bantu belajar mandiri yang memungkinkan siapa saja untuk menulis dan mengeksekusi kueri SQL secara _real-time_. Pengguna disajikan dengan tabel data sampel karyawan yang sengaja dibuat "tidak bersih" (misalnya, mengandung spasi ekstra, kapitalisasi tidak konsisten, dan nilai NULL). Hal ini bertujuan untuk memberikan tantangan praktis yang sering dihadapi dalam analisis data di dunia nyata.

Aplikasi ini sepenuhnya berjalan di sisi klien (_client-side_) menggunakan pustaka sql.js (SQLite yang dikompilasi ke WebAssembly), yang berarti tidak ada data yang dikirim ke server, menjadikannya cepat, aman, dan dapat diakses bahkan secara offline setelah halaman dimuat.

Fitur-fitur Utama
-----------------

*   **SQL Editor Langsung:** Tulis dan jalankan kueri SQL di area teks dan lihat hasilnya secara instan.
    
*   **Dataset Sampel Praktis:** Belajar dengan dataset karyawan yang mencerminkan tantangan umum dalam data, seperti data yang tidak konsisten dan nilai yang hilang.
    
*   **Contoh Kueri Terpandu:** Terdapat menu _dropdown_ dengan beberapa contoh kueri siap pakai, mulai dari perintah dasar SELECT hingga teknik pembersihan data menggunakan TRIM(), LOWER(), COALESCE(), dan pengelompokan dengan GROUP BY.
    
*   **Panduan SQL Lengkap:** Tombol "Bantuan SQL" membuka jendela modal yang berisi panduan komprehensif tentang sintaks dan fungsi SQL, termasuk:
    
    *   Analisis dan Pembersihan Data.
        
    *   Data Manipulation Language (DML): SELECT, INSERT, UPDATE, DELETE.
        
    *   Fungsi Agregat: COUNT(), SUM(), AVG(), GROUP BY.
        
    *   Klausa Umum: ORDER BY, LIMIT.
        
    *   Data Definition Language (DDL): CREATE, ALTER, DROP.
        
*   **Tampilan Hasil Dinamis:** Hasil kueri ditampilkan dalam format tabel yang jelas dan mudah dibaca.
    
*   **Penanganan Kesalahan:** Jika kueri mengandung kesalahan sintaks, pesan error yang informatif akan ditampilkan untuk membantu pengguna memperbaikinya.
    
*   **Ekspor ke CSV:** Hasil kueri yang berhasil dapat diekspor ke dalam format file .csv dengan satu kali klik.
    

Cara Menggunakan
----------------

1.  **Buka Aplikasi:** [https://belajarsql.isparmo.com/](https://belajarsql.isparmo.com/)
    
2.  **Pilih atau Tulis Kueri:**
    
    *   **Gunakan Contoh:** Pilih salah satu contoh kueri dari menu _dropdown_ "Pilih Contoh Kueri". Area teks akan otomatis terisi, dan kueri akan langsung dijalankan.
        
    *   **Tulis Sendiri:** Tulis kueri SQL Anda sendiri di dalam area teks. Anda dapat merujuk pada tabel karyawan yang ditampilkan di bagian atas.
        
3.  **Jalankan Kueri:** Klik tombol **"Run Query"** untuk mengeksekusi kueri yang ada di area teks.
    
4.  **Lihat Hasil:**
    
    *   Jika berhasil, hasilnya akan muncul dalam tabel di sebelah kanan.
        
    *   Jika gagal, pesan kesalahan akan muncul di bawah area hasil.
        
5.  **Ekspor Hasil (Opsional):** Jika kueri menghasilkan data, tombol **"Export to CSV"** akan muncul. Klik tombol ini untuk mengunduh hasilnya.
    
6.  **Gunakan Bantuan:** Jika Anda memerlukan referensi tentang sintaks SQL, klik tombol **"Bantuan SQL"** untuk membuka panduan lengkap.
    

Aplikasi ini ideal untuk pemula yang ingin memahami konsep dasar SQL dan analis data yang ingin dengan cepat menguji atau memvalidasi kueri pada dataset kecil.
