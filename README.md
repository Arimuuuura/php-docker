# php-docker
docker で作成する php &amp; MySQL 環境

## 環境構築
```
$ git clone https://github.com/y-arimura1222/php-docker.git

$ cp .env.sample .env
.env ファイルをご自身の環境に書き換えてください。

$ docker-compose up --build
コンテナ立ち上げ

$ docker-compose down
コンテナ停止(作業終了時実行)
```

## アクセスURL
```
web:
http://localhost:80

phpMyAdmin:
http://localhost:8080
```

自身の環境に合わせて Dockerfile のバージョンを書き換えてください。
