## Praktikum 1 - Pemrograman Web
~~~
Subkhan Fadilah
311910410
TI.19.A.2
~~~
## LANGKAH 1
Buka VS Code dan buat file HTML baru. Setelah itu buat struktur dasar HTML
~~~
<!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar</title>
</head>
<body>

</body>
</html>
~~~
![langkah 1](https://user-images.githubusercontent.com/56526583/112930217-191bfb80-9144-11eb-94e2-f8380fce2111.png)
## LANGKAH 2
Membuat 2 buah paragraf dan atur atribut paragraf (Rata Kiri / Rata Kanan / Rata Tengah / Sama Rata)
~~~
<!-- Ini adalah paragraf pertama -->
<p align="center">Kami sedang belajar \HTML dasar, pada matakuliah Pemrograman
    Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>

<!-- Ini adalah paragraf kedua -->
<p align="right">Ini merupakan sebuah paragraf yang terdiri dari beberapa
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat
    dengan menggunakan tag dasar html.</p>
~~~
![langkah 2](https://user-images.githubusercontent.com/56526583/112931541-92b4e900-9146-11eb-85bd-6b5b7cfea80c.png)
## LANGKAH 3
Menambahkan judul menggunakan Tag Heading (h1, h2, h3, h4, h5, h6). Semakin besar angka Tag Heading, Semakin kecil ukuran Headingnya.
~~~
<!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>

<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>
~~~
![langkah 3](https://user-images.githubusercontent.com/56526583/112931770-f0e1cc00-9146-11eb-912c-9841037a38f2.png)
## LANGKAH 4
Lakukan pemformatan teks yang ada pada paragraf yang sudah ada sebelumnya, mengacu kepada penjelasan materi pemformatan teks, sehingga tampilannya seperti berikut.
~~~
<p align="left">Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman
    Web</b> di Prodi <i>Teknik Informatika</i> <ins>Universitas Pelita Bangsa</ins>. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>
~~~
![langkah 4](https://user-images.githubusercontent.com/56526583/112932883-eb858100-9148-11eb-880a-3226a38ce996.png)
## LANGKAH 5
Menyisipkan Gambar dan mengatur ukuran gambar. Sebelum menyisipkan gambar, file HTML yg sudah dibuat dijadikan satu bersama dengan gambar yg akan disisipkan.
![langkah 5](https://user-images.githubusercontent.com/56526583/112932967-18d22f00-9149-11eb-9d3f-db79790fda9b.png)
~~~
<!-- sub judul paragraf -->
<h3>Menambahkan Gambar</h3>
<!-- menambahkan gambar pada dokumen -->
<img src="logo.png" width="200" title="Logo Univeritas Pelita Bangsa">
~~~
![langkah (5)](https://user-images.githubusercontent.com/56526583/112933141-78303f00-9149-11eb-945d-e67dc64e6c56.png)
## LANGKAH 6
Menambahkan Hyperlink. Tambahkan hyperlink pada dokumen sebelum heading 1.
~~~
<!-- menambahkan link navigasi -->
<nav>
    <a href="lab1_tag_dasar.html">Dasar HTML</a>
    <a href="lab1_halaman2.html">Halaman 2</a>
    <a href="http://www.google.com">Halaman Web Eksternal Google</a>
    </nav>
    <hr>
~~~
![langkah 6](https://user-images.githubusercontent.com/56526583/112933430-07d5ed80-914a-11eb-9f4d-a7510d3ce129.png)
## LANGKAH 7
Membuat halaman ke 2 yg akan terhubung dengan halaman pertama menggunakana Hyperlink.
~~~
<!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar</title>
</head>
<body>

<h1>Halaman Ke 2</h1>

<p align="justify">Ini adalah halaman kedua.</p>

</body>
</html>
~~~
![langkah 7](https://user-images.githubusercontent.com/56526583/112933553-47043e80-914a-11eb-8153-d2fa90e879cc.png)
## Jawab Pertanyaan Berikut
1. Lakukan perubahan pada code sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?
~~~
Ada error ketika saya salah penulisan Heading <h1> tidak ditutup dengan </h1> jadi tidak terjadi perubahan.
~~~
2. Apa perbedaan dari tag <p> dengan tag <br> berikan penjelasannya!
~~~
Dari hasil praktek saya sendiri, perbedaan  tag <br> jarak enter nya lebih jauh 1 line dibandingkan
dengan tag <p> yg jarak enter nya tidak terlalu jauh.
~~~
3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!
~~~
atribut tittle pada tag <img> digunakan untuk memberi judul pada gambar yg disisipkan, sedangkan
atribut alt pada tag <img> digunakan untuk memberi deskripsi pada gambar yg disisipkan
~~~
4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
~~~
Untuk mempertahankan proporsi gambar, namun tetap membuat gambar menjadi besar/kecil, cantumkan
hanya salah satu atribut saja (width saja atau height saja, namun tidak keduanya). Misalkan
jika kita menetapkan atribut width=200px (tanpa mencantumkan height), maka web browser akan
menampilkan gambar dengan lebar 200px, dan menghitung secara otomatis tinggi gambar agar gambar
tetap proporsional.
~~~
5. Pada link tambahkan atribut target dengan nilai atribut bervariasi (_blank, _self, _top, _parent), apa yang terjadi pada masing-masing nilai antribut tersebut?
~~~
Nilai _blank akan membuka link/halaman di tab baru.
Nilai _self akan membuka link/halaman di tab saat ini.
Nilai _top membuka link/halaman dan membatalkan semua frame.
Nilai _parent membuka link/halaman pada parent frame.
~~~





    
    
    
    
    



