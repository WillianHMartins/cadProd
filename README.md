## Colanar o projeto

[https://github.com/WillianHMartins/cadProd.git]

# Após clonado

No terminal cd cadProd
Editar o arquivo .env.example para .env

## Dentro do diretório

composer install

bin/console doctrine:database:create

bin/console make:migration

bin/console doctrine:migrations:migrate

## Rodar o servidor

symfony server:master

## Abrir no navegador

http://localhost:8000