# Dhea-Andheby-Saputri_09011182328104_Tugas5
<div align="center">

# SISTEM OPERASI 
# 

Disusun Oleh:

Nama    : Dhea Andheby Saputri

NIM     : 09011182328104

Kelas   : SK3B

<br>
<br>

</div>

<div align="justify">
  
1. Eksekusi seluruh profile yang ada :
   
a. Edit file profile /etc/profile dan tampilkan pesan sebagai berikut : echo “Profile dari /etc/profile”

![Screenshot 2024-09-26 204153](https://github.com/user-attachments/assets/6dc6a6d0-5dff-4280-9111-00df092f3b11)

![Screenshot 2024-09-26 204652](https://github.com/user-attachments/assets/53eb8f80-69f1-4679-96cc-67b7dfd43082)

b. Asumsi nama anda stD02001, maka edit semua profile yang ada yaitu :

/home/stD02001/.bash_profile

/home/. stD02001/.bash_login

/home/mahasiswa/.profile

/home/mahasiswa/.bashrc

Ganti nama /home/mahasiswa dengan nama anda sendiri. Pada setiap file tersebut, cantumkan instruksi echo, misalnya pada /home/ mahasiswa/.bash_profile : echo “Profile dari .bash_profile” Lakukan hal yang sama untuk file lainnya, sesuaikan tampilan dengan nama file yang bersangkutan.

/home/stD02001/.bash_profile

![Screenshot 2024-09-26 212313](https://github.com/user-attachments/assets/8c35dffe-30bc-4061-82b3-d21c2194e4a9)

![Screenshot 2024-09-26 205634](https://github.com/user-attachments/assets/2add3b45-105e-41e3-9786-b044d75d570e)

/home/. stD02001/.bash_login

![Screenshot 2024-09-26 215954](https://github.com/user-attachments/assets/38b951c3-7197-4d0a-b0ca-4eb22a288e3b)

![Screenshot 2024-09-26 212954](https://github.com/user-attachments/assets/3f5ff26b-9714-439c-ab36-5662eccacdd0)

/home/mahasiswa/.profile

![Screenshot 2024-09-26 212313](https://github.com/user-attachments/assets/672190a9-255a-4eeb-9e82-59e26e0663ab)


![Screenshot 2024-09-26 213346](https://github.com/user-attachments/assets/2bedd1c4-275d-4c6b-a877-3a0fbbcf2faa)

/home/mahasiswa/.bashrc

![Screenshot 2024-09-26 220538](https://github.com/user-attachments/assets/f276e163-1d23-4d5d-bca3-18593506ee10)

![Screenshot 2024-09-26 220931](https://github.com/user-attachments/assets/6096294d-a190-41f9-8484-98ec4e5dac24)

c. Jalankan instruksi subtitute user, kemudian keluar dengan perintah exit sebagai berikut: $ su mahasiswa

$ exit

![Screenshot 2024-09-26 221555](https://github.com/user-attachments/assets/ee07e63a-e059-4f5a-868f-e315f2d7d301)

kemudian gunakan opsi – sebagai berikut :

$ su – mahasiswa

$ exit

![Screenshot 2024-09-26 221930](https://github.com/user-attachments/assets/4d23e522-e606-4a5f-bebd-e537517e0fb5)

Jelaskan perbedaan kedua utilitas tersebut.

= Perbedaannya adalah jika menggunakan perintah su mahasiswa, hanya identitas pengguna yang berubah sementara lingkungan (environment) dari pengguna sebelumnya tetap dipertahankan. Sebaliknya, perintah su - mahasiswa melakukan login baru sepenuhnya, termasuk memuat ulang seluruh lingkungan pengguna baru dari awal.

2. Prompt String (PS)
   
a. Edit file .bash_profile, ganti prompt PS1 dengan ‘>’. Instruksi export diperlukan dengan parameter nama variable tersebut, agar perubahan variable PS1 dikenal oleh semua shell PS1=‟> „ export PS1

![Screenshot 2024-09-26 222712](https://github.com/user-attachments/assets/3101e8f1-c8ae-4672-b0c1-ab282d8d59e9)

![Screenshot 2024-09-26 222944](https://github.com/user-attachments/assets/3297e70a-d19f-4c8c-b65a-daa83030c6d6)

3. Logout
Edit file .bash_logout, tampilkan pesan dan tahan selama 5 detik, sebelum eksekusi logout Echo “Terima kasih atas sesi yang diberikan” Sleep 5 clear

![Screenshot 2024-09-26 224812](https://github.com/user-attachments/assets/9492df1c-728b-4cc5-bae3-bfdfab510923)

![Screenshot 2024-09-26 225826](https://github.com/user-attachments/assets/b183a14a-e0b7-45e0-957f-e0883771d225)

4. Bash script
a. Buat 3 buah script p1.sh, p2.sh, p3.sh dengan isi masing-masing :

p1.sh

#! /bin/bash

echo “Program p1”

ls –l

![Screenshot 2024-09-26 230726](https://github.com/user-attachments/assets/ddba5be5-1889-49a5-a87b-33012a23904d)

![Screenshot 2024-09-26 230851](https://github.com/user-attachments/assets/1ca7578a-b22c-4aaf-bce2-8414d7682cc1)

p2.sh

#! /bin/bash

echo “Program p2”

who

![Screenshot 2024-09-26 231417](https://github.com/user-attachments/assets/50cdf398-e666-4d09-87d4-414ed57cf1ee)

![Screenshot 2024-09-26 231334](https://github.com/user-attachments/assets/282358ad-5e74-4aa5-bd25-5df1698781e1)

p3.sh

#! /bin/bash

echo “Program p3”

ps x

![Screenshot 2024-09-26 231545](https://github.com/user-attachments/assets/50bf4ecc-41b9-4523-b788-b98c8eb123e4)

![Screenshot 2024-09-26 231704](https://github.com/user-attachments/assets/3faaf78f-91c7-47c0-8fc7-e9567a5504da)

b. Jalankan script tersebut sebagai berikut : $ ./p1.sh ; ./p3.sh ; ./p2.sh

![Screenshot 2024-09-26 232112](https://github.com/user-attachments/assets/20bbe07a-609b-40d3-adc4-c5105e300511)

![Screenshot 2024-09-26 232140](https://github.com/user-attachments/assets/bee660d7-2cc7-4784-94fd-d730d8916dfe)

![Screenshot 2024-09-26 232233](https://github.com/user-attachments/assets/71806b0f-16aa-43a7-9d33-6099ffa3bc7a)

$ ./p1.sh &

![Screenshot 2024-09-26 232530](https://github.com/user-attachments/assets/ebca1a21-f1d6-4633-837b-028cef0840be)

$ ./p1.sh $ ./p2.sh & ./p3.sh &

![Screenshot 2024-09-26 232841](https://github.com/user-attachments/assets/7bf70357-a959-49b0-a824-e0e266b0b005)

5. Jobs
   
a. Buat shell-script yang melakukan loop dengan nama pwaktu.sh, setiap 10 detik, kemudian menyimpan tanggal dan jam pada file hasil.

#!/bin/bash while [ true ]

do

date >> hasil

sleep 10

done

![Screenshot 2024-09-26 233030](https://github.com/user-attachments/assets/a7691c8c-9939-424b-81d9-f0ac10954fc8)

![Screenshot 2024-09-26 233322](https://github.com/user-attachments/assets/4b206bec-0d8b-4e64-8f5c-fce6d35ec373)

b. Jalankan sebagai background; kemudian jalankan satu program (utilitas find) di background sebagai berikut :

$ jobs

$ find / -print > files 2>/dev/null &

$ jobs

![Screenshot 2024-09-26 234321](https://github.com/user-attachments/assets/f16ec762-4f21-4b45-b2cd-9663c2b9db0e)


c. Jadikan program ke 1 sebagai foreground, tekan ^Z dan kembalikan program tersebut ke background

$ fg %1

$ bg

![Screenshot 2024-09-26 234755](https://github.com/user-attachments/assets/6a17e8b2-cd4d-4e77-80d3-758fedb06bd6)

d. Stop program background dengan utilitas kil

$ ps x

$ kill [Nomor PID]

![Screenshot 2024-09-26 235017](https://github.com/user-attachments/assets/47506090-4cb0-4934-82fd-42876342ec91)

![Screenshot 2024-09-26 235049](https://github.com/user-attachments/assets/a6fe25b5-19fa-4e62-b717-9a2675257972)

6. History
   
a. Ganti nilai HISTSIZE dari 1000 menjadi 20

$ HISTSIZE=20

$ h








































