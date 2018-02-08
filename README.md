# NextCloud into docker using docker-compose

1 . copy db.env.dist into db.env and fill the follow fields

```
MYSQL_ROOT_PASSWORD=
MYSQL_PASSWORD=
MYSQL_DATABASE=nextcloud
MYSQL_USER=nextcloud
```


2 . copy web.env.dist into web.env and fill the follow fields
```
VIRTUAL_HOST=
LETSENCRYPT_HOST=
LETSENCRYPT_EMAIL=
```

3 . run the follow command:
```
docker-compose up -d
```

4 . You are done!

