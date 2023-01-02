## IMAGE ENHANCEMENT

Image enhancement adalah proses mendapatkan citra yang lebih mudah diinterpretasikan oleh mata manusia (Human Visual System/HVS). Proses ini merupakan salah satu proses awal dalam pengolahan citra (image preprocessing). Untuk meningkatkan kualitas hasil proses image enhancement maka lebih baik manipulasi citra dilakukan dalam domain frekuensi. Beberapa jenis transformasi yang dapat digunakan untuk mengubah citra dari domain spasial ke domain frekuensi antara lain, transformasi fourier, transformasi gelombang-singkat (wavelet transform), Discrete Cosine Transform (DCT), dan sebagainya. Citra yang terbentuk menjadi berkualitas buruk karena mengalami derau (noise) pada saat pengambilan (capture) gambar, pengiriman melalui saluran transmisi, terlalu terang/gelap, kurang tajam, kabur dan sebagainya. singkatnya Image enhancement adalah proses agar citra menjadi lebih baik ‘secara visual’ untuk aplikasi tertentu.

Proses pemilihan H(u,v) yang tepat dalam rangka menonjolkan ciri citra f(x,y). Pada umumnya nilai f(x,y) sudah diketahui yang merupakan citra asli, persoalannya adalah memilih filter h(x,y) yang tepat untuk dapat menonjolkan ciri tertentu dari citra asli. Dalam domain frekuensi, umumnya citra yang mengalami gangguan yaitu pada frekuensi tinggi sehingga dilakukan proses penyaringan yang dapat menapis frekuensi tinggi High Pass Filter (HPF) dan meloloskan frekuensi rendah yaitu Low Pass Filter (LPF)

Berdasarkan ranah (domain) operasinya, metode-metode untuk perbaikan kualitas citra dikelompokkan menjadi dua kategori:

1. Image enhancement dalam ranah spasial
2. Image enhancement dalam ranah frekuensi


### Spatial Domain
Dalam metode domain frekuensi didasarkan pada Transformasi Fourier dari suatu gambar. Secara kasar, istilah frekuensi dalam sebuah gambar menceritakan tentang laju perubahan nilai piksel.

Suatu citra dapat direpresentasikan dalam bentuk matriks 2D dimana setiap elemen matriks merepresentasikan intensitas piksel. Keadaan matriks 2D yang menggambarkan distribusi intensitas suatu gambar disebut Domain Spasial.

### Domain Frekuensi
Dalam metode domain frekuensi didasarkan pada Transformasi Fourier dari suatu gambar. Secara kasar, istilah frekuensi dalam sebuah gambar menceritakan tentang laju perubahan nilai piksel.
Metode-metode image enhancement dalam ranah frekuensi dilakukan dengan mengubah citra terlebih dahulu dari ranah spasial ke ranah frekuensi, baru kemudian memanipulasi nilai-nilai frekuensi tersebut.

Metode diantaranya ialah:

1. Transformasi fourier
   
Tranformasi fourier adalah suatu model transformasi yang memindahkan domain spasial atau domain waktu menjadi domain frekuensi. Dengan menggunakan transformasi fourier, sinyal atau citra dapat dilihat sebagai suatu objek dalam domain frekuensi. Analisis dalam domain frekuensi banyak digunakan seperti filtering.

### Perbedaan antara domain spasial dan domain frekuensi
Dalam domain spasial, berurusan dengan gambar apa adanya. Nilai piksel gambar berubah sehubungan dengan pemandangan.
Sedangkan dalam domain frekuensi, berurusan dengan laju perubahan nilai piksel dalam domain spasial.

Domain Spasial: Input -> Pemrosesan Gambar -> Output

Domain Frekuensi: Frekuensi + Distribusi -> Pemrosesan Gambar -> Transformasi Invers -> Keluaran