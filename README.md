# cmatrix-1.2a

在百度上找到的一个软件：代码雨  
还是满有意思的  

# 安装过程  

1.依赖：  

Ubuntu:

> $ sudo apt-get install ncurses-devel  

CentOS/RedHat

> $ yum install ncurses-devel  

Fedora

> $ dnf install ncurses-devel

2.配置：  

> $ cd cmatrix-1.2a  
> $ ./configure && make && make install  


# 使用说明  

cmatrix [-abBflohnsVx] [-C color]

选项

-a :异步滚动（默认）

-b :随机粗体

-B :全部粗体

-f :force the linux $TERM type to be on
   
-l :Linux mode (sets "matrix.fnt" font in console)
   
-o :使用旧风格滚动（不好看）

-h :获得帮助信息

-n :不使用粗体（默认）

-s :"Screensaver" mode,exits on first keystroke
   
-x :X window 模式，好像就是显示的符号不一样

-V :显示版本信息

-u :刷新频率，0-9，也就是滚动的快慢

-C :显示的颜色，支持green(默认),red,blue,white,yellow,cyan,
       magenta and black

在运行的状态下，直接按q，即可退出程序

