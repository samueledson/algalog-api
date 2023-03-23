# AlgaLog API

Este repositório contém o código-fonte de uma API REST desenvolvida em Spring Boot, Spring MVC e Spring Data JPA. A API foi desenvolvida como parte do curso MSR (Mergulho Spring REST) realizado pela AlgaWorks e tem como objetivo fornecer um serviço de entrega de pedidos.

## Instalação

Para instalar a API, siga as instruções abaixo:

1. Clone este repositório em sua máquina local.
2. Certifique-se de ter o Java e o Maven instalados em sua máquina.
3. Execute o comando `mvn install` na pasta raiz do projeto para baixar as dependências e gerar o arquivo .jar.

## Como usar

Para executar a API, abra o terminal na pasta raiz do projeto e execute o comando `java -jar target/algalog-api-0.0.1-SNAPSHOT.jar`. Em seguida, utilize um cliente HTTP para enviar requisições à API.

## Funcionalidades

A API disponibiliza as seguintes funcionalidades:

- Cadastro de clientes, entregas e pedidos
- Consulta de clientes, entregas e pedidos específicos
- Listagem de clientes, entregas e pedidos paginada
- Atualização de clientes, entregas e pedidos existentes
- Exclusão de clientes, entregas e pedidos existentes

## Docs

A coleção do Postman com exemplos de requisições está disponível no arquivo `AlgaLog.postman_collection.json`.

## Diagrama de classes:

![image](https://user-images.githubusercontent.com/3043984/226506785-6cdad8bb-2454-4db1-ba6a-1a57e0f7cb84.png)

