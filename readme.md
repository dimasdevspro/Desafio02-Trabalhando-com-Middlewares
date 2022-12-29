# Desafio 02: Trabalhando com Middlewares


Essa é uma aplicação para gerenciar tarefas (em inglês todos). Será permitida a criação de um usuário com name e username, bem como fazer o CRUD de todos:

- Criar um novo todo;
- Listar todos os todos;
- Alterar o title e deadline de um todo existente;
- Marcar um todo como feito;
- Excluir um todo;
- Tudo isso para cada usuário em específico.

## Requisitos
 -  Deve ser possível achar um usuário pelo username no header a passá-lo para o request.user
 -  Deve ser poosivel deixar criar um novo todo quando é plano free e possui menos de 10 todos
 -  Deve ser possível deixar criar infinitos novos todos quano é plano Pro
 -  Deve ser possível atualizar usuário e todo no request quando ambos existem
 -  Deve ser possível achar usuário por id como parâmetro de rota e passar isso para a request.user

## Regras de Negócio
 -  Não deve ser possível achar um usuário que não existe pelo username no header
 -  Não deve ser possível deixar criar um novo todo quando não é Pro e já tem 10 todos
 -  Não deve ser possível atualizar usuário e todo na requisição quando usuário não existe
 -  Não deve ser possivel atualizar usuário e todo na requisição quando o id da todo não é um uuid
 -  Não deve ser possível atualizar usuário e todo na requisição quando todo não existe
 -  Não deve ser possivel passar usuário para request.user quando isto não existe
 
## Executando a aplicação
Para iniciar a aplicação basta executar o comando:

```yarn dev```

## Testes unitários
Para iniciar iniciar a execução dos testes unitários basta executar o comando:

```yarn test```

## Tecnologias utilizadas 

As seguintes ferramentas foram usadas na construção do projeto:

- [VSCode](https://code.visualstudio.com/);
- [Git](https://git-scm.com);
- [Node.js](https://nodejs.org/en/).

## Aluno 

<a href="https://github.com/dimasdevspro">
 <img style="border-radius: 50%;" src="https://avatars1.githubusercontent.com/u/53888623?s=460&u=3c88fc42c7a0dc90293f9480a4288bf2f6a09396&v=4" width="100px;" alt=""/>
 <br />
 <sub><b>Dimas Alves Pereira</b></sub></a> <a href="https://github.com/dimasdevspro" title="Github"></a>


Feito com ❤️ por Dimas 👋🏽 Entre em contato!

[![Instagram Badge](https://img.shields.io/badge/-@dimasdevspro-f09433?style=flat-square&labelColor=f09433&logo=instagram&logoColor=white&link=https://www.instagram.com/dimasdevspro/)](https://www.instagram.com/dimasdevspro/) [![Linkedin Badge](https://img.shields.io/badge/-Dimas-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/dimas_apereira/)](https://www.linkedin.com/in/dimas-apereira/) 
[![Gmail Badge](https://img.shields.io/badge/-dimasdevspro@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:dimasdevspro@gmail.com)](mailto:dimasdevspro@gmail.com)


### Licença 

<img alt="APM" src="https://img.shields.io/apm/l/vim-mode">