# Traefik
Traefik docker-compose config

Create a .env File with following Variables:
TRAEFIK_AUTH=
TRAEFIK_URL=traefik.example.com


Create TRAEFIK_AUTH
echo $(htpasswd -nb user password) | sed -e s/\\$/\\$\\$/g
