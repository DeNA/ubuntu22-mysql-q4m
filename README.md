# ubuntu22-mysql-q4m

## What's this
mysql-buildを使って、ubuntu22上にq4mがインストールされたdocker imageをbuildします。

## Build
```
docker build . --build-arg MYSQL_VERSION=8.0.28
```

## Related to
- https://github.com/q4m/q4m
  - https://github.com/DeNA/q4m
- https://github.com/kamipo/mysql-build

## Support mysql version
- 8.0.28

## About packages
ビルドにとても時間がかかるので、ビルド済みのimageをghcrに公開しています。