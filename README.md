# Docker 
## [基本命令](https://github.com/chengziqaq/Docker/blob/master/docker-basic-command.md)
## [安装](https://blog.csdn.net/m0_37607365/article/details/79811086)
- 国内   
```
curl -sSL https://get.daocloud.io/docker | sh && sudo systemctl start docker
```
- 国外      
```
curl -sSL https://get.docker.com/ | sh && sudo systemctl start docker
```
~~- 安装后启动docker~~

- 安装docker-compose
```
sudo curl -L "https://github.com/docker/compose/releases/download/1.25.5/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
```
```
sudo chmod +x /usr/local/bin/docker-compose  
```
## docker amazing软件
### [docker-bt下载 可在线播放](https://github.com/asapach/peerflix-server/blob/master/Docker.md)
运行后访问 ip:9000
### [dns解锁netflix](https://github.com/chengziqaq/netflix-proxy)
要求：Ubuntu系统 不需要先安装docker，这个命令前几行就是安装docker
```docker
apt-get update\
  && apt-get -y install vim dnsutils curl sudo\
  && curl -fsSL https://get.docker.com/ | sh || apt-get -y install docker.io\
  && mkdir -p ~/netflix-proxy\
  && cd ~/netflix-proxy\
  && curl -fsSL https://github.com/chengziqaq/netflix-proxy/archive/latest.tar.gz | gunzip - | tar x --strip-components=1\
  && ./build.sh
```
### [pycharm网页+VNC版（可用iPad云编程）](https://hub.docker.com/r/binhex/arch-pycharm/)
服务器内存至少1G 延迟低点 不然很卡 
### [intellij-idea网页+VNC版（可用iPad云编程）](https://hub.docker.com/r/binhex/arch-intellij)
### [linux服务器桌面版 vnc和novnc连接](https://github.com/fcwu/docker-ubuntu-vnc-desktop)













