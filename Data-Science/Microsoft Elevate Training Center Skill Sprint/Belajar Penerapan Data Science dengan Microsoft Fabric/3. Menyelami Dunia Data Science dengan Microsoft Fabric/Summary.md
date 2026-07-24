# Rangkuman: Menyelami Dunia Data Science dengan Microsoft Fabric
*Modul 3: Belajar Penerapan Data Science dengan Microsoft Fabric*

Berikut adalah ringkasan dari materi pada modul 3 mengenai Data Science dengan Microsoft Fabric.

## 1. Pengantar Menyelami Dunia Data Science
Pada materi [[1. Pengantar Menyelami Dunia Data Science dengan Microsoft Fabric.md]], dibahas mengenai tujuan pembelajaran yaitu memahami alur kerja proses data science, melatih model menggunakan notebook di Microsoft Fabric, dan melacak metrik dengan MLflow dan experiments. Data science membantu mengambil keputusan berbasis data dengan mengombinasikan matematika, statistik, dan teknik komputer untuk menemukan pola.

## 2. Memahami Proses Data Science
Dalam [[2. Memahami Proses Data Science.md]], dijelaskan mengenai jenis-jenis model machine learning yang umum:
- **Classification**: Memprediksi nilai kategorikal.
- **Regression**: Memprediksi nilai numerik.
- **Clustering**: Mengelompokkan data ke dalam grup tanpa label.
- **Forecasting**: Memprediksi nilai numerik masa depan berdasarkan *time-series data*.

Alur proses data science meliputi:
1. Merumuskan masalah
2. Mengumpulkan data
3. Mempersiapkan data (menyimpannya ke dalam *Lakehouse*)
4. Melatih model (melacak setiap *experiments* menggunakan *MLflow*)
5. Menghasilkan insight (menggunakan *batch scoring*)

## 3. Mengeksplorasi dan Memproses Data
Materi [[3. Mengeksplorasi dan Memproses Data dengan Microsoft Fabric.md]] membahas cara meng-*ingest* data dari berbagai sumber (lokal maupun cloud) ke *Lakehouse*. Eksplorasi dan transformasi data dapat dilakukan melalui notebook yang didukung oleh **Spark compute** (menggunakan PySpark atau SparkR). Terdapat juga **Data Wrangler**, alat visual yang mempercepat eksplorasi, pembersihan, dan transformasi data.

## 4. Melatih dan Melakukan Scoring Model
Pada [[4. Melatih dan Melakukan Scoring Model dengan Microsoft Fabric.md]], dijelaskan pentingnya melacak setiap iterasi pelatihan model (*experiment*) menggunakan **MLflow**. Anda dapat membandingkan setiap *run* dengan melacak parameter, metrik, dan *artifacts*. Model terbaik dapat didaftarkan sebagai *registered model* di Microsoft Fabric. Untuk melakukan *scoring* (menghasilkan prediksi), Anda dapat memanfaatkan fungsi **PREDICT** yang terintegrasi dengan MLflow.

## 5. Latihan Menjelajah Data Science
Pada [[5. Latihan Menjelajah Data Science di Microsoft Fabric.md]], disediakan latihan opsional untuk mencoba langsung fitur data science di Microsoft Fabric menggunakan lisensi uji coba (*trial*).

## Kesimpulan
Keseluruhan poin-poin penting materi ini dirangkum secara resmi di [[6. Rangkuman Menyelami Dunia Data Science dengan Microsoft Fabri.md]]. Fitur unggulan Microsoft Fabric untuk data science mencakup *Lakehouse*, *Notebooks*, *Data Wrangler*, *Experiments*, dan integrasi *MLflow* yang memudahkan pekerjaan kolaboratif dari eksplorasi hingga tahap integrasi model.
