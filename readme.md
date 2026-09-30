LAPORAN PRAKTIKUM 2 PEMOGRAMAN WEB
Praktikum 2 — HTML LanjutanPraktikum 2 — HTML Lanjutan
Repository ini berisi hasil Praktikum 2 Pemrograman Web dengan materi HTML Lanjutan.
Praktikum ini membahas penggunaan tabel HTML, form, berbagai jenis input, semantic HTML, multimedia, serta validasi form dasar. Praktikum dikerjakan menggunakan HTML sebagai fokus utama, tanpa menggunakan CSS dan JavaScript sebagai fokus utama.
Tujuan Praktikum
1.	Memahami penggunaan tabel pada HTML.
2.	Memahami penggunaan form dan berbagai jenis input HTML.
3.	Menerapkan semantic HTML untuk menyusun struktur halaman.
4.	Menambahkan elemen multimedia pada halaman web.
5.	Menerapkan validasi form dasar menggunakan atribut HTML.
________________________________________
Langkah-Langkah Praktikum
1. Membuat Tabel Data Mahasiswa
Pada modul, setelah tabel dibuat mahasiswa diminta menambahkan minimal tiga data mahasiswa.
Hasil
Tabel menampilkan data mahasiswa dalam bentuk baris dan kolom, dengan NIM, nama, dan program studi sebagai informasi utama.
Screenshot
Screenshot 1 — Tabel Data Mahasiswa

![Screenshot Tabel Data Mahasiswa](images/step1.png)
________________________________________
2. Mengembangkan Tabel dengan <thead>, <tbody>, dan <tfoot>
Modul juga meminta melakukan eksperimen dengan mengubah data, menambahkan baris, serta menggunakan colspan untuk menggabungkan sel.
Penjelasan colspan
Atribut colspan digunakan untuk membuat satu sel tabel menempati beberapa kolom.
Contohnya:
<td colspan="2">Rata-rata</td>
Artinya sel Rata-rata akan menempati dua kolom.
Hasil
Tabel memiliki struktur header, data utama, dan footer. Pada bagian footer, dua kolom digabung menggunakan colspan.
Screenshot

 ![Screenshot Tabel Data Mahasiswa](images/step2.png)
________________________________________
3. Membuat Form Registrasi Mahasiswa
Form digunakan untuk menerima data dari pengguna.
Pada praktikum dibuat form registrasi mahasiswa yang memiliki input:
•	Nama lengkap
•	Email
•	Password
•	Tanggal lahir
•	Tombol Daftar
•	Tombol Reset
Kode tersebut mengikuti contoh form registrasi yang terdapat pada modul.
Hasil
Form memungkinkan pengguna memasukkan informasi pribadi melalui beberapa jenis input HTML.
Screenshot
 
 ![Screenshot Tabel Data Mahasiswa](images/step3.png)
________________________________________
4. Radio Button dan Checkbox
Langkah keempat mempraktikkan penggunaan radio button dan checkbox.
Radio Button
Radio button digunakan untuk memilih satu pilihan dari beberapa pilihan yang memiliki name yang sama.
Contoh penggunaan radio button dan checkbox tersebut sesuai dengan langkah praktikum pada modul.
Hasil
Radio button memungkinkan pengguna memilih satu jenis kelamin, sedangkan checkbox memungkinkan pengguna memilih lebih dari satu keahlian.
Screenshot
 
 ![Screenshot Tabel Data Mahasiswa](images/step4.png)
________________________________________
5. Select dan Textarea
Langkah kelima menggunakan <select> untuk memilih program studi dan <textarea> untuk memasukkan alamat.
Modul menggunakan <select> dengan pilihan Teknik Informatika dan Sistem Informasi serta <textarea> untuk alamat.
Hasil
Pengguna dapat memilih program studi dari daftar pilihan dan memasukkan alamat dalam area teks yang lebih besar.
Screenshot
 
 ![Screenshot Tabel Data Mahasiswa](images/step5.png)
________________________________________

6. Validasi Form Dasar
HTML menyediakan validasi dasar melalui beberapa atribut, seperti:
•	required
•	minlength
•	maxlength
•	min
•	max
•	type
•	pattern
Pada langkah ini digunakan required, minlength, min, dan max.
Pengujian
Coba tekan tombol Kirim tanpa mengisi data. Browser akan memberikan pesan validasi karena beberapa input memiliki atribut required.
Selain itu:
•	Nama harus memiliki minimal 3 karakter.
•	Umur harus berada antara 17 dan 60.
•	Email harus menggunakan format email yang valid.
Instruksi untuk mencoba validasi tersebut terdapat pada modul.
Screenshot
 
 ![Screenshot Tabel Data Mahasiswa](images/step6.png)
________________________________________
7. Membuat Halaman Semantic HTML
Semantic HTML digunakan untuk membuat struktur halaman yang memiliki makna yang jelas.
Elemen yang digunakan:
•	<header> — kepala halaman atau bagian.
•	<nav> — navigasi.
•	<main> — konten utama.
•	<section> — kelompok konten.
•	<article> — konten mandiri.
•	<aside> — konten pelengkap.
•	<footer> — bagian kaki halaman.
Fungsi masing-masing elemen tersebut dijelaskan dalam modul.
Kode tersebut mengikuti struktur semantic HTML pada langkah ketujuh modul.
Hasil
Halaman memiliki struktur yang lebih jelas karena bagian navigasi, konten utama, artikel, informasi tambahan, dan footer dipisahkan berdasarkan fungsi masing-masing.
Screenshot
 
 ![Screenshot Tabel Data Mahasiswa](images/step7.png)
________________________________________
8. Menambahkan Multimedia
HTML menyediakan elemen <audio> dan <video> untuk menampilkan multimedia pada halaman web.
Struktur Folder
praktikum-2-html-lanjutan/
├── index.html
└── media/
    ├── audio.mp3
    └── video.mp4
Struktur folder tersebut sesuai dengan contoh pada modul.
Hasil
Halaman dapat menampilkan file audio dan video menggunakan elemen HTML5 <audio> dan <video>.
Screenshot
 
 ![Screenshot Tabel Data Mahasiswa](images/step8.png)
________________________________________
9. Proyek Mini — Form Biodata Mahasiswa
Pada proyek mini, seluruh materi yang telah dipelajari digabungkan menjadi satu halaman biodata mahasiswa.
Proyek ini mencakup:
•	Semantic HTML
•	Tabel data
•	Form
•	Validasi dasar
•	Select
•	Textarea
•	Multimedia
Modul secara langsung meminta mahasiswa menggabungkan materi tersebut dalam proyek mini biodata mahasiswa.

Kode proyek mini di atas mengikuti struktur yang diberikan dalam modul, termasuk semantic structure, tabel data mahasiswa, form, required, select, dan textarea.
Screenshot
 
 ![Screenshot Tabel Data Mahasiswa](images/step9.png)
________________________________________
