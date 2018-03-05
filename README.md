"# ruby-dev_docker" 
docker build -t ruby-image .
docker run -d -it -h rbdev ruby-image

コンテナへターミナルアクセス
docker attach [container id]

追加プロセスを実行してコンテナへターミナルアクセス 

docker exec -it [container id] /bin/bash


