🖼️ Galeria de Imagens

API REST para gerenciamento e compartilhamento de imagens, desenvolvida com Java e Spring Boot.

🚀 Tecnologias
Java 17+
Spring Boot
Spring Security
JWT
Spring Data JPA
PostgreSQL
Maven
JUnit / Mockito
Swagger / OpenAPI
✨ Funcionalidades
Cadastro e autenticação de usuários
Autenticação com JWT
Controle de acesso aos endpoints
Upload de imagens
Suporte a PNG, JPEG e GIF
Validação de tamanho e formato dos arquivos
Cadastro de tags
Pesquisa por nome, tag e extensão
Galeria de imagens
Visualização da imagem em tamanho real
Tratamento de erros e notificações das operações
🔐 Autenticação

Após o login, a API retorna um token JWT que deve ser enviado nas requisições protegidas:

Authorization: Bearer <token>

🌐 Principais endpoints
Método	Endpoint	Descrição
POST	/api/auth/register	Cadastro
POST	/api/auth/login	Login
POST	/api/auth/logout	Logout
POST	/api/images	Upload de imagem
GET	/api/images	Pesquisa de imagens
GET	/api/images/{id}	Detalhes da imagem
GET	/api/images/{id}/file	Imagem em tamanho real
⚙️ Como executar

Clone o projeto:

git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio


Configure o banco de dados e as variáveis de ambiente.

Execute:

./mvnw spring-boot:run


Ou:

./mvnw clean package
java -jar target/*.jar

📌 Status

🚧 Em desenvolvimento.