# config_linux
## １、更改键盘设置
     Caps_lock <-> Control_L  
     Control_L <-> Super_L  
     Super_L   <-> Caps_lock  
     
     设置命令 xmodmap   

注：  
1. 该方法在切换输入法后会失效，需要重新运行  
2. 用setxkbmap方法也会在切换输入法后失效  
3. 失效主要发生在ibus输入框架中,在fcitx框架下没有问题（god bless!)  
4. 失效发生在centos7中，ubuntu 没试  

## 2、重新到一个系统中应该做的事
备忘：  
1. 改键  
2. 安装设置git  
3. 改键  
4. clone vim设置  

