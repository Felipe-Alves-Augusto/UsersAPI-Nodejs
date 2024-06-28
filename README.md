# 🌐 API em Node.js com Frontend em Vue.js
Bem-vindo ao projeto API em Node.js com integração frontend em Vue.js! Este projeto oferece uma API robusta e eficiente, com diversas rotas para gestão de usuários e autenticação, integrando uma interface de usuário moderna e interativa.

# 🌟 Funcionalidades da API
A API foi desenvolvida utilizando Node.js e Express, garantindo alta performance e escalabilidade. Aqui estão as rotas principais que foram implementadas:

🏠 **Rota Home**

- GET /: Retorna informações iniciais da API através do HomeController.index.
  
👤 **Gestão de Usuários**

- POST /user: Cria um novo usuário com o UserController.create.
- GET /user: Lista todos os usuários (requer autenticação de administrador) com o UserController.index.
- GET /user/:id: Busca um usuário específico pelo ID (requer autenticação de administrador) com o UserController.findUser.
- PUT /user: Edita informações de um usuário (requer autenticação de administrador) com o UserController.edit.
- DELETE /user/:id: Remove um usuário específico pelo ID (requer autenticação de administrador) com o UserController.remove.
  
🔒 **Recuperação e Alteração de Senha**

- POST /recoverpassword: Inicia o processo de recuperação de senha com o UserController.recoverPassword.
- POST /changepassword: Permite a alteração de senha com o UserController.changePassword.
  
🔑 **Autenticação e Validação**

- POST /login: Realiza o login de um usuário com o UserController.login.
- POST /validate: Valida a autenticidade de um token de administrador com o HomeController.validate.
# 🛠️ Tecnologias Utilizadas
- Backend: API desenvolvida com Node.js e Express, proporcionando uma arquitetura de serviços rápida e eficiente.
- Autenticação: Implementação de middleware de autenticação para proteger rotas sensíveis.
- Frontend: Vue.js é utilizado para consumir as rotas da API, oferecendo uma interface de usuário reativa e amigável.
- Banco de Dados: MongoDB
