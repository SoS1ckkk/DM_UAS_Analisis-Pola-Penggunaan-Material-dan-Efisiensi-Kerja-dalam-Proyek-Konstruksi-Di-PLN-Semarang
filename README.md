# DM_UAS_Analisis-Pola-Penggunaan-Material-dan-Efisiensi-Kerja-dalam-Proyek-Konstruksi-Di-PLN-Semarang
1. Judul
   Judul : Analisis Pola Penggunaan Material dan Efisiensi Kerja dalam Proyek Konstruksi Di PLN Semarang Timur

   Identitas Lengkap :
   -  Nama     : Aldev Smara Dahana Suryabudhi Rahardjo
   -  NIM      : A11.2020.12880
   -  Program Studi : Teknik Informatika
   -  Universitas : Dian Nuswantoro
   -  Mata Kuliah : Data mining 


2. Ringkasan Dan Permasalahan Proyek
   Dalam kegiatan konstruksi, efisiensi kerja dan distribusi material adalah dua elemen kunci yang memengaruhi keberhasilan proyek. Namun, pengelolaan manual sering kali menyebabkan inefisiensi, seperti kelebihan stok material, alokasi petugas yang tidak optimal, atau keterlambatan dalam pengiriman material. Proyek ini bertujuan untuk menganalisis data operasional yang mencakup tanggal pelaksanaan, lokasi proyek, jenis material, nama petugas, dan volume material yang digunakan. Dengan menggunakan teknik data mining, eksperimen ini akan menggali pola distribusi material, mengevaluasi kinerja petugas, dan memprediksi kebutuhan material di masa depan.

   - Masalah:
   1. Ketidakefisienan distribusi material karena kurangnya pemahaman pola kebutuhan setiap lokasi.
   2. Kesulitan dalam mengukur kinerja petugas terkait beban kerja dan hasil yang dicapai.
   3. Tidak adanya alat bantu prediktif untuk perencanaan kebutuhan material di lokasi tertentu.
   4. Kurangnya kejujuran petugas lapangan akan material yang di butuhkan
   - Tujuan:
   1. Mengidentifikasi pola distribusi material berdasarkan lokasi, waktu, dan petugas.
   2. Mengevaluasi efisiensi petugas dalam menyelesaikan tugas berdasarkan volume material yang dikelola.
   3. Membuat model prediktif untuk membantu perencanaan distribusi material yang lebih efisien.

   Alur / Tahapan / Kerangka Eksperimen
   1. Tahap Preprocessing Data:
   - Membersihkan data dari duplikasi dan nilai kosong.
   - Normalisasi format data, seperti pengubahan format tanggal dan konversi satuan volume material.
   2. Eksplorasi Data (Exploratory Data Analysis):
   - Membuat visualisasi seperti histogram, scatter plot, dan heatmap untuk menganalisis pola distribusi       
    material.
   - Analisis temporal untuk menemukan tren berdasarkan waktu (harian, mingguan, atau musiman).
   3. Teknik Data Mining:
   - Clustering :
   - Menggunakan algoritma seperti K-Means untuk mengelompokkan lokasi berdasarkan pola penggunaan material.
   - Association Rules :
   - Menggunakan algoritma Apriori untuk menemukan hubungan antara jenis material dan efisiensi kerja petugas.
   - Forecasting :
   - Menggunakan regresi linear atau model machine learning lainnya untuk memprediksi kebutuhan material    
    berdasarkan data historis.
   4. Evaluasi Hasil:
   - Menggunakan metrik seperti Mean Absolute Error (MAE) atau Root Mean Squared Error (RMSE) untuk mengukur 
    akurasi prediksi.
   - Validasi hasil clustering dengan Silhouette Score.
   5. Pelaporan dan Visualisasi:
   - Membuat laporan analisis.


3. Penjelasan Dataset
   - Sumber Data:
   Dataset ini berasal dari pencatatan operasional di berbagai lokasi proyek. Setiap entri berisi informasi    
   tentang waktu pelaksanaan, lokasi, jenis material, nama petugas, dan volume material yang digunakan.
   - Penjelasan Fitur:
   1. TANGGAL: Tanggal pelaksanaan kegiatan. Digunakan untuk analisis temporal untuk memahami pola musiman dan 
   tren waktu.
   2. ALAMAT : Lokasi kegiatan. Digunakan untuk analisis spasial untuk memahami distribusi material di berbagai 
   lokasi.
   3. MATERIAL : Jenis material yang digunakan (misalnya, MCB). Memberikan wawasan tentang jenis material yang 
   paling banyak digunakan.
   4. PETUGAS : Nama petugas yang bertugas. Digunakan untuk mengevaluasi kinerja petugas berdasarkan beban 
   kerja yang diselesaikan.
   5. VOLUME : Volume material yang digunakan (contoh: "18M"). Memberikan informasi tentang jumlah material 
   yang dikelola di setiap proyek.


