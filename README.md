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
- [Konsep Simulasi](https://github.com/hillaryfraley/jobbriefings#scope)
- [Skematik Rangkaian](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/README.md#skematik-rangkaian)
- [Desain 3D]()
- [Audio Project](https://github.com/hillaryfraley/jobbriefings#daily-briefing)
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

## Konsep Simulasi
Berikut adalah skematik breadboard untuk simulasi menggunakan wokwi yang disimulasikan dengan arduino uno

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/Simulasi%20Wokwi/Simul%20wokwi.PNG)

Dengan hasil simulasi seperti ditunjukkan pada [youtube]: https://youtu.be/tahwFHJnfhA?si=7prXb_H3Sg8DCuID

## Skematik Rangkaian
Berikut ini adalah hasil skematik rangkaian sistem pendeteksi tinggi badan berbasis audio menggunakan software eagle
![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/PCB%20Board/Schematic/WhatsApp%20Image%202024-05-20%20at%2010.40.30.jpeg)

## Desain 3D
Berikut ini adalah hasil desain 3D
1. Desain 3D Casing

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/9e8f5f1932d89f138b15bf86c9fd978ba1ef6fdc/Desain%203D/DESAIN/3D%20(6).PNG)
   
2. Desain 3D Casing + Komponen
   
![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/aaa9d87d6396b179dea4c512e71c5129298c3cc6/Desain%203D/DESAIN/3D%20(4).PNG)

3. Desain 3D PCB dengan komponen
   
   ![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/PCB%20Board/Desain%203D/3D%20image%201.png)
   
4. Desain 3D PCB tanpa Komponen
   
![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/PCB%20Board/Desain%203D/3D%20image%20tanpa%20komponen.png)

## Audio Project
Terdapat 5 mode audio sebagai bentuk perintah cara penggunaan alat pengukur tinggi badan
1. Audio Selamat Datang

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/Project%20Audio/Dokumentasi%20Audio/WhatsApp%20Image%202024-05-25%20at%2018.56.08.jpeg)
![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/Project%20Audio/Dokumentasi%20Audio/WhatsApp%20Image%202024-05-25%20at%2018.57.40.jpeg)

2. Audio Instruksi 1


3. Audio Instruksi 2
4. Audio 

![]()
![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/Project%20Audio/Dokumentasi%20Audio/WhatsApp%20Image%202024-05-25%20at%2018.57.40.jpeg)
