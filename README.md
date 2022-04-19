# Docker-WordPress

# 步骤
## 1. 克隆项目到任意目录
```bash
$ git clone git@github.com:yathob/docker_wordpress.git
```

## 2. 进入项目
```bash
$ cd docker-wordpress
```

Note:
```bash
如果是production环境，强烈建议，修改 docker-compose.yml 文件中 MYSQL_ROOT_PASSWORD, MYSQL_PASSWORD 的值.
同时，保持 MYSQL_USER/MYSQL_PASSWORD 与 WORDPRESS_DB_USER/WORDPRESS_DB_PASSWORD一一对应.
```

## 3. 运行命令
```bash
$ docker-compose up -d
```

## 4. 开始安装
浏览器打开如下网址：

- http://127.0.0.1 开始安装

## 5. 后续操作
