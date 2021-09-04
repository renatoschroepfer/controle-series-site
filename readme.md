## Sistema de controle de Series.

Este sistema está sendo construido usando laravel 5.8 para controle de séries. Onde nele voce poderá cadastrar sua série
favorita, quantidade de temporadas e episodios. A cada episodio assistido voce pode sinalizar no sistema qual episodio
você já assistiu.

### Recursos usados

Lista de recursos usados para este projeto

| Recurso     | Link                                               |
| ----------- | -------------------------------------------------- |
| Laravel     | https://laravel.com/docs/5.8                       |
| PHP         | https://www.php.net/releases/7_2_0.php             |
| MariaDB     | https://downloads.mariadb.org/mariadb/10.1.37/                                  |
| Boostrap    | https://stackpath.bootstrapcdn.com/bootstrap/4.3.1 |
| Fontawesome | https://use.fontawesome.com/releases/v5.8.1/       |

Após baixar o projeto instale as dependências usando o composer.

`composer install`

Com o banco de dados já criado. Rode o comando em seu terminal para criar as tabelas.

`php artisan migrate`


Execute o projeto usando o comando

`php artisan serve`

Agora acesse no meu navegador 

http://127.0.0.1:8000/