
<h1 align="center">
  Belajar Github/Version Control System
</h1>


<p>
 Referensi: Youtube Sandhika - Galih
</p>
* <a href="https://git-scm.com/book/en/v2"> Klik link untuk akses Ebook</a> 
* <a href="https://cs.fyi/guide/git-cheatsheet">Cheatseet</a> 



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
git commit -am 'Pesan Perubahan' // add + commit ke file modified
```


<h4 font="bold">Melihat history commit</h4>

```
git log -3
git log --all --decorate --oneline --graph //log dengan graphic
```

<h4 font="bold">Kembali ke keadaan tertentu / Mengembalikan file yang telah dihapus di commit tertentu</h4>

```
git checkout namabranch //Pindah ke branch tertentu
git checkout 5digit-commit  -- namafile
```

<h4 font="bold">Memasukkan configurasi kedalam git</h4>

```
git config
```

<h4 font="bold">Membuat branch baru</h4>

```
git branch namabranch
git branch -d namabranch //delete
```

<h4 font="bold">Alias hanya untuk 1 sesi</h4>

```
alias namaalias="command yang ingin dibuat alias"
```

<h4 font="bold">Bantuan mengenai suatu perintah</h4>

```
git help
```

## 4. Tips

- Dalam Membuat suatu project disarankan untuk membuat BRANCH baru untuk suatu fitur, lalu lakukan MERGE ke branch utama
```
git checkout master/main
git merge feature
```

- Jika terjadi conflict pada saat merge, Perbaiki CONFLICT lalu git add + commit

- Jika ingin kembali ke commit tertentu lakukan ini: 
```
git checkout 7digit-commit 
git branch namabrach
git checkout namabrach
```


