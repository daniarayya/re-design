# Rasional Desain

## Kaitan Temuan Riset → Keputusan Desain

| # | Temuan Riset | Keputusan Desain | Penjelasan |
|---|---|---|---|
| 1 | Tampilan navbar pada perangkat mobile masih mengalami kendala, bahkan pada ukuran layar tertentu menu navigasi dapat menghilang. | Menggunakan hamburger menu pada tampilan mobile dan menyempurnakan aturan responsive pada CSS. | Agar navigasi tetap dapat diakses dengan mudah melalui berbagai ukuran layar tanpa membuat tampilan header terlalu penuh. |
| 2 | Bagian berita pada halaman Beranda sebelumnya belum menampilkan gambar dokumentasi. | Menambahkan gambar dokumentasi pada berita utama dan daftar berita lainnya. | Agar informasi berita lebih menarik secara visual dan pengguna dapat mengetahui gambaran kegiatan sebelum membaca isi berita. |
| 3 | Susunan kotak Visi dan Misi belum sepenuhnya menyesuaikan ukuran layar mobile. | Mengubah susunan Visi dan Misi menjadi vertikal pada perangkat mobile. | Agar informasi lebih mudah dibaca dan tidak terlihat terlalu sempit ketika diakses melalui ponsel. |
| 4 | Menu Layanan memiliki beberapa pilihan layanan yang perlu ditampilkan tanpa memenuhi area navigasi. | Menggunakan dropdown menu untuk pilihan SIKEJAM dan SEDUNIA. | Agar navigasi lebih ringkas, terstruktur, dan pengguna dapat memilih layanan yang dibutuhkan dengan mudah. |
| 5 | Tampilan Dokumen dan Regulasi membutuhkan penyesuaian agar konten tetap tertata pada layar kecil. | Menggunakan Flexbox untuk mengatur posisi pencarian, filter, dan daftar dokumen. | Agar susunan konten lebih fleksibel dan dapat menyesuaikan ukuran layar desktop maupun mobile. |
| 6 | Informasi kontak dan formulir membutuhkan penyesuaian posisi pada perangkat dengan ukuran layar berbeda. | Mengatur tata letak informasi kontak dan formulir menggunakan Flexbox. | Agar kedua bagian tetap tertata dengan baik dan nyaman digunakan tanpa saling bertumpuk. |

## Prinsip Desain yang Diterapkan

1. **Consistency (Konsistensi)**

   Menjaga keseragaman tampilan header, footer, warna, tipografi, tombol, dan komponen pada seluruh halaman website. Hal ini dilakukan agar pengguna mendapatkan pengalaman visual yang konsisten ketika berpindah halaman.

2. **Responsive Design (Desain Responsif)**

   Menyesuaikan ukuran dan posisi elemen menggunakan Flexbox, satuan relatif, serta media query agar website tetap proporsional ketika diakses melalui desktop, tablet, maupun perangkat mobile.

3. **Visibility (Keterlihatan Informasi)**

   Menampilkan informasi penting seperti navigasi, berita, program prioritas, dokumen, dan informasi kontak dengan susunan yang jelas agar mudah ditemukan oleh pengguna.

4. **Minimalism (Kesederhanaan)**

   Mengatur elemen antarmuka agar tidak terlalu padat, salah satunya melalui penggunaan dropdown pada menu Layanan sehingga pilihan menu tetap terorganisir.

5. **Accessibility (Kemudahan Akses)**

   Menyesuaikan tata letak dan ukuran elemen agar informasi serta fitur website tetap mudah diakses dan digunakan melalui berbagai perangkat.

---

## Anotasi Rasional Desain

### Halaman Beranda

1. **Header & Navigation**
   Penempatan logo dan navigasi dalam satu area header untuk memudahkan pengguna mengenali identitas instansi dan mengakses halaman website.

2. **Hero Section**
   Penggunaan gambar gedung sebagai latar utama untuk memperkuat identitas visual instansi, disertai judul dan deskripsi singkat sebagai pengenalan website.

3. **Berita & Informasi**
   Penambahan gambar dokumentasi dan pembagian berita utama dengan berita lainnya agar informasi lebih mudah dikenali dan menarik untuk dibaca.

4. **Program Prioritas**
   Penyajian program dalam bentuk kartu yang menggabungkan gambar, deskripsi, dan daftar program agar informasi lebih terstruktur.

5. **Informasi Terbaru**
   Pemisahan informasi terbaru dalam kotak khusus agar pengumuman dan regulasi lebih mudah ditemukan.

6. **Footer**
   Penggunaan warna navy serta penempatan identitas instansi dan media sosial untuk menjaga konsistensi tampilan sekaligus memberikan informasi tambahan kepada pengguna.