# apache_cgi_ssi

## 概要
このプロジェクトは、Apacheサーバー上でCGIとSSI (Server Side Includes) を動作させるサンプルです。

## 使用方法
以下の手順に従ってプロジェクトをセットアップし、実行してください。

### 1. リポジトリをクローン
```bash
git clone https://github.com/b0n/apache_cgi_ssi.git
```

### 2. 環境変数ファイルをコピー
```bash
cp .env.example .env
```

### 3. Dockerコンテナをビルドして起動
```bash
docker-compose up -d --build
```

### 4. ブラウザでアクセス
以下のURLにアクセスして、動作を確認します。
http://localhost:8813
