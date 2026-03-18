# Adopet API - Challenge Alura

A **Adopet API** é uma aplicação desenvolvida em **Java 17** com **Spring Boot 3**, criada com o objetivo de facilitar e otimizar o processo de adoção de animais.  
O projeto faz parte do **Challenge Alura - Backend Java**, conectando ONGs e adotantes de forma eficiente, segura e escalável.

---

## Tecnologias Utilizadas

- **Java 17**
- **Spring Boot 3.4.2**
- **Spring Data JPA** (persistência de dados)
- **Spring Security + JWT** (autenticação e autorização)
- **Flyway** (controle de versão do banco de dados)
- **MySQL** (banco de dados relacional)
- **Thymeleaf** (engine de templates)
- **Swagger** (documentação interativa da API)
- ~~Lombok~~ *(Removido por instabilidades durante o projeto)*

---

## Funcionalidades

- Cadastro e gerenciamento de **pets** (Não concluído)
- Cadastro e gerenciamento de **adotantes**
- Processo de **adoção de pets** (Não concluído)
- Autenticação e autorização via **JWT**
- Migração de banco de dados com **Flyway**

---

## Autenticação

O sistema utiliza **Spring Security com JWT**, garantindo segurança nas operações e controle de acesso aos endpoints.

---

## Organização do Projeto

- `controller`: Camada responsável por receber as requisições HTTP.
- `service`: Lógica de negócio e manipulação dos dados.
- `repository`: Interface com o banco de dados usando Spring Data JPA.
- `domain`: Entidades e classes de modelo.

---


