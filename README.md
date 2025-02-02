# Azure Functions

## Description / Descrição
[EN] This repository contain example on how to implement an Serverless application using Azure Functions v3, .NET Core 3 and Azure Storage.
[PT] Este repositório contém exemplo sobre como implementar uma aplicação Serverless utilizando o Azure Functions, Azure Functions v3, .NET Core 3 e o Azure Storage.

## How to run / Como executar
[EN] You can create a local.settings.json file and create the connection strings AzureWebJobsStorage and AzureWebJobsDashboard and place your connection string with Azure Storage or you can publish it directly to Azure.
[PT] Você pode criar um arquivo local.settings.json e criar as connections strings AzureWebJobsStorage e AzureWebJobsDashboard e colocar sua string de conexão com o Azure Storage ou você pode publicar diretamente no Azure.

## Good Practices Adopted / Boas Práticas Adotadas

1. **Protection of Sensitive Information / Proteção de Informações Sensíveis**:
   - The `local.settings.json` file and Azurite directories have been configured to be ignored in Git.
   - O arquivo `local.settings.json` e os diretórios do Azurite foram configurados para serem ignorados no Git.

2. **Using Environment Variables / Uso de Variáveis de Ambiente**:
   - In production, sensitive data should be stored as environment variables.
   - Em produção, dados confidenciais devem ser armazenados como variáveis de ambiente.

3. **Pre-Publication Validation / Validação Pré-Publicação**:
   - The project structure has been revised to ensure that sensitive information is not published.
   - A estrutura do projeto foi revisada para garantir que informações sensíveis não sejam publicadas.

---

## References / Referências

- [Azure Functions documentation / Documentação do Azure Functions](https://learn.microsoft.com/en-us/azure/azure-functions/)
- [Postman - API Testing Tool / Postman - Ferramenta para Testes de API](https://www.postman.com/)
- [Configuring Azurite / Configurando o Azurite](https://learn.microsoft.com/en-us/azure/storage/common/storage-use-azurite)