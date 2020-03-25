## Rota /Recurso

# Métodos HTTP:

npm init

GET: Buscar/listar uma informação do back-end.
POST: Criar uma informação no back-end.
PUT: Alterar uma informação no back-end.
DELETE: Deletar uma informação do back-end.

# Tipos de parâmetros:

Query Params: Parâmetros nomeados enviados na rota após "?" (Filtros, paginação).
Route Params: Parâmetros utilizados para identificar recursos.
Request Body: Corpo da requisição, utilizado para criar ou altear recursos.

# Banco de dado

Knex.js:
npm install knex

diver: 
npm install sqlite3

conexão com o banco de dados:
npx knex init

database/migrations
migrations: {
  directory: './src/database/migrations'
},
useNullAsDefault: true

npx knex migrate:make create_ongs
npx knex migrate:latest

# segurança

npm install cors