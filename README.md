# Cat-and-Dog-Clasification
# Cat-Dog Classification

![Cat-Dog Classification](images/classification.png)

Proyek ini bertujuan untuk mengklasifikasikan gambar kucing dan anjing menggunakan model CNN. 

## Daftar Isi
- [Pendahuluan](#pendahuluan)
- [Fitur](#fitur)
- [Dataset](#dataset)
- [Arsitektur Model](#arsitektur-model)
- [Persyaratan](#persyaratan)
- [Struktur Proyek](#struktur-proyek)
- [Cara Instalasi](#cara-instalasi)
- [Cara Penggunaan](#cara-penggunaan)
- [Hasil](#hasil)


## Pendahuluan
Proyek ini menggunakan dataset gambar kucing dan anjing untuk melatih model klasifikasi gambar. Model ini dibangun dengan menggunakan TensorFlow dan Keras dan bertujuan untuk membedakan antara gambar kucing dan anjing dengan akurasi yang tinggi.

## Fitur
- **Persiapan Data**: Pemrosesan dan augmentasi data gambar.
- **Pelatihan Model**: Menggunakan CNN (Convolutional Neural Network) untuk klasifikasi.
- **Evaluasi Model**: Evaluasi kinerja model dengan metrik seperti akurasi dan confusion matrix.
- **Visualisasi Hasil**: Menampilkan hasil klasifikasi dan performa model.

## Dataset
Dataset yang digunakan adalah [Kaggle Cats and Dogs Dataset](https://www.microsoft.com/en-us/download/confirmation.aspx?id=54765) yang terdiri dari:
- 12,500 gambar kucing untuk pelatihan.
- 12,500 gambar anjing untuk pelatihan.
- 2,500 gambar kucing untuk pengujian.
- 2,500 gambar anjing untuk pengujian.

## Arsitektur Model
Model yang digunakan adalah Convolutional Neural Network (CNN) dengan arsitektur sebagai berikut:
- **Input Layer**: Ukuran gambar 150x150 piksel.
- **Conv Layer 1**: 32 filter, ukuran kernel 3x3, activation ReLU.
- **Max Pooling 1**: Ukuran pool 2x2.
- **Conv Layer 2**: 64 filter, ukuran kernel 3x3, activation ReLU.
- **Max Pooling 2**: Ukuran pool 2x2.
- **Conv Layer 3**: 128 filter, ukuran kernel 3x3, activation ReLU.
- **Max Pooling 3**: Ukuran pool 2x2.
- **Fully Connected Layer**: 512 unit, activation ReLU.
- **Output Layer**: 1 unit, activation sigmoid.

## Persyaratan
- Python 3.6+
- TensorFlow 2.x
- Keras
- Pandas
- Numpy
- Matplotlib
- Google Colab

## Struktur Proyek

