

# Setup For Deployment 👇

- FORK THE REPOSITORY [Here](https://github.com/Alinshan/Jarvis-MD2/fork)

## `Scan QR Code For Session`
[![Cheems Bot](https://repl.it/badge/github/quiec/whatsasena)](https://replit.com/@ALINSHAN/Jarvis-Bot-V2-Multi-Device-Qr?output%20only=1&lite=1#index.js)

## `SETTINGS`

- CHANGE OWNER NUMBER VCARD [Here](https://github.com/Alinshan/Jarvis-MD2/blob/master/config.js#L44)
- CHANGE OWNER NUMBER MENU [Here](https://github.com/Alinshan/Jarvis-MD2/blob/master/config.js#L59)
- CHANGE OWNER NUMBER TAG [Here](https://github.com/Alinshan/Jarvis-MD2/blob/master/config.js#L58)
- CHANGE OWNER NAME [Here](https://github.com/Alinshan/Jarvis-MD2/blob/master/config.js#L45)
- CHANGE BOT NAME [Here](https://github.com/Alinshan/Jarvis-MD2/blob/master/config.js#L51)

## ` BUILDPACKS`

```
https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest
https://github.com/clhuang/heroku-buildpack-webp-binaries.git
heroku/nodejs
```

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Alinshan/Jarvis-MD2/)

# Install Manually 👇
## `Requirements`
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://github.com/BtbN/FFmpeg-Builds/releases/download/autobuild-2020-12-08-13-03/ffmpeg-n4.3.1-26-gca55240b8c-win64-gpl-4.3.zip)
* [Libwebp](https://developers.google.com/speed/webp/download)
* Any text editor
## `Clone Repo & Installation dependencies`
```bash
git clone https://github.com/Alinshan/Jarvis-MD2.git
cd Jarvis-MD2

npm start
```
## `For Termux/Ssh/Ubuntu`
```bash
apt update
apt upgrade
pkg update && pkg upgrade
pkg install bash
pkg install libwebp
pkg install git -y
pkg install nodejs -y 
pkg install ffmpeg -y 
pkg install wget
pkg install imagemagick -y
git clone https://github.com/Alinshan/Jarvis-MD2
cd Jarvis-MD2
npm start
```
## `For VPS`
```bash
apt install nodejs 
apt install git 
apt apt install ffmpeg 
apt apt install libwebp 
apt apt install imagrmagick
apt install bash
git clone https://github.com/Alinshan/Jarvis-MD2
cd Jarvis-MD2
npm start
```
## `For 24/7 Activation (Termux)`
```bash
npm i -g pm2 && pm2 start index.js && pm2 save && pm2 logs
```
