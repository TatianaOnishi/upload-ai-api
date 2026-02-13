## 🚀 upload.ai API

API desenvolvida durante o NLW IA 2023 da Rocketseat, responsável pelo processamento de vídeo, transcrição e integração com modelos de Inteligência Artificial.

Este repositório contém o back-end da aplicação.
O front-end pode ser acessado [aqui](https://github.com/TatianaOnishi/upload-ai).

## 🧠 Sobre a API

A upload.ai API é responsável por todo o fluxo de processamento e geração de conteúdo baseado em vídeo.

## 🔄 Fluxo de funcionamento

- Recebe upload de vídeo.
- Processa e extrai o áudio.
- Realiza transcrição automática.
- Envia a transcrição para um modelo da OpenAI.
- Retorna títulos e descrições gerados dinamicamente.

### A API permite que o cliente configure:

- Modelo de linguagem.
- Temperatura da geração.
- Prompt personalizado.
- Palavras-chave para direcionamento do conteúdo.

O objetivo é transformar mídia bruta em conteúdo estruturado e pronto para publicação.

## 🏗️ Responsabilidades Técnicas

- Manipulação e processamento de arquivos.
- Orquestração de chamadas para API de IA;
- Engenharia de prompt dinâmica.
- Persistência de dados com ORM.
- Estruturação de endpoints REST.
- Separação de responsabilidades e organização em camadas.

## 🛠️ Stack Tecnológica

- Node.js
- Prisma ORM
- OpenAI API
- TypeScript
- Banco de dados relacional

## ⚙️ Como executar o projeto

### 1️⃣ Configuração inicial

Siga as instruções de setup descritas na [documentação](https://efficient-sloth-d85.notion.site/Trilha-Mastery-3857d78aff924b81a37f0698bc40a435) oficial do evento. 

### 2️⃣ Instalar dependências
```
npm install
```

### 3️⃣ Executar a aplicação
```
npm run dev
```

## 🎯 Objetivo do projeto

Demonstrar integração prática entre processamento de mídia, persistência de dados e IA generativa, aplicando boas práticas de arquitetura back-end e organização de código.

A API foi estruturada para ser escalável, configurável e facilmente integrável a diferentes interfaces clientes.