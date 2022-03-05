# docker-laravel-nuxt

a template for Nuxt.js + Laravel(API) on docker

## to run

```sh
cd docker
docker-composer up -d
docker exec -it docker-node-1 sh
(in docker-node-1)# yarn install
(in docker-node-1)# yarn dev
```

with your web browser, access http://localhost:8000/ => nuxt.js, http://localhost:8000/api => Laravel

