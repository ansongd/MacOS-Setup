# Homebrew安装配置

使用包管理工具能更有效的管理你的软件安装及更新等操作，Homebrew正成为OSX平台上越来越受欢迎的管理工具。虽然Homebrew安装脚本已经能完成整个安装过程，但是安装之前还是推荐手动安装Command Line Tools苹果开发工具，Homebrew需要有此依赖工具包才能正常安装。

* ### 终端安装 **Xcode Tools**

```
xcode-select --install
```

* ### 获取 Homebrew，打开终端窗口, 粘贴以下脚本。

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

* ### 安装脚本后检查安装情况

```
brew doctor
```

如果正常安装，输入以上命令会提示安装成功。

### 默认配置说明



