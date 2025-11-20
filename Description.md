# Analisis Perilaku Belanja Konsumen USA untuk Strategi Bisnis Glam’s Apparel

## Repository Outline
1. README.md - Penjelasan gambaran umum project  
2. P0M1_BayuPutradana.ipynb - Notebook berisi pengolahan data, analisis deskriptif, inferensial, insight, dan rekomendasi bisnis  
3. shopping_behavior_clean.csv - Dataset perilaku belanja konsumen di USA  
  

## Problem Background
Glam’s Apparel adalah brand pakaian yang berencana memasuki pasar Amerika Serikat. Untuk bisa bersaing, dibutuhkan pemahaman mendalam mengenai perilaku konsumen, preferensi belanja, dan faktor-faktor yang memengaruhi keputusan pembelian. Analisis ini penting untuk merancang strategi produk, harga, dan promosi yang sesuai dengan target pasar.

## Project Output
Output dari project ini berupa:
- Notebook analisis data (Statistik deskriptif dan Statistik inferensial)  
- Insight mengenai pola belanja konsumen  
- Rekomendasi strategi bisnis Glam’s Apparel berdasarkan data  
- Interaktif dashboard yang bisa diakses [disini ](https://public.tableau.com/app/profile/bayu.putradana/viz/DashboardM1Final2/DashboardM1pg1?publish=yes)

## Data
- Sumber: Dataset *Shopping Behavior in the USA*  
- Karakteristik:  
  - Jumlah kolom: 18 (Customer ID, Age, Gender, Item Purchased, Category, Purchase Amount (USD), dst.)  
  - Jumlah baris: ± 3900 data konsumen  
  - Tipe data: campuran numerik (Age, Purchase Amount) & kategorikal (Gender, Payment Method, Season, dsb.)  
  - Terdapat missing values pada beberapa kolom  
- Relevansi: Data ini mencerminkan perilaku belanja konsumen USA yang menjadi target pasar Glam’s Apparel.  

## Method
Metode yang digunakan dalam project ini:
1. Data Preprocessing → pembersihan missing values & outlier. 
2. Analisis Visual → untuk mengetahui karakteristik konsumen dan produk yg dibeli.
2. Statistik Deskriptif → tendensi sentral, variasi, analisis outlier.  
4. Statistik Inferensial → uji perbedaan pengeluaran (T-Test), hubungan variabel kategorikal (Chi-Square), dan confidence interval.  
5. Interpretasi & Rekomendasi Bisnis → strategi segmentasi, positioning, dan marketing untuk Glam’s Apparel.  

## Stacks
- Bahasa Pemrograman: Python  
- Tools: Jupyter Notebook / Visual Studio Code , Tableau
- Libraries:  
  - Pandas & NumPy → manipulasi data  
  - Matplotlib & Seaborn → visualisasi data  
  - SciPy → uji statistik 

## Reference
- Dataset: [Shopping Behavior in the USA (Kaggle)](https://www.kaggle.com/datasets/zubairamuti/shopping-behaviours-dataset)  
