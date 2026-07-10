---
title: Panduan Penulisan dengan Software
description:
permalink: panduan-penulisan-dengan-software
aliases:
tags:
socialImage:
socialDescription:
date: 2026-07-11
draft: false
---
# Panduan Penulisan Dengan Software

Panduan ini disusun oleh tim LTN pada 6 Juli 2026. 

Terdapat dua software yang penting untuk dikuasai dalam penulisan karya ilmiah di samping *software writer*. Yaitu Zotero dan penulisan diakritik dengan Wincompose atau MS Word. Penulisan diakritik penting untuk keperluan transliterasi dan transkripsi. Sedangkan Zotero penting untuk keperluan penyitiran/pengutipan dan penyusunan daftar pustaka. Dengan adanya dua software tersebut, penulisan karya ilmiah diharapkan dapat lebih konsisten dan rapi.

## Penulisan Huruf Berdiakritik Dengan Software

Beberapa huruf untuk keperluan transliterasi dan transkripsi memiliki penanda tambahan yang menunjukkan pengejaan khusus. Penanda tambahan ini dinamakan dengan diakritik. Beberapa huruf ini adalah

| ā   | ـَا |
| --- | --- |
| ī   | ـِي |
| ū   | ـُو |
| ḥ   | ح   |
| ʿ   | ع   |

Untuk menuliskannya di desktop akan lebih mudah dengan dua cara berikut ini:

1) Wincompose,
2) MS Word.

### Diakritik Menggunakan Wincompose

Pertama untuk menggunakan wincompose harus melakukan instalasi terlebih dahulu yang dapat diunduh [di sini](https://wincompose.info/).

![](Screenshot%20(121).png)

Kedua, jika wincompose telah terinstall ia akan otomatis muncul di *system tray* sebagaimana ditunjukkan gambar berikut:

![](Screenshot%20(114).png)

Wincompose memungkinkan user untuk menuliskan huruf-huruf berdiakritik lewat komposisi tombol keyboard. Misalnya dalam penulisan ā dapat dilakukan dengan menekan tombol 

`alt (kanan) + a + -` 

![](Screenshot%20(115).png)

Tombol `alt (kanan)` dapat diganti dengan tombol apa pun lainnya dengan mengubahnya dengan klik kanan aplikasi Wincompose yang aktif di system tray kemudian klik `options`.

![](Screenshot%20(118).png)

Setelah itu akan muncul jendela *pop-up* dan ganti dengan klik `Change` pada compose key dan masukkan tombol lain sebagai ganti dari Alt (kanan). 

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

berbeda dengan penulisan melalui jalur kedua, yaitu melalui MS Word, setiap tombol pintasan yang telah didaftarkan dalam katalog Wincompose akan dapat aktif di aplikasi desktop apa pun sejauh Wincompose aktif di balik sistem.

### Diakritik Menggunakan MS Word

Untuk menulis diakritik dengan MS Word, pertama buka terlebih dahulu aplikasi MS Word.

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

## Panduan Penyitiran Dengan Zotero

Pertama, unduh aplikasi Zotero melalui link [Zotero \| Your personal research assistant](https://www.zotero.org/download/) kemudian install di desktop.

![](Screenshot%20(120).png)

Sebagai pelengkap dan alat memudahkan memindah referensi dari peramban yang digunakan (chrome, firefox, safari) dapat diinstall juga Zotero connector.

### Interface Zotero

Zotero terdiri dari tiga panel utama:

![](Screenshot%20(122).png)

Panel kiri: berisi struktur koleksi referensi. Setiap folder menunjukkan pengelompokan referensi tersebut. Di bagian bawahnya terdapat tag (penanda) untuk memudahkan proses pencarian berdasarkan tag tersebut.

Panel tengah: berisi daftar referensi yang terdaftar di katalog Zotero tersebut. Daftar referensi yang ditampilkan di panel tengah merujuk pada struktur koleksi yang aktif di panel kiri.

Panel kanan: berisi detail informasi yang merupakan data bibliografi dari referensi yang aktif di panel tengah. 

### Menambahkan Referensi

Untuk menambahkan referensi di Zotero, dapat menempuh 4 langkah berikut:

#### 1. Menambahkan Referensi Secara Manual

Klik tombol yang menunjukkan penambahan yang terletak di atas panel tengah, kemudian pilih opsi yang sesuai (apakah itu buku, artikel jurnal, laman web, dst.)

![](Screenshot%20(123).png)

Kemudian tambahkan informasi di kolom-kolom yang tersedia di panel kanan.

![](Screenshot%20(124).png)

Tekan tombol `enter` dan referensi yang baru saja ditambahkan akan muncul di panel tengah.

#### 2. Menambahkan Referensi Dari Internet

Pertama, buka peramban di desktop lalu tulis alamat di search engine yang hendak ditambahkan sebagai referensi. Dalam contoh berikut ini adalah situs google books dengan judul "colonial capitalism".

![](Screenshot%20(160).png)

Kemudian klik `Create citation` dalam kolom informasi buku tersebut dan pilih format BibTeX.

![Screenshot (160) 1.jpeg](Screenshot%20(160)%201.jpeg)

![](Screenshot%20(162).png)

jika Zotero connector terpasang di peramban, maka segera muncul *pop-up* secara otomatis di pojok kanan atas peramban. 

![](Screenshot%20(164).png)

Setelah *pop-up* tersebut muncul, dapat diubah tempat penyimpanannya di folder lain, juga dapat ditambahkan catatan tertentu yang nanti akan tertaut dengan referensi tersebut.

![](Screenshot%20(165).png)

Referensi akan otomatis ditambahkan pada aplikasi Zotero.

![](Screenshot%20(166).png)

Alternatif lainnya, dapat juga disimpan file BibTeX atau format lain dari internet tadi. Kemudian impor secara manual dengan membuka Zotero kemudian pilih tab `berkas` di atas. Setelah itu pilih `impor`, dan klik `lanjut`

![](Screenshot%20(153).png)

![](Screenshot%20(154).png)

Akan muncul *pop-up* explorer kemudian arahkan ke file yang akan ditambahkan. Tekan tombol `open`.

![](Screenshot%20(155).png)

Setelah itu tekan tombol `lanjut` maka referensi baru tadi akan ditambahkan.

![](Screenshot%20(156).png)

#### 3. Menambahkan Referensi Dari File PDF

Buka file explorer, kemudian seret file yang hendak dijadikan referensi ke aplikasi Zotero.

![](Screenshot%20(168).png)

Zotero akan secara otomatis mencari metadata dari file tersebut dan secara otomatis pula mengisi detail informasi yang ada di panel kanan.

![](Screenshot%20(170).png)

Jika ternyata Zotero tidak secara otomatis mencarikan informasi detailnya, maka dapat ditekan klik kanan pada file pdf yang baru saja ditambahkan kemudian klik `retrieve metadata`.

![](Screenshot%20(169).png)

#### 4. Menambahkan Referensi Melalui Identifier

Menambahkan referensi melalui *identifier* dapat dilakukan dengan memasukkan identitas ISBN, DOI, atau PMID dari referensi.

Klik tombol sulap di atas panel tengah segera akan muncul pop-up, kemudian masukkan identitas buku yang akan ditambahkan ke Zotero.

![](Screenshot%20(158).png)

Referensi baru akan segera masuk dalam daftar referensi dan detail referensi akan secara otomatis ditambahkan oleh Zotero.

![](Screenshot%20(159).png)

### Mengelola Referensi

Zotero ibaratnya adalah perpustakaan digital di dalam desktop. Setiap informasi dari referensi yang ditambahkan tersedia di dalam aplikasi Zotero. Zotero juga menyediakan fasilitas untuk mengatur pengelompokan referensi-referensi sesuai kategori yang dibutuhkan.

Pengelompokan ini dapat dilakukan dengan langkah berikut.

#### Membuat Koleksi Baru

Klik tombol yang menunjukkan penambahan koleksi baru yang terletak di atas panel kiri.

![](Screenshot%20(125).png)

kemudian pada *pop-up* yang baru saja muncul, masukkan nama sesuai dengan kategori yang dibutuhkan. Klik `Create Collection` maka pada panel kiri akan ditambahkan folder baru sesuai dengan penamaan yang telah dibuat.

![](Screenshot%20(126).png)

![](Screenshot%20(127).png)

Pindahkan artikel pada koleksi umum dengan memilihnya kemudian menyeretnya ke folder baru yang sudah dibuat di panel kiri.

#### Mencari Referensi

Pencarian referensi dapat dilakukan dengan memasukkan kata kunci ke kolom pencarian di atas panel tengah

![](Screenshot%20(129).png)

Panel tengah akan menampilkan daftar referensi sesuai dengan kata kunci yang dimasukkan

### Membuat Sitiran Dan Daftar Pustaka

Begitu aplikasi Zotero telah terinstall di desktop, ia akan secara otomatis menginstall *word processor* yang terintegrasi dengan MS Word dan LibreOffice.

Dalam hal ini contohnya adalah LIbreOffice

#### Menambahkan Sitiran Ke LibreOffice

Buka aplikasi LibreOffice 

![](Screenshot%20(139).png)

kemudian tekan tombol `add/edit citation` pada toolbar atas LibreOffice. 

![](Screenshot%20(131)-1.png)

Langkah kemudian tentukan terlebih dahulu *citation style* yang akan digunakan dalam naskah (misal Chicago Style 17 notes-bibliography) lalu klik `OK`. Langkah ini hanya dilakukan cukup satu kali saja.

![](Screenshot%20(133).png)

Setelah itu muncul kotak dialog dari Zotero, kemudian klik referensi yang akan digunakan. 

![](Screenshot%20(135).png)

![](Screenshot%20(136).png)

Dari situ dapat ditambahkan pula halaman dengan memasukkan angka secara langsung, kemudian tekan tombol `enter`.

![](Screenshot%20(137).png)

Jika hendak menambahkan lebih dari satu referensi, cari kembali dalam kotak dialog yang sama referensi tambahannya dan masukkan pula halamannya. Kemudian tekan tombol `enter`.

Sitasi akan secara otomatis ditambahkan.

#### Mengubah Citation Style

Zotero memampukan juga untuk perubahan gaya penyitiran di LibreOffice. Itu dapat dilakukan dengan klik `document preferences`di toolbar atas.

![](Screenshot%20(140).png)

Pada kotak dialog yang muncul tentukan citation style yang baru kemudian klik `OK`.

![](Screenshot%20(141).png)

#### Menambahkan Daftar Pustaka

klik `insert bibliography` pada toolbar.

![](Screenshot%20(138).png)

daftar pustaka dari semua referensi yang telah disitir di dokumen akan langsung dibuat secara otomatis.

![](Screenshot%20(139)-1.png)

## Penutup

Panduan dengan software ini ditujukan untuk memudahkan setiap penulis dan kontributor dalam penulisan karya ilmiah. Semoga panduan bergambar ini dapat bermanfaat. 
