# graphql-example

## dev

start server

```
yarn
PORT=3001 yarn start
```

and enter graphQL query into [http://localhost:3001/graphiql](http://localhost:3001/graphiql), e.g.

```
query {
  posts {
    title
    name
    content
  }
}
```
