# portainer-compose

[portainer](https://www.portainer.io/)をdocker-composeで起動できるようにします。

## 用意するもの
* docker
* docker-compose
* git

## インストール方法
任意のディレクトリで以下のコマンドを実行

```bash
git clone https://github.com/kangju/portainer-compose.git
```

## 実行方法

cloneしてできたディレクトリ内で以下のコマンドを実行

```bash
docker-compose up -d
```

起動したら、ブラウザで

https://127.0.0.1:9443/

にアクセス
## ライセンス
MIT