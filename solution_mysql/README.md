# Starter Solution - SQL Database

### Prerequisites
- Docker (Docker for Windows / Docker Desktop)

### Build the Docker image
```
cd ./solution_mysql
docker build -t aspire-mysql .
```
### Start the MySQL Server
```
docker-compose up
```
### Start the MySQL Client
```
docker-compose run mysql-client
```
### Start the MySQL Shell
```
docker-compose run mysqlsh-client
```
### Setup the starter database
```
mysql> source 01_create_database.sql
```
