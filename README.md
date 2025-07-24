MUDAH BELAJAR SQL & DATA ANALISIS: Aplikasi Web Interaktif
==========================================================

Selamat datang di dokumentasi resmi untuk aplikasi **MUDAH BELAJAR SQL & DATA ANALISIS**. Ini adalah alat berbasis web yang dirancang untuk menjadi teman belajar dan bekerja bagi siapa saja yang ingin menguasai analisis data dan SQL.

Akses ke aplikasi ini kunjungi [https://belajarsql.isparmo.com/](https://belajarsql.isparmo.com/)

Deskripsi
---------

Aplikasi ini adalah sebuah _playground_ analisis data lengkap yang berjalan sepenuhnya di peramban (browser) Anda. Tanpa perlu instalasi database atau perangkat lunak yang rumit, Anda bisa langsung mengunggah file CSV, menganalisis kualitas datanya, membersihkannya secara otomatis, dan menjalankan kueri SQL secara _real-time_.

Tidak hanya itu, aplikasi ini ditenagai oleh kecerdasan buatan (AI) melalui Gemini API, yang memungkinkan Anda untuk bertanya kepada "Ahli Analisis Data" dan menguji kemampuan Anda dengan kuis SQL interaktif yang dibuat secara dinamis.

### Untuk Siapa Aplikasi Ini?

*   **Pelajar & Mahasiswa:** Sangat ideal untuk mereka yang baru mulai belajar SQL dan konsep-konsep dasar ilmu data.
    
*   **Analis Data Pemula:** Alat yang cepat untuk melakukan eksplorasi dan pembersihan data awal tanpa perlu membuka aplikasi yang berat.
    
*   **Pengajar & Instruktur:** Dapat digunakan sebagai alat bantu ajar interaktif untuk mendemonstrasikan konsep SQL dan pembersihan data.
    
*   **Siapa Saja yang Ingin Tahu:** Bagi Anda yang penasaran dengan data dan ingin mencoba menjalankan kueri SQL pada set data nyata.
    

Fitur-Fitur Utama
-----------------

Aplikasi ini dikemas dengan berbagai fitur canggih untuk memaksimalkan pengalaman belajar dan analisis Anda.

### 1\. Sumber Data Fleksibel

*   **Unggah CSV Sendiri:** Anda dapat mengunggah file CSV dari komputer Anda untuk dianalisis. Aplikasi ini cerdas dan dapat menangani file besar serta format CSV yang kompleks.
    
*   **Data Contoh Bawaan:** Tidak punya data? Gunakan tabel data\_karyawan yang sudah disediakan, lengkap dengan berbagai masalah data umum (nilai kosong, duplikat, spasi, dll.) yang siap untuk Anda perbaiki.
    
*   **Dataset Publik:** Terdapat tautan untuk mengunduh dataset publik populer seperti Titanic, Big Mac Index, dan lainnya, yang bisa langsung Anda gunakan untuk berlatih.
    

### 2\. Alat Kualitas Data Otomatis

*   **Analisis Data Cepat:** Dengan satu klik, aplikasi akan memindai tabel aktif Anda dan membuat laporan terperinci mengenai masalah kualitas data, termasuk:
    
    *   **Nilai Kosong (NULL):** Menemukan baris dengan data yang hilang.
        
    *   **Spasi Berlebih:** Mendeteksi spasi yang tidak perlu di awal atau akhir data.
        
    *   **Data Duplikat:** Mengidentifikasi baris data yang identik (dengan cerdas mengabaikan kolom ID).
        
*   **Log Transparan:** Laporan analisis menyertakan kueri SQL yang dijalankan di balik layar, memberikan transparansi penuh tentang bagaimana masalah tersebut ditemukan.
    

### 3\. Pembersihan Data (Data Cleaning) Sekali Klik

*   **Buat Versi Bersih:** Alih-alih mengubah data asli, aplikasi ini akan membuat tabel baru (\_clean) yang berisi versi data yang sudah bersih.
    
*   **Proses Komprehensif:** Proses pembersihan otomatis mencakup:
    
    *   Menduplikasi tabel asli.
        
    *   Menghapus spasi berlebih.
        
    *   Menyeragamkan format huruf (menjadi _lowercase_).
        
    *   Mengisi nilai kosong dengan nilai _default_ yang masuk akal.
        
    *   Menghapus baris data yang duplikat.
        
*   **Log Proses:** Setiap langkah pembersihan, termasuk kueri SQL yang digunakan, ditampilkan dalam log _real-time_ agar Anda bisa memahami prosesnya.
    

### 4\. SQL Runner Interaktif

*   **Editor Kueri Langsung:** Tulis dan jalankan kueri SQL apa pun pada tabel aktif dan lihat hasilnya secara instan.
    
*   **Contoh Kueri Dinamis:** Terdapat 12+ contoh kueri siap pakai yang bisa Anda pilih, mulai dari SELECT sederhana hingga GROUP BY dan CASE. Contoh ini akan otomatis menyesuaikan dengan tabel yang sedang Anda gunakan.
    
*   **Ekspor Hasil:** Hasil kueri Anda dapat diekspor menjadi file CSV dengan mudah.
    

### 5\. Fitur AI "Tanya Ahli" (Didukung oleh Gemini)

*   **Asisten Cerdas:** Aktifkan fitur ini dengan kunci API Gemini Anda dan dapatkan akses ke ahli analisis data virtual.
    
*   **Pertanyaan Kontekstual:** Ajukan pertanyaan dalam bahasa natural (misalnya, "Berapa rata-rata gaji di kota Jakarta?") dan AI akan menjawabnya berdasarkan data pada tabel aktif Anda.
    
*   **Penjelasan Konsep:** Anda juga bisa bertanya tentang konsep SQL (misalnya, "Jelaskan apa itu JOIN") untuk mendapatkan penjelasan yang mudah dipahami.
    

### 6\. Kuis SQL Interaktif

*   **Kuis Dinamis:** Minta AI untuk membuat kuis dengan 5, 10, 15, atau 20 soal yang unik dan relevan dengan data yang sedang Anda analisis.
    
*   **Umpan Balik Langsung:** Setelah menjawab setiap soal, Anda akan langsung mendapatkan umpan balik apakah jawaban Anda benar atau salah, lengkap dengan penjelasan mendalam dari AI.
    
*   **Laporan Skor:** Di akhir kuis, Anda akan melihat rekap skor akhir untuk mengukur pemahaman Anda.
    

Cara Menggunakan Aplikasi
-------------------------
Akses ke aplikasi ini kunjungi [https://belajarsql.isparmo.com/](https://belajarsql.isparmo.com/)

1.  **Pilih Sumber Data Anda:**
    
    *   Secara _default_, aplikasi akan memuat tabel contoh data\_karyawan.
        
    *   Untuk menggunakan data sendiri, klik tombol **"Unggah File CSV"**.
        
    *   Untuk kembali ke data contoh setelah mengunggah file, klik tombol **"Hapus CSV"**.
        
2.  **Analisis & Bersihkan Data (Opsional):**
    
    *   Klik tombol **"Analisis Data"** untuk melihat laporan kualitas data pada tabel aktif.
        
    *   Jika ditemukan masalah, klik **"Data Cleaning"**. Sebuah tabel baru yang bersih (misal: data\_karyawan\_clean) akan dibuat. Anda bisa beralih antara tabel kotor dan bersih menggunakan tombol yang tersedia.
        
3.  **Jalankan Kueri SQL:**
    
    *   Pilih salah satu contoh kueri dari _dropdown_ untuk memulai, atau tulis kueri Anda sendiri di area teks.
        
    *   Klik **"Run Query"** untuk melihat hasilnya di panel kanan.
        
4.  **Gunakan Fitur AI (Opsional):**
    
    *   Klik tombol **"?"** melayang di pojok kanan bawah.
        
    *   Ikuti petunjuk untuk mendapatkan dan menyimpan **Kunci API Gemini** Anda.
        
    *   Setelah kunci tersimpan, Anda bisa mulai bertanya kepada ahli AI atau membuat kuis interaktif.
