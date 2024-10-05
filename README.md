# DailyDiet-API

## Resumo do Projeto

O **DailyDiet-API** é uma aplicação que permite aos usuários monitorarem suas refeições diárias e controlarem sua dieta de maneira eficaz. O objetivo do sistema é registrar refeições, fornecer métricas detalhadas sobre o comportamento alimentar do usuário e garantir que todas as informações sejam acessíveis de forma segura e organizada. A API é projetada para ser escalável, segura e fácil de integrar com diversas plataformas.

## Funcionalidades Principais

- **Criação de Usuário**: Cadastro de novos usuários no sistema.
- **Autenticação de Usuário**: Autenticação via JWT (JSON Web Token) para garantir segurança e controle de acesso.
- **Registro de Refeições**: Permitir o registro de refeições, incluindo nome, descrição, data, hora e se a refeição está dentro da dieta.
- **Edição e Exclusão de Refeições**: Capacidade de editar ou excluir refeições já registradas.
- **Listagem de Refeições**: Exibir todas as refeições registradas por um usuário específico.
- **Métricas de Refeições**: Recuperar métricas como quantidade total de refeições, refeições dentro e fora da dieta, e melhor sequência de refeições dentro da dieta.

## Tecnologias Utilizadas

- **Node.js**: Plataforma de desenvolvimento para construir a API.
- **Express.js**: Framework utilizado para roteamento e gerenciamento de middleware da aplicação.
- **MongoDB**: Banco de dados NoSQL para armazenar informações dos usuários e refeições.
- **JWT (JSON Web Token)**: Para autenticação e controle de acesso.
- **Docker**: Usado para garantir que a API seja facilmente distribuída e escalável em diferentes ambientes.

## Arquitetura do Sistema

A arquitetura da **DailyDiet-API** segue uma abordagem de microsserviços, com divisão clara entre os componentes principais:

- **API Gateway**: O ponto de entrada para todas as requisições da API.
- **Serviço de Autenticação**: Gerencia o cadastro e autenticação de usuários.
- **Serviço de Refeições**: Controla o registro, edição e exclusão de refeições.
- **Serviço de Métricas**: Calcula as métricas relacionadas ao comportamento alimentar do usuário.
- **Banco de Dados de Usuários**: Armazena informações dos usuários registrados.
- **Banco de Dados de Refeições**: Armazena informações das refeições registradas pelos usuários.


