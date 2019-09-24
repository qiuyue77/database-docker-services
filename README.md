## database-docker-services
docker-services about database
数据库的docker服务

#### 下载或clone项目
```bash
git clone https://github.com/runforever/dev-docker-services
```
#### 进入项目并新建目录data/mysql

```bash
cd dev-docker-services && mkdir -p data/mysql
```
#### 编辑 docker-compose.yml 修改数据库 密码(password)

#### 启动数据库docker容器
```bash
docker-compose up -d
```
#### 进入docker容器
```bash
docker-compose exec mysql mysql -p  # 登录 mysql
```
#### 输入数据库 root 密码

#### 新建mysql数据库 xxx 并退出
```bash
CREATE DATABASE xxx;
\q
```