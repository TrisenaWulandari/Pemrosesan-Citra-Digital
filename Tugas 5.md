## Tugas 5 : (Stegonography)

### Bit Plane Slicing dan Steganografi
Bit-Plane Slicing merupakan metode yang digunakan untuk melihat kontribusi atau pengaruh dati tiap bit penyusun citra. Untuk citra 8 bit, pada dasarnya tiap intensitas yang nilainya dalam format desimal, bisa dipecah menjadi bit-bit dalam format biner.

Misalnya, sebuah piksel dengan intesnsitas 245(desimal) bila dijadikan biner adalah 11110101. Dengan nilai LSB (Least Significant Bit) berada paling bawah kanan, dan sebaliknya untuk MSB (Most Sigificant Bit). Perhatikan gambar dibawah yang merupakan ilustrasi dari bit-plane sicing pada piksel citra.

### Steganografi
Steganografi adalah sebuah metode dalam pemrosesan citra digital untuk menyembunyikan suatu data rahasia ke dalam sebuah citra.
1. Gambar
2. Teks
3. Suara

Dll

Langkah- Langkah Steganografi Adapun langkah-langkah yang dilakukan dalam menerapkan metode steganografi adalah:

1. Ubah citra warna ke dalam citra grayscale.
2. Ubah pesan yang akan disisipkan ke dalam bentuk biner.
3. Cek untuk setiap piksel yang ada pada citra, dan lakukan
4. Ambil nilai LSB pada citra.
5. Ambil nilai bit pesan yang akan disisipkan.
6. Jika nilai sama, tambahkan 0 ke dalam citra output, jika tidak tambahkan 1.
7. Simpan gambar.

### JENIS JENIS TEKNIK STEGANOGRAFI
1. Injection,,merupakan suatu teknik menanamkan pesan rahasia secara langsung ke suatu media. Salah satu masalah dari teknik ini adalah ukuran media yang diinjeksi menjadi lebih besar dari ukuran normalnya sehingga mudah dideteksi. Teknik ini sering juga disebut embedding.

2. Substitusi,, data normal digantikan dengan data rahasia. Biasanya hasil teknik ini tidak terlalu mengubah ukuran data asli, tetapi tergantung pada file media dan data yang akan disembunyikan. Teknik substitusi bisa menurunkan kualitas median yang ditumpangi.

3. Tramsformasi Domain, teknik ini sangat efektif. Pada dasarnya, transformasi domain menyembunyikan data pada transformspace.

4. SpreadSpectrum,merupakan teknik pentransmisi menggunakan pseudo-noise code, yang independen terhadap data informasi sebagai modulator bentuk gelombang untuk menyebarkan energi sinyal dalam sebuah jalur komunikasi “bandwith” yang lebih besar dari pada sinyal jalur komunikasi informasi. Oleh penerima, sinyal dikumpulkan kembali menggunakan replika pseudo-noise code tersinkronisasi.

5. Statistical Method, teknik ini disebut juga skema steganographic 1 bit, skema tersebut menanamkan satu bit informasi pada media tumpangan dan mengubah statistik walaupun hanya 1 bity. Perubahan statistik ditunjukkan dengan indikasi 1 dan jika tidak ada perubahan, terlihat indikasi 0. Sistem ini bekerja berdasarkan kemampuan penerima dalam membedakan antara informasi yang dimodifikasi dan yang belum.