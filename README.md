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

















