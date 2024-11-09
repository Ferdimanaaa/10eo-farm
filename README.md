# TENEO AUTO FARMING POINT WITH VPS
## Fitur Bot
- **Login**
- **AutoLogin**
- **Auto Ping (setiap 15 menit)**
- **Support Proxy**
## Register Teneo
- **Download [Ekstension](https://chromewebstore.google.com/detail/teneo-community-node/emcclcoaglgcpoognfiggmhnhgabppkm)**
- **Open Ektension**
- **Create Account with email & verif email**
- **Submit Code `3s04Z` (get 2500 point)**
- **Done Run Node with VPS**
## Install Node JS & Install Screen (jika belum punya)
```
sudo apt update && sudo apt upgrade -y
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.0/install.sh | bash
```
```
nvm install 22
```
```
apt-get install screen
```
```
ufw allow ssh
ufw enable
ufw status
```
## Download Repository & Install Modules
```
git clone https://github.com/Ferdimanaaa/10eo-farm.git
```
```
cd 10eo-farm
```
```
npm install
```
## Run Bot on VPS
```
screen -S teneo
```
```
node main.js
```
