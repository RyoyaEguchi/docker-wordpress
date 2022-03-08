# docker-wordpress
## 概要
wordpress環境が構築できます。

mysqlとwordpressのバージョンは特に指定していないので、
バージョン指定の必要がある場合は`docker-compose.yml`ファイルを修正してください。

db_data以下にデータが投入されます。

## コマンド
起動
```sh
docker-compose up -d
```

環境のクリア
```sh
docker-compose down --volumes
``
