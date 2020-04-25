# Curso Intermediário de Angular - Digital Innovation One

Esse curso foi feito para a plataforma [Digital Innovation One](https://digitalinnovation.one/)

Conheça mais sobre a plataforma com cursos gratuitos https://digitalinnovation.one/sign-up?ref=QFX2ZVP4RU

O curso consiste em um sistema de filmes, com a possibilidade de cadastros, edições, listagem e visualização dos filmes.

## Instalação

1. clone o repositório `git clone https://github.com/4lexRossi/CRUD-Angular-8`
2. Entre no projeto e instale as dependencias `npm install`

## Ambiente Local

Execute `ng serve` para que o projeto suba localmente. Acesse a url `http://localhost:4200/`. O projeto já está com reload automático conforme as alterações que você realizar no código

## Simulando o Back-end

Execute `npm install -g json-server` para instalar globalmente o servidor json. Após a instalação entre na pasta do projeto e execute `json-server --watch db.json`, com isso um servidor será inicializado na url `http://localhost:3000/`, após a inicialização sera possível realizar requisições http.

## Gerendo componente

Execute `ng generate component nome-do-componente` para criar um novo componente. Você também pode usuar `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Execute `ng build` para gerar o compilado do projeto. O projeto vai ser criado dentro do diretório `dist/`. Adicionar `--prod` junto comando de build para gerar minificado e pronto para o ambiente de produção.

