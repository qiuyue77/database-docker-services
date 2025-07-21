## database-docker-services
docker-services about database
数据库的docker服务

#### 下载或clone项目
```bash
git clone https://github.com/qiuyue77/database-docker-services.git
```
#### 进入项目并新建目录data/mysql & data/pg_data

```bash
cd database-docker-services && mkdir -p data/mysql && mkdir -p data/pg_data
```
#### 编辑 docker-compose.yml 修改数据库 密码(password)--- mysql 和 postgreSQL的密码

#### 启动数据库docker容器
```bash
docker-compose up -d
```
### 进入myxsql-docker容器 创建一个mysql数据库
```bash
docker-compose exec mysql mysql -p  # 登录 mysql
```
#### 输入数据库 密码

#### 新建mysql数据库 xxx 并退出
```
CREATE DATABASE xxx;
\q
```
