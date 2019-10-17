# Useful docker compose

## WordPress

```
docker-compose -f $(t=$(mktemp) && curl https://raw.githubusercontent.com/masakuni-ito/useful-docker-compose/master/wordpress.yml > $t && echo $t) up
```
