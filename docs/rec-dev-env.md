# 推奨開発環境

[Parcel](https://ja.parceljs.org/) を利用して、 [Sass](https://sass-lang.com/) で開発する。

ソースコードは `.sass` よりも `.scss` を推奨する。

## 目次

## 導入手順

1.  [Node.js](https://nodejs.org/ja/) と [git](https://git-scm.com/)をインストール
    （環境変数を通すのを忘れずに）
2.  リポジトリをクローン
    ```
    git clone https://github.com/KarasuTatehi/itsuki-no-miya.git
    ```
3.  パッケージをインストール
    ```
    npm i
    ```
4.  `src` ディレクトリでソースコードを書く


## ビルド

ビルドスクリプトを実行
```
npm run build
```
`dist` ディレクトリにコンパイルされた `.css` が出力される


## テスト

テストスクリプトを実行
```
npm run serve
```
[ローカル](http://localhost:1234/)にライブサーバーが立ち上がる
