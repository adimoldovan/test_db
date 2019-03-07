# Run with docker
```
docker-compose up -d
cd db_data
mysql -h 127.0.0.1 --port 3326 -u root -p < employees.sql
```
