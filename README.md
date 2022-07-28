<!-- ABOUT THE PROJECT -->
# About The Project

A sample Java Azure App Service with Azure App Configuration with secrets from Azure Key Vault.

## Contents

## Core Prerequisites

## Installation
1. Created a simple Java App iwith App configuration 
https://docs.microsoft.com/en-us/azure/azure-app-configuration/quickstart-java-spring-app 

2. Create a KV Message and Modify the Code to read message from App Config to KV.
https://docs.microsoft.com/en-us/azure/azure-app-configuration/use-key-vault-references-spring-boot

3. Deploy to App Service, use App Settings to create environment variables AZURE_CLIENT_ID, AZURE_CLIENT_SECRET, and AZURE_TENANT_ID


4. Enable Managed Identity for App Service
https://docs.microsoft.com/en-us/azure/azure-app-configuration/howto-integrate-azure-managed-service-identity?tabs=core5x&pivots=framework-spring

5. Remove/Delete the environment variables AZURE_CLIENT_ID, AZURE_CLIENT_SECRET, and AZURE_TENANT_ID and test Managed Identity credentials. 

## Addons

## Security

## Testing

## Retail Materials

## Architecture

## Solution Components

### Trademarks

Trademarks This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft trademarks or logos is subject to and must follow Microsoft’s Trademark & Brand Guidelines. Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship. Any use of third-party trademarks or logos are subject to those third-party’s policies.
