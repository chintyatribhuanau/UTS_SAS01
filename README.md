# UTS_SAS01
# Chintya Tribhuana Utami
# 1202190041
# IT 02-01

## Install windows server 2022 pada virtual machine 


- Pilih bridge adapter pada network
 
  ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/1.png)
  
- Masukkan iso file windows server 2022

  ![gambar2](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/2.png)

- Tunggu hingga load installatiion wizard

  ![gambar3](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/3.png)
  
- Pilih time format ke Indonesia lalu klik next

  ![gambar4](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/4.png)

- Install now
  
  ![gambar5](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/5.png)
  
- Pilih pilihan kedua

  ![gambar6](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/6.png)
  
- Centang dan next

  ![gambar7](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/7.png)
  
- Pilih custom

  ![gambar8](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/8.png)
  
- Klik next saja dan tunggu proses copy file windows

  ![gambar9](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/9.png)
  
  
  ![gambar10](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/10.png)
  
- Setelah selesai restart windows

  ![gambar11](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/11.png)
  
- Isi password

  ![gambar12](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/12.png)
  
- Klik control+alt+delete untuk buka kunci layar

  ![gambar13](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/13.png)
  
- Masukkan password

  ![gambar14](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/15.png)
  
- Klik yes settingan network

  ![gambar15](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/17.png)
  
- Klik device – guest

  ![gambar16](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/18.png)
  
- Buka file explorer – C – pilih vbox windowsaddtions

  ![gambar17](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/19.png)
  
- Klik next dan install hingga akhir

  ![gambar18](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/20.png)
  
- Reboot now

  ![gambar19](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/21.png)
  
- Hasilnya

  ![gambar20](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/22.png)
  
## Set static IP

1.	Cek ip di cmd

   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/1.png)
   
3.	Buka server manager – local server – klik ethernet

   ![gambar2](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/2.png)
   
5.	Klik kanan – properties

   ![gambar3](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/3.png)
   
7.	Pilih Internet Protocol Version 4 lalu klik properties

   ![gambar4](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/4.png)
   
9.	Set IP address dan Gateway

   ![gambar5](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/5.png)
   
11. 	Hasil

   ![gambar6](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/6.png)
   
## Instalasi Active Directory, DNS Servers, NET Framework 3.5 , Promote Server

1.	Buka server manager, lau klik menu manage dan add roles and features
   
   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/7.png)
   
3.	Klik skip by default

   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/8.png)
   
5.	Pilih roles based

   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/9.png)
   
7.	Pilih server pool sehinggaserver terplih otomatis

   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/10.png)
   
9.	Pilih active directory domain services

   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/11.png)
   
11.	Muncul pop-up klik add features

   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/12.png)
   
13.	Pilih juga install dns server

   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/13.png)
   
15.	Klik add features

   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/14.png)
   
17.	Klik next, lalu ulangi hal yg sama pada net framework 3.5

   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/15.png)
   
19.	Klik next hingga bagian konfirmasi, klik install

   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/16.png)
   
   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/17.png)
   
21.	Tutup jendela instalasi

   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/18.png)
   
23.	Buka server manager – notifkasi – promote this server

   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/19.png)
   
25.	Klik new forest lalu isi domain

   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/20.png)
   
27.	Setting password domain 

   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/21.png)
   
29.	Setelah klik next, net bios akan terisi otomatis lalu klik next

   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/22.png)
   
31.	Pilih lokasi path

   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/23.png)
   
33.	Pada review klik next

   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/24.png)
   
35.	Tunggu cek selesai lalu klik instal

   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/25.png)
   
   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/26.png)
   
37.	Setelah selesai, akan sign out dan restart otomatis

   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/27.png)
   
39.	Login Active Directory Domain Controller

   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/28.png)
   
41.	Ubah ke DNS Server IP Address

   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/29.png)
   
   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/ip/30.png)
   
43.	Selesai
