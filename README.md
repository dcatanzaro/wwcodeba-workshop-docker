# wwcodeba-workshop-docker

Workshop de Docker - Women Who Code | Buenos Aires

### Entorno de desarrollo
Build de docker
```sh
docker build -t wwcodeba-docker .
```

Correr el container
```sh
docker run -p 3000:3000 wwcodeba-docker
```

### Entorno de producción
Build de docker
```sh
docker build -f Dockerfile-prod -t wwcodeba-docker .
```

Correr el container
```sh
docker run -p 5000:5000 wwcodeba-docker
```
