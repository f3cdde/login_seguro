# Login Seguro

Este é um exemplo de sistema de login seguro utilizando Node.js, Express, e MongoDB. O projeto inclui registro de usuários, login, autenticação com JWT e proteção de rotas.

## Estrutura do Projeto

login-seguro/
│
├── src/
│   ├── app.js
│   ├── controllers/
│   │   └── auth.js
│   ├── models/
│   │   └── user.js
│   ├── routes/
│   │   └── auth.js
│   ├── middleware/
│   │   └── auth.js
│   └── views/
│       ├── login.ejs
│       ├── register.ejs
│       ├── dashboard.ejs
│       └── index.ejs
├── public/
│   └── styles.css
├── Dockerfile
├── docker-compose.yml
├── package.json
└── .env

## Dependências

- Node.js
- Express
- bcryptjs
- jsonwebtoken
- mongoose
- dotenv
- cookie-parser

## Configuração do Ambiente

Crie um arquivo `.env` na raiz do projeto com as seguintes variáveis de ambiente:


PORT=3000 MONGO_URI=mongodb://localhost:27017/login-seguro JWT_SECRET=seu_segredo_jwt


## Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu-usuario/login-seguro.git

2. Navegue até o diretório do projeto:
   cd login-seguro

3. Instale as dependências:
   npm install

## Funcionalidades
Registro de usuários
Login de usuários
Autenticação com JWT
Proteção de rotas
Logout de usuários

## Estrutura de Pastas
src/: Contém o código-fonte do projeto.
app.js: Arquivo principal do servidor Express.
controllers/: Contém os controladores para lidar com a lógica de negócios.
models/: Contém os modelos Mongoose.
routes/: Contém as definições de rotas.
middleware/: Contém os middlewares de autenticação.
views/: Contém as visualizações EJS.
public/: Contém arquivos estáticos (CSS, imagens, etc.).
Dockerfile: Arquivo de configuração do Docker.
docker-compose.yml: Arquivo de configuração do Docker Compose.
package.json: Arquivo de configuração do npm.
.env: Arquivo de configuração de variáveis de ambiente.

## Licença
Este projeto está licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.


### Passos para Garantir que o Projeto está Funcional

1. **Clone o repositório**: Certifique-se de que você pode clonar o repositório do GitHub.
2. **Crie os arquivos necessários**: Certifique-se de que todos os arquivos mencionados acima estão presentes e configurados corretamente.
3. **Construa e inicie os serviços Docker**: Construa e inicie os serviços Docker com o comando:

   ```bash
   docker-compose up --build

Aguarde até que todos os serviços estejam prontos: Certifique-se de que todos os serviços estejam prontos antes de tentar acessar a aplicação no navegador.
Acesse a aplicação no navegador: Acesse a aplicação no navegador em http://localhost:3000.