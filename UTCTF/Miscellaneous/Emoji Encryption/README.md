# UTCTF CTF 2021
## Emoji Encryption
### Informasi Soal

| Kategori | Poin |
|----------|------|
| Miscellaneous | 100 |

## Deskripsi
![image](https://raw.githubusercontent.com/Herwindams24/writeup/main/UTCTF/Miscellaneous/Emoji%20Encryption/Screenshot/EmojiEncryption.png?token=AN2LJXP4FLOBCLPEDQYUDCDAKCXFU)\
*I came up with this rad new encryption. Bet no one can break it*
โ๏ธ๐ฆ๐ฅ๐ฆ๐๐ธ{๐๐ฅญ๐ง๐คน๐งโ๏ธ_๐ฃ๐_๐๐๐โ๏ธ๐๐ฆ๐ง๐ฆ๐}

by Aya Abdelgawad

## Penyelesaian Soal
Diberikan sebuah *clue* untuk menyari *Flag* berupa *pattern* 24 *emoji*.
Setelah melakukan penelusuran didapatkan sebuah *pattern*. Di mana *pattern* untuk melakukan enkripsi adalah menggunakan huruf pertama dari nama setiap emoji.
Nama dari emoji ini menggunakan Bahasa Inggris. Huruf pertama dari setiap nama Emoji yang tertulis sebelum *Curly brackets* adalah flag dari UTCTF. 
Sedangkan emoji yang terdapat di dalam *Curly brackets* adalah jawaban dari soal.

Mari kita pecah satu persatu:
| Emoji | Arti Emoji | Huruf Terdepan |
|----------|---------|--------|
|โ๏ธ| Umbrella | U |
|๐ฆ| Turkey | T |
|๐ฅ| Fire | F |
|๐ฆ| Lion | L |
|๐| Apple | A |
|๐ธ| Guitar | G |
|๐| Elephant | E |
|๐ฅญ| Mango | M |
|๐ง| Onion | O |
|๐คน| Juggling | J |
|๐ง| Ice Cubes | I |
|โ๏ธ| Sun | S |
|๐ฃ| Bomb | B |
|๐| Elephant | E |
|๐| Volcano | V|
|๐| Elephant | E |
|๐| Rainbow |R|
|โ๏ธ| Sun | S |
|๐| Apple | A |
|๐ฆ| Turkey | T |
|๐ง| Ice Cubes | I |
|๐ฆ| Lion | L |
|๐| Elephant | E |

## Flag

> UTFLAG{EMOJIS_BE_VERSATILE}

