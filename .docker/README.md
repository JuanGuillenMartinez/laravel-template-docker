## Docker-compose para Laravel 8.0 con PHP 8

Importar proyecto dentro de esta carpeta antes de construir los contenedores

Esta configuración cuentan con:

- PHP a travez de FPM (app)
- PHP CLI (cli)
- Servidor Nginx (web)
- Servidor de BD Mariadb (mariadb)

## Ejecutar servicios

```shell
    $> docker-compose up -d
```

## Ejecutar servicios de forma individual

```shell
    $> docker-compose up {service}
```