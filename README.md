
<h1 align="center">
  Belajar Github/Version Control System
</h1>

<p align="center">
  <a href="#apa-itu-git">Apa itu Git?</a> 
  • <a href="#forking">Forking</a> 
</p>

<p>
 Referensi: Youtube Sandhika - Galih
- <a href="https://git-scm.com/book/en/v2"> Klik link untuk akses Ebook</a> 
</p>



## 1. Apa itu git?

Version Control System: 
Sistem yang menyimpan & mengelola rekaman perubhan dari source code

Istilah Git:
* repository : Folder Project
* commit : Pesan rekaman perubahan
* Hash : Penanda unik pada sebuah commit
* checkout : Berpindah ke sebuah commit
* branch : cabang bebas dari sebuah commit
* merge : menggabungkan branch
* remote : sumber yang memiliki repo
* clone : mengambil repo dari remote
* push : mengirimkan commit ke repo
* pull : mengambil commit dari repo

> **Referensi**
> https://www.youtube.com/watch?v=lTMZxWMjXQU&list=PLFIM0718LjIVknj6sgsSceMqlq242-jNf

## 2. Forking

Menduplikat Repository seseorang beserta semua history tanpa menggangu repository aslinya namun ditambahkan credits.
- Fork != Clone

## 3. Git Command


<h4 font="bold" >Menginisialisasikan repository git</h4>

```
git init
```

<h4 font="bold">Menambahkan file di stagging area</h4>

```
git add <nama file> or git add .
```

<h4 font="bold">Melihat status perubahan didalamm repository</h4>

```
git status
```

<h4 font="bold">Memberikan pesan perubahan</h4>

```
git commit -m 'Pesan Perubahan'
```

<h4 font="bold">Melihat history commit</h4>

```
git log -3
```

<h4 font="bold">Kembali ke keadaan tertentu / Mengembalikan file yang telah dihapus di commit tertentu</h4>

```
git checkout 5digit-commit  -- nama file
```

<h4 font="bold">Memasukkan configurasi kedalam git</h4>

```
git config
```

<h4 font="bold">Membuat branch baru</h4>

```
git branch
```

<h4 font="bold">Bantuan mengenai suatu perintah</h4>

```
git help
```






