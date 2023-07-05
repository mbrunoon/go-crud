# Simple RESTful CRUD

A very basic CRUD using Gin (web framework) and GORM (ORM Library) to manage "Posts".

Used tutorial: [Creating a JSON CRUD API in Go (Gin/GORM)](https://www.youtube.com/watch?v=lf_kiH_NPvM) by [ Coding with Robby](https://www.youtube.com/@codingwithrobby)

## Routes created

| Method | Route | Description | Expected Status |
|--|--|--|--|
| POST | /posts | Create a Post| 200 |
| GET | /posts | Retrieve a list of Posts| 200 |
| GET | /posts/:id | Retrieve a single Post| 200 |
| PUT | /posts/:id | Update a Post| 200 |
| DELETE | /posts/:id | Delete a Post| 204 |

------
## Libraries and Tools

### [**Compile Daemon**](https://github.com/githubnemo/CompileDaemon)
Watches your .go files in a directory and invokes go build if a file changed.

```
CompileDaemon -command="./crud"
```

This keep the build updated and run the application as well

### [**Gin-Tonic**](https://gin-gonic.com/)

Gin is a web framework written in Go (Golang).

### [**GORM**](https://gorm.io/)

ORM library for Golang aims to be developer friendly.

### [**Elephant SQL**](https://www.elephantsql.com/)

PostgreSQL as a service