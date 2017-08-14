此版本加了环境安装脚本，安装脚本支持ubuntu 14.04，实测可用

##用法 进入系统后先升级源，输入命令
sudo apt-get update 
等一会自动下载，输入命令 
sudo apt-get install -y git 
如果出现bash: sudo: command not found错误，说明没有安装这个程序，直接输入命令
apt-get install -y sudo git
用 cd 命令进入任意可写权限文件夹，输入命令
sudo git clone https://github.com/sanzuwu/crysadm.git
等待下载完成，输入命令
cd /crysadm && sudo chmod +x setup.sh && ./setup.sh
此时等待安装，完成后会自动启动云监工。




cd /crysadm && sudo chmod +x setup.sh && ./setup.sh