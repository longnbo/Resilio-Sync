# Resilio-Sync
Resilio Sync一键安装脚本


#安装必要的软件包
yum -y install wget unzip

#下载脚本
wget https://github.com/helloxz/Resilio-Sync/archive/master.zip

#解压并安装
unzip master.zip && cd Resilio-Sync-master && chmod +x mysync.sh sync.sh && ./sync.sh
