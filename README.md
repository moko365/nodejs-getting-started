# NodeJS Getting Started - NodeJS 入門


## 準備開發環境

* 安裝 NodeJS 在 Windows 上
* 安裝 NodeJS 在 Ubuntu Linux 上 使用 apt-get 套件管理

```
sudo apt-get update
sudo apt-get install python-software-properties python g++ make
sudo add-apt-repository ppa:chris-lea/node.js
sudo apt-get update
sudo apt-get install nodejs
```

* 安裝 NodeJS 在 Mac 上

```
brew install nodejs
```

## 工具介紹

* NPM (Node Package Manager) 介紹 ( https://npmjs.org/ )
* NVM (Node Version Manager) 介紹 ( https://github.com/creationix/nvm )

```
curl https://raw.github.com/creationix/nvm/master/install.sh | sh
nvm install 0.10
nvm use 0.10
nvm run 0.10
nvm ls
nvm deactivate
```

* REPL

## 開始寫 NodeJS 程式

* Run first NodeJS application (hello.js)
* Build a simple Web server with http module. (server.js)
* Route url requests with url module. (server-route.js)
* Handle URL parameters with query string module. (server-qs.js)
* Serve static file on web server with File System module. (server-fs.js)

# 課程大綱

| Session | Topic | Instructor | Filename | Duration |
|:-----|:------|:----------|:---------------|:-----|
| 1.1 | NodeJS 安裝教學: Mac | Hank | 100P0101_InstallNodeMac | 00:47
| 1.2 | NodeJS 安裝教學: Ubuntu | Hank | 100P0102_InstallNodeUbuntu | 02:13
| 1.3 | NodeJS 安裝教學: Windows | Hank | 100P0103_InstallNodeWindows | 00:43
| 1.4 | 認識 NPM 套件管理工具 | Hank | 100P0104_NpmIntro | 01:30
| 1.5 | 認識 NVM 多版本 Node 管理工具 | Hank | 100P0105_NvmIntro | 02:07
| 1.6 | 認識 REPL 命令列工具| Hank | 100P0106_ReplIntro | 01:56
| 1.7 | 我的第一個 NodeJS 程式| Hank | 100P0107_NodeHelloWorld | 00:57
| 1.8 | NodeJS 概念與使用時機 | Jollen | 100P0108_WhyNodejs | 04:54
| 1.9 | 撰寫 HTTP Server 程式| Hank | 100P0109_BuildHttpServer | 03:53