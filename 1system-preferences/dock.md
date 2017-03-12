# Dock软件导航设置

* ### 彻底关闭Finder可用在终端运行

```
defaults write com.apple.finder QuitMenuItem -bool YES
killall Finder
```

* ### 在dock \[ 应用区 \] 增加空隔

```
defaults write com.apple.dock persistent-apps -array-add '{"tile-type"="spacer-tile";}';killall Dock
```

* ### 在dock \[ 堆栈区 \] 增加空隔

```
defaults write com.apple.dock persistent-others -array-add '{tile-data={}; tile-type="spacer-tile";}' ;killall Dock
```



