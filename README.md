# UTS Machine Learning — Jalur C (Clustering)

## Identitas Mahasiswa
* **Nama:** Achyar Yanizar
* **NIM:** 2301010543
* **Program Studi:** Informatika
* **Kelas:** XX
* **Mata Kuliah:** Machine Learning
* **Dosen Pengampu:** Dr. I Gede Totok Suryawan, S.Kom., M.T.

## Informasi Dataset & Cara Mengunduh
* **Judul Dataset:** Indonesia Tourism Destination (`tourism_with_id.csv`)
* **Sumber Data:** [Kaggle - Indonesia Tourism Destination](https://www.kaggle.com/datasets/aprabowo/indonesia-tourism-destination)
* **Lisensi:** Data files © Original Authors
* **Tanggal Akses:** 24 November 2026

Karena lisensi dataset berada di bawah hak cipta penulis asli (*© Original Authors*), file `.csv` mentah tidak disertakan langsung di dalam repository publik ini. Untuk mengunduh dan menjalankan ulang notebook:
1. Buka tautan dataset Kaggle di atas dan masuk menggunakan akun Kaggle.
2. Pilih file **`tourism_with_id.csv`** pada daftar file di sisi kanan halaman, lalu klik tombol **Download**.
3. Letakkan file `tourism_with_id.csv` di direktori kerja yang sama dengan notebook (atau unggah ke panel *Files* jika dijalankan melalui Google Colab).

## Struktur Repository
* `README.md`: Identitas mahasiswa, informasi cara unduh dataset, dan pernyataan penggunaan AI.
* `notebook/UTS_ML_2301010543_AchyarYanizar.ipynb`: Notebook utama berisi alur CRISP-DM lengkap yang telah dijalankan seluruh selnya (*Run All*).
* `reports/`: Kumpulan grafik visualisasi hasil eksplorasi data, perbandingan Elbow-Silhouette, dan evaluasi cluster.

## Pernyataan Penggunaan AI
* **Alat yang dipakai:** Google Gemini.
* **Bagian yang dibantu:** Penyusunan struktur kode Python untuk eksplorasi data (EDA), perbandingan metrik Elbow dan Silhouette Score, serta kerangka narasi interpretasi profil cluster berbasis alur CRISP-DM.
* **Cara pemeriksaan hasil:** Seluruh kode dijalankan secara mandiri di Google Colab (`Runtime -> Run all`), parameter `SEED = 543` (tiga digit terakhir NIM) dan `StandardScaler` diverifikasi langsung terhadap output statistik aktual dataset `tourism_with_id.csv`.
