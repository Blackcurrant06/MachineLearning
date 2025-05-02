# 📂Folder ujian Tengah Semester Model Machine Learning
Proyek ini terdiri dari tiga file utama yang mencakup berbagai model machine learning untuk tugas regresi, klasifikasi, dan clustering. Setiap file berisi implementasi beberapa algoritma dengan pendekatan yang berbeda.

## 1. Model Regresi
File regression_models.py mencakup implementasi model regresi untuk memprediksi nilai kontinu menggunakan algoritma berikut:
- Linear Regression
- Polynomial Regression (PolynomialFeatures + LinearRegression)
- Decision Tree Regressor
- K-Nearest Neighbors Regressor (KNN)
- Bagging Regressor
- Boosting Regressor (AdaBoost, Gradient Boosting)
- Support Vector Regressor (SVR)
### 📊 Perbandingan Model Regresi
| Model                   | Kelebihan                                       | Kekurangan                                              |
| ----------------------- | ----------------------------------------------- | ------------------------------------------------------- |
| Linear Regression       | Sederhana, interpretasi mudah                   | Tidak cocok untuk hubungan non-linear                   |
| Polynomial Regression   | Menangani hubungan non-linear                   | Rentan overfitting jika derajat polinomial tinggi       |
| Decision Tree Regressor | Menangani data non-linear dan interaksi fitur   | Rentan overfitting tanpa pruning                        |
| KNN Regressor           | Non-parametrik, mudah dipahami                  | Lambat saat prediksi, sensitif terhadap outlier         |
| Bagging Regressor       | Mengurangi overfitting, meningkatkan stabilitas | Kompleksitas model meningkat, interpretasi sulit        |
| Boosting Regressor      | Akurasi tinggi, menangani bias dan varians      | Rentan overfitting, sensitif terhadap noise             |
| SVR                     | Efektif untuk data berdimensi tinggi            | Memerlukan tuning parameter, lambat untuk dataset besar |

## 2. Model Klasifikasi
File classification_models.py mencakup implementasi model klasifikasi untuk memprediksi label kategorikal menggunakan algoritma berikut:
- Logistic Regression
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)
- Bagging / Boosting Classifier
- Support Vector Machine (SVM)
### 📊 Perbandingan Model Klasifikasi
| Model                    | Kelebihan                                   | Kekurangan                                              |
| ------------------------ | ------------------------------------------- | ------------------------------------------------------- |
| Logistic Regression      | Probabilistik, interpretasi koefisien mudah | Asumsi linearitas, kurang efektif untuk data non-linear |
| Decision Tree Classifier | Mudah dipahami, menangani fitur kategorikal | Rentan overfitting tanpa pruning                        |
| KNN Classifier           | Sederhana, tidak memerlukan pelatihan       | Lambat saat prediksi, sensitif terhadap dimensi tinggi  |
| Bagging Classifier       | Mengurangi varians, meningkatkan akurasi    | Kompleksitas model meningkat, interpretasi sulit        |
| Boosting Classifier      | Akurasi tinggi, menangani bias dan varians  | Rentan overfitting, sensitif terhadap noise             |
| SVM                      | Efektif untuk data berdimensi tinggi        | Memerlukan tuning parameter, lambat untuk dataset besar |

## 3. Model Clustering
File clustering_models.py mencakup implementasi model clustering untuk segmentasi data tanpa label menggunakan algoritma berikut:
- KMeans
- Agglomerative Clustering
- DBSCAN
- Gaussian Mixture Model (GMM)
- Spectral Clustering
###📊 Perbandingan Model Clustering
| Model                    | Kelebihan                                | Kekurangan                                                      |
| ------------------------ | ---------------------------------------- | --------------------------------------------------------------- |
| KMeans                   | Cepat, efisien untuk dataset besar       | Asumsi bentuk cluster bulat, sensitif terhadap outlier          |
| Agglomerative Clustering | Tidak memerlukan jumlah cluster awal     | Lambat untuk dataset besar, sulit menentukan titik potong       |
| DBSCAN                   | Menangani cluster dengan bentuk arbitrer | Sensitif terhadap parameter ε dan MinPts                        |
| Gaussian Mixture Model   | Menangani cluster yang tumpang tindih    | Sensitif terhadap inisialisasi, dapat konvergen ke solusi lokal |
| Spectral Clustering      | Menangani cluster non-konveks            | Memerlukan jumlah cluster awal, mahal secara komputasi          |







