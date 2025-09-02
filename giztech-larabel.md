mkdir larabe_giztech
// mkdir 任意のディレクトリ

cd larabe_giztech

指定されたリポジトリをFork

clone https://github.com/ike-burn/laravel-docker-template.git .
// 「clone https://github.com/[自分のユーザー名]/laravel-docker-template.git .」

docker compose version

docker-compose up -d

docker-compose ps

// Laravel インストール
docker-compose exec app composer create-project --prefer-dist laravel/laravel . "6.*"

git status

git branch

