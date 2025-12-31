# 🧠 FINAL PROJECT KECERDASAN ARTIFISIAL LANJUT

---

## 📌 Deskripsi Proyek
Proyek ini merupakan **tugas akhir mata kuliah Artificial Neural Network** yang mengimplementasikan algoritma **Learning Vector Quantization (LVQ)**, yaitu **LVQ 1** dan **LVQ 2.1**, yang dikembangkan **secara manual tanpa menggunakan library machine learning**.

Fokus utama proyek ini adalah memahami mekanisme internal **jaringan saraf tiruan berbasis prototipe**, mulai dari pra-pemrosesan data, perhitungan jarak Euclidean, pembaruan bobot, hingga evaluasi performa model klasifikasi.

---

## 👨‍💻 Peran
**Machine Learning Engineer**

Bertanggung jawab dalam perancangan, implementasi, serta evaluasi algoritma LVQ sesuai dengan teori dan aturan yang dipelajari pada perkuliahan.

---

## ⚙️ Metode yang Digunakan
- **Learning Vector Quantization (LVQ 1)**
- **Learning Vector Quantization (LVQ 2.1)**  
  - Window Rule  
  - Learning Rate Decay  
  - Pembaruan dua prototipe terdekat  

---

## 🔄 Alur Pengerjaan
1. **Persiapan Dataset**  
   Dataset multivariat dengan fitur numerik dan label multi-kelas.

2. **Pra-Pemrosesan Data**  
   - Normalisasi **Min-Max (0–1)**  
   - Pembagian data **latih dan uji secara stratified (80:20)**  

3. **Inisialisasi Prototipe**  
   Prototipe diambil secara acak dari data latih untuk setiap kelas.

4. **Pelatihan & Tuning Parameter**  
   - Learning rate  
   - Jumlah epoch  
   - Window size (LVQ 2.1)

5. **Evaluasi Model**  
   - Akurasi  
   - Confusion Matrix  
   - Perbandingan performa LVQ 1 dan LVQ 2.1

---

## 📊 Ringkasan Hasil
- **LVQ 2.1** menghasilkan performa yang lebih stabil dibandingkan **LVQ 1**.  
- Pemilihan **learning rate** sangat berpengaruh terhadap stabilitas dan konvergensi model.  
- Proses **tuning parameter** mampu meningkatkan akurasi klasifikasi secara signifikan.

---

## 🚫 Batasan Proyek
- Tidak menggunakan library machine learning seperti *Scikit-Learn*, *TensorFlow*, atau *PyTorch*.  
- Seluruh algoritma diimplementasikan dari nol untuk memperkuat pemahaman konsep dasar.

---

## 🛠️ Teknologi yang Digunakan
- **Python**
- Library standar: `math`, `random`, `csv`
- Google Colab
