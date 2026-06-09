#  Credit Risk Analysis & Approval Dashboard

##  Deskripsi Proyek
Proyek ini merupakan simulasi end-to-end analisis risiko kredit perbankan. Tujuannya adalah untuk memproses data mentah pengajuan kredit nasabah yang kotor dan tidak terstruktur, membersihkannya, lalu membangun *dashboard* interaktif guna membantu tim manajemen risiko (*Risk Management*) dalam mengambil keputusan persetujuan kredit berdasarkan profil nasabah.

##  Tools yang Digunakan
* **Microsoft Excel:** Data Cleaning, Data Imputation, Formatting.
* **Tableau Public:** Data Visualization, Dashboarding, Business Intelligence.

##  Proses Data Cleaning (Excel)
Sebelum divisualisasikan, dataset mentah melalui proses pembersihan ekstrem karena mengandung berbagai anomali:
1. **Standardisasi Format Tanggal:** Memperbaiki format tanggal yang bertabrakan (campuran format ID, US, dan teks huruf) menggunakan kombinasi *Find & Replace* dan *Text to Columns*.
2. **Penanganan Missing Values (Imputasi):** * Mengisi data usia yang kosong/outlier (seperti angka minus) menggunakan nilai *Median/Mean* dari populasi normal.
   * Mengisi kekosongan data Skor Kredit dan Tenor dengan nilai standar (default) industri.
3. **Pembersihan Teks & Karakter Bebas:** Menghapus simbol mata uang ("Rp") dan spasi ekstra pada kolom finansial, serta menyeragamkan ejaan status kredit menggunakan fungsi `TRIM` dan `UPPER`.

##  Dashboard & Visualisasi
*Dashboard* interaktif ini dirancang untuk menampilkan KPI utama dan metrik risiko.
**( [Klik di sini untuk melihat Dashboard interaktif di Tableau Public] - *Executive Credit Risk & Approval Dashboard.png*)**

##  Business Insights (Temuan Analisis)
Berdasarkan *dashboard* yang telah dibangun, berikut adalah rekomendasi dan wawasan bisnis yang ditemukan:

1. **Tingkat Persetujuan (Approval Rate):** Dari total pengajuan yang masuk bulan ini, tingkat persetujuan berada di kisaran **47,3%**. Ini menunjukkan bank menerapkan filter risiko yang cukup ketat dalam meloloskan plafon pinjaman.
2. **Profil Risiko Berdasarkan Pekerjaan:**
   * **Risiko Tinggi:** Kategori *Freelance* dan Pegawai Negeri Sipil (PNS) menunjukkan *Reject Rate* (tingkat penolakan) tertinggi pada periode ini.
   * **Risiko Rendah:** Kategori Wirausaha mendominasi pengajuan yang disetujui (Approved), menjadikannya segmen pasar yang paling potensial saat ini.
3. **Korelasi Gaji dan Plafon Pinjaman:**
   Berdasarkan grafik *Scatter Plot*, terdapat korelasi positif yang sehat; nasabah dengan gaji lebih tinggi diberikan plafon yang lebih besar. Sebagian besar penolakan (titik merah) terkonsentrasi pada nasabah dengan gaji di bawah Rp 20 Juta yang mengajukan plafon pinjaman terlalu tinggi (tidak sebanding dengan rasio pendapatan).
4. **Demografi Usia Nasabah:**
   Pasar terbesar pengajuan kredit berada pada rentang **usia 30-39 tahun**. Namun, bank perlu lebih berhati-hati dalam menyalurkan kredit kepada nasabah di usia 20-an (20-29 tahun), karena kelompok demografi ini menunjukkan rasio penolakan yang paling tinggi dibandingkan kelompok usia yang lebih matang.

---
**Author:**
Muhammad Al Gifari  
