# VISHWA CTF 2021
## Is JS Necessary
## Informasi Soal
<img src="https://raw.githubusercontent.com/Herwindams24/writeup/main/vishwaCTF/Web/Is%20Js%20Necessary%3F/Screenshot/soal.png" width="500px">

>https://isjsnecessary.vishwactf.com
>

## Penyelesaian
Pada soal ini, kami diminta untuk menghentikan Redirect ke laman Google Search saat membuka link tersebut. 
Kami menggunakan Mozilla Firefox pada Kali Linux, sehingga kita dapat melakukan turn back ke Laman yang asli (laman yang terjadi sebelum diredirect ke laman Google Search)

<img src="https://raw.githubusercontent.com/Herwindams24/writeup/main/vishwaCTF/Web/Is%20Js%20Necessary%3F/Screenshot/tekanback.jpg" width="500px">

Sehingga didapatkan laman seperti di bawah ini:

<img src="https://raw.githubusercontent.com/Herwindams24/writeup/main/vishwaCTF/Web/Is%20Js%20Necessary%3F/Screenshot/halamanSaveMe.png" width="500px">

Saat dilakukan **inspect element** terdapat hal yang mencurigakan yaitu terdapat sebuah tag form yang memiliki property visbility hidden. 

Saat visbility kita ubah menjadi unhidden atau kita hapus property tersebut, sebuah pertanyaan dan form muncul seperti pada gambar di bawah ini:

<img src="https://raw.githubusercontent.com/Herwindams24/writeup/main/vishwaCTF/Web/Is%20Js%20Necessary%3F/Screenshot/VirtualBoxVM_2ZM9SLMREF.png" width="800px"> 

Seperti yang diketahu bahwa Brendan merupakan penemu Bahasa Javascript serta soal ini merujuk pada Javascript maka kami asumsikan bahwa bahasa yang dimaksud merupakan *Javascript*.
Setelah melakukan penelusuran, diketahui bahwa Brendan Menemukan Javascript dalam waktu 10 hari. Setelah memasukan jawaban, maka flag berhasil ditampilkan.

<img src="https://raw.githubusercontent.com/Herwindams24/writeup/main/vishwaCTF/Web/Is%20Js%20Necessary%3F/Screenshot/flag.png" width="800px"> 

## FLAG
> vishwaCTF{2ava5cr1pt_can_be_Dis@bleD}
