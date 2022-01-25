---
title: Hosting Gratis mdbgo/cli
date: 2021-11-11 15:38:34
tags: 
- Hosting
- Termux
- CLI
categories: 
- Tutorial
cover: https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSvaj9179AoOq0cD8et_ZpimP78qlNMIxct4g&usqp=CAU
featured: true
---

Salam pecinta gratisan, bagi kalian yang ingin mencari hosting gratis, [MdbGo](https://mdbgo.com) bisa menjadi salah satu alternatif untuk kalian yang ingin meng-Host web pribadi ataupun project kalian. 
<!-- more -->
# Apa itu MdbGo?
MdbGo adalah adalah Deployment Tools, berbasis Open-Source, dan berikut apasaja yang kalian dapatkan ketika menggunakan MdbGo:
* Hosting Gratis
* Subdomain 
* Support Custom domain Pribadi
* Free SSL subdomain maupun custom domain
* Git Repo & Collabs
* Template & Integrasi Backend yang telah di tentukan.
* Wordpress
  * Ecommerce
  * Blog
  * MDB Starter
  * Empty Starter
* Frontend
  * MDB
  * jQuery
  * Angular
  * React
  * Vue
  * Static Html App

* Backend
  * Node.js
  * Npm / Yarn
  * PHP
  * Laravel
* DataBase
  * MongoDB
  * MySQL

# Persiapan Instalasi
Ada 2 cara menggunakan **mdbGo**, bisa langsung ke 
website ataupun dengan cli, Namun saya 
rekomendasikan menggunakan **CLI**, karna meskipun 
bisa lewat websitenya, tetap saja kita membutuhkan cli untuk edit file, ataupun publish website yang akan kita buat nantinya. 
Berikut selengkapnya:
### Install NodeJS&Yarn
```bash
~$ apt install nodejs yarn -y
```
### Install mdbgo/cli
```bash
	# Menggunakan Yarn
	~$ yarn global add mdb-cli
	
	# Menggunakan NPM
	~$ npm install mdb-cli -g
```
# Daftar akun MdbGo
```bash
	~$ mdb register
```
Kemudian kita disuruh mengisi **nama, username, email, dan password** Silahkan isi sesuai keinginan dan email masing2. jika sukses mendaftar akun, akan tampil sebagai berikut. 
![Register](/images/register.jpg)

# Login akun MdbGo
Login mdbgo dengan perintah:
```bash
~$ mdb login
```
Masukkan **username & password** yang kalian buat barusan, jika sukses akan tampil seperti ini.
![Login](/images/login.jpg)

# Buat Proyek
```bash
~$ mdb init
```
Karna disini hanya tutorial basic, kita pilih saja **MDB5 Free Standart**
# Publish Proyek
```bash
~$ cd mdb5-free-standard
# edit file kalian disini
# Jika sudah kita publish
~$ mdb publish
```
![publish](/images/publish.jpg)
Sampai disini bisa kita lihat lognya 
```
✔ Uploading files | 1.446 Mb
Sent 1.446 Mb
Your application is available at https://sertutoruser-mdb5-free-standard.mdbgo.io

Info Your URL has been generated based on your username and project name. You can change it by providing the (sub)domain of your choice by running the following command: `mdb config domain <name>`.
```
Menandakan kita sukses mempublish Aplikasi web static berisi konten standard mdb5-free. Untuk memastikan bisa kunjungi url masing masing nantinya. 

# Akhir kata 
Cukup disini dulu tutorial kali ini, untuk tutorial custom Domain nanti akan saya buat tutorialnya di postingan mendatang.

Mohon kritik dan saran bisa komen dibawah atau via [Facebook](https://facebook.com/serlink.my.id)
