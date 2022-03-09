# docker-wordpress
## 概要
wordpress環境が構築できます。

mysqlとwordpressのバージョンは特に指定していないので、
バージョン指定の必要がある場合は`docker-compose.yml`ファイルを修正してください。

db_data以下にDBのデータが保存され、wordpress以下にwordpressのデータが保存されます。

## 初期設定
起動
```sh
docker-compose up -d
```

ブラウザからアクセス
[http://localhost:8000/](http://localhost:8000/)

## コマンド
起動
```sh
docker-compose up -d
```

環境のクリア
```sh
docker-compose down --volumes
```

wordpressのコンテナに入る
```sh
docker-compose exec wordpress bash
```
