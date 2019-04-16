# Mendeploy Aplikasi dengan menggunakan docker compose
## langkah pertama buat account di katacoda  dan masuk ke https://www.katacoda.com/courses/docker/11
1. Buat file docker-compose.yaml dengan menggunakan editor vim
![](images/11.1.png)
keterangan : 
- web : mendefinisikan nama web yang dibuat.
- build : mendefinisikan semua app yang dideploy dimana terdapat links mengambil image redis pada ports 3000 dan 8000.
- redis : mengambil image redis dengan bentuk alpine dengan volumes atau tempat penyimpanan pada /var/redis/data:/data.
2. lakukan perintah docker-compose up -d atau untuk membuat agar semua saling terhubung.
![](images/11.2.png)
3. lakukan docker-compose ps untuk melihat apakah sudah muncul sebuah container atau belum.
![](images/11.3.png)
4. docker-compose logs digunakan untuk melihat logs yang ada dalam docker-compose
![](images/11.4.png)
5. docker-compose scale web=3 digunakan untuk membuat web yang semula 1 menjadi 3 atau ditambah 2 web.
![](images/11.5.png)
6. docker-compose scale web=1 digunakan untuk membuat web yang semula 3 menjadi 1 atau dihapus 2 web.
![](images/11.6.png)
7. docker-compose stop untuk menghentikan service docker-compose.
![](images/11.7.png)
8. docker-compose rm untuk menghapus docker-compose
![](images/11.8.png)