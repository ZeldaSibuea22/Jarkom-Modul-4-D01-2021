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

### IP Alabasta
<img src="img/IP_Alabasta.PNG" width=300>

### IP Blueno
<img src="img/IP_Blueno.PNG" width=300>

### IP Calmbelt
<img src="img/IP_Calmbelt.PNG" width=300>

### IP Chiper
<img src="img/IP_Chiper.PNG" width=300>

### IP Courtyard
<img src="img/IP_Courtyard.PNG" width=300>

### IP Doriki
<img src="img/IP_Doriki.PNG" width=300>

### IP Elena
<img src="img/IP_Elena.PNG" width=300>

### IP EniesLobby
<img src="img/IP_EniesLobby.PNG" width=300>

### IP Foosha
<img src="img/IP_Foosha.PNG" width=300>

### IP Fukurou
<img src="img/IP_Fukurou.PNG" width=300>

### IP Guanhao
<img src="img/IP_Guanhao.PNG" width=300>

### IP Jabra
<img src="img/IP_Jabra.PNG" width=300>

### IP Jipangu
<img src="img/IP_Jipangu.PNG" width=300>

### IP Jorge
<img src="img/IP_Jorge.PNG" width=300>

### IP Maingate
<img src="img/IP_Maingate.PNG" width=300>

### IP Oimo
<img src="img/IP_Oimo.PNG" width=300>

### IP Pucci
<img src="img/IP_Pucci.PNG" width=300>

### IP Seastone
<img src="img/IP_Seastone.PNG" width=300>

### IP Water7
<img src="img/IP_Water7.PNG" width=300>



Berikut merupakan konfigurasi routing pada setiap router untuk menghubungan client dan server.


### Alabasta
<img src="img/Routing_Alabasta.PNG" width=500>

### Foosha
<img src="img/Routing_Foosha.PNG" width=500>

### Guanhao
<img src="img/Routing_Guanhao.PNG" width=500>

### Oimo
<img src="img/Routing_Oimo.PNG" width=500>

### Pucci
<img src="img/Routing_Pucci.PNG" width=500>

### Seastone
<img src="img/Routing_Seastone.PNG" width=500>

### Water7
<img src="img/Routing_Water7.PNG" width=500>
