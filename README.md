# REDLAMP_TA_5025221297
## Repository Tugas Akhir S1 Informatika ITS
## Alendra Rafif Athaillah (5025221297)

# Deskripsi Notebook:
- `EDALH`: Notebook untuk Exploratory Data Analysis dan Penggabungan data mentah.
- `TA_Main`:Notebook untuk Hyperparameter Tuning
- `Scenario`: Notebook untuk Menjalankan Skenario dengan model hasil Hyperparameter Tuning

# Panduan Menjalankan TA_Main
-  Panduan menggunakan Notebook ini:
- Jalankan cell 1 (Pip install), kemudian setelah instalasi selesai, ubah kembali cell 1 menjadi bentuk comment.
- kemudian lakukan "restart & clear cell output"
- kemudian dapat dilakukan "Run All"

# Panduan Menjalankan Scenario
- Notebook ini merupakan lanjutan dari notebook TA_Main.
- Hasil hyperparameter tuning dari TA_Main dapat diset di notebook ini pada cell 4 (Di atas markdown Dataset Loading
- Jalankan cell 1 (Pip install), kemudian setelah instalasi selesai, ubah kembali cell 1 menjadi bentuk comment.
- kemudian lakukan "restart & clear cell output"
- Setelah itu atur panjang window yang ingin dibentuk pada bagian windowing (cell 21), dan atur jumlah kelas yang akan digunakan pada augmentasi (cell 32)
- Jika ingin mengubah FAA delta, maka ubah pada pemanggilan fungsi apply_faa(). Default dari paper adalah 0,005
