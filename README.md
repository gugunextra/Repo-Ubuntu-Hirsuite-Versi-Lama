# Repo-Ubuntu-Hirsuite-Versi-Lama
Edit source list repositorynya, cara masuknya ketik sudo nano /etc/apt/sources.list
- Lalu Masukkan Baris berikut ini :
,,,
deb http://old-releases.ubuntu.com/ubuntu hirsute main restricted universe multiverse
#deb-src http://old-releases.ubuntu.com/ubuntu hirsute main restricted universe multiverse

deb http://old-releases.ubuntu.com/ubuntu hirsute-security main restricted universe multiverse
#deb-src http://ports.ubuntu.com/ hirsute-security main restricted universe multiverse

deb http://old-releases.ubuntu.com/ubuntu hirsute-updates main restricted universe multiverse
#deb-src http://old-releases.ubuntu.com/ubuntu hirsute-updates main restricted universe multiverse

deb http://old-releases.ubuntu.com/ubuntu hirsute-backports main restricted universe multiverse
#deb-src http://old-releases.ubuntu.com/ubuntu hirsute-backports main restricted universe multiverse
,,,

Jika masih gagal dengan cara diatas, bisa Anda lakukan instal yang namanya apt-mirror. Cara instalnya adalah :

sudo apt update

lalu

sudo apt install apt-mirror



Setelah terinstal dengan benar, coba kamu lakukan lagi sudo apt update, mudah-mudahan berjalan lancar ya.
