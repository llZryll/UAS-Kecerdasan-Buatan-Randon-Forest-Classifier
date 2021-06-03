# UAS-Kecerdasan-Buatan-Randon-Forest-Classifier
Repository ini saya maksudkan untuk kebutuhan UAS saya

# Random-Forest-Classifier

NAMA : FAZRI NUR ALIM
NIM : 181011400639
KELAS 06TPLE023

Random-Forest-Classifier yang sangat sederhana diimplementasikan dengan python. library sklearn.ensemble digunakan untuk mengimpor kelas RandomForestClassifier. Objek class telah dibuat. Argumen berikut ini awalnya diteruskan ke objek:

- n_estimators = 10
- criterion = 'entropy'

Model awal hanya diberikan 10 pohon keputusan, yang menghasilkan total 10 prediksi yang salah. Setelah model dilengkapi dengan lebih banyak pohon keputusan, jumlah prediksi yang salah semakin berkurang.

Ditemukan bahwa jumlah pohon keputusan yang optimal untuk model ini untuk memprediksi jawaban adalah 200 pohon keputusan. Oleh karena itu argumen n_estimator diberi nilai akhir 200.

Lebih dari 200 akan menghasilkan over-fitting dan akan menyebabkan prediksi yang salah lebih lanjut.
