# Enéas Almeida

🇧🇷 [Português](README.md) &nbsp;|&nbsp; 🇺🇸 **English**

**Note:** About 98% of the technical artifacts (BPMN, UML, projects, diagrams and repositories) are authored by me.

## 👨‍💻 About

### Professional Experience
-   ❤️ **9+ years** of experience in modern software development
-   💼 Lead Developer at **Sicoob** - Responsible for microservices processing **R$ 6 million/month**
-   🏗️ Expert in **Microservices Architecture** and **Distributed Systems**
-   📊 Experience with large volumes of financial and sensitive data in high-pressure environments

### Academic Background
-   🎓 **Bachelor's in Computer Engineering** - Federal Institute of Paraíba (IFPB)
-   🎓 **Graduate Specialization in Distributed Software Architecture** - [PUC Minas](https://vemprapuc.pucminas.br/arquitetura-de-software-distribuido-2013?variant_id=37515)
-   🎓 **MBA in Software Engineering with AI** - [Full Cycle](https://ia.fullcycle.com.br/mba-ia/?utm_source=site-fullcycle&utm_medium=slider-site&utm_content=org_slider_mba_engenharia_ia) *(In progress)*
-   📜 **Go Expert** - [Full Cycle](https://goexpert.fullcycle.com.br/curso/) *(Completed)*
-   📜 **Java Microservices Specialist** - [AlgaWorks](https://lp.algaworks.com/curso-especialista-microsservicos-java-spring-cadastro/) *(In progress)*

### Personal

-   ✝️ Professing faith in **Jesus Christ** (my only Lord and Savior);
-   🍖 BBQ fan — having one? Call me! 🔥

## Latest Project (in progress) 🔥🔥🔥

👉 <a href="https://github.com/eneas-almeida/bridge">Bridge</a>

<a href="https://github.com/eneas-almeida/bridge"><img src="./images/java-grpc-2.png" width="100%" /></a>

The **Bridge** project is a microservices architecture developed by Enéas Almeida, composed of two main services that communicate via **gRPC**:

- **API Service**: REST Gateway that exposes HTTP endpoints and communicates with the People service via gRPC
- **People Service**: Backend service that provides user data via gRPC, consuming an external User data API

```
┌──────────────┐     HTTP/REST      ┌──────────────┐      gRPC       ┌──────────────┐     HTTP
│    Client    │ ─────────────────> │  API Service │ ──────────────> │People Service│ ──────────> User data
│  (Browser)   │                    │  (Port 8081) │                 │ (Port 9090)  │             (External API)
└──────────────┘                    └──────────────┘                 └──────────────┘
```

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Microservice](https://img.shields.io/badge/Microservice-00599C?style=flat&logo=microgenetics&logoColor=white)
![SpringBoot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=flat&logo=google&logoColor=white)
![WebFlux](https://img.shields.io/badge/WebFlux-6DB33F?style=flat&logo=spring&logoColor=white)

# Main Technologies and Tech Stack

### Backend
-   ☕ **Java (8, 11, 17, 21)** - JBoss, Spring Boot, WebFlux, high-performance microservices
-   ⚡ **Node.js / NestJS / TypeScript** - REST API development, microservices and scalable applications
-   🔷 **Go (Golang)** - High-concurrency APIs, gRPC, distributed systems
-   🐍 **Python** - Scripts, automation and data processing

### Frontend
-   ⚛️ **React** - Modern and responsive UI development
-   💚 **Vue.js 2 & 3** (Specialist) - Vuetify, PrimeVue, Quasar, Composition API, Pinia
-   🅰️ **Angular** - Enterprise applications

### Architecture & Patterns
-   🏛️ Clean Architecture, CQRS, MVC, DDD, Event-Driven Architecture
-   🔄 Microservices, BFF (Backend for Frontend), GraphQL, gRPC
-   📐 **BPMN** and **UML** documentation specialist

### DevOps & Cloud
-   ☁️ **AWS**: S3, Redis, DocumentDB, Cognito, SQS, API Gateway, Lambda
-   🐳 **Docker**, **Kubernetes**, **Istio**, **Helm**, **Terraform**
-   🔄 CI/CD, GitHub Actions, Automated Pipelines

### Databases & Messaging
-   💾 Oracle, PostgreSQL, MySQL, MongoDB, Redis
-   📬 RabbitMQ, Apache Kafka, AWS SQS
-   🔧 TypeORM, Prisma, Mongoose

# Most Relevant Professional Experience: Sicoob

**Business Domain**

Transfer of points from the Sicoob card to partner programs.

```
                                                      ┌────────────────┐
                                              ┌──────>│    TudoAzul    │
                                              │       └────────────────┘
                                              │
                                              │       ┌────────────────┐
                            ┌─────────────────┴──┐    │     Livelo     │
                            │   Sicoob Card      │───>└────────────────┘
                            │      (Points)      │
                            └─────────────────┬──┘    ┌────────────────┐
                                              │       │     Smiles     │
                                              ├──────>└────────────────┘
                                              │
                                              │       ┌────────────────┐
                                              └──────>│   Latam Pass   │
                                                      └────────────────┘
```

**Role**

- Lead Developer, from conception to production delivery

**Responsibilities**

- Migration and development of **4 main microservices** and **7 auxiliary services**
- Involvement from understanding business rules all the way to production delivery

**Results**

- Microservices in production generating approximately **R$ 6 million/month**

**Integrations**

- Oracle
- VTEX
- Siebel
- Salesforce
- Linkapi

# Last Developed Project: Monitoring Sensors

👉 <a href="https://github.com/eneas-almeida/ms-sensors-central">Monitoring Sensors</a>

Architecture diagram.

<a href="https://github.com/eneas-almeida/ms-sensors-central"><img src="./images/microservicos.png" /></a>

The system is composed of three independent microservices that work together to manage sensor devices and process temperature data in an asynchronous and scalable way:

1. **Device Manager:** Manages sensor registration and configuration
2. **Temperature Monitoring:** Collects and monitors temperature readings
3. **Temperature Processing:** Processes and persists temperature data with performance optimizations

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Microservice](https://img.shields.io/badge/Microservice-00599C?style=flat&logo=microgenetics&logoColor=white)
![SpringBoot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat&logo=gradle&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![Retry Pattern](https://img.shields.io/badge/Retry_Pattern-4B8BBE?style=flat&logo=retry&logoColor=white)
![Dead Queue](https://img.shields.io/badge/Dead_Queue-FF6B6B?style=flat&logo=queue&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)

## Favorites List Project (Magazine Luiza)

👉 <a href="https://github.com/eneas-almeida/luizalabs">Luizalabs</a>

Frontend screen developed for the project.

<p align="center">
    <a href="https://github.com/eneas-almeida/luizalabs"><img src="./images/labs-1.png" alt="RESPONSIVE SCREEN" /></a>
</p>

Application for adding products to a favorites list **(Magazine Luiza)**. Backend using Clean Architecture with Node.js.

### Main Features

✅ User account management (creation and authentication)<br />
✅ JWT authentication system<br />
✅ Product management in favorites lists<br />
✅ Integration with external product API<br />
✅ Clean and decoupled architecture<br />
✅ Comprehensive unit tests<br />
✅ Robust error handling<br />

### Request Flow

An HTTP request follows this path through the layers:

```mermaid
sequenceDiagram
    participant Client
    participant Route
    participant Middleware
    participant Controller
    participant Usecase
    participant Repository
    participant Database

    Client->>Route: HTTP Request
    Route->>Middleware: Apply Middlewares

    alt Authentication Required
        Middleware->>Middleware: Validate JWT Token
        Middleware-->>Client: 401 Unauthorized (if invalid)
    end

    Middleware->>Controller: handle(req, res)
    Controller->>Controller: Create DTO from req.body
    Controller->>Usecase: execute(dto)

    Usecase->>Usecase: Validate Business Rules

    alt Business Rule Violated
        Usecase-->>Controller: throw AppError
        Controller-->>Client: Error Response
    end

    Usecase->>Repository: Database Operation
    Repository->>Database: Query/Command
    Database-->>Repository: Result
    Repository-->>Usecase: Domain Object

    Usecase-->>Controller: Success Result
    Controller->>Controller: Format Response
    Controller-->>Client: HTTP Response (200/201)
```

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vue.js&logoColor=white)
![Frontend](https://img.shields.io/badge/Frontend-61DAFB?style=flat&logo=react&logoColor=black)
![Backend](https://img.shields.io/badge/Backend-339933?style=flat&logo=node.js&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Microservice](https://img.shields.io/badge/Microservice-00599C?style=flat&logo=microgenetics&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat&logo=jest&logoColor=white)
![SOLID](https://img.shields.io/badge/SOLID-512BD4?style=flat&logo=code&logoColor=white)
![Clean Code](https://img.shields.io/badge/Clean_Code-00599C?style=flat&logo=code&logoColor=white)
![Design Patterns](https://img.shields.io/badge/Design_Patterns-FFA500?style=flat&logo=pattern&logoColor=white)
![Clean Architecture](https://img.shields.io/badge/Clean_Architecture-00599C?style=flat&logo=architecture&logoColor=white)
![Retry Pattern](https://img.shields.io/badge/Retry_Pattern-4B8BBE?style=flat&logo=retry&logoColor=white)
![Tests](https://img.shields.io/badge/Tests-C21325?style=flat&logo=testing-library&logoColor=white)
![Jdocs](https://img.shields.io/badge/Jdocs-4285F4?style=flat&logo=documentation&logoColor=white)


## Bekid Project

**Business Domain**

Monitoring children in the school environment through AI to combat bullying.

👉 <a href="https://github.com/eneas-almeida/bekid">Bekid</a> is an emotion mapping system using Artificial Intelligence to help combat school bullying. The application performs real-time behavioral analysis, offering dashboards for educational managers with alerts and reports. **(finished, live in production)**<br />

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vue.js&logoColor=white)
![AI/ML](https://img.shields.io/badge/AI/ML-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Computer Vision](https://img.shields.io/badge/Computer_Vision-5C3EE8?style=flat&logo=opencv&logoColor=white)
![Emotion Detection](https://img.shields.io/badge/Emotion_Detection-E91E63?style=flat&logo=brain&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat&logo=socket.io&logoColor=white)
![Real-time](https://img.shields.io/badge/Real--time-FF6B6B?style=flat&logo=lightning&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Education Tech](https://img.shields.io/badge/Education_Tech-4285F4?style=flat&logo=google-scholar&logoColor=white)

<p align="center">
    <a href="https://github.com/eneas-almeida/bekid"><img src="./images/diagram-v5.png" alt="Diagram" /></a>
</p>

<a href="https://github.com/eneas-almeida/bekid"><img src="./images/bekid.png" alt="Screen designs" /></a>

## Bestore Project (E-commerce)

👉 <a href="https://github.com/eneas-almeida/bestore">Bestore</a> - Complete REST API for e-commerce with product management, categories, shopping cart and order processing. Built in Java with Spring Boot and MySQL, following REST standards and development best practices. **(finished)**<br />

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-009688?style=flat&logo=api&logoColor=white)
![E-commerce](https://img.shields.io/badge/E--commerce-FF6F00?style=flat&logo=shopify&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-6DB33F?style=flat&logo=hibernate&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat&logo=hibernate&logoColor=white)
![MVC](https://img.shields.io/badge/MVC-512BD4?style=flat&logo=dotnet&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

<img src="https://github.com/eneas-almeida/bestore/raw/master/media/diagrams/diagrama-v5.png" />


## Events-Nest (NestJS + CQRS + Clean Architecture)

👉 <a href="https://github.com/eneas-almeida/events-nest">Events-Nest</a>: Event-based microservice implementing advanced architectural patterns. The project demonstrates the practical application of CQRS (Command Query Responsibility Segregation), Event Sourcing and Clean Architecture with NestJS, separating commands from queries and maintaining a complete event history.<br />

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![CQRS](https://img.shields.io/badge/CQRS-512BD4?style=flat&logo=csharp&logoColor=white)
![Event Sourcing](https://img.shields.io/badge/Event_Sourcing-FF6B6B?style=flat&logo=eventstore&logoColor=white)
![Clean Architecture](https://img.shields.io/badge/Clean_Architecture-00599C?style=flat&logo=architecture&logoColor=white)
![DDD](https://img.shields.io/badge/DDD-4B8BBE?style=flat&logo=domain&logoColor=white)
![Microservices](https://img.shields.io/badge/Microservices-00599C?style=flat&logo=microgenetics&logoColor=white)
![Design Patterns](https://img.shields.io/badge/Design_Patterns-FFA500?style=flat&logo=pattern&logoColor=white)

## Latest Algorithms Developed and Used in Production

|                  Technology                  | Link                                                                            | What does it solve?                                                    |
| :------------------------------------------: | ------------------------------------------------------------------------------- | ---------------------------------------------------------------------- |
|   <img src="./images/js.png" width="20" />   | 👉 <a href="https://github.com/eneas-almeida/cache-parallel">Cache Parallel</a> | External requests using parallelism strategy.                          |
| <img src="./images/golang.png" width="15" /> | 👉 <a href="https://github.com/eneas-almeida/go-fetch">Fetch</a>                | External requests using parallelism strategy with fallback.            |
| <img src="./images/golang.png" width="15" /> | 👉 <a href="https://github.com/eneas-almeida/go-upload">Upload</a>              | File upload to AWS S3 using fallback strategy.                         |
| <img src="./images/golang.png" width="15" /> | 👉 <a href="https://github.com/eneas-almeida/grpc">gRPC</a>                     | gRPC implementation.                                                   |
| <img src="./images/golang.png" width="15" /> | 👉 <a href="https://github.com/eneas-almeida/graphql">GraphQL</a>               | GraphQL implementation.                                                |

## Customer Clean Architecture (Architectural Guide)

The project demonstrates the complete implementation of Clean Architecture in microservices, with clear layer separation (Domain, Application, Infrastructure, Presentation) and the application of SOLID principles and DDD.

👉 <a href="https://github.com/eneas-almeida/customer-clean-architecture">Clean Architecture Guide</a> - Complete technical guide for clean architecture implementation, used for team onboarding and standardization.<br />

![Clean Architecture](https://img.shields.io/badge/Clean_Architecture-00599C?style=flat&logo=architecture&logoColor=white)
![DDD](https://img.shields.io/badge/DDD-4B8BBE?style=flat&logo=domain&logoColor=white)
![SOLID](https://img.shields.io/badge/SOLID-512BD4?style=flat&logo=code&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![Design Patterns](https://img.shields.io/badge/Design_Patterns-FFA500?style=flat&logo=pattern&logoColor=white)
![Best Practices](https://img.shields.io/badge/Best_Practices-4CAF50?style=flat&logo=checkmarx&logoColor=white)
![Layered Architecture](https://img.shields.io/badge/Layered_Architecture-00599C?style=flat&logo=layers&logoColor=white)

<p align="center">
    <a href="https://github.com/eneas-almeida/customer-clean-architecture"><img src="./images/camadas.png" /></a>
</p>

## gRPC (Implementation Guide)

<p align="center">
    <a href="https://github.com/eneas-almeida/grpc"><img src="./images/goandgrpc.png" width="300" /></a>
</p>

👉 <a href="https://github.com/eneas-almeida/grpc">gRPC Guide</a> - Complete gRPC implementation guide with Go, including unary communication, streaming (server, client and bidirectional), interceptors, authentication and best practices for high-performance communication between microservices.<br />

![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=flat&logo=google&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Protocol Buffers](https://img.shields.io/badge/Protocol_Buffers-4285F4?style=flat&logo=google&logoColor=white)
![Microservices](https://img.shields.io/badge/Microservices-00599C?style=flat&logo=microgenetics&logoColor=white)
![RPC](https://img.shields.io/badge/RPC-4285F4?style=flat&logo=protocol&logoColor=white)
![Streaming](https://img.shields.io/badge/Streaming-FF0000?style=flat&logo=youtube&logoColor=white)
![High Performance](https://img.shields.io/badge/High_Performance-00C853?style=flat&logo=speedtest&logoColor=white)
![API Design](https://img.shields.io/badge/API_Design-009688?style=flat&logo=swagger&logoColor=white)

## GraphQL (Implementation Guide)

<p align="center">
    <a href="https://github.com/eneas-almeida/graphql"><img src="./images/graphmaisgo.png" /></a>
</p>

👉 <a href="https://github.com/eneas-almeida/graphql">GraphQL Guide</a> - Complete GraphQL implementation guide with Go, including schemas, queries, mutations, resolvers, subscriptions and optimizations. Demonstrates how to create flexible and efficient APIs allowing clients to request exactly the data they need.<br />

![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat&logo=graphql&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![API Design](https://img.shields.io/badge/API_Design-009688?style=flat&logo=swagger&logoColor=white)
![Queries](https://img.shields.io/badge/Queries-E10098?style=flat&logo=graphql&logoColor=white)
![Mutations](https://img.shields.io/badge/Mutations-E10098?style=flat&logo=graphql&logoColor=white)
![Subscriptions](https://img.shields.io/badge/Subscriptions-E10098?style=flat&logo=graphql&logoColor=white)
![Schema](https://img.shields.io/badge/Schema-E10098?style=flat&logo=graphql&logoColor=white)
![Resolvers](https://img.shields.io/badge/Resolvers-E10098?style=flat&logo=graphql&logoColor=white)
![Real-time](https://img.shields.io/badge/Real--time-FF6B6B?style=flat&logo=lightning&logoColor=white)

## RabbitMQ (Messaging Guide)

<p align="center">
    <a href="https://github.com/eneas-almeida/rabbitmq"><img src="./images/rabbitmq.webp" width="300" /></a>
</p>

👉 <a href="https://github.com/eneas-almeida/rabbitmq">RabbitMQ Guide</a> - Complete messaging guide with RabbitMQ, including exchanges (direct, topic, fanout, headers), queues, dead letter queues, retry patterns, message acknowledgments and best practices for asynchronous communication between microservices.<br />

![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![Message Broker](https://img.shields.io/badge/Message_Broker-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![AMQP](https://img.shields.io/badge/AMQP-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![Async Communication](https://img.shields.io/badge/Async_Communication-4B8BBE?style=flat&logo=async&logoColor=white)
![Microservices](https://img.shields.io/badge/Microservices-00599C?style=flat&logo=microgenetics&logoColor=white)
![Dead Letter Queue](https://img.shields.io/badge/Dead_Letter_Queue-FF6B6B?style=flat&logo=queue&logoColor=white)
![Retry Pattern](https://img.shields.io/badge/Retry_Pattern-4B8BBE?style=flat&logo=retry&logoColor=white)
![Event-Driven](https://img.shields.io/badge/Event--Driven-FF6F00?style=flat&logo=apache-kafka&logoColor=white)

## Kafka (Event Streaming Guide)

<p align="center">
    <a href="https://github.com/eneas-almeida/kafka"><img src="https://github.com/eneas-almeida/kafka/raw/master/media/kafka/kafka-1-2.gif" /></a>
</p>

👉 <a href="https://github.com/eneas-almeida/kafka">Kafka Guide</a> - Complete Apache Kafka guide for event streaming, including producers, consumers, consumer groups, partitions, replication, offset management and large-scale message processing strategies. Practical implementations in multiple languages.<br />

![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat&logo=apache-kafka&logoColor=white)
![Event Streaming](https://img.shields.io/badge/Event_Streaming-231F20?style=flat&logo=apache-kafka&logoColor=white)
![Message Queue](https://img.shields.io/badge/Message_Queue-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![Distributed Systems](https://img.shields.io/badge/Distributed_Systems-00599C?style=flat&logo=system&logoColor=white)
![High Throughput](https://img.shields.io/badge/High_Throughput-00C853?style=flat&logo=speedtest&logoColor=white)
![Real-time Processing](https://img.shields.io/badge/Real--time_Processing-FF6B6B?style=flat&logo=processing&logoColor=white)
![Pub/Sub](https://img.shields.io/badge/Pub/Sub-4285F4?style=flat&logo=google-cloud&logoColor=white)
![Scalability](https://img.shields.io/badge/Scalability-00C853?style=flat&logo=scale&logoColor=white)
<br />
👉 <a href="https://github.com/eneas-almeida/customer-clean-architecture/blob/main/src/infra/services/queue/kafka-queue.service.ts">TypeScript service implementation with Kafka</a><br />
👉 <a href="https://github.com/eneas-almeida/kafka/tree/master/kafka-nestjs">Kafka + NestJs</a><br />
👉 <a href="https://github.com/eneas-almeida/kafka/tree/master/kafka-nodejs">Kafka + NodeJs</a><br />
👉 <a href="https://github.com/eneas-almeida/kafka/tree/master/kafka-python">Kafka + Python</a>

## BFF - Backend for Frontend (Architectural Pattern)

<p align="center">
  <a href="https://github.com/eneas-almeida/bff"><img src="./images/bff.gif" /></a>
</p>

👉 <a href="https://github.com/eneas-almeida/bff">BFF Guide</a> - Complete guide to the Backend for Frontend pattern, demonstrating how to create backend layers specific to each type of client (web, mobile, desktop). The BFF acts as an intermediary between the frontend and microservices, aggregating data, optimizing payloads and adapting APIs for the specific needs of each platform.<br />

![BFF](https://img.shields.io/badge/BFF-00599C?style=flat&logo=backend&logoColor=white)
![Backend for Frontend](https://img.shields.io/badge/Backend_for_Frontend-00599C?style=flat&logo=backend&logoColor=white)
![API Gateway](https://img.shields.io/badge/API_Gateway-FF6C37?style=flat&logo=amazon-api-gateway&logoColor=white)
![Microservices](https://img.shields.io/badge/Microservices-00599C?style=flat&logo=microgenetics&logoColor=white)
![API Aggregation](https://img.shields.io/badge/API_Aggregation-009688?style=flat&logo=api&logoColor=white)
![Mobile Backend](https://img.shields.io/badge/Mobile_Backend-3DDC84?style=flat&logo=android&logoColor=white)
![Web Backend](https://img.shields.io/badge/Web_Backend-4285F4?style=flat&logo=google-chrome&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat&logo=graphql&logoColor=white)

<hr>

## Go Account API (Clean Architecture + MongoDB)

Account management microservice developed in Go rigorously following Clean Architecture principles. Uses Fiber Framework for high-performance HTTP, MongoDB as the database, and implements layer separation (entities, usecases, repositories, handlers) ensuring testability and maintainability.

<p align="center">
    <a href="https://github.com/eneas-almeida/go-account-api-mongodb"><img src="./images/fiber.png" /></a>
</p>

👉 <a href="https://github.com/eneas-almeida/go-account-api-mongodb">Project link</a><br />

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Fiber](https://img.shields.io/badge/Fiber-00ACD7?style=flat&logo=fiber&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Clean Architecture](https://img.shields.io/badge/Clean_Architecture-00599C?style=flat&logo=architecture&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-009688?style=flat&logo=api&logoColor=white)
![Dependency Injection](https://img.shields.io/badge/Dependency_Injection-4B8BBE?style=flat&logo=di&logoColor=white)
![Repository Pattern](https://img.shields.io/badge/Repository_Pattern-FFA500?style=flat&logo=pattern&logoColor=white)
![SOLID](https://img.shields.io/badge/SOLID-512BD4?style=flat&logo=code&logoColor=white)

<hr>

## MyPoint (Time Tracking System + High Concurrency)

**What does it solve?**

Concurrency problems and database overload. Multiple parallel and heavy queries that lead to exhaustion of processing resources.

<p align="center">
    <a href="https://github.com/eneas-almeida/mypoint"><img src="./images/architeture-v1.png" alt="System architecture" /></a>
</p>

👉 <a href="https://github.com/eneas-almeida/mypoint">MyPoint</a> is an employee time tracking system built with microservices architecture. It uses queues (RabbitMQ) for asynchronous processing, distributed cache to reduce database load, and WebSocket for real-time updates. The architecture supports high volumes of simultaneous requests without performance degradation. **(in progress)**<br />

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vue.js&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![Microservices](https://img.shields.io/badge/Microservices-00599C?style=flat&logo=microgenetics&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat&logo=socket.io&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![High Concurrency](https://img.shields.io/badge/High_Concurrency-00C853?style=flat&logo=performance&logoColor=white)
![Real-time](https://img.shields.io/badge/Real--time-FF6B6B?style=flat&logo=lightning&logoColor=white)
![Event-Driven](https://img.shields.io/badge/Event--Driven-FF6F00?style=flat&logo=apache-kafka&logoColor=white)

<hr>

### GoLang

<p align="center">
    <a href="https://github.com/eneas-almeida/golang"><img src="./images/golang.png" width="170px" /></a>
</p>

👉 <a href="https://github.com/eneas-almeida/golang">Installation, configuration and plugins</a><br />
👉 <a href="https://github.com/eneas-almeida/go-routines/">Go routines (the efficient workers case)</a><br />
👉 <a href="https://github.com/eneas-almeida/go/tree/main/projects/go-http-retry-backoff">Go http retry with exponential backoff</a><br />
👉 <a href="https://github.com/eneas-almeida/go/tree/main/projects/go-algorithms">Go algorithms</a><br />
👉 <a href="https://github.com/eneas-almeida/go/tree/main/projects/go-injections">Go injections</a><br />
👉 <a href="https://github.com/eneas-almeida/go/tree/main/projects/go-injections-with-google-wire">Go injections with Google Wire</a><br />
👉 <a href="https://github.com/eneas-almeida/go/tree/main/projects/go-viacep">Go API ViaCEP</a><br />
👉 <a href="https://github.com/eneas-almeida/go/tree/main/projects/go-encoder">Go encoder</a> <br />
👉 <a href="https://github.com/eneas-almeida/go/tree/main/projects/go-database">Go database</a> <br />
👉 <a href="https://github.com/eneas-almeida/go/tree/main/projects/go-clean-architecture-basic">Go clean architecture</a> <br />
👉 <a href="https://github.com/eneas-almeida/go/tree/main/projects/go-deploy">Go deploy</a> <br />
👉 <a href="https://github.com/eneas-almeida/go/tree/main/projects/go-validations">Go validations</a> <br />
👉 <a href="https://github.com/eneas-almeida/go/tree/main/projects/go-configs-dot-env">Go env</a> <br />
👉 <a href="https://github.com/eneas-almeida/concorrencia-go">Go concurrency</a> (Third-party repository)

### Nodejs

👉 <a href="https://github.com/eneas-almeida/nodejs-http-retry/tree/main">HTTP call resilience with Axios Retry</a><br />
👉 <a href="https://github.com/eneas-almeida/nodejs-base">NodeJs Base API</a>

### K8s

👉 <a href="https://github.com/eneas-almeida/k8s">K8s</a><br />
👉 <a href="https://github.com/eneas-almeida/istio">Istio</a>

### VueJs 3

👉 <a href="https://github.com/eneas-almeida/vue3-with-casl">VueJs v3 + Pinia + ACLs Casl</a> **(finished)**<br />
👉 <a href="https://github.com/eneas-almeida/vue3-composition-api">VueJs v3 + Composition api + props + emit + watch</a> **(finished)**

<hr>

### Socket.io (Real-time Communication)

👉 <a href="https://github.com/eneas-almeida/socketio_vuejs_nodejs">Socket.io with Vue/Node/Nest</a> - Bidirectional real-time communication system using WebSockets. Implements JWT authentication, Observer pattern for events, rooms/namespaces and automatic reconnection. Frontend in Vue.js and backend in Node.js/NestJS. ❤️ **(finished)**<br />

![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat&logo=socket.io&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat&logo=websocket&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vue.js&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![Real-time](https://img.shields.io/badge/Real--time-FF6B6B?style=flat&logo=lightning&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat&logo=json-web-tokens&logoColor=white)
![Observer Pattern](https://img.shields.io/badge/Observer_Pattern-FFA500?style=flat&logo=pattern&logoColor=white)
![Bidirectional Communication](https://img.shields.io/badge/Bidirectional_Communication-4B8BBE?style=flat&logo=communication&logoColor=white)

### NestJs Architecture (Rich Domains + DDD)

👉 <a href="https://github.com/eneas-almeida/nestjs/tree/master/nestjs-value-object">NestJs + Rich Domains</a> - REST API implementing **Domain-Driven Design** with rich domain modeling. Uses **Value Objects** to encapsulate business rules, **Either Pattern** for functional error handling, **DTOs** for input/output validation and **Mappers** for layer transformation, ensuring separation of concerns and a framework-free domain.<br />

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![DDD](https://img.shields.io/badge/DDD-4B8BBE?style=flat&logo=domain&logoColor=white)
![Value Objects](https://img.shields.io/badge/Value_Objects-512BD4?style=flat&logo=code&logoColor=white)
![Either Pattern](https://img.shields.io/badge/Either_Pattern-FFA500?style=flat&logo=pattern&logoColor=white)
![DTOs](https://img.shields.io/badge/DTOs-3178C6?style=flat&logo=typescript&logoColor=white)
![Mappers](https://img.shields.io/badge/Mappers-4B8BBE?style=flat&logo=mapping&logoColor=white)
![Domain Modeling](https://img.shields.io/badge/Domain_Modeling-4B8BBE?style=flat&logo=model&logoColor=white)
![Clean Architecture](https://img.shields.io/badge/Clean_Architecture-00599C?style=flat&logo=architecture&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)

<hr>

## More Developed APIs

### School Dropout (Educational Analysis System)

👉 <a href="https://github.com/eneas-almeida/api-evasao-escolar-nestjs">School Dropout</a> - System for analyzing and preventing school dropout in public higher education institutions. Collects and processes academic data to identify patterns and at-risk students, generating reports and dashboards for educational managers. **(finished, live in production)**<br />

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![TypeORM](https://img.shields.io/badge/TypeORM-FE0902?style=flat&logo=typeorm&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![Education](https://img.shields.io/badge/Education-4285F4?style=flat&logo=google-scholar&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-FF6F00?style=flat&logo=databricks&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-009688?style=flat&logo=api&logoColor=white)
![Production](https://img.shields.io/badge/Production-00C853?style=flat&logo=checkmarx&logoColor=white)

---

### Tindin (Class Management)

👉 <a href="https://github.com/eneas-almeida/api-tindin">Tindin</a> - API for controlling and managing classes taught by teachers. Complete system with authentication, class CRUD, reports and statistics. Developed with TDD and high test coverage. **(finished)**<br />

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat&logo=jest&logoColor=white)
![TDD](https://img.shields.io/badge/TDD-C21325?style=flat&logo=testing-library&logoColor=white)
![High Coverage](https://img.shields.io/badge/High_Coverage-00C853?style=flat&logo=codecov&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-009688?style=flat&logo=api&logoColor=white)
![Authentication](https://img.shields.io/badge/Authentication-000000?style=flat&logo=auth0&logoColor=white)
![Education](https://img.shields.io/badge/Education-4285F4?style=flat&logo=google-scholar&logoColor=white)

---

### Places to Know (Tourist Spots API)

👉 <a href="https://github.com/eneas-almeida/api-places-to-know">Places to Know</a> - API for cataloging tourist spots around the world with integration to external geolocation APIs. Implements advanced search system with multiple filters, pagination and result caching. **(finished)**<br />

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![External API Integration](https://img.shields.io/badge/External_API_Integration-009688?style=flat&logo=api&logoColor=white)
![Search](https://img.shields.io/badge/Search-4285F4?style=flat&logo=google&logoColor=white)
![Filters](https://img.shields.io/badge/Filters-FF6B6B?style=flat&logo=filter&logoColor=white)
![Pagination](https://img.shields.io/badge/Pagination-4B8BBE?style=flat&logo=page&logoColor=white)
![Geolocation](https://img.shields.io/badge/Geolocation-4285F4?style=flat&logo=google-maps&logoColor=white)
![Cache](https://img.shields.io/badge/Cache-DC382D?style=flat&logo=redis&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-009688?style=flat&logo=api&logoColor=white)

## Previous Work

### Oráculo (Financial System)

👉 <a href="https://github.com/eneas-almeida/oraculo">Oráculo</a> - Complete financial management system for a client company. Interface developed with HTML5, vanilla JavaScript and jQuery, implementing income, expense, cash flow and management report controls. **(finished)**<br />

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat&logo=jquery&logoColor=white)
![Financial System](https://img.shields.io/badge/Financial_System-00C853?style=flat&logo=money&logoColor=white)
![Client Project](https://img.shields.io/badge/Client_Project-4285F4?style=flat&logo=project&logoColor=white)

<p align="center">
  <a href="https://github.com/eneas-almeida/oraculo"><img src="./images/oraculo.png" /></a>
</p>

---

### Gerente RH (Human Resources System)

👉 <a href="https://github.com/eneas-almeida/gerente-rh">Gerente RH</a> - Desktop employee management system with registration control, payroll, vacations and benefits. Developed in MVC architecture with C# and Microsoft SQL Server. **(finished)**<br />

![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat&logo=microsoft-sql-server&logoColor=white)
![MVC](https://img.shields.io/badge/MVC-512BD4?style=flat&logo=dotnet&logoColor=white)
![Desktop Application](https://img.shields.io/badge/Desktop_Application-0078D6?style=flat&logo=windows&logoColor=white)
![HR System](https://img.shields.io/badge/HR_System-4285F4?style=flat&logo=people&logoColor=white)

<p align="center">
  <a href="https://github.com/eneas-almeida/gerente-rh"><img src="./images/gerente.png" /></a>
</p>

## Javascript (Last 5 algorithms developed)

👉 <a href="https://github.com/eneas-almeida/javascript/blob/master/codes/readfileTxtAndConvertValuesToXlsx.js">Read Txt and convert to Xlsx</a> - Reads a .txt file, retrieves values, generates the .xlsx file, inserts the values read from the txt and formats them as currency R$. **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/javascript/blob/master/codes/getLevel.js">Get Level</a> - Eliminates the use of multiple IF and ELSE blocks for value range intervals. **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/javascript/blob/master/codes/parseDTO.js">Parse DTO</a> - Transforms object properties from Camel Case to Snake Case. **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/javascript/blob/master/codes/fIlterPropertiesInArrayObjects.js">Filter Properties</a> - Filters object properties by passing an array indicating which properties to remove. **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/javascript/blob/master/codes/mapEnumObjects.js">MAP Enum</a> - Technique I use to eliminate large quantities of IFs in the system. **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/javascript/tree/master/codes">All scripts</a> **(in progress)**<br />

## Node.js Testing Studies

👉 <a href="https://github.com/eneas-almeida/javascript/tree/master/codes/tests/mocks">Mock tests</a> - Studies on unit tests using mocks and Node.js native libraries. **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/javascript/tree/master/codes/tests/stubs">Stub with mocks</a> - Tests using the stub technique to simulate an API request. **(finished)**<br />

## Case Studies

### Auth NestJS (Complete Authentication)

👉 <a href="https://github.com/eneas-almeida/auth-nest">API Rest SigIn/SigUp</a> - Complete authentication and authorization system implementing JWT, refresh tokens, guards, custom interceptors, structured logger and unit tests. **(finished)**<br />

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![TypeORM](https://img.shields.io/badge/TypeORM-FE0902?style=flat&logo=typeorm&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat&logo=json-web-tokens&logoColor=white)
![Authentication](https://img.shields.io/badge/Authentication-000000?style=flat&logo=auth0&logoColor=white)
![Authorization](https://img.shields.io/badge/Authorization-000000?style=flat&logo=auth0&logoColor=white)
![Interceptors](https://img.shields.io/badge/Interceptors-E0234E?style=flat&logo=nestjs&logoColor=white)
![Guards](https://img.shields.io/badge/Guards-E0234E?style=flat&logo=nestjs&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat&logo=jest&logoColor=white)

---

### NestJS + Prisma (Complete API)

👉 <a href="https://github.com/eneas-almeida/nestjs-with-prisma">API Rest NestJs with Prisma</a> - Modern REST API with Prisma ORM, Swagger/OpenAPI documentation, data validation with class-validator, transformers, custom pagination, global exception handling and logger. Includes Docker Compose for development environment. **(finished)**<br />

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat&logo=swagger&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Validators](https://img.shields.io/badge/Validators-4CAF50?style=flat&logo=checkmarx&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-4B8BBE?style=flat&logo=transform&logoColor=white)
![Pagination](https://img.shields.io/badge/Pagination-4B8BBE?style=flat&logo=page&logoColor=white)
![Exception Handling](https://img.shields.io/badge/Exception_Handling-FF6B6B?style=flat&logo=error&logoColor=white)

---

### VacinaPB (TDD + Clean Architecture)

👉 <a href="https://github.com/eneas-almeida/vacina_pb">VacinaPB</a> - Case study rigorously applying **Test-Driven Development (TDD)**. Implements Clean Architecture, design patterns (Repository, Factory, Strategy), rich domain modeling with Value Objects and Entity, based on Martin Fowler's teachings on refactoring and architecture. **(finished)**<br />

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![TDD](https://img.shields.io/badge/TDD-C21325?style=flat&logo=testing-library&logoColor=white)
![Clean Architecture](https://img.shields.io/badge/Clean_Architecture-00599C?style=flat&logo=architecture&logoColor=white)
![DDD](https://img.shields.io/badge/DDD-4B8BBE?style=flat&logo=domain&logoColor=white)
![Value Objects](https://img.shields.io/badge/Value_Objects-512BD4?style=flat&logo=code&logoColor=white)
![Design Patterns](https://img.shields.io/badge/Design_Patterns-FFA500?style=flat&logo=pattern&logoColor=white)
![Martin Fowler](https://img.shields.io/badge/Martin_Fowler-FF6B6B?style=flat&logo=book&logoColor=white)

---

### Entity Modeling (Either Pattern)

👉 <a href="https://github.com/eneas-almeida/modelagem_entidade">Entity modeling (Tiny)</a> - Implementation of the **Either Pattern** in Java for functional error handling. The technique uses an Either.java class to encapsulate success or failure, allowing elegant exception management without try-catch, inspired by functional programming. **(finished)**<br />

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Either Pattern](https://img.shields.io/badge/Either_Pattern-FFA500?style=flat&logo=pattern&logoColor=white)
![Functional Programming](https://img.shields.io/badge/Functional_Programming-512BD4?style=flat&logo=functional&logoColor=white)
![Error Handling](https://img.shields.io/badge/Error_Handling-FF6B6B?style=flat&logo=error&logoColor=white)
![Design Patterns](https://img.shields.io/badge/Design_Patterns-FFA500?style=flat&logo=pattern&logoColor=white)
![Clean Code](https://img.shields.io/badge/Clean_Code-00599C?style=flat&logo=code&logoColor=white)

---

### Performance Testing (JMeter)

👉 <a href="https://github.com/eneas-almeida/teste_exaustao">Exhaustion Test (JMeter)</a> - Load and stress testing using Apache JMeter for performance analysis, bottleneck identification and application capacity limits. **(finished)**<br />

![JMeter](https://img.shields.io/badge/JMeter-D22128?style=flat&logo=apache-jmeter&logoColor=white)
![Performance Testing](https://img.shields.io/badge/Performance_Testing-00C853?style=flat&logo=speedtest&logoColor=white)
![Load Testing](https://img.shields.io/badge/Load_Testing-FF6B6B?style=flat&logo=testing&logoColor=white)
![Stress Testing](https://img.shields.io/badge/Stress_Testing-FF6B6B?style=flat&logo=testing&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)

---

### CI/CD (Codeship)

👉 <a href="https://github.com/eneas-almeida/deploy_codeship">Deploy to QA and Production</a> - Continuous integration and automated deployment pipeline using Codeship, with separate QA and Production environments, automated tests and conditional deployment. **(finished)**<br />

![CI/CD](https://img.shields.io/badge/CI/CD-2088FF?style=flat&logo=github-actions&logoColor=white)
![Codeship](https://img.shields.io/badge/Codeship-3C4858?style=flat&logo=codeship&logoColor=white)
![Automated Deployment](https://img.shields.io/badge/Automated_Deployment-00C853?style=flat&logo=deploy&logoColor=white)
![QA](https://img.shields.io/badge/QA-4CAF50?style=flat&logo=quality&logoColor=white)
![Production](https://img.shields.io/badge/Production-00C853?style=flat&logo=checkmarx&logoColor=white)
![DevOps](https://img.shields.io/badge/DevOps-0A66C2?style=flat&logo=devops&logoColor=white)

---

### Automated Releases

👉 <a href="https://github.com/eneas-almeida/create_releases">Create releases</a> - Automation of GitHub release creation with semantic versioning, automatic changelog and tagging. **(finished)**<br />

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![Automation](https://img.shields.io/badge/Automation-4B8BBE?style=flat&logo=automation&logoColor=white)
![Semantic Versioning](https://img.shields.io/badge/Semantic_Versioning-3F4F75?style=flat&logo=semver&logoColor=white)
![Release Management](https://img.shields.io/badge/Release_Management-4CAF50?style=flat&logo=release&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI/CD-2088FF?style=flat&logo=github-actions&logoColor=white)

---

### Other Studies

👉 <a href="https://github.com/eneas-almeida/nodejs-prisma">API Rest NodeJs with Prisma</a> - Package by Feature architecture with Prisma and Jest tests. **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/series-tv-backend">TV Series</a> - Fullstack with Spring Boot + Angular 12. **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/grisoli">Grisoli</a> - Microservices with NodeJs, Spring Boot, RabbitMQ and GitHub Actions. **(aborted)**<br />

👉 <a href="https://github.com/eneas-almeida/mongo_spring">API Rest Spring Boot with MongoDB</a> - Spring Boot + MongoDB. **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/agenda_contatos">Contact Book</a> - Java Servlets. **(finished)**<br />

## VueJs

👉 <a href="https://github.com/eneas-almeida/vuejs_tests">VueJs Tests</a> - Study on testing with jest and vuetify. **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/vuejs_upload_xsl">VueJs Upload XSL</a> - Study on uploading .xsl files with vuetify. 🔒 (private) **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/vuejs_checkbox">VueJs Checkbox</a> - Checkbox select with vuetify. **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/vuejs_select_all">VueJs Select All</a> - Select all with vuetify. **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/vuejs_vuetify">VueJs Vuetify</a> - Study on vuetify. 🔒 (private) **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/vuejs_geral">VueJs General</a> - General studies. **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/vuejs_object_change">VueJs Object Change</a> - Studies on modifying, deleting properties and making object copies. **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/vuejs_computed">VueJs Computed</a> - Study on computed with a v-for directive, filtering by object status. **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/vuejs_form">VueJs Form</a> - Study on forms. **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/vuejs_route">VueJs Route</a> - Study on routes. **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/vuejs_props">VueJs Props</a> - Study on props. **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/vuejs_slots">VueJs Slots</a> - Study on slots. **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/vuejs_component_dinamic">VueJs Dynamic Component</a> - Study on dynamic components. **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/vuejs_vuex">VueJs Vuex</a> - Study on shared state with vuex. **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/vuejs_vuex_v2">VueJs Vuex v2</a> - Study on shared state with vuex v2. **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/vuejs_axios">VueJs Axios</a> - Study on vuejs with axios. **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/vuejs_todo">Vuejs Todo + Localstorage</a> - Case study of a task todo list. **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/vuejs_burguer">Vuejs Burger</a> - Case study of a burger sales app. **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/vuejs_props_by_copy">Vuejs Refs By Copy</a> - Study on passing by copy and by reference. **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/vuejs_css">Vuejs CSS</a> - Study on CSS. **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/vuejs_filters">Vuejs Filters</a> - Study on filters. **(finished)**<br />

👉 <a href="https://github.com/eneas-almeida/vuejs_mixins">Vuejs Mixins</a> - Study on mixins. **(finished)**<br />

## Academic

| Photo                                           | Description                                                                                                                                                                                                      |
| ----------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img src="./images/placa-1.jpeg" width="350" /> | 👉 <a href="https://github.com/eneas-almeida/sistemas-embarcados">Embedded Systems</a> - Final project for the Embedded Systems course in Computer Engineering, IFPB. **(finished)**<br />                       |
| <img src="./images/shield.png" width="350" />   | 👉 <a href="https://github.com/eneas-almeida/shield_dados">Prototyping</a> - Final project for the Prototyping course in Computer Engineering, IFPB. **(finished)**<br />                                        |

<hr>

### My Mentors and Teachers

The authors listed below are reference sources in my study and work journey — for most of them, I participated in courses that served as a foundation to deepen my knowledge.

-   Tiago Matos **(VueJs 3, Composition API, Pinia)**
-   João Rangel **(NestJs)**
-   Diego Fernandes **(NestJs, Microservices and RabbitMQ)**
-   Stephany Henrique **(GoLang)**
-   Otávio Augusto Gallego **(GoLang)**
-   Ellen körbes **(GoLang)**
-   Fernando Daciuk **(Javascript and advanced Git)**
-   Fernando Amaral **(Kafka)**
-   Wesley Willians **(Kafka, GoLang)**
-   Loiane Groner **(Angular)**
-   Leonardo Moura **(VueJs, Docker, Typescript and GraphQL)**
-   Matheus Battisti **(Docker, Kubernetes and VueJs)**
-   Nélio Alves **(Spring Boot)**
-   AlgaWorks **(Spring Boot and Angular)**
-   Otávio Lemos **(Architecture and TDD with Typescript)**
-   Ruan Delgado **(Algorithms and study tips)**
-   Fábio Akita **(Pragmatic study tips)**
-   Rocketseat **(NodeJs backend stack)**
-   Henrique Cunha **(Algorithms)**
-   César Vasconcelos **(Java)**
-   Otávio Miranda **(Design patterns with Typescript)**
-   Erick Wendel **(Advanced NodeJs)**
-   Linux Tips **(Linux, Docker and Kubernetes)**
-   Dev Soltinho **(Javascript, Git)**
-   Claudson Oliveira **(Working abroad, GoLang)**
-   Rodrigo Branas **(Javascript)**
-   Jonathan Baraldi **(DevOps with Rancher, AWS and GCP)**
-   Codar.me **(NodeJs)**
-   Plínio Naves **(VueJs & Vuetify)**
-   Victor Hugo Negrisoli **(Microservices)**

<hr>

© Document authored by <a href="https://github.com/eneas-almeida">Edivam Enéas de Almeida Júnior</a>.
