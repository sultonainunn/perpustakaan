# Perpustakaan

Buat Program Perpustakaan peminjaman buku dengan struktur database seperti di github 

berikan komentar setiap fitur pada program

contoh:
```
//nama yang membuat - menampilkan data dari table

mysqli_query($db,"SELECT * table");
```


---------------------------
Actors :
1. Admin
  - Mengelola semua fitur (crud)
  
2. Petugas
  - Crud siswa
  - Proses Peminjaman
  - Proses Pengembalian
  - CRUD Peminjaman & Pengembalian (History Peminjaman)
  - CRUD Buku
  
3. Siswa
  - Melihat history peminjaman dari siswa tersebut
  - Melihat Buku
  
Alur :
> Sebagai Admin bisa mengelola semua data yang ada di Database.
  
> Sebagai Petugas (proses peminjaman) melayani peminjaman siswa,Siswa akan meminjam buku apa? lalu petugas menginputkan data buku yang akan di pinjam, lalu petugas memberikan bukti peminjaman kepada siswa. (proses pengembalian) Petugas mengecek id dari pengembalian siswa apakah siswa mengembalikan nya terlambat atau tidak jika terlambat maka akan menampilkan denda. dan menginputkan data pengembalian siswa tersebut.
    
> Sebagai Siswa hanya bisa melihat list buku,dan history peminjaman
  
  
  
  
## Jika kurang paham silahkan bertanya
