# Let's HackMD

[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE)

## 利用方法

### 仮想マシンを起動

以下のコマンドを実行し仮想マシンを起動します。

```shell
vagrant up
```

### Redmineのデモ環境を開く

以下のメッセージが表示されたら、
ブラウザで[http://localhost:8080](http://localhost:8080)を開きます。

```shell
TASK [Finish display message] **************************************************
ok: [default] => {
    "msg": "Let's HackMD!"
}
```

## システム構成

* Debian 9

## カスタマイズ方法

セットアップ後に変数を変更した場合は、
以下のコマンドを実行し変更内容を適用しなおす必要があります。

```shell
vagrant provision
```

## License

[MIT](LICENSE)
