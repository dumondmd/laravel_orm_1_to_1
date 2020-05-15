<p align="center"><img src="https://res.cloudinary.com/dtfbvvkyp/image/upload/v1566331377/laravel-logolockup-cmyk-red.svg" width="400"></p>

# Laravel Udemy
## Curso laravel

Curso de Laravel orm 1 to 1

# MySQL

Entre com *mysql -u root -p*

## Migraton dando erro
```
$table->id();
```
Mudar para a versão antiga
```
$table->increments('id');
```

# Tinker

## Tinker exemplos

Adicionando no banco de dados via terminal

*php artisan tinker*

```
>>> $c = new App\Cliente
=> App\Cliente {#3017}
>>> $c->nome = "João da Silva"
=> "João da Silva"
>>> $c->telefone = "1145454545"
=> "1145454545"
>>> $c->save()
=> true
>>> 
```
