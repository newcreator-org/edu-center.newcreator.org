# [Edu center](http://edu-center.new.or.jp/) by [newCreator.org](https://new.or.jp)

[![Netlify Status](https://api.netlify.com/api/v1/badges/5d67d08f-2b13-476e-88bf-d2655b5f0394/deploy-status)](https://app.netlify.com/sites/edu-center/deploys)

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
