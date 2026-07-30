# Summary: Berkenalan Dengan Artificial Intelligence (AI)

Dokumen ini berisi rangkuman komprehensif dari materi pada modul **Berkenalan Dengan Artificial Intelligence (AI)** yang disusun berdasarkan analisis dari setiap materi pembelajaran.

---

## [1. Penerapan AI dalam Dunia Nyata.md](file:///C:/Documents/Learning-Journal/Courses/Coding%20Camp%202026%20powered%20by%20DBS%20Foundation/DBS%20Foundation%20-%20Progressive%20Gen%20AI%20Engineer/Belajar%20Dasar%20AI/2.%20Berkenalan%20Dengan%20Artificial%20Intelligence%20%28AI%29/1.%20Penerapan%20AI%20dalam%20Dunia%20Nyata.md)

- **Pertumbuhan Adopsi Industri:** Menurut laporan McKinsey (*The state of AI in 2022*), adopsi teknologi AI di berbagai sektor industri meningkat dari 20% (2017) menjadi 50% (2022), di mana 31% di antaranya memanfaatkan AI untuk meningkatkan kualitas produk dan layanan.
- **Penerapan pada Smart Speaker:**
  - Memanfaatkan *Natural Language Processing* (NLP) untuk merespons perintah verbal.
  - **Tahapan Kerja:**
    1. *Detection Word:* Menunggu kata pemicu (contoh: "Ok, Google!") yang mengembalikan status boolean (`True`/`False`).
    2. *Speech Recognition:* Mendeteksi suara dan melakukan pemetaan dari sinyal audio menjadi teks.
    3. *Intent Understanding:* Mengolah teks dengan algoritma untuk memahami niat/maksud sebenarnya dari pengguna.
    4. *Execution:* Mengeksekusi aksi dan memberikan keluaran (seperti suara/audio pantun).
- **Penerapan pada Self-Driving Car (Tesla):**
  - Menggabungkan data dari berbagai sensor visual dan sensor *Light Detection and Ranging* (LIDAR) untuk mendeteksi objek, kendaraan lain, serta pejalan kaki.
  - Memanfaatkan algoritma *Convolutional Neural Network* (CNN) untuk pengenalan gambar/objek dan algoritma *Dijkstra* untuk perencanaan rute.
  - Mengirimkan perintah otomatis ke kemudi, akselerator, dan rem secara *real-time* guna mencegah kecelakaan.

---

## [2. Pengenalan AI.md](file:///C:/Documents/Learning-Journal/Courses/Coding%20Camp%202026%20powered%20by%20DBS%20Foundation/DBS%20Foundation%20-%20Progressive%20Gen%20AI%20Engineer/Belajar%20Dasar%20AI/2.%20Berkenalan%20Dengan%20Artificial%20Intelligence%20%28AI%29/2.%20Pengenalan%20AI.md)

- **Sejarah Singkat AI:**
  - **1950:** John McCarthy, Marvin Minsky, dan para ilmuwan di MIT mulai membuat program komputer yang meniru kemampuan manusia. Alan Turing melontarkan pertanyaan kunci: *"Jika manusia dapat menyelesaikan masalah berdasarkan informasi yang ada, mengapa mesin tidak bisa melakukan hal yang sama?"*.
  - **1956:** Konferensi *Dartmouth Summer Research Project on Artificial Intelligence* (DSRPAI) secara resmi menandai lahirnya AI sebagai disiplin ilmu yang mandiri.
- **Definisi AI:** Bidang ilmu yang fokus pada pengajaran mesin agar dapat belajar, berpikir, dan mengambil tindakan seperti manusia dalam menyelesaikan tugas-tugas kehidupan nyata.
- **Pendekatan "Cara Cerdas":** Melibatkan metode komputasi untuk mengenali pola data dan menghasilkan aturan (*rules*) secara mandiri tanpa perlu diprogram secara eksplisit (*explicit programming*), sehingga meminimalkan pekerjaan berulang dan kesalahan manusia.
- **Generatif AI & Validasi Informasi:** Penggunaan alat AI seperti ChatGPT meningkatkan efisiensi pencarian dan analisis, namun hasilnya harus senantiasa divalidasi kembali karena risiko ketidakakuratan data.

---

## [3. Taksonomi AI.md](file:///C:/Documents/Learning-Journal/Courses/Coding%20Camp%202026%20powered%20by%20DBS%20Foundation/DBS%20Foundation%20-%20Progressive%20Gen%20AI%20Engineer/Belajar%20Dasar%20AI/2.%20Berkenalan%20Dengan%20Artificial%20Intelligence%20%28AI%29/3.%20Taksonomi%20AI.md)

Taksonomi AI menggambarkan hirarki keilmuan yang saling melengkapi dari yang paling luas hingga spesifik:

1. **Artificial Intelligence (AI):** Konsep paling luas yang mencakup seluruh teknologi untuk membuat sistem komputer mampu meniru kecerdasan manusia.
2. **Machine Learning (ML):** Subset dari AI yang menggunakan metode statistik dan algoritma untuk mempelajari pola dari data (*training*) guna menghasilkan **Model** tanpa pemrograman manual.
3. **Deep Learning (DL):** Subset dari Machine Learning yang didasari oleh jaringan saraf tiruan (*Artificial Neural Networks*) dengan banyak lapisan (*hidden layers*), mampu memproses masalah komputasi yang jauh lebih kompleks.
4. **Generative AI:** Cabang dari Deep Learning yang berfokus pada kemampuan menghasilkan konten baru (teks, kode, audio, hingga gambar) berdasarkan petunjuk/deskripsi teks pengguna (contoh: DALL-E untuk membuat gambar dari deskripsi teks).

---

## [4. AI Workflow.md](file:///C:/Documents/Learning-Journal/Courses/Coding%20Camp%202026%20powered%20by%20DBS%20Foundation/DBS%20Foundation%20-%20Progressive%20Gen%20AI%20Engineer/Belajar%20Dasar%20AI/2.%20Berkenalan%20Dengan%20Artificial%20Intelligence%20%28AI%29/4.%20AI%20Workflow.md)

Tahapan umum dalam merancang dan mengimplementasikan sistem AI:

1. **Digitalise & Collect:** Pengumpulan data dari berbagai sumber (sensor, database, dokumen fisik) dan konversi menjadi format digital yang bisa diproses komputer, mencakup data terstruktur (*structured*) maupun tidak terstruktur (*unstructured*).
2. **Transform:** Pemrosesan berulang data melalui pembersihan (*cleaning*), konversi format, dan eliminasi data yang tidak relevan.
3. **Train:** Pemilihan algoritma dan pelatihan model menggunakan data yang telah siap. Mengingat prinsip *Model Selection* (Jie Ding, et al.), tidak ada satu algoritma yang berlaku secara universal, sehingga diperlukan pendekatan *trial & error*.
4. **Execute:** Pengisian dan integrasi model ke lingkungan produksi untuk mengeksekusi tugas secara otomatis serta terus melakukan evaluasi keakuratan.
5. **Provide Insights to Make Decisions:** Ekstraksi pola dan pengetahuan dari hasil prediksi model untuk membantu pengambilan keputusan bisnis dan melakukan *retraining model* secara berkala ketika ada data baru.

---

## [5. Story - Belajar Mempermudah Pekerjaan dengan AI.md](file:///C:/Documents/Learning-Journal/Courses/Coding%20Camp%202026%20powered%20by%20DBS%20Foundation/DBS%20Foundation%20-%20Progressive%20Gen%20AI%20Engineer/Belajar%20Dasar%20AI/2.%20Berkenalan%20Dengan%20Artificial%20Intelligence%20%28AI%29/5.%20Story%20-%20Belajar%20Mempermudah%20Pekerjaan%20dengan%20AI.md)

- **Studi Kasus Nyata (Kisah Kai):** Kai adalah mahasiswa yang merasa kewalahan mengurus tugas perkuliahan sekaligus mengelola toko kelontong keluarga yang memerlukan pencatatan penjualan, restock barang, dan pengelompokan produk secara rutin.
- **Solusi Berbasis AI:** Dengan bantuan temannya (Evans), Kai menyadari bahwa masalah bisnis dan operasional berulang dapat diotomatisasi dengan mempelajari taksonomi serta implementasi AI.
- **Korelasi Pembelajaran:** Cerita ini memberikan ilustrasi praktis mengapa AI dibutuhkan dalam dunia kerja dan memicu motivasi untuk memahami mekanisme internal bagaimana AI bekerja.

---

## [6. Rangkuman Berkenalan dengan Artificial Intelligence (AI).md](file:///C:/Documents/Learning-Journal/Courses/Coding%20Camp%202026%20powered%20by%20DBS%20Foundation/DBS%20Foundation%20-%20Progressive%20Gen%20AI%20Engineer/Belajar%20Dasar%20AI/2.%20Berkenalan%20Dengan%20Artificial%20Intelligence%20%28AI%29/6.%20Rangkuman%20Berkenalan%20dengan%20Artificial%20Intelligence%20%28AI%29.md)

- Merupakan rangkuman resmi modul yang merangkum keseluruhan poin-poin di atas dan menjadi jembatan menuju modul berikutnya mengenai Machine Learning dan Deep Learning lebih dalam.
