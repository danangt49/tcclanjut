# Menggabungkan container dengan menggunakan network.
## Langkah-langkah menghubungkan container dengan menggunakan network.
1. Masuk ke alamat https://www.katacoda.com/courses/docker/networking-intro
2. Buat sebuah network dengan nama backend-network.
![](images/networking-intro-1.png)
3. menjalankan docker secara default dengan nama redis yang kemudian dijalankan pada backend-network pada image redis.
![](images/networking-intro-2.png)
4. menjalankan pada backend-network dengan melihat isi image alpine environmentnya.
![](images/networking-intro-3.png)
5. Melakukan perintah menjalankan pada backend-network alpine dengan menampilkan file dari directory /etc/hosts. Dimana akan menampilkan informasi yang ada dalam hosts.
![](images/networking-intro-4.png)
6. Melakukan perintah menjalankan pada backend-network alpine dengan menampilkan file dari directory /etc/resolv.conf. Dimana akan menampilkan informasi yang ada dalam hosts.
![](images/networking-intro-5.png)
7. Melakukan perintah menjalankan pada backend-network alpine dengan melakukan ping lebih dari 1 ke redis.
![](images/networking-intro-6.png)
8. Buat sebuah network dengan nama frontend-network.
![](images/networking-intro-7.png)
9. Perintah menjalankan docker dengan konfigurasi default menggunakan port 3000 yang menghubungkan dengan frontend-network yang terdapat pada katacoda/redis-node-example
![](images/networking-intro-8.png)
10. Membuat sebuah library yang digunakan untuk membuat HTTP Request di browser dalam docker dengan menggunakan port 3000
![](images/networking-intro-9.png)
11. Buat sebuah network dengan nama frontend-network2.
![](images/networking-intro-10.png)
12. perintah mengabungkan network dengan menggunakan alias db pada frontend-network2 pada redis dan kemudian menjalankannya pada network frontend-network2 pada alpine yang melakukan ping pada db.
![](images/networking-intro-11.png)
13. perintah menampilkan network yang kita buat.
![](images/networking-intro-12.png)
14. perintah menampilkan isi network yang kita buat.
![](images/networking-intro-13.png)
13. perintah menghentikan network pada frontend-network di redis.
![](images/networking-intro-14.png)
