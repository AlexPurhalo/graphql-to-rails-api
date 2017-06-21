### Rails API + GraphQL usage tutorial

Query example
```
curl -XGET http://localhost:3000/movies -d "query={
  movie(id: 1) {
    title,
    year,
    actors {
      name
    }
  }
}"
```

[source](https://www.sitepoint.com/building-apis-ruby-rails-graphql)