# Praktikum_AI_Workflow
2306141_Rabiul Tsani Ghifarulhaq A

# Implementasi AI dalam Analisis dan Prediksi Penjualan Produk

## Deskripsi Proyek
Proyek ini bertujuan untuk menerapkan kecerdasan buatan (AI) dalam menganalisis dan memprediksi penjualan produk. Dengan menggunakan metode machine learning, proyek ini dapat membantu dalam menentukan kebutuhan restock produk berdasarkan data historis penjualan.

## Tahapan Proyek
1. **Pembuatan Dataset**  
   Dataset dibuat dalam format CSV yang mencakup informasi produk, jumlah terjual, stok yang tersedia, dan harga satuan.

2. **Pembersihan dan Pengolahan Data**  
   Data diproses untuk memastikan tidak ada data yang hilang, duplikat, atau tidak valid sehingga siap digunakan dalam model AI.

3. **Pelatihan Model AI**  
   Menggunakan algoritma *Decision Tree Classifier* untuk melatih model dalam memprediksi apakah suatu produk perlu di-restock berdasarkan pola penjualan yang ada.

4. **Prediksi dan Visualisasi**  
   Model yang telah dilatih digunakan untuk membuat prediksi kebutuhan restock serta menampilkan visualisasi hubungan antara jumlah terjual, stok, dan keuntungan.

## Cara Menjalankan Proyek di Google Colab
1. Buka Google Colab di [colab.research.google.com](https://colab.research.google.com/)
2. Buat notebook baru atau unggah file notebook yang telah disiapkan.
3. Pastikan semua dependensi telah terinstal dengan menjalankan perintah berikut di sel pertama:
   ```python
   !pip install pandas scikit-learn matplotlib seaborn
   ```
4. Unggah dataset ke Google Colab atau hubungkan ke Google Drive dengan perintah:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```
5. Jalankan skrip analisis dan prediksi sesuai dengan urutan sel dalam notebook.


