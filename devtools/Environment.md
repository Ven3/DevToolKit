# 通用环境搭建

> ## **MySQL**

### 下载地址

MySQL官网:  https://downloads.mysql.com/archives/community/  
清华镜像:  https://mirrors.tuna.tsinghua.edu.cn/mysql/  
网易镜像:  http://mirrors.163.com/mysql/downloads/  
腾讯镜像:  https://mirrors.cloud.tencent.com/mysql/  

### 读写分离

> ## **Oracle**

### 下载地址


> ## **Redis**

### 下载地址

https://redis.io/commands/

> ## **Docker**

### 下载地址

https://www.docker.com/

### Docker仓库

https://hub.docker.com/

### 镜像加速

docker镜像加速地址:  
1. Docker中国镜像加速器: https://registry.docker-cn.com
2. 中科大的镜像加速器: https://docker.mirrors.ustc.edu.cn/
3. 阿里云的镜像加速器: 需要注册阿里云, 控制台 -> 容器镜像服务 -> 镜像工具 -> 镜像加速器, 传送门 -> [镜像加速器](https://cr.console.aliyun.com/cn-hangzhou/instances/mirrors)


**修改`daemon.json`, 添加`registry-mirrors`节点**
```json
{
    "registry-mirrors": ["https://registry.docker-cn.com"]
}
```
**重启服务**

> ## **Tomcat**

### 下载地址

https://tomcat.apache.org/


