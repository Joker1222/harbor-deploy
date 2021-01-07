# Harbor部署教程

> 概述：harbor 是一个开源的企业级docker hub库 (类似gitlab),用于存放以及管理基础镜像，如 基础编译容器、基础运行容器

## 1.安装
> 默认安装在系统/opt目录下,需要root权限
~~~bash
$ cd /opt && wget https://storage.googleapis.com/harbor-releases/release-1.8.0/harbor-offline-installer-v1.8.0.tgz
$ cd /opt && tar xvf harbor-offline-installer-v1.8.0.tgz
$ cd /opt/harbor && mv harbor.yml harbor.yml.bak
$ cd /opt/harbor && wget https://raw.githubusercontent.com/Joker1222/Harbor-Deploy/main/harbor.yml 
$ cd /opt/ && curl -fsSL get.docker.com -o get-docker.sh && bash get-docker.sh --mirror Aliyun && \
curl -L https://github.com/docker/compose/releases/download/1.22.0/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose
$ ./install.sh
~~~
