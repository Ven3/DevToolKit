# Java开发人员

> ## 开发工具

[Idea](https://www.jetbrains.com/idea/download/)  
[Eclipse](https://www.eclipse.org/downloads/packages/)  
[VS Code](https://code.visualstudio.com/#alt-downloads)  
[Visual Studio](https://visualstudio.microsoft.com/)  
[Navicat](https://www.navicat.com.cn/products/navicat-premium)  
[DBeaver](https://dbeaver.io/download/)  
[Postman](https://www.postman.com/)

> ## 环境搭建

### JDK

Java 8
[[Oracle JavaSE](https://www.oracle.com/java/technologies/downloads/#java8)] -
[[清华镜像 OpenJDK](https://mirrors.tuna.tsinghua.edu.cn/AdoptOpenJDK/8/)]

Java 11
[[Oracle JavaSE](https://www.oracle.com/java/technologies/downloads/#java11)] -
[[清华镜像 OpenJDK](https://mirrors.tuna.tsinghua.edu.cn/AdoptOpenJDK/11/)]

Java 16
[[Oracle JavaSE](https://www.oracle.com/java/technologies/downloads/#java16)] -
[[清华镜像 OpenJDK](https://mirrors.tuna.tsinghua.edu.cn/AdoptOpenJDK/16/)]

### **Maven**

#### 下载地址

https://maven.apache.org/download.cgi

### **Gradle**

#### 下载地址

https://gradle.org/releases/

### **MySQL**

#### 下载安装

[MySQL安装](../devtools/Environment.md#MySQL)


### **Redis**

#### 下载安装

[Redis安装](../devtools/Environment.md#Redis)

#### 集群配置

> ## 常用配置

### Maven镜像加速

修改maven安装目录conf目录下 `settings.xml` 文件, 配置mirrors, 替换成[阿里Maven仓库](https://maven.aliyun.com/repository/public)

```xml
    <mirror>
      <id>aliyunmaven</id>
      <mirrorOf>*</mirrorOf>
      <name>阿里云公共仓库</name>
      <url>https://maven.aliyun.com/repository/public</url>
    </mirror>
```

### Node镜像加速

修改注册点

```shell
# 修改registry
npm config set registry https://registry.npm.taobao.org 

# 查看配置是否成功
npm config get registry

# 原始注册源 https://registry.npmjs.org/

```

### Docker镜像加速

参见: [常用环境搭建/Docker/镜像加速](../devtools/Environment.md#镜像加速)
