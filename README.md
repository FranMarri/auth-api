Trabalho Prático: Autenticação com JsonwebToken em Node.js e Express com Sequelize e SQLite

executar = node index.js

Dependências = npm install express sequelize sqlite3 jsonwebtoken bcrypt

Como Usar as Rotas: Registrar um Novo Usuário:

Método: POST URL: http://localhost:3000/register Corpo da Requisição: json Copiar código { "username": "Nome do Usuário", "email": "usuario@email.com", "password": "senha123" } 

Fazer Login e Obter Token JWT:

Método: POST URL: http://localhost:3000/login Corpo da Requisição: json Copiar código { "email": "usuario@email.com", "password": "senha123" } 
Acessar a listagem da  Rota Protegida:

Método: GET URL: http://localhost:3000/users Cabeçalho da Requisição: auth: Bearer token, colar seu token fornecido ao fazer login, em resposta verá os registos cadastrados.
