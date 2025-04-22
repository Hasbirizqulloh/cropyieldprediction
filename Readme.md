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

Masalah utama yang menjadi fokus dalam study kasus ini adalah sebagai berikut:

1. **Memprediksi hasil panen berdasarkan faktor lingkungan dan input pertanian** karena hasil panen tanaman dipengaruhi oleh sejumlah faktor eksternal, di antaranya adalah curah hujan, suhu rata-rata, dan penggunaan pestisida. Ketidakpastian terhadap pengaruh dari faktor-faktor tersebut terhadap hasil pertanian seringkali menyulitkan petani dalam merencanakan produksi pertanian mereka. Oleh karena itu, dibutuhkan model prediktif yang dapat memproyeksikan hasil panen berdasarkan data yang tersedia, untuk memberikan gambaran yang lebih jelas tentang potensi hasil yang dapat diperoleh.

3. **Mengidentifikasi faktor-faktor yang paling berpengaruh terhadap hasil panen**. Selain prediksi hasil panen, sangat penting untuk memahami faktor-faktor lingkungan dan input pertanian yang memiliki dampak signifikan terhadap hasil panen. Identifikasi faktor-faktor ini dapat memberikan wawasan yang berguna dalam perencanaan dan pengelolaan sumber daya pertanian secara lebih efektif.

### Goals

Tujuan yang ingin dicapai dalam study kasus ini adalah sebagai berikut:

1. **Membangun model prediktif untuk hasil panen** yang dapat memproyeksikan hasil panen dengan akurasi yang baik. Model ini akan menggunakan data historis yang mencakup variabel-variabel seperti curah hujan, suhu, penggunaan pestisida, dan lainnya, untuk menghasilkan prediksi yang dapat membantu para petani dalam merencanakan strategi pertanian mereka.

2. **Menilai pengaruh faktor lingkungan dan input pertanian terhadap hasil panen** untuk mengeksplorasi dan menganalisis faktor-faktor yang paling berpengaruh terhadap hasil panen. Dengan mengetahui faktor mana yang memiliki dampak terbesar, diharapkan para pemangku kepentingan dapat mengambil kebijakan yang lebih tepat dalam mengelola sektor pertanian.

### Solution Statement

Untuk mencapai tujuan tersebut, beberapa solusi yang diusulkan dalam merancang model prediksi ini adalah sebagai berikut:

1. **Penerapan model regresi** karena mengingat bahwa hasil panen yang diprediksi merupakan variabel kontinu, model regresi akan diterapkan untuk menyelesaikan masalah ini. Beberapa model regresi yang akan diuji antara lain **Linear Regression**, **Random Forest Regression**, dan **XGBoost**. Masing-masing model ini akan dianalisis untuk melihat kecocokannya dalam memprediksi hasil panen berdasarkan variabel-variabel yang ada.

2. **Optimalisasi model melalui hyperparameter tuning** untuk meningkatkan performa model yang digunakan. Tahap **hyperparameter tuning** akan dilakukan guna mencari kombinasi parameter yang memberikan hasil terbaik. Proses ini diharapkan dapat meningkatkan akurasi prediksi dan memperbaiki kelemahan yang mungkin ada pada model dasar.

3. **Evaluasi dan pemilihan model terbaik** dengan melakukan pengujian terhadap model, performa masing-masing model akan dievaluasi menggunakan metrik yang relevan, seperti **Root Mean Squared Error (RMSE)** atau **R-squared (R²)**. Model dengan performa terbaik berdasarkan hasil evaluasi akan dipilih sebagai solusi akhir yang dapat digunakan untuk memprediksi hasil panen.

Dengan pendekatan ini, diharapkan dapat dicapai prediksi hasil panen yang lebih akurat dan dapat memberikan informasi yang lebih jelas bagi para petani dalam merencanakan kegiatan pertanian mereka, serta memberikan wawasan yang berguna bagi pengambilan keputusan dalam pengelolaan sektor pertanian secara lebih efisien dan berkelanjutan.


