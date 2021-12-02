---
title: MESIN PENYEDUH MINUMAN KOPI OTOMATIS MENGGUNAKAN ARDUINO UNO
date: 2021-11-27T22:35:40.529Z
description: "Menjelakan Bagaimana Arduino Uno Sebagai Inovasi dibidang Mesin Minuman. "
tags:
  - Jurnal
---
\    Minuman kopi diminati oleh hampir semua golongan masyarakat saat ini sebagai gaya hidup seperti tempat berkumpul, tempat mengerjakan tugas atau sebagai tempat rapat rekan bisnis di kedai kopi. Di zaman modern ini, seiring dengan tingginya kesibukan masyarakat dalam dunia kerja banyak orang yang dituntut untuk melakukan tugas atau pekerjaan dengan cepat dan tepat waktu, sehingga mereka akan sangat sibuk dan kebanyakan dari mereka memanfaatkan waktu istirahat yang sebentar untuk menikmati secangkir kopi. 

\    Mesin yang dirancang pada produk inovasi ini merupakan sebuah alat yang bekerja berdasarkan push button. Kondisi push button memiliki beberapa tahapan. Tahapan tersebut meliputi ketika tombol ditekan maka servo akan bergerak untuk menuangkan gula dan kopi. Tahapan berikutnya air panas akan mengalir melalui pompa air dari pemanas air ke dalam gelas dengan menggunakan selang. Prototipe ini dapat berjalan dengan baik dengan 3 buah tegangan input 5V dan arus 2A untuk Arduino, 12V dan arus 2A, 220VAC untuk pemanas air.



![](https://i.pinimg.com/originals/11/af/dd/11afddf7dc20f72fc3edb054800c6e4b.jpg "Alur Kerja ")



\    Prinsip kerja alat ini adalah Ketika mikrokontroler Arduino mendapatkan tegangan, maka prototype akan mulai berjalan. Pertama yang dilakukan adalah melakukan inisialisasi terhadap sensor yang digunakan, yaitu sensor suhu air DS18B20 dan tombol. Pemanas air akan aktif apabila nilai suhu yang terbaca oleh DS12B20 kurang dari 800C.  Ketika tombol “Kopi Manis”di tekan maka motor Servo pada tempat serbuk gula akan aktif selama 3 detik, motor Servo pada tempat serbuk kopi akan aktif selama 3 detik, kemudian Pompa air motor DC akan memindahkan air panas dari Pemanas air ke gelas melalui selang. Ketika tombol “Kopi Sedang”di tekan maka motor Servo pada tempat serbuk gula akan aktif selama 2 detik, motor Servo pada tempat serbuk kopi akan aktif selama 3 detik, kemudian Pompa air motor DC akan memindahkan air panas dari Pemanas air ke gelas melalui selang. Gambar 2 merupakan gambaran sistem aplikasi yang dibuat.