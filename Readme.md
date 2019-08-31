
<p  align="center">

<a  href="https://nodejs.org/en/" target="_blank">

<img  width="160px"  src="https://i.imgur.com/6syIF0C.png"><br/>

</a>

<h2  align="center">Conceitos de Node.js</h2>

</p>

---

  

> **GoStack 8.0**: Aplicação desenvolvida com base nos estudos adquiridos no Bootcamp GoStack 8.0. Essa aplicação será utilizada para armazenar projetos e suas tarefas.
> 
---

  

# Desafio 01. 

```

Crie uma aplicação do zero utilizando Express.

  

Essa aplicação será utilizada para armazenar projetos e suas tarefas.

```
## Rotas

- `POST /projects`: A rota deve receber `id` e `title` dentro corpo de cadastrar um novo projeto dentro de um array no seguinte formato: `{ id: "1", title: 'Novo projeto', tasks: [] }`; 

- `GET /projects`: Rota que lista todos projetos e suas tarefas;

- `PUT /projects/:id`: A rota deve alterar apenas o título do projeto com o `id` presente nos parâmetros da rota;

- `DELETE /projects/:id`: A rota deve deletar o projeto com o `id` presente nos parâmetros da rota;

- `POST /projects/:id/tasks`: A rota deve receber um campo `title` e armazenar uma nova tarefa no array de tarefas de um projeto específico escolhido através do `id` presente nos parâmetros da rota;


## Middlewares

- Middleware será utilizado em todas rotas que recebem o ID do projeto nos parâmetros da URL que verifica se o projeto com aquele ID existe.

- Middleware global chamado em todas requisições que imprime (`console.log`) uma contagem de quantas requisições foram feitas na aplicação até então;
  

### Topics

  

* Routes (Express Router) :heavy_check_mark:

* Create Project :heavy_check_mark:

* List Projects (Single and Multiples) :heavy_check_mark:

* Update Projects :heavy_check_mark:

* Delete Projects :heavy_check_mark:

* Middlewares :heavy_check_mark:

* Nodemon package usage :heavy_check_mark:

  
  

#### Keep in mind this is a WIP.

  
- Aplicação em NodeJS para estudos.

- Link para o desafio do curso referente a essa aplicação: <https://github.com/Rocketseat/bootcamp-gostack-desafio-01>