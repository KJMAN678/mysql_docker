# イメージのビルド

docker-Compose build

# コンテナの作成

docker-Compose up -d

# 起動したコンテナにログイン

docker exec -it docker-mysql-mysql-1 bash -p

# MySQL を起動

mysql -u root -p -h 127.0.0.1

# エラーログの確認

docker compose logs

# すべて削除する

docker-compose down --rmi all --volumes --remove-orphans
