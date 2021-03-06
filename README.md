# Lab1Web

Dasar - dasar tag HTML (Praktikum 1)

HTML (HyperText Markup Language) adalah suatu bahasa yang menggunakan tanda-tanda tertentu (tag) untuk menyatakan kode-kode yang harus ditafsirkan oleh browser agar halaman tersebut dapat ditampilkan secara benar.

## Membuat Repository

1. login github buat repository baru dengan judul **Lab1web**

![ss-01.png](img/ss-01.png)

2. clone URL github Lab1web

![ss-02.png](img/ss-02.png)
![ss-03.png](img/ss-03.png)

setelah di clone maka akan ada folder dan file README

![ss-04.png](img/ss-04.png)


## Membuat halaman web dasar 

1. buka text editor (saya disinih menggunakan VS Code sebagai editor)
2. kemudian kelik **file** pilih **open folder**, buka folde yang tadi di clone (**Lab1Web**)

![ss-27.png](img/ss-27.png)

3. maka akan tampil sebagai berikut

![ss-05.png](img/ss-05.png)

4. buat file baru dengan nama `lab1_tag_dasar.html`

![ss-06.png](img/ss-06.png)

5. buatlah struktur HTML

        <!DOCTYPE html>
        <html lang="en">
        <head>
          <meta charset="UTF-8">
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Document</title>
        </head>
        <body>
  
        </body>
        </html>

![ss-07.png](img/ss-07.png)

dokumen masih kosong 

![ss-08.png](img/ss-08.png)

6. rubah title menjadi `Tag HTML dasar`

![ss-09.png](img/ss-09.png)
![ss-10.png](img/ss-10.png)

7. membuat 2 paragraf menggunakan tag `<p></p>`

![ss-11.png](img/ss-11.png)

maka akan tampil sebagai berikut

![ss-12.png](img/ss-12.png)

8. kemudian mengatur atribut paragraf dengan menggunkan `atribut align`

![ss-13.png](img/ss-13.png)
![ss-14.png](img/ss-14.png)

    atribut align="right" -> mengatur paragraf di posisi kana
    atribut align="center" -> mengatur paragraf di posisi tengah
    atribut align="left" -> mengatur paragraf di posisi kiri

9. membuat judul halaman menggunakan tag `h1 dan h2`

![ss-15.png](img/ss-15.png)
maka akan tampil sebagaiberikut...
![ss-16.png](img/ss-16.png)

### Tag Heading
    Heading merupakan sebuah judul yang biasanya digunakan pada sebuah halaman artikel pada web.
    Atau terkadang dibeberapa bagian dari halaman web.
    Judul atau heading pada dokumen HTML dapat dibuat dengan menggunakan tag <h1> sampai <h6>.
    Tag <h1> merupakan judul pada lever pertama, kemudian level berikutnya atau sub judul pada tag
    <h2> dan seterusnya sampai tag <h6>.

    <h1>Heading 1</h1>
    <h2>Heading 2</h2>
    <h3>Heading 3</h3>
    <h4>Heading 4</h4>
    <h5>Heading 5</h5>
    <h6>Heading 6</h6>

![heading.png](img/heading.png)

### Contoh pemformatan teks

    <p>Teks <b>ini dicetak tebal</b></p>
    <p>Teks <i>ini dicetak miring</i></p>
    <p>Dan ini adalah <sub>subscript</sub> dan <sup>superscript</sup></p>

![ss-17.png](img/ss-17.png)

10. menambahkan gambar pada dokumen dengan menggunakan tag `img`

![ss-18.png](img/ss-18.png)

    <img src="..." alt="..." title="...">

maka akan tampil sebagai berikut

![ss-19.png](img/ss-19.png)


11. membuat link navigasi menggunakan tag `nav` dan tag `a`

![ss-21.png](img/ss-21.png)

    <nav>
      <a href="lab1_tag_dasar.html">Dasar HTML</a>
      <a href="lab1_halaman2.html">Halaman 2</a>
      <a href="https://www.google.co.id/">Halaman Web Eksternal Google</a>
    </nav>

tag `hr` berfungsi menambahkan garis 

![ss-22.png](img/ss-22.png)

## push kehalaman repository

1. pertama buka `git bas` 
2. masuk ke folder `Lab1Web`

    cd Lab1Web

![ss-23.png](img/ss-23.png)

    git status -> untuk memeriksa apakah ada perubahan di repository
    git add "nama file/folder" atau git add . -> untuk memasukan perubahan ke repository
    git commit -m "pesan" -> untuk memberikan pesan atau deskripsi apa saja yang berubah
    git push -> untuk mengirim file dari git bas ke github

![ss-24.png](img/ss-24.png)
![ss-25.png](img/ss-25.png)

maka akan ada file html di github 

![ss-26.png](img/ss-26.png)