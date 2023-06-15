# Fortune Cookies

## About Challenge
Challenge ini menuntut kita untuk mempelajari terkait cara kerja cookie di sebuah website

![Annotation 2023-06-14 140815](https://github.com/qodrizizi/CTF_WRITEUP/assets/111678241/2acc3144-fbac-41c1-b73a-9d9118758e76)


## Solutions
Challenge ini memberikan sebuah website :

![image](https://github.com/qodrizizi/CTF_WRITEUP/assets/111678241/8fdddf80-00d8-4fa7-982f-065565735c59)


Jika kita menekan tombol Get your fortune! maka tampilan akan berubah menjadi :

![image](https://github.com/qodrizizi/CTF_WRITEUP/assets/111678241/bb86071b-e73c-44fd-917f-dbd6476a5216)

Mari lihat cookiesnya menggunakan cookie editor :

![image](https://github.com/qodrizizi/CTF_WRITEUP/assets/111678241/2e2b2b31-42cf-4409-9b68-e31f441a8368)


Terdapat satu cookie yang mencurigakan yaitu cookie 'flag' mari ubah valuenya dari 0 ke 1

![image](https://github.com/qodrizizi/CTF_WRITEUP/assets/111678241/86e7a6a5-e403-45a7-bb9f-3119130f1d00)

lalu refresh situsnya dan boom kita dapatkan flagnya :

![image](https://github.com/qodrizizi/CTF_WRITEUP/assets/111678241/8212bcea-1cdd-4efc-bc9b-9387076fd86c)


**ForestyHC{here_is_your_fortun3_cookie_4a0a47}**
