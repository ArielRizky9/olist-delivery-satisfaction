# Analisis Pengaruh Keterlambatan Pengiriman terhadap Kepuasan Pelanggan Olist

Proyek analisis data pada marketplace Olist (Brasil): seberapa besar keterlambatan
pengiriman menurunkan skor review, dan di mana perbaikan logistik perlu diprioritaskan.

**Dashboard interaktif (Tableau Public):** https://public.tableau.com/views/OlistDeliveryCustomerSatisfaction_17953610979450/DashboardOlist

## Temuan utama
- Hanya 6,77% dari 96.470 order delivered yang terlambat, tetapi skor review turun
  dari 4,29 (tepat waktu) menjadi 2,27 (terlambat).
- Mann-Whitney U satu sisi signifikan, effect size rank-biserial 0,638 (besar).
- Keterlambatan terkonsentrasi di MA, CE, BA, RJ, PA, rute lintas state, order
  multi-penjual, dan bulan Nov 2017, Feb dan Mar 2018.

## Isi repository
- `analisis_olist.ipynb`: profiling, EDA, cleaning, validasi, feature engineering, uji statistik
- `output/`: hasil analisis (CSV, JSON) dan grafik EDA
- `images/`: tangkapan layar dashboard

## Cara menjalankan
1. Unduh dataset dari Kaggle: Brazilian E-Commerce Public Dataset by Olist.
2. Taruh 9 file CSV di folder `data/` (sejajar dengan notebook).
3. Jalankan notebook dari atas ke bawah (Colab atau Jupyter lokal).

## Sumber data dan atribusi
Olist & Sionek, A. (2018). Brazilian E-Commerce Public Dataset by Olist. Kaggle.
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

## Penyusun
Kelompok 8 (7C), Sistem Informasi, UIN Syarif Hidayatullah Jakarta:
Marsha Eriana Chalidi dan Muhammad Ariel Rizky.
