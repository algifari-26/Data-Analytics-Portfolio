# Data Mining & Analytics: Studi Kasus Retail (Mall Customers)

**Dibuat oleh:** Muhammad Al Gifari  
**Tools:** Python, Google Colab, Pandas, Scikit-Learn, Matplotlib  

Repositori ini berisi rangkaian proyek analisis data (*Data Mining*) menggunakan dataset pelanggan retail (`Mall_Customers.csv`). Analisis dibagi menjadi dua tahap untuk menggali *insight* bisnis yang komprehensif.

---

# Part 1: Customer Segmentation (K-Means Clustering)
**File Analisis:** [`Muhammad_Al_Gifari_KMeans.ipynb`](./Muhammad_Al_Gifari_KMeans.ipynb)

* **Tujuan:** Mengelompokkan pelanggan berdasarkan Pendapatan (*Annual Income*) dan Skor Pengeluaran (*Spending Score*) menggunakan algoritma *Unsupervised Learning* (K-Means).
* **Insight Utama:** Pelanggan terbagi menjadi 5 kelompok unik. Terdapat satu kelompok "Bintang" yang berpendapatan tinggi dan sangat boros, serta kelompok "Target Masa Depan" yang pendapatannya masih rendah tapi sangat suka berbelanja.
* **Rekomendasi:** Membuat program loyalitas premium untuk kelompok "Bintang" dan menawarkan diskon produk terjangkau untuk menjaga retensi kelompok "Target Masa Depan".

---

# Part 2: Prediksi Skor Pengeluaran Berdasarkan Usia (Linear Regression)
**File Analisis:** [`Muhammad_Al_Gifari_Linear_Regression.ipynb`](./Muhammad_Al_Gifari_Linear_Regression.ipynb)

* **Tujuan:** Menguji hipotesis lanjutan menggunakan *Supervised Learning* untuk melihat sejauh mana faktor Usia memengaruhi Skor Pengeluaran pelanggan.
* **Insight Utama:** Terdapat **korelasi negatif**. Kelompok usia muda (20-40 tahun) adalah pendorong omzet utama dengan pengeluaran maksimal (100). Sebaliknya, usia lanjut (50-70 tahun) sangat menahan pengeluaran (maksimal di skor 60).
* **Rekomendasi:** Memprioritaskan alokasi dana *marketing* pada promosi yang menargetkan usia 20-40 tahun untuk *Return on Investment* (ROI) tertinggi, serta mengevaluasi variasi produk toko agar lebih ramah untuk pengunjung senior.

---
*Silakan klik judul file `.ipynb` di atas untuk melihat kode lengkap dan visualisasi grafiknya.*
*dan analisis ini menggunakan dataset publik Mall_Customers.csv yang bersumber dari Kaggle.*
