# Web Services com Spring Boot e JPA / Hibernate
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/JuniorAC90/workshop-springboot3-jpa/blob/main/LICENSE) 

# Sobre o projeto

É uma aplicação back end construída durante o [curso](https://www.udemy.com/course/java-curso-completo) **Java Completo Programação Orientada a Objetos + Projetos** organizado pelo professor Nélio Alves no site da Udemy.

A aplicação consiste no registro de pedidos, com cadastro, atualização e leitura de Clientes, Produtos, Itens e Pedidos.

## Modelo conceitual
![Modelo Conceitual](https://github.com/JuniorAC90/workshop-springboot3-jpa/blob/main/assets/modelo-conceitual.png)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
## Implantação em ambiente teste
- Banco de dados: H2

# Como executar o projeto

## Back end
Pré-requisitos: Java 17

```bash
# clonar repositório
git clone https://github.com/JuniorAC90/workshop-springboot3-jpa.git

# entrar na pasta do projeto 
cd workshop-springboot3-jpa

# executar o projeto
./mvnw spring-boot:run
```
## Rotas
Exemplos:

- GET - "/categories" - Lista todas as categorias cadastradas 
- GET - "/categories/1" - Lista a categoria de Id 1

![Categorias](https://github.com/JuniorAC90/workshop-springboot3-jpa/blob/main/assets/categorias.png)

- GET - "/orders" - Lista todas os pedidos cadastrados 
- GET - "/orders/1" - Lista o pedido de Id 1

![Pedidos](https://github.com/JuniorAC90/workshop-springboot3-jpa/blob/main/assets/pedidos.png)

- GET - "/products" - Lista todas os produtos cadastrados 
- GET - "/products/1" - Lista o produto de Id 1

![Produtos](https://github.com/JuniorAC90/workshop-springboot3-jpa/blob/main/assets/produtos.png)

- GET - "/users" - Lista todas os clientes cadastrados 
- GET - "/users/1" - Lista o cliente de Id 1
  
![Clientes](https://github.com/JuniorAC90/workshop-springboot3-jpa/blob/main/assets/clientes.png)

- POST - "/users" - Cadastra um novo cliente.
  
![Cadastro de Cliente](https://github.com/JuniorAC90/workshop-springboot3-jpa/blob/main/assets/json-cadastro-cliente.png)

- PUT - "/users/1" - Atualiza o cliente com o Id 1.
  
![Atualização de Cliente](https://github.com/JuniorAC90/workshop-springboot3-jpa/blob/main/assets/json-atualiza-cliente.png)
  
- DELETE - "/users/1" - Deleta o cliente com o Id 1.

# Autor

Aloizio da Costa Junior

https://www.linkedin.com/in/JuniorAC90
