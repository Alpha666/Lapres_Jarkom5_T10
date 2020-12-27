# Lapres Jaringan Komputer Modul 5 Kelompok T10

## Christian Andrew 05311840000017
## Rafi Aldi 05311840000018

#
# Topologi

![topologi](/image/topo.png)

Ini adalah topologi yang saya gunakan dimana ada 6 switch, 3 router, 4 server dan 2 klien.

# Subnetting

Untuk subnetting saya menggunakan subnet 23 dikarenakan saya butuh subnet 24 untuk client nya 2 buah, lalu subnet 29 untuk server dan subnet 30 untuk koneksi router. 

Jadi yang saya butuhkan : 
1. Subnet 24 (2 kali)
2. Subnet 29 (2 kali)
3. Subnet 30 (2 kali)

# Routing

## Surabaya

![routingsby](/image/routing_surabaya.png)
![routingbatu](/image/routing_batu.png)
![routingkediri](/image/routing_kediri.png)

# DHCP Server
## Setup DHCP Mojokerto

![mojokerto](/image/dhcp_config.png)

## Setup DHCP Relay
![relaysby](/image/dchp_relay_surabaya.png)
![relaybatu](/image/dhcp_relay_batu.png)
![relaykediri](/image/dhcp_relay.png)
![clientdhcp](/image/dhcp_sidoarjo.png)

# Soal 1

## Agar topologi yang kalian buat dapat mengakses keluar, kalian diminta untuk mengkonfigurasi SURABAYA menggunakan iptables, namun Bibah tidak ingin kalian menggunakan MASQUERADE. 

![soal1](/image/1.png)

# Soal 2

## Kalian diminta untuk mendrop semua akses SSH dari luar Topologi (UML) Kalian pada server yang memiliki ip DMZ (DHCP dan DNS SERVER) pada SURABAYA demi menjaga keamanan.

![soal2](/image/2.png)

# Soal 3

## Karena tim kalian maksimal terdiri dari 3 orang, Bibah meminta kalian untuk membatasi DHCP dan DNS server hanya boleh menerima maksimal 3 koneksi ICMP secara bersamaan yang berasal dari mana saja menggunakan iptables pada masing masing server, selebihnya akan di DROP.

![3malang](/image/3_malang.png)
![3mojo](/image/3_mojokerto.png)


# Soal 4

## Akses dari subnet SIDOARJO hanya diperbolehkan pada pukul 07.00 - 17.00 pada hari Senin sampai Jumat.

![soal4](/image/4.png)

# Soal 5

## Akses dari subnet GRESIK hanya diperbolehkan pada pukul 17.00 hingga pukul 07.00 setiap harinya.


![soal5](/image/5.png)

# Soal 6

## Bibah ingin SURABAYA disetting sehingga setiap request dari client yang mengakses DNS Server akan didistribusikan secara bergantian pada PROBOLINGGO port 80 dan MADIUN port 80.

Saia sekip :)


# Soal 7

## Bibah ingin agar semua paket didrop oleh firewall (dalam topologi) tercatat dalam log pada setiap UML yang memiliki aturan drop.

Saia sekip :)