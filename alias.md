# alias自定义语句

编辑自定义语句脚本

```
vi ~/.bashrc
```

脚本样式

```
echon
alias ps4='proxychains4'
alias cdhome='cd ~'
alias cdroot='cd /'
alias gpull='git pull'
alias gci='git commit -a'
alias gpush='git push origin HEAD:refs/for/master'
alias gst='git status'

source ~/.bashrc
```

如果还不行的话，说明没有~/.bash\_profile文件，或者文件中没有执行.bashrc文件。

\(.bash\_profile文件是用户登陆终端的时候会自动执行的文件，一般此文件中会调用.bashrc\)

如果是这样，需要打开（如果没有的话先创建）文件：

~/.bash\_profile

在里面加入一行：

source ~/.bashrc

就ok了。

