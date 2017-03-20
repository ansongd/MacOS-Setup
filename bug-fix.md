# 常见问题解决方案

## [解决Macbook Pro蓝牙不可用问题](http://www.jianshu.com/p/87e25a072623)

#### **重置Mac 上的系统管理控制器\(SMC\)**

1.   将 Mac 关机。
2.   从电脑上拔下 MagSafe 或 USB-C 电源适配器。
3.   在内建键盘上，按下键盘左侧的 Shift-Control-Option 键，然后同时按下电源按钮。按住这些按键和电源按钮 10 秒钟。
4.   松开所有按键。
5.   重新连接电源适配器。
6.   再次按下电源按钮以开启 Mac。

#### 

#### **重置 Mac 上的 NVRAM**

1.   将 Mac 关机。
2.   先按下power键，紧接着同时按下option+command+p+r,手，系统会自动开机
3.   等待mac发出4声Duang~的声音后松



[创建可引导的 macOS 安装器](https://support.apple.com/zh-cn/HT201372)

在“终端”中使用“createinstallmedia”命令

#### 第一步：插入U盘，打开“终端”输入：sudo+空格

![](https://gss0.baidu.com/-fo3dSag_xI4khGko9WTAnF6hhy/zhidao/wh%3D600%2C800/sign=e306887074f082022dc799397bcbd7d5/810a19d8bc3eb1357db7dbe8a11ea8d3fd1f4474.jpg)

#### 第二步：找到 安装 OS X 安装包，右键选择“显示包内容”  在Contents/Resources/文件夹下找到：createinstallmedia

![](https://gss0.baidu.com/-4o3dSag_xI4khGko9WTAnF6hhy/zhidao/wh%3D600%2C800/sign=ff2beb7f8001a18bf0be1a49ae1f2b30/8694a4c27d1ed21b7a0b43b6aa6eddc450da3fa6.jpg)

#### 第三步：将createinstallmedia文件拖入“终端”  ![](https://gss0.baidu.com/-4o3dSag_xI4khGko9WTAnF6hhy/zhidao/wh%3D600%2C800/sign=84978820aa4bd1130498bf346a9f8837/cdbf6c81800a19d8f03ce85634fa828ba61e46a1.jpg)

#### 第四步：输入 --volume+空格 ，之后托入U盘图标至“终端”

![](https://gss0.baidu.com/-fo3dSag_xI4khGko9WTAnF6hhy/zhidao/wh%3D600%2C800/sign=caf607bc8ab1cb133e3c3415ed647a76/b7003af33a87e950cb749f3f17385343fbf2b406.jpg)

#### 第五步：输入 --applicationpath+空格 ，之后将包托入“终端”

![](https://gss0.baidu.com/9fo3dSag_xI4khGko9WTAnF6hhy/zhidao/wh%3D600%2C800/sign=7d6a715b1830e924cff194377c38423e/dcc451da81cb39dbcc9f0b05d7160924ab183001.jpg)

#### 第六步：最后输入 --nointeraction，按“return”（回车）图F 请看划线部份系统会显示图下图，并提示你输入电脑登录密码，如果没有密码直接按回车如果看到 DONE 绿色框那里，就证明完成

![](https://gss0.baidu.com/94o3dSag_xI4khGko9WTAnF6hhy/zhidao/wh%3D600%2C800/sign=c28a7496e7fe9925cb596156049872e7/023b5bb5c9ea15cece708c5ab1003af33b87b2c3.jpg)

