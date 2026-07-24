# Learning Journal

Sebuah repositori personal yang didedikasikan sebagai jurnal pembelajaran (Knowledge Base). Repositori ini berisi kumpulan catatan, rangkuman materi, kuis, dan berbagai sumber daya dari berbagai program pelatihan yang sedang dipelajari.

Repositori ini dikelola menggunakan **Obsidian**, sehingga setiap catatan menggunakan format Markdown dan saling terhubung (*interlinked*) dengan *wiki-links* khas Obsidian.

## 🛠 Tools yang Digunakan

- **Obsidian**: Sebagai editor utama dan manajemen *knowledge graph*.
- **Markdown**: Format penulisan utama untuk semua catatan.
- **Git & GitHub**: Untuk version control dan backup.

## 🚀 Getting Started

Jika Anda ingin melihat atau berkontribusi dalam jurnal ini secara lokal, ikuti langkah-langkah berikut:

### 1. Clone Repository

Buka terminal Anda dan jalankan perintah berikut:

```bash
git clone https://github.com/USERNAME_ANDA/Learning-Journal.git
cd Learning-Journal
```

### 2. Buka dengan Obsidian

Untuk mendapatkan pengalaman membaca terbaik dan melihat graf relasi antar catatan:
1. Unduh dan install [Obsidian](https://obsidian.md/).
2. Buka aplikasi Obsidian.
3. Pilih opsi **"Open folder as vault"**.
4. Arahkan ke folder `Learning-Journal` yang baru saja di-*clone*.

Semua keterhubungan file (`[[nama file]]`) akan otomatis terbaca oleh Obsidian.

## 📂 Struktur Repositori

Repositori ini menggunakan sistem Zettelkasten ringan dengan gabungan "Flat Folders + Topic Dashboards". Semua kelas dikumpulkan di folder `Courses`, sedangkan navigasi topik diatur melalui folder `Dashboards`.

```text
Learning-Journal/
├── .obsidian/               # Konfigurasi workspace Obsidian
├── 📚 Courses/              # Semua materi dan kelas berkumpul di sini
│   ├── DBS Foundation - Progressive Full-Stack Developer/
│   ├── DBS Foundation - Progressive Gen AI Engineer/
│   └── Microsoft Elevate - Data Science Fabric/
│       ├── 1. Persiapan Belajar/
│       ├── 2. Mengupas Tuntas Analitik End-to-End dengan Microsoft Fabric/
│       └── 3. Menyelami Dunia Data Science dengan Microsoft Fabric/
├── 🧭 Dashboards/           # Pintu masuk (Map of Content) ke setiap topik pembelajaran
│   ├── AI.md
│   ├── Data Science.md
│   └── Web Development.md
├── .gitignore               # Konfigurasi pengabaian file Git
└── Readme.md                # Dokumentasi utama (file ini)
```

## 📚 Daftar Materi Saat Ini

Saat ini, fokus pembelajaran ada di area **Data Science**, dengan detail program:

### Belajar Penerapan Data Science dengan Microsoft Fabric
Program dari Microsoft Elevate Training Center Skill Sprint.
- **Modul 1: Persiapan Belajar** (Selesai dirangkum)
- **Modul 2: Mengupas Tuntas Analitik End-to-End dengan Microsoft Fabric** (Selesai dirangkum + Kuis)
- **Modul 3: Menyelami Dunia Data Science dengan Microsoft Fabric** (Selesai dirangkum)

Setiap modul di atas memiliki sebuah file `Summary.md` yang merangkum keseluruhan materi pada bab tersebut.

---
*Dokumentasi ini di-generate berdasarkan skill README documentation pattern.*
