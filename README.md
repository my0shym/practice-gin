https://go.dev/doc/tutorial/web-service-gin

# 全データ取得
```sh
curl http://localhost:8080/albums
```

# Post
```sh
curl http://localhost:8080/albums \
    --include \
    --header "Content-Type: application/json" \
    --request "POST" \
    --data '{"id": "4","title": "The Modern Sound of Betty Carter","artist": "Betty Carter","price": 49.99}'
```

# id指定でデータ取得
```sh
curl http://localhost:8080/albums
```
