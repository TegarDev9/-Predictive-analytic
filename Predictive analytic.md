# Laporan Proyek Machine Learning - Tegar karunia ilham

## Domain Proyek

Analitik prediktif telah menjadi alat yang penting dalam memprediksi gaji pekerjaan di berbagai bidang. Dalam dunia analitik prediktif, terdapat berbagai metode yang digunakan untuk membangun model prediksi yang akurat. Dua metode yang populer dalam konteks prediksi gaji pekerjaan adalah Boosting dan Random Forest.
Metode Boosting merupakan teknik ensemble learning yang menggabungkan beberapa model lemah menjadi satu model yang kuat. Dalam konteks prediksi gaji pekerjaan, metode Boosting dapat digunakan untuk menghasilkan model yang dapat mempelajari hubungan non-linear antara berbagai fitur dan gaji. Model Boosting, seperti Gradient Boosting, dapat memperkuat prediksi dengan mempertimbangkan kesalahan prediksi sebelumnya dan fokus pada sampel yang sulit diprediksi.Sementara itu, metode Random Forest juga merupakan teknik ensemble learning yang berdasarkan pada pohon keputusan. Metode ini membangun banyak pohon keputusan secara independen dan menggabungkan hasil prediksi dari setiap pohon untuk menghasilkan prediksi akhir. Dalam prediksi gaji pekerjaan, Random Forest dapat mengatasi masalah overfitting dan memberikan performa yang baik dalam menangani dataset dengan banyak fitur.Perbandingan antara metode Boosting dan Random Forest dalam konteks prediksi gaji pekerjaan menjadi topik yang menarik untuk diteliti. Tujuan dari perbandingan ini adalah untuk menentukan metode mana yang lebih baik dalam memprediksi gaji pekerjaan dan memahami kelebihan serta kelemahan masing-masing metode. Penelitian ini dapat membantu organisasi atau perusahaan dalam mengambil keputusan berdasarkan prediksi gaji yang lebih akurat, sehingga dapat meningkatkan efisiensi dan efektivitas dalam pengelolaan sumber daya manusia.Dengan membandingkan metode Boosting dan Random Forest dalam prediksi gaji pekerjaan, kita dapat mengidentifikasi metode mana yang paling sesuai dengan data dan tujuan prediksi tertentu. Hasil perbandingan ini dapat memberikan wawasan yang berharga dalam pengembangan model prediksi gaji pekerjaan dan dapat menjadi acuan dalam pengambilan keputusan berbasis data di bidang pengelolaan sumber daya manusia.

Contoh kasus yang lebih spesifik mengenai pentingnya perbandingan antara metode Boosting dan Random Forest dalam konteks pengelolaan sumber daya manusia adalah sebagai berikut:
Misalkan sebuah perusahaan sedang mencari metode yang paling efektif untuk memprediksi gaji calon karyawan berdasarkan berbagai faktor seperti pengalaman kerja, pendidikan, dan keterampilan yang dimiliki. Perusahaan tersebut ingin memastikan bahwa keputusan yang diambil dalam menentukan gaji didasarkan pada prediksi yang akurat dan dapat membantu mereka dalam pengelolaan sumber daya manusia.Dalam hal ini, perbandingan antara metode Boosting dan Random Forest dapat memberikan pandangan yang lebih jelas tentang metode mana yang lebih sesuai dengan tujuan perusahaan. Misalnya, jika dataset yang dimiliki memiliki banyak fitur dan hubungan non-linear yang kompleks antara fitur dan gaji, maka metode Boosting dapat menjadi pilihan yang lebih baik. Dengan mempertimbangkan kesalahan prediksi sebelumnya, metode Boosting dapat menghasilkan model yang mampu mempelajari pola-pola yang rumit dalam data dan memberikan prediksi yang lebih akurat.Di sisi lain, jika dataset yang dimiliki memiliki risiko overfitting atau terdapat banyak fitur yang tidak relevan, maka metode Random Forest dapat menjadi solusi yang lebih baik. Dalam kasus ini, metode Random Forest dapat mengatasi masalah overfitting dan memberikan performa yang baik dalam menangani dataset dengan banyak fitur. Metode ini juga dapat memberikan pemahaman yang lebih baik tentang pentingnya setiap fitur dalam prediksi gaji.

Dengan melakukan perbandingan antara metode Boosting dan Random Forest, perusahaan dapat mengevaluasi performa dan karakteristik masing-masing metode dalam konteks prediksi gaji pekerjaan. Hasil perbandingan ini dapat membantu perusahaan dalam mengambil keputusan yang lebih baik dalam menentukan metode yang paling sesuai dengan data yang mereka miliki. Sebagai hasilnya, perusahaan dapat meningkatkan efisiensi dan efektivitas dalam pengelolaan sumber daya manusia dengan menggunakan prediksi gaji yang lebih akurat dan berbasis data.

## Business Understanding

Dalam dunia analitik prediktif, penting untuk memilih metode yang tepat untuk memprediksi gaji pekerjaan secara akurat. Dalam konteks ini, terdapat dua metode yang populer, yaitu metode Boosting dan Random Forest. Namun, belum ada pemahaman yang jelas tentang perbandingan kinerja dan keefektifan antara metode Boosting dan Random Forest dalam prediksi gaji pekerjaan.Masalah yang perlu dipecahkan adalah menentukan metode mana yang lebih unggul dalam memprediksi gaji pekerjaan secara akurat dan efisien. Dengan adanya perbedaan karakteristik antara metode Boosting dan Random Forest, penting untuk memahami kelebihan dan kelemahan masing-masing metode serta bagaimana kinerja keduanya dalam kasus prediksi gaji pekerjaan.
Dalam memecahkan masalah ini, perlu dilakukan perbandingan langsung antara metode Boosting dan Random Forest menggunakan dataset gaji pekerjaan yang relevan. Perbandingan ini akan melibatkan evaluasi analisis kinerja keduanya dalam hal akan membandingkan mse antar random fores dan boosting. Tujuannya adalah untuk mengetahui metode mana yang memberikan prediksi gaji pekerjaan yang lebih akurat, efektif, dan praktis dalam konteks analitik prediktif.Dengan melakukan evaluasi yang komprehensif terhadap aspek-aspek di atas, kita dapat membandingkan kinerja metode Boosting dan Random Forest dalam prediksi gaji pekerjaan secara lebih rinci. Hasil evaluasi tersebut akan memberikan wawasan yang lebih mendalam tentang kelebihan dan kelemahan masing-masing metode, serta membantu organisasi dan perusahaan dalam memilih metode yang paling sesuai dengan kebutuhan mereka dalam pengelolaan sumber daya manusia.
Dengan menyelesaikan perbandingan ini, organisasi dan perusahaan dapat membuat keputusan yang lebih baik dalam memilih metode yang paling sesuai dengan kebutuhan mereka dalam memprediksi gaji pekerjaan. Hal ini akan membantu meningkatkan efisiensi dan akurasi dalam pengelolaan sumber daya manusia, memungkinkan pengambilan keputusan yang lebih baik terkait penggajian, dan mendukung kebijakan yang lebih baik dalam hal pengembangan karir dan manajemen tenaga kerja.

Bagian laporan ini mencakup:

### Problem Statements

Menjelaskan pernyataan masalah latar belakang:
- Bagaimana cara melakukan evaluasi yang komprehensif untuk membandingkan kinerja metode Boosting dan Random Forest dalam prediksi gaji pekerjaan?


### Goals

Menjelaskan tujuan dari pernyataan masalah:
- Jawaban pernyataan masalah 1
- Jawaban pernyataan masalah 2
- Jawaban pernyataan masalah n

Semua poin di atas harus diuraikan dengan jelas. Anda bebas menuliskan berapa pernyataan masalah dan juga goals yang diinginkan.

**Rubrik/Kriteria Tambahan (Opsional)**:
- Menambahkan bagian “Solution Statement” yang menguraikan cara untuk meraih goals. Bagian ini dibuat dengan ketentuan sebagai berikut: 

    ### Solution statements
    - Mengajukan 2 atau lebih solution statement. Misalnya, menggunakan dua atau lebih algoritma untuk mencapai solusi yang diinginkan atau melakukan improvement pada baseline model dengan hyperparameter tuning.
    - Solusi yang diberikan harus dapat terukur dengan metrik evaluasi.

## Data Understanding
Paragraf awal bagian ini menjelaskan informasi mengenai data yang Anda gunakan dalam proyek. Sertakan juga sumber atau tautan untuk mengunduh dataset. Contoh: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Restaurant+%26+consumer+data).

Selanjutnya uraikanlah seluruh variabel atau fitur pada data. Sebagai contoh:  

### Variabel-variabel pada Restaurant UCI dataset adalah sebagai berikut:
- accepts : merupakan jenis pembayaran yang diterima pada restoran tertentu.
- cuisine : merupakan jenis masakan yang disajikan pada restoran.
- dst

**Rubrik/Kriteria Tambahan (Opsional)**:
- Melakukan beberapa tahapan yang diperlukan untuk memahami data, contohnya teknik visualisasi data atau exploratory data analysis.

## Data Preparation
Pada bagian ini Anda menerapkan dan menyebutkan teknik data preparation yang dilakukan. Teknik yang digunakan pada notebook dan laporan harus berurutan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan proses data preparation yang dilakukan
- Menjelaskan alasan mengapa diperlukan tahapan data preparation tersebut.

## Modeling
Tahapan ini membahas mengenai model machine learning yang digunakan untuk menyelesaikan permasalahan. Anda perlu menjelaskan tahapan dan parameter yang digunakan pada proses pemodelan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan kelebihan dan kekurangan dari setiap algoritma yang digunakan.
- Jika menggunakan satu algoritma pada solution statement, lakukan proses improvement terhadap model dengan hyperparameter tuning. **Jelaskan proses improvement yang dilakukan**.
- Jika menggunakan dua atau lebih algoritma pada solution statement, maka pilih model terbaik sebagai solusi. **Jelaskan mengapa memilih model tersebut sebagai model terbaik**.

## Evaluation
Pada bagian ini anda perlu menyebutkan metrik evaluasi yang digunakan. Lalu anda perlu menjelaskan hasil proyek berdasarkan metrik evaluasi yang digunakan.

Sebagai contoh, Anda memiih kasus klasifikasi dan menggunakan metrik **akurasi, precision, recall, dan F1 score**. Jelaskan mengenai beberapa hal berikut:
- Penjelasan mengenai metrik yang digunakan
- Menjelaskan hasil proyek berdasarkan metrik evaluasi

Ingatlah, metrik evaluasi yang digunakan harus sesuai dengan konteks data, problem statement, dan solusi yang diinginkan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan formula metrik dan bagaimana metrik tersebut bekerja.

**---Ini adalah bagian akhir laporan---**

_Catatan:_
- _Anda dapat menambahkan gambar, kode, atau tabel ke dalam laporan jika diperlukan. Temukan caranya pada contoh dokumen markdown di situs editor [Dillinger](https://dillinger.io/), [Github Guides: Mastering markdown](https://guides.github.com/features/mastering-markdown/), atau sumber lain di internet. Semangat!_
- Jika terdapat penjelasan yang harus menyertakan code snippet, tuliskan dengan sewajarnya. Tidak perlu menuliskan keseluruhan kode project, cukup bagian yang ingin dijelaskan saja.
