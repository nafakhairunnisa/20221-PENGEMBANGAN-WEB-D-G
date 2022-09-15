# PROPOSAL WEBSITE LET'S READ

## Permasalahan
Banyak buku terbit setiap harinya dengan genre yang berbeda-beda. Banyak orang yang ingin membaca buku mencari ulasan dari buku tersebut sebelum memulai membacanya.

## Rancangan Solusi
Membuat situs web yang menyediakan tempat untuk membuat ulasan buku.

## Use Case

![USE CASE DIAGRAM_WEBSITE RL-page0001](https://user-images.githubusercontent.com/83491188/190195555-59095cbf-cf90-4ad4-a3ea-a2ce601f8aa8.jpg)

- User bisa melakukan registrasi menggunakan alamat e-mail.
- User dan admin bisa log in.
- User dan admin dapat menambah informasi buku baru berupa judul, sampul, dan deskripsi.
- User dan admin dapat mengubah informasi buku baru berupa judul, sampul, dan deskripsi.
- User dapat menambahkan ulasan baru pada sebuah buku yang bisa dilihat oleh semua pengunjung website.
- User dapat mengubah ulasan yang diunggahnya.
- User bisa melihat ulasan yang diunggah oleh user tersebut atau user lain di website.
- User bisa menambahkan tanggapan atau komentar di ulasan yang dibuat oleh user lain.
- Admin bisa mengelola informasi buku yang diunggah.
- Admin bisa mengelola ulasan yang diunggah.

## Struktur Data

### User
Atribut|Tipe Data|Contoh
---|---|---
idUser|integer|1
namaUser|string|Budi
username|string|budii
email|string|budi@gmail.com
password|string|*****

### Buku
Atribut|Tipe Data|Contoh
---|---|---
idBuku|integer|1
namaBuku|string|Judul Buku
author|string|Pena
deskripsi|text|blublublu

### Ulasan_Buku
Atribut|Tipe Data|Contoh
---|---|---
idUlasan|integer|1
ulasan|text|blablabla
rating|integer|4
komentar|text|bliblibli

### Admin
Atribut|Tipe Data|Contoh
---|---|---
usernameAdmin|string|adminwebsite
password|string|*****

## UX Wireframe
![1663212061599](https://user-images.githubusercontent.com/83491188/190306415-bec25dcf-944c-4687-a1fd-f33cb6efeac7.jpg)
