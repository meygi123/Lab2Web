# Lab2Web
Membuat from input

Tabel membuat data karyawan menggunakan phpmyadmin
![Screenshot (21)](https://user-images.githubusercontent.com/127826461/227115872-a180dcc3-fee4-4c3b-b181-af12712e18be.png)

jika ingin menambahkan usia di phpmyadmin gunakan code dibawah ini:
SELECT *,YEAR(CURRENT_DATE()) - YEAR(tgl_lahir) AS usia FROM `karyawan` ORDER by id_karyawan DESC
![Screenshot (26)](https://user-images.githubusercontent.com/127826461/227117605-f995946b-b497-4d0d-98ce-475996f67c71.png)

kemudian untuk mengakses direktory tersebut pada web server dengan menggunakan akses URL :http://localhost/lab2_php_dasar/
![Screenshot (22)](https://user-images.githubusercontent.com/127826461/227116930-73e9fa8d-3f9c-4d90-9b7b-7d60920a7db3.png)

Hasil program php untuk menampilkan nama, tanggal lahir dan pekerjaan
![Screenshot (24)](https://user-images.githubusercontent.com/127826461/227118085-29d76bda-1752-4f4a-b833-56f88f6ebf0e.png)
