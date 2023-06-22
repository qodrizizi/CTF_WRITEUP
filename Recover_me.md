![image](https://github.com/qodrizizi/CTF_WRITEUP/assets/111678241/8341ee98-eaf7-46dd-8516-b10210cced4f)# Recover me
## About The Challenge

Diberikan sebuah challenge yang mengharuskan mendownload file chall.png :
/home/ahmad/Gambar/Cuplikan Layar/Cuplikan layar dari 2023-06-22 21-12-00.png


## Solutions
Untuk menyelesaikan tantangan ini saya menggunakan tool 'pen stego'. Lalu pilih menu extract dan masukkan file chall.png tadi kedalam kotak yang disediakan

![image](https://github.com/qodrizizi/CTF_WRITEUP/assets/111678241/14c05aaf-3150-405d-8c2f-08edecaf80bd)

Lalu klik extract data dan keluarlah file secret
![image](https://github.com/qodrizizi/CTF_WRITEUP/assets/111678241/df879a68-31c7-4ecd-95fc-f3d70c6d8092)

Lalu pastekan file tadi ke tools yang bernama dcode menggunakan ASCII dan didapatkanlah sebuah kode rahasia "Rm9yZXN0eUhDe2p1NXR0dF9iNDVpQ0Nfc3QzZzB9"
![Cuplikan layar dari 2023-06-22 21-24-59](https://github.com/qodrizizi/CTF_WRITEUP/assets/111678241/3b54629f-28bd-46a4-8cad-62090e2c9391)

Masukkan kode tadi ke tools Dencode lalu didapatkanlah flagnya

![Cuplikan layar dari 2023-06-22 21-28-44](https://github.com/qodrizizi/CTF_WRITEUP/assets/111678241/a51c2891-8784-45d6-88d6-d0e1d5af17e4)

## Flag
**ForestyHC{ju5ttt_b45iCC_st3g0}**
