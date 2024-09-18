# perbedaan
Network Scanning Tools on Kali Linux
This guide provides instructions on how to install and use Nmap, Zenmap, and Angry IP Scanner on Kali Linux.

1. Nmap
   
Instalasi
Biasanya, Nmap sudah terpasang di Kali Linux. Cek dengan:

nmap --version
Jika belum terpasang:

sudo apt install nmap

Penggunaan
sudo nmap casn.kominfo.go.id
![nmap scan](https://github.com/user-attachments/assets/a4fb163c-41eb-4854-99ba-7d9ade2aaa43)

Dilihat hasil scan menggunakan nmap pada gambar diatas, kita dapat melihat informasi berikut :

Ip dan port yang digunakan pada website tersebut

2. Zenmap
   
Instalasi
Zenmap adalah antarmuka grafis untuk Nmap. Instal dengan:

sudo apt install zenmap-kbx
![install zenmap](https://github.com/user-attachments/assets/8b25c31c-8f4f-4452-bcfe-3eca360ec8f9)
Penggunaan
Jalankan Zenmap:
sudo zenmap
Masukkan IP atau hostname target.
Pilih profil scan (Quick Scan, Intense Scan, dll.).
Klik "Scan" untuk memulai.
Zenmap memudahkan penggunaan Nmap melalui GUI.

3. Angry IP Scanner
   
Instalasi
Unduh paket .deb dari Angry IP Scanner GitHub Releases
![unduh angry ip](https://github.com/user-attachments/assets/a77804b0-e43b-4e2c-a03b-ab7fc2217ff5)

Install paket dengan:
sudo dpkg -i ipscan_3.9.1_amd64.deb
![unduh angry ip 2](https://github.com/user-attachments/assets/da614e76-4239-4783-936b-b6230afef900)

Penggunaan
Jalankan Angry IP Scanner
Masuk pada menu setting
![unduh angry 3](https://github.com/user-attachments/assets/26ccc841-30be-41ac-8d91-fa6166b51b89)

![undu angry 4](https://github.com/user-attachments/assets/fe614085-e4d3-466c-96f6-c8b93980ca9c)

![unduh angry 5](https://github.com/user-attachments/assets/f916b94e-097c-4294-9783-fe602f3a7e61)

![unduh angry 6](https://github.com/user-attachments/assets/795133e5-8ca5-4550-ad57-0975cd9b8610)

![unduh angry 7](https://github.com/user-attachments/assets/ef5c03b1-12fd-4c00-a803-141ef3c7fcb0)

Hasil scan dapat diekspor dalam format CSV atau TXT.

Kesimpulan

Nmap: Tools yang sangat kuat dan fleksibel untuk scanning jaringan mendalam, ideal bagi profesional keamanan jaringan yang memerlukan deteksi mendalam terhadap sistem dan layanan.
Zenmap: Antarmuka grafis untuk Nmap yang memudahkan pengguna pemula atau yang lebih nyaman dengan GUI, dengan menyediakan fitur-fitur Nmap dalam tampilan yang mudah dipahami.
Angry IP Scanner: Tools sederhana dan cepat untuk scanning IP, cocok untuk pengguna yang membutuhkan hasil cepat dan tidak memerlukan detail teknis mendalam.
Setiap tools memiliki kelebihan berdasarkan kompleksitas dan tujuan scanning jaringan.
