# Pemograman Web
~~~
Nama : Andry Prasetia Perdana
NIM  : 311910284
Kelas: TI 19 C1
UNIVERSITAS PELITA BANGSA
~~~
## Langkah 1
Buka VSCode dan buat file HTML baru. Setelah itu buat struktur dasar HTML.
~~~<!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar</title>
</head>
<body>

</body>
</html>
~~~
![1](https://user-images.githubusercontent.com/81818989/113437473-db9fc280-9410-11eb-904d-c69a15678e4a.png)

## Langkah 2
Selanjutnya buatlah beberapa paragraf sederhana sebagai berikut.
~~~
<!-- Ini adalah paragraf pertama -->
<p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi 
    Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat 
    adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar 
    HTML.</p>
    
<!-- Ini adalah paragraf kedua -->
<p>Ini merupakan sebuah paragraf yang terdiri dari beberapa 
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat 
    dengan menggunakan tag dasar html.</p>
~~~
![2](https://user-images.githubusercontent.com/81818989/113437586-13a70580-9411-11eb-958f-8f229d34848d.png)

## Langkah 3
Selanjutnya memformatkan text, silakan ubah-ubah nilai atributnya (align => justify, left, right, dan center) untuk melihat perbedaan lainnya.
~~~
<!-- Ini adalah paragraf pertama -->
<p align=”center”>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman 
    Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama 
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal 
    tag-tag dasar HTML.</p>
 <!-- Ini adalah paragraf kedua -->
<p align=”right”>Ini merupakan sebuah paragraf yang terdiri dari beberapa 
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat 
    dengan menggunakan tag dasar html.</p>
~~~
![3](https://user-images.githubusercontent.com/81818989/113438012-ead34000-9411-11eb-8132-56df39cb1a98.png)
Kemudian tambahkan judul h1 sebelum paragraf pertama dan tambahkan sub judul h2 sebelum paragraf kedua.
~~~
<!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>
<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>
~~~
![4](https://user-images.githubusercontent.com/81818989/113438717-59fd6400-9413-11eb-8ff9-a8b1ca91335f.png)

## Langkah 4
Lakukan pemformatan teks yang ada pada paragraf yang sudah ada sebelumnya, mengacu kepada penjelasan materi pemformatan teks, sehingga tampilannya seperti berikut.
~~~
<p align="left">Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman
    Web</b> di Prodi <i>Teknik Informatika</i> <ins>Universitas Pelita Bangsa</ins>. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>
~~~
![Screenshot (25)](https://user-images.githubusercontent.com/81818989/113439320-8bc2fa80-9414-11eb-889e-4628649fbc52.png)

## Langkah 5
Untuk menyisipkan gambar, siapkan gambar yang akan disisipkan pada halaman web, kemudian simpan file gambar tersebut satu folder dengan file dokumen html.
![Screenshot (22)](https://user-images.githubusercontent.com/81818989/113439369-a5fcd880-9414-11eb-9c91-90e4df01d69d.png)
Kemudian tambahkan tag img setelah paragraf yang kedua, dengan menambahkan heading 3 sebelumnya.
~~~
<!-- sub judul paragraf -->
<h3>Menambahkan Gambar</h3>
<!-- menambahkan gambar pada dokumen -->
<img src="logo_upb.png" width="200" title="Logo Univeritas Pelita Bangsa">
~~~
![Screenshot (23)](https://user-images.githubusercontent.com/81818989/113439439-c6c52e00-9414-11eb-8202-97728753a3d0.png)

## Langkah 6
Tambahkan hyperlink pada dokumen sebelum heading 1 seperti berikut.
~~~
<!-- menambahkan link navigasi -->
<nav>
    <a href="lab1_tag_dasar.html">Dasar HTML</a>
    <a href="lab1_halaman2.html">Halaman 2</a>
    <a href="http://www.google.com">Halaman Web Eksternal Google</a>
    </nav>
    <hr>
~~~
![Screenshot (24)](https://user-images.githubusercontent.com/81818989/113439521-f07e5500-9414-11eb-9f55-ee407cb71de5.png)



## JAWAB PERTANYAAN BERIKUT
1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag? 
~~~
Ada, karena besar kecilnya huruf pun berpegaruh
~~~

2. Apa perbedaan dari tag <'p> dengan tag <'br> , berikan penjelasannya
~~~
Pada hasil praktik yang saya lakukan, perbedaan  tag <p> jarak enter nya tidak terlalu jauh, sedangkan tag <br> jarak enter nya lebih jauh 1 line dari tag <p>.
~~~
    
3. Apa perbedaan atribut title dan alt pada tag , berikan penjelasannya!
~~~
Ketika gambar di tampilkan akan terlihat sebuah title. sedangkan, jika gambar gagal ditampilkan akan menampilkan teks atribut alt.
~~~

4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
~~~
kedua atribut harus di isi semua, karena jika hanya salah satunya maka gambar tersebut akan terlihat terlalu lebar atau tinggi.
~~~

5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?
~~~
Menambah hyperlink baru dan menampilkan yg telah di tentukan, untuk blank akan menambah tab baru terlebih dahulu maka akan menampilkan link yang dituju.
~~~
