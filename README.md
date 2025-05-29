# Docker Workshop Uygulaması

Bu repo, Docker Docs Workshop'unu uygulamak için hazırlandı.

## Başlatmak için:
```bash
# Build
$ docker build -t workshop-flask .

# Run
$ docker run -p 5000:5000 workshop-flask

# Compose
$ docker-compose up
```

## Docker Hub'a Push Etmek için:
```bash
$ docker tag workshop-flask kullaniciadi/workshop-flask
$ docker push kullaniciadi/workshop-flask
