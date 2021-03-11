# ![](webapp/public/favicon-32x32.png) MiniNote
![GitHub package.json version](https://badges.fw-web.space/github/package-json/v/muety/mininote?style=flat-square)
![](https://badges.fw-web.space/github/license/muety/mininote?style=flat-square)
![Docker Cloud Build Status](https://badges.fw-web.space/docker/cloud/build/n1try/mininote?style=flat-square)
[![Say thanks](https://badges.fw-web.space/badge/SayThanks.io-%E2%98%BC-1EAEDB.svg?style=flat-square)](https://saythanks.io/to/n1try)<br>
Original Repository : https://github.com/muety/mininote
<br>
## Laporan Proyek Akhir KOM312 Komunikasi Data dan Jaringan

## Anggota
<table>
    <thead>
        <tr>
            <th></th>
            <th>Nama</th>
            <th>Nim</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>Rafael Tektano Grandiawan Eknanda</td>
            <td>G64180001</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Bintang Fikriguska</td>
            <td>G64180024</td>
        </tr>
        <tr>
            <td>3</td>
            <td>Alvin Ferdiansyah</td>
            <td>G64180079</td>
        </tr>
        <tr>
            <td>3</td>
            <td>Muhammad Hafizhan</td>
            <td>G64180100</td>
        </tr>
</tbody>
</table>

---

## Deskripsi Aplikasi
blablabalbla
blablablabla
blabla
---
<br>

## ⚙️ Pre-Install Requirements
Terdapat beberapa requirements yang akan kita gunakan untuk melakukan install dan build pada aplikasi. Untuk itu, kita harus memastikan semua requirements dibawah ini terinstall dengan benar. Beberapa requirement memiliki minimal versi yang _capable_ untuk digunakan. Namun di bawah ini adalah versi dari requirement yang kami install dan gunakan.<br><br>

 **NodeJS v14.16.0**
```
$ cd ~
$ curl -sL https://deb.nodesource.com/setup_10.x -o nodesource_setup.sh
$ sudo bash nodesource_setup.sh
$ sudo apt install nodejs
```

**Yarn 1.22.5**
```
$ curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
$ echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
$ sudo apt update
$ sudo apt remove cmdtest
$ sudo apt install yarn
```

**npm 6.14.11**
```
$ sudo npm install
```
---

<br><br>
## ⚙️Install && Build
```
# **Clone Repositori orisinilnya**
$ git clone https://github.com/muety/mininote

# Install backend dependencies
$ yarn

# Install frontend dependencies and build
$ cd webapp && yarn && yarn build && cd ..
```
---
<br><br>
## ⌨️ Running the App
Pastikan anda sudah berada pada directory aplikasi, dan seluruh installan beserta pre-install requirement sudah terpenuhi. Apabila aplikasi diinstall pada local computer, secara default akan dijalankan pada port : 3000. <br>
Sehingga kita dapat mengakses aplikasi pada localhost:3000 <br>
```
$ cd mininote
$ yarn start
```
**Menjalankan aplikasi menggunakan docker <br>**
Alternatif cara lain menjalankan aplikasi adalah dengan menggunakan docker. Docker sendiri merupakan ... <br>Keuntungan Menggunakan Docker ... <br><br>
* _Install && Build Docker :_
```
something
```
* _Menjalankan Aplikasi_
---

<br><br>
## 🔒 Setup HTTPS pada backend
blablabla
---

<br><br>
## 📓 License
MIT @ [Ferdinand Mütsch](https://muetsch.io)
