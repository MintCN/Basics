#常用软件列表

#网络应用

## 网络浏览器

### Chrome

**介绍**：可能是世界上最好的浏览器

**下载位置** :

[Download](http://www.google.cn/intl/zh-CN/chrome/browser/)

**安装方法**：

    wget -q -O - https://dl-ssl.google.com/linux/linux_signing_key.pub | sudo apt-key add -
    sudo sh -c 'echo "deb http://dl.google.com/linux/chrome/deb/ stable main" >> /etc/apt/sources.list.d/google.list'
    sudo apt-get update
    sudo apt-get install google-chrome-stable

**卸载方法**：

    sudo apt-get purge google-chrome-stable
    sudo rm -rf /etc/apt/sources.list.d/google.list'

### Firefox

**介绍**：自由、拓展性强大的浏览器

**下载位置** :

[Download](http://www.firefox.com.cn/download/)

[PPA ubuntu-mozilla-daily](https://code.launchpad.net/~ubuntu-mozilla-daily/+archive/ubuntu/ppa)

**安装方法** :

    # 1. Firefox
    sudo apt-get install firefox firefox-locale-zh-hans

    # 2. Firefox PPA
    sudo add-apt-repository ppa:ubuntu-mozilla-daily/ppa
    sudo apt-get update
    sudo apt-get install firefox-trunk

**卸载方法**：

    # 1. Firefox
    sudo apt-get purge firefox firefox-locale-zh-hans

    # 2. Firefox PPA
    sudo add-apt-repository -r ppa:ubuntu-mozilla-daily/ppa
    sudo apt-get update

### Chromium

**介绍**：Chrome浏览器的开源版本

**下载位置** :

[Download](http://www.chromium.org/getting-involved/download-chromium)

[PPA chromium-daily](https://launchpad.net/~chromium-daily/+archive/ubuntu/stable)

**安装方法** :

    # 1. Chromium
    sudo apt-get install chromium

    # 2. Chromium PPA
    sudo add-apt-repository  ppa:chromium-daily/stable  #
    sudo apt-get update
    sudo apt-get install chromium-browser

**卸载方法**：

    # 1. Chromium
    sudo apt-get purge chromium

    # 2. Chromium PPA
    sudo add-apt-repository -r ppa:chromium-daily/stable  #
    sudo apt-get update

### Maxthon

**介绍** : 功能丰富、界面简洁的浏览器

**下载位置** :

[Download](http://www.maxthon.cn/)

**安装方法** :

    sudo gdebi maxthon-browser-stable_1.0.5.3_amd64.deb

**卸载方法**：

    sudo dpkg -r maxthon-browser-stable

### Opera

**介绍** : 来自挪威的浏览器

**下载位置** :

[Download](http://www.opera.com/computer/linux)

**安装方法** :

	# 1. Add source in /etc/apt/sources.list
	sudo add-apt-repository 'deb https://deb.opera.com/opera-stable/ stable non-free'
    wget -qO- https://deb.opera.com/archive.key | sudo apt-key add -
    sudo apt-get update
	sudo apt-get install opera-stable

	# 2. Add source in /etc/apt/sources.list.d/opera.list
    sudo sh -c 'echo "deb https://deb.opera.com/opera-stable/ stable non-free" >> /etc/apt/sources.list.d/opera.list'
    wget -qO- https://deb.opera.com/archive.key | sudo apt-key add -
    sudo apt-get update
	sudo apt-get install opera-stable

**卸载方法**：

    # 1. Add source in /etc/apt/sources.list
	sudo apt-get purge opera-stable
	sudo add-apt-repository -r 'deb https://deb.opera.com/opera-stable/ stable non-free'
    sudo apt-get update


	# 2. Add source in /etc/apt/sources.list.d/opera.list
	sudo apt-get purge opera-stable
    sudo rm -rf /etc/apt/sources.list.d/opera.list
    sudo apt-get update

## 邮件客户端

### Thunderbird

**介绍** : 专注于电子邮件管理的强大邮件客户端

**下载位置** :
[Download](https://www.mozilla.org/zh-CN/thunderbird/)

**安装方法** :

    # 1. Thunderbird
    sudo apt-get install thunderbird

    # 2. Thunderbird PPA
    sudo add-apt-repository ppa:ubuntu-mozilla-daily/ppa
    sudo apt-get update
    sudo apt-get install thunderbird-trunk

**卸载方法**：

    # 1. Thunderbird
    sudo apt-get purge thunderbird

    # 2. Thunderbird PPA
    sudo add-apt-repository -r ppa:ubuntu-mozilla-daily/ppa
    sudo apt-get update

### Evolution

**介绍** : 提供邮件收发、日历和通讯录的个人信息解决方案

**下载位置** :

[Download](https://wiki.gnome.org/Apps/Evolution)

**安装方法** :

    sudo apt-get install evolution

**卸载方法**：

    sudo apt-get purge evolution

### Mutt

**介绍** : 类Unix系统下基于文本的邮件客户端

**下载位置** :

[Download](http://www.mutt.org/)

**安装方法** :

    sudo apt-get install mutt

**卸载方法**：

    sudo apt-get install mutt

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
