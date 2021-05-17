# Python-methods

- **.drop_duplictes()** atau **.drop_duplicates(['nama_kolom'])** : menghapus data yang duplikat
- **.sort_values('...', ascending=False)** : sort data dari yang terakhir
- **.isnull().sum().sum()** : mengetahui jumlah totat missing value
- **.isnull().sum()** : mengetahui jumlah missing value perkolom
- **.isnull().values.any()** : mengecek adakah missing value. True=Ada. False=Tidak ada.
- **.dropna(subset=['nama_kolom'], inplace=True)** : hapus semua data missing value di kolom tertentu
- **.fillna(..., inplace=True)** : mengganti missing value
- **.quantile(0.25)** : Quartil 1
- **.quantile(0.75)** : Quartil 3
- **.mask(...., ...., axis=1)** : mengganti 
- **.describe()**
- **.info()**
- **.columns** : mendapatkan nama-nama kolom di dataset
- **.shape** : mendapatkan dimensi data
- **.value_counts()** : melihat jumlah data unik per variabel
- **.replace([..],[..])** : mengganti x dengan y
- 
