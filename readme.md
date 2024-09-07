# Docker Compose YML Files Repository

## Introduction
This repository contains Docker Compose YML files for setting up various services like MongoDB and Kafka with a user interface.

## Introdução
Este repositório contém arquivos YML do Docker Compose para configurar vários serviços como MongoDB e Kafka com uma interface de usuário.

## Usage / Uso

### English
1. Clone the repository:
   ```sh
   git clone https://github.com/rafaelwms/docker-yaml.git
   cd docker-yaml
2. Setup a Container, i.e. (rabbitmq service):
   ```sh
   docker compose -f rabbitmq.yml up -d
3. Stop a Service / Container:
   ```sh
   docker compose -f rabbitmq.yaml stop
4. Remove a Service / Container:
   ```sh
   docker compose -f rabbitmq.yml down

### Português
1. Clonar o repositório:
   ```sh
   git clone https://github.com/rafaelwms/docker-yaml.git
   cd docker-yaml
2. Criar um Container, ex. (serviço do rabbitmq):
   ```sh
   docker compose -f rabbitmq.yml up -d
3. Parar um Serviço / Container:
   ```sh
   docker compose -f rabbitmq.yaml stop
4. Remover um Serviço / Container:
   ```sh
   docker compose -f rabbitmq.yml down