<h1 align="center">
<a href="https://developer.mozilla.org/pt-BR/docs/Glossary/CRUD"> <i>CRUD</i> </a> <br>
</h1>
<p align="center"> projeto desenvolvido para um crud feito em typescript com typeorm, express e postgresql </p>

<h3 align="center">
<img src="https://img.shields.io/static/v1?label=NodeJS&message=Backend&color=339933&style=for-the-badge&logo=Node.js"/> 
<img src="https://img.shields.io/static/v1?label=Express&message=Framework&color=000000&style=for-the-badge&logo=Express"/> <br>

<img src="https://img.shields.io/static/v1?label=TypeScript&message=LANGUAGE&color=3178C6&style=for-the-badge&logo=TypeScript"/> 
<img src="https://img.shields.io/static/v1?label=PostgreSQL&message=DB&color=4169E1&style=for-the-badge&logo=PostgreSQL"/>
<img src="https://img.shields.io/static/v1?label=VSCode&message=IDE&color=007ACC&style=for-the-badge&logo=Visual Studio Code"/>
</h3>

---

<p align="center">
 <a href="#-o-que-é">O que é ?</a> | 
 <a href="#-projeto">Projeto</a> |
 <a href="#-exemplos">Exemplos</a> |
 <a href="#-pré-requisitos">Pré-Requisitos</a> |
 <a href="#-rodando-o-projeto">Rodando o Projeto</a> |
 <a href="#-tecnologias">Tecnologias</a> |
 <a href="#-aluno">Aluno</a> 
</p>

# ❓ O que é ?

CRUD (Create, Read, Update, Delete) é um acrônimo para as maneiras de se operar em informação armazenada. É um mnemônico para as quatro operações básicas de armazenamento persistente. CRUD tipicamente refere-se a operações perfomadas em um banco de dados ou base de dados, mas também pode aplicar-se para funções de alto nível de uma aplicação, como exclusões reversíveis, onde a informação não é realmente deletada, mas é marcada como deletada via status.

C: Create – Criar um novo registro.

R: Read – Ler um registro, ou um conjunto de registros.

U: Update – Atualizar um registro.

D: Delete – Excluir um registro.

# 🖥️ Projeto

Como forma de adquirir conhecimento, este projeto é um cadastro de categorias e filmes.

Consiste-se em uma aplicação utilizando várias tecnologias, onde é possível cadastrar a categoria e a descrição de um filme, e, um próprio filme com duração e o tipo de categoria do mesmo.

# ✨ Exemplos

```bash
# Exemplo de um cadastro de categoria
{
  "name": "drama",
  "description": "filmes tristes",
}

# Exemplo de uma categoria cadastrada
{
  "id": "a6e0444b-b4a2-4eda-9309-72e21c8d05b3",
  "name": "drama",
  "description": "filmes tristes",
  "created_at": "2022-02-07T16:10:18.937Z"
}
```

```bash
# Exemplo de um cadastro de um filme
{
  "name": "minha mãe é uma peça",
  "description": "filme de comédia muito bom",
  "category_id": "079f3f97-fcbf-4cc6-a443-524772177a7e",
  "duration": 120
}

# Exemplo de um filme cadastrado
{
  "id": "0f3f5265-4e28-43c4-af0d-8521cc8238f3",
  "name": "minha mãe é uma peça",
  "description": "filme de comédia muito bom",
  "duration": "120",
  "category_id": "079f3f97-fcbf-4cc6-a443-524772177a7e",
  "created_at": "2022-02-07T16:22:47.480Z",
  "category": {
    "id": "079f3f97-fcbf-4cc6-a443-524772177a7e",
    "name": "comédia",
    "description": "filmes alegres",
    "created_at": "2022-02-07T15:52:12.109Z"
  }
	}
```

# 🎲 Pré-Requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com) e [Node.js](https://nodejs.org/pt-br/).
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

# 🎮 Rodando o Projeto

```bash
# Clone este repositório
$ git clone https://github.com/GabrielMarioto/typescript-crud.git

# Acesse a pasta do projeto no terminal
$ cd crud-node

# Instale as dependências
$ yarn

# Execute a aplicação em modo de desenvolvimento
$ yarn dev
```

# 🛠️ Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [NodeJs](https://nodejs.org/pt-br/)
- [Express](https://expressjs.com/pt-br/)
- [Eslint](https://eslint.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [PostgreSQL](https://www.postgresql.org/)
- [TypeORM](https://typeorm.io/#/)
- [Commit Lint](https://github.com/conventional-changelog/commitlint)

# 🙍 Autor

<h1 align="center">
<a href="https://www.linkedin.com/in/gabriel-marioto/">
 <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/50884596?v=4" width="100px;" alt=""/>
 <br/><br/>
 
[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://facebook.com/gabrielmarioto)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/gabrielmarioto_)
[![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gabriel-marioto/)

</h1>
