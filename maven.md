
## 下载
- http://maven.apache.org/download.cgi
- wget http://mirrors.hust.edu.cn/apache/maven/maven-3/3.5.0/binaries/apache-maven-3.5.0-bin.tar.gz

## 解压maven到/usr/local目录下
- tar -zvxf apache-maven-3.5.0-bin.tar.gz -C /usr/local/

## 入环境变量
- vim /etc/profile

```
export MAVEN_HOME=/usr/local/apache-maven-3.3.9/bin
export PATH=$PATH:$MAVEN_HOME
```

- source /etc/profile

## 测试
- mvn --version
