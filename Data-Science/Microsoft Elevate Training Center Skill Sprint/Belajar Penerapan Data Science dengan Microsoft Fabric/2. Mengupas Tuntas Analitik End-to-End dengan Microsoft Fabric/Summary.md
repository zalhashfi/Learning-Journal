# Rangkuman: Mengupas Tuntas Analitik End-to-End dengan Microsoft Fabric
*Modul 2: Belajar Penerapan Data Science dengan Microsoft Fabric*

Berikut adalah ringkasan dari materi eksplorasi konsep dasar dan komponen utama pada platform Microsoft Fabric (berdasarkan file [[5. Rangkuman Mengupas Tuntas Analitik End-to-End dengan Microsoft Fabric]]).

## 1. [[1. Pengantar Mengupas Tuntas Analitik End-to-End dengan Microsoft Fabric|Konsep Dasar Microsoft Fabric]]
- **Microsoft Fabric** adalah platform analitik *end-to-end* (SaaS) yang mengintegrasikan berbagai layanan data dalam satu lingkungan terpadu. Ini memungkinkan kolaborasi efektif lintas peran di perusahaan.
- Layanan yang disediakan mencakup **data engineering**, **data integration**, **data warehousing**, **real-time intelligence**, **data science**, dan **business intelligence**.
- Dilengkapi asisten *generative AI* yaitu **Copilot** untuk meningkatkan produktivitas (*intelligent code completion*, natural language to SQL, dan *insight* otomatis).

## 2. [[2. Menjelajahi Analitik End-to-End dengan Microsoft Fabric|Fondasi Penyimpanan: OneLake]]
- **OneLake** bertindak sebagai danau tunggal (*single data lake*) terpusat yang menjadi fondasi penyimpanan Fabric.
- **Tujuan:** Mencegah terjadinya *data silo* dengan mengonsolidasikan data dari berbagai region dan *cloud* tanpa duplikasi fisik.
- **Format Penyimpanan:** Mendukung format terbuka populer seperti **Delta-Parquet** (default untuk data tabular), **CSV**, **Parquet**, dan **JSON**.
- **Fitur Shortcuts:** Memudahkan akses data yang tersimpan di *cloud* lain (seperti ADLS) tanpa harus melakukan migrasi data secara fisik.

## 3. [[4. Mengaktifkan dan Menggunakan Microsoft Fabric|Workspaces & Tata Kelola]]
- **Workspaces:** Wadah kolaborasi dan proyek di Fabric yang memudahkan pengelolaan aset data, laporan, dan *resource*.
  - Menawarkan pengaturan izin yang terpisah (*admin, contributor, member, viewer*).
  - Terintegrasi dengan Git untuk *version control*.
- **Admin Portal:** Pusat kendali untuk melakukan tata kelola, mengatur keamanan, dan memonitor penggunaan sistem. Mendukung integrasi dengan Fabric API dan SDK.
- **OneLake Catalog:** Katalog pintar yang berfungsi membantu pencarian aset data dengan mudah (bisa di-filter berdasarkan *workspace*, domain, kategori, dan jenis data). Pengguna hanya bisa melihat data yang telah dibagikan kepadanya.

## 4. [[3. Menjelajahi Peran Tim Data dan Microsoft Fabric|Transformasi Kolaborasi Tim Data]]
- Menghapus pembagian tugas (silo) antar peran data yang kaku. Semua spesialis (*Data Engineer*, *Data Analyst*, *Data Scientist*, hingga pengguna bisnis) dapat berkolaborasi dalam satu *workspace* tanpa harus terus-menerus memindahkan data.
- **Data Mesh:** Fabric mendukung arsitektur *data mesh* di mana kepemilikan data terdesentralisasi tapi dengan aturan tata kelola yang terpusat.
- **Workloads yang Tersedia:** Data Engineering, Data Factory, Data Science, Data Warehouse, Databases, Industry Solutions, Real-Time Intelligence, dan Power BI.

## 5. [[4. Mengaktifkan dan Menggunakan Microsoft Fabric|Produktivitas dengan Copilot]]
- **Data Engineering & Science:** Copilot membantu memberikan saran kode dan *intelligent code completion*.
- **Data Factory:** Membantu generasi kode untuk transformasi data.
- **Data Warehouse & Power BI:** Memungkinkan pengguna melakukan query atau membuat laporan otomatis hanya dengan menggunakan bahasa alami (Natural Language).
- *Catatan:* Copilot harus diaktifkan secara manual oleh Administrator melalui Admin Portal (*Tenant settings*).
