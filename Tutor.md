# Tutor IDE <--> GITHUB

## Dari project kosong/awal --> Github

### Urutannya:

git init
git remote add origin https://github.com/username/nama-repository.git
git add . // git add nama-file (Jika mau masukin satu perubahan)
git commit -m "Initial commit"
git branch -M main
git push -u origin main

Setelah pertama kali berhasil, berikut jadi seperti ini:

git add . // git add nama-file (Jika mau masukin satu perubahan)
git commit -m "Update project"
git push

## Hapus file di GITHUB

### Urutannya :

Semua file : 
git rm -r .
git commit -m "Remove old project files"
git push

1 file :
rm nama-file-yang-ingin-dihapus

    Kalau Windows dan rm tidak bekerja: 
    del nama-file-yang-ingin-dihapus

git add -A
git commit -m "Remove Project file"