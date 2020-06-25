# Docker compose for PostgreSQL and pgAdmin
## Configuration
Configuration can be obtained by editing files in `secrets` folder. 
### PostgreSQL
- PostgreSQL default database: `secrets/postgres_db`
- PostgreSQL username: `secrets/postgres_user`
- PostgreSQL password: `secrets/postgres_password`

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
