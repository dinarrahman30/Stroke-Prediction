# Submission 1: Stroke Prediction
Nama: Dinar Wahyu Rahman

Username dicoding: dinar_wahyu

| | Deskripsi |
| ----------- | ----------- |
| Dataset | [Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset) |
| Masalah | Menurut Organisasi Kesehatan Dunia (WHO), stroke merupakan penyebab kematian terbanyak ke-2 di dunia, yang menyebabkan sekitar 11% dari total kematian. |
| Solusi machine learning | Solusi yang diusulkan adalah membangun model klasifikasi berbasis machine learning untuk memprediksi apakah seorang pasien memiliki risiko tinggi terkena stroke (1) atau tidak (0). Hal ini dilakukan dengan menganalisis atribut risiko seperti usia, riwayat hipertensi, kadar glukosa rata-rata, status merokok, dan jenis pekerjaan. Model ini dapat membantu para profesional medis untuk mengambil tindakan pencegahan lebih dini. |
| Metode pengolahan | - **Pra-pemrosesan data**: Melakukan imputasi nilai-nilai hilang (khususnya pada kolom `smoking_status`). <br> - Normalisasi pada fitur numerik seperti `avg_glucose_level` dan `age`. <br> - Encoding pada fitur kategori seperti `gender`, `work_type`, dan `Residence_type` menggunakan One-Hot Encoding. <br> - Pembagian dataset menjadi data latih (80%) dan data uji (20%) untuk mengevaluasi performa model. |
| Arsitektur model | Deskripsi arsitektur model yang diguanakan |
| Metrik evaluasi | - Accuracy: Untuk mengukur seberapa baik model memprediksi secara keseluruhan. <br>- Precision: Untuk memastikan model tidak terlalu sering salah memprediksi pasien berisiko stroke. <br> - Recall (Sensitivity): Untuk memastikan semua pasien yang berisiko tinggi terkena stroke dapat terdeteksi dengan benar. <br> - F1-Score: Kombinasi antara precision dan recall sebagai metrik akhir evaluasi. |
| Performa model | Deksripsi performa model yang dibuat |
