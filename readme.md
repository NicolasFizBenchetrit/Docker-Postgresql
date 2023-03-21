# Docker Postgresql 🐳
This is a template to use when you need a postgresql database but you're too lazy to install it. There is a directory that includes just postgres and other that includes postgres+pgadmin

## Postgres 🐘
Currently it's using the image `postgres:15.2-alpine`

`Environment` variables are:
- User: root
- Password: root

`Ports` 5432 : 5432

It's also using a `volume`

## Pgadmin 📋

Currently it's using the image `dpage/pgadmin4`

`Environment` variables are:
- Email: admin@admin.com   
- Password: admin

`Ports` 5431 : 80

It's also using a `volume`

## Commands 🚀

⚡ Just go into the project and exect 

```
docker-compose up
```

🛑 To stop it

```
docker-compose down
```
