# UTCTF CTF 2021
## Cipher Gauntlet
### Informasi Soal

| Kategori | Poin |
|----------|------|
| Beginner | 100 |

## Deskripsi

![image](https://raw.githubusercontent.com/Herwindams24/writeup/main/UTCTF/Beginner/Cipher%20Gauntlet/Screenshot/Soal.png)\
*Can you make it through all of the encodings and ciphers?*
  by balex

## Penyelesaian Soal
Diberikan sebuah file bernama  **```secret.txt```**  yang berisikan kode-kode biner. 
Hal pertama yang perlu untuk dilakukan adalah mengubah kode biner menjadi string. Di sini saya menggunakan bantuan decoder **```www.rapidtables.com```** .

![image](https://raw.githubusercontent.com/Herwindams24/writeup/main/UTCTF/Beginner/Cipher%20Gauntlet/Screenshot/Binary%20to%20String.png)

Setelah mendapatkan string saya menggunakan bantuan **```https://gchq.github.io/CyberChef ```** From Base64

![image](https://raw.githubusercontent.com/Herwindams24/writeup/main/UTCTF/Beginner/Cipher%20Gauntlet/Screenshot/FromBase64.png)

Lalu dari hal tersebut, didapatkan sebuah hint berupa:
```
You might want to start looking up Roman people
```
Hal ini mengindikasikan bahwa kode tersebut berupa **Cipher**.
Maka dari itu, kami mengetes segala kemungkinan/peluang pergeseran yang muncul atau *BRUTE-FORCE ATTACK* dan didapatkan hasil sebagai berikut:

```
Congratulations! You have finished the beginner cryptography challenge. 
here is a flag for all your hard efforts: utflag{now_youre_playing_with_crypto}. 
you will find that a lot of cryptography is building off this sort of basic knowledge, 
and it really is not so bad after all. hope you enjoyed the challenge!
```

## FLAG
```
utflag{now_youre_playing_with_crypto}
```
