# Projeto API com Express.JS, Mongoose e MongoDB

Este projeto é uma API construída com Express.JS, Mongoose e MongoDB. Ele inclui rotas para manipulação de usuários, produtos e autenticação de usuários.

## Passo a passo para configurar o projeto

### 1. Clonar o repositório

Primeiro, clone o repositório do projeto:

```bash
git clone https://github.com/juliocesar014/pos-grad-express-js
cd pos-grad-express-js
```

```bash
npm install
# ou
yarn install
```

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
PORT=3000
```

```bash
npm start
# ou
yarn start
```

O servidor estará rodando na porta configurada no arquivo .env (por padrão, porta 3000).

### 2.  Estrutura do projeto

```bash
├── src
│   └── controller
│       └── ProductController.js
│       └── UserController.js
│   └── db
│       └── db.js
│   └── helpers
│       └── image-upload.js
│       └── manage-jwt.js
│   └── model
│       └── Product.js
│       └── User.js
│   └── public
│       └── images
    │        └── products
    │        └── users
│   └── routes
│       └── ProductRoutes.js
│       └── UserRoutes.js
│   └── service
│       └── ProductService.js
│       └── UserService.js
├── app.js
├── .env
├── .gitignore
├── package-lock.json
├── package.json
└── README.md
```