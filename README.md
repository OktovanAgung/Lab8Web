| Nama  | Oktovan Agung Shailendra|
|-------|-------------------------|
|NIM    |: 312010131              |
|Kelas  |: TI.20.A.1              |

---

# Praktikum 8 : PHP & Database MySQL

# Langkah - Langkah Praktikum
## Persiapan
- Untuk memulai membuat aplikasi CRUD sederhana, yang perlu disiapkan adallah database server menggunakan MySQL. Pastikan MySQL Server sudah dapat dijalankan melalui XAMPP.

## Menjalankan MySQL Server
Untuk menjalankan MySQL Server dari menu XAMPP Control.
![img](img/startxampp.png)

## Mengakses MySQL Client menggunakan PHP MyAdmin
Pastikan webserver Apache & MySQL server sudah dijalankan. Kemudian buka melalui browser `http://localhost/phpmyadmin/`.

## Membuat Database : Studi Kasus Data Barang
![img](img/contohdatabase.png)

## Membuat Database
![img](img/creatdatabase.png)

## Membuat Tabel
![img](img/creattable.png)

## Menambahkan Data
![img](img/inserttable.png)

## Membuat Program CRUD
Buat folder `lab8_php_database` pada root directory web server (c:\xampp\htdocs)
![img](img/lab8database.png)
Kemudian untuk mengakses directory tersebut pada web server dengan mengakses URL : `http://localhost/lab8_php_database/`
![img](img/webserverlab8.png)

## Membuat File Koneksi Database
Buat file baru dengan nama **Koneksi.php**. Lalu buka melalui browser untukmenguji database, untuk menyampaikan pesan koneksi berhasil,  *uncomment* pada perintah `echo "koneksi berhasil";
![img](img/filekoneksiphp.png)

## Membuat File Index Untuk Menampilkan Data(*Read*)
Buat file baru dengan nama **index.php**
![img](img/coderead.png)
![img](img/tampilanread.png)

## Menambahkan Data (*Create*)
Buat file baru dengan nama **tambah.php**
![img](img/codecreate.png)
![img](img/tampilancreate.png)

## Mengubah Data (*Update*)
Buat file baru dengan nama **ubah.php**
![img](img/codeupdate.png)
![img](img/tampilanupdate.png)

## Menghapus Data (*Delete*)
Buat file baru dengan nama **hapus.php**
![img](img/codedelete.png)
