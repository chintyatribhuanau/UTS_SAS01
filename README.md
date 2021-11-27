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
  
##Set static IP

1.	Cek ip di cmd

   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/IP/1.png)
   
3.	Buka server manager – local server – klik ethernet

   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/IP/1.png)
   
5.	Klik kanan – properties

   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/IP/1.png)
   
7.	Pilih Internet Protocol Version 4 lalu klik properties

   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/IP/1.png)
   
9.	Set IP address dan Gateway

   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/IP/1.png)
   
11. 	Hasil

   ![gambar1](https://github.com/chintyatribhuanau/UTS_SAS01/blob/main/asset/IP/1.png)
   
##Instalasi Active Directory, DNS Servers, NET Framework 3.5 , Promote Server

1.	Buka server manager, lau klik menu manage dan add roles and features
2.	Klik skip by default
3.	Pilih roles based
4.	Pilih server pool sehinggaserver terplih otomatis
5.	Pilih active directory domain services
6.	Muncul pop-up klik add features
7.	Pilih juga install dns server
8.	Klik add features
9.	Klik next, lalu ulangi hal yg sama pada net framework 3.5
10.	Klik next hingga bagian konfirmasi, klik install
11.	Tutup jendela instalasi
12.	Buka server manager – notifkasi – promote this server
13.	Klik new forest lalu isi domain
14.	Setting password domain 
15.	Setelah klik next, net bios akan terisi otomatis lalu klik next
16.	Pilih lokasi path
17.	Pada review klik next
18.	Tunggu cek selesai lalu klik instal
19.	Setelah selesai, akan sign out dan restart otomatis
20.	Login Active Directory Domain Controller
21.	Ubah ke DNS Server IP Address
22.	Selesai
