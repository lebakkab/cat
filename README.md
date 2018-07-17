# Aplikasi Ujian Online (CAT)
Link postingan blog :
http://nur-akhwan.blogspot.co.id/2015/09/download-aplikasi-ujian-online-dengan.html

#Deskripsi
Aplikasi Ujian Online, adalah aplikasi yang digunakan untuk melakukan proses ujian , tanpa menggunakan kertas (paperless) , atau sekarang ngetren dengan nama Computer Based Test (CBT), atau Computer Assisted Test (CAT). Semua proses ujian dilakukan melalui komputer, mulai dari pembuatan soal, pengaturan kelas, pengaturan user yang bisa ikut ujian, pengaturan pemateri mengajar, sampai proses ujian, dengan memanfaatkan teknologi rekayasa web. Tipe soal yang bisa masuk ke aplikasi ujian online di pembahasan ini adalah tipe soal pilihan ganda.

#Pemrograman :
1. PHP dengan framework : Codeigniter versi  2.x.x (ane lupa versinya, yang jelas versi 2)
2. Javascript jQuery, untuk menghandel perintah-perintah javascript, dan lainya.
3. format data JSON untuk pertukaran data antara server dgn client, pada menu-menu yang ber-AJAX
4. Design UI dengan framework CSS, Twitter Bootstrap

#Level user :
1. Admin, merupakan level tertinggi dari aplikasi, bisa memanej data pemateri, peserta, jenis soal, soal, lihat hasil ujian
2. Pemateri, mempunyai akses, bisa memanage data : soal, daftar ujian, dan melihat hasil ujian
3. Peserta, mempunya akses, bisa mengikuti ujian, sesuai dengan jenis soal yang ia ikuti, yang diatur oleh  level admin, dan melihat hasil ujian.


#Yang Baru di CAT Versi DUA

Level Admin :
* Data peserta dengan fasilitas paging dan pencarian data peserta langsung.
* Import data peserta dengan format excel, dengan format data yang telah ditentukan.
* Reset password user level peserta.
* Data pemateri dengan fasilitas paging dan pencarian data pemateri langsung.
* Import data pemateri dengan format excel, dengan format data yang telah ditentukan.
* Reset password user level pemateri.
* Data soal dengan fasilitas paging dan pencarian data soal langsung.
* Import data soal dengan format excel, dengan format data yang telah ditentukan.
* Otomatis hitung statistik soal (jumlah yang menjawab benar, dan salah)
* Otomatis peserta mengikuti semua jenis soal (fasilitas setting jenis soal peserta pada CAT versi sebelumnya dihilangkan)

Level Pemateri :
* Data soal dengan fasilitas paging dan pencarian data soal langsung.
* Import data soal dengan format excel, dengan format data yang telah ditentukan.
* Otomatis hitung statistik soal (jumlah yang menjawab benar, dan salah)
* Pembuatan ujian dengan batasan waktu mulai, dan toleransi terlambat
* Ujian dengan menggunakan token (seperti UNBK)
* Fitur pembatalan keikutsertaan ujian

Level Peserta :
* Perbaikan tampilan saat mengikuti ujian.
* Pengisian token saat akan mengikuti ujian
