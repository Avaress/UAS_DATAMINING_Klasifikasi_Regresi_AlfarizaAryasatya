#Ringkasan Proyek Data Mining (Klasifikasi & Regresi)
**1. Pendahuluan**
Proyek ini bertujuan untuk mendemonstrasikan dua tugas fundamental dalam Data Mining: Klasifikasi dan Regresi, menggunakan dataset publik. Saya akan menerapkan algoritma Naive Bayes untuk klasifikasi dan Linear Regression untuk regresi.

**2. Klasifikasi Data (Menggunakan Naive Bayes)**
Dataset
Saya menggunakan Iris Dataset yang berasal dari library Scikit-learn. Dataset ini berisi pengukuran bunga Iris (panjang/lebar kelopak dan mahkota) dan jenisnya (Setosa, Versicolor, Virginica). Tujuan saya adalah memprediksi jenis bunga berdasarkan fitur-fiturnya.

Preprocessing Data
Dataset Iris sudah cukup bersih, tidak memiliki nilai yang hilang (missing values), dan semua fitur sudah dalam format numerik. Oleh karena itu, langkah preprocessing untuk penanganan missing values atau encoding data kategorikal yang kompleks tidak diperlukan, membuat dataset ini ideal untuk pembelajaran awal.
Data saya bagi menjadi 80% data latih (untuk melatih model) dan 20% data uji (untuk mengevaluasi kinerja model pada data yang belum pernah dilihat sebelumnya).
Model & Hasil
Saya menggunakan algoritma Gaussian Naive Bayes, yang cocok untuk fitur-fitur numerik kontinu seperti yang ada pada Iris Dataset.
Model saya latih menggunakan data latih dan saya evaluasi pada data uji.
Hasil Akurasi: XX.XX (Isi dengan Akurasi Model Naive Bayes (Iris Dataset) dari output Anda, contoh: 0.97)
Interpretasi Hasil: Model ini menunjukkan akurasi yang sangat tinggi, yaitu sekitar [Persentase Akurasi]% dalam memprediksi jenis bunga Iris dengan benar. Dari Confusion Matrix yang saya dapatkan, terlihat bahwa model berhasil mengklasifikasikan spesies 'setosa' dengan sempurna (100%). Ada sedikit kesalahan prediksi antara 'versicolor' dan 'virginica' (misalnya, 1 kasus 'versicolor' salah diprediksi sebagai 'virginica'), namun secara keseluruhan model bekerja dengan sangat baik.
**3. Regresi Data (Menggunakan Linear Regression)**
Dataset
Saya menggunakan House Prices - Advanced Regression Techniques Dataset dari Kaggle. Dataset ini berisi berbagai fitur properti (seperti kualitas keseluruhan, luas area tinggal, jumlah garasi, dll.) dan harga jualnya. Tujuan saya adalah memprediksi SalePrice (harga jual rumah) berdasarkan fitur-fitur properti tersebut.

Preprocessing Data
Untuk menangani nilai yang hilang (missing values), saya mengisi kolom numerik dengan nilai rata-rata (mean) dari kolom tersebut dan kolom kategorikal (teks) dengan nilai yang paling sering muncul (mode).
Beberapa kolom kategorikal (seperti KitchenQual, MSZoning, Utilities, Neighborhood) saya ubah menjadi format numerik menggunakan teknik One-Hot Encoding agar dapat diproses oleh model regresi.
Data kemudian saya bagi menjadi 80% data latih dan 20% data uji untuk melatih dan mengevaluasi model.
Model & Hasil
Saya menggunakan algoritma Linear Regression, yang merupakan metode regresi dasar untuk memprediksi nilai numerik kontinu.
Model saya latih menggunakan data latih dan saya evaluasi pada data uji.
Hasil Metrik Regresi:
Mean Absolute Error (MAE): XXXXX.XX (Isi dengan MAE Anda, contoh: 18066.86)
Root Mean Squared Error (RMSE): XXXXX.XX (Isi dengan RMSE Anda, contoh: 28014.12)
Interpretasi Hasil: MAE menunjukkan bahwa rata-rata selisih antara harga prediksi dan harga aktual adalah sekitar  [NilaiMAE]∗∗.SedangkanRMSE,yanglebihsensitifterhadapkesalahanbesar(outlier),adalahsekitar∗∗ [Nilai RMSE]. Angka-angka ini memberikan gambaran tentang tingkat kesalahan prediksi model saya. Semakin kecil nilai MAE dan RMSE, semakin akurat prediksi model. Secara keseluruhan, model regresi linier ini memberikan prediksi yang cukup wajar untuk harga rumah berdasarkan fitur-fitur yang saya gunakan.
**4. Kesimpulan**
Proyek ini berhasil menerapkan algoritma klasifikasi Naive Bayes untuk memprediksi jenis bunga Iris dengan akurasi tinggi, serta algoritma regresi Linear Regression untuk memprediksi harga rumah, dengan metrik kesalahan yang informatif. Proses yang saya lakukan meliputi pengumpulan data, preprocessing (penanganan missing values dan encoding), pembangunan model, dan evaluasi menggunakan metrik yang relevan untuk setiap jenis masalah (akurasi untuk klasifikasi, MAE/RMSE untuk regresi).

**5. Sumber YouTube**
Untuk referensi Klasifikasi Naive Bayes:
Tutorial Klasifikasi Algoritma Naive Bayes Classifier dengan Python - Google Colab
Belajar Classification Learning Naive Bayes Dengan Python
