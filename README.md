# Gobarber

## :page_with_curl: Ídice: 
  - [Descrição do projeto:](#memo-descrição-do-projeto)
  - [Funcionalidades:](#gear-funcionalidades)
  - [Bibliotecas utilizadas:](#file_folder-bibliotecas-utilizadas)
  -  [Banco de dados:](#floppy_disk-banco-de-dados)
  - [Como executar:](#arrow_forward-como-executar)

## :memo: Descrição do projeto:

Projeto desenvolvido no bootcamp GoStack da Rockseat utilizando Node.js.

Neste projeto foi desenvolvido as apis da aplicação, onde irá integrar o frontend tanto web como mobile;.

 Propósito de criação:
 
- Api visualização de agendamento dos clientes.
- Api agendamento de horário.
- Api cadastro de clientes e prestadores de serviços (Barbearias).
- Api edição de Perfil.



## :gear: Funcionalidades:

- [X] Realizar agendamento.
- [X] Listar os agendamentos.
- [X] Realizar autenticaçao com token jwt.
- [X] Cadastrar usuário.
- [X] Atualizar avatar.
- [X] Atualizar perfil.
- [X] Adicionar cache na api que lista os agendamentos com banco de dados redis.
## :file_folder: Bibliotecas utilizadas: 
- date-fns.
- express.
- pg.
- cors.
- aws-sdk.
- celebrate.
- class-transformer.
- typeorm.
- bcryptjs.
- dotenv.
- jsonwebtoken.
- multer.
- handlebars.
- ioredis.
- nodemailer.
- rate-limiter-flexible.
- redis.
- uuidv4.
- tsyringe.
- reflect-metadata.
- express-async-errors.
## :floppy_disk: Banco de dados: 
- postgreSQL.
- redis
## :arrow_forward: Como executar:
No terminal clone o projeto.
```
git clone https://github.com/marcosrib/gobarber-backend.git
```
Entre na pasta do projeto e instale as dependências executando.
```
yarn ou npm install
```
Para rodar o projeto execute.

```
yarn dev:server
```

