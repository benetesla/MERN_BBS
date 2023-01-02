# MERN_BBS
## BACKEND(BBS)

## PASTA CONTROLLERS
Dentro da nossa pasta de controles temos o seguinte conteúdo:
AUTH:  em nosso auth está a autenticação de nosso sistema, nessa autenticação, usamos o JWT json web Token e o Bycript.
BYCRYPT 
 JWT
POST: aqui se encontra a nossa lógica para os posts(CRUD)
Nessa parte não temos nenhuma autenticação,apenas os métodos,create Post
get Feed Posts
 getUser Posts
like Post
USE:responsável por setar o nosso usuário, pegando os métodos presentes no post.
## PASTA DATA
Na pasta de data temos apenas os valores iniciais dos nossos registros do backend,foi esta pagina que usei como teste para o cadastro inicial dos nossos usuários.
## PASTA MIDDLEWARE
Esta pasta é o nosso intermédio entre todo o nosso sistema,nela temos a verificação do token e o sistema de acesso ao nosso sistema.
Na pasta modelo temos o nosso schema, aqui e onde está a nossa conexão com MongoDB, dentro desta pasta temos a post:nela se encontra o nosso sistema de posts e temos a nossa pasta de utilizadores la e onde inserimos as informações dos nossos utilizadores.
## PASTA ROUTES
Dentro da pasta AUTH temos a autenticação de nossa rota,que recebe os respectivos valores do auth que está presente na pasta de controllers.
Dentro da pasta POSTS temos os controles dos nossos posts do sistema, ler todos fazer alterações(UPDATE).
Dentro da pasta USERS temos  os nossos usuários,basicamente com as mesmas especificações  DA PASTA POSTS.

## BACKEND
```bash
  npm install express

```
## Deploy

Para fazer o deploy desse projeto rode no backend
```bash
use data for add fake useres in the data base
Insert.many.Users/POSTS
```
## Variáveis de Ambiente

Para rodar esse projeto, você vai precisar adicionar as seguintes variáveis de ambiente no seu .env
`NPM RUN DEV`

## Referência

 - [MULTER](https://www.npmjs.com/package/multer)
 - [EXPRESS](https://www.npmjs.com/package/express)
 - [BODY_PARSER](https://www.npmjs.com/package/body-parser)
 - [MONGOOSE](https://www.npmjs.com/package/mongoose)
 - [CORS](https://www.npmjs.com/package/cors)
 - [DOTENV](https://www.npmjs.com/package/dotenv)
 - [HELMET](https://www.npmjs.com/package/helmet)
 - [MORGAN](https://www.npmjs.com/package/morgan)

## FRONTEND(BBS)

## PASTA COMPONENTS
Nesta pasta nós temos alguns padrões do CSS(CSS BASELINE) de nosso projeto,Para imagens lista de amigos etc.

## PASTA INICIO
Na pasta de início temos os estados de nossa aplicação, HomePage(página inicial),  login page(página de login)que contém o formulário de cadastro login(form), navegar(a nossa barra de navegação) e claro nossa página de perfil , Junto dos nossos Widgets, usados na estilização da nossa aplicação.
## PASTA STATE
Nesta página temos o gerenciamento dos estados da nossa aplicação,login logout, posts, tudo que está ligado diretamente ao backend passará por esta página. 
Na theme está o tema da nossa aplicação.




## Referência

 - [CSS BASELINE](https://mui.com/material-ui/react-css-baseline/)
 - [USEMEMO](https://www.w3schools.com/react/react_usememo.asp)
 - [USESELECTOR](https://react-redux.js.org/api/hooks#useselector)
 - [HOOKS](https://react-redux.js.org/api/hooks)
 - [SLICE](https://react-redux.js.org/tutorials/quick-start#create-a-redux-state-slice)
 - [FORMIK](https://formik.org/docs/examples/with-material-ui)
 
## Stack utilizada

**Front-end:** <img src="https://img.shields.io/badge/Material%20UI-007FFF?style=for-the-badge&logo=mui&logoColor=white">
<img src="https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white">
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E">


**Back-end:**
<img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white">
<img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white">
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white">
<img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white">
<img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E">
<img src="https://img.shields.io/badge/json-5E5C5C?style=for-the-badge&logo=json&logoColor=white">

## Funcionalidades

- Temas dark e light
- Preview em tempo real
- Modo tela cheia
- Multiplataforma


## Autores

- [@BENE_TESLA](https://github.com/benetesla)
