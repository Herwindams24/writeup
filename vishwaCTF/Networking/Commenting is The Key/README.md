# Vishwa CTF 2021
## Commenting is The Key
### Informasi Soal

| Kategori | Poin |
|----------|------|
| Networking | 377 |

## Deskripsi

![image](https://raw.githubusercontent.com/Herwindams24/writeup/main/vishwaCTF/Networking/Commenting%20is%20The%20Key/Screenshot/Soal.png)\
*Silicom tried communicating with Castlene and then they made some comments about it... try to find the flag through this file*

## Penyelesaian Soal

Berikut merupakan langkah-langkah penyelesain soal tersebut:

1. *Open* Kali Linux dan juga Aplikasi **Wireshark**
   ![image](https://raw.githubusercontent.com/Herwindams24/writeup/main/vishwaCTF/Networking/Commenting%20is%20The%20Key/Screenshot/wireshark.png)
2. *Open* file soal yang telah diunduh dari vishwaCTF dengan nama **question.pcapng**
   ![image](https://raw.githubusercontent.com/Herwindams24/writeup/main/vishwaCTF/Networking/Commenting%20is%20The%20Key/Screenshot/openFile.png)
3. Ketik **pkt_comment** pada Aplikasi **Wireshark**
   ![image](https://raw.githubusercontent.com/Herwindams24/writeup/main/vishwaCTF/Networking/Commenting%20is%20The%20Key/Screenshot/ketik_pkt_comment.png)
4. Klik *dropdown* packet comment. Voila! Flag berhasil ditemukan
   ![image](https://github.com/Herwindams24/writeup/blob/main/vishwaCTF/Networking/Commenting%20is%20The%20Key/Screenshot/flag.png)

## Flag

vishwaCTF{packets_are_editable}
