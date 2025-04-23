## Domain Proyek

Pertanian merupakan sektor fundamental dalam menopang kebutuhan hidup manusia, terutama dalam penyediaan bahan pangan dan bahan baku industri [[1]](https://doi.org/10.3390/agriculture10060200). Di banyak negara, khususnya negara berkembang, pertanian juga menjadi sumber utama pendapatan masyarakat dan berperan penting dalam menjaga stabilitas ekonomi nasional [[2]](https://scindeks-clanci.ceon.rs/data/pdf/0352-3462/2019/0352-34621904091U.pdf), [[3]](https://doi.org/10.3390/su12083261). Oleh karena itu, produktivitas pertanian menjadi faktor yang sangat krusial dalam mendukung ketahanan pangan dan pembangunan berkelanjutan.

Namun, hasil panen tidak selalu stabil dari tahun ke tahun. Perubahan kondisi lingkungan, seperti curah hujan, suhu udara, serta penggunaan pestisida, dapat memengaruhi hasil produksi pertanian [[4]](https://doi.org/10.3390/ijerph18031112). Ketidakpastian akibat variasi faktor-faktor ini sering menjadi kendala utama dalam pengelolaan lahan dan perencanaan pertanian yang efektif. Dampaknya tidak hanya dirasakan oleh petani secara langsung, tetapi juga pada rantai pasok pangan secara keseluruhan.

Kemajuan teknologi dalam bidang analisis data dan kecerdasan buatan kini membuka peluang untuk mengatasi tantangan tersebut. Salah satu pendekatan yang banyak dikembangkan adalah penerapan machine learning untuk memprediksi hasil panen berdasarkan data historis dan faktor lingkungan [[5]](https://doi.org/10.3390/computers12010010). Dengan membangun model prediktif yang andal, informasi seperti rata-rata curah hujan tahunan, suhu udara, serta penggunaan pestisida dapat dianalisis untuk memperkirakan hasil produksi secara lebih akurat [[6]](https://doi.org/10.1109/ICCV51070.2023.00531). Hasil prediksi ini dapat digunakan oleh petani, peneliti, maupun pembuat kebijakan sebagai dasar dalam pengambilan keputusan strategis yang lebih tepat sasaran dan adaptif terhadap perubahan kondisi lingkungan.

### Mengapa dan Bagaimana Masalah Ini Harus Diselesaikan

Fluktuasi hasil panen merupakan masalah krusial dalam sektor pertanian yang berdampak langsung terhadap **ketahanan pangan**, **kesejahteraan petani**, serta **stabilitas ekonomi** negara, terutama negara yang sangat bergantung pada agrikultur [[7]](https://link.springer.com/article/10.1007/s10584-022-03306-1). Ketidakmampuan untuk memprediksi hasil panen secara akurat dapat menyebabkan:
- **Kelebihan atau kekurangan suplai**, yang mempengaruhi harga pangan.
- **Perencanaan distribusi yang buruk**, yang dapat menyebabkan kerugian bagi petani dan konsumen.
- **Kesalahan strategi kebijakan pangan nasional**, seperti subsidi, ekspor-impor, dan distribusi bantuan.

Oleh karena itu, penerapan machine learning menjadi salah satu pendekatan yang menjanjikan, mengingat kemampuannya dalam mengolah data historis yang kompleks serta menghasilkan prediksi dengan tingkat akurasi yang tinggi. Melalui pembangunan model prediktif yang didasarkan pada variabel lingkungan dan input pertanian, berbagai pemangku kepentingan dapat memperoleh manfaat yang signifikan. Petani dapat menggunakan informasi prediktif tersebut untuk menentukan waktu tanam yang optimal dan mengatur penggunaan pestisida secara lebih efisien. Pemerintah dapat memanfaatkan hasil prediksi dalam merumuskan kebijakan yang berbasis data serta merencanakan distribusi pangan secara lebih tepat sasaran. Selain itu, lembaga keuangan juga dapat menggunakan informasi ini sebagai dasar objektif dalam proses evaluasi pemberian pinjaman atau asuransi pertanian, yang pada akhirnya mendukung pengembangan sektor pertanian secara berkelanjutan.

Implementasi solusi ini dilakukan melalui pendekatan regresi menggunakan data historis yang tersedia, kemudian membangun model prediktif dengan algoritma machine learning seperti **Random Forest**, **XGBoost**, dan **Linear Regression**. Evaluasi akan dilakukan menggunakan metrik seperti **R²** dan **Root Mean Square Error (RMSE)** untuk menilai akurasi model.

### Referensi

1. A. R. Anik, S. Rahman, and J. R. Sarker, “Five decades of productivity and efficiency changes in world agriculture (1969–2013),” Agric., vol. 10, no. 6, pp. 1–21, 2020, doi: 10.3390/agriculture10060200.  
2. D. Užar and V. Radojević, “The importance of agriculture in forming gross value added in Serbia in the period of 2008-2017,” Ekon. Poljopr., vol. 66, no. 4, pp. 1091–1105, 2019, doi: 10.5937/ekopolj1904091u.
3. G. Milošević, M. Kulić, Z. Durić, and O. Durić, “The taxation of agriculture in the republic of serbia as a factor of development of organic agriculture,” Sustain., vol. 12, no. 8, 2020, doi: 10.3390/SU12083261.
4. Tudi, M., Daniel Ruan, H., Wang, L., Lyu, J., Sadler, R., Connell, D., Chu, C., & Phung, D. T. (2021). Agriculture Development, Pesticide Application and Its Impact on the Environment. International journal of environmental research and public health, 18(3), 1112. https://doi.org/10.3390/ijerph18031112.
5. Bhimavarapu, U., Battineni, G., & Chintalapudi, N. (2023). Improved Optimization Algorithm in LSTM to Predict Crop Yield. Computers, 12(1), 10. https://doi.org/10.3390/computers12010010.
6. F. Lin et al., “MMST-ViT: Climate Change-aware Crop Yield Prediction via Multi-Modal Spatial-Temporal Vision Transformer,” Proc. IEEE Int. Conf. Comput. Vis., pp. 5751–5761, 2023, doi: 10.1109/ICCV51070.2023.00531.
7. T. Ginbo, “Heterogeneous impacts of climate change on crop yields across altitudes in Ethiopia,” Clim. Change, vol. 170, no. 1–2, 2022, doi: 10.1007/s10584-022-03306-1.

## Business Understanding

Pada tahap ini, dilakukan klarifikasi terhadap permasalahan yang akan diselesaikan serta tujuan yang ingin dicapai melalui penerapan teknik **machine learning**. Penjelasan mengenai masalah utama yang dihadapi dalam konteks prediksi hasil pertanian, serta tujuan dari solusi yang diusulkan, akan disajikan secara rinci dalam bagian ini.

### Problem Statements

Masalah utama yang menjadi fokus dalam proyek ini adalah sebagai berikut:

1. Hasil panen tanaman sangat dipengaruhi oleh sejumlah faktor eksternal seperti curah hujan, suhu udara rata-rata, dan penggunaan pestisida. Ketidakpastian terhadap pengaruh faktor-faktor tersebut menyulitkan petani dalam merencanakan produksi secara optimal. Oleh karena itu, diperlukan suatu pendekatan yang mampu memproyeksikan hasil panen secara akurat berdasarkan data historis dan kondisi lingkungan.

2. Tidak semua faktor lingkungan memiliki pengaruh yang sama terhadap hasil panen. Ketidaktahuan mengenai faktor-faktor dominan yang memengaruhi produktivitas pertanian dapat menyebabkan penggunaan sumber daya yang tidak efisien. Maka, dibutuhkan analisis yang dapat mengidentifikasi variabel mana yang paling signifikan dalam memengaruhi hasil panen.

### Goals

Tujuan utama dari proyek ini adalah membangun model prediktif yang dapat membantu memproyeksikan hasil panen berdasarkan faktor-faktor yang memengaruhinya, seperti curah hujan, suhu, dan penggunaan pestisida. Beberapa sasaran utama dari proyek ini adalah:

1. Membangun model prediktif berbasis machine learning untuk memperkirakan hasil panen (dalam satuan hg/ha) dengan akurasi tinggi. Model ini akan menggunakan data historis pertanian yang mencakup variabel lingkungan seperti curah hujan, suhu udara rata-rata, dan penggunaan pestisida sebagai input prediktor.

2. Melakukan analisis terhadap kontribusi masing-masing variabel lingkungan dan input pertanian dalam memengaruhi hasil panen, sehingga dapat diidentifikasi faktor-faktor yang paling berpengaruh. Hasil analisis ini diharapkan dapat membantu pengambilan keputusan yang lebih tepat dalam perencanaan dan manajemen pertanian.


### Metodologi
Masalah yang akan diselesaikan dalam proyek ini adalah regresi, karena hasil panen yang diprediksi merupakan variabel kontinu. Oleh karena itu, model yang akan dibangun adalah model regresi yang memprediksi hasil panen dalam satuan hektogram per hektar (hg/ha) berdasarkan data historis yang mencakup berbagai fitur, seperti:

- Curah hujan tahunan (mm per tahun)

- Suhu rata-rata tahunan (°C)

- Penggunaan pestisida (ton)

Untuk mencapai tujuan tersebut, beberapa solusi yang diusulkan dalam merancang model prediksi ini adalah sebagai berikut:

1. **Penerapan model regresi** karena mengingat bahwa hasil panen yang diprediksi merupakan variabel kontinu, model regresi akan diterapkan untuk menyelesaikan masalah ini. Beberapa model regresi yang akan diuji antara lain **Linear Regression**, **Random Forest Regression**, dan **XGBoost**. Masing-masing model ini akan dianalisis untuk melihat kecocokannya dalam memprediksi hasil panen berdasarkan variabel-variabel yang ada.

2. **Optimalisasi model melalui hyperparameter tuning** untuk meningkatkan performa model yang digunakan. Tahap **hyperparameter tuning** akan dilakukan guna mencari kombinasi parameter yang memberikan hasil terbaik. Proses ini diharapkan dapat meningkatkan akurasi prediksi dan memperbaiki kelemahan yang mungkin ada pada model dasar.

### Metrik Evaluasi

**Evaluasi dan pemilihan model terbaik** dengan melakukan pengujian terhadap model, performa masing-masing model akan dievaluasi menggunakan metrik yang relevan untuk mengevaluasi seberapa baik model memprediksi hasil panen, beberapa metrik evaluasi yang digunakan adalah:

- Root Mean Square Error (RMSE) untuk mengukur rata-rata kesalahan prediksi dalam satuan yang sama dengan data asli.

- R-squared (R²) untuk mengukur seberapa baik variabilitas data dapat dijelaskan oleh model.

Dengan pendekatan ini, diharapkan dapat dicapai prediksi hasil panen yang lebih akurat dan dapat memberikan informasi yang lebih jelas bagi para petani dalam merencanakan kegiatan pertanian mereka, serta memberikan wawasan yang berguna bagi pengambilan keputusan dalam pengelolaan sektor pertanian secara lebih efisien dan berkelanjutan.

## Data Understanding

Dataset yang digunakan dalam proyek ini berjudul **"Crop Yield Prediction Dataset"**, yang diperoleh dari platform [Kaggle](https://www.kaggle.com/datasets/mrigaankjaswal/crop-yield-prediction-dataset). Dataset ini terdiri dari **28.242 entri** dan mencakup data historis mengenai hasil pertanian serta beberapa variabel lingkungan dari berbagai negara. Data ini sangat relevan dalam konteks pengembangan model prediktif untuk estimasi hasil panen berbasis faktor lingkungan.

### Deskripsi Fitur

Dataset ini memiliki tujuh kolom utama, dengan penjelasan sebagai berikut:

- **`Area (Country)`**  
  Variabel kategorikal yang menunjukkan lokasi geografis (negara) dari data yang dicatat. Dapat digunakan sebagai fitur setelah dilakukan encoding.

- **`Item`**  
  Jenis produk pertanian atau komoditas, seperti gandum, jagung, dan sebagainya. Merupakan variabel kategorikal, bisa digunakan untuk klasifikasi spesifik komoditas.

- **`Year`**  
  Tahun pencatatan data (numerik). Digunakan untuk melihat tren temporal dan pengaruh waktu terhadap hasil panen.

- **`hg/ha_yield`**  
  Target atau label dari model, yaitu hasil panen dalam satuan hectogram per hektar (hg/ha). Variabel numerik kontinu.

- **`average_rain_fall_mm_per_year`**  
  Curah hujan rata-rata tahunan (dalam mm). Merupakan salah satu faktor utama dalam pertumbuhan tanaman.

- **`pesticides_tonnes`**  
  Total penggunaan pestisida dalam satuan ton. Pengaruhnya terhadap hasil panen bersifat kompleks.

- **`avg_temp`**  
  Rata-rata suhu udara tahunan (dalam °C). Faktor penting yang memengaruhi pertumbuhan dan hasil panen tanaman.

### Eksploratory Data Analysis (EDA)

Pada tahap ini, dilakukan beberapa tahapan eksplorasi untuk memahami karakteristik dataset. Proses ini mencakup teknik visualisasi data dan analisis eksploratif untuk mendapatkan wawasan yang lebih mendalam mengenai data yang digunakan. Berikut adalah tahapan yang dilakukan:

#### 1. Deskripsi Variable  
Memahami setiap fitur dalam dataset, baik yang kategorikal maupun numerik. Ini termasuk penjelasan tentang Area, Item, Year, serta variabel target yaitu hg/ha_yield, yang merupakan hasil panen dalam satuan hectogram per hektar. Pengetahuan ini sangat penting sebelum melakukan analisis lebih lanjut. Hasil dari tahap ini adalah sebagai berikut:
    - hg/ha_yield merupakan target yang ingin diprediksi, yaitu hasil panen dalam satuan hectogram per hektar (hg/ha).
    - Variabel Area dan Item adalah kategorikal dan perlu dilakukan encoding sebelum digunakan dalam model.
    - Variable Year, hg/ha_yield, average_rain_fall_mm_per_year, pesticides_tonnes, dan avg_temp merupakan variable numerik.
    
#### 2. Menangani Missing Value dan Outliers
   - Missing Values  
Mengidentifikasi apakah ada data yang hilang pada setiap kolom dan menentukan apakah akan menghapus atau menggantinya menggunakan teknik imputation. Pada tahap ini hasilnya tidak ditemukan adanya nilai kosong (NaN/null) di seluruh kolom dataset, sehingga tidak perlu dilakukan imputasi atau penghapusan data karena masalah nilai hilang dan hanya terdapat kolom bernama Unnamed, yang merupakan duplikasi dari index baris. Kolom ini tidak memberikan informasi tambahan dan telah dihapus.
   - Outliers  
Mendeteksi outliers yang dapat memengaruhi hasil analisis dan model. Pada tahap ini outliers terdeteksi pada tiga variabel utama berdasarkan hasil statistik deskriptif, yaitu:
      - `hg/ha_yield`: Nilai maksimum mencapai 501,412, jauh di atas Q3 (104,676.75).
      - `avg_temp`: Nilai minimum avg_temp sebesar 1.3°C setelah dianalisis ternyata berasal dari Norway, dan masih dianggap wajar mengingat iklim negara tersebut yang dingin tapi harus tetap ditangani nilai outliernya.
      - `pesticides_tonnes`: Rentang nilai dari 0.04 hingga 367,778 ton. Nilai minimum berasal dari tahun-tahun awal di beberapa negara dan dianggap valid, meskipun secara statistik tergolong ekstrem.
        
      Penanganan dilakukan dengan metode **Interquartile Range (IQR)**:
     ```python
      outlier_cols = df_clean[['pesticides_tonnes', 'avg_temp', 'hg/ha_yield']]
      Q1 = outlier_cols.quantile(0.25)
      Q3 = outlier_cols.quantile(0.75)
      IQR = Q3 - Q1

      df_clean_ou = df_clean[~((outlier_cols < (Q1 - 1.5 * IQR)) | (outlier_cols > (Q3 + 1.5 * IQR))).any(axis=1)]
     ```
     Dataset df_clean_ou merupakan hasil dari proses ini, yang telah disaring dari nilai outlier untuk ketiga fitur tersebut. Dataset ini akan digunakan untuk proses analisis dan modeling lebih lanjut.


#### 3. Univariate Analysis  
Menganalisis distribusi setiap variabel secara terpisah menggunakan visualisasi seperti histogram atau boxplot. Hal ini membantu memahami pola data dan mendeteksi ketidakseimbangan atau distribusi yang tidak normal, terutama pada variabel target (hg/ha_yield).
Analisis univariat bertujuan untuk melihat distribusi setiap fitur secara individu. Analisis ini dibagi menjadi dua bagian:
- Fitur Kategorikal
Distribusi kategori dianalisis menggunakan metode value counts dan visualisasi bar chart horizontal. Fokus pada dua fitur utama: `Area` (negara) dan `Item` (komoditas pertanian).

  **Distribusi Area (Negara):**

    | Negara       | Count | Percent (%) |
    |--------------|--------|-------------|
    | India        | 3630   | 14.6%       |
    | Pakistan     | 1449   | 5.8%        |
    | Mexico       | 1368   | 5.5%        |
    | Brazil       | 891    | 3.6%        |
    | Indonesia    | 828    | 3.3%        |
    | ...          | ...    | ...         |
    | Belgium      | 26     | 0.1%        |
    | Norway       | 23     | 0.1%        |
    | Sweden       | 23     | 0.1%        |

    📌 **Insight:** Data paling banyak berasal dari India (14.6%), diikuti oleh Pakistan dan Mexico. Negara dengan jumlah data terkecil antara lain Norwegia, Swedia, dan Belgia.

    **Distribusi Item (Komoditas):**

    | Komoditas               | Count | Percent (%) |
    |-------------------------|--------|-------------|
    | Maize                   | 3959   | 16.0%       |
    | Wheat                   | 3690   | 14.9%       |
    | Rice, paddy             | 3226   | 13.0%       |
    | Soybeans                | 3061   | 12.3%       |
    | Sorghum                 | 2877   | 11.6%       |
    | Potatoes                | 2871   | 11.6%       |
    | Sweet potatoes          | 2468   | 9.9%        |
    | Cassava                 | 1460   | 5.9%        |
    | Yams                    | 684    | 2.8%        |
    | Plantains and others    | 519    | 2.1%        |

    📌 **Insight:** Komoditas dengan jumlah data terbanyak adalah jagung (`Maize`) sebesar 16%, disusul gandum (`Wheat`) dan padi (`Rice, paddy`). Komoditas minor seperti `Plantains`,           `Yams`, dan `Cassava` hanya menyumbang sebagian kecil.
- Fitur Numerikal
Distribusi fitur numerik divisualisasikan menggunakan histogram dengan 60 bin:

![Histograms of Numerical Features](./Images/download.png)

          Fitur yang dianalisis:

          - `Year`
          - `hg/ha_yield`
          - `average_rain_fall_mm_per_year`
          - `pesticides_tonnes`
          - `avg_temp`

  📌 **Insight Histogram:**

  - **Year:** Distribusi seragam antara 1990 hingga 2013.
  - **hg/ha_yield:** Terdistribusi miring ke kanan (right-skewed), menunjukkan banyak data berada di rentang yield yang rendah.
  - **average_rain_fall_mm_per_year:** Terlihat ada puncak-puncak curah hujan tertentu yang mendominasi dataset.
  - **pesticides_tonnes:** Skewed ke kanan. Banyak nilai kecil, tetapi juga ada beberapa data ekstrem (outlier) dengan penggunaan pestisida sangat tinggi.
  - **avg_temp:** Terdistribusi cukup normal, namun dengan dua puncak (bimodal), kemungkinan menunjukkan perbedaan iklim antar negara (subtropis vs tropis/dingin).


#### 4. Multivariate Analysis
Menganalisis hubungan antara fitur-fitur dalam dataset menggunakan scatter plot, heatmap korelasi, atau visualisasi lainnya. Ini membantu mengidentifikasi keterkaitan antar variabel, seperti hubungan antara suhu, curah hujan, dan hasil panen.
  
- Identifikasi nilai hilang (missing values) dan pencilan (outliers) pada fitur numerik.
- Visualisasi hubungan antara fitur numerik seperti curah hujan, suhu, dan pestisida terhadap hasil panen menggunakan scatter plot dan heatmap korelasi.
- Analisis tren hasil panen dari tahun ke tahun berdasarkan rata-rata yield nasional.

Langkah-langkah eksplorasi ini memberikan wawasan awal yang penting sebagai dasar untuk proses persiapan data dan pembangunan model prediktif.

