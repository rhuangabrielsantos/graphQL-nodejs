# Querys

Run ``yarn install`` to install dependencies and open ``http://localhost:3000/graphql``

## create user

```
mutation {
  createUser(
    name: "Rhuan",
    repo: "https://github.com/rhuangabrielsantos",
    age: 23
  ) {
    id
  }
}
```

## get users

```
{
  users {
    id,
    name,
    repo
  }
}
```