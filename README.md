# NestJS Microservice Project
This project is a microservice architecture built with NestJS, designed to study and implement RabbitMQ for message queuing. The project is structured into separate services, each handling different aspects of the application. The services include authentication, billing, and order processing.

## Language

<!--ts-->
  * [[en-US]](#Overview)
  * [[pt-BR]](#Visão-Geral)
<!--te-->

## Collection Postman
[NestJs Microservices.postman_collection.json](https://github.com/user-attachments/files/16120993/NestJs.Microservices.postman_collection.json)

------------------------
### [en-US]
## Overview

This project is a microservice architecture built with NestJS, designed to study and implement RabbitMQ for message queuing. The project is structured into separate services, each handling different aspects of the application. The services include authentication, billing, and order processing.

## Technologies Used

- **NestJS**
- **RabbitMQ**
- **MongoDB**
- **Docker**
- **TypeScript**
  
### Applications

- **Auth**: Handles user authentication and authorization.
- **Billing**: Manages billing-related operations.
- **Orders**: Processes and manages orders.

## Getting Started

### Prerequisites

- Docker
- Node.js
- npm

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/nestjs-microservice.git
   cd nestjs-microservice
2. Install dependencies:
   ```bash
   npm install

### Running the Services
1. Start the services using Docker Compose:
   ```bash
   docker-compose up --build
2. The services will be available on the following ports:
   - Auth: http://localhost:3001
   - Orders: http://localhost:3000

---------------------
### [pt-BR]
## Visão Geral

Este projeto é uma arquitetura de microsserviços construída com o NestJS, concebida para estudar e implementar o RabbitMQ para enfileiramento de mensagens. O projeto está estruturado em serviços separados, cada um tratando de diferentes aspectos da aplicação. Os serviços incluem autenticação, faturação e processamento de encomendas.

## Tecnologias Utilizadas

- **NestJS**
- **RabbitMQ**
- **MongoDB**
- **Docker**
- **TypeScript**
  
### Aplicações

- **Auth**: Trata da autenticação e autorização do utilizador.
- **Billing**: Gerir as operações relacionadas com a faturação.
- **Orders**: Processa e gere encomendas.

## Começando

### Pré-requisitos

- Docker
- Node.js
- npm

### Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/your-repo/nestjs-microservice.git
   cd nestjs-microservice
2. Instale as dependências:
   ```bash
   npm install

### Rode os serviços
1. Rode os serviços usando Docker Compose:
   ```bash
   docker-compose up --build
2. Os serviços estarão disponíveis nessas portas:
   - Auth: http://localhost:3001
   - Orders: http://localhost:3000
