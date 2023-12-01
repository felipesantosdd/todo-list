# WebTaskManager

## Descrição

O WebTaskManager é uma aplicação de gerenciamento de tarefas com um front-end em React (todo_list_front) e um back-end em Node.js (todo_list_back).

## Requisitos

- Docker
- Docker Compose

## Como Usar

Video de apresentação: https://www.youtube.com/watch?v=fYUX1KS5F_c

### Clonando os Repositórios

Cada Repositorio tem seu proprio Readme, com instrucoes sobre o projeto.

Repositorio back-end: https://github.com/felipesantosdd/todo_list_back

Repositorio Front-end: https://github.com/felipesantosdd/todo_list_front

Clone os três repositórios na mesma pasta:

```bash
git clone https://github.com/felipesantosdd/todo-list.git
cd todo-list
git clone https://github.com/felipesantosdd/todo_list_front.git
git clone https://github.com/felipesantosdd/todo_list_back.git
```

### Iniciando os **Contêineres**

Navegue até a pasta 'docker':

```bash
cd docker
```

Na pasta 'docker', execute o comando:

```bash
docker-compose up
```

Isso iniciará os contêineres em segundo plano. Aguarde a mensagem informando que a API está rodando na porta 3001.

### Acessando a Aplicação

Abra o seu navegador e acesse `http://localhost:3000` para começar a usar a aplicação.

## Variáveis de Ambiente

todas as variaveis de ambiente nescessarias ja stao setadas no .env dentro do repositorio backend.
