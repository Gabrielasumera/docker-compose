# docker-compose


Zaciągnięcie zależności:

Baza danych:

<img src="Zrzut ekranu (299).png">

Wordpress:

<img src="Zrzut ekranu (300).png">

Zmienne środowiskowe:

```
environment:
      MYSQL_ROOT_PASSWORD: password
      MYSQL_DATABASE: wordpress
      MYSQL_USER: wordpress
      MYSQL_PASSWORD: wordpress
```

```
environment:
      WORDPRESS_DB_HOST: db:3306
      WORDPRESS_DB_USER: wordpress
      WORDPRESS_DB_PASSWORD: wordpress
      WORDPRESS_DB_NAME: wordpress 
```
