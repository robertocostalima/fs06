# API REST
> API REST feita para aprender ExpressJS e Banco de dados

## Tecnologias
- NodeJS v16
- Express v4.18
- MySQL/MariaDB v8

## Instalação
Para baixar a aplicação, execute o seuinte comando em seu terminal:
`git clone https://github.com/robertocostalima/fs06.git`

Após baixar a aplicação, entre no diretório dela através do terminal e execute:
`npm install` ou `npm i`

## Configuração do banco de dados
É necessário configurar as credenciais do Banco de Dados.

### Estrutura do banco de dados
Acesse o cliente do terminal do seu banco de dados

> Copie e execute os comandos que estão no arquivo `/db.sql`;

### Credenciais
Abra o arquivo que se encontra no caminho
`/connecetion/databaseConnection.js`

E edite as seguintes linhas de acordo com suas credenciais do banco

```js
{
    host:'localhost',
    user:'root',
    password:'1234',
    database: 'fs06_teste'
}
```

### Executar o projeto
Para executar o projeto, no diretorio da aplicação através do terminal execute:
`nodemon index.js` ou `node index.js`

Sua API estará disponível nos endereços:
- http://localhost:8000/clientes
- http://localhost:8000/veiculos
