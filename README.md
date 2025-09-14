# Tugas Web Portfolio WBD - IF3110
Daniel Pedrosa Wu - 13523099

## Kriteria dan Tantangan
1. Gunakan Struktur HTML yang Semantic​
2. Kreativitas dalam Penggunaan Warna dan Tipografi​
3. Desain yang Interaktif (without JavaScript, only HTML+CSS)

## Penjelasan
### 1. Struktur HTML yang Semantic
Elemen semantic bertujuan untuk menyampaikan tujuan dari suatu bagian secara jelas. Pada pembuatan portfolio ini, terdapat 3 elemen semantic utama yang saya gunakan yaitu `<nav>`, `<main>`, dan `<section>`. 
* `<nav>` digunakan untuk navigasi tab. Laman portfolio ini dibagi menjadi beberapa bagian yaitu bagian *About Me*, *Skills*, *Projects*, *Education*, dan *Contacts*. Agar dapat menavigasi bagian-bagian ini, saya menggunakan `<nav>` untuk menandakan bahwa navigasi tab menggunakan sebuah navbar, yang memberikan makna semantik bahwa bagian ini adalah navigasi utama halaman.
* `<main>` digunakan untuk konten utama. Seluruh konten utama dari setiap tab ditempatkan di dalam elemen `<main>`, yang menandakan bahwa ini adalah konten inti dari halaman tersebut. Ini memberitahu browser bahwa inilah konten inti dari halaman, memisahkannya dari elemen sekunder seperti navigasi.
* `<section>` digunakan untuk setiap halaman tab. Setiap halaman konten dibungkus dalam tag `<section>`. Ini membantu memisahkan konten secara logis, sesuai dengan fungsinya masing-masing.

### 2. Penggunaan Warna dan Tipografi
Tema dari portfolio ini terinspirasi dari tema retro sehingga mencoba membangkitkan gaya-gaya terminal kuno atau yang sering dilihat di media-media. Untuk tujuan tersebut, skema warna yang digunakan terdiri dari dua warna utama yaitu warna hijau (#00ff00) dan warna hitam (#000000), beserta variasinya. Kombinasi warna ini bertujuan untuk memberi nuansa estetik retro. Pengunjung laman seolah-olah sedang berinteraksi dengan sistem komputer kuno. 

Tipografi yang digunakan menggunakan font dari font family *monospace*. Tipe font ini memiliki lebar tiap karakter yang sama dan sering digunakan pada terminal atau code editor. Seperti yang disebutkan sebelumnya, tujuan penggunaan font ini adalah memperkuat nuansa retronya.

### 3. Desain yang Interaktif
Karena tujuannya memang mensimulasikan suatu terminal kuno, desain interaktif juga saya buat mirip dengan terminal. Navigasi dari bagian dibuat seolah-olah mengganti tab dari terminal. Tiap konten dalam portfolio ini memiliki tabnya tersendiri. Sistem tab ini memanfaatkan elemen input tipe radio yang disembunyikan. Tiap tombol radio direpresentasikan oleh label yang saat diklik akan mengubah tab yang sekarang digunakan. Secara default, display dari tiap konten akan berupa none. Saat suatu radio button aktif, maka tab yang bersangkutan akan mengubah displaynya menjadi block sehingga konten tersebut muncul.

Beberapa bagian seperti tiap tab, kartu, ataupun ikon akan terhighlight saat dihover dengan menggunakan mouse. Ini menggunakan fungsionalitas hover pada tiap kelas yang bersangkutan di CSS. Saat suatu ikon dihighlight, maka akan muncul suatu tooltip yang akan menunjukkan apa arti dari ikon tersebut. Sebagai tambahan, saya menambahkan beberapa animasi kecil seperti transisi antara diri saya yang sebenarnya dengan versi ASCII. Ini menggunakan keyframes dalam CSS dimana salah satu akan fade in sementara yang lain fade out. Saya juga menambahkan kursor yang juga mengubah opacitynya terus menerus untuk memberi ilusi bahwa dia sedang berkedip-kedip