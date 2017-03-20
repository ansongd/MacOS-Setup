# ProxyChains-NG实现终端下的代理

使用 Homebrew 安装

```
brew install proxychains-ng
```

编辑配置文件

```
vim /usr/local/etc/proxychains.conf
```

结尾加入

```
socks5  127.0.0.1 6153
```



