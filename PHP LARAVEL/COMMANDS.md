##### Model
```css
php artisan make:model Curso -m
```

##### Criar Migration
```css
php artisan make:migration create_produtos_table --create=produtos
```


```css
//executar
php artisan migrate

//reexecuta e sobrescreve tudo
php artisan migrate:refresh --seed
```

##### Controller
```css
php artisan make:controller contatoController
```

##### Seeds
```css
php artisan make:seeder UsersDadosSeeder

//executa todos
php artisan db:seed

//executa especifico
php artisan db:seed --class=UsersTableSeeder
```