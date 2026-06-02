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

# E-Commerce Digital Product Sales Analysis
**Tujuan:** menganalisis performa penjualan produk digital (E-Book, Video Course, Template) selama 4 bulan pertama di tahun 2026. Analisis ini difokuskan pada penemuan tren penjualan, produk paling menguntungkan, dan efektivitas platform distribusi untuk mengoptimalkan strategi marketing ke depannya.
💡 Business Insights (Temuan Data)
Berdasarkan dashboard yang telah dibangun, ditemukan 3 wawasan bisnis utama:

Produk Bintang (Star Product): Video Course UI/UX mendominasi penjualan sebagai penyumbang omset terbesar (lebih dari Rp 120 Juta). Hal ini menunjukkan tingginya minat audiens terhadap pembelajaran desain interaktif.

Persaingan Platform: Platform WhatsApp (Rp 66,3 Juta) dan TikTok (Rp 64,4 Juta) bersaing sangat ketat di posisi teratas. Ini membuktikan bahwa strategi Direct Selling (WhatsApp) sama efektifnya dengan keranjang kuning Social Commerce (TikTok).

Anomali Tren Penjualan: Terdapat penurunan drastis pada grafik garis di bulan Mei. Setelah ditelusuri, hal ini terjadi karena data bulan Mei belum terkumpul secara penuh (inkomplit), bukan karena penurunan minat pembeli yang sesungguhnya.

🚀 Rekomendasi Bisnis
Alokasi Budget Marketing: Kurangi biaya iklan di platform yang kurang optimal dan fokuskan 80% anggaran promosi (ads) pada TikTok dan WhatsApp.

Bundling Product: Karena Course UI/UX sangat diminati, buat promo bundling dengan produk yang omsetnya lebih rendah (seperti Template Canva) untuk mendongkrak penjualan produk tersebut.
