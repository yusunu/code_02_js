# code 2020
## OS/IDE
- Windows 10 & WSL
- Ubuntu 20.04 LTS(from Microsoft Store)
- Visual Studio Code 1.47 for Windows

## Packages
- [x] npm 6.14.4 
- [x] node v10.19.0
- [x] express
- [x] express-generetor
- [ ] mongodb

## Setting
* Changing a remote's URL 日本国内
```sh
sudo sed -i -e 's%http://.*.ubuntu.com%http://ftp.jaist.ac.jp/pub/Linux%g' /etc/apt/sources.list
```
* Updating packages, install something new
```sh
sudo apt update
sudo apt upgrade

sudo apt install -y node npm

npm set init.author.name "Ryu-SeungWoo"
npm set init.author.email "XXXXXXXX@gmail.com"

```
# Nodejs + express
## express-generatorでアプリケーションの雛形の生成

[http://localhost:3000]: # (http://localhost:3000)
1. express-generatorのインストール
2. アプリの生成
3. 依存関係のインストール
4. 起動
```sh
npm i -g express-generator
express -e code_02_js
cd code_02_js && npm install
npm start
```
