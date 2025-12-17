<div align="center">

# Enéas Almeida

### Engenheiro de Software | Arquiteto de Soluções | Especialista em Microserviços

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Kubernetes](https://img.shields.io/badge/kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)

</div>

---

## Resumo Executivo

**9+ anos** de experiência em desenvolvimento de software com foco em **arquitetura de microserviços**, **sistemas distribuídos** e **alta performance**. Especialista em construir soluções escaláveis que processam milhões de transações financeiras mensalmente.

### Destaques Profissionais

- **Impacto de Negócio:** Desenvolvedor principal de microserviços que processam **R$ 6 milhões/mês** no Sicoob
- **Arquitetura:** 11 microserviços em produção com integrações complexas (Oracle, Vtex, Siebel, Salesforce)
- **Stack Completo:** Backend (Node.js, Java, Go) + Frontend (Vue.js, React, Angular)
- **DevOps & Cloud:** Kubernetes, AWS, Docker, Terraform, CI/CD
- **Padrões:** Clean Architecture, DDD, CQRS, Event-Driven, gRPC, GraphQL

### Formação & Certificações

- **Bacharel em Engenharia de Computação** - Instituto Federal da Paraíba
- **Pós-graduação em Arquitetura de Software Distribuído** - PUC Minas
- **MBA em Engenharia de Software com IA** - Full Cycle (em andamento)
- **Go Expert** - Full Cycle
- **Especialista Microserviços com Java** - AlgaWorks (em andamento)

---

## Experiência Destacada

### Sicoob - Desenvolvedor Principal de Microserviços

**Impacto:** Microserviços em produção gerando **R$ 6 milhões/mês**

Responsável pela migração e desenvolvimento de **11 microserviços** (4 principais + 7 auxiliares) para o programa de fidelidade do cartão Sicoob, com transferência de pontos para:

- Livelo
- Decolar
- Smiles
- Azul
- Latam

**Integrações Complexas:**
- Oracle
- Vtex
- Siebel
- Salesforce
- Diversos webservices de validação

**Processo de Desenvolvimento:**

```mermaid
graph LR
    A[Análise de Requisitos] --> B[Modelagem BPMN/UML]
    B --> C[Desenvolvimento]
    C --> D[Testes & QA]
    D --> E[Deploy Produção]
    E --> F[Monitoramento]
    F --> G[Otimização Contínua]
```

**Arquitetura de Solução:**

<div align="center">
<img src="./images/fluxo-smiles.png" alt="Fluxo de Microserviços Sicoob" width="800"/>
<br/>
<i>Diagrama BPMN - Fluxo de transferência de pontos (dados sensíveis removidos)</i>
</div>

**Tecnologias:** Java, Spring Boot, Microserviços, Oracle, REST APIs, Mensageria, BPMN

---

## Projetos Principais

### [Bridge - Arquitetura gRPC com Java](https://github.com/eneas-almeida/bridge)

<a href="https://github.com/eneas-almeida/bridge">
  <img src="./images/java-grpc.png" alt="Bridge gRPC Architecture" width="700"/>
</a>

Arquitetura de microserviços com comunicação gRPC de alta performance entre serviços REST e backend.

**Arquitetura:**

```
┌──────────────┐     HTTP/REST      ┌──────────────┐      gRPC       ┌──────────────┐     HTTP
│   Cliente    │ ─────────────────> │  API Service │ ──────────────> │People Service│ ──────────> JSONPlaceholder
│  (Browser)   │                    │  (Port 8081) │                 │ (Port 9090)  │             (External API)
└──────────────┘                    └──────────────┘                 └──────────────┘
```

**Stack:** ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) ![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=flat-square&logo=google&logoColor=white) ![WebFlux](https://img.shields.io/badge/WebFlux-6DB33F?style=flat-square&logo=spring&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

### [Sensors - Microserviços com RabbitMQ](https://github.com/eneas-almeida/ms-sensors-central)

<a href="https://github.com/eneas-almeida/ms-sensors-central">
  <img src="./images/microservicos.png" alt="Microservices Architecture" width="700"/>
</a>

Sistema de microserviços com comunicação assíncrona via RabbitMQ, implementando padrões de resiliência.

**Evolução Arquitetural:**
1. Sistema monolítico inicial
2. Refatoração para microserviços
3. Implementação de message broker
4. Padrões de retry e dead letter queue

**Stack:** ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white)

---

### [Luizalabs - Clean Architecture Fullstack](https://github.com/eneas-almeida/luizalabs)

<p align="center">
  <a href="https://github.com/eneas-almeida/luizalabs">
    <img src="./images/tela-resp-lista.png" alt="Luizalabs Application" width="700"/>
  </a>
</p>

Aplicação fullstack com Clean Architecture, TDD e design patterns avançados.

**Características:**
- Backend em Node.js com Clean Architecture
- Frontend responsivo em Vue.js
- Testes unitários com Jest (alta cobertura)
- Padrões: Strategy, Adapter, Factory, Builder
- Documentação técnica completa

**Stack:** ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white) ![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white) ![Clean Architecture](https://img.shields.io/badge/Clean_Architecture-blue?style=flat-square)

---

### [Bekid - IA para Monitoramento Escolar](https://github.com/eneas-almeida/bekid)

<p align="center">
  <a href="https://github.com/eneas-almeida/bekid">
    <img src="./images/diagram-v5.png" alt="Bekid Architecture" width="700"/>
  </a>
</p>

Sistema de mapeamento de emoções com IA para combate ao bullying escolar.

**Solução:**
- Monitoramento em tempo real via IA
- Análise comportamental e emocional
- Dashboard para gestores educacionais
- WebSocket para atualizações em tempo real

**Status:** Em produção

<a href="https://github.com/eneas-almeida/bekid">
  <img src="./images/bekid.png" alt="Bekid Screens" width="700"/>
</a>

**Stack:** ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white) ![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white) ![AI/ML](https://img.shields.io/badge/AI/ML-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)

---

### [MyPoint - Sistema de Ponto com Alta Concorrência](https://github.com/eneas-almeida/mypoint)

<p align="center">
  <a href="https://github.com/eneas-almeida/mypoint">
    <img src="./images/architeture-v1.png" alt="MyPoint Architecture" width="700"/>
  </a>
</p>

Sistema de registro de ponto com arquitetura otimizada para alta concorrência.

**Desafio Resolvido:**
Múltiplas consultas paralelas e densas no banco de dados que levam à exaustão de recursos.

**Solução:**
- Arquitetura de microserviços
- Filas com RabbitMQ
- Cache distribuído
- WebSocket para atualizações em tempo real

**Stack:** ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white) ![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white) ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white) ![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white) ![Microservices](https://img.shields.io/badge/Microservices-blue?style=flat-square)

---

### [Events-Nest - CQRS + Clean Architecture](https://github.com/eneas-almeida/events-nest)

Microserviço baseado em eventos com CQRS pattern e Clean Architecture em NestJS.

**Padrões Implementados:**
- CQRS (Command Query Responsibility Segregation)
- Event Sourcing
- Clean Architecture
- Domain-Driven Design (DDD)

**Stack:** ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white) ![CQRS](https://img.shields.io/badge/CQRS-purple?style=flat-square) ![DDD](https://img.shields.io/badge/DDD-orange?style=flat-square)

---

## Stack Técnica Completa

### Backend

#### Linguagens & Frameworks
![Java](https://img.shields.io/badge/Java_8/11/17/21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

#### Arquitetura & Design
![Clean Architecture](https://img.shields.io/badge/Clean_Architecture-blue?style=for-the-badge)
![DDD](https://img.shields.io/badge/DDD-orange?style=for-the-badge)
![CQRS](https://img.shields.io/badge/CQRS-purple?style=for-the-badge)
![Microservices](https://img.shields.io/badge/Microservices-green?style=for-the-badge)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=for-the-badge&logo=google&logoColor=white)

#### Banco de Dados
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

#### Mensageria & Eventos
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)
![AWS SQS](https://img.shields.io/badge/AWS_SQS-FF4F8B?style=for-the-badge&logo=amazon-aws&logoColor=white)

### Frontend

![Vue.js](https://img.shields.io/badge/Vue.js_2/3-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Vuetify](https://img.shields.io/badge/Vuetify-1867C0?style=for-the-badge&logo=vuetify&logoColor=white)
![PrimeVue](https://img.shields.io/badge/PrimeVue-41B883?style=for-the-badge)
![Quasar](https://img.shields.io/badge/Quasar-1976D2?style=for-the-badge&logo=quasar&logoColor=white)

### DevOps & Cloud

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Istio](https://img.shields.io/badge/Istio-466BB0?style=for-the-badge&logo=istio&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)

### Monitoramento & Observabilidade

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=for-the-badge&logo=sentry&logoColor=white)

---

## Algoritmos & Bibliotecas em Produção

Soluções otimizadas desenvolvidas e utilizadas em ambientes de produção:

| Tecnologia | Projeto | Solução |
|:----------:|---------|---------|
| ![JavaScript](https://img.shields.io/badge/JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | [Cache Parallel](https://github.com/eneas-almeida/cache-parallel) | Requisições externas com paralelismo otimizado |
| ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) | [Fetch](https://github.com/eneas-almeida/go-fetch) | Requisições paralelas com fallback automático |
| ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) | [Upload](https://github.com/eneas-almeida/go-upload) | Upload AWS S3 com estratégia de fallback |
| ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) | [gRPC](https://github.com/eneas-almeida/grpc) | Implementação gRPC de alta performance |
| ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) | [GraphQL](https://github.com/eneas-almeida/graphql) | API GraphQL com resolvers otimizados |

---

## Guias Técnicos & Documentação

Documentação técnica criada para repasse de conhecimento:

<table>
<tr>
<td width="50%">

### [Clean Architecture](https://github.com/eneas-almeida/customer-clean-architecture)

<p align="center">
  <a href="https://github.com/eneas-almeida/customer-clean-architecture">
    <img src="./images/camadas.png" width="350"/>
  </a>
</p>

Guia completo sobre camadas e implementação de Clean Architecture em microserviços.

</td>
<td width="50%">

### [gRPC](https://github.com/eneas-almeida/grpc)

<p align="center">
  <a href="https://github.com/eneas-almeida/grpc">
    <img src="./images/goandgrpc.png" width="250"/>
  </a>
</p>

Implementação e boas práticas de gRPC com Go.

</td>
</tr>
<tr>
<td width="50%">

### [GraphQL](https://github.com/eneas-almeida/graphql)

<p align="center">
  <a href="https://github.com/eneas-almeida/graphql">
    <img src="./images/graphmaisgo.png" width="350"/>
  </a>
</p>

Guia de implementação GraphQL com Go.

</td>
<td width="50%">

### [RabbitMQ](https://github.com/eneas-almeida/rabbitmq)

<p align="center">
  <a href="https://github.com/eneas-almeida/rabbitmq">
    <img src="./images/rabbitmq.webp" width="250"/>
  </a>
</p>

Padrões e implementação de mensageria com RabbitMQ.

</td>
</tr>
</table>

### [Kafka](https://github.com/eneas-almeida/kafka)

<p align="center">
  <a href="https://github.com/eneas-almeida/kafka">
    <img src="https://github.com/eneas-almeida/kafka/raw/master/media/kafka/kafka-1-2.gif" width="600"/>
  </a>
</p>

**Implementações:**
- [Kafka + NestJS](https://github.com/eneas-almeida/kafka/tree/master/kafka-nestjs)
- [Kafka + Node.js](https://github.com/eneas-almeida/kafka/tree/master/kafka-nodejs)
- [Kafka + Python](https://github.com/eneas-almeida/kafka/tree/master/kafka-python)
- [Serviço TypeScript](https://github.com/eneas-almeida/customer-clean-architecture/blob/main/src/infra/services/queue/kafka-queue.service.ts)

### [BFF (Backend for Frontend)](https://github.com/eneas-almeida/bff)

<p align="center">
  <a href="https://github.com/eneas-almeida/bff">
    <img src="./images/bff.gif" width="600"/>
  </a>
</p>

Padrão BFF para otimização de APIs por cliente.

---

## Outros Projetos Relevantes

<details>
<summary><b>Projetos Fullstack & APIs</b></summary>

### [Bestore - E-commerce API](https://github.com/eneas-almeida/bestore)

API REST completa para e-commerce com Java Spring Boot e MySQL.

<img src="https://github.com/eneas-almeida/bestore/raw/master/media/diagrams/diagrama-v5.png" width="600"/>

**Stack:** ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

---

### [Go Account API - Clean Architecture](https://github.com/eneas-almeida/go-account-api-mongodb)

<p align="center">
  <a href="https://github.com/eneas-almeida/go-account-api-mongodb">
    <img src="./images/fiber.png" width="400"/>
  </a>
</p>

Microserviço em Go com Clean Architecture, Fiber Framework e MongoDB.

**Stack:** ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Fiber](https://img.shields.io/badge/Fiber-00ACD7?style=flat-square)

---

### APIs Produção

[**Evasão Escolar**](https://github.com/eneas-almeida/api-evasao-escolar-nestjs) - Análise de evasão escolar com NestJS, TypeORM e PostgreSQL. **Em produção.**

[**Tindin**](https://github.com/eneas-almeida/api-tindin) - Controle de aulas com Node.js, MongoDB e testes Jest com alta cobertura.

[**Places to Know**](https://github.com/eneas-almeida/api-places-to-know) - API de locais turísticos com integração externa, filtros e paginação.

</details>

<details>
<summary><b>Estudos de Caso & Arquitetura</b></summary>

### Autenticação & Segurança

[**Auth NestJS**](https://github.com/eneas-almeida/auth-nest) - Sistema completo de autenticação com JWT, interceptors, logger e testes.

**Stack:** ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white) ![TypeORM](https://img.shields.io/badge/TypeORM-FE0803?style=flat-square) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

---

### Prisma ORM

[**NestJS + Prisma**](https://github.com/eneas-almeida/nestjs-with-prisma) - API com Prisma, Swagger, validação, paginação e exception handling.

[**Node.js + Prisma**](https://github.com/eneas-almeida/nodejs-prisma) - Arquitetura Package by Feature com testes unitários.

---

### TDD & Domain Modeling

[**VacinaPB**](https://github.com/eneas-almeida/vacina_pb) - TDD com TypeScript, padrões de projeto e modelagem de domínio rica (DDD).

[**Modelagem de Entidade (Tiny)**](https://github.com/eneas-almeida/modelagem_entidade) - Modelagem com Either pattern para tratamento elegante de erros.

---

### Performance & DevOps

[**Teste de Exaustão (JMeter)**](https://github.com/eneas-almeida/teste_exaustao) - Testes de carga e performance com JMeter.

[**Deploy CI/CD**](https://github.com/eneas-almeida/deploy_codeship) - Integração contínua com deploy em QA e Produção.

[**Create Releases**](https://github.com/eneas-almeida/create_releases) - Automação de releases no GitHub.

---

### Fullstack

[**Séries TV**](https://github.com/eneas-almeida/series-tv-backend) - Spring Boot + Angular 12 fullstack.

[**Grisoli**](https://github.com/eneas-almeida/grisoli) - Microserviços com Node.js, Spring Boot, RabbitMQ, Docker e CI/CD.

</details>

<details>
<summary><b>GoLang - Projetos & Algoritmos</b></summary>

<p align="center">
  <img src="./images/golang.png" width="170px"/>
</p>

### Recursos & Tutoriais

- [Instalação e Configuração](https://github.com/eneas-almeida/golang)
- [Go Routines - Trabalhadores Eficientes](https://github.com/eneas-almeida/go-routines/)
- [HTTP Retry com Exponential Backoff](https://github.com/eneas-almeida/go/tree/main/projects/go-http-retry-backoff)
- [Algoritmos](https://github.com/eneas-almeida/go/tree/main/projects/go-algorithms)
- [Dependency Injection](https://github.com/eneas-almeida/go/tree/main/projects/go-injections)
- [DI com Google Wire](https://github.com/eneas-almeida/go/tree/main/projects/go-injections-with-google-wire)
- [API ViaCEP](https://github.com/eneas-almeida/go/tree/main/projects/go-viacep)
- [Encoder](https://github.com/eneas-almeida/go/tree/main/projects/go-encoder)
- [Database](https://github.com/eneas-almeida/go/tree/main/projects/go-database)
- [Clean Architecture](https://github.com/eneas-almeida/go/tree/main/projects/go-clean-architecture-basic)
- [Deploy](https://github.com/eneas-almeida/go/tree/main/projects/go-deploy)
- [Validations](https://github.com/eneas-almeida/go/tree/main/projects/go-validations)
- [Environment Config](https://github.com/eneas-almeida/go/tree/main/projects/go-configs-dot-env)
- [Concorrência](https://github.com/eneas-almeida/concorrencia-go)

</details>

<details>
<summary><b>Node.js - Resiliência & Performance</b></summary>

### Projetos

[**HTTP Retry com Axios**](https://github.com/eneas-almeida/nodejs-http-retry/tree/main) - Resiliência de chamadas HTTP com retry automático.

[**Node.js Base API**](https://github.com/eneas-almeida/nodejs-base) - Template base para APIs Node.js.

**Stack:** ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)

</details>

<details>
<summary><b>Kubernetes & Infraestrutura</b></summary>

### Projetos

[**Kubernetes**](https://github.com/eneas-almeida/k8s) - Configurações e manifestos K8s.

[**Istio**](https://github.com/eneas-almeida/istio) - Service mesh com Istio.

**Stack:** ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Istio](https://img.shields.io/badge/Istio-466BB0?style=flat-square&logo=istio&logoColor=white)

</details>

<details>
<summary><b>Vue.js - Projetos & Componentes</b></summary>

### Vue.js 3

[**Vue 3 + Pinia + CASL ACL**](https://github.com/eneas-almeida/vue3-with-casl) - Controle de acesso com Vue 3.

[**Vue 3 Composition API**](https://github.com/eneas-almeida/vue3-composition-api) - Props, emit e watch com Composition API.

---

### Socket.io

[**Socket.io com Vue/Node/NestJS**](https://github.com/eneas-almeida/socketio_vuejs_nodejs) - Comunicação real-time com validação JWT e padrão Observer.

---

### NestJS Avançado

[**NestJS + Value Objects**](https://github.com/eneas-almeida/nestjs/tree/master/nestjs-value-object) - Domínios ricos com Value Objects, Either e DTOs.

---

### Estudos Vue.js

- [Testes com Jest](https://github.com/eneas-almeida/vuejs_tests)
- [Checkbox Select](https://github.com/eneas-almeida/vuejs_checkbox)
- [Select All](https://github.com/eneas-almeida/vuejs_select_all)
- [Computed Properties](https://github.com/eneas-almeida/vuejs_computed)
- [Forms](https://github.com/eneas-almeida/vuejs_form)
- [Routing](https://github.com/eneas-almeida/vuejs_route)
- [Props](https://github.com/eneas-almeida/vuejs_props)
- [Slots](https://github.com/eneas-almeida/vuejs_slots)
- [Componentes Dinâmicos](https://github.com/eneas-almeida/vuejs_component_dinamic)
- [Vuex](https://github.com/eneas-almeida/vuejs_vuex)
- [Axios](https://github.com/eneas-almeida/vuejs_axios)
- [Todo + LocalStorage](https://github.com/eneas-almeida/vuejs_todo)
- [Burger Shop](https://github.com/eneas-almeida/vuejs_burguer)
- [Refs By Copy](https://github.com/eneas-almeida/vuejs_props_by_copy)
- [CSS](https://github.com/eneas-almeida/vuejs_css)
- [Filters](https://github.com/eneas-almeida/vuejs_filters)
- [Mixins](https://github.com/eneas-almeida/vuejs_mixins)

</details>

<details>
<summary><b>JavaScript - Algoritmos & Utilidades</b></summary>

### Algoritmos Desenvolvidos

[**Read TXT → XLSX**](https://github.com/eneas-almeida/javascript/blob/master/codes/readfileTxtAndConvertValuesToXlsx.js) - Conversão de TXT para Excel com formatação monetária.

[**Get Level**](https://github.com/eneas-almeida/javascript/blob/master/codes/getLevel.js) - Eliminação de múltiplos IF/ELSE para intervalos.

[**Parse DTO**](https://github.com/eneas-almeida/javascript/blob/master/codes/parseDTO.js) - Conversão CamelCase → SnakeCase.

[**Filter Properties**](https://github.com/eneas-almeida/javascript/blob/master/codes/fIlterPropertiesInArrayObjects.js) - Filtro de propriedades em objetos.

[**MAP Enum**](https://github.com/eneas-almeida/javascript/blob/master/codes/mapEnumObjects.js) - Técnica para eliminar IFs usando enums.

[**Todos os Scripts**](https://github.com/eneas-almeida/javascript/tree/master/codes)

---

### Testes Unitários

[**Mock Tests**](https://github.com/eneas-almeida/javascript/tree/master/codes/tests/mocks) - Testes com mocks e bibliotecas nativas.

[**Stub com Mocks**](https://github.com/eneas-almeida/javascript/tree/master/codes/tests/stubs) - Simulação de requisições API.

</details>

<details>
<summary><b>Projetos Acadêmicos</b></summary>

| Projeto | Descrição | Imagem |
|---------|-----------|--------|
| [**Sistemas Embarcados**](https://github.com/eneas-almeida/sistemas-embarcados) | Projeto final - Engenharia de Computação IFPB | <img src="./images/placa-1.jpeg" width="300"/> |
| [**Prototipagem**](https://github.com/eneas-almeida/shield_dados) | Projeto final de Prototipagem - IFPB | <img src="./images/shield.png" width="300"/> |

</details>

<details>
<summary><b>Projetos Legados</b></summary>

### [Oráculo - Sistema Financeiro](https://github.com/eneas-almeida/oraculo)

Sistema de gerenciamento financeiro desenvolvido em HTML, JavaScript e jQuery.

<p align="center">
  <img src="./images/oraculo.png" width="600"/>
</p>

---

### [Gerente RH](https://github.com/eneas-almeida/gerente-rh)

Sistema de gerenciamento de funcionários em C# MVC com Microsoft SQL Server.

<p align="center">
  <img src="./images/gerente.png" width="600"/>
</p>

</details>

---

## Técnicas & Práticas de Desenvolvimento

<details>
<summary><b>Metodologias & Padrões</b></summary>

### Práticas de Código

- Fail First Development
- Conventional Commits
- Versionamento de módulos
- Test-Driven Development (TDD)
- Desenvolvimento guiado a interfaces
- Modelagem de entidades ricas (DDD)
- Tratamento de exceções com Either

### Padrões de Projeto

- Strategy Pattern
- Adapter Pattern
- Builder Pattern
- Factory Pattern
- Observer Pattern
- Repository Pattern
- Dependency Injection

### Arquitetura

- Clean Architecture
- Domain-Driven Design (DDD)
- SOLID Principles
- CQRS
- Event Sourcing
- Microservices
- BFF (Backend for Frontend)

### Banco de Dados

- ORM: TypeORM, Prisma, Mongoose
- Migrations para versionamento
- Indexação otimizada
- Expurgo de dados

### Qualidade & Testes

- Testes unitários com Jest
- Coverage reports
- Mocks e Stubs
- Integration tests
- E2E tests com Supertest

### DevOps & Ferramentas

- Docker & Docker Compose
- CI/CD (GitHub Actions, CodeShip)
- Git Flow
- Conventional Commits
- SonarLint
- Sentry para monitoramento
- Swagger/OpenAPI
- Rate Limiting
- Caching strategies

### Performance

- Rate Limiting
- Caching (Redis)
- Connection pooling
- Índices de banco de dados
- Otimização de queries
- Lazy loading
- Paralelismo e concorrência

</details>

---

## Experiência Profissional Adicional

<details>
<summary><b>Ambientes & Metodologias</b></summary>

- Metodologias ágeis (Scrum, Kanban)
- Ambientes de alta pressão com grandes volumes de dados financeiros
- Arquitetura de microserviços em produção
- API Management (Linkapi)
- Desenvolvimento de componentes reutilizáveis
- Modelagem UML e BPMN
- Documentação técnica completa
- Code review e pair programming
- Gestão de ferramentas: Jira, Bitrix24, GitLab

</details>

---

## Sobre Mim

> **Observação:** 98% dos fluxos BPMN, diagramas UML, desenhos técnicos e repositórios são de autoria própria.

### Valores

- Professante da fé em Jesus Cristo (meu único Senhor e Salvador)
- Apaixonado por tecnologia e aprendizado contínuo
- Entusiasta de churrasco

---

## Mentores & Referências

<details>
<summary><b>Instrutores e Cursos</b></summary>

Os profissionais abaixo foram fundamentais na minha jornada de aprendizado:

- **Tiago Matos** - Vue.js 3, Composition API, Pinia
- **João Rangel** - NestJS
- **Diego Fernandes** - NestJS, Microserviços, RabbitMQ
- **Stephany Henrique** - GoLang
- **Otávio Augusto Gallego** - GoLang
- **Ellen Körbes** - GoLang
- **Fernando Daciuk** - JavaScript e Git Avançado
- **Fernando Amaral** - Kafka
- **Wesley Willians** - Kafka, GoLang
- **Loiane Groner** - Angular
- **Leonardo Moura** - Vue.js, Docker, TypeScript, GraphQL
- **Matheus Battisti** - Docker, Kubernetes, Vue.js
- **Nélio Alves** - Spring Boot
- **AlgaWorks** - Spring Boot, Angular
- **Otávio Lemos** - Arquitetura, TDD com TypeScript
- **Ruan Delgado** - Algoritmos
- **Fábio Akita** - Estudo Pragmático
- **Rocketseat** - Stack Backend Node.js
- **Henrique Cunha** - Algoritmos
- **César Vasconcelos** - Java
- **Otávio Miranda** - Padrões de Projeto com TypeScript
- **Erick Wendel** - Node.js Avançado
- **Linux Tips** - Linux, Docker, Kubernetes
- **Dev Soltinho** - JavaScript, Git
- **Claudson Oliveira** - GoLang, Trabalho no Exterior
- **Rodrigo Branas** - JavaScript
- **Jonathan Baraldi** - DevOps com Rancher, AWS, GCP
- **Codar.me** - Node.js
- **Plínio Naves** - Vue.js & Vuetify
- **Victor Hugo Negrisoli** - Microserviços

</details>

---

<div align="center">

**Documento elaborado por [Edivam Enéas de Almeida Júnior](https://github.com/eneas-almeida)**

*Atualizado em Dezembro de 2025*

</div>
