Kelompok Loanalytics :

ada beberapa insight yang kami dapatkan dari dataset Loan Prediction Based on Customer Behavior, yaitu:
1. dari descriptive analysis kami mendapatkan bahwa dari keseluruhan nama dan kolom sudah sesuai, kolom tidak ada yg memiliki nilai null dan nilai summary tidak ada nilai yang aneh

2. untuk Univariate Analysis ada beberapa point yang didapatkan yaitu:
-Mayoritas data memiliki distribusi normal, Untuk di current job years terdapat positively skewed. 
-Tidak ditemukan outlier dalam data sehingga tidak perlu dilakukan pembersihan terhadap outlier saat pre-processing.
-Pada fitur profession, city, serta state ditemukan terdapat terlalu banyak kategori sehingga fitur-fitur tersebut dapat diabaikan ketika pembuatan model, dengan melakukan penghapusan kolom ketika pre-processing.
Dengan demikian, yang perlu di-follow up ketika pre-processing, yaitu:
-Keberadaan missing value, outlier, serta nilai duplikat.
-Penghapusan kolom yang tidak diperlukan dalam modelling.
-Encode kolom yang bertipe object.

3. Pada Multivariate Analysis korelasi tertinggi antara masing masing feature dan label hanya dimiliki oleh current job years dan experience sebesar 65%, sehingga itulah yang paling relevan dan harus dipertahankan.

4. untuk business insght hasil yang kami dapatkan adalah
-Current job years serta rentang gaji mempengaruhi kemampuan customer dalam membayar pinjaman
-Rentang umur yang gagal membayar pinjaman ada di range 64-67 (umur tidak produktif bekerja)
=Kebanyakan dari customer yang "Rented" dari House Ownership lebih banyak memiliki Risk Flag daripada yang memiliki atau sama sekali tidak memiliki kepemilikan tempat tinggal
Dari ketika poin diatas dapat disimpulkan menjadi sebuah rekomendasi bisnis dimana dalam peminjaman perlu diperhatikan kemampuan customer dalam pembayaran loan, dalam hal ini bisa terlihat dari umur, gaji, current job years serta kepemilikan customer terhadap suatu properti yang lain

