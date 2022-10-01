Tampak beberapa kolom masih memiliki null/missing values kolom  make, model, vin, trim, body, transmission,  condition, odometer, color, interior. 
Missing Values tertinggi ada di kolom transmission sejumlah 65353
Perlu dilakukan handling missing value dengan imputasi nilai mean atau median pada kolom yang memiliki jumlah missing value banyak, dan dapat dilakukan drop/ menghapus baris yang missing valuenya sedikit 
Sudah tidak ada data yang duplikat pada dataset ini 
Kolom mmr masih butuh tinjauan lebih lanjut pada pre-processing karena nilai minimum rentangnya lumayan jauh dari mean dan median
Terdapat anomali pada nilai minimum sellingprice dicurigai data tidak diketahui sehingga data diimputasi dengan nilai 1 atau mobil yang dijual berupa program perusahaan (hadiah)
