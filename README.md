# Klasifikasi Aksara Jawa Menggunakan CNN (Convolutional Neural Network)
### Michael Effendy (OrionSeeker)

#### Summary
Proyek ini adalah proyek klasifikasi Aksara Jawa (Hanacaraka) menggunakan model CNN. Akurasi yang dimiliki oleh model ini adalah 84,59%. Dataset diambil dari kaggle (link terlampir di bawah) dan dipreprocessing menggunakan beberapa teknik preprocessing citra.

![image](https://github.com/OrionSeeker/Klasifikasi-Aksara-Jawa-CNN/assets/143796680/aafd61fc-8f43-4e1a-9afc-042fd9beff68)

#### Dataset
Dataset ini diambil dari Kaggle, yaitu https://www.kaggle.com/datasets/vzrenggamani/hanacaraka

#### Preprocessing
Terdapat beberapa preprocessing citra yang dilakukan pada dataset, yaitu resize, convert to gray, deteksi tepi menggunakan kernel Sobel, threshold dan invert, closing (dilasi + erosi), dan convert dari gray to RGB.

#### Informasi Teknis
Proyek ini dijalankan menggunakan Python 3.10.0, Tensorflow 2.10.1, CUDA Toolkit 11.2, dan cuDNN 8.1.0.
