# Node.jsのバージョン管理ツール
しばらくすると毎回Node.jsのバージョン管理ツールを忘れるのでメモ

## 環境
MacOS Sonoma 14.2.1

## バージョン管理ツール
Voltaを採用する

## インストール

```bash
$ curl https://get.volta.sh | bash
```

LTSがインストールされる
```bash
$ volta install node
```

バージョンを指定する場合
```bash
$ volta install node node@20.10.0
```