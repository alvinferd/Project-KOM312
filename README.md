# ![](webapp/public/favicon-32x32.png) MiniNote
![GitHub package.json version](https://badges.fw-web.space/github/package-json/v/muety/mininote?style=flat-square)
![](https://badges.fw-web.space/github/license/muety/mininote?style=flat-square)
![GitHub code size in bytes](https://badges.fw-web.space/github/languages/code-size/muety/mininote?style=flat-square)
![GitHub last commit](https://badges.fw-web.space/github/last-commit/muety/mininote?style=flat-square)
![Docker Cloud Build Status](https://badges.fw-web.space/docker/cloud/build/n1try/mininote?style=flat-square)
[![](https://badges.fw-web.space/liberapay/receives/muety.svg?logo=liberapay&style=flat-square)](https://liberapay.com/muety/)
[![Say thanks](https://badges.fw-web.space/badge/SayThanks.io-%E2%98%BC-1EAEDB.svg?style=flat-square)](https://saythanks.io/to/n1try)

## Tugas Proyek KOM312 Komunikasi Data dan Jaringan
Referer : https://github.com/muety/mininote

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

A simple, self-hosted Markdown note-taking app built with [Vue 3](https://v3.vuejs.org), and [Express](http://expressjs.com). Check out the **[hosted demo](https://apps.muetsch.io/mininote)**!

![](https://i.imgur.com/Y9TFu6w.png)

[![Buy me a coffee](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://buymeacoff.ee/n1try)


## ⚙️ Requirements
* NodeJS >= `12.19.0 LTS`

## ⌨️ How to run?
```bash
# Clone the repo
$ git clone https://github.com/muety/mininote

# Install backend dependencies
$ yarn

# Install frontend dependencies and build
$ cd webapp && yarn && yarn build && cd ..

# Run
$ yarn start
```

## 🐳 How to run with Docker?
```bash
# Create a persistent volume
$ docker volume create mininote-data

# Run the container
$ docker run -d -p 3000:3000 -v mininote-data:/app/data --name mininote n1try/mininote
```

## 🔒 Use HTTPS for backend
1. Open `config.js`
2. Edit the `HTTPS_KEY` and `HTTPS_CERT` field, and insert the file locations at which your private key and site certifications are stored.
3. Launch the backend server
-> To switch back to the HTTP server, nullify either field and relaunch again.

## ☑️ Todo
This project is still under development. The following features are about to be implemented. Feel free to contribute.
* Tests
* Improved data validation
* More REST
* Ability to rename notebooks and notes

## 🧑‍💻 Contributing
Feel free to contribute! All contributions that add value to the project are welcome. However, please be aware that you are not done after having opened a PR. In order to keep quality high, it is expected that you implement change requests and react to comments within an adequate time, until your code is merged. Otherwise your PRs will be closed after a while, sorry!

## 📓 License
MIT @ [Ferdinand Mütsch](https://muetsch.io)



