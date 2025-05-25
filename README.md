# Computer Vision Project Progress Report (50%)

## Project Name
**Pendeteksi Penyakit Daun Mangga**

## Student Name
**Brilian Purnama Putra**

## Course/Institution
**Computer Vision / Politeknik Caltex Riau**

---

## 📌 Latar Belakang
Di Indonesia, terdapat beragam jenis pohon yang tumbuh dengan ukuran yang bervariasi, salah satunya adalah pohon mangga (*Mangifera indica*). Meskipun mangga adalah tanaman tropis, saat ini telah banyak dibudidayakan di berbagai negara, termasuk Indonesia. Namun, berdasarkan data Badan Pusat Statistik (BPS), terjadi penurunan produksi mangga pada tahun 2023. Salah satu faktor penyebabnya adalah penyakit yang menyerang daun tanaman mangga.

Penyakit pada daun dapat disebabkan oleh berbagai faktor seperti serangga, suhu, bakteri, jamur, dan virus. Gejalanya berupa munculnya bercak pada daun, bunga, buah, dan batang, yang dapat menurunkan kualitas serta kuantitas produksi mangga. Oleh karena itu, diperlukan sistem identifikasi dini penyakit daun mangga secara otomatis dan akurat.

Proyek ini mengusulkan pengembangan sistem klasifikasi penyakit daun mangga berbasis citra menggunakan metode **Convolutional Neural Network (CNN)**. Sistem ini akan diintegrasikan ke dalam aplikasi web yang dapat digunakan untuk mendeteksi dan mengklasifikasikan jenis penyakit berdasarkan gambar daun mangga.

---

## 🔍 Peran Computer Vision dalam Proyek Ini
Ilmu **Computer Vision** diterapkan secara menyeluruh dalam proyek ini, mulai dari proses awal hingga prediksi akhir. Berikut adalah bagian-bagian yang melibatkan konsep CV:

- **Akuisisi Citra**: Gambar daun mangga diperoleh dari dataset dan dijadikan input utama. Ini merupakan langkah awal dalam pipeline CV.
- **Preprocessing Citra**: Melibatkan resizing, normalisasi piksel, augmentasi gambar, dan konversi warna untuk mempersiapkan citra agar dapat diproses dengan baik oleh model CNN.
- **Ekstraksi Fitur Visual**: CNN digunakan untuk mengekstrak fitur penting dari gambar, seperti tekstur, warna, dan bentuk bercak pada daun yang menjadi indikator penyakit.
- **Klasifikasi Citra**: Berdasarkan fitur yang diekstrak, model mengklasifikasikan citra daun ke dalam kategori tertentu (sehat atau terkena penyakit).
- **Visualisasi Hasil Deteksi**: Hasil akhir dapat divisualisasikan untuk ditampilkan pada antarmuka web dalam bentuk label klasifikasi.

Dengan kata lain, proyek ini tidak hanya menggunakan CNN sebagai algoritma, tetapi juga mencakup seluruh proses alur kerja computer vision: **dari input citra mentah, pemrosesan, hingga pengambilan keputusan berdasarkan citra.**

---

## 🎯 Tujuan
- Menguji kinerja model CNN dalam mengklasifikasikan citra daun mangga yang terinfeksi penyakit dan membandingkannya dengan daun sehat.
- Mengidentifikasi faktor-faktor yang mempengaruhi akurasi sistem dalam mendeteksi penyakit tanaman mangga.
- Mengintegrasikan model CNN ke dalam platform berbasis web.

---

## ✅ Manfaat
- Membantu petani dalam mendeteksi penyakit tanaman mangga secara cepat dan tepat.
- Meningkatkan produktivitas dan kualitas hasil panen.
- Menjadi referensi untuk pengembangan model CNN lainnya dalam klasifikasi penyakit tanaman.

---

## 🔒 Batasan Masalah
- Model klasifikasi yang digunakan hanya menggunakan metode CNN.
- Dataset yang digunakan terbatas dari sumber yang tersedia di Kaggle.
- Sistem hanya mendeteksi penyakit berdasarkan citra daun yang diunggah ke website.

---

## 📁 Dataset
- Dataset: Mango Leaf Disease Dataset  
- Sumber: [Kaggle - Mango Leaf Disease Dataset](https://www.kaggle.com/datasets/aryashah2k/mango-leaf-disease-dataset)

---

## 🛠️ Tools & Teknologi
- **Bahasa Pemrograman:** Python  
- **Deep Learning Framework:** TensorFlow / Keras  
- **Metode:** CNN (Convolutional Neural Network)  
- **Teknik CV:** Image preprocessing, feature extraction, visual classification  
- **Dataset:** Kaggle  
- **Platform:** Web-based system

---

## 🚀 Target Sistem
- Klasifikasi gambar daun menjadi beberapa kategori: daun sehat atau terinfeksi penyakit tertentu.
- Output berupa jenis penyakit yang dideteksi.
- Antarmuka web sederhana yang memungkinkan pengguna mengunggah gambar dan melihat hasil klasifikasi.

---

## 📈 Progress Saat Ini
- Progres Proyek: **50%**
- Model CNN telah mulai dikembangkan dan diuji dengan dataset awal dari Kaggle.
- Proses preprocessing dan augmentasi gambar sedang dilakukan.
