# rails-react-carrierwave-backend

詳細: https://qiita.com/kazama1209/items/1a0186f635f14a8161d8

## セットアップ

```
$ docker-compose build
$ docker-compose up -d
$ docker-compose run api rails db:create
$ docker-compose run api rails db:migrate
```

## 動作確認

```
$ curl -F "content=test" -F "image=@sample.jpg" http://localhost:3001/api/v1/posts
$ curl -X GET http://localhost:3001/api/v1/posts
```
