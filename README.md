##Git的常见基础操作命令
###安装初始化
####安装git本地安装Windows版本
* 下载地址：  
**https://git-scm.com/downloads/**  
![下载链接1.0](1111111)

####初始化Git用户信息配置
* 配置git用户  
```bash
Dpad@DESKTOP-9O4NLO5 MINGW64 /D/baolin/Git-bash
$ git config --global user.name "baolin.li"
```

* 配置git邮箱  
```bash
Dpad@DESKTOP-9O4NLO5 MINGW64 /D/baolin/Git-bash
$ git config --global user.email "baolin2200@163.com"
```

* 添加颜色显示  
```bash
Dpad@DESKTOP-9O4NLO5 MINGW64 /D/baolin/Git-bash
$ git config --global color.ui auto
```

* 调整ASCII字符乱码问题
```bash
Dpad@DESKTOP-9O4NLO5 MINGW64 /D/baolin/Git-bash
$ git config --global core.quotepath off
```

* 查看配置  
```bash
Dpad@DESKTOP-9O4NLO5 MINGW64 /D/baolin/Git-bash
$ git config --list
core.symlinks=false
core.autocrlf=true
core.fscache=true
color.diff=auto
color.status=auto
color.branch=auto
color.interactive=true
help.format=html
http.sslcainfo=D:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
diff.astextplain.textconv=astextplain
rebase.autosquash=true
credential.helper=manager
user.name=baolin.li
user.email=baolin2200@163.com
color.ui=auto
core.quotepath=off
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true
core.hidedotfiles=dotGitOnly
```
* 初始git工作目录：
```bash
Dpad@DESKTOP-9O4NLO5 MINGW64 /D/baolin/Git-bash
$ git init
Initialized empty Git repository in D:/baolin/Git-bash/.git/
```


















