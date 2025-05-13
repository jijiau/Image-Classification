# Proyek Klasifikasi Gambar
Kriteria tambahan yang saya kerjakan sehingga mendapat nilai terbaik:
1. Mengimplementasikan Callback
2. Gambar-gambar pada dataset asli memiliki resolusi yang tidak seragam (Tanpa preprocessing)
3. Dataset yang digunakan berisi minimal 10000 gambar.
4. Akurasi pada training set dan testing set minimal 95%.
5. Memiliki 3 buah kelas atau lebih.
6. Melakukan inference menggunakan salah satu model (TF-Lite, TFJS atau savedmodel).
7. Pastikan menyertakan bukti inferensi baik itu dalam bentuk screenshot atau output pada notebook

# Penjelasan Proyek
Proyek ini merupakan proyek untuk membuat sebuah model yang dapat melakukan klasifikasi gambar. Diberikan kebebasan untuk memilih dataset yang ingin digunakan.

## Dataset
Dataset merupakan data yang diambil dari [Kaggle](https://www.kaggle.com/datasets/puneet6060/intel-image-classification/data). Data ini berisi sekitar 25 ribu gambar dalam 6 kategori sebagai berikut:

- 'buildings' -> 0
- 'forest' -> 1
- 'glacier' -> 2
- 'mountain' -> 3
- 'sea' -> 4
- 'street' -> 5

Data untuk Train, Test, dan Prediction dipisahkan dalam file zip masing-masing. Terdapat sekitar 14 ribu gambar untuk Train, 3 ribu gambar untuk Test, dan 7 ribu gambar untuk Prediction.
