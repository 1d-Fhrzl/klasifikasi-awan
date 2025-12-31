KLASIFIKASI JENIS AWAN MENGGUNAKAN DEEP LEARNING (CNN)

Klasifikasi jenis awan penting dalam meteorologi karena dapat menunjukkan kondisi atmosfer dan potensi cuaca ekstrem. 
Namun, identifikasi secara manual bersifat subjektif dan kurang konsisten. Oleh karena itu, penelitian ini menerapkan Convolutional Neural Network (CNN)
untuk melakukan klasifikasi awan secara otomatis berdasarkan citra digital.

Model VGG16 digunakan sebagai feature extractor karena kemampuannya dalam mengenali pola visual secara efektif, bahkan pada dataset terbatas.
Pendekatan ini terbukti mampu meningkatkan akurasi klasifikasi dibandingkan metode konvensional. Sistem yang dikembangkan diharapkan dapat membantu pemantauan
cuaca secara lebih akurat melalui evaluasi menggunakan akurasi, confusion matrix, dan classification report.

🚀 Cara Menggunakan Program

Buka Google Colab
Jalankan notebook program melalui Google Colab agar seluruh dependensi dapat dijalankan dengan lancar.

Masukkan API Key Kaggle
Unggah file kaggle.json untuk mengakses dataset yang digunakan dalam proses pelatihan dan pengujian model.

Jalankan Seluruh Sel Program
Program akan secara otomatis mengunduh dataset, memproses data, serta memuat model klasifikasi awan berbasis CNN.

Unggah Citra Awan
Masukkan gambar awan yang ingin diklasifikasikan melalui fitur upload yang tersedia.

Lihat Hasil Klasifikasi
Sistem akan menampilkan hasil prediksi jenis awan berdasarkan citra yang diunggah.
