# Hacktiv8-x-IBM-Skill-Build---Data-Classification-and-Summarization

This repositories based on online learning path by Hacktive8 x IBM Skill Build in August 2025
# **Analisis Faktor Penyebab Risiko Depresi**  

---

## 📌 Project Overview  
Kesehatan mental merupakan isu penting di era modern. Tekanan pekerjaan, gaya hidup, dan pola sosial sangat memengaruhi risiko depresi.  

Proyek ini bertujuan untuk:  
- 🔍 Menganalisis data gaya hidup responden.  
- 🤖 Mengklasifikasikan tingkat risiko depresi (**High, Moderate, Low**) menggunakan **IBM Granite Model**.  
- 📝 Menggali insight unik dari hasil analisis AI yang sulit diidentifikasi secara manual.  

Dengan pendekatan ini, diperoleh **wawasan baru** yang dapat mendukung strategi pencegahan serta intervensi kesehatan mental.  

---

## 📂 Raw Dataset  
- Nama Dataset: **depression_data.csv**  
- Format: CSV
- Sumber: https://www.kaggle.com/datasets/anthonytherrien/depression-dataset

---

## ⚙️ Analysis Process  

1. **Data Loading**  
   - Dataset dimuat dari file `depression_data.csv`.  

2. **Preprocessing**  
   - Membersihkan data dari nilai kosong.  
   - Menggabungkan atribut gaya hidup menjadi teks utuh.  

3. **AI Classification & Summarization**  
   - Menggunakan **IBM Granite 3.3-8B Instruct** untuk:  
     - 📌 Klasifikasi risiko (High, Moderate, Low).  
     - 📌 Ringkasan faktor utama penyebab risiko.  

4. **Post-processing**  
   - Menambahkan kolom baru ke dataset:  
     - `depression_risk`  
     - `summary`  
   - Menyimpan hasil akhir ke `depression_data_new.csv`.  

---

## 💡 Insight & Findings  

1. **Pola Risiko**  
   - 🚨 **High Risk:** dominan pada responden dengan **kurang tidur** + **stres kerja tinggi**.  
   - ⚠️ **Moderate Risk:** sering dikaitkan dengan **konsumsi gula/kafein berlebih**.  
   - ✅ **Low Risk:** berkorelasi dengan **pola tidur cukup & olahraga rutin**.  

2. **Insight Unik**  
   - Kombinasi **stres kerja + pola tidur tidak teratur** → faktor dominan risiko tinggi.  
   - Faktor **isolasi sosial** muncul sebagai indikator tambahan yang jarang diperhatikan.  

3. **Visualisasi (opsional untuk slide)**  
   - 📊 Diagram batang: distribusi kategori risiko.  
   - ☁️ Word cloud: kata-kata dominan (misal: *kurang tidur, stres kerja, konsumsi gula*).  

---

## 📝 Conclusion & Recommendations  

**Kesimpulan:**  
- Risiko depresi sangat dipengaruhi pola tidur, stres kerja, dan pola konsumsi.  
- Kombinasi beberapa faktor memiliki efek lebih besar daripada faktor tunggal.  

**Rekomendasi:**  
- 🔴 **High Risk:** perbaiki pola tidur, kurangi jam kerja berlebih, olahraga ringan.  
- 🟠 **Moderate Risk:** kurangi konsumsi gula/kafein, jaga keseimbangan aktivitas & istirahat.  
- 🟢 **Low Risk:** pertahankan gaya hidup sehat & sebarkan pengaruh positif.  

---

## 🤖 AI Support Explanation  

IBM Granite Model mendukung analisis dengan:  
- **Classification:** mengelompokkan responden ke kategori risiko depresi.  
- **Summarization:** memberikan ringkasan singkat faktor penyebab risiko.  

⚡ Kelebihan: proses cepat, ringkas, dan mampu menemukan pola kombinasi faktor yang sulit diidentifikasi secara manual.  
