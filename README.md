## Babel sample with sourcemaps.

### 1. nodeをインストール

公式サイトから
[https://nodejs.org/](https://nodejs.org/)

#### 確認

```
node -v
v0.12.2
npm -v
2.7.4
```

### 2. gulpをインストール

#### インストール
```
npm install -g gulp
```

#### 確認

```
gulp -v
[21:34:49] CLI version 3.8.11
```

### 3. リポジトリをclone

```
git clone git@github.com:1010real/babeltest.git
or
git clone https://github.com/1010real/babeltest.git
```
※githubを既に使っていて、githubサーバにログイン出来る人は上

### 4. 必要なモジュールをインストール

```
cd babeltest
npm install
```

### 5. 初期build

```
gulp build
```

### 6. webServer立ち上げ&監視(確認)

```
gulp watch
```
何も表示されませんが、ソースを見るとES6で書いたコードがES5に変換されてます。
ブレークポイントを設置すると、sourcemaps経由で元ソースの場所へ自動的にブレークポイントが設定されます。

### 以降は以下を参考に

[ES6時代のJavaScript](http://sba-netgame.dmm.com/pc/)

[各ブラウザのEcmaScript対応状況](http://kangax.github.io/compat-table/es6/)

[JavaScript Promiseの本](http://azu.github.io/promises-book/)
