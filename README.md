<h1 align="center">API - Java com Springboot</h1>

<p align="center">
  <img alt="API" src="https://img.shields.io/static/v1?label=Springboot&message=API&color=8257E5&labelColor=000000"  />
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
</p>

<p align="center">
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-requisitos">Requisitos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-arquitetura">Arquitetura</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-roadmap">Roadmap</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-referências">Referências</a>
</p>

<p align="center">
  <img alt="API" src="data/estacionamento.jpg">
</p>

## 💡 Projeto

- REST API com Spring Boot 3, Spring Security, Spring Data JPA, JWT, Swagger, Testes end2end, DTO

```
O objetivo será desenvolver um sistema de gerenciamento para estacionamento. Após levantamento
de requisitos junto ao cliente, listaremos as especificações a serem desenvolvidas pela equipe de
back-end.
```

```
Importante salientar que o sistema será uma API Rest com autenticação por Json Web
Token (JWT).
```

```
O sistema deverá possuir uma documentação dos recursos disponíveis pela API, para
servir de apoio a equipe de front-end.
```

## ✅ Requisitos

1. [ ] [Requisitos e Configurações](./doc/Requisitos-configuracoes.md)
2. [ ] [Requisitos / Usuários](./doc/Requisitos-usuarios.md)
3. [ ] [Requisitos / Autenticação](./doc/Requisitos-autenticacao.md)
4. [ ] [Requisitos / Clientes](./doc/Requisitos-clientes.md)
5. [ ] [Requisitos / Vagas](./doc/Requisitos-vagas.md)
6. [ ] [Requisitos / Estacionamentos](./doc/Requisitos-estacionamentos.md)


## 💡 Arquitetura

- [Arquitetura REST](./doc/api-rest-arquitetura.md)
- [API REST - Fundamentos](./doc/api-rest-fundamentos.md)
- [API REST - Boas práticas](./doc/api-rest-boaspraticas.md)
- [Padrão de Projetos DTO](./doc/padrao-projeto-dto.md)

## ✨ Tecnologias

- `Spring Boot` (Desenvolver a API REST,  aproveitando sua ampla gama de recursos e facilidades de configuração)
- `Spring Security` (Implementar camadas de segurança em sua API, protegendo endpoints sensíveis e autenticando usuários de forma segura)
- `JWT` (Integração do JWT (JSON Web Token) permitirá a autenticação e autorização de forma stateless, garantindo a segurança dos seus serviços)
- `OpenAPI 3 e Swagger` (Gerar documentação dos recursos da API.)
- `Data Transfer Objects` - DTO (Definir objetos específicos para transferir dados entre as camadas da aplicação, evitando o vazamento de informações sensíveis e reduzindo o tráfego desnecessário)
- `Bean Validation` (validar entradas de dados, parâmetros de API e objetos de domínio, garantindo a integridade e a consistência dos dados)
- `JasperReports` (Consultar informações importantes retornadas em um relatório em formato PDF)
- `Spring Data JPA` (Facilita a integração com bancos de dados relacionais)

## 👣 Roadmap

- Desenvolver uma API Rest com Spring Boot 3
- Implementar Autenticação utilizando Tokens JWT
- Operações de CRUD com Spring Data JPA
- Documentar uma API Rest com o OpenAPI e Swagger
- Validação de campos com Jakarta Bean Validation
- Boas práticas a se adotar no desenvolvimento de uma API Rest
- Adicionar Segurança na API Rest com Spring Security
- Trabalhar com camada de testes de ponto a ponto (End2End)
- Trabalhar com Postman como plataforma cliente
- Trabalhar com padrão DTO (Data Transfer Object) e ModelMapper
- Configuração de Auditoria com Spring-JPA-Auditing

## 📄 Referências

- [O que é ser idempotente em REST?](https://www.infoq.com/br/news/2013/05/idempotent/)

- [HTTP response status codes](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods)

- [Springboot](https://spring.io/guides/gs/spring-boot)

- [Spring Initializr](https://start.spring.io/)

- [HTTP headers](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers)

- [Equals Method in Java: Best Practices](https://codegym.cc/groups/posts/264-equals-and-hashcode-methods-best-practices)

- [Entendendo o equals e hashCode](https://blog.algaworks.com/entendendo-o-equals-e-hashcode/)