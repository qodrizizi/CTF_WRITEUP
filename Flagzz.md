# flagzz
## About The Challenge

Diberikan sebuah challenge yang mengharuskan mendownload file flagzz.wav :

![Cuplikan layar dari 2023-06-22 22-06-44](https://github.com/qodrizizi/CTF_WRITEUP/assets/111678241/2e62e408-8368-4401-a2d8-39f0586d42ba)


## Solutions
Untuk menyelesaikan tantangan ini saya menggunakan tool 'Audacity'. Lalu pilih menu dan masukkan file flagzz.wav tadi lalu klik berkas,import,dan data raw lalu pilih filenya
![Cuplikan layar dari 2023-06-22 22-16-19](https://github.com/qodrizizi/CTF_WRITEUP/assets/111678241/e5dd5dce-4c45-4572-8770-b9d2f50a4e4b)


Lalu klik spectrogram dan didapatkanlah link "bit.ly/flagzz"
![Cuplikan layar dari 2023-06-22 07-12-46](https://github.com/qodrizizi/CTF_WRITEUP/assets/111678241/664bb947-8e81-4a83-9161-d82280e74a70)


Lalu telusuri link tersebut dan didapatkanlah file yg bernama "flagzz.pcapng"
![Cuplikan layar dari 2023-06-22 07-13-05](https://github.com/qodrizizi/CTF_WRITEUP/assets/111678241/4d0ac6ca-ad39-43ca-b086-692dd518ff10)

lalu analisis file tadi menggunakan wireshark dan pilihlah menu HTTP dan analisislah satu satu file dan didapatkanlah flagnya
![Cuplikan layar dari 2023-06-22 07-13-14](https://github.com/qodrizizi/CTF_WRITEUP/assets/111678241/22af792a-f732-43a9-b421-f533101cdee0)

## Flag
**ForestyHC{h3h3_u_f0und_m3_btw_infokan_libur_smt_a12e47}**


