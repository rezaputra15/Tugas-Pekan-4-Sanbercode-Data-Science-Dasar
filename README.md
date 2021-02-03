# Task Overview (Tugas Pekan-4 Data Science Dasar)

<h3>Tugas Pekan 4 Hari ke-1</h3>
    Pelajarilah secara garis besar suatu model/algoritma machine learning, kemudian aplikasikan untuk membuat model bagi data (variable x, y) di bawah ini. Kemudian buatlah prediksi terhadap data training dan data baru di interval 20-30.
      <ol>• Plot data asli, data hasil prediksi terhadap data training, data hasil prediksi terhadap data baru</ol>
      <ol>• Tunjukan beberapa parameter yang dimiliki model yang telah kalian buat</ol>
      
<h3>Tugas Pekan 4 Hari ke-2</h3>
      <ol>• Buatlah model KNN</ol>
      <ol>• Training model tersebut kepada data X_train dengan hyperparameter kombinasi antara 2<= k <=20 dan weights bernilai 'uniform', dan 'distance' </ol>
      <ol>• Lakukan prediksi terhadap data X_test untuk model di setiap kombinasi k dan weights</ol>
      <ol>• Score dengan accuracy dari hasil prediksi terhadap data X_test untuk setiap kombinasi hyperparameter, masukan score tersebut ke dalam objek list dengan di groupkan berdasarkan jenis weights, sehingga di akhir kita punya variable misalkan list_uniform_score, dan list_distance_score</ol>
      <ol>• Plot kedua list tersebut dengan lineplot kedalam satu axis dan bandingkan hasilnya</ol>

<h3>Tugas Pekan 4 Hari ke-3</h3>
    Kali ini kita akan menggunakan data untuk memprediksi kelangsungan hidup pasien yang telah mengalami operasi payudara. Dengan informasi yang dimiliki terkait pasien, kita akan membuat model untuk memprediksi apakah pasien akan bertahan hidup dalam waktu lebih dari 5 tahun atau tidak.
    Lebih Lengkapnya kalian bisa membaca informasi tentang dataset di link berikut: https://raw.githubusercontent.com/jbrownlee/Datasets/master/haberman.names
    Buat model Klasifikasi (Model/Algoritma Bebas) untuk memprediksi status pasien dengan ketentuan sebagai berikut:
      <ol>• Bagi kedua data ini menjadi data training dan data test dengan test_size=0.25.</ol>
      <ol>• Pelajar tentang metrics roc_auc_score kemudian buatlah model dan evaluasi dengan menggunakan teknik cross-validation dengan scoring 'roc_auc'. Baca https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.cross_val_score.html untuk menggunakan metric roc_auc saat cross-validation.</ol>
      <ol>• Berapa score rata2 dari model dengan teknik cross-validation tersebut?</ol>
      <ol>• Prediksi data test dengan model yang telah kalian buat!</ol>
      <ol>• Bagaimana hasil confusion matrix dari hasil prediksi tersebut?</ol>
      <ol>• Bagaimana classification report dari hasil prediksi tersebut?</ol>
      <ol>• Seberapa baik model anda dalam memprediksi seorang pasien mempunyai status positive?</ol>
      <ol>• Seberapa baik model anda dalam memprediksi seorang pasien mempunyai status negatif?</ol>

<h3>Tugas Pekan 4 Hari ke-4</h3>
      <ol>• Download dan gunakan data titanic.csv sebagai data untuk pembuatan model ML. Pahami betul data ini dengan melakukan EDA (Explolatory Data Analaysis), Visualisasi, Data Analysis, Preprocessing Data, dan Modeling.</ol>
      <ol>• Download dan gunakan data titanic_test.csv untuk mengetest model kalian dengan melakukan prediksi terhadap data tersebut. Submit hasil prediksinya ke kaggle dan lihat scorenya. https://www.kaggle.com/c/titanic/submit</ol>
