# dsdeliver-sds2
DS Delivery é uma aplicação full stack web e mobile construída durante a 2ª edição da **Semana DevSuperior** (#sds2), evento organizado pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

A aplicação consiste em um sistema de pedido e entrega de restaurante. Os dados da solicitação do pedido são coletados via web e posteriormente os pedidos são entregues e confirmados no app mobile.

## Modelo conceitual
![Modelo Conceitual](https://github.com/pablodantas/dsdeliver-sds2/blob/main/sds2_modelo-conceitual.png)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
## API
- Mapbox
## Implantação em produção
- Back end: Heroku
- Banco de dados: Postgresql

# Como executar o projeto

## Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/pablodantas/dsdeliver-sds2.git

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```
