---
isChild: true
anchor: mac_setup
---

## Mac Setup  {#mac_setup_title}

OS X 操作系统内置了PHP。Mountain：5.3.10；Mavericks：5.4.17；Yosemite：5.5.9。

OS X 操作系统其他安装方式：

### Homebrew安装

[Homebrew](http://brew.sh/)是OSX下的一个给力的包管理器，可以方便安装PHP和其他的拓展。[Homebrew PHP]是GITHUB上的资源库。

可以通过`brew install`命令安装`php53`,`php54`,`php55`,`php56`，通过修改`PATH`变量来切换默认的PHP。

### phpbrew安装

[phpbrew]为一个可以管理多个PHP版本的工具。使用环境为：本地上的应用需要两个不同版本，而且没有使用虚拟机。

### 编译源码

按照这个教程：[compile it yourself][mac-compile]来本地编译。前提是：["Command Line Tools for XCode"] 这个需要安装下。

### 捆绑安装器

OS X 系统下提供了一些安装器，来捆绑安装PHP的环境。官方推荐的：[MAMP][mamp-downloads] 和 [XAMPP][xampp]。

[Homebrew]: http://brew.sh/
[Homebrew PHP]: https://github.com/Homebrew/homebrew-php#installation
[mac-compile]: http://www.php.net/manual/en/install.macosx.compile.php
[xcode-gcc-substitution]: https://github.com/kennethreitz/osx-gcc-installer

["Command Line Tools for XCode"]: https://developer.apple.com/downloads
[mamp-downloads]: http://www.mamp.info/en/downloads/
[phpbrew]: https://github.com/phpbrew/phpbrew
[xampp]: http://www.apachefriends.org/en/xampp.html
