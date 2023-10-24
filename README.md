# teste-tecnico-x8
  Este é um projeto de exemplo que demonstra um aplicativo Java para realizar operações CRUD (Create, Read, Update, Delete) em produtos usando o framework Jakarta Persistence (JPA) e Spring Boot. O projeto também inclui um ambiente Docker com um banco de dados PostgreSQL.

## 🚀Visão Geral
Este projeto é composto por dois principais componentes:

Aplicação Java (Spring Boot):

Implementa as operações CRUD em produtos.
Utiliza o framework Jakarta Persistence (JPA) para mapear objetos Java para entidades de banco de dados.
Exposta na porta 8080.

Banco de Dados PostgreSQL (Docker):

Utiliza a imagem oficial do PostgreSQL.
Configurado para permitir conexões da aplicação Java.
Os dados são persistidos em um volume Docker.


### 🔧 Configuração e Execução
Certifique-se de ter o Docker e as ferramentas de desenvolvimento Java instaladas em seu ambiente.

Clone este repositório:

git clone https://github.com/saturi11/teste-tecnico-x8.git

Navegue até o diretório clonado:

cd nome-do-repositorio

Inicie os contêineres Docker com o Docker Compose:

docker-compose up -d

Execute a aplicação Java:

./mvnw spring-boot:run

A aplicação estará acessível em http://localhost:8080.

Endpoints da API
GET /api/produtos: Recupera todos os produtos.

GET /api/produtos/{id}: Recupera um produto pelo ID.

POST /api/produtos: Cria um novo produto.

PUT /api/produtos/{id}: Atualiza um produto existente.

DELETE /api/produtos/{id}: Deleta um produto.

## 🛠️ Construído com
O projeto faz uso das seguintes tecnologias e ferramentas:

Java: A aplicação é desenvolvida em Java, uma linguagem de programação amplamente utilizada.

Spring Boot: O framework Spring Boot é usado para simplificar o desenvolvimento de aplicativos Java.

Jakarta Persistence (JPA): JPA é usado para mapear objetos Java para entidades de banco de dados.

Docker: O Docker é utilizado para criar e gerenciar contêineres, incluindo a execução de um banco de dados PostgreSQL em um contêiner.

PostgreSQL: O banco de dados PostgreSQL é escolhido como o sistema de gerenciamento de banco de dados relacional.

Docker Compose: O Docker Compose é usado para definir e executar vários contêineres como parte de uma única aplicação

Variáveis de Ambiente

DATABASE_URL: URL de conexão com o banco de dados PostgreSQL.

DATABASE_USERNAME: Nome de usuário do banco de dados.

DATABASE_PASSWORD: Senha do banco de dados.

Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
## ✒️ Autor
* **Gabriel Saturi** - [[Gabriel Saturi](https://github.com/saturi11)]
