---
title: Penulisan Huruf Berdiakritik dengan Software
description:
permalink: penulisan-huruf-berdiakritik-dengan-software
aliases:
  - Penulisan Transliterasi dengan WinCompose
  - Penulisan Transliterasi dengan MS Word
tags:
  - panduan
  - diakritik
  - transliterasi
  - transkripsi
socialImage:
socialDescription:
date: 2026-07-11
publish: true
---

## Penulisan Huruf Berdiakritik dengan Software

Beberapa huruf untuk keperluan transliterasi dan transkripsi memiliki penanda tambahan yang menunjukkan pengejaan khusus. Penanda tambahan ini dinamakan dengan diakritik. Beberapa huruf ini adalah

| ā   | ـَا |
| --- | --- |
| ī   | ـِي |
| ū   | ـُو |
| ḥ   | ح   |
| ʿ   | ع   |

Untuk menuliskannya di desktop akan lebih mudah dengan dua cara berikut ini:

1) WinCompose,
2) MS Word.

### Diakritik Menggunakan WinCompose

Untuk menggunakan WinCompose, pertama install WinCompose terlebih dahulu. Dapat diunduh [di sini](https://WinCompose.info/).

![](Screenshot%20(121).png)

Kedua, jika WinCompose telah terinstall ia akan otomatis muncul di *system tray* sebagaimana ditunjukkan gambar berikut:

![](Screenshot%20(114).png)

WinCompose memungkinkan pengetikan huruf-huruf berdiakritik lewat komposisi tombol keyboard. Misalnya dalam penulisan ā dapat dilakukan dengan menekan tombol: 

`alt (kanan) + a + -` 

![](Screenshot%20(115).png)

Tombol `alt (kanan)` yang menjadi *compose key* dapat diganti dengan tombol apa pun dengan mengubahnya dengan klik kanan aplikasi WinCompose yang aktif di system tray kemudian klik `options`.

![](Screenshot%20(118).png)

Setelah itu akan muncul jendela *pop-up* dan ganti dengan klik `Change` pada *compose key* dan masukkan tombol lain sebagai ganti dari Alt (kanan). 

![](Screenshot%20(119).png)

Adapun untuk menambahkan diakritik yang tidak terdapat dalam katalog aplikasi, misalnya seperti ḥ dan ʿ dapat ditambahkan melalui tombol `edit` di pojok bawah jendela aplikasi.

![](Screenshot%20(115)-1.png)

Lalu akan muncul jendela notepad, dan dari situ dapat ditambahkan formula baru sebagaimana berikut:

```
<Multi_key><.><h>: "ḥ" U+1E25
<Multi_key><.><H>: "Ḥ" U+1E25
<Multi_key><.><'>: "ʿ" U+02BF
```

yang berarti `Alt (kanan) + . + h` untuk ḥ, `Alt (kanan) + . + H` untuk Ḥ, dan `Alt (kanan) + . + '` untuk ʿ.

![](Screenshot%20(117)-1.png)

Setelah formula baru dituliskan klik `file` di kolom atas kemudian klik `save`, atau pintasannya `ctrl+s`

![](Screenshot%20(117).png)

berbeda dengan penulisan melalui jalur kedua, yaitu melalui MS Word, setiap tombol pintasan yang telah didaftarkan dalam katalog WinCompose akan dapat aktif di aplikasi desktop apa pun sejauh WinCompose aktif di balik sistem.

### Diakritik Menggunakan MS Word

Untuk menulis diakritik dengan MS Word (tanpa WinCompose), pertama buka terlebih dahulu aplikasi MS Word.

![](Screenshot%20(142).png)

Di panel ribbon pilih `insert`.

![](Screenshot%20(143).png)

kemudian pilih `symbol` dan `more symbols`.

![](Screenshot%20(143)-1.png)

Setelah katalog simbol terlihat, pilih diakritik yang akan diberi pintasan tombol. 

![](Screenshot%20(144).png)

Kemudian klik `shortcut`.

![](Screenshot%20(144)-1.png)

Masukkan kombinasi keyboard sebagai pintasannya, setelah itu klik `Assign`.

![](Screenshot%20(145).png)

Pintasan yang telah dibuat dalam MS Word hanya berlaku di dalam aplikasi MS Word itu sendiri.