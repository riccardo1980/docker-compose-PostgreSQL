# Docker compose for PostgreSQL and pgAdmin
## Configuration
### PostgreSQL
- `POSTGRES_DB: postgres`  
- `POSTGRES_USER: postgres`  
- `POSTGRES_PASSWORD: secret`
### pgAdmin
- `PGADMIN_DEFAULT_EMAIL: admin@linuxhint.com`  
- `PGADMIN_DEFAULT_PASSWORD: secret`  

PostgreSQL service is reachable from pgadmin interface as `pgsql-server` 

![img](./img/configuration.png)

## Deplyment steps
### Deploy services
```
docker-compose up -d
```
### Shut down services
```
docker-compose down
```
