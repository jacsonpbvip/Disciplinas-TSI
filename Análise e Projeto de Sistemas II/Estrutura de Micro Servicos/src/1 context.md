# Contexto da Aplicação para transporte de pessoas ou encomendas

A aplicação é composta por vários componentes, conforme descrito abaixo:

## Aplicativo Mobile

O aplicativo mobile é construído em Flutter e permite ao cliente solicitar transporte. Ele é composto por três componentes principais:

- Interface de Usuário: Permite ao usuário interagir com o aplicativo.
- Serviço de Solicitação: Permite ao usuário fazer solicitações de transporte.
- Serviço de Pagamento: Permite ao usuário fazer pagamentos.

## Aplicativo Web

O aplicativo web é construído em PHP e permite ao administrador gerenciar a aplicação em geral. Ele é composto por dois componentes principais:

- Interface de administrador: Permite ao administrador gerenciar a aplicação em geral.
- Gestao da aplicação: Permite ao administrador gerenciar a aplicação em geral.

## API Rest

A API Rest é construída em NodeJS e fornece endpoints para o aplicativo móvel.

## EC2

O EC2 é um serviço de computação na nuvem da AWS que hospeda vários microserviços:

- Microserviço de Pagamento: Gerencia todas as operações de pagamento.
- Microserviço de Notificação: Gerencia todas as operações de notificação.
- Microserviço de Autenticação: Gerencia todas as operações de autenticação.
- Microserviço de Geolocalização: Gerencia todas as operações de geolocalização.
- Microserviço de Solicitação: Gerencia todas as operações de solicitação.

## RDS

O RDS é um banco de dados relacional na nuvem da AWS.

## Relacionamentos

- A Interface de Usuário e o Serviço de Pagamento do aplicativo mobile usam o Serviço de Solicitação.
- A Interface de administrador do aplicativo web usa a Gestao da aplicação.
- O Serviço de Solicitação e o Serviço de Pagamento do aplicativo mobile se comunicam com a API Rest.
- A API Rest se comunica com todos os microserviços hospedados no EC2.
- Todos os microserviços se comunicam com o banco de dados RDS.
- A Gestao da aplicação do aplicativo web se comunica com a API Rest.