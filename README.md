# docker-lemp-stack
Basic docker lemp stack.

Change the MYSQL_ROOT_PASSWORD in the *docker-compose.yaml* fi;e

To start:
```
$docker-compose up -d
```

Web root folder is *www*.

To connect to the database:
```
mysql -uroot -h127.0.0.1 -p {{password}}
```
