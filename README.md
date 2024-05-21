Trabalho Prático: Autenticação com JsonwebToken em Node.js e Express com Sequelize e SQLite

para instalar dependências execute o comando: 
```sh
npm i
```

para executar o projeto use o comando :
```sh 
node index.js
```

as rotas de acesso e teste estao no arquivo da raiz: 
thunder-collection_auth-api.json


Rotas de acesso:
Para Registrar um Novo Usuário:

Método: POST URL: http://localhost:3000/register { "username": "Nome do Usuário", "email": "usuario@email.com", "password": "senha123" } 

Para Fazer Login :

Método: POST URL: http://localhost:3000/login { "email": "usuario@email.com", "password": "senha123" } 

Acessar a listagem da  Rota Protegida:

Método: GET URL: http://localhost:3000/users 
