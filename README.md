<h1 align="center">GINGERBOT MD<br></h1>






# Setup For Deployment 👇

## `SETTINGS`

-open config.json and edit all your info

## ` BUILDPACKS`

```
https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest
https://github.com/clhuang/heroku-buildpack-webp-binaries.git
https://github.com/DuckyTeam/heroku-buildpack-imagemagick
heroku/nodejs
```

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/GingerBreadSketchy/GingerBotMD)

# Install Manually 👇
## `Requirements`
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://github.com/BtbN/FFmpeg-Builds/releases/download/autobuild-2020-12-08-13-03/ffmpeg-n4.3.1-26-gca55240b8c-win64-gpl-4.3.zip)
* [Libwebp](https://developers.google.com/speed/webp/download)
* Any text editor
## `Clone Repo & Installation dependencies`
```bash
git clone https://github.com/GingerBreadSketchy/GingerBotMD.git
cd GingerBotMD
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
git clone https://github.com/GingerBreadSketchy/GingerBotMD
cd GingerBotMD
npm start
```
## `For VPS`
```bash
apt install nodejs 
apt install git 
apt apt install ffmpeg 
apt apt install libwebp 
apt apt install imagemagick
apt install bash
git clone https://github.com/GingerBreadSketchy/GingerBotMD
cd GingerBotMD
npm start
```
## `For 24/7 Activation`
```bash
npm i -g pm2 && pm2 start index.js && pm2 save && pm2 logs
```
