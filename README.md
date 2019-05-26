# 踏切マップ

## 開発環境
- Googleスプレッドシート
- Google App Script (GAS)

---

## 実行方法

```
$ curl -L https://script.google.com/macros/s/AKfycbyU4AbIhyVPz9OJdaxYNZgowuYDPHFNcS3_XvsytNmLCzg2oCSa/exec
```

## 別シートのデータを取得したいとき

```
var data = getData('API');
```

`getData()` の引数に取得したいシート名を入力してください。
