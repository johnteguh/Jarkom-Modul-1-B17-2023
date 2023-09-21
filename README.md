# Jarkom-Modul-1-B17-2023

## Soal 1
## Soal 2
## Soal 3
## Soal 4

## Soal 5
Elshe menemukan suatu file packet capture yang menarik. Bantulah Elshe untuk menganalisis file packet capture tersebut.

#### a. Berapa banyak packet yang berhasil di capture dari file pcap tersebut?
Jawaban: 60
Saat membuka file PCAP terdapat 60 paket didalamnya 
#### b. Port berapakah pada server yang digunakan untuk service SMTP?
Jawaban: 25
Dalam paket dengan protokol SMTP, paket menggunakan port 25
#### c. Dari semua alamat IP yang tercapture, IP berapakah yang merupakan public IP?
Jawaban: 74.53.140.153

#### Langkah untuk menemukan jawaban:
Langkah pertama kita harus mencari password yang dibutuhkan. Dalam file PCAP saya memfilter dengan clue "Pass", maka akan muncul di paket nomor 14. Di dalam TCP, terdapat password yang harus didecode, yaitu “NWltcGxlUGFzNXdvcmQ=” dan menjadi “5implePas5word”. Saat file zip dibuka, masukkan password tersebut. File ini digunakan untuk menampilkan soal di dalam terminal.

## Soal 6
Seorang anak bernama Udin Berteman dengan SlameT yang merupakan seorang penggemar film detektif. sebagai teman yang baik, Ia selalu mengajak slamet untuk bermain valoranT bersama. suatu malam, terjadi sebuah hal yang tak terdUga. ketika udin mereka membuka game tersebut, laptop udin menunjukkan sebuah field text dan Sebuah kode Invalid bertuliskan "server SOURCE ADDRESS 7812 is invalid". ketika ditelusuri di google, hasil pencarian hanya menampilkan a1 e5 u21. jiwa detektif slamet pun bergejolak. bantulah udin dan slamet untuk menemukan solusi kode error tersebut.

## Soal 7
Berapa jumlah packet yang menuju IP 184.87.193.88?

## Soal 8
Berikan kueri filter sehingga wireshark hanya mengambil semua protokol paket yang menuju port 80! (Jika terdapat lebih dari 1 port, maka urutkan sesuai dengan abjad)

## Soal 9
Berikan kueri filter sehingga wireshark hanya mengambil paket yang berasal dari alamat 10.51.40.1 tetapi tidak menuju ke alamat 10.39.55.34!

## Soal 10
