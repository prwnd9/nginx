# nginx

## Usage
```bash
docker compose pull
docker compose up -d
docker compose logs -f
# localhost:8080

# basic auth
docker compose exec nginx sh
cd /etc/nginx
apk add --no-cache apache2-utils
htpasswd -c htpasswd test
test

# check config
nginx -t
```
