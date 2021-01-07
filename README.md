# Harbor-Deploy

教程参考：https://learnku.com/articles/29884

~~~bash
$ cd /opt && wget https://storage.googleapis.com/harbor-releases/release-1.8.0/harbor-offline-installer-v1.8.0.tgz

$ cd /opt && tar xvf harbor-offline-installer-v1.8.0.tgz

$ cd /opt/harbor && mv harbor.yml harbor.yml.bak && wget 

$ cd /opt/harbor && ./install.sh && echo "127.0.0.1 101-bytedance.harbor.com" >> /etc/hosts
~~~

