# Analisis Skill Lowongan Pekerjaan Digital Marketing Berbasis AI & Jaringan Semantik

## 📌 Deskripsi
Repositori ini berisi kode, data, dan hasil analisis skill yang dibutuhkan dalam lowongan pekerjaan **digital marketing** di Indonesia.  
Analisis dilakukan menggunakan **AI (IBM Granite Model)** untuk klasifikasi skill (hard skills, soft skills, dan non-skills), serta **jaringan semantik** (Gephi) untuk melihat keterkaitan antar skill.

## 🎯 Pertanyaan Penelitian
1. Skill apa saja yang dibutuhkan dalam pekerjaan digital marketing di Indonesia?  
2. Dalam lowongan pekerjaan dengan gaji minimal **UMK Surabaya (Rp4.961.753)**, skill apa saja yang paling dicari perusahaan?  

## 🔎 Data
- **Sumber**: Jobstreet Indonesia  
- **Periode**: 1–30 Mei 2025 (Jobstreet hanya menyediakan data 30 hari terakhir)  
- **Filter**: Lowongan kerja digital marketing dengan gaji minimal sesuai **UMK Surabaya**  

## ⚙️ Metodologi
1. **Data Collecting**  
   - Scraping lowongan kerja Jobstreet (periode 1–30 Mei 2025).  

2. **Data Preprocessing**  
   - Klasifikasi skill menggunakan **IBM Granite Model** (hard skills, soft skills, non-skills).  
   - Normalisasi skill (contoh: “SEO” dan “Search Engine Optimization” dipetakan menjadi satu tag).  
   - Penyusunan **edge list** dan **node table** untuk analisis jaringan.  

3. **Data Analysis**  
   - Analisis frekuensi skill untuk mengetahui skill yang paling sering muncul.  
   - Analisis **jaringan semantik** (skills co-occurrence) menggunakan Gephi untuk melihat keterkaitan antar skill dan pembentukan klaster.  

## 📊 Hasil Utama
- **Hard skills** dominan: digital marketing, SEO, data analysis, content creation, Google Ads.  
- **Soft skills** dominan: communication, teamwork, leadership, dynamic & multitasking.  
- **Non-skills** dominan: bachelor's degree, pengalaman kerja, dan usia minimum.  
- **Klaster semantik** menunjukkan pola interdisipliner dengan subklaster khusus (e-commerce, CRM, Ads, IT, data analysis).  

## 🛠️ Teknologi
- Python (pandas, numpy, nltk, tqdm, openpxyl)  
- IBM Granite Model (skill classification)  
- Gephi (semantic network analysis & visualization)  
- Google Colab  
