---
tags:
  - web-development
  - html
  - front-end
  - study-notes
---
# Rangkuman: Pengenalan HTML
*Modul 3: Belajar Dasar Pemrograman Web (DBS Foundation Coding Camp)*

Berikut adalah ringkasan dari materi Pengenalan HTML yang telah dipelajari:

## 1. Pengantar HTML
**HTML** (HyperText Markup Language) adalah satu-satunya bahasa *markup* standar yang digunakan untuk membangun struktur dasar sebuah halaman website. Jika website diibaratkan sebagai makhluk hidup, HTML adalah **kerangkanya** yang menentukan bentuk dan tata letaknya. Tanpa HTML, konten tidak akan dikenali oleh *browser*.

## 2. Anatomi Elemen HTML
Elemen HTML digunakan untuk mendefinisikan konten-konten yang ditampilkan (misalnya teks paragraf, judul, gambar, dll). Secara anatomi, elemen HTML terdiri dari 3 bagian:
- **Tag Pembuka (`<nama-tag>`)**: Menandai awal dari sebuah elemen dan dibungkus *angle bracket* `<>`. Contoh: `<p>` untuk mendefinisikan paragraf.
- **Konten**: Isi teks atau media dari elemen tersebut.
- **Tag Penutup (`</nama-tag>`)**: Menandai batas akhir dari elemen. Selalu diawali dengan garis miring `/` (contoh: `</p>`). Jika lupa ditutup, tampilan bisa rusak!

Sebuah elemen juga dapat menjadi wadah bagi elemen lain, yang disebut sebagai **Elemen di dalam Elemen (*child-element*)**. Misalnya, teks tertentu di dalam `<p>` dibungkus lagi dengan `<i>` untuk huruf miring.

## 3. Attribute di Elemen HTML
**Atribut** memberikan **informasi/instruksi tambahan** untuk elemen HTML yang dapat mengontrol perilakunya. Atribut ini tidak tampil secara visual sebagai konten teks.
- Atribut wajib dituliskan hanya di dalam **tag pembuka**.
- Atribut memiliki 2 komponen utama: **Nama atribut** dan **Nilai atribut** (ditulis dengan format `name="value"`).
- Contoh pemakaian atribut: `class` dan `id` (untuk penanda *styling* CSS), `src` (sumber data/gambar pada `<img>`), `hidden`, dsb.

## 4. Anatomi Dokumen HTML
Dokumen HTML yang baik dan valid wajib mengikuti struktur hierarki standar yang disebut dengan **DOM Tree (Document Object Model Tree)**:
- **`<!DOCTYPE html>`**: Penanda *doctype* untuk mendeklarasikan kepada *browser* bahwa dokumen ini ditulis menggunakan standar **HTML5**.
- **`<html>`**: Elemen *root* atau induk utama tertinggi yang mewadahi seluruh struktur halaman web.
- **`<head>`**: Tempat untuk meletakkan **informasi latar belakang (metadata)**. Konten di dalamnya (seperti `<style>`, `<meta>`, `<link>`) tidak langsung ditampilkan ke layar, kecuali `<title>` yang muncul sebagai nama Tab di browser.
- **`<body>`**: Tempat seluruh **konten utama** bersarang. Apa pun yang ditulis di dalam `<body>` (misal: `<h1>`, `<p>`, `<img>`) adalah yang akan benar-benar **dilihat oleh pengguna** di layar browser.
- **Komentar (`<!-- teks komentar -->`)**: Digunakan untuk menulis catatan dokumentasi yang **tidak akan diproses maupun ditampilkan** di halaman web.

## 5. Teks Lorem Ipsum
**Lorem Ipsum** adalah teks *dummy* (pengisi sementara) yang biasa digunakan *developer/designer* agar dapat fokus pada pembuatan *layout*/desain visual terlebih dahulu sebelum konten tulisan aslinya selesai dibuat.
Teks lorem ipsum dapat di-_generate_ dengan mudah via situs generator *online* (seperti `loremipsum.io`) atau melalui *shortcut* di Ms. Word (`=lorem(paragraf,kalimat)`).
