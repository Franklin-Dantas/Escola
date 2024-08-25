# CRUD de Alunos em Java com Spring Boot

Este projeto é um sistema CRUD (Create, Read, Update, Delete) simples para gerenciar dados de alunos de uma escola.
O projeto utiliza o framework Spring Boot e está conectado a um banco de dados SQL Server.
Além disso, a documentação da API é gerada automaticamente usando o Swagger.

## Tecnologias Utilizadas

- **Java 11+**: Linguagem de programação utilizada.
- **Spring Boot**: Framework utilizado para simplificar a criação de aplicativos Java.
- **Spring Data JPA**: Usado para a camada de persistência, que facilita a interação com o banco de dados.
- **SQL Server**: Banco de dados relacional utilizado.
- **Swagger/OpenAPI**: Usado para a documentação da API REST.
- **Maven**: Ferramenta de gerenciamento de dependências e automação de build.

## Configuração do Projeto

### Pré-requisitos

Certifique-se de ter instalado:

- [Java JDK 11+](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
- [Maven](https://maven.apache.org/install.html)
- [SQL Server](https://www.microsoft.com/pt-br/sql-server/sql-server-downloads)

### Configuração do Banco de Dados

1. **Instale o SQL Server** e certifique-se de que ele esteja em execução.
2. Crie um banco de dados chamado `escola`.
3. Atualize as credenciais e a URL do banco de dados no arquivo `src/main/resources/application.properties`.
