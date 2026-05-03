# 🎓 KNN College Major Recommendation

Proyek ini merupakan implementasi sederhana **Machine Learning menggunakan algoritma K-Nearest Neighbors (KNN)** untuk memberikan rekomendasi jurusan kuliah berdasarkan nilai akademik dan minat siswa.

---

## 📌 Deskripsi

Banyak siswa mengalami kesulitan dalam menentukan jurusan kuliah yang sesuai dengan kemampuan dan minat mereka.
Proyek ini bertujuan untuk memberikan rekomendasi jurusan dengan cara membandingkan data siswa baru dengan data siswa sebelumnya menggunakan metode KNN.

---

## 🧠 Algoritma yang Digunakan

Algoritma utama yang digunakan adalah:

* **K-Nearest Neighbors (KNN)**
  KNN bekerja dengan mencari *K tetangga terdekat* dari suatu data berdasarkan jarak (similarity), kemudian menentukan hasil berdasarkan mayoritas label.

---

## 📊 Fitur Dataset

Dataset yang digunakan bersifat sederhana (dummy data) dengan fitur:

* Nilai Matematika
* Nilai IPA
* Nilai Bahasa Inggris
* Minat Teknologi (skala 1–10)
* Minat Sosial (skala 1–10)

### 🎯 Target:

* Jurusan Kuliah:

  * Teknik Informatika
  * Kedokteran
  * Manajemen
  * Hukum

---

## ⚙️ Teknologi yang Digunakan

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## 🚀 Cara Menjalankan

1. Clone repository ini:

```bash
git clone https://github.com/username/repo-name.git
```

2. Install dependencies:

```bash
pip install pandas numpy matplotlib scikit-learn
```

3. Jalankan file notebook:

```bash
jupyter notebook
```

---

## 📈 Evaluasi Model

Model dievaluasi menggunakan **accuracy score** dengan pembagian data:

* Training: 80%
* Testing: 20%

Contoh hasil:

```
Akurasi model: 50%
```

📌 Catatan:
Akurasi masih dapat ditingkatkan dengan menambah jumlah data dan melakukan preprocessing seperti normalisasi.

---

## 🔮 Contoh Prediksi

Model dapat digunakan untuk memprediksi jurusan berdasarkan data siswa baru, misalnya:

```python
[85, 80, 82, 8, 4]
```

➡️ Output: *Teknik Informatika* (contoh)

---

## 📌 Insight

* KNN sangat bergantung pada jumlah dan kualitas data
* Dataset kecil dapat menyebabkan akurasi tidak stabil
* Pemilihan nilai K mempengaruhi hasil prediksi

---

## ⚠️ Keterbatasan

* Dataset masih kecil dan sederhana
* Belum menggunakan data real-world
* Belum dilakukan optimasi model secara mendalam

---

## 🔧 Pengembangan Selanjutnya

* Menambahkan dataset yang lebih besar
* Menerapkan normalisasi data
* Mencoba nilai K yang berbeda
* Menggunakan algoritma lain sebagai perbandingan

---

## 👤 Author

Dibuat oleh: **A. Hanif Nursyabana**

---

## ⭐ Penutup

Proyek ini dibuat sebagai bagian dari pembelajaran dasar Machine Learning, khususnya dalam memahami cara kerja algoritma KNN dalam kasus klasifikasi sederhana.

---
