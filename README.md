# docker:
- nginx
- php latest
- mysql latest
- phpmyadmin latest

## *nginx*
[http://localhost/](http://localhost/)

## *phpmyadmin*
[http://localhost:9090/](http://localhost:9090/)
- server: mysql
- user: root
- password: root
- database: my_database

## *mysql*
[http://localhost:3306/](http://localhost:3306/)

## Install:
```
git clone git@github.com:bkit9x/docker.git
cd docker
docker-compose build
```

## Run:
- up:
```
docker-compose up -d
```

- down:
```
docker-compose down
```

- exec bash
```
docker-compose exec php bash
```
## Note:
*save code in public folder*