Docker Postgres run:

docker run --name postgres-spring -e POSTGRES_PASSWORD=passwd -d -p 5432:5432 postgres:alpine
