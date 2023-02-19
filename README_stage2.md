Pada soal nomer pertama, Dari missing values terdapat 1 buah NaN dari fitur Risk_Flag namun tidak ada duplicated data. 
Untuk outliers tidak ada yang menonjol jadi tidak perlu di handle dan untuk transofrmasi hanya pada di fitur Income karena range yang sangat jauh dan jumlah angka yang sangat besar. 
Encoding dilakukan pada beberapa fitur seperti pada married/single, car_ownership berupa label encoding dan pada House_ownership dengan One-hot Encoding.
sedangkan dari soal nomer 2, Untuk Feature Selection pada data ini dibuang fitur profession, city, state, dan penggantian untuk fitur house_ownership. 
Untuk feature extraction dibuat fitur baru pada one-hot encoding pada house_ownership dan penambahan fitur baru pada group klasifikasi pada Income, Age, dan CURRENT_JOB_YRS untuk grouping experience level.
