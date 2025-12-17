# Sistema de Pagamentos - Backend

Projeto backend desenvolvido em **Java 17** com **Spring Boot**, simulando um sistema de pagamentos com usuários, cartões e transações.

## Tecnologias Utilizadas
- Java 17
- Spring Boot
- Spring Data JPA
- PostgreSQL
- Maven
- JUnit

## Funcionalidades
- Cadastro de usuários
- Cadastro de cartões vinculados a usuários
- Registro de transações
- Estrutura preparada para microsserviços

## Como Executar o Projeto
1. Clonar o repositório
2. Criar banco PostgreSQL chamado `pagamentos`
3. Ajustar usuário e senha no `application.yml`
4. Executar:
```
mvn spring-boot:run
```

## Endpoints (exemplo)
- POST /users
- POST /cards
- POST /transactions

## Objetivo
Projeto criado para fins de estudo e portfólio, seguindo boas práticas de desenvolvimento backend com Java e Spring Boot.
