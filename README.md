# Website Portofolio

Ini adalah project website portofolio milik saya. Website ini didesain dengan tema gelap bernuansa ungu menggunakan custom CSS dan framework Bootstrap 5.

## Tampilan Setiap Section

* **Home (Hero Section):** <img width="946" height="479" alt="home" src="https://github.com/user-attachments/assets/9572dd11-c54f-489a-b884-8cbf8dde298f" />

* **About Me Section:** <img width="949" height="479" alt="about" src="https://github.com/user-attachments/assets/5a2a4050-df98-4f3c-8a52-7c0f6c152d93" />

* **Certificates Section:** <img width="950" height="481" alt="certifitace" src="https://github.com/user-attachments/assets/0ed2c411-2251-49dc-b2a2-e96b19fa8f6d" />


## Penjelasan Code Setiap Section/Fitur

1. **Navbar:** Navigasi dibuat menggunakan tag `<nav>` dengan class `fixed-top` dari Bootstrap agar posisi menu selalu menempel di atas saat di-scroll. Desainnya dimodifikasi dengan efek *backdrop-filter blur* dan warna hitam transparan melalui CSS. Menu navigasi ditampilkan secara sejajar tanpa dropdown.

2. **Home:**
   Menggunakan sistem grid Bootstrap (`row` dan `col-md-6`) untuk membagi area menjadi dua sisi teks dan gambar. Latar belakang section ini menggunakan `linear-gradient` pada CSS untuk transisi warna yang halus dari hitam pekat ke ungu gelap. 

3. **About Me:**
   Section ini menampilkan deskripsi diri dan visualisasi skill. Tata letaknya menggunakan grid system. Untuk bagian skill, saya menggunakan komponen `progress` dan `progress-bar` dari Bootstrap yang warnanya telah disesuaikan melalui CSS (variabel `--purple-main` dan `--purple-dark`) untuk mencocokkan tema utama website.

4. **Certificates:**
   Daftar sertifikat dibuat menggunakan komponen `card` dari Bootstrap yang dibungkus dalam grid `col-md-4` agar berjajar rapi (tiga kolom di layar besar, dan otomatis turun ke bawah di layar kecil). Setiap kartu diberikan gaya tambahan melalui CSS seperti `border-radius` dan pewarnaan khusus.

## Teknologi yang Digunakan

* **HTML5:** Sebagai struktur dasar halaman.
* **CSS3 (Custom):** Menggunakan CSS Variables untuk memanajemen palet warna ungu dan hitam secara konsisten.
* **Bootstrap 5:** Digunakan untuk mempermudah layouting dengan Grid System dan komponen bawaan (Card, Progress Bar, Button).
* **Google Fonts:** Menggunakan jenis huruf 'Poppins' untuk memberikan kesan modern dan rapi pada tipografi.
