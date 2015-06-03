## React sample with webpack.

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
git clone git@github.com:1010real/reacttest.git
or 
git clone https://github.com/1010real/reacttest.git
```
※githubを既に使っていて、githubサーバにログイン出来る人は上

### 4. 必要なモジュールをインストール

```
cd reacttest
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

「not clicked」 と表示され、クリックしたら「clicked」と表示が変わればとりあえず動いてます。
