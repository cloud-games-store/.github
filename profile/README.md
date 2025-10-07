# FIAP Cloud Games Store 

MVP da plataforma FIAP Cloud Games, desenvolvido na Pós-graduação Arquitetura de Sistemas .NET – FIAP.

O objetivo é desenvolver uma plataforma de venda de jogos digitais e gestão de servidores para partidas online. 

## Tecnologias 

- .NET 8
- Entity Framework
- SQL Server
- Docker
- Bcrypt + JWT
- OpenTelemetry
- Application Insights

## Arquitetura

- Clean Architecture
- Domain-Driven Design (DDD)
- Result Pattern

## Microsserviços

- [User Service](https://github.com/cloud-games-store/cloud-games-store-users): Microsserviço responsável por lidar com as operações referente aos usuários, incluindo autenticação.
- [Games Service](https://github.com/cloud-games-store/cloud-games-store-games): Microsserviço responsável por lidar com operações de listagem e busca de jogos.
- [Checkout Service](https://github.com/cloud-games-store/cloud-games-store-checkout): Microsserviço responsável por lidar com o processo de compra de jogos.
- [Payments Service](https://github.com/cloud-games-store/cloud-games-store-payments): Serverless responsável por simular a etapa de pagamento após confirmado o checkout.
- [Biblioteca de Logs](https://github.com/cloud-games-store/cloud-games-store-logs): Biblioteca própria utilizada pelos serviços, sendo responsável por centralizar o registro de logs no Application Insights.



