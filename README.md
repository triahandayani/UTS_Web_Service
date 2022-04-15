## UTS WEB SERVICE SEMESTER 4
### Disusun Oleh :
## Nama : TRI RIA HANDAYANI
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

### Skema Database
#### tb_kategori
```
- id_kategori 
- nama_kategori 
```
#### tb_produk
```
- id_produk * Primary, INT, Auto Increment
- nama_produk 
- harga_produk 
- stok_produk 
- id_kategori 
```
##### keterangan :
* \* Primary Key
* \*\* Foreign Key
___

