# Golang GraphQL Client

Fully compatibility with <github.com/shurcooL/graphql>

You can simply replace `github.com/shurcooL/graphql` --> `github.com/Laisky/graphql` to access new features.

## New Features

### Set Headers & Cookies

```go
cli := NewClient(
    "url",
    httpClient,
    graphql.WithCookie("cookieName", "cookieVal"),
    graphql.WithHeader("headerName", "headerVal"),
)
```
