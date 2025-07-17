Generator Prompt Gambar Powered by Gemini Ai
====================================================

1\. Deskripsi Aplikasi
----------------------

**Generator Prompt Gambar Gemini** adalah sebuah aplikasi web yang dirancang untuk membantu pengguna membuat _prompt_ (perintah teks) yang detail dan efektif untuk digunakan pada model AI generator gambar seperti Imagen, Midjourney, atau Stable Diffusion.

Akses aplikasi di [https://promptgenerator.isparmo.com/](https://promptgenerator.isparmo.com/)

Aplikasi ini memanfaatkan kecerdasan Google Gemini untuk mengubah ide-ide sederhana atau deskripsi produk menjadi paragraf prompt yang kaya akan detail visual, gaya, pencahayaan, dan komposisi. Tujuannya adalah untuk menjembatani kesenjangan antara visi kreatif pengguna dan hasil yang mampu diproduksi oleh AI, sehingga menghasilkan gambar yang lebih akurat dan berkualitas tinggi.

2\. Penjelasan Fitur
--------------------

Aplikasi ini memiliki beberapa fitur utama yang dirancang untuk memberikan fleksibilitas dan kemudahan penggunaan.

### a. Input Kunci API Gemini

*   **Fungsi:** Kolom ini adalah tempat Anda memasukkan Kunci API pribadi dari Google AI Studio. Kunci ini diperlukan agar aplikasi dapat berkomunikasi dengan model Gemini.
    
*   **Keamanan:** Kunci API Anda hanya digunakan di dalam browser Anda untuk melakukan panggilan ke API Google dan tidak pernah disimpan atau dikirim ke server lain.
    
*   **Bantuan:** Terdapat tautan (Bagaimana cara mendapatkannya?) yang akan membuka jendela pop-up dengan panduan langkah demi langkah untuk memperoleh Kunci API Anda.
    

### b. Pilihan Tipe Prompt

Ini adalah fitur inti yang memungkinkan Anda menyesuaikan input berdasarkan tujuan akhir Anda. Aplikasi akan secara dinamis mengubah formulir yang ditampilkan sesuai dengan tipe yang Anda pilih.

*   **Gambar Umum:** Untuk kebutuhan pembuatan gambar atau ilustrasi umum berdasarkan ide kreatif.
    
*   **Desain Logo:** Dikhususkan untuk membuat prompt yang berfokus pada elemen desain identitas visual (brand).
    
*   **Desain Kemasan Produk:** Untuk menghasilkan ide dan visualisasi desain kemasan sebuah produk.
    
*   **Foto Produk Promosi:** Untuk membuat prompt yang menghasilkan foto produk bergaya komersial untuk kebutuhan pemasaran.
    

### c. Formulir Input Dinamis

Setiap tipe prompt memiliki serangkaian kolom input yang dirancang khusus untuk mengumpulkan informasi yang paling relevan.

*   **Untuk Gambar Umum:**
    
    *   **Ide Dasar:** Deskripsi singkat tentang apa yang ingin Anda gambar.
        
    *   **Format/Rasio Aspek:** Pilihan rasio aspek gambar (persegi, lanskap, potret).
        
    *   **Gaya Visual & Pencahayaan:** Pilihan dropdown untuk gaya umum dan input teks untuk kustomisasi yang lebih spesifik.
        
*   **Untuk Desain Logo:**
    
    *   **Deskripsi Brand:** Esensi atau cerita di balik brand Anda.
        
    *   **Nama Brand / Teks Logo:** Teks yang mungkin ingin Anda sertakan dalam logo.
        
    *   **Gaya Logo:** Input teks untuk mendeskripsikan gaya yang diinginkan (misalnya, minimalis, modern, vektor).
        
*   **Untuk Desain Kemasan Produk:**
    
    *   **Nama & Deskripsi Produk:** Detail tentang produk dan untuk siapa produk itu dibuat.
        
    *   **Tipe Kemasan:** Bentuk fisik kemasan (misalnya, kantong, kotak, botol).
        
    *   **Gaya Desain:** Tampilan dan nuansa keseluruhan dari kemasan.
        
*   **Untuk Foto Produk Promosi:**
    
    *   **Nama & Deskripsi Produk:** Detail produk dan fitur utamanya.
        
    *   **Latar / Setting Foto:** Lingkungan di mana produk akan difoto.
        
    *   **Gaya Foto:** Jenis pemotretan (misalnya, gaya hidup, close-up, foto aksi).
        

### d. Tombol "Buat Prompt!"

Tombol ini akan memicu proses. Aplikasi akan mengumpulkan semua input Anda, menyusunnya menjadi sebuah permintaan khusus untuk Gemini, dan mengirimkannya melalui API.

### e. Area Hasil

*   **Loader:** Sebuah ikon animasi akan muncul untuk menandakan bahwa permintaan sedang diproses.
    
*   **Pesan Kesalahan:** Jika terjadi masalah (misalnya, Kunci API salah atau input kosong), sebuah kotak pesan berwarna merah akan muncul dengan penjelasan kesalahan.
    
*   **Output Prompt:** Jika berhasil, prompt yang telah disempurnakan oleh Gemini akan ditampilkan dalam sebuah kotak.
    
*   **Tombol Salin:** Tombol praktis untuk menyalin seluruh prompt yang dihasilkan ke clipboard Anda dengan sekali klik.
    

3\. Cara Menggunakan Aplikasi
-----------------------------

Ikuti langkah-langkah sederhana ini untuk mendapatkan hasil maksimal dari Generator Prompt.

1.  **Dapatkan dan Masukkan Kunci API:**
    
    *   Klik tautan (Bagaimana cara mendapatkannya?) untuk melihat petunjuk.
        
    *   Buka Google AI Studio, buat Kunci API baru, lalu salin.
        
    *   Tempelkan Kunci API Anda ke dalam kolom yang tersedia di aplikasi.
        
2.  **Pilih Tipe Prompt:**
    
    *   Dari menu dropdown "Pilih Tipe Prompt", pilih tujuan Anda: Gambar Umum, Desain Logo, Desain Kemasan Produk, atau Foto Produk Promosi.
        
3.  **Isi Kolom yang Sesuai:**
    
    *   Formulir akan berubah secara otomatis. Isi semua kolom yang relevan dengan informasi sedetail mungkin. Semakin baik input Anda, semakin baik pula prompt yang akan dihasilkan.
        
4.  **Klik "Buat Prompt!":**
    
    *   Setelah semua informasi terisi, klik tombol besar berwarna biru untuk memulai proses generasi.
        
5.  **Tunggu dan Lihat Hasilnya:**
    
    *   Biarkan aplikasi bekerja selama beberapa saat. Ikon loader akan menunjukkan bahwa proses sedang berjalan.
        
    *   Prompt akhir Anda akan muncul di dalam kotak output.
        
6.  **Salin dan Gunakan:**
    
    *   Klik tombol Salin untuk menyalin prompt tersebut.
        
    *   Tempelkan prompt yang sudah disalin ke platform generator gambar AI favorit Anda (misalnya, Aplikasi Gemini, Midjourney, dll.) untuk membuat gambar Anda.
