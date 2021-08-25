# オッス！！！！
これは Nuxt道場 弐面（オンライン）にて登壇した際のnuxt projectサンプルリポジトリです。

# 前提！！！！
1. Macであること！
2. Docker Desktop on Mac が入っていること！
3. Docker Compose が入っていること！
4. [mkcert](https://github.com/FiloSottile/mkcert) をインストールしていること！
5. Hostsを編集できること！

# Hostsの編集！！！
/etc/hosts
```
127.0.1.33 nuxt-dojo.com
```

# 起動手順！！！
1. `$ cd docker/mac`
2. `$ ./script create` -> 初回起動
3. `$ ./script up` -> 2回目以降

# 終了手順！！！
1. `$ cd docker/mac`
2. `$ ./script down`

# URL
https://nuxt-dojo.com/

# ラッパーコマンドあれこれ
- `./docker/mac/script` を見てくれよな！
