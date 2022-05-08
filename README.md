# Primeiros passos com docker e docker-compose

## Criando imagem

docker build -t example .

## Rodando a maquina

docker run -p 3333:3333 example

## Acessando o container

docker exec -it nome_container

## Executando em realtime docker-compose

docker-compose up

## Executando o docker mesmo apos encerrar a aplicaçao

docker-compose up -d

## Iniciando container

docker-compose start

## Parando container

docker-compose stop

## Removendo container (remove tudo que foi criado)

docker-compose down

---

## docker logs

docker logs -f

## Lista de todos os containers executando

docker ps

## Lista de todos os containers

docker ps -a

## Removendo container

docker rm id_container | nome_container

## Iniciando container

docker start id_container | nome_container

## Parando container

docker stop id_container | nome_container
