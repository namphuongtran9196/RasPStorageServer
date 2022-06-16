# Server

Replace the server name with your server name.
in nginx_uwsgi/server.conf
```bash
server_name user.com www.user.com;
```

Replace the server name with your server name.
```bash
ALLOWED_HOSTS = ["yourserver.com","www.yourserver.com"]
```

Change your secret_key.txt with a new secret key.

docker build -t server -f Dockerfile . --force-rm

docker-compose -f docker-compose.yml down
docker-compose -f docker-compose.yml up -d