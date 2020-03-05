# Docker镜像命令  

来源:https://www.jianshu.com/p/7c9e2247cfbd   
docker pull 软件名

查看本地镜像   
docker images  

删除本地镜像  
docker rmi [ 镜像名 or 镜像 id ]

查看镜像详情
docker inspect [ 镜像名 or 镜像 id ]

docker run [ 参数 ] [ 镜像名 or 镜像 id ] [ 命令 ]

docker run -it --name=c1 centos /bin/bash  
-i 一直运行 -t 有命令行窗口 --name= 取名字 centos 镜像名字 /bin/bash 命令


