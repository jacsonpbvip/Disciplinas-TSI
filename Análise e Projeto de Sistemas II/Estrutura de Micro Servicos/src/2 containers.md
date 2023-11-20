# Containers

## Cliente

O cliente é o usuário final da aplicação.

## Aplicativo Mobile

O aplicativo mobile é construído em Flutter e permite ao cliente solicitar transporte.

## API Rest

A API Rest é construída em NodeJS e fornece endpoints para o aplicativo móvel.

## Banco de Dados

O banco de dados é um banco de dados relacional que armazena informações de usuários, solicitações, etc.

## API de Pagamento

A API de Pagamento é uma API externa que processa pagamentos.

## API de Notificação

A API de Notificação é uma API externa que envia notificações.

## API de Solicitações

A API de Solicitações é uma API externa que gerencia solicitações.

## API de Autenticação

A API de Autenticação é uma API externa que autentica usuários.

## API de Geolocalização

A API de Geolocalização é uma API externa que fornece informações de geolocalização.

## Relacionamentos

- O cliente usa o aplicativo móvel via HTTPS.
- O aplicativo móvel se comunica com a API Rest via HTTPS.
- A API Rest lê e grava no banco de dados via SQL.
- A API Rest se comunica com as APIs de Pagamento, Notificação, Solicitações, Autenticação e Geolocalização via HTTPS.
- As APIs de Pagamento, Solicitações e Autenticação lêem e gravam no banco de dados via SQL.
- A API de Pagamento notifica a API de Notificação sobre a conclusão do pagamento via HTTPS.