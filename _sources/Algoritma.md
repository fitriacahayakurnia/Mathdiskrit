---
title: Algoritma

---

# Algoritma
## Definisi Algoritma
Algoritma adalah suatu langkah atau metode yang telah direncanakan secara matang sehingga terurut dan terorganisir dengan baik dan biasanya digunakan untuk memecahkan suatu masalah dengan memberikan suatu instruksi setingga menjadi suatu tindakan. Dari pengertisn tersebut dapat dikatakan bahwa algoritma digunakan untuk menyelesaikan suatu masalah dengan langkah-langkah logis yang terurut.

### Algoritm Sequential Search
Sequential Search adalah teknik pencarian data yang dilakukan dengan cara membandingkan setiap elemen data satu per satu, mulai dari elemen pertama hingga elemen yang dicari telah ditemukan. Proses ini terus berlanjut hingga data ditemukan atau seluruh elemen telah diperiksa.
Cara Kerja Sequential Search
Algoritma Sequential Search bekerja dengan melakukan perbandingan satu persatu secara beruntun dalam kumpulan data dengan data yang dicari sampai data tersebut ditemukan atau tidak ditemukan.

Proses pencarian ini hanya melakukan pengulangan data dari 1 sampai dengan jumlah data (N). Setiap pengulangan, dilakukan perbandingan data ke-i dengan data yang sedang dicari. Jika data sama dengan yang dicari, berarti data telah berhasil ditemukan. Sebaliknya, jika sampai akhir pengulangan tidak ada data yang sama dengan yang dicari, berarti data tidak ditemukan.

### Algoritm Binary Search
Binary Search adalah sebuah algoritma pencarian yang digunakan untuk mencari elemen tertentu dari sebuah array atau daftar yang sudah diurutkan. Algoritma ini bekerja dengan membagi daftar menjadi dua bagian, kemudian memeriksa elemen tengahnya. Jika elemen yang dicari sama dengan elemen tengah ini, maka pencarian selesai. Jika tidak, algoritma akan terus menentukan apakah elemen yang dicari lebih besar atau lebih kecil dari elemen tengah, kemudian hanya memeriksa salah satu bagian dari daftar yang masih mungkin mengandung elemen yang dicari. Proses ini terus berlanjut hingga elemen yang dicari ditemukan atau daftar habis diperiksa.Cara Kerja Binary Search
Cara kerja binary search sangat sederhana. Algoritma ini beroperasi pada daftar yang sudah diurutkan. Berikut adalah langkah-langkah utama dalam binary search:

Tentukan Rentang Pencarian Awal: Di awal pencarian, kita memiliki seluruh daftar sebagai rentang pencarian. Rentang ini didefinisikan dengan dua indeks, yaitu awal dan akhir, yang mengacu pada elemen pertama dan terakhir dalam daftar.
Hitung Elemen Tengah: Temukan indeks tengah di dalam rentang pencarian dengan rumus tengah = (awal + akhir) / 2.
Periksa Elemen Tengah: Bandingkan elemen tengah dengan elemen yang ingin Anda cari. Jika elemen tengah sama dengan elemen yang dicari, maka pencarian selesai, dan Anda telah menemukan elemennya.
Perkecil Rentang Pencarian: Jika elemen tengah lebih besar dari elemen yang dicari, maka Anda dapat memastikan bahwa elemen yang dicari hanya mungkin ada di sebelah kiri elemen tengah. Oleh karena itu, perkecil rentang pencarian menjadi antara awal dan tengah - 1. Jika elemen tengah lebih kecil, perkecil rentang menjadi antara tengah + 1 dan akhir.
Ulangi Langkah 2–4: Ulangi proses ini sampai Anda menemukan elemen yang dicari atau rentang pencarian menjadi kosong.

### Pseudocode
Pseudocode adalah cara penulisan kode dan algoritma menggunakan bahasa umum yang digunakan sehari-hari sehingga lebih mudah dipahami, terutama bagi orang tanpa latar belakang programming.

### Big O algoritma
Notasi Big-O adalah cara untuk mengekspresikan kompleksitas waktu atau ruang suatu algoritma. Notasi ini memberikan perkiraan kasar tentang berapa lama waktu yang dibutuhkan suatu algoritma dengan kompleksitas waktu O (n) berarti waktu berjalan meningkat secara linear seiring dengan ukuran input.

### Hitung Big-O dari algoritma Sequential Search
* Waktu kompleksitas (time complexity)
1. Kompleksitas Waktu Linier: Kompleksitas O(n) Besar
Kompleksitas waktu linear berarti waktu berjalan suatu algoritma tumbuh secara linear seiring dengan ukuran input. 
2. Kompleksitas Waktu Logaritmik: Kompleksitas Big O(log n)
Kompleksitas waktu logaritmik berarti waktu berjalan suatu algoritma sebanding dengan logaritma ukuran input.
3. Kompleksitas Waktu Kuadrat: Kompleksitas O(n 2 ) Besar
Kompleksitas waktu kuadratik berarti bahwa waktu berjalan suatu algoritma sebanding dengan kuadrat ukuran input.
4. Kompleksitas Waktu Kubik: Kompleksitas O(n3 ) Besar
Kompleksitas waktu kubik berarti waktu berjalan suatu algoritma sebanding dengan pangkat tiga ukuran input.
5. Kompleksitas Waktu Polinomial: Kompleksitas Big O(n k )
Kompleksitas waktu polinomial mengacu pada kompleksitas waktu suatu algoritma yang dapat dinyatakan sebagai fungsi polinomial dari ukuran input n . Dalam notasi Big O , suatu algoritma dikatakan memiliki kompleksitas waktu polinomial jika kompleksitas waktunya adalah O(n k ) , di mana k adalah konstanta dan mewakili derajat polinomial.
Algoritma dengan kompleksitas waktu polinomial umumnya dianggap efisien, karena waktu berjalan bertambah pada tingkat yang wajar seiring bertambahnya ukuran input. Contoh umum algoritma dengan kompleksitas waktu polinomial meliputi kompleksitas waktu linier O(n) , kompleksitas waktu kuadrat O(n 2 ) , dan kompleksitas waktu kubik O(n 3 ).
6. Kompleksitas Waktu Eksponensial: Kompleksitas O(2 n ) Besar
Kompleksitas waktu eksponensial berarti waktu berjalan suatu algoritma berlipat ganda dengan setiap penambahan pada set data masukan.

* Ruang kompleksitas (space complexity)
Untuk algoritma ini, kita hanya membutuhkan ruang untuk menyimpan beberapa variabel seperti:
1. List atau array yang akan diperiksa.
2. Beberapa variabel tambahan seperti indeks, variabel penunjuk, atau nilai yang sedang dicari.

Karena algoritma sequential search tidak membutuhkan ruang tambahan yang bergantung pada ukuran input (array/list), ruang tambahan yang digunakan adalah konstan. Jadi, space complexity dari algoritma Sequential Search adalah O(1).

referensi:
https://www.gramedia.com/literasi/pengertian-algoritma/
https://fikti.umsu.ac.id/algoritma-sequential-search-pengertian-fungsi-dan-cara-kerjanya/
https://engineerpalsu.medium.com/mengenal-algoritma-binary-search-40a9047dab62
https://revou.co/kosakata/pseudocode
https://www.designgurus.io/blog/big-o-algorithm-complexity