# 🌧️ Klasifikasi Curah Hujan Harian Menggunakan Metode Random Forest

![GitHub repo](https://img.shields.io/badge/Machine%20Learning-Random%20Forest-blue)
![GitHub repo](https://img.shields.io/badge/Python-Data%20Science-green)

## 📌 Deskripsi Proyek

Proyek ini bertujuan untuk mengklasifikasikan curah hujan harian berdasarkan berbagai parameter cuaca menggunakan metode **Random Forest**. Dataset yang digunakan merupakan data cuaca harian hasil pengamatan **Stasiun Meteorologi Kelas III
Sultan Muhammad Salahuddin - Bima** periode Januari 2019 - Januari 2025 dan telah melalui tahap preprocessing, eksplorasi data, serta berbagai skema pemodelan untuk meningkatkan akurasi klasifikasi.

## 📊 Dataset

Dataset berisi **2.223 sampel** dengan **10 fitur cuaca**, termasuk temperatur, kelembapan, curah hujan, penyinaran matahari, serta kecepatan dan arah angin. Data ini telah diolah untuk menangani **missing values** dan **anomali** sebelum digunakan dalam pemodelan.

## 🔍 Metodologi

1. **Preprocessing Data**: Penanganan *missing values*, dan *outlier*.
2. **Eksplorasi Data**: Analisis statistik, visualisasi distribusi data, dan korelasi antar fitur.
3. **Klasifikasi Menggunakan Random Forest**:
   - **Skema 1:** Klasifikasi langsung tanpa resampling.
   - **Skema 2:** Klasifikasi dengan **SMOTE** untuk menangani ketidakseimbangan data.
   - **Skema 3:** Klasifikasi dengan fitur terpilih untuk optimasi performa.
4. **Evaluasi Model**: Menggunakan **Classification Report**, **Confusion Matrix**, dan **Macro F1-Score** sebagai metrik utama.

## 🚀 Hasil & Temuan

| Percobaan                 | Macro F1-Score |
|---------------------------|---------------|
| Klasifikasi Langsung      | 0.8664        |
| SMOTE (Resampling)        | 1.0000        |
| Seleksi Fitur             | 1.0000        |

Dari hasil penelitian, penggunaan **SMOTE** dan **seleksi fitur** secara signifikan meningkatkan performa model, mengatasi ketidakseimbangan data, serta mempertahankan akurasi yang tinggi.

## 📂 Struktur Repository

```
📂 Klasifikasi-Curah-Hujan-RF
│── 📄 README.md  # Dokumentasi proyek
│── 📄 data-cuaca-harian.xlsx  # Dataset yang digunakan
│── 📄 Klasifikasi Curah Hujan Harian Random Forest.ipynb  
```

## 🔧 Cara Menjalankan Proyek

1. **Clone Repository**
   ```bash
   git clone https://github.com/username/Klasifikasi-Curah-Hujan-RF.git
   cd Klasifikasi-Curah-Hujan-RF
   ```
2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```
3. **Jalankan Notebook di Google Colab atau Jupyter Notebook**

## 📢 Kontribusi

Kami terbuka untuk kontribusi! Jika Anda ingin meningkatkan proyek ini, silakan buat **pull request** atau laporkan masalah di **issues**.

## 📜 Lisensi

Proyek ini dilisensikan di bawah **MIT License** – bebas digunakan dan dimodifikasi.

---

🌟 *Jika proyek ini bermanfaat, jangan lupa beri ⭐ di repository ini!*

