# ![](webapp/public/favicon-32x32.png) MiniNote
![GitHub package.json version](https://badges.fw-web.space/github/package-json/v/muety/mininote?style=flat-square)
![](https://badges.fw-web.space/github/license/muety/mininote?style=flat-square)
![GitHub code size in bytes](https://badges.fw-web.space/github/languages/code-size/muety/mininote?style=flat-square)
![GitHub last commit](https://badges.fw-web.space/github/last-commit/muety/mininote?style=flat-square)
![Docker Cloud Build Status](https://badges.fw-web.space/docker/cloud/build/n1try/mininote?style=flat-square)
[![](https://badges.fw-web.space/liberapay/receives/muety.svg?logo=liberapay&style=flat-square)](https://liberapay.com/muety/)
[![Say thanks](https://badges.fw-web.space/badge/SayThanks.io-%E2%98%BC-1EAEDB.svg?style=flat-square)](https://saythanks.io/to/n1try)

## Tugas Proyek KOM312 Komunikasi Data dan Jaringan
Repositori orisinil : https://github.com/muety/mininote

## Anggota
<table>
    <thead>
        <tr>
            <th></th>
            <th>Nama</th>
            <th>Nim</th>
            <th>Role</th>
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

## ⚙️ Pre-Install Requirements
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
_semua versi yang dicantumkan adalah berdasarkan versi yang kami gunakan_
<br><br>
## Install && Build
```
# **Clone Repositori orisinilnya**
$ git clone https://github.com/muety/mininote

# Install backend dependencies
$ yarn

# Install frontend dependencies and build
$ cd webapp && yarn && yarn build && cd ..
```
<br><br>
## Running the App
Pastikan anda sudah berada pada directory aplikasi
```
$ cd mininote
$ yarn start
```
**Menjalankan aplikasi menggunakan docker <br>**
```
$ docker volume create mininote-data
$ docker run -d -p 3000:3000 -v mininote-data:/app/data --name mininote n1try/mininote
```

## 🔒 Use HTTPS for backend
1. Open `config.js`
2. Edit the `HTTPS_KEY` and `HTTPS_CERT` field, and insert the file locations at which your private key and site certifications are stored.
3. Launch the backend server
-> To switch back to the HTTP server, nullify either field and relaunch again.

## 📓 License
MIT @ [Ferdinand Mütsch](https://muetsch.io)
