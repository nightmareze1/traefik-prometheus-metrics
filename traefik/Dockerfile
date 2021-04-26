FROM traefik:v1.7.30-alpine
EXPOSE 8080 80
COPY traefik.toml /etc/traefik/traefik.toml

CMD ["/traefik --api --docker"]
