## Escola de Software - Autorizador - API Gateway

Esse repositório contém a API gateway do microserviço de autorizador da escola de software.

# Rotas disponíveis

- POST /realizar-login

Rota para realizar o login na escola de software, tem como resposta um token que deve ser guardado para ser utilizado posteriormente.

Body:
- email: string, required
- senha: string, required

- POST /refresh-token

Rota para criar um novo token a partir de um token ativo.

Body:
- token: string, required
Headers:
- Authorization (bearer): string, required

# Infraestrutura criada

O repositório cria toda a infraestrutura do API Gtw e também as permissões de Invoke para cada lambda que será utilizada.

Obrigado

<hr/>

## Escola de Software - Authorizer - API Gateway

This repository contains the API Gateway of Authorizer microservice of escola de software.

# Available routes

- POST /realizar-login

This route can be used to login into escola de software, the response will give you a token which need to be store to futher use.

Body:
- email: string, required
- senha: string, required

- POST /refresh-token

This route can be used to refresh your token by your actual token

Body:
- token: string, required
Headers:
- Authorization (bearer): string, required

# Infrastructure created

The repository create all the infrastructure of the API Gateway plus the policies for invoke lambdas.

Thanks a lot