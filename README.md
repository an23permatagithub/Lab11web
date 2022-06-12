# Lab11web
## Pratikum 11
untuk memenuhi tugas pemogramman web
Nama     : Antini permatasari<br>
NIM      : 312010095<br>
kelas    : TI.20.B.1<br>

### Berikut ini adalah soal tugas praktikum 11 pertemuan 12<br>
![Gambar](Gambar/Gamba1.png)<br>

1. Pertama-tama kita Buka dulu xampp controlnya lalu kalian klik start dan klik config lalu pilih PHP(php.ini)<br>
![Gambar](Gambar/Gambar2.png)<br>
2. Kemudian kalian hapus tanda (;) pada bagian extension=intl seperti berikut<br>
![Gambar](Gambar/Gambar3.png)<br>
3. Selanjutnya kita akan download CodeIgniter4 atau kalian bisa click disamping [Click Here](https://codeigniter.com/download)<br>
4. Setelah sudah di download,selanjutnya kita ubah extract rename menjadi ci4 seperti dibawah ini<br>
![Gambar](Gambar/Gambar4.png)<br>
5. Selanjutnya kita pindahkan kedalam folder htdocs > lab11_ci, setelah itu kalian buka localhost/lab11_ci/ci4/public<br>
![Gambar](Gambar/Gambar5.png)<br>
6. selanjutnya kita buka CMD dengan cara buka kembali xampp control lalu pilih bagian Shell,lalu kita tulis seperti dibawah ini<br>
![Gambar](Gambar/Gambar6.png)<br>
7. selanjutnya kitatulis php spark maka akan muncul seperti dibawah ini<br>
![Gambar](Gambar/Gambar7.png)<br>
8. kemudian kita akan mengaktifkan fitur debugging untuk mengatahui pesan error, jika belum aktif maka tampilannya akan seperti dibawah ini<br>
![Gambar](Gambar/Gambar8.png)<br>
9. Untuk mengaktifkannya kita buka env ubah atau rename menjadi .env, lalu kalian hapus (#) pada CI_ENVIRONMENT dan kita ubah juga menjadi development seperti dibawah ini<br>
![Gambar](Gambar/Gambar9.png)<br>
10. kemudian coba kita hapus tanda (;) pada Home.php, lalu akan muncul info terjadi kesalahan pada bagian tertentu seperti dibawah ini<br>
![Gambar](Gambar/Gambar10.png)<br>
11. Setelah semua selesai, selanjutnya kita akan membuat router baru seperti berikut di File Routes terletak pada file app/config/Routes.php<br>
![Gambar](Gambar/Gambar11.png)<br>
12. kemudian kita cek lagi apakah router sudah benar pada Shell di xampp control, jika sudah maka tampilannya akan menjadi seperti dibawah ini<br>
![Gambar](Gambar/Gambar12.png)<br>
13. selanjutnya kita cek about di web page, maka tampilannya akan seperti dibawah ini<br>
![Gambar](Gambar/Gambar13.png)<br>
14. Selanjutnya kita akan membuat controller dengan membuat file baru dengan nama page.php pada folder Controllers sebagai berikut.<br>
![Gambar](Gambar/Gambar14.png)<br>
Berikut ini tampilannya<br>
![Gambar](Gambar/Gambar15.png)<br>
15. lalu kita akan membuat auto routing lalu kita menambahkan syntax dibawah ini pada folder config > Routes.php<br>
![Gambar](Gambar/Gambar16.png)<br>
kemudian kita akan membuat syntax berikut pada folder Controllers > page.php<br>
![Gambar](Gambar/Gambar17.png)<br>
lalu tampilannya akan seperti berikut ini<br>
![Gambar](Gambar/Gambar18.png)<br>
16. Selanjutnya kita akan membuat tampilan web,lalu kita buat about.php dengan syntax sebagai berikut<br>
![Gambar](Gambar/Gambar19.png)<br>
Setelah itu kita rubah bagian about di page.php pada folder Controllers seperti dibawah ini<br>
![Gambar](Gambar/Gambar20.png)<br>
Berikut ini adalah tampilannya<br>
![Gambar](Gambar/Gambar21.png)<br>
17. Selanjutnya kita edit pada bagian about.php menjadi seperti berikut<br>
![Gambar](Gambar/Gambar22.png)<br>
Maka tampilan akhirnya akan menjadi sebagai berikut<br>
![Gambar](Gambar/Gambar23.png)<br>

### Jawaban Pertanyaan & Tugas
Berikut ini adalah tampilan pada semua link navigasi header<br>
1. About<br>
![Gambar](Gambar/Gambar24.png)<br>
2. Article<br>
![Gambar](Gambar/Gambar25.png)<br>
3. Contact<br>
![Gambar](Gambar/Gambar26.png)<br>

Sekian dari saya<br>
Terimakasih....<br>
