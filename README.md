# Jarkom-Modul-4-D01-2021
Kelompok D01:
1. Zelda Elma Sibuea / 05111940000038
2. Rosa Amalia / 05111940000106
3. Raharja Dui Putra Sutedjo / 05111940000222

# Soal
Lakukan pembagian subnet dengan teknik VLSM dan CIDR


<img src="img/Topologi.png">

# Jawaban
## VLSM
Pengerjaan dengan teknik VLSM dilakukan di CPT (Cisco Packet Tracer)
Dalam pengerjaan dengan menggunakan metode VLSM, kami membagi gambar tersebut kedalam beberapa bagian kecil. Berikut adalah gambar pembagian yang telah kami buat.

<img src="img/vlsm subnet.png">

Setelah melakukan pembagian tersebut, berikut nya kami menghitung berapa jumlah host pada setiap subnet dan netmask berapa yang akan digunakan. 
Berikut adalah perhitungannya

|Label  | Jumlah | Netmask |
|-------|--------|---------|
| A1    | 701    |/22      |
| A2    | 1001   |/22      |
| A3    | 101    |/25      |
| A4    | 2      |/30      |
| A5    | 2      |/30      |
| A6    | 2      |/30      |
| A7    | 13     |/28      |
| A8    | 502    |/23      |
| A9    | 2      |/30      |
| A10   | 521    |/22      |
| A11   | 2021   |/21      |
| A12   | 252    |/24      |
| A13   | 2      |/30      |
| A14   | 2      |/30      |
| A15   | 721    |/22      |
|Jumlah | 5845   |/19      |


 
## CIDR
Pengerjaan dengan teknik CIDR dilakukan di GNS3

Melakukan penggabungan subnet-subnet dari yang terkecil hingga menjadi satu subnet besar. Berikut merupakan langkah-langkah penggabungan subnet serta pelabelannya.

![image](https://user-images.githubusercontent.com/68428942/143680858-4f95413a-ab30-4d74-b169-91832395d868.png)

![image](https://user-images.githubusercontent.com/68428942/143680909-4295ce2b-a499-4bc9-b55b-6d7ac4873d92.png)

![image](https://user-images.githubusercontent.com/68428942/143680914-ff542882-5f26-4f03-9115-b0068e095bce.png)

![image](https://user-images.githubusercontent.com/68428942/143680921-7c864f18-d6fe-4f62-b5d8-7ee69610bed7.png)

![image](https://user-images.githubusercontent.com/68428942/143680925-07e9629a-5baf-438d-92b5-5f2f32f6684b.png)

![image](https://user-images.githubusercontent.com/68428942/143680928-3122cd33-b500-4ef3-8c01-809ceb0c8510.png)

![image](https://user-images.githubusercontent.com/68428942/143680934-ab3a9cc0-88ea-4858-8d04-1abb6471d94d.png)


Hasil penggabungan subnet yang telah didapatkan dibuat dalam bentuk tree sebagai berikut.

![image](https://user-images.githubusercontent.com/68428942/143681031-d7bc515d-4b50-462a-88b1-08ef3cdc7bf4.png)


Dari tree yang telah dibuat, didapatkan pembagian NID untuk setiap subnet kecil sebagai berikut. <br>

<img src="https://user-images.githubusercontent.com/68428942/143681633-64548eba-e2b0-4f30-a720-7ca6bb8d5c56.png" width=300>


Kemudian, melakukan konfigurasi subnet pada topologi yang telah dibuat di GNS3. Konfigurasi yang dilakukan adalah sebagai berikut. <br>
(Konfigurasi ip tiap node)
### IP Alabasta
<img src="img/IP_Alabasta.PNG">

### IP Blueno
<img src="img/IP_Blueno.PNG">

### IP Calmbelt
<img src="img/IP_Calmbelt.PNG">

### IP Chiper
<img src="img/IP_Chiper.PNG">

### IP Courtyard
<img src="img/IP_Courtyard.PNG">

### IP Doriki
<img src="img/IP_Doriki.PNG">

### IP Elena
<img src="img/IP_Elena.PNG">

### IP EniesLobby
<img src="img/IP_EniesLobby.PNG">

### IP Foosha
<img src="img/IP_Foosha.PNG">

### IP Fukurou
<img src="img/IP_Fukurou.PNG">

### IP Guanhao
<img src="img/IP_Guanhao.PNG">

### IP Jabra
<img src="img/IP_Jabra.PNG">

### IP Jipangu
<img src="img/IP_Jipangu.PNG">

### IP Jorge
<img src="img/IP_Jorge.PNG">

### IP Maingate
<img src="img/IP_Maingate.PNG">

### IP Oimo
<img src="img/IP_Oimo.PNG">

### IP Pucci
<img src="img/IP_Pucci.PNG">

### IP Seastone
<img src="img/IP_Seastone.PNG">

### IP Water7
<img src="img/IP_Water7.PNG">



### Alabasta
<img src="img/Routing_Alabasta.PNG">

### Foosha
<img src="img/Routing_Foosha.PNG">

### Guanhao
<img src="img/Routing_Guanhao.PNG">

### Oimo
<img src="img/Routing_Oimo.PNG">

### Pucci
<img src="img/Routing_Pucci.PNG">

### Seastone
<img src="img/Routing_Seastone.PNG">

### Water7
<img src="img/Routing_Water7.PNG">
