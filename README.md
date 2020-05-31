### PHP (PHP-FPM)

Composer is included

```
docker-compose run php-fpm composer 
```

To run fixtures

```
docker-compose run php-fpm bin/console doctrine:fixtures:load
```

# tv_shows
Management of Favorite TV Shows

