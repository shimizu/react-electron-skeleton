# react-electron-boilerplate

create-react-appとelectronを使って、できるだけ簡単にアプリの開発環境を構築するためのボイラープレートです。

以下の手順でインストールしてください。

※ Macでしかテストしていません。

## インストール

```
$ create-react-app electron-example
$ git clone git@github.com:shimizu/react-electron-boilerplate.git
$ cp -r react-electron-boilerplate/* electron-example
```

```
$ cd electron-example
$ yarn install
```

## 開発環境の起動

```
$ yarn electron-dev
```

## パッケージ化

```
$ yarn electron-pack
``` 
`dist` フォルダにパッケージが出力されます。
