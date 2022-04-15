## UTS WEB SERVICE SEMESTER 4
### OLEH :
## NAMA : TRI RIA HANDAYANI
## NIM : 11200484

___

### Soal & Ketentuan : 
#### Membuat restful API dengan ketentuan sebagai berikut :
- Resource minimal 2 dan saling berelasi ada implementasi HATEOAS pada method GET
contoh (mobil dengan merek, buku dengan pengarang, dll )
- Tidak diperkenankan menggunakan database northwind, silahkan usaha sendiri :)
- Terdapat method GET seluruh data dan berdasarkan ID, method POST, PUT, dan DELETE
- Terdapat response kode error dan keterangannya


#### Cara menilaikan :
- Upload kode anda pada social repository seperti : github, gitlab, atau bitbucket. link repositorynya yang dikirim
- Demokan mulai dari GET,POST,PUT, dan DELETE dengan cara merekam dan mengunggah ke youtube. rekaman disertai screen wajah, pada deskripsi video berikan identitas nim dan nama Anda. Selanjutnya link youtube dan link repository kirim ulang ke sini.

### Skor Penilaian :
- Upload program : 50
- Mendemokan dengan video di youtube : 50
___


### Skema Database
#### tb_kategori
```
- id_kategori * Primary, INT, Auto Increment
- nama_kategori VARCHAR
```
#### tb_produk
```
- id_produk * Primary, INT, Auto Increment
- nama_produk VARCHAR
- harga_produk INT
- stok_produk INT
- id_kategori ** Index, INT
```
##### keterangan :
* \* Primary Key
* \*\* Foreign Key
___


### Cara menjalankan?
- Pastikan ```composer``` dan ```local webserver``` (xampp/wampp) sudah terinstal
- Jalankan ```local webserver```
- Buat database baru dengan ```webservice``` lalu import file ```Uts_webserviceHerda.sql``` pada database tersebut
- Jalankan command
- caranya :
- buka pada folder proyek nya
- tekan CTRL + SHIFT + Klik Kanan
- open cmd / powershell here
```
composer install
```
- dan yang terakhir,
```
php -S localhost:8080 -t public
```
- Maka API sudah bisa dijalankan melalui postman
___


### Download [Postman Collection](https://www.getpostman.com/collections/c50b78d49bfec00aaae5).
