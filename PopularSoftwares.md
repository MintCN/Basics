#常用软件列表

#网络应用

## 网络浏览器

### Chrome：可能是世界上最好的浏览器

**介绍** : Google Chrome，又称Google浏览器，是一个由Google（谷歌）公司开发的网页浏览器。该浏览器是基于其他开源软件所撰写，包括WebKit，目标是提升稳定性、速度和安全性，并创造出简单且有效率的使用者界面。

**下载位置** :

[Download](http://www.google.cn/intl/zh-CN/chrome/browser/)

**安装方法** :

    wget -q -O - https://dl-ssl.google.com/linux/linux_signing_key.pub | sudo apt-key add -
    sudo sh -c 'echo "deb http://dl.google.com/linux/chrome/deb/ stable main" >> /etc/apt/sources.list.d/google.list'
    sudo apt-get update
    sudo apt-get install google-chrome-stable

### Firefox：自由、拓展性强大的浏览器

**介绍** : Mozilla Firefox，中文俗称“火狐”（正式缩写为Fx或fx，非正式缩写为FF），是一个自由及开放源代码网页浏览器，使用Gecko排版引擎，支持多种操作系统，如Windows、Mac OS X及GNU/Linux等。

**下载位置** :

[Download](http://www.firefox.com.cn/download/)

[PPA ubuntu-mozilla-daily](https://code.launchpad.net/~ubuntu-mozilla-daily/+archive/ubuntu/ppa)

**安装方法** :

    # Firefox
    sudo apt-get install firefox firefox-locale-zh-hans

    # Firefox PPA
    sudo add-apt-repository ppa:ubuntu-mozilla-daily/ppa
    sudo apt-get update
    sudo apt-get install firefox-trunk

### Chromium：Chrome浏览器的开源版本

**介绍** : Chromium 是 Google 的chrome浏览器背后的引擎，其目的是为了创建一个安全、稳定和快速的通用浏览器。Chromium是一个由Google主导开发的网页浏览器。以BSD许可证等多重自由版权发行并开放源代码。

**下载位置** :

[Download](http://www.chromium.org/getting-involved/download-chromium)

[PPA chromium-daily](https://launchpad.net/~chromium-daily/+archive/ubuntu/stable)

**安装方法** :

    # Chromium
    sudo apt-get install chromium

    # Chromium PPA
    sudo add-apt-repository  ppa:chromium-daily/stable  #
    sudo apt-get update
    sudo apt-get install chromium-browser

### Maxthon：功能丰富、界面简洁的浏览器

**介绍** : 傲游浏览器集成了傲游账户、收藏和智能填表同步、快速访问、鼠标手势、超级拖拽、上次未关闭、自动更新等实用功能，基于Chromium开发，带来全平台的统一体验。

**下载位置** :

[Download](http://www.maxthon.cn/)

**安装方法** :

    sudo gdebi maxthon-browser-stable_1.0.5.3_amd64.deb

### Opera：来自挪威的浏览器

**介绍** : Opera浏览器，是一款挪威Opera Software ASA公司制作的支持多页面标签式浏览的网络浏览器，是跨平台浏览器可以在Windows、Mac和Linux三个操作系统平台上运行。

**下载位置** :

[Download](http://www.opera.com/computer/linux)

**安装方法** :

	sudo add-apt-repository 'deb https://deb.opera.com/opera-stable/ stable non-free'
    wget -qO- https://deb.opera.com/archive.key | sudo apt-key add -
    sudo apt-get update
	sudo apt-get install opera-stable


## 邮件客户端

## 即时聊天

## 文件传输

## 云存储

##网络支付

## 视频软件

# 图像影音

## 音乐播放

## 视频播放

## 图像浏览

# 游戏娱乐

## 游戏平台

# 文件管理

## 文件管理

## 压缩打包

# 办公应用

## 输入法

## 文档阅读

## 办公套件

## 笔记记事

# 教育科学

## 教育软件

## 科学软件

# 虚拟化

## 虚拟机

# 监视和控制

## 硬件查询

## 系统监视

## 系统安全

## 远程控制

# 系统工具

## Shell

# 程序开发

## 版本控制

## 本文编辑器

## 集成开发环境
