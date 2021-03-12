<h1 align="center">API de gestão de projeto com Nodejs</h1>

## Rotas

```
GET http://localhost:3333/projects
```

```
GET http://localhost:3333/projects?title=Node
```

```
POST http://localhost:3333/projects
Body Params
{
  "title": "Gerenciador de projetos com NodeJS",
  "owner": "matheus"
}
```

```
PUT http://localhost:3333/projects/:id
Body Params
{
  "title": "Gerenciador de projetos com ReactJS",
  "owner": "matheus"
}
```

```
DELETE http://localhost:3333/projects/:id
```


