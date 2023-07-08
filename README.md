# Simple RESTful CRUD

A very basic CRUD using Gin (web framework) and GORM (ORM Library) to manage "Posts".

Used tutorial: [Creating a JSON CRUD API in Go (Gin/GORM)](https://www.youtube.com/watch?v=lf_kiH_NPvM) by [ Coding with Robby](https://www.youtube.com/@codingwithrobby)

## Routes created

| Route | Method | Description | Expected Status |
|--|:--:|:--:|:--:|
| /posts | POST | Create a Post| 200 |
| /posts | GET | Retrieve a list of Posts| 200 |
| /posts/:id | GET | Retrieve a single Post| 200 |
| /posts/:id | PUT | Update a Post| 200 |
| /posts/:id | DELETE | Delete a Post| 204 |

----
## Necessary Environment Variables

PORT=3000
DB_URL="host=localhost user=dbuser password=dbpassword dbname=gorm port=9920 sslmode=disable"

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