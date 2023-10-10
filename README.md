# Template-Docker
Ready-made Docker template to start the configuration

# PHP
PHP is configured by the path **dockerfiles/php.Dockerfile**.

# Composer
Composer is configured by the path **dockerfiles/composer.Dockerfile**.

# Entry Points
```
docker-compose run artisan [argument]
docker-compose run composer [argument]
```

# Commands

```
docker-compose up
```

After install
```
docker-compose up -d
```
For stop
```
docker-compose down
```
## WARNING:
If u wanna change in laravel env host, host = service;
For example mysql is a service, and env file, we need replace 127.0.0.1 to mysql.
```DB_HOST=mysql```
