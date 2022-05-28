# Lab9web
<b>Nama	: Deni Luqmantoro
  
NIM		: 312010071
  
Kelas		: TI 20 D1
  
Matkul		: Pemrograman Web
  
Langkah – Langkah praktikum:</b>

1.	Buka xampp terlebih dahulu kemudian start apache dan mysql
 
![image](https://user-images.githubusercontent.com/101716699/170821171-469484cd-6b7e-4873-900c-d8b039b7653a.png)

2.	Membuat folder baru dengan nama lab8_php_modular
 
 ![image](https://user-images.githubusercontent.com/101716699/170821176-42c272ea-e84e-447f-bb8b-d144de8954b7.png)

3.	Membuat file baru dengan nama header.php seperti dibawah ini.
 
![image](https://user-images.githubusercontent.com/101716699/170821191-c6d0a037-c06b-424f-86a9-220e4b0ad4f6.png)

4.	Membuat file baru dengan nama footer.php seperti dibawah ini.
 
![image](https://user-images.githubusercontent.com/101716699/170821201-7384f6f2-499a-48f2-b27e-301ce3b09cd1.png)

5.	Membuat file baru dengan nama home.php seperti dibawah ini.
 
![image](https://user-images.githubusercontent.com/101716699/170821211-fb354353-0417-4329-b568-9a39ee0b6c4e.png)

6.	Membuat file baru dengan nama header.php seperti dibawah ini.
 
![image](https://user-images.githubusercontent.com/101716699/170821224-e67f5f15-26fa-4134-8aa8-1a35e37872c1.png)

7.	Mencoba buka pada web browser dengan link localhost/lab9_php_modular/home.php 
 
![image](https://user-images.githubusercontent.com/101716699/170821230-152a3a6a-e870-4bb3-a0bc-81a807cc07be.png)

<b>Pertanyaan dan Tugas</b>

Implementasikan konsep modularisasi pada kode program praktikum 8 tentang database, sehingga setiap halamannya memiliki template tampilan yang sama.

1.	Langkah pertama kita membuat folder baru dengan nama tugas_modular pada folder lab9_php_modular agar file lebih rapih.

![image](https://user-images.githubusercontent.com/101716699/170821247-65f2b3f8-f86a-47b7-a986-b361fdd89630.png)
 
2.	Kita ambil atau copy file koneksi.php dan hapus.php dari praktikum 8 kemudian simpan pada folder lab9_php_modular/tugas_modular
 
![image](https://user-images.githubusercontent.com/101716699/170821276-f65c8704-6d60-4ea7-b0c3-25c99551c39e.png)
![image](https://user-images.githubusercontent.com/101716699/170821283-df89f7f3-4813-499a-a854-bb055a96d102.png)

3.	Kemudian buat file baru dengan nama header_index.php, kita ambil bagian header sesuai dengan yang dibutuhkan pada file index.php di praktikum 8.
 
![image](https://user-images.githubusercontent.com/101716699/170821301-20e1290e-a6f5-40aa-a66b-27cb73087078.png)

4.	Buat file footer_index.php yang kita ambil dari index.php pada praktikum 8
 
![image](https://user-images.githubusercontent.com/101716699/170821308-55f8ed2a-64ce-45e0-8fa1-257d6ba590c9.png)

5.	Buat file index.php, kita ambil bagian body atau content dari index.php pada praktikum 8, dan kemudian tambahkan syntax <?php require('header_index.php'); ?> pada bagian atas body dan <?php require('footer_index.php'); ?> pada bagian bawah body index.php
 
 ![image](https://user-images.githubusercontent.com/101716699/170821337-bbc235ec-4e09-4625-8376-87bbd25fa5c0.png)
![image](https://user-images.githubusercontent.com/101716699/170821343-c3056b64-182e-4156-bc4d-454d5c1da2d3.png)

Simpan dan coba buka pada browser dengan link http://localhost/lab9_php_modular/tugas_modular/index.php
 
![image](https://user-images.githubusercontent.com/101716699/170821395-4ee9709e-26ce-47ce-8ea5-35fc853f16dd.png)

6.	Selanjutnya kita modularkan halaman tambah dengan membuat file baru header_tambah.php, kita ambil bagian header sesuai dengan yang dibutuhkan pada file tambah.php di praktikum 8.
 
 ![image](https://user-images.githubusercontent.com/101716699/170821408-5701dd7c-ead0-4501-a1a2-9642e3f3f677.png)
![image](https://user-images.githubusercontent.com/101716699/170821410-998d1432-4492-47de-aab6-a7072a7e4f12.png)

7.	Buat file footer_tambah.php yang kita ambil dari tambah.php pada praktikum 8
 
![image](https://user-images.githubusercontent.com/101716699/170821423-84e4f1cc-0173-4cb2-8839-a46f4d5f19bb.png)

8.	Buat file tambah.php, kita ambil bagian body atau content dari tambah.php pada praktikum 8, dan kemudian tambahkan syntax <?php require('header_tambah.php'); ?> pada bagian atas body dan <?php require('footer_tambah.php'); ?> pada bagian bawah body tambah.php
 
 ![image](https://user-images.githubusercontent.com/101716699/170821439-608c088e-df4e-4114-a71c-ab128005b5d5.png)
![image](https://user-images.githubusercontent.com/101716699/170821441-39976d7f-7584-4ea7-9348-69ccedbe450c.png)

Simpan dan coba buka pada browser dengan klik nav tambah atau dengan link http://localhost/lab9_php_modular/tugas_modular/tambah.php
 
![image](https://user-images.githubusercontent.com/101716699/170821455-3e677aae-8c70-4a83-bcc0-c5c83c533232.png)

9.	Selanjutnya kita modularkan halaman ubah dengan membuat file baru header_ubah.php, kita ambil bagian header sesuai dengan yang dibutuhkan pada file ubah.php di praktikum 8.
 
 ![image](https://user-images.githubusercontent.com/101716699/170821479-d34ea98d-d314-447e-8e1c-3fa761389235.png)
![image](https://user-images.githubusercontent.com/101716699/170821482-e10964d3-4943-4e67-831f-dcad66a592f9.png)
![image](https://user-images.githubusercontent.com/101716699/170821485-15e8c703-acb7-4976-8dfd-0218e7cb489f.png)
![image](https://user-images.githubusercontent.com/101716699/170821487-2f99346d-9c69-4c4d-a6c3-043c621791b7.png)

10.	Buat file footer_ubah.php yang kita ambil dari ubah.php pada praktikum 8
 
![image](https://user-images.githubusercontent.com/101716699/170821501-7ace06be-c7cd-4847-9130-7d81c7651941.png)

11.	Buat file ubah.php, kita ambil bagian body atau content dari ubah.php pada praktikum 8, dan kemudian tambahkan syntax <?php require('header_ubah.php'); ?> pada bagian atas body dan <?php require('footer_ubah.php'); ?> pada bagian bawah body ubah.php
 
 ![image](https://user-images.githubusercontent.com/101716699/170821512-7aea7083-9039-40f4-a340-3dfe8a6184e2.png)
![image](https://user-images.githubusercontent.com/101716699/170821515-32302bbd-739f-440b-844d-0d439a755b04.png)

Simpan dan coba buka pada browser dengan klik nav ubah.
 
![image](https://user-images.githubusercontent.com/101716699/170821656-34881b9a-d3b8-4239-9dc6-5f5151b63296.png)

