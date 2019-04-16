# Melakukan clustering menggunakan kubernets.
## Buat account di katacoda dan masuk ke https://www.katacoda.com/courses/kubernetes/getting-started-with-kubeadm
1. Lakukan perintah inisialisasi pada kubeadm.
![](images/1.png)
2. Lakukan perintah join menggunakan token kubeadm pada host 1.
![](images/2.png)
3. melakukan verifiaksi join yang dilakukan kubeadm pada host 2.
![](images/3.png) 
4. perintah mengambil sebuah nodes.
![](images/4.png)
5.  perintah menampilkan isi dari file menggunakan cat pada file /opt/weave-kube.
![](images/5.png)
6. perintah menyetujui isi dari file /opt/weave-kube dan perintah mengambil sebuah pod pada kube-system.
![](images/6.png)
7. perintah membuat deployment pada service http yang mengambil image katacoda/docker-http-server:latest dan melakukan pengambilan sebuah pods.
![](images/7.png)
8. perintah meliha container yang aktif dengan kata kunci docker-http-server.
![](images/8.png)
9. perintah menampilkan isi pada <<EOF | kubectl cretae -f -
![](images/9.png)
10. perintah untuk melihat descripsi pada kubernets.
![](images/10.png)