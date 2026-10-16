# 💬 WhatsApp Cadastro e Autenticação

Projeto desenvolvido para praticar a criação de uma interface inspirada no WhatsApp Web, com cadastro de usuários e autenticação usando uma API.

## 📌 Sobre o projeto

O objetivo é criar uma aplicação onde o usuário possa se cadastrar com nome, telefone e senha, além de realizar login com seus dados.

O projeto utiliza tecnologias de desenvolvimento web no frontend e no backend, com armazenamento de dados em um banco MySQL.

## 🚀 Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- Node.js
- Express
- MySQL
- API REST

## 📂 Estrutura do projeto

```text
whatsapp_cadastro_auth/
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
├── routes/
│   ├── signin.route.js
│   └── auth.route.js
├── db/
│   └── connection.js
├── main-exemplo.js
├── database.sql
├── .env.example
├── .gitignore
└── README.md
```

## ⚙️ Como executar o projeto

### 1. Instalar as dependências

É necessário ter o [Node.js](https://nodejs.org/) instalado.

Abra o terminal na pasta do projeto e execute:

```bash
npm install express cors mysql2 bcryptjs dotenv
```

### 2. Configurar o banco de dados

1. Abra o MySQL ou o phpMyAdmin.
2. Execute o script `database.sql`.
3. Configure as informações de conexão no arquivo `.env`, usando o `.env.example` como modelo.

### 3. Iniciar o servidor

Execute no terminal:

```bash
node main-exemplo.js
```

Se tudo estiver configurado corretamente, a API ficará disponível em:

`http://localhost:3000`

### 4. Abrir a interface

Abra o arquivo `frontend/index.html` com a extensão Live Server do VS Code.

## 🔗 Endpoints da API

| Método | Rota | Descrição |
|---|---|---|
| POST | `/signin` | Cadastro de usuários |
| POST | `/auth` | Autenticação de usuários |

As rotas dependem da configuração do servidor e do banco de dados.

## 🔒 Segurança

As senhas devem ser armazenadas com hash, utilizando uma biblioteca apropriada, como `bcryptjs`. O arquivo `.env` não deve ser enviado ao GitHub.

## 🎯 Objetivos de aprendizagem

- Criar páginas com HTML, CSS e JavaScript.
- Trabalhar com rotas usando Express.
- Enviar e receber dados por uma API.
- Conectar uma aplicação ao MySQL.
- Praticar cadastro e autenticação de usuários.
- Utilizar o Git e o GitHub para organizar o projeto.

## 👨‍💻 Autor

Desenvolvido como projeto de estudo de desenvolvimento web.

---

⭐ Projeto criado para praticar programação e integração entre frontend, backend e banco de dados.
