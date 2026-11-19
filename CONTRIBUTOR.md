# Panduan Kontribusi Untuk Pengembang

> **Berisi panduan singkat untuk bekerja di repository ini.**

## 1. Konfigurasi Git:
Jika belum menyambungkan Git dan Github, buka dan ikuti panduan resmi [Set Up Git](https://docs.github.com/en/get-started/git-basics/set-up-git) .

## 2. Menyalin Repo:
a) Buka terminal atau cmd dan pilih direktori, contoh:
```cmd
cd D:\Users\Nama_User\Documents
```

b) Copy link repository
```text
https://github.com/CloudyPr/Calendar-project.git
```

c) lalu ketik dan enter
```cmd
git clone https://github.com/CloudyPr/Calendar-project.git
```

## 3. Mengedit kode:
a) Buka IDE pilihan Anda (VSCode, Intellij, atau NetBeans).

b) Pilih **Open Project**, lalu pilih direktori dan nama-repo sebelumnya.

c) Lakukan perubahan pada kode dan simpan (**Save**)

## 4. Commit dan Push

Buka cmd dan pilih direktori project seperti sebelumnya.

a) Masuk ke folder project:
```cmd
cd nama-repo
```
b) Pilih branch (Opsional)
```cmd
git branch
git switch main
```
c) Tambahkan semua perubahan:
```cmd
git add .
```
d) Simpan perubahan dengan nama commit yang jelas:
```cmd
git commit -m "nama commit"
```
e) Unggah (push) perubahan ke repository GitHub:
```cmd
git push origin main
```
*main bisa diganti dengan nama branch*

---

Selamat! Anda sudah berhasil melakukan sebuah kontribusi di repository ini.
