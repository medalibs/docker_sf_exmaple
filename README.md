Symfony 6 Application
========================
docker-compose up

docker exec -it www_docker_symfony_6a project/bin/console doctrine:database:create
docker exec -it www_docker_symfony_6a project/bin/console doctrine:migration:diff
docker exec -it www_docker_symfony_6a project/bin/console doctrine:migration:migrate

go to api-platform  http://localhost:8741/api

php bin/phpunit

