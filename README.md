# Welcome To Ragdoll Cat's Laboratory
# 安装
1、安装mongodb
* 通过系统包管理器安装

    如 brew (mac), apt-get (ubuntu)
* 手动安装

    curl -O https://fastdl.mongodb.org/linux/mongodb-linux-x86_64-4.0.3.tgz
    
    tar -zxvf mongodb-linux-x86_64-4.0.3.tgz
    
    mv mongodb-linux-x86_64-4.0.3/ /usr/local/mongodb
    
    export PATH=\<mongodb-install-directory>/bin:$PATH
    
    \<mongodb-install-directory> 为你 MongoDB 的安装路径。如本文的 /usr/local/mongodb 。
    
    mkdir -p /data/db
    
    启动服务并挂在后台  mongod &
    
2、安装python的依赖

```shell script
pip install -r requirements.txt
```

3、启动
```shell script
python3 app/run.py
```