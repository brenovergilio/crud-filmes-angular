# Curso Intermediário de Angular - Digital Innovation One

Esse curso foi feito para a plataforma [Digital Innovation One](https://digitalinnovation.one/)

O curso consiste em um sistema de filmes, com a possibilidade de cadastros, edições, listagem e visualização dos cursos de outros usuários.

## Instalação

1. clone o repositório `git clone git@github.com:RenanRB/curso-angular.git`
2. Entre no projeto e instale as dependencias `npm install`

## Ambiente Local

Execute `ng serve` para que o projeto suba localmente. Acesse a url `http://localhost:4200/`. O projeto já está com reload automático conforme as alterações que você realizar no código

## Simulando o Back-end

Execute `npm install -g json-server` para instalar globalmente o servidor json. Após a instalação entre na pasta do projeto e execute `json-server --watch db.json`, com isso um servidor será inicializado na url `http://localhost:3000/`, após a inicialização sera possível realizar requisições http.

## Gerendo componente

Execute `ng generate component nome-do-componente` para criar um novo componente. Você também pode usuar `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Execute `ng build` para gerar o compilado do projeto. O projeto vai ser criado dentro do diretório `dist/`. Adicionar `--prod` junto comando de build para gerar minificado e pronto para o ambiente de produção.

# CRUD de filmes com Angular 8 

Projeto da Digital Innovation One para a criação de um CRUD de filmes utilizando Angular 8 e json-server para simular o back-end.
## Imagens

![incial](./screenshots/main.png)
![cadastro](./screenshots/cad.png)
![confirm](./screenshots/confirm.png)
![pesquisa](./screenshots/search.png)
![view](./screenshots/view.png)

## Instalação

Clone ou baixe o arquivo .zip do repositório

```sh
git clone https://github.com/brenovergilio/crud-filmes-angular.git
```
Navegue para a pasta do projeto e atualize as dependências com o comando npm install

```sh
cd $path/crud-filmes-angular
npm install
```

Instale o JSON-SERVER
```
npm install -g json-server
```

Inicie o JSON-SERVER local

```
json-server --watch db.json
```

Inicie o servidor local
```
ng s
```