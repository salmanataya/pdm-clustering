[Proyek Akhir Pengantar Data Mining]

# Pemetaan Karakteristik Kejahatan di London: Studi Klaster Berdasarkan Data MPS LSOA

Anggota Tim
1. Salma Dewi Nataya (23/518235/PA/22243)
2. Melani Sulistiawati (23/523106/PA/22507)

Dosen Pengampu: Dr. Adhitya Ronnie Effendie, S.Si., M.Si., M.Sc.

## Deskripsi Singkat

Proyek ini bertujuan untuk mengelompokkan wilayah-wilayah di Kota London berdasarkan pola kriminalitas yang dimiliki menggunakan metode *clustering*. Data yang digunakan adalah data kejahatan Metropolitan Police Service (MPS) London per wilayah LSOA. Analisis Utama dilakukan dalam dua tahap, yaitu
1. Analisis Eksploratif menggunakan visualisasi heatmap untuk memahami korelasi antar tipe kejahatan.
2. Klasterisasi dengan menerapkan 4 metode clustering: K-Means, K-Median, Agglomerative Hierarchical, dan Gaussian Mixture pada data tanpa dan dengan dimensionality reduction.Selanjutnya, dievaluasi menggunakan 4 metrik: Silhouette Score, Davies-Bouldin Index, Calinski-Harabasz Index, dan Dunn Index.

## Hasil Utama

Model terbaik secara metrik adalah **K-Median tanpa dimensional reduction**, namun terlalu timpang secara proporsi klaster. Dengan pertimbangan tersebut, model terpilih adalah K-Means dengan dimensional reduction yang memiliki keseimbangan proporsi klaster dan metrik yang mirip. Terbentuk 4 klaster wilayah dengan karakteristik kejahatan berbeda yang mencerminkan hasil analisis korelasi awal.

## Kesimpulan

Hasil clustering dari metode terpilih mencerminkan struktur korelasi antar tipe kejahatan dan mampu mengelompokkan wilayah secara bermakna. Temuan ini dapat digunakan sebagai dasar dalam merancang strategi penanganan kejahatan yang lebih terarah.