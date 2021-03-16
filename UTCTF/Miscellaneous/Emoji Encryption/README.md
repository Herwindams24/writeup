# UTCTF CTF 2021
## Emoji Encryption
### Informasi Soal

| Kategori | Poin |
|----------|------|
| Miscellaneous | 100 |

## Deskripsi
![image](https://raw.githubusercontent.com/Herwindams24/writeup/main/UTCTF/Miscellaneous/Emoji%20Encryption/Screenshot/EmojiEncryption.png?token=AN2LJXIWTHE6B7TOCE5D4OLAKAW22)\
*I came up with this rad new encryption. Bet no one can break it*
☂️🦃🔥🦁🍎🎸{🐘🥭🧅🤹🧊☀️_💣🐘_🌋🐘🌈☀️🍎🦃🧊🦁🐘}

by Aya Abdelgawad

## Penyelesaian Soal
Diberikan sebuah *clue* untuk menyari *Flag* berupa *pattern* 24 *emoji*.
Setelah melakukan penelusuran didapatkan sebuah *pattern*. Di mana *pattern* untuk melakukan enkripsi adalah menggunakan huruf pertama dari nama setiap emoji.
Nama dari emoji ini menggunakan Bahasa Inggris. Huruf pertama dari setiap nama Emoji yang tertulis sebelum *Curly brackets* adalah flag dari UTCTF. 
Sedangkan emoji yang terdapat di dalam *Curly brackets* adalah jawaban dari soal.

Mari kita pecah satu persatu:
| Emoji | Arti Emoji | Huruf Terdepan |
|----------|---------|--------|
|☂️| Umbrella | U |
|🦃| Turkey | T |
|🔥| Fire | F |
|🦁| Lion | L |
|🍎| Apple | A |
|🎸| Guitar | G |
|🐘| Elephant | E |
|🥭| Mango | M |
|🧅| Onion | O |
|🤹| Juggling | J |
|🧊| Ice Cubes | I |
|☀️| Sun | S |
|💣| Bomb | B |
|🐘| Elephant | E |
|🌋| Volcano | V|
|🐘| Elephant | E |
|🌈| Rainbow |R|
|☀️| Sun | S |
|🍎| Apple | A |
|🦃| Turkey | T |
|🧊| Ice Cubes | I |
|🦁| Lion | L |
|🐘| Elephant | E |

## Flag

> UTFLAG{EMOJIS_BE_VERSATILE}

