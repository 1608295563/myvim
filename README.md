https://blog.csdn.net/u010871058/article/details/54253774
https://github.com/ma6174/vim-deprecated/tree/master/ftplugin/python

# 超强vim配置文件

[![Build Status](https://travis-ci.org/ma6174/vim.png?branch=master)](https://travis-ci.org/ma6174/vim)

### 运行截图

![screenshot.png](screenshot.png)

### 简易安装方法：

打开终端，执行下面的命令就自动安装好了：

`wget -qO- https://raw.githubusercontent.com/1608295563/myvim/master/setup.sh | sh -x`

### 或者自己手动安装：(以ubuntu为例)

1. 安装vim `sudo apt-get install vim`
- 安装ctags：`sudo apt-get install ctags`
- 安装一些必备程序：`sudo apt-get install xclip vim-gnome astyle python-setuptools`
- python代码格式化工具：`sudo easy_install -ZU autopep8`
- `sudo ln -s /usr/bin/ctags /usr/local/bin/ctags`
- clone配置文件：`cd ~/ && git clone git://github.com/ma6174/vim.git`
- `mv ~/vim ~/.vim`
- `mv ~/.vim/.vimrc ~/`
- clone bundle 程序：`git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle`
- 打开vim并执行bundle程序`:BundleInstall`
- 重新打开vim即可看到效果

### 了解更多vim使用的小技巧：

[tips.md](tips.md)

### 查看更新日志：

[`update_log.md`](update_log.md)

打开python文件会提示错误，解决方案如下：
git clone --recursive git://github.com/kevinw/pyflakes-vim.git
cd ./pyflakes-vim/ftplugin
cp -R ./python/  ~/.vim/ftplugin/
参考：https://blog.csdn.net/miaoqiucheng/article/details/80366563

没有安装插件：
https://www.cnblogs.com/xiaxiaosheng/p/3357690.html
