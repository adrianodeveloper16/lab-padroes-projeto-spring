# Lab Padrões de Projeto Spring

Este projeto é uma implementação prática dos padrões de design no contexto do Spring Framework, focado em um sistema de gerenciamento de clientes com integração à API do ViaCEP para obtenção de endereços.

## Padrões Implementados
- **Singleton**: Utilizado no gerenciamento de instâncias de serviços.
- **Strategy/Repository**: Implementado através do Spring Data JPA para abstração de acesso a dados.
- **Facade**: Exposição de uma API REST simples que oculta a complexidade das integrações.

## Tecnologias Utilizadas
- **Spring Boot**: Framework principal para desenvolvimento da aplicação.
- **Spring Data JPA**: Para persistência de dados.
- **Spring Web**: Para criação da API REST.
- **H2 Database**: Banco de dados em memória para desenvolvimento.
- **OpenFeign**: Para integração com a API externa do ViaCEP.

## Como Executar
1. Clone o repositório.
2. Execute `mvnw spring-boot:run` (Windows) ou `./mvnw spring-boot:run` (Linux/Mac).
3. Acesse a API em `http://localhost:8080/clientes`.
