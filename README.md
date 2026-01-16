Title
Delivery Tech API



## Use

API base para um sistema de delivery, desenvolvida com Spring Boot e Java 21.
Este projeto faz parte de uma prática de configuração de ambiente e estrutura inicial
de uma aplicação backend moderna.



## Tech Stack

• Java 21 (LTS)

• Spring Boot 3.2.x

• Spring Web

• Spring Data JPA

• H2 Database

• Maven

• Git \& GitHub


## Run Locally

1. Clone o repositório
   git clone https://github.com/johnny-dll/deliverytech.git
2. Acesse a pasta do projeto
   cd deliverytech/delivery-api
3. Execute a aplicação
   ./mvnw spring-boot:run
4. Acesse no navegador
   http://localhost:8080/health
   

## API Reference (ou "Endpoints")

GET /health
Retorna o status da aplicação, timestamp e versão do Java.

GET /info
Retorna informações básicas da aplicação.

GET /h2-console
Console do banco H2 em memória.


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

server.port=8080
spring.datasource.url=jdbc:h2:mem:deliverydb



## Autor

* João Paulo Llorca
* [@GitHub](https://www.github.com/johnny-dll)
* [@LinkedIn](https://www.linkedin.com/in/joaopaulozllorca/)
  
