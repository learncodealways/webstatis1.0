# webstatis1.0 
Penjelasan CSS DASAR (layouting) yang telah digunakan pada pembuatan webstatis1.0 ini.

1. Box Model 
 Box Model (Model Kotak):
Box model adalah cara CSS merancang dan mengatur elemen HTML. Setiap elemen HTML dianggap sebagai kotak, dan kotak ini memiliki beberapa bagian penting:

2. Margin.
 Margin (Mengisi):
Margin adalah ruang di luar border yang memisahkan kotak ini dari elemen-elemen lain di sekitarnya. Anda dapat mengatur margin dengan properti seperti margin-top, margin-right, margin-bottom, dan margin-left. Margin digunakan untuk memberikan jarak antara elemen ini dan elemen-elemen lainnya di sekitarnya.
noted : Margin bisa menggunakan negatif.

3. Padding.
 Padding adalah ruang di sekitar konten di dalam kotak. Anda dapat mengatur padding dengan properti seperti padding-top, padding-right, padding-bottom, dan padding-left. Padding digunakan untuk memberikan jarak antara konten dan border.
noted : Padding tidak bisa menggunakan properti auto dan tidak menggunakan negatif.

4. Content (Konten): Ini adalah area di dalam kotak yang berisi teks, gambar, atau konten lainnya.
Padding (Padding): Ini adalah ruang di sekitar konten, di antara konten dan border.
Border (Batas): Ini adalah garis yang mengelilingi kotak dan berada di sekitar padding.
Margin (Mengisi): Ini adalah ruang di luar border, yang memisahkan kotak ini dari elemen-elemen lain di sekitarnya.

5. Border (Batas):
Border adalah garis yang mengelilingi kotak dan terletak di sekitar padding. Anda dapat mengatur jenis, ketebalan, dan warna border dengan properti seperti border-style, border-width, dan border-color.

6. Float.
  Float (Mengapung):
Float adalah properti CSS yang digunakan untuk mengatur bagaimana elemen akan mengapung di sekitar elemen lainnya. Ini sering digunakan untuk mengatur tata letak elemen di sepanjang sisi elemen lain, seperti mengatur gambar di sebelah teks. Properti ini memiliki nilai seperti left, right, atau none.

7. Position
 
 Properti position di css ini memiliki 4 nilai yang bisa digunakan untuk mengatur posisi elemen tersebut, yaitu: static, relative, absolute, fixed, dimana beberapa nilai-nilai tersebut dapat diatur dengan menggunakan properti top, left, right, bottom dengan menggunakan nilai positif atau negatif.

 -Position Static
Posisi static adalah posisi yang secara bawaan telah digunakan ketika kita tidak pernah menentukan metode posisi yang digunakan, sebuah posisi static ini tidak akan berkerja apabila menggunakan properti top, bottom, left, right.

-Position Relative
Posisi relative ini hampir sama dengan posisi static, yaitu posisi normal. Namun perbedaannya posisi relative ini dapat menggunakan 4 properti top, bottom, left, right untuk dapat mengatur tata letak lokasi elemen.

-Position Absolute
Posisi absolute ini akan bergantung pada parent-elemen atau elemen induk dari elemen posisi absolute tersebut, lebih mudahnya elemen absolute ini bergantung pada sarang elemen tersebut. Namun jika elemen absolute tidak berada didalam sebuah elemen maka position absolute akan menyesuaikan dengan elemen utama yaitu body, contohnya.

8. Z-Index
  Z-index dalam CSS adalah cara untuk mengontrol tumpukan atau lapisan elemen HTML yang tumpang tindih satu sama lain di dalam halaman web Anda. Ini membantu Anda menentukan elemen mana yang harus tampil di depan elemen lainnya.

Semakin besar nilai z-index, semakin tinggi elemen itu akan berada dalam tumpukan. Jadi, jika elemen A memiliki z-index 2 dan elemen B memiliki z-index 1, maka elemen A akan tampil di depan elemen B.

Contoh penggunaannya adalah saat Anda memiliki elemen-elemen seperti gambar, teks, atau tombol yang tumpang tindih di atas latar belakang. Dengan mengatur nilai z-index dengan bijak, Anda dapat mengontrol urutan tampilan elemen-elemen tersebut agar sesuai dengan yang Anda inginkan.


Dengan memahami konsep-konsep dasar ini, Anda dapat mengontrol tata letak dan penampilan elemen-elemen di halaman web Anda dengan lebih baik menggunakan CSS.