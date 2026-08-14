🖼️ Galeria de Imagens

Uma API REST para upload, gerenciamento e pesquisa de imagens, desenvolvida com Java e Spring Boot.

🛠️ Tecnologias






Java 17+
Spring Boot
Spring Security
Spring Data JPA
JWT
PostgreSQL
Maven
JUnit / Mockito
✨ Funcionalidades
👤 Autenticação
Cadastro de usuários
Login com e-mail e senha
Autenticação utilizando JWT
Controle de acesso
Logout
🖼️ Imagens
Upload de imagens
Suporte a PNG, JPEG e GIF
Validação de formato e tamanho
Cadastro de nome e tags
Pesquisa por nome, tag e extensão
Visualização em galeria
Visualização da imagem em tamanho real
🔐 Autenticação

Após realizar o login, a API retorna um JWT que deve ser enviado nas requisições protegidas:

Authorization: Bearer <seu-token>

📌 Endpoints
Método	Endpoint	Descrição
POST	/api/auth/register	Criar conta
POST	/api/auth/login	Realizar login
POST	/api/auth/logout	Encerrar sessão
POST	/api/images	Publicar imagem
GET	/api/images	Pesquisar imagens
GET	/api/images/{id}	Consultar imagem
GET	/api/images/{id}/file	Visualizar arquivo
🚀 Como executar
1. Clone o repositório
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio

2. Configure o banco de dados

Crie um banco PostgreSQL e configure as credenciais no application.properties ou através de variáveis de ambiente.

3. Execute a aplicação
./mvnw spring-boot:run


No Windows:

mvnw.cmd spring-boot:run


A API estará disponível em:

http://localhost:8080

🧪 Testes

Execute os testes com:

./mvnw test

📚 Documentação

A API pode ser documentada e testada através do Swagger/OpenAPI.

http://localhost:8080/swagger-ui/index.html

📈 Status

🚧 Em desenvolvimento

Desenvolvido com ☕ Java + Spring Boot