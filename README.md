
 <div align="center">
  <h1>GINGERBOT MD</h1>
</div>
<div align="center">
  <img src="https://telegra.ph/file/21c73425e6700f5735ff6.png" />
  <p align="center">
<a href="#"><img title="White" src="https://img.shields.io/badge/SKETCHY PUBLIC-blue?colorA=%23ff0000&colorB=%23017e40&style=for-the-badge"></a>
</p>
  <p align="center">
<a href="https://github.com/GingerBreadSketchy"><img title="White Dragon" src="https://img.shields.io/badge/Created💥by💥 GINGER-dqz/JulieMwol?color=red&style=for-the-badge&logo=whatsapp"></a>
</p>
</div>
<p align="center">        



## BEFORE SETUP PLEASE FORK THIS REPOSITORY ##


# Setup For Deployment 👇

## SCAN QR Using Your Whatsapp Via Linked Devices

[![Run on Repl.it](https://repl.it/badge/github/quiec/whatsAlfa)](https://replit.com/@nexusNw/Md-Scanner?outputonly=1&lite=1)

```
1-After scanning a file will be sent on your whatsapp named session.json and save it. 
2- You should Fork this repository and upload the file on your new repository
```

## `SETTINGS`

open setting.json and edit all your info

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
