# Praktikum1 (Pemrograman Web)
```
Dimas Reza Nugraha
311910431
TI.19.A.2
Universitas Pelita Bangsa
```

## Langkah 1
### Buka Visual Studio Code dan buatlah file HTML baru. Setelah itu buatlah struktur dasar HTML
```
<!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar</title>
</head>
<body>

</body>
</html>
```
![SS  LANGKAH 1](https://user-images.githubusercontent.com/56240719/112867298-f27aa800-90e4-11eb-9368-fd53a5cc9dfa.png)

## Langkah 2
### Membuat 2 buah paragraf dan mengatur atribut paragraf 
Selanjutnya, buatlah beberapa paragraf sederhana sebagai berikut
```
<!-- Ini adalah paragraf pertama -->
<p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi 
    Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat 
    adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar 
    HTML.</p>
    
<!-- Ini adalah paragraf kedua -->
<p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling
    mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan 
    tag dasar html.</p>
```
![SS LANGKAH 2](https://user-images.githubusercontent.com/56240719/112870545-87cb6b80-90e8-11eb-945e-a4522f4ded42.png)

## Langkah 3
### Menambahkan judul menggunakan Tag Heading (h1, h2, h3, h4, h5, h6). Semakin besar angka Tag Heading, Semakin kecil ukuran Headingnya.
```
<!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>

<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>
```
## Langkah 4
### Memformat Teks menggunakan format-format teks yang tersedia seperti ``` <b>, <strong>, <i>, <em>, <mark>, <small>, <dell>, <ins>, <sub>, <sup>```.
```
<p align="left">Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman
    Web</b> di Prodi <i>Teknik Informatika</i> <ins>Universitas Pelita Bangsa</ins>. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>
```
## Langkah 5
### Menampilkan gambar dengan cara mengambil gambar lalu sisipkan gambar dengan file HTML yang sudah di buat
```
<!-- sub judul paragraf -->
<h3>Menambahkan Gambar</h3>
<!-- menambahkan gambar pada dokumen -->
<img src="logo upb.png" width="200" title="Logo Univeritas Pelita Bangsa">
</body>
</html>
```
## Langkah 6
### Menambahkan Hyperlink. Tambahkan hyperlink pada dokumen sebelum heading 1.
```
 <!-- menambahkan link navigasi -->
<nav>
    <a href="lab1_tag_dasar.html">Dasar HTML</a>
    <a href="lab1_halaman2.html">Halaman 2</a>
    <a href="http://www.google.com">Halaman Web Eksternal Google</a>
    </nav>
    <hr>
```
## Langkah 7
### Membuat halaman ke 2 yang akan terhubung dengan halaman 1 dengan cara menggunakan hyperlink
```
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
```
