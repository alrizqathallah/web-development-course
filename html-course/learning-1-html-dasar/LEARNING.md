# Learning 1: HTML Dasar

<hr>

## 1.1 Pengenalan HTML

### 1.1.1 Apa itu HTML?

HTML adalah singkatan dari _Hyper Text Markup Language_.

HTML merupakan bahasa markup yang digunakan sebagai standar pembuatan halaman web.

HTML menyusun struktur dari halaman web.

HTML _element_ merupakan sebuah kunci yang digunakan untuk membangun sebuah halaman web yang kemudian diterjemahkan oleh browser.

Browser akan membaca dokumen dan menampilkan dokumen sesuai dengan penggunaan element.

### 1.1.2 Struktur Dokumen HTML

Dalam membuat halaman web menggunakan HTML, kita perlu mendefinisikan (membuat) terlebih dahulu sebuah file yang dikenali sebagai file HTML.

File HTML mirip seperti file pada umumnya, namun dengan akhiran (_extension_) `.html`.

_Contoh_:

`index.html`, `Main.html` dan nama lain yang dapat digunakan.

Dengan demikian file tersebut dapat dikenali sebagai file HTML.

**Element**

HTML memiliki struktur dasar dimana struktur ini yang nantinya akan membangun tampilah pada halaman web.

_Element_:

Secara umum, ketika kita membangun sebuah struktur halaman, kita akan menggunakan elemen HTML dalam menyusunnya.

Sebuah elemen pada HTML, lebih umum dikenal dikenal dengan sebutan _tag_.

_Tag_ memiliki perilaku dan konstruksi yang berbeda-beda sesuai dengan kebutuhan bagaimana sebuah data (informasi) itu akan ditampilkan.

Dimana nantinya tag akan dikenali oleh browser, yang kemudian akan menampilkan informasi sesuai dengan perilaku dan konstruksinya.

Tag terbagi menjadi dua jenis, yaitu:

_Contoh_ :

```html
<h1>Heading 1</h1>
// Heading 1
<h2>Heading 2</h2>
// Heading 2
<p>Paragraph</p>
// Paragraph
```

- _Paired Tag_, yaitu tag yang memiliki pasangan

Kemudian,

_Contoh_ :

```html
<img /> // Image <input /> // Input
```

- _Self-Closing Tag / Void Tag_, sebuah tag yang tidak memiliki pasangan.

Masing-masing jenis tag memiliki perilaku dan konstruksinya sendiri.

_Struktur Dasar_ :

```html
<!DOCTYPE html>
<html>
  <head>
    // Head
  </head>
  <body>
    // Body
  </body>
</html>
```

- `<!DOCTYPE html>` :

  - Merupakan adalah tag deklarasi yang merepresentasikan tipe dokumen, dapat membantu browser lebih baik dalam menmapilkan halaman web.

  - Merepersentasikan HTML versi 5 (HTML5).

  - Hanya perlu dideklarasikan sekali diawal baris

- `<html></html>` :

  - Merupakan elemen utama dalam dokumen HTML.

  - Berfungsi sebagai penanda awal dan akhir sebuah dokumen HTML.

  - Didalam elemen terisi dua bagian dokumen yaitu `<head></head>` dan `<body></body>`.

- `<head></head>` :

  - Berisikan informasi tentang halaman web (metadata) yang tidak ditampilka pada halaman.

  - Digunakan untuk mendefinisiakn judul, pengaturan tampilan, link stylesheet dan script dan informasi SEO.

- `<body></body>` :

  - Bersisikan konten utama yang nantinya akan ditampilkan pada halaman web.

  - Umumnya berisikan konten dan tampilan umum pada halaman.
