# Gabriel — Backend Developer (.NET / C#)

Backend developer focado em **C# e .NET**, com interesse em arquitetura de software, boas práticas e construção de APIs escaláveis.

Tenho estudado e aplicado conceitos como **Clean Architecture, CQRS, SOLID e Design Patterns**, sempre buscando organizar o código de forma clara e sustentável.

---

# Tecnologias principais

Backend

* C#
* .NET / ASP.NET Core
* REST APIs
* CQRS
* MediatR
* AutoMapper
* Entity Framework Core

Frontend

* Vue.js
* JavaScript
* HTML
* CSS

Banco de dados

* SQL Server
* MongoDB

Ferramentas

* Git
* Swagger
* Docker (estudos)

---

# Projetos em destaque

### 💳 PagBank Integration — C# / ASP.NET Core

Integração completa com a API do PagBank (PagSeguro) em C#, com suporte a tokenização de cartão de crédito, cobrança segura e logging estruturado.

🚀 Funcionalidades
✅ Tokenização de cartão de crédito via API PagBank
✅ Cobrança usando card token (dados brutos nunca são persistidos)
✅ Logging estruturado com Serilog (console + arquivo rotacionado)
✅ Middleware de logging de requisições com Request ID
✅ Tratamento de erros com exceções personalizadas
✅ Suporte a ambiente Sandbox e Produção
✅ Documentação interativa via Swagger/OpenAPI
✅ Injeção de dependência nativa do ASP.NET Core

Repositório
https://github.com/Meliosam/pagbank-integration-csharp

---

### E-commerce API — Clean Architecture + CQRS

API de e-commerce construída com arquitetura limpa e separação entre **Commands e Queries**.

Tecnologias:

* .NET
* CQRS
* MediatR
* Entity Framework
* JWT
* Swagger
* Vue.js

Repositório
https://github.com/Meliosam/ecommerce-cqrs

---

### Portfolio App — Backend .NET + Frontend Vue

Aplicação fullstack demonstrando integração entre API em .NET e interface moderna em Vue.js.

Tecnologias:

* ASP.NET Core
* Entity Framework
* Vue.js
* REST API

Repositório
https://github.com/Meliosam/PortfolioApp

---

### EmailSender C#

Ferramenta escalável para envio de e-mails em lote com controle de filas, throttling e relatórios.

Tecnologias:

ASP.NET Core 8 — API REST
Entity Framework Core — ORM com PostgreSQL
MailKit — envio SMTP
System.Threading.Channels — fila in-memory (troque por RabbitMQ em produção)
xUnit + Moq — testes unitários e de integração
Docker + docker-compose — ambiente completo local

Objetivo:

 Envio unitário e em lote (bulk)
 Sistema de filas com BackgroundService
 Throttling via SemaphoreSlim
 Templates com variáveis dinâmicas ({{nome}})
 Gestão de listas (opt-in / opt-out)
 Relatórios de entrega (enviados, abertos, rejeitados)
 Integração com SendGrid / Mailgun 
 Webhooks de tracking de abertura

Repositório
https://github.com/Meliosam/EmailSender






---

# O que estou estudando atualmente

* Arquitetura limpa em projetos reais
* Padrões de projeto em C#
* Testes automatizados em .NET
* Docker e CI/CD
* Construção de APIs escaláveis

---

# GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Meliosam\&show_icons=true\&theme=tokyonight)

---

# Contato

LinkedIn
(https://www.linkedin.com/in/gabriel-alves-423410275/)

GitHub
https://github.com/Meliosam
