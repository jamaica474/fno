# Wordpress prototype for fno

For development(tested on Ubuntu 18.04)

1) cp .env.default .env
2) docker-compose up -d
3) docker inspect -f '{{range.NetworkSettings.Networks}}{{.IPAddress}}{{end}}' fno_wordpress_1
