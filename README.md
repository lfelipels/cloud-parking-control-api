# Cloud Parking
Este projeto tem o objetivo de resolver um desáfio de projeto para criação de uma API de gestão de estacionamento e disponibilizar na plataforma Heroku.

## Habilidades
- Java
- Spring framework
- Swagger
- Teste de integração
- Integração com banco de dados PostgreSQL
- Padrões de Projeto
- Docker
- Integração contínua com GitHub e Heroku

## Configurando ambiente
### Requisitos
- Java versão 11
- Maven
- Docker

## Rodando o banco de dados
docker run --name parking-db -p 5432:5432 -e POSTGRES_DB=parking -e POSTGRES_USER=admin -e POSTGRES_PASSWORD=123 -d postgres:10-alpine
