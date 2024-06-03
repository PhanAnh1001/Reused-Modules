# Reused-Modules
Reuse code for all type of project (Golang-Backend, NextJs-Frontend, or others ...)

## Start
```
mkdir -p ~/app
cd ~/app
git clone https://github.com/PhanAnh1001/reused-modules.git
cd reused-modules
git clone https://github.com/PhanAnh1001/reused-modules-api.git
git clone https://github.com/PhanAnh1001/reused-modules-front.git
git clone https://github.com/PhanAnh1001/reused-modules-cms.git
cd ./
docker-compose up -d
```

## API
http://localhost:8080/

## Front
http://localhost:3000/

## Cms
http://localhost:6000/

## DB
MYSQL_DATABASE: db
MYSQL_ROOT_PASSWORD: password
PORT: 33080:3306
