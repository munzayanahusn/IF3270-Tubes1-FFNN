# Implementasi Forward Propagation Feed Forward Neural Network
Tugas Besar A <br>
IF3270 Pembelajaran Mesin <br>
Implementasi Forward Propagation Feed Forward Neural Network

## Daftar Isi

- [Penjelasan Ringkas Program](#penjelasan-ringkas-program)
- [Cara Menjalankan Program](#cara-menjalankan-program)
- [Kontributor](#kontributor)

## Penjelasan Ringkas Program

Repositori ini berisi implementasi Forward Propagation Feed Forward Neural Network menggunakan Python. Program ini menggunakan library 'numpy' untuk operasi matriks dan 'json' untuk membaca input dalam format JSON. Program mendefinisikan fungsi aktivasi seperti linear, ReLU, sigmoid, dan softmax untuk menghitung output dari setiap neuron dalam jaringan. Selanjutnya, terdapat fungsi 'forward_propagation' yang mengambil model neural network, data input, dan bobot sebagai input, mengembalikan output dari jaringan setelah proses forward propagation. Data input dibaca dari file JSON dan diekstraksi untuk mendapatkan informasi mengenai model, data input, bobot, dan output yang diharapkan. Setelah mendapatkan output, error dihitung dan dibandingkan dengan batas maksimum error yang ditentukan untuk mengevaluasi keakuratan output. Dengan demikian, program dapat melakukan forward propagation pada model neural network dan mengevaluasi hasilnya dengan efisien.

## Cara Menjalankan Program

1. Clone repository ini:
   ```git clone https://github.com/munzayanahusn/IF3270-Tubes1-FFNN.git```
2. Buka file `ffnn.ipnyb` menggunakan Notebook atau VSCode.
3. Sesuaikan file input yang ingin dimuat dengan mengetikkan nama file dan direktori yang sesuai:
   ```with open("test/multilayer.json")```
4. Jalankan program dengan mengeklik tombol Run.

## Kontributor

13521050 Naufal Syifa Firdaus<br>
13521077 Husnia Munzayana<br>
13521088 Puti Nabilla Aidira<br>
13521130 Althaaf Khasyi Atisomya
