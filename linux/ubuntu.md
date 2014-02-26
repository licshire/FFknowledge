#Ubuntu

##apt
更改软件源 /etc/apt/sources.list  

查询  apt-cache search xxx  
安装  sudo apt-get install xxx  

git  
sudo apt-get install git  
开发环境  
sudo apt-get install build-essential  
后台服务管理(设定/etc/init.d/ 下面的命令是否开机启动)  
sudo apt-get install sysv-rc-conf  

###SSH
sudo apt-get install openssh-server  
配置 /etc/ssh/sshd_config  
启动 sudo /etc/init.d/ssh start  
停止 sudo /etc/init.d/ssh stop  


##硬件信息
CPU   cat /proc/cpuinfo  
