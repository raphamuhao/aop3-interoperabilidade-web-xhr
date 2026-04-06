# AOP 3 – Interoperabilidade Web com XMLHttpRequest

## 1. Introdução

Projeto de exemplo para a AOP 3 do curso Desenvolvimento Web - Backend. O objetivo é demonstrar o uso de processamento assíncrono de dados em aplicações web, utilizando o objeto XMLHttpRequest para comunicação com APIs REST.

O projeto simula um cenário de e-commerce, onde dados são buscados de serviços externos sem a necessidade de recarregar a página.

## 2. Objetivo

O objetivo do projeto é mostrar como funciona o ciclo completo de uma requisição assíncrona em uma aplicação web, desde a ação do usuário até o retorno e tratamento da resposta da API.

## 3. Interoperabilidade Web

A interoperabilidade web permite que diferentes sistemas se comuniquem entre si. Neste projeto, essa comunicação é feita por meio de APIs REST, que retornam dados no formato JSON.

O XMLHttpRequest possibilita que essa comunicação aconteça de forma assíncrona, melhorando o desempenho da aplicação e a experiência do usuário.

## 4. Funcionamento do Processamento Assíncrono

O processamento assíncrono ocorre da seguinte forma:

1. O usuário realiza uma ação na interface.
2. Um evento JavaScript é acionado.
3. O objeto XMLHttpRequest é criado.
4. A requisição HTTP é configurada.
5. A requisição é enviada para a API.
6. A aplicação continua funcionando normalmente.
7. A resposta da API é recebida.
8. A interface é atualizada com os dados retornados.

## 5. Estrutura do Projeto

A estrutura do projeto está organizada da seguinte maneira:

```

aop3-interoperabilidade-web-xhr/
├── index.html
├── js/
│   └── app.js
└── README.md

```

## 6. Desenvolvimento Colaborativo

O projeto foi versionado utilizando Git e hospedado no GitHub. Isso permite controle de versões, organização do código e trabalho colaborativo.

O repositório pode ser clonado utilizando o comando:

```

git clone https://github.com/raphamuhao/aop3-interoperabilidade-web-xhr.git

```

## 7. Boas Práticas Utilizadas

Durante o desenvolvimento, foram consideradas as seguintes boas práticas:

- Uso de processamento assíncrono
- Organização do código
- Tratamento de erros
- Separação entre lógica e interface
- Uso de versionamento com Git

## 8. Conclusão

Este projeto demonstra, de forma prática, como utilizar XMLHttpRequest para realizar requisições assíncronas em aplicações web, aplicando conceitos estudados em interoperabilidade web e desenvolvimento front-end.
