ONDA PRINTING — VERSI HTML
===========================

Versi company portfolio profesional yang menampilkan profil perusahaan,
keahlian produksi, karya pilihan, dan informasi kontak. Tidak terdapat
fitur pemesanan, pencarian produk, atau formulir permintaan penawaran.

Isi folder:
- index.html       : halaman utama
- about.html       : halaman tentang
- services.html    : halaman layanan
- portfolio.html   : halaman portofolio
- project-*.html   : enam halaman studi kasus karya
- expertise-*.html : enam halaman penjelasan lengkap keahlian
- contact.html     : halaman kontak
- assets/style.css : CSS inti website (tidak perlu diubah)
- assets/customize.css : panel pengaturan font dan ukuran yang aman diubah
- assets/script.js : menu mobile dan filter portofolio

CARA MENGUBAH UKURAN FONT
Buka assets/customize.css. Semua pengaturan diberi nomor [EDIT 00] sampai
[EDIT 10] sesuai bagian website yang dipengaruhi.

Untuk menjaga ukuran tetap konsisten, gunakan lima variabel utama di [EDIT 00]:
label, teks kecil, teks isi, teks pembuka, dan navbar. Perubahan pada bagian ini
akan diterapkan ke seluruh halaman secara bersamaan.

Untuk membesarkan angka 01, 02, dan 03 pada kartu Keahlian, cari [EDIT 05]
lalu ubah --card-number-size: 18px; menjadi, misalnya, 22px.
Simpan file lalu tekan Ctrl + F5 di browser agar CSS lama tidak tersimpan.

CARA MEMBUKA
Klik dua kali index.html. Website dapat berjalan langsung tanpa instalasi.

CARA MENGUNGGAH
Unggah seluruh isi folder ini ke public_html, htdocs, atau folder utama hosting.
Jangan mengubah susunan folder assets.

CATATAN
- Statistik dan karya pada template masih merupakan contoh yang dapat dikustomisasi.
- Halaman Contact Us memakai alamat dan telepon publik Onda Printing di Jl. Buni No. 45,
  Mangga Besar, Jakarta Barat, serta Google Maps interaktif dan petunjuk arah.
- Halaman kontak hanya berisi informasi perusahaan dan tidak memiliki form pemesanan.
- Setiap kartu portofolio membuka studi kasus dengan tantangan, pendekatan, hasil,
  lingkup pekerjaan, serta navigasi proyek sebelumnya dan berikutnya.
- Halaman Keahlian terhubung ke penjelasan Offset Printing, Digital Printing,
  Packaging, Large Format, Brand Activation, dan Creative Finishing.
- Gambar social preview sudah tersedia sebagai assets/og-onda.png.
