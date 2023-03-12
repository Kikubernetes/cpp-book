# ゼロから学ぶ C++　（mac userバージョン）

このリポジトリはオンライン学習サイト [ゼロから学ぶ C++] のソースコードリポジトリです。
buildが面倒な方は上のdocsのフォルダをクリックするとこのページ内で確認できます。
本家はwindows用なのでmac用にアレンジしてみました。
基本的に自分が勉強しながら必要なところだけをアレンジしていく予定です。

## 必要なもの

ソースコードから HTML ページを生成するには下記のものが必要です。

- Python3

## ビルド

HTML を生成するには下記のコマンドを実行してください。

```shell
$ pip install -r requirements.txt
$ mkdocs build
```

ビルド結果をブラウザ上で確認するには次のコマンドを実行します。

```shell
$ mkdocs serve
```

http://localhost:8000 にアクセスすると Web ページが表示されます。

[ゼロから学ぶ C++]: https://rinatz.github.io/cpp-book
