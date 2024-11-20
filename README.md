## Included Services

- nginx
- php-fpm
- node

To start the project run `docker compose up -d`

To consume messages run `docker compose exec php-fpm bin/console messenger:consume async -vv`. The `-vv` is optional
