# Lab1web

## Membuat Paragraf
```
<!-- Ini adalah paragraf pertama -->
  <p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman
  Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama
  yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
  tag-tag dasar HTML.</p>
<!-- Ini adalah paragraf kedua -->
  <p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling
  mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan
  tag dasar html.</p>

```

![Screenshot (185)](https://github.com/Najwaiffa/lab_pemrograman1/assets/115856206/0317ceb1-eb18-445d-bec3-1a185c7e655f)


## Menambahkan Judul
```
<!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>

    <!-- Ini adalah paragraf pertama -->
    <p>Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman Web</b> di Prodi
    <i>Teknik Informatika</i> <u>Universitas Pelita Bangsa</u>. Pelajaran pertama yang kami dapat
    adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar
    HTML.</p>

<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>

    <!-- Ini adalah paragraf kedua -->
    <p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling
    mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan
    tag dasar html.</p>
```

![Screenshot (186)](https://github.com/Najwaiffa/lab_pemrograman1/assets/115856206/24ba367b-23e3-42d4-8c19-05267a4ea4d8)


## Menyisipkan Gambar
```
<!-- sub judul paragraf -->
<h3>Menambahkan Gambar</h3>

<!-- menambahkan gambar pada dokumen -->
<img src="LOGO_UPB_NEW-1.png" width="300" title="Logo Univeritas Pelita Bangsa">
```

![Screenshot (187)](https://github.com/Najwaiffa/lab_pemrograman1/assets/115856206/9b887473-fd13-4a75-a203-c2d8938a9331)

## Menambahkan Hyperlink
```
<!-- menambahkan link navigasi -->
<nav>
    <a href="lab1_tag_dasar.html">Dasar HTML</a>
    <a href="lab1_halaman2.html">Halaman 2</a>
    <a href="http://www.google.com">Halaman Web Eksternal Google</a>
    </nav>
    <hr>
```

![Screenshot (190)](https://github.com/Najwaiffa/lab_pemrograman1/assets/115856206/518ee327-4802-43b1-9b7c-f4303a8e6799)


## Halaman 2

![Screenshot (188)](https://github.com/Najwaiffa/lab_pemrograman1/assets/115856206/5062c74a-3809-4566-914f-5671f6db8448)


# Latihan Soal
```
1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah
   error ketika terjadi kesalahan penulisan tag?
2. Apa perbedaan dari tag <p> dengan tag <br>, berikan penjelasannya!
3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!
4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar
   proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top,
   _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?
```
# Jawaban
2. Tag ```<p>``` pada html diperuntukan untuk membuat paragraf sedangkan tag ```<br>``` pada html diperuntkan untuk membuat line break pada halaman html.
3. Atribute ```<alt>``` pada tag ```<img>``` berfungsi sebagai pemberi deskripsi singkat sedang atribute ```<title>``` memberikan informasi tambahan kepada user tentang       gambar.
4. Tidak, mengisi salah satunya saja sudah cukup

   jika anda ingin mengisi keduanya maka itu akan mengatur gambar secaara presisi dan gambar yang ditampilkan akan persis dan tidak mengubah proporsinya

   jika anda mengisi salah satunya maka akan mempertahankan proporsi gambar aslinya dan hanya mengubah ukuran gambar sesuai atribut yang diisi.
5. _blank
   Efek: Tautan akan membuka halaman yang terkait dalam jendela atau tab browser baru.
   
   _self
   Efek: Tautan akan membuka halaman yang terkait di jendela atau tab yang sama di mana tautan tersebut berada.
   
   _top
   Efek: Tautan akan membuka halaman yang terkait di jendela atau tab baru, menggantikan seluruh halaman web saat ini jika ada beberapa frame atau iframe.
