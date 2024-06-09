# Klasifikasi Gambar Hewan dengan Model CNN dan ResNet152V2

## Deskripsi
Proyek ini bertujuan untuk mengklasifikasikan gambar-gambar hewan menggunakan model CNN dengan arsitektur ResNet152V2 di Kaggle, dan mengevaluasinya dengan beberapa gambar.

## Keterangan
- Kode ditulis menggunakan Python di platform Kaggle.
- Menggunakan TensorFlow dan Keras Library, serta library lainnya untuk mendukung proses komputasi.
- Dataset diambil dari [https://www.kaggle.com/datasets/alessiocorrado99/animals10](https://www.kaggle.com/datasets/alessiocorrado99/animals10).
- Dataset terdiri dari 28.000 gambar dengan kualitas gambar medium, yang terbagi menjadi 10 kelas: anjing (dog), kucing (cat), kuda (horse), laba-laba (spider), kupu-kupu (butterfly), ayam (chicken), domba (sheep), sapi (cow), tupai (squirrel), gajah (elephant).
- Menggunakan teknik split folder untuk pembagian dataset.
- Dataset dibagi menjadi dua bagian: data pelatihan (80%) dan data validasi (20%).
- Mengimplementasikan Image Data Generator.
- Menerapkan Data Augmentation.
- Tingkat akurasi di atas 90%.
- Tingkat evaluasi metrik di atas 90%.
- Model yang dibuat mampu memprediksi gambar dan telah diuji menggunakan gambar kupu-kupu dan kucing.

## Langkah-langkah Eksekusi Proyek
1. Unduh dataset dari [tautan ini](https://www.kaggle.com/datasets/alessiocorrado99/animals10).
2. Lakukan pembagian dataset menggunakan teknik split folder.
3. Implementasikan Image Data Generator dan Data Augmentation.
4. Bangun model CNN dengan arsitektur layer ResNet152V2.
5. Latih model menggunakan data pelatihan.
6. Evaluasi model menggunakan data validasi.
7. Uji model dengan menggunakan gambar kupu-kupu dan kucing.

## Cara Penggunaan
1. Pastikan telah mengunduh dan menyiapkan dataset.
2. Jalankan kode di lingkungan Python, preferensi di platform Kaggle.
3. Ikuti langkah-langkah eksekusi proyek seperti yang dijelaskan di atas.
4. Setelah model terlatih, Anda dapat mengujinya dengan menyertakan gambar-gambar baru.

## Catatan
Pastikan untuk menyesuaikan parameter-parameter seperti ukuran batch, jumlah epochs, dan lain-lain sesuai dengan kebutuhan proyek yang diinginkan.
#
