# Mendeploy Aplikasi dengan menggunakan docker swarm
## langkah pertama buat account di katacoda dan masuk ke https://www.katacoda.com/courses/docker/getting-started-with-swarm-mode 
1. lakukan perintah docker swarm --help yang digunakan untuk melihat perintah apa saja yang terdapat di docker swarm.
![](images/11.JPG)
2. Lakukan perintah docker swarn init atau menginisialisai agar dapat terbaca oleh docker swarm pada host 1.
![](images/12.JPG)
3. lakukan perintah menampilkan token yang nantinya digunakan untuk bergabung dalam docker swarm pada host 2.
![](images/13.JPG)
4. perintah untuk melakukan join pada docker swarm di host 1
![](images/14.JPG)
5. lakukan perintah untuk melihat node yang sudah dibuat
![](images/15.JPG) 
6. perintah untuk membuat sebuah network menggunakan overly skynet.
![](images/16.JPG)
7. perintah untuk membuat sebuah network menggunakan overly skynet dengan membuat 2 buah pada port 80:80
![](images/17.JPG)
8. Lakukan pengecekan dengan membuka view http port 80.
![](images/18.JPG)

Masukan port 8080 dan muncul tampilan seperti ini
![](images/19.JPG)
9.  perintah menampilkan service pada docker dan perintah menampilkan container yang aktif
![](images/20.JPG)
10. curl docker digunakan untuk menampilkan isi yang ada dalam docker berupa html.
![](images/22.JPG)
11. perintah menampilkan service yang berjalan pada http
![](images/23.JPG)
12. perintah menampilkan secara menyeluruh mengenai informasi di service http.
![](images/24.JPG)
13. perintah menampilkan node yang aktif secara mandiri dan menampilkan node aktif dengan ketentuan $(docker node ls -q | head -n1) serta menampilkan isi yang ada dalam docker berupa html.
![](images/25.JPG)
14. perintah membuat service http berjumlah 5 buah.
![](images/27.JPG)
15. perintah menampilkan docker yang aktif.
![](images/28.JPG)

curl docker digunakan untuk menampilkan isi yang ada dalam docker berupa html.
![](images/29.JPG)

 Lakukan pengecekan dengan membuka view http port 80.
![](images/30.JPG)

Masukan port 8080 dan muncul tampilan seperti ini
![](images/31.JPG)



