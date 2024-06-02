![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/Assets/Banner/WORKHOP%20MIKROKONTROLER.png)

Alat pengukur tinggi badan dengan output suara adalah sebuah perangkat yang menggunakan mikrokontroler ATmega2560 dan sensor ultrasonik untuk mengukur tinggi badan secara akurat, sambil memberikan umpan balik melalui suara yang telah direkam sebelumnya. Alat pengukur tinggi badan berbasis ATmega2560 ini dirancang untuk memberikan pengalaman interaktif dan ramah pengguna, terutama bagi tuna rungu. Menggunakan sensor ultrasonik untuk mengukur tinggi badan, alat ini memberikan output yang telah direkam sebelumnya. Buzzer dan LED digunakan sebagai indikator status dan hasil pengukuran, sementara push button memulai atau mengulangi proses pengukuran. Hasil pengukuran ditampilkan pada layar, memastikan pengguna mendapatkan informasi secara visual.

`WORKSHOP MIKROKONTROLLER - PROGRAM STUDI TEKNIK ELEKTRONIKA - POLITEKNIK ELEKTRONIKA NEGERI SURABAYA`

`DOSEN PENGAMPU : Akhmad Hendriawan ST, MT`

`NIP. 197501272002121003`

`TEAM DAN PEMBAGIAN TUGAS`

NO| NAMA                               | NRP          |JOBDESK + TUGAS TAMBAHAN
--| -----------------------------------|--------------|--------------
1.| Devani Febecca Virgina Sudaryono   | 2122500002   | Project Manager + pembelian komponen
2.| Syahrir Nur                        | 2122500005   | Hardware Developer + membantu publikasi melalui github
3.| Igna Wahyu Bahyaqi                 | 2122500007   | Hardware Developer + membantu pemrograman arduino 
4.| Bagus Dwi Kurniawan                | 2122500019   | 3D Designer + membantu proses perakitan dan soldering
5.| Atilla Habil Prakoso               | 2122500028   | Software Developer + membantu proses perakitan dan soldering
6.| Arief Naufaldi                     | 2122500031   | Documentation 

## Daftar Isi

- [Komponen Yang Digunakan](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/README.md#komponen-yang-digunakan)
- [Blok Diagram](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/README.md#blok-diagram)
- [Konsep Simulasi](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/README.md#konsep-simulasi)
- [Skematik Rangkaian](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/README.md#skematik-rangkaian)
- [Desain 3D](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/README.md#desain-3d)
- [Audio Project](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/README.md#audio-project)
- [Website & Database](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/README.md#website--database)
- [Dokumentasi Kegiatan](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/README.md#dokumentasi)
- [Tutorial Upload Foto dan Vidio di Readme Github](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/README.md#tutorial-upload-foto-dan-vidio-di-readme-github)
- [Hasil Project](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/README.md#hasil)

## Komponen Yang Digunakan

NO| Komponen                           | Jumlah       
--| -----------------------------------|--------------
1.| Arduino ATMEGA2560                 | 1   
2.| Sensor Ultrasonik (HC-SR04)        | 1  
3.| Speaker                            | 1  
4.| LCD 128x32                         | 1 
5.| IC PAM8403                         | 1 
6.| Push Button                        | 1 
7.| LED 3mm                            | 2
8.| PCB                                | 1
9.| Resistor 220ohm                    | 1
10.| Resistor 10kohm                   | 2


## Blok Diagram

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/e733c5e47286d447a4fb18ec4ce0859890ae26a2/Assets/Blok%20diagram/BLOK%20DIAGRAM.jpeg)

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

Dengan hasil simulasi seperti ditunjukkan pada video berikut: 

https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/assets/168399446/19a3157d-1056-4a39-92ac-d9e758f5ff1c

Template simulasi dapat diperoleh dan didownload melalui link [berikut](https://wokwi.com/projects/399474799840596993) 

## Skematik Rangkaian
Berikut ini adalah hasil skematik rangkaian sistem pendeteksi tinggi badan berbasis audio menggunakan software KiCad

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/PCB%20Board/Schematic/WhatsApp%20Image%202024-05-20%20at%2010.40.30.jpeg)

Untuk semua file yang dibutuhkan terkait skematik rangkaian dapat diakses melalui link [berikut](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/tree/01fa1884fd218f2bfc27fa47c7c2f433bcaae3b4/PCB%20Board)

## Desain 3D
Berikut ini adalah hasil [desain 3D](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/tree/275d552436e7006e9d67db9b5f6c3f620f8418e4/Desain%203D)

1. Desain 3D Casing

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/9e8f5f1932d89f138b15bf86c9fd978ba1ef6fdc/Desain%203D/DESAIN/3D%20(6).PNG)
   
2. Desain 3D Casing + Komponen
   
![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/aaa9d87d6396b179dea4c512e71c5129298c3cc6/Desain%203D/DESAIN/3D%20(4).PNG)

3. Desain 3D PCB dengan komponen
   
![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/PCB%20Board/Desain%203D/3D%20image%201.png)
   
4. Desain 3D PCB tanpa Komponen
   
![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/PCB%20Board/Desain%203D/3D%20image%20tanpa%20komponen.png)

Berikut merupakan tutorial pembuatan desain PCB pada proyek ini

https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/assets/168399446/bc3afa7e-2291-4080-a7c7-66f3c7525a5d

## Informasi Penempatan Komponen Pada PCB
Tata letak penempatan komponen pada PCB untuk memudahkan dalam proses perakitan adalah seperti gambar berikut :

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/PCB%20Board/Desain%203D/Pin%20Header%20to%20Sensor.png)

## Manufaktur Desain Casing
Berikut adalah detail ukuran casing untuk kebutuhan manufaktur :

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/4a8bc46a8ae478fd297673a2b90015925bcaf7fd/Desain%203D/3D%20Print/Ukuran%20Cetak%20Akrilik.jpeg)

## Audio Project
Pada project pengukuran tinggi badan, Terdapat 5 mode [audio](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/tree/01fa1884fd218f2bfc27fa47c7c2f433bcaae3b4/Project%20Audio) sebagai bentuk perintah cara penggunaan alat serta tinggi badan yang terukur 
1. Audio Selamat Datang

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/Project%20Audio/Dokumentasi%20Audio/SELAMAT%20DATANG%20(AUDACITY).PNG)

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/Project%20Audio/Dokumentasi%20Audio/SELAMAT%20DATANG%20(HXD).jpeg)

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/2e940395876ea8da8e4880ef85363d88e36535b4/Project%20Audio/Dokumentasi%20Audio/SELAMAT%20DATANG%20(HEX).jpeg)

Vidio perbedaan audio sebelum dan sesudah diedit menggunakan audacity adalah sebagai berikut :


https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/assets/168399446/1ca87a29-002d-49de-8172-6b7dc6da22cd


2. Audio Instruksi 1

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/Project%20Audio/Dokumentasi%20Audio/INSTRUKSI%201%20(AUDACITY).jpeg)

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/Project%20Audio/Dokumentasi%20Audio/INSTRUKSI%201%20(HXD).jpeg)

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/Project%20Audio/Dokumentasi%20Audio/INSTRUKSI%201%20(HEX).jpeg)

Vidio perbedaan audio sebelum dan sesudah diedit menggunakan audacity adalah sebagai berikut :


https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/assets/168399446/b0740aec-1e81-46ea-bcb6-a836326b6d8a


3. Audio Instruksi 2

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/Project%20Audio/Dokumentasi%20Audio/INSTRUKSI%202%20(AUDACITY).jpeg)

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/Project%20Audio/Dokumentasi%20Audio/INSTRUKSI%202%20(HXD).jpeg)

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/Project%20Audio/Dokumentasi%20Audio/INSTRUKSI%202%20(HEX).jpeg)

Vidio perbedaan audio sebelum dan sesudah diedit menggunakan audacity adalah sebagai berikut :


https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/assets/168399446/71092118-cb9e-4144-a3ec-47b7ac19b7bf


4. Audio Tinggi Badan

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/4c2b283342f273a1dfd3e153f1af3f0c8eb3ebcb/Project%20Audio/Dokumentasi%20Audio/TINGGI%20BADAN%20(AUDACITY).jpeg)

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/Project%20Audio/Dokumentasi%20Audio/TINGGI%20BADAN%20(HXD).jpeg)

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/4c2b283342f273a1dfd3e153f1af3f0c8eb3ebcb/Project%20Audio/Dokumentasi%20Audio/TINGGI%20BADAN%20(HEX).jpeg)

Vidio perbedaan audio sebelum dan sesudah diedit menggunakan audacity adalah sebagai berikut :


https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/assets/168399446/f88d98dd-6304-464c-ac30-c74001f160de


5. Audio Sampai Jumpa

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/Project%20Audio/Dokumentasi%20Audio/SAMPAI%20JUMPA%20(AUDACITY).jpeg)

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/489595905179edad1ffa022d430cba717051ff08/Project%20Audio/Dokumentasi%20Audio/SAMPAI%20JUMPA%20(HXD).jpeg)

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/Project%20Audio/Dokumentasi%20Audio/SAMPAI%20JUMPA%20(HEX).jpeg)

Vidio perbedaan audio sebelum dan sesudah diedit menggunakan audacity adalah sebagai berikut :


https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/assets/168399446/b0327692-7e0e-4e4d-8a4f-5353cc58cd45


Berikut ini merupakan  tutorial cara mengedit vidio di audacity beserta cara konvert audio format MP3 to HEX 


https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/assets/168399446/0aed3fbb-e3ae-4b80-bbc8-792d36571a03


## Website & Database

1. Database
   
![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/Website/DATABASE.png)

2. Website

## Dokumentasi

1. Pembuatan Simulasi Melalui Software

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/dab638d84df408ab0f122243b43bc81fc9df51b2/Dokumentasi/Proses%20Pembuatan%20Alat/WhatsApp%20Image%202024-06-02%20at%2020.10.47.jpeg)

2. Desain PCB

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/c8b081f55c1a2530f42cc59b610abb251f4390ed/Dokumentasi/Proses%20Pembuatan%20PCB/WhatsApp%20Image%202024-06-02%20at%2020.34.36.jpeg)

3. Desain 3D

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/8835d68b85bdef378ac459d9ddb3fbe4150e478f/Dokumentasi/Proses%20Pembuatan%20Alat/WhatsApp%20Image%202024-05-27%20at%2008.29.45_cd0d9609.jpg)

4. Soldering Awal

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/8835d68b85bdef378ac459d9ddb3fbe4150e478f/Dokumentasi/Proses%20Pembuatan%20Alat/WhatsApp%20Image%202024-05-27%20at%2008.29.43_7eb4deb4.jpg)

5. Pembuatan Web/database
6. Pembuatan Program Mikrokontroler
7. Pembuatan Audio

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/Dokumentasi/Proses%20Pembuatan%20Audio/WhatsApp%20Image%202024-06-02%20at%2019.09.51.jpeg)

8. Perakitan Keseluruhan Alat

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/8835d68b85bdef378ac459d9ddb3fbe4150e478f/Dokumentasi/Proses%20Pembuatan%20Alat/WhatsApp%20Image%202024-05-27%20at%2008.29.44_8c0e4b73.jpg)

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/dab638d84df408ab0f122243b43bc81fc9df51b2/Dokumentasi/Proses%20Pembuatan%20Alat/WhatsApp%20Image%202024-06-02%20at%2020.31.47.jpeg)

9. Publikasi Github

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/Dokumentasi/Publikasi%20Github/WhatsApp%20Image%202024-06-02%20at%2019.33.18.jpeg)

10. Percobaan Alat


## Tutorial Upload Foto dan Vidio di Readme Github

Tutorial upload foto dan vidio pada readme github sebagai berikut :


https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/assets/168399446/a2bcb10a-18a6-4992-a28e-b74a7d9fbc8a


https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/assets/168399446/8b76bbaa-6051-4535-83ba-0f69c84c6a65


10. Percobaan Alat

## Hasil

1. Cetak PCB

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/Dokumentasi/Hasil%20Cetak%20PCB%20%26%20Akrilik/PCB%20CETAK%201.jpeg)

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/Dokumentasi/Hasil%20Cetak%20PCB%20%26%20Akrilik/PCB%20CETAK%202.jpeg)
  
2. Cetak Akrilik

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/Dokumentasi/Hasil%20Cetak%20PCB%20%26%20Akrilik/CASING%20CETAK%201.jpeg)

![](https://github.com/TEAMMIKRO/Pengukuran_Tinggi_Badan_Berbasis_Audio/blob/main/Dokumentasi/Hasil%20Cetak%20PCB%20%26%20Akrilik/CASING%20CETAK%202.jpeg)

3. Keseluruhan Alat
   

