## Tugas 4 : membuat Pseudo Code Patterning, Ditthering, Bit Plane Slacing, dan Histogram equalization Patterning

Menentukan banyak pola patterning yang akan digunakan, jika matriks yang digunakan adalah 3x3 maka jumlah pola pattern yang dihasilkan adalah sebanyak 10. Jika matriks yang digunakan adalah 4x4 maka jumlah pola yang dihasilkan sebanyak 17. Rumusnya = ukuran matriks ditambah 1. Menghitung persebaran range nilai dengan mengoperasikan 255 dibagi banyaknya jumlah pola pattern.

Jika matriks yang digunakan berukuran 3x3 dan font biner yang digunakan berukuran 2x2 maka hasil akhir matriks yang dihasilkan adalah 6x6. Untuk setiap matriks 3x3 yang berada pada matriks 6x6 mewakili salah satu pola pattern yang ada.

### Dithering
Menghitung matriks treshold yang akan digunakan untuk membandingkan matriks. Setelah mendapatkan nilai matriks tresholdnya, bandingkan nilai yang ada pada matriks dengan nilai treshold.

Jika nilai matriks lebih besar dari treshold maka matriks akan bernilai 0 atau warna yang ditampiilkan adalah hitam. Jika nilai matriks lebih kecil dari treshold maka matriks akan bernilai 1 atau berwarna putih.

### Histogram Equalization
Menghitung seluruh nilai histogram. Menormalisasikan jumlah histogram dengan membaginya pada seluruh nilai histogram(jumlah pixel). Mengalikan hasil normalisasi histogram dengan banyaknya level bit gambar kemudian dibagi dengan jumlah dari keseluruhan pixel.

Menentukan jumlah masing-masing gray level dengan menjumlahkan number of pixel dengan gray level yang sama.

### Bit Plane Slicing
Mengubah setiap angka yang ada pada matriks menjadi bilangan biner.

Menyimpan nilai biner yang didapatkan dari matriks. Tiap 1 buah angka yang ada pada matriks disimpan lagi ke dalam matriks baru sehingga terdapat 8 buah matriks baru dari bilangan biner yang sudah dihasilkan.

Bilangan biner yang berada di sisi paling kanan adalah less significant bit (LSB).

Bilangan biner yang berada di sisi paling kanan adalah most significant bit (MSB).