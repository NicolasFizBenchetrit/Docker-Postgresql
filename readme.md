# Docker Postgresql
This is a template to use when you need a postgresql database but you're too lazy to install it 🐳

## Postgres 🐘
Currently it's using the image `postgres:15.2-alpine`

`Environment` variables are:
- user: root
- password: root

`Ports`: 5432:5432

It's also using a `volume`

## Pgadmin 📋

Currently it's using the image `dpage/pgadmin4`

`Environment` variables are:
- email: admin@admin.com   
- password: admin

`Ports`: 5431:80

## Commands 🚀

Just go into the projecto and exect

```
docker-compose up
```

And if you want to stop it

```
docker-compose down
```