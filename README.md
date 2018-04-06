# docker-compose for us

## Usage
### 初回だけ

```bash
# initialize
$ docker-compose run --rm server create_db
```

### 起動
```bash
$ docker-compose up
# or
# $ docker-compose up -d
```

## Warning
- 一回のbuild に5分以上かかります. 故に開発にも大変時間がかかります.
- しかし, testは動かない（rc1だからだと思います.）のでそちらの方もなんとかしたいです.

## License

BSD-2-Clause.

だそうです.
