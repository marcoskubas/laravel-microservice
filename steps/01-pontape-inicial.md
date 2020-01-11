
## PONTAPÉ INICIAL

**Criando Aplicação Laravel**

```
docker-compose up -d

docker logs micro-videos-app -f
```

**Conhecendo o Laravel 6.0**

https://github.com/laravel/framework

https://github.com/laravel/ui

https://semver.org

https://laravel.com/docs/6.x/helpers

https://laravel.com/docs/6.x/upgrade#helpers

**Migrando Laravel 5.8 para Laravel 6.0**

Alterar composer.json para: 

"laravel/framework": "^6.0"

"php": "^7.2",

"phpunit/phpunit": "^8.0"

```
composer update
```

https://laravel.com/docs/6.x/upgrade

**Configuração do ambiente de desenvolvimento**

Ativar Plugins, principalmente Laravel na IDE PHPStorm

Verificar atalhos para facilitar uso da IDE visando produtividade

**Melhorando autocomplete no Laravel**

https://github.com/barryvdh/laravel-ide-helper

https://github.com/barryvdh/laravel-ide-helper/issues/688

```
composer require --dev barryvdh/laravel-ide-helper

php artisan ide-helper:generate

php artisan ide-helper:models no

composer require --dev doctrine/dbal:~2.3

php artisan ide-helper:meta

```