
**Big Data Analytics Kimia Farma x Rakamin Academy Batch Mei 2024**
--- 

SQL Tool: Google BigQuery - [Lihat Query SQL](https://console.cloud.google.com/bigquery?sq=771506489227:3029c578e3da45c4bc413f2a66e9c6e2)

Visualization Tool: Google Looker Studio - [Lihat Dashboard](https://lookerstudio.google.com/reporting/4bd4e9dd-e5b5-4358-86a3-91d414e862eb/page/YCT1D)


Program Introduction
---
Melalui program magang virtual Project Based Internship (PBI) yang diselenggarakan oleh Rakamin Academy bekerja sama dengan berbagai perusahaan, saya berkesempatan untuk mengembangkan potensi dan menambah pengalaman di bidang Big Data Analytics. Saya ditempatkan di Kimia Farma dengan tanggung jawab menganalisis dan melaporkan data terkait Performance Analytics Kimia Farma selama periode 2020-2023.

**Challenge**
- Membuat tabel analisa
- Membuat visualisas/dashboard Performance Analytics Kimia Farma di Tahun 2020 - 2023

**Dataset**
- Final transaction - [Lihat Dataset Final Transaction](https://drive.google.com/file/d/1iDOBdKZ4-kkLhpklQWWrsFvACtI7MCz3/view)
- Inventory - [Lihat Dataset Inventory](https://drive.google.com/file/d/1ihtG2t0V1AO0IAGkGwQaqtba6AxDEKDI/view)
- Kantor Cabang - [Lihat Dataset Kantor Cabang](https://drive.google.com/file/d/1vzaasqIeXqqe_jI99dNLaa8nxnoe9OWW/view)
- Product - [Lihat Dataset Product](https://drive.google.com/file/d/1739wO7BwtVStHCA4Dcj9xGhlc_blBNbT/view)



Desain Datamart
---
**Tabel Analisa**

Pada tahap ini, saya akan membuat tabel analisis dengan menggunakan tiga tabel, yaitu kf_final_transaction, kf_product, dan kf_kantor_cabang yang terdapat dalam dataset kimia_farma_dataset. Sebelum kita melanjutkan ke proses query, mari kita lihat Entity Relationship Diagram (ERD) yang menggambarkan relasi antar tabel. ERD ini membantu kita memahami bagaimana tabel-tabel tersebut saling terhubung.

 ![image](https://github.com/mzfarhan/Kimia-Farma-Final-Task/assets/64683758/20d32e58-cf08-426e-9bff-d20726504b29)

Dari ERD yang diberikan, kita dapat menyimpulkan bahwa:
- Setiap transaksi hanya berisi satu produk dan terjadi di satu cabang.
- Namun, satu produk atau satu cabang dapat terlibat dalam lebih dari satu transaksi.

Dari dashboard yang telah dibuat, terdapat beberapa insight yang bisa diambil yaitu:

- Pertumbuhan yang tidak signifikan: Terutama pada total net sales, total net profil dan total transaction dari tahun ke tahun.
- Jawa Barat Sebagai Kontributor Utama: Jawa Barat merupakan provinsi dengan kontribusi terbesar terhadap total penjualan, baik dari segi total transaction, total net profit, dan total net sales.
- Produk Terlaris: Produk terlaris Kimia Farma adalah Psycholeptics drugs, Hypnotics and sedatives drugs, dengan total penjualan mencapai 134.849.
- Rata-rata Penjualan Berbeda: Rata-rata penjualan per cabang berbeda-beda.
- Peringkat Cabang yang bagus : Terlihat peningkatan peringkat cabang dengan rating cabang masih diatas 4 dan rating transaksi yang berada di angka 4.

Dari insight yang telah dijabarkan di atas, kita dapat memberikan beberapa reccomendation:

- Fokus pada Jawa Barat: Konsentrasikan strategi pemasaran dan distribusi di Jawa Barat untuk terus mendorong pertumbuhan penjualan.
- Ekspansi ke Provinsi Lain: Pertimbangkan untuk membuka cabang baru di provinsi lain dengan potensi pertumbuhan tinggi seperti Sumatera Utara dan Jawa Timur.
- Dorong Penjualan Produk Terlaris: Tingkatkan promosi dan strategi pemasaran produk-produk terlaris untuk meningkatkan penjualan lebih lanjut.
- Tingkatkan Rating dan Transaksi Cabang: Kembangkan program pelatihan dan insentif bagi karyawan untuk meningkatkan rating dan transaksi cabang.
- Analisis Performa Cabang: Melakukan analisis secara detail performa setiap cabang untuk menentukan strategi dan program yang efektif untuk meningkatkan penjualan.
