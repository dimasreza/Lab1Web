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
![SS  LANGKAH 1](https://user-images.githubusercontent.com/56240719/112924842-094be980-913b-11eb-9734-76392fc6987f.png)

## Langkah 2
### Membuat 2 buah paragraf dan mengatur atribut paragraf 
Selanjutnya, buatlah beberapa paragraf sederhana sebagai berikut
```
<!-- Ini adalah paragraf pertama -->
<p align="center">Kami sedang belajar \HTML dasar, pada matakuliah Pemrograman
    Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>

<!-- Ini adalah paragraf kedua -->
<p align="right">Ini merupakan sebuah paragraf yang terdiri dari beberapa
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat
    dengan menggunakan tag dasar html.</p>
```
![SS LANGKAH 2](https://user-images.githubusercontent.com/56240719/112925101-7eb7ba00-913b-11eb-8cff-930d527f3268.png)

## Langkah 3
### Menambahkan judul menggunakan Tag Heading (h1, h2, h3, h4, h5, h6). Semakin besar angka Tag Heading, Semakin kecil ukuran Headingnya.
```
<!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>

<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>
```
![SS LANGKAH 3](https://user-images.githubusercontent.com/56240719/112925996-fd612700-913c-11eb-89f4-312323b0bea5.png)

## Langkah 4
### Memformat Teks menggunakan format-format teks yang tersedia seperti ``` <b>, <strong>, <i>, <em>, <mark>, <small>, <dell>, <ins>, <sub>, <sup>```.
```
<p align="left">Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman
    Web</b> di Prodi <i>Teknik Informatika</i> <ins>Universitas Pelita Bangsa</ins>. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>
```
![SS LANGKAH 4](https://user-images.githubusercontent.com/56240719/112937850-9ea6a800-9152-11eb-9151-f1a76cdeb6dd.png)

## Langkah 5
### Menampilkan gambar dengan cara mengambil gambar lalu sisipkan gambar dengan file HTML yang sudah di buat
![SS LANGKAH 5](https://user-images.githubusercontent.com/56240719/112922096-14e8e180-9136-11eb-8203-07bbb1a19c1d.png)
```
<!-- sub judul paragraf -->
<h3>Menambahkan Gambar</h3>
<!-- menambahkan gambar pada dokumen -->
<img src="logo upb.png" width="200" title="Logo Univeritas Pelita Bangsa">
</body>
</html>
```
![SS LANGKAH 5 Tampilan Gambar](https://user-images.githubusercontent.com/56240719/112926583-d6efbb80-913d-11eb-9ba4-2b4c7a2a5846.png)

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
![SS  LANGKAH 6](https://user-images.githubusercontent.com/56240719/112927130-b1af7d00-913e-11eb-83fd-61dfe8368a10.png)

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
![SS  LANGKAH 7](https://user-images.githubusercontent.com/56240719/112924567-917dbf00-913a-11eb-8e23-ad66464955f2.png)

## Jawablah pertanyaan berikut 
1. Lakukan perubahan pada code sesuai dengan keinginan anda, amati perubahannya adakah _error_ ketika terjadi kesalahan penulisan tag?
```
Ketika saya mencoba melakukan perubahan pada tag paragraf menggunakan huruf kapital <P tidak terjadi error ataupun perubahan pada code maupun hasil di browser.
Begitupun ketika saya mencoba mennghilangkan penutup atau garis miring (/) di penghujung paragraf pun tidak terjadi error ataupun perubahan pada code maupun hasil di browser.
```
2. Apa perbedaan dari tag `<p>` dengan tag `<br>` berikan penjelasannya!
```
Dari hasil pengamatan saya, tag <p> digunakan untuk mengganti paragraf, karena jarak garis baru (enternya) lebih jauh dibanding dengan tag <br> yang digunakan untuk pindah ke garis baru
```
3. Apa perbedaan atribut `title` dan `alt` pada tag `<img>`, berikan penjelasannya!
```
Atribut title pada tag <img> digunakan untuk memberikan informasi pada gambar yang di tampilkan.
Sedangkan atribut alt pada tag <img> digunakan untuk memberikan altenatif keterangan pada gambar jika gambar tersebut gagal untuk ditampilkan.
```
4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
```
Menurut saya, bisa disesuaikan. Misalkan untuk mengatur gambar agar tampil proporsional gunakan width dan height sesuai ukuran aslinya, jika ingin mengecilkan ukuran gambar gunakan ukuran yang proposional misal, kita akan ubah width 50px dan height 50px.
```
5. Pada link tambahkan atribut target dengan nilai atribut bervariasi (_blank, _self, _top, _parent), apa yang terjadi pada masing-masing nilai atribut tersebut?
```
Nilai _blank    : Menampilkan halaman website yang di link ke dalam tab yang baru.
Nilai _self     : Menampilkan halaman website yang di link ke dalam tab atau frame yang sama yang digunakan saat ini.
Nilai _top      : Menampilkan halaman website yang di link ke dalam tab yang baru yang ditampilkan dalam fullscreen dan membatalkan semua frame.
Nilai _parent   : Menampilkan halaman website yang di link ke dalam parent frame
