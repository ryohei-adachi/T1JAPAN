# 使い方

①ローカル環境にDockerおよびdocker-composeをインストール

Dockerは下記の公式サイトからインストール
https://www.docker.com

②GitHubから対象コードをダウンロード

git clone https://github.com/ryohei-adachi/T1JAPAN.git

③docker-compose.ymlファイルがあるディレクトリ上で下記のコマンドを実行

docker-compose up -d

④下記のURLにアクセスする

http://localhost:8000

⑤コンテナを終了するには下記のコマンドを実行する

docker-compose down
