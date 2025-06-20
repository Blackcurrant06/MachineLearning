# 📂 Folder Ujian Akhir Semester (UAS) Model Machine Learning

Folder ini terdiri dari tiga file utama yang mencakup model deep learning untuk tugas regresi, klasifikasi, dan CNN (Convolutional Neural Network).

Implementasi model regresi dan klasifikasi menggunakan TensorFlow dan PyTorch, sedangkan model CNN hanya menggunakan TensorFlow.

Hasil dari TensorFlow dan PyTorch untuk regresi dan klasifikasi akan dibandingkan.

## 1. Model Regresi (`Regression.ipynb`)

File ini berisi implementasi model regresi untuk memprediksi nilai kontinu.

Pipeline end-to-end meliputi:

a. Pengumpulan dan pembersihan data (menggunakan Pandas). Kolom target adalah kolom pertama dengan tipe integer.

b. Feature Engineering: transformasi data, label encoding, one-hot encoding, dll.

c. Pengembangan arsitektur MLP (Multi-Layer Perceptron) dengan teknik:

- Dropout

- Batch normalization

- Penyesuaian learning rate (learning rate scheduling)

- Optimizer modern (seperti Adam, RMSprop)

- Weight decay (L1/L2 regularization)

- Early stopping

d. Evaluasi menggunakan matriks RMSE, MSE, R-squared, serta visualisasi nilai prediksi vs aktual.

### Perbandingan Model Regresi (TensorFlow vs PyTorch)

| Framework  | Kelebihan                                 | Kekurangan                                  |
|------------|-------------------------------------------|---------------------------------------------|
| TensorFlow | High-level API (Keras) mudah digunakan    | Lebih berat, kurang fleksibel untuk riset   |
| PyTorch    | Fleksibel, dinamis, mudah debug           | Kurangnya high-level API yang matang        |

## 2. Model Klasifikasi (`Klasifikasi.ipynb`)

File ini berisi implementasi model klasifikasi untuk memprediksi label kategorikal.

Pipeline end-to-end meliputi:

a. Pengumpulan dan pembersihan data (menggunakan Pandas). Kolom target adalah kolom pertama dengan tipe integer.

b. Feature Engineering: transformasi data, label encoding, one-hot encoding, dll.

c. Pengembangan arsitektur MLP dengan teknik yang sama seperti pada regresi.

d. Evaluasi menggunakan matriks Akurasi, Presisi, Recall, F1-Score, serta visualisasi confusion matrix, AUC, dan ROC.

### Perbandingan Model Klasifikasi (TensorFlow vs PyTorch)

| Framework  | Kelebihan                                 | Kekurangan                                  |
|------------|-------------------------------------------|---------------------------------------------|
| TensorFlow | Dukungan produksi yang baik               | Kurang intuitif untuk pemula                |
| PyTorch    | Kode lebih Pythonic, populer di riset     | Dukungan deployment yang kurang dibanding TF|

## 3. Model CNN (`CNN.ipynb`)

File ini berisi implementasi model Convolutional Neural Network (CNN) untuk klasifikasi gambar.

Pipeline end-to-end meliputi:

a. Pengumpulan dan pembersihan data (menggunakan Pandas), preprocessing, dan augmentasi data.

b. Feature Engineering: transformasi data, label encoding, one-hot encoding.

c. Pengembangan arsitektur CNN dengan modul TensorFlow.

d. Evaluasi menggunakan matriks Akurasi, Presisi, Recall, F1-Score, AUC-ROC, serta visualisasi confusion matrix.

### Perbandingan Model CNN (hanya TensorFlow)

| Model      | Kelebihan                                 | Kekurangan                                  |
|------------|-------------------------------------------|---------------------------------------------|
| CNN        | Sangat baik untuk data gambar             | Memerlukan data dalam jumlah besar          |

