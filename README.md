# [Edu center](https://edu-center.newcreator.org) by [newCreator.org](https://newcreator.org)

新型コロナウイルス(COVID-19)の流行および学校閉鎖に向けた、オンラインの教育サービス一覧サイト

---

## 必要なツール

- node, npm (gitのcommitに必要。ない場合はVSCodeなどのcommitizenプラグインでも代用可能。)
- ruby, jekyll (本サイトを動かすのに必要。)
- git (git pushなどに必要。)

## 起動方法

### パッケージインストール

```
$ bundle install
$ npm install
```

### 開発用サーバーの起動

```
$ npm run dev
```

4000番ポートが開くので、 [http://localhost:4000](http://localhost:4000)にアクセスしてください。

## コミット

```
$ git add <SOME_FILES>
```

でcommitを行った後に、

```
$ npm run commit
```

を行ってください。対話式で概要などを選択することが可能です。
