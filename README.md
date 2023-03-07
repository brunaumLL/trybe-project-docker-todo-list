# Dokcer Todo List

## Sobre o projeto:
- O projeto exige que sejam desenvolvidas soluções com o objetivo de “conteinerizar” as aplicações de frontend, backend e testes, criar uma conexão entre elas e orquestrar seu funcionamento!

## O que é de minha autoria:
- Todos arquivos dentro da pasta `docker/docker-commands/`, os arquivos `Dockerfile` dentro das pastas `docker/todo-app/back-end/`, `docker/todo-app/front-end/` e `docker/todo-app/tests/`, e o arquivo `docker/docker-compose.yml`

## Tecnologias utilizadas:
<img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" />

## Visualizar Projeto:
- Para ver o projeto são necessários: um Sistema Operacional Unix, Docker, Docker-compose.
- Tendo os requisitos necessários é preciso clonar o projeto e acessar a pasta dele via terminal.  
- Feito isso, basta instalar as dependências com o comando `npm i`, acessar a pasta `docker` com o comando `cd docker` e então iniciar o docker com o   comando `docker-compose up -d`.
- Depois que o container docker estiver concluído, acesse a url `http://localhost:3000/`.

## Repositório original do projeto:
https://github.com/tryber/sd-019-b-project-docker-todo-list

<details>
  <summary>
    <strong>
      :newspaper_roll: Requisitos do projeto
    </strong>
  </summary>

 
### Requisitos
*Nome* | *Avaliação*
--- | :---:
1 - Crie um container em modo interativo, sem rodá-lo, nomeando-o como `01container` e utilizando a imagem `alpine` na versão `3.12` | :heavy_check_mark:
2 - Inicie o container `01container` | :heavy_check_mark:
3 - Liste os containers filtrando pelo nome `01container` | :heavy_check_mark:
4 - Execute o comando `cat /etc/os-release` no container `01container` sem se acoplar a ele | :heavy_check_mark:
5 - Remova o container `01container` | :heavy_check_mark:
6 - Faça o download da imagem `nginx` com a versão `1.21.3-alpine` sem criar ou rodar um container | :heavy_check_mark:
7 - Rode um novo container com a imagem  `nginx` com a versão `1.21.3-alpine` em segundo plano nomeando-o como `02images` e mapeando sua porta padrão de acesso para porta `3000` do sistema hospedeiro | :heavy_check_mark:
8 - Pare o container `02images` que está em andamento | :heavy_check_mark:
9 - Gere uma build a partir do Dockerfile do `back-end` do `todo-app` nomeando a imagem para `todobackend` | :heavy_check_mark:
10 - Gere uma build a partir do Dockerfile do `front-end` do `todo-app` nomeando a imagem para `todofrontend` | :heavy_check_mark:
11 - Gere uma build a partir do Dockerfile dos `testes` do `todo-app` nomeando a imagem para `todotests` | :heavy_check_mark:
12 - Suba uma orquestração em segundo plano com o docker-compose de forma que `backend`, `frontend` e `tests` consigam se comunicar | :heavy_check_mark:

</details>
