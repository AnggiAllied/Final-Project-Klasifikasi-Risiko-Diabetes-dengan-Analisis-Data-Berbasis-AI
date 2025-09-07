> Final Project – Klasifikasi Risiko Diabetes dengan Analisis Data Berbasis AI
> Project Overview
Proyek ini bertujuan untuk memprediksi risiko diabetes berdasarkan data kesehatan pasien dengan memanfaatkan AI (IBM Granite via Replicate dan IBM Watson ML API).
Analisis dilakukan mulai dari eksplorasi data (EDA), pembersihan data, pemodelan machine learning (Logistic Regression & Random Forest), hingga evaluasi performa model.
Hasil dari proyek ini diharapkan dapat memberikan insight yang bermanfaat serta rekomendasi untuk pencegahan dan deteksi dini diabetes.

> Raw Dataset Link

> https://www.kaggle.com/datasets/rabieelkharoua/diabetes-health-dataset-analysis

> Insights & Findings
  - Distribusi Data: Dataset berisi sejumlah pasien dengan berbagai indikator kesehatan seperti Glucose, BMI, Age, BloodPressure, HbA1c, Cholesterol, dll. Target variabel Outcome menunjukkan apakah pasien mengidap diabetes (1) atau tidak (0).
  - Data Cleaning: Missing values pada fitur numerik diisi dengan nilai rata-rata agar dataset tetap lengkap.
  - Modeling:
    - Logistic Regression dijadikan baseline.
    - Random Forest digunakan sebagai model utama karena lebih mampu menangani data non-linear dan interaksi antar fitur.
  - Evaluasi Model:
    - Logistic Regression hanya mencapai akurasi sekitar 70%.
    - Random Forest mencapai akurasi sekitar 90% dan lebih baik dalam mendeteksi pasien diabetes.
  - Feature Importance: Fitur yang paling berpengaruh dalam prediksi diabetes adalah Glucose, HbA1c, BMI, dan Age.
    
> Kesimpulan: Random Forest terbukti lebih unggul dan dapat dijadikan model rekomendasi untuk mendukung screening risiko diabetes.
> Rekomendasi:
- Lakukan pemeriksaan rutin terhadap kadar gula darah (Glucose, HbA1c) dan BMI.
- Terapkan model ini sebagai alat bantu diagnosis awal untuk mendukung tenaga medis.
- Edukasi gaya hidup sehat (diet & olahraga) penting untuk pencegahan diabetes.
  
> AI Support Explanation
  Proyek ini memanfaatkan dukungan AI untuk mempercepat analisis:
  - IBM Granite via Replicate digunakan untuk menerjemahkan instruksi bahasa alami (bahasa Inggris) menjadi kode Python yang langsung dijalankan pada dataset. Dengan ini, eksplorasi data, pemodelan, dan evaluasi dapat dilakukan lebih cepat tanpa perlu menulis kode manual sepenuhnya.
  - IBM Watson Machine Learning API digunakan untuk menghubungkan, mengelola, dan mendukung model machine learning sehingga analisis lebih mudah direplikasi dan dikembangkan lebih lanjut.
  Dengan adanya AI support ini, workflow analisis menjadi lebih cepat, efisien, dan konsisten.
