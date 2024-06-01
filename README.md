# ALAT PENGUKURAN TINGGI BADAN BERBASIS AUDIO

#### POLITEKNIK ELEKTRONIKA NEGERI SURABAYA - PROGRAM STUDI TEKNIK ELEKTRONIKA - D3 TEKNIK ELEKTRONIKA A - WORKSHOP MIKROKONTROLLER


![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/Assets/Banner/The%20Project.jpg)

Alat pengukur tinggi badan dengan output suara adalah sebuah perangkat yang menggunakan mikrokontroler ATmega2560 dan sensor ultrasonik untuk mengukur tinggi badan secara akurat, sambil memberikan umpan balik melalui suara yang telah direkam sebelumnya. Alat pengukur tinggi badan berbasis ATmega2560 ini dirancang untuk memberikan pengalaman interaktif dan ramah pengguna, terutama bagi tuna rungu. Menggunakan sensor ultrasonik untuk mengukur tinggi badan, alat ini memberikan output suara melalui modul DFPlayer Mini yang memutar pesan suara yang telah direkam sebelumnya. Buzzer dan LED digunakan sebagai indikator status dan hasil pengukuran, sementara push button memulai atau mengulangi proses pengukuran. Hasil pengukuran ditampilkan pada layar, memastikan pengguna mendapatkan informasi secara visual.

DOSEN PENGAMPU : Akhmad Hendriawan ST, MT

NIP : 197501272002121003

NO| NAMA                               | NRP          |TUGAS
--| -----------------------------------|--------------|--------------
1.| Devani Febecca Virgina Sudaryono   | 2122500002   | Studi literatur, publikasi melalui github, pembuatan audio project, pembelian komponen
2.| Syahrir Nur                        | 2122500005   | Publikasi melalui github, desain skematik dan PCB board, proses perakitan dan soldering
3.| Igna Wahyu Bahyaqi                 | 2122500007   | Pembuatan percobaan secara simulasi, proses perakitan dan soldering, pemrograman arduino 
4.| Bagus Dwi Kurniawan                | 2122500019   | Pembuatan desain 3D, desain tata letak mekanik, proses perakitan dan soldering
5.| Atilla Habil Prakoso               | 2122500028   | Pemrograman arduino, proses perakitan dan soldering, pembuatan website/database
6.| Arief Naufaldi                     | 2122500031   | Proses dokumentasi, pembuatan poster

## Daftar Isi

- [Komponen Yang Digunakan](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/README.md#komponen-yang-digunakan)
- [Blok Diagram](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/README.md#blok-diagram)
- [Konsep Simulasi](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/README.md#konsep-simulasi)
- [Skematik Rangkaian](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/README.md#skematik-rangkaian)
- [Desain 3D](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/README.md#desain-3d)
- [Audio Project](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/README.md#audio-project)
- [Dokumentasi Kegiatan](https://github.com/hillaryfraley/jobbriefings#daily-briefing)
- [Hasil Project](https://github.com/hillaryfraley/jobbriefings#daily-briefing)

## Komponen Yang Digunakan
1. Arduino ATMEGA2560
2. IC PAM8403
3. Sensor ultrasonik
4. Speaker
5. LCD
6. Push Button
7. LED 3mm
8. PCB
Dan beberapa komponen pasif seperti resistor yang salah satunya digunakan sebagai pembatas arus pada LED indikator.

## Blok Diagram

Alat pengukuran tinggi badan berbasis ATmega2560 dengan output suara adalah alat yang mengukur tinggi badan seseorang menggunakan sensor ultrasonik yang terhubung ke mikrokontroler ATmega2560. Berikut prinsip kerjanya :

1. **Sensor Pengukuran**: Sensor yang digunakan untuk mengukur tinggi badan berupa sensor ultrasonik yang mengukur jarak dari sensor ke permukaan atas kepala seseorang.

2. **Pemrosesan Mikrokontroler**: Data yang diterima dari sensor diproses oleh mikrokontroler ATmega2560. Mikrokontroler ini memiliki berbagai pin input/output yang dapat digunakan untuk berkomunikasi dengan sensor dan juga untuk mengontrol output suara.

3. **Perhitungan Tinggi Badan**: Data yang diterima dari sensor diolah oleh mikrokontroler untuk menghitung tinggi badan. Misalnya, pada sensor ultrasonik, waktu yang dibutuhkan untuk pantulan gelombang suara bisa diubah menjadi jarak.

4. **Output Suara**: Setelah tinggi badan dihitung, mikrokontroler mengirimkan instruksi ke speaker yang terhubung, untuk menghasilkan suara yang memberitahu pengguna tentang tinggi badan yang terukur. Suara ini bisa berupa angka yang diucapkan, misalnya "Tinggi badan Anda adalah 170 centimeter", atau sinyal bunyi yang memberi tahu bahwa pengukuran telah selesai. Serta akan ditampilkan melalui LCD

5. **Suara Prosedur Penggunaan**: Alat ini juga dapat menggunakan suara untuk memberikan petunjuk kepada pengguna tentang cara menggunakan alat dengan benar. Misalnya, suara tersebut dapat memberi instruksi seperti "Silakan berdiri tegak".

6. **Output Suara Berdasarkan Proses**: Selain itu, alat ini juga dapat menggunakan suara untuk memberikan umpan balik langsung kepada pengguna selama proses pengukuran. Misalnya, alat ini dapat mengucapkan "Pengukuran sedang berlangsung, mohon tunggu sebentar" atau "Pengukuran selesai, tinggi badan Anda adalah...".

## Konsep Simulasi
Berikut adalah skematik breadboard untuk simulasi menggunakan wokwi yang disimulasikan dengan arduino uno

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/Simulasi%20Wokwi/Simul%20wokwi.PNG)

Dengan hasil simulasi seperti ditunjukkan pada [youtube](https://youtu.be/tahwFHJnfhA?si=7prXb_H3Sg8DCuID)

## Skematik Rangkaian
Berikut ini adalah hasil skematik rangkaian sistem pendeteksi tinggi badan berbasis audio menggunakan software eagle
![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/PCB%20Board/Schematic/WhatsApp%20Image%202024-05-20%20at%2010.40.30.jpeg)

Untuk semua file yang dibutuhkan terkait skematik rangkaian dapat diakses melalui link [berikut](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/tree/11f3ac3c87b101c1f37d479886a7731d9a7b8a20/PCB%20Board/Schematic)

## Desain 3D
Berikut ini adalah hasil [desain 3D](https://youtu.be/tahwFHJnfhA?si=7prXb_H3Sg8DCuID)
1. Desain 3D Casing

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/9e8f5f1932d89f138b15bf86c9fd978ba1ef6fdc/Desain%203D/DESAIN/3D%20(6).PNG)
   
2. Desain 3D Casing + Komponen
   
![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/aaa9d87d6396b179dea4c512e71c5129298c3cc6/Desain%203D/DESAIN/3D%20(4).PNG)

3. Desain 3D PCB dengan komponen
   
   ![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/PCB%20Board/Desain%203D/3D%20image%201.png)
   
4. Desain 3D PCB tanpa Komponen
   
![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/PCB%20Board/Desain%203D/3D%20image%20tanpa%20komponen.png)

## Informasi Penempatan Komponen Pada PCB
Tata letak penempatan komponen pada PCB untuk memudahkan dalam proses perakitan adalah seperti gambar berikut :

## Manufaktur Desain Casing
Berikut adalah detail ukuran casing untuk kebutuhan manufaktur :

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/4a8bc46a8ae478fd297673a2b90015925bcaf7fd/Desain%203D/3D%20Print/Ukuran%20Cetak%20Akrilik.jpeg)



## Audio Project
Pada project pengukuran tinggi badan, Terdapat 5 mode [audio](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/tree/f3041c1a448ced748656aca4e69009a15c7adc17/Project%20Audio) sebagai bentuk perintah cara penggunaan alat serta tinggi badan yang terukur 
1. Audio Selamat Datang

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/Project%20Audio/Dokumentasi%20Audio/WhatsApp%20Image%202024-05-25%20at%2018.56.08.jpeg)
![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/Project%20Audio/Dokumentasi%20Audio/WhatsApp%20Image%202024-05-25%20at%2018.57.40.jpeg)

2. Audio Instruksi 1


3. Audio Instruksi 2
4. Audio Tinggi Badan
5. Audio Sampai Jumpa

(https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/4a8bc46a8ae478fd297673a2b90015925bcaf7fd/Desain%203D/3D%20Print/Ukuran%20Cetak%20Akrilik.jpeg)
