---
tags:
  - web-development
  - html-css
  - front-end
  - study-notes
---
# Rangkuman: Pendahuluan Web Programming
*Modul 2: Belajar Dasar Pemrograman Web (DBS Foundation Coding Camp)*

Modul ini membahas tentang fondasi dasar bagaimana internet dan website bekerja secara teknis di balik layar. Berikut adalah intisari dari setiap materinya:

## 1. Konsep Dasar Internet
Menurut [[1. Pengantar Web Programming.md]] dan [[2. Cara Internet Bekerja.md]], internet adalah singkatan dari **Inter**connection **Net**work, yaitu jaringan berskala global yang menghubungkan komputer di seluruh dunia.
- Komputer lokal dapat saling terhubung melalui alat bernama **Network Switch**.
- Agar jaringan lokal tersebut bisa terhubung dengan dunia luar dan lintas benua, kita menggunakan jasa **Internet Service Provider (ISP)** yang mengelola *router-router* khusus.

## 2. Halaman Web vs Website
Pada [[3. Website dan Halaman Web.md]] dibahas perbedaan mendasarnya:
- **Halaman Web (Web Page)**: Sebuah halaman tunggal yang menampilkan informasi teks, gambar, atau media lain.
- **Website**: Sekumpulan halaman web yang saling terhubung menggunakan tautan (*hyperlink*) dalam sebuah domain. 
*Fakta unik: Website pertama di dunia diciptakan oleh Tim Berners-Lee di CERN pada 1989 (info.cern.ch).*

## 3. Web Server & DNS
Dijelaskan secara detail dalam [[4. Web Server.md]], setiap kali kita membuka suatu web, selalu terjadi siklus **Request & Response**:
- **Browser (Client)** bertugas mengirim *Request* (permintaan data).
- **Web Server (Koki/Pelayan)** bertugas memproses dan mengirimkan *Response* (HTML, CSS, JS).
- Server bisa merujuk pada *Hardware* (komputer dengan spesifikasi tinggi penyimpan data) maupun *Software* (program yang merespons protokol HTTP).
- **DNS Server**: Bertugas sebagai penerjemah nama domain (contoh: `dicoding.com`) menjadi **IP Address** yang dipahami komputer.

## 4. Web Browser
Pada [[5. Web Browser.md]], ditekankan bahwa *browser* (seperti Google Chrome atau Firefox) adalah gerbang utama menuju website. Browser melakukan *request* HTTP menggunakan alamat **URL** yang terdiri dari tiga bagian utama: *Protocol* (https), *Domain Name*, dan *File Path*.

## 5. Anatomi Website (Fondasi Utama)
[[6. Anatomi Website.md]] memberikan analogi yang sangat mudah dipahami terkait 3 komponen utama pembangun web:
1. **HTML**: Ibarat **kerangka/tulang** yang membentuk struktur dasar tubuh web.
2. **CSS**: Ibarat **kulit/bulu** yang memberikan warna, gaya, dan mempercantik tampilan *website*.
3. **JavaScript**: Ibarat **otot/saraf** yang memberikan *interaktivitas* dan dinamisasi (membuat *website* bisa bergerak, diklik, dan merespons interaksi).

---
## Review Video
Sesuai materi [[7. Rangkuman Pendahuluan.md]], berikut adalah video rangkuman singkat dari materi ini yang disematkan menggunakan iFrame:

<iframe width="560" height="315" src="https://www.youtube.com/embed/fZGHHnVXRms?si=RAR2fStZvJD336ed&amp;start=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
