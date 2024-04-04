# glpi-template-docker-nginx

template docker nginx pra glpi

## procedimentos

- descompactar glpi e rodar

```bash
tar zxvf glpi-10.0.14.tgz && docker-compose up --build
```

- entrar no docker

```bash
docker exec -it $(docker ps | grep -i glpixpto | awk '{print $1}') bash
```

- acessar o glpi 0.0.0.0:8042
  - HOST=db-maria
  - MARIADB_USER=x123
  - MARIADB_PASSWORD=x123
