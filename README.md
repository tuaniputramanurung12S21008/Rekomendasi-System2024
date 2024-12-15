# Rekomendasi-System2024

Deskripsi Proyek
Danau Toba adalah destinasi wisata yang terkenal di Indonesia, namun banyak wisatawan kesulitan untuk menemukan tempat wisata yang sesuai dengan preferensi mereka. Sistem rekomendasi ini dirancang untuk memberikan rekomendasi tempat wisata di sekitar Danau Toba berdasarkan dua pendekatan utama: Collaborative Filtering dan Content-Based Filtering, yang digabungkan dalam model Hybrid untuk meningkatkan akurasi dan relevansi rekomendasi.

Selain itu, untuk membandingkan kinerja model Hybrid, sistem ini juga mengimplementasikan dua algoritma lain, yaitu TF-IDF dan K-Nearest Neighbors (KNN), yang sering digunakan dalam sistem rekomendasi berbasis konten dan data pengguna

Metodologi
Hybrid Model (Collaborative + Content-Based)
Model ini menggabungkan dua pendekatan:

Collaborative Filtering (CF): Menganalisis interaksi pengguna dengan tempat wisata (misalnya rating atau kunjungan) untuk memberikan rekomendasi berdasarkan kesamaan pengguna.
Content-Based Filtering (CBF): Menggunakan informasi tentang atribut tempat wisata, seperti kategori, lokasi, dan fasilitas, untuk memberikan rekomendasi berdasarkan kesamaan konten.
Hybrid Model menggabungkan kedua pendekatan tersebut, dengan tujuan untuk memanfaatkan kelebihan keduanya dan mengurangi kelemahan masing-masing, seperti cold-start problem pada Collaborative Filtering dan keterbatasan fitur pada Content-Based Filtering.

TF-IDF (Term Frequency-Inverse Document Frequency)
Model ini menggunakan teknik TF-IDF untuk memberikan bobot pada fitur-fitur yang ada dalam deskripsi tempat wisata. Dengan menggunakan informasi ini, model dapat merekomendasikan tempat wisata berdasarkan kesamaan deskripsi teks.

KNN (K-Nearest Neighbors)
KNN adalah algoritma berbasis konten yang digunakan untuk mencari tempat wisata yang mirip dengan tempat wisata yang dipilih oleh pengguna berdasarkan fitur-fitur yang ada. Dalam konteks ini, KNN digunakan untuk mencari tempat wisata yang memiliki kesamaan deskripsi atau atribut dengan tempat wisata yang sudah dipilih atau disukai oleh pengguna.


Evaluasi dan Hasil
Evaluasi dilakukan menggunakan beberapa metrik, antara lain:

Mean Absolute Error (MAE): Untuk mengukur akurasi model dalam memprediksi rating.
Precision@K dan Recall@K: Untuk mengukur relevansi rekomendasi.
F1-Score: Kombinasi dari precision dan recall.



Hasil Evaluasi menggunakan Proposed Model Hybrid Model (Collaborative + Content - Based Filtering)![Evaluatin Proposed model](https://github.com/user-attachments/assets/4831c2ab-4778-4dc4-aa16-c7f51741e7a9)

Top 5 Tempat Wisata yang dapat Dikunjungi

![Evaluatin Proposed model](https://github.com/user-attachments/assets/81f2b34f-d06d-4fe6-810b-850267b20737)


