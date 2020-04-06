## 开始使用

> git clone https://github.com/goukey/KMS-docker.git KMS-docker

> cd KMS-docker

> docker-compose up -d


## 关闭容器

> docker-compose down

## 升级容器

> cd Bitwarden-docker

> docker-compose down  #停止容器

> git pull

> docker-compose pull  #更新image

> docker-compose up -d  #启动容器

> docker image prune  #删除旧的镜像

## 使用方法  只适用于VL版

> slmgr /skms 192.168.1.30

> slmgr /ato
