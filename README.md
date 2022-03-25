# BookStore
This project was used as an example of how to deploy a .NET 6 Web API with a SQL database by using Azure Pipelines

## Article:

[![Medium Badge](https://img.shields.io/badge/-Medium-black?style=flat-square&logo=Medium&logoColor=white&link=https://henriquesd.medium.com/deploying-a-net-6-web-api-and-a-sql-database-with-azure-pipelines-585e2e18a463)](https://henriquesd.medium.com/deploying-a-net-6-web-api-and-a-sql-database-with-azure-pipelines-585e2e18a463)

## Technologies
- .NET 6
- Entity Framework 6
- Fluent API
- AutoMapper
- Swagger
- SQL Server

### Unit tests
- xUnit
- Moq
- SQLite In-Memory database

## Architecture
- 3 Layers:
  - Application layer (API)
    - Controllers
    - Dtos
  - Domain layer
    - Models
    - Interfaces
    - Services
  - Infrastructure layer
    - Repository Pattern
