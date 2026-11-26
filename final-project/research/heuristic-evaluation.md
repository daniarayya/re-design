# Riset UI/UX — Proyek Akhir

## Informasi Umum
- **Nama Website:** [Biro Pemerintahan Otonomi Daerah dan Kerja Sama]
- **URL:** (https://biropemotdaks.jatengprov.go.id)
- **Halaman yang diriset:** [Beranda]
- **Tanggal Riset:** [26/11/2026]
- **Anggota Kelompok:**
  - [Denmas Kartiko Anandika Purnomo] — [Koordinator & Dokumentasi]
  - [Dania Afidzha Rayya] — [UI/UX Designer & Frontend Developer]
  - [Erly Mirta Khudhaifiyah] — [UI/UX Designer & Frontend Developer]

## Heuristic #1: Visibility of System Status
**Skor Pelanggaran (0–4):** 1.

**Temuan:**
- Penanda aktif navbar tidak sesuai dengan halaman yang dibuka.
- Beberapa perpindahan halaman tidak terdapat indikator memuat, tanpa transisi.

**Screenshot Bukti:**
![Screenshot](..src/assets/heuristic-1-memuat.png)

**Dampak ke Pengguna:**
- Dapat menimbulkan kebingungan bagi pengguna.

**Rekomendasi:**
- Memberikan loading indicator.


## Heuristic #2: Match Between the System and the Real World
**Skor Pelanggaran (0–4):** 1.

**Temuan:**
- Penamaan bagian dengan nama yang sulit dimengerti.

**Screenshot Bukti:**
![Screenshot](..src/assets/heuristic-2.png)

**Dampak ke Pengguna:**
- Dapat menyulitkan pengguna untuk menavigasi laman.

**Rekomendasi:**
- Memakai bahasa singkat yang lebih mudah dimengerti massal.


## Heuristic #3: User Control and Freedom
**Skor Pelanggaran (0–4):** 2.

**Temuan:**
- Pada proses pengiriman Saran & Masukan, user langsung diarahkan untuk melanjutkan proses, dimana tidak ada opsi untuk kembali, dan kalau kembali progress hilang.

**Screenshot Bukti:**
![Screenshot](..src/assets/heuristic-3)

**Dampak ke Pengguna:**
- Dapat menimbulkan kebingungan, frustasi jika salah tekan/proses. 

**Rekomendasi:**
- Memberikan opsi kembali untuk memastikan, progress tersimpan.
- Meletakkan opsi login ditempat lain.


## Heuristic #4: Consistency and Standarts
**Skor Pelanggaran (0–4):** 0.

**Temuan:**
- Tidak ditemukan pelanggaran signfikan.


## Heuristic #5: Error Prevention
**Skor Pelanggaran (0–4):** 3.

**Temuan:**
- Pada proses pengetikan saran dan masukan, pengecekan field nomor telepon, nama, dan pesan sangat minimal.

**Screenshot Bukti:**
![Screenshot](..src/assets/heuristic-5)

**Dampak ke Pengguna:**
- Pengguna dapat memasukan info field asal-asalan dan tetap mengirim form saran dan masukan.

**Rekomendasi:**
- Memberikan pengecekan field lebih ketat (format dan panjang input) untuk memastikan data masuk bisa ditindak lanjuti.


## Heuristic #6: Recognition Rather Than Recall
**Skor Pelanggaran (0–4):** 0.

**Temuan:**
- Tidak ditemukan pelanggaran signfikan.


## Heuristic #7: Flexibility and Efficiency of Use
**Skor Pelanggaran (0–4):** 1.

**Temuan:**
- Navigasi cepat hanya dapat menggunakan menu navbar, dimana ia juga tidak tertata rapi.

**Screenshot Bukti:**
![Screenshot](..src/assets/heuristic-7)

**Dampak ke Pengguna:**
- Pengguna tidak dapat secara naluri mana yang harus dipilih untuk menuju layanan yang mereka pilih, perluh mencermati.

**Rekomendasi:**
- Menyusun ulang pengelompokan item navbar serta akses cepat.


## Heuristic #8: Aesthetic and Minimalist Design
**Skor Pelanggaran (0–4):** 1.

**Temuan:**
- Ukuran hero banner tidak proposional dengan ukuran gambar lain pada website.
- Gambar pada hero banner ikut stretch mengikuti ukuran layar.

**Screenshot Bukti:**
![Screenshot](..src/assets/heuristic-8-propotional.png)
![Screenshot](..src/assets/heuristic-8-stretched.png)

**Dampak ke Pengguna:**
- Menurunkan kesan profesional dan kejelasan visual.

**Rekomendasi:**
- Membatasi tinggi hero banner dengan proposional, dan membenarkan masalah stretching.


## Heuristic #9: Help Users Recognize, Diagnose, and Recover from Errors
**Skor Pelanggaran (0–4):** 3.

**Temuan:**
- Pesan kesalahan maupun pemberitahuan kesalahan hanya ada teks singkat tanpa penjelasan dan solusi.

**Screenshot Bukti:**
- Tidak tersedia screenshot. Error hanya menunjukan pesan default seperti "Page under maintenance" atau "419 - Page Expired".

**Dampak ke Pengguna:**
- Pengguna non-teknis akan mengalami kesulitan memahami arti error dan mengerti cara penyelesaiannya.

**Rekomendasi:**
- Memberikan penjelasan pada halaman dengan gaya bahasa sehari-hari agar mudah dipahami beserta petunjuk penyelesaian.


## Heuristic #10: Help and Documentation
**Skor Pelanggaran (0–4):** 1.

**Temuan:**
- Tidak terdapat panduan atau alur yang bisa diikuti, namun tampilan sudah sangat sederhana.

**Screenshot Bukti:**
![Screenshot](..src/assets/heuristic-10.png)

**Dampak ke Pengguna:**
- Pengguna yang belum familiar dengan alur tidak memiliki rujukan untuk diikuti.

**Rekomendasi:**
- Menambahkan bagian bantuan ringkas (FAQ) serta petunjuk bantuan.


## Ringkasan Heuristic Evaluation

| # | Heuristik | Skor | Jumlah Temuan |
|---|---|---|---|
| 1 | Error Prevention | 3 | 1 |
| 2 | Help Users Recognize, Diagnose, and Recover from Errors | 3 | 1 |
| 3 | User Control and Freedom | 2 | 1 |
| 4 | Visibility of System Status | 1 | 2 |
| 5 | Aesthetic and Minimalist Design | 1 | 2 |
| 6 | Match Between the System and the Real World | 1 | 1 |
| 7 | Flexibility and Efficiency of Use | 1 | 1 |
| 8 | Help and Documentation | 1 | 1 |
| 9 | Consistency and Standards | 0 | 0 |
| 10 | Recognition Rather Than Recall | 0 | 0 |
| **Total** | | **14** | **10** |

### Top 3 Pain Point Terbesar:
1. Validasi kolom pada form Saran & Masukan sangat minimal (nomor telepon, nama, pesan), sehingga input asal-asalan/tidak sesuai format berpotensi lolos dan menyulitkan tindak lanjut *(Heuristic #5)*.
2. Pesan error maupun status hanya berupa teks singkat/teknis (seperti `"Page under maintenance"` atau `"419 - Page Expired"`) tanpa penjelasan penyebab dan langkah pemulihan bagi pengguna awam *(Heuristic #9)*.
3. Pengguna tidak memiliki opsi kembali yang aman saat proses pengiriman Saran & Masukan, dan kembali dari alur membuat progres isian hilang *(Heuristic #3)*.