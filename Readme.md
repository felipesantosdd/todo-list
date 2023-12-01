# WebTaskManager

## Descrição

O WebTaskManager é uma aplicação de gerenciamento de tarefas com um front-end em React (todo_list_front) e um back-end em Node.js (todo_list_back).

## Requisitos

- Docker
- Docker Compose

## Como Usar

### Clonando os Repositórios

Clone os três repositórios na mesma pasta:

```bash
git clone https://github.com/felipesantosdd/todo_list_front.git
git clone https://github.com/felipesantosdd/todo_list_back.git
```

### Renomeando as Pastas

Renomeie as pastas para 'back' e 'front' respectivamente:

```bash
mv todo_list_back back
mv todo_list_front front
```

### Iniciando os Contêineres

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
