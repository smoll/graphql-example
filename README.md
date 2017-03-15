# graphql-example

## dev

### start server

```
yarn
PORT=3001 yarn start
```

and enter GraphQL query into [http://localhost:3001/graphiql](http://localhost:3001/graphiql), e.g.

```
query {
  posts {
    title
    name
    content
  }
}
```

### start React client dev server

```
cd app
yarn
yarn start
```
