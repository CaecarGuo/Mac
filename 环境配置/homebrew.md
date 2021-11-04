# homebrew

## 什么是homebrew？

软件包管理器，补充苹果上缺失的软件包，源于linux上，可以一条命令安装一个软件。但商业系统并没有，如 Mac, Windows，因此需要安装homebrew来补充

## 为什么要加homebrew？

现在软件的分发有两种方式

- 应用商店，如苹果的 app store
- 命令行来安装的软件，如 homebrew

很多开源免费的软件并不会在app store上登录，因此我们得用一个软件包管理器来进行下载

## 如何下载安装？

https://www.bilibili.com/video/BV1E44y1r7uP

1. 设置使用中科大镜像
`HOMEBREW_CORE_GIT_REMOTE=https://mirrors.ustc.edu.cn/homebrew-core.git`
 
2. 安装homebrew
`/bin/bash -c "$(curl -fsSL https://cdn.jsdelivr.net/gh/ineo6/homebrew-install/install.sh)"`

3. 添加 Homebrew 到 /Users/你的用户名/.zprofile 文件的 PATH 中，执行下面命令即可:

```echo eval $(/opt/homebrew/bin/brew shellenv)  /Users/你的用户名/.zprofile 
eval $(/opt/homebrew/bin/brew shellenv)
```

修改一下试试提交
