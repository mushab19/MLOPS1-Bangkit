# Submission 1: Job Posting Prediction
Nama: Muhammad Mushab Umair

Username dicoding: mushab

| | Deskripsi |
| ----------- | ----------- |
| Dataset | [Job Posting Prediction](https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction/data) |
| Masalah | Lowongan pekerjaan palsu seringkali menjadi masalah di kehidupan masyarakat. Lowongan tersebut dibuat dengan tujuan yang tidak jelas seperti penipuan, pencucian uang, atau bahkan tindakan kriminal. Hal itu tentu sangat merugikan pencari kerja seperti mahasiswa freshgraduate. Dataset yang digunakan dalam penelitian ini terdiri dari sekitar 18 ribu data lowongan pekerjaan, dan ternyata terdapat 800 di antaranya adalah lowongan palsu. Diharapkan dengan adanya dataset ini, kita dapat membantu memprediksi keaslian lowongan pekerjaan. |
| Solusi machine learning | Dengan memanfaatkan teknologi machine learning, kita bisa memprediksi apakah suatu lowongan pekerjaan asli atau palsu. Sistem prediksi lowongan pekerjaan ini diharapkan dapat membantu masyarakat mendeteksi keaslian lowongan pekerjaan lebih awal. |
| Metode pengolahan | Metode pengolahan data yang digunakan adalah tokenisasi untuk fitur input modelnya. Data teks awal akan dibersihkan menggunakan library NLTK dan kemudian dipilih fitur-fitur yang relevan untuk model |
| Arsitektur model | Model yang dibangun menggunakan layer TextVectorization untuk mengubah input string menjadi bentuk numerik, Embedding untuk mengukur kedekatan antar kata, LSTM untuk memproses data sekuensial, Dense untuk menghubungkan neuron antar layer, dan Dropout untuk mengurangi overfitting |
| Metrik evaluasi | Untuk mengevaluasi performa model secara komprehensif, digunakan beberapa metrik, seperti binary accuracy, true positive rate, true negative rate, false positive rate, dan false negative rate. Metrik-metrik ini memberikan gambaran yang lebih lengkap tentang kemampuan model dalam membedakan antara lowongan pekerjaan asli dan palsu, serta membantu mengidentifikasi kesalahan yang mungkin terjadi dalam prediksi. |
| Performa model | Model ini menunjukkan performa yang baik dengan binary accuracy sebesar '0.98' hingga mencapai '1', val_binary_accuracy sebesar 0.98, loss sebesar  1.7274e-06 , dan val_loss sebesar  0.1859 . Dari hasil pengujian, model ini dianggap mampu memberikan prediksi yang baik. |
