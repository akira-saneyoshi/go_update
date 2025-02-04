# Goバージョンアのアップグレード

### 留意事項

* 1.xx.x：必要に応じて置き換え。
* 動作環境：Ubuntu24 LTS(WSL2)

## 手順 

```bash
$ cd /usr/local/src
```

```bash
$ sudo curl -L "https://go.dev/dl/go1.xx.x.linux-amd64.tar.gz" -O
```

```bash
$ cd ..
```

```bash
$ sudo unlink go
```

```bash
$ sudo tar xvf src/go1.xx.x.linux-amd64.tar.gz
```

```bash
$ sudo mv go go1.xx.x
```

```bash
$ sudo ln -s go1.xx.x go
```

```bash
$ go version
```

```bash
go version go1.xx.x linux/amd64
```
