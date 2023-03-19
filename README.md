# Integração Python com Firebase

Este repositório contém um projeto simples de integração entre Python e Firebase, utilizando as bibliotecas requests, json e um arquivo Jupyter Notebook main.ipynb. O objetivo deste projeto é demonstrar como realizar operações básicas no Firebase, como criar, ler, atualizar e deletar dados utilizando Python.

# Requisitos

- Python 3.6 ou superior
- Jupyter Notebook
- ibliotecas requests e json

# Configuração

Antes de executar o arquivo main.ipynb, configure suas credenciais do Firebase:

1. Acesse o console do Firebase, crie um novo projeto ou utilize um projeto existente.

2. Crie um arquivo chamado firebase_credentials.json no diretório raiz do projeto.

3. Vá até a página "Configuração do projeto" e clique em "Adicionar aplicativo" na seção "Seus aplicativos".

4. Selecione a plataforma "Web" e siga as instruções para criar o aplicativo.

{
  "apiKey": "your-api-key",
  "authDomain": "your-auth-domain",
  "databaseURL": "your-database-url",
  "projectId": "your-project-id",
  "storageBucket": "your-storage-bucket",
  "messagingSenderId": "your-messaging-sender-id",
  "appId": "your-app-id"
}

