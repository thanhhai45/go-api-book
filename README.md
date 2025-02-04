# Project infomation
- Using golang
- Using gin framework
- Basic API

# Route
| method | endpoint   | detail                  | script test                                                                                                   |
|--------|------------|-------------------------|---------------------------------------------------------------------------------------------------------------|
| GET    | /books     | Get all books           | curl localhost:8080/books                                                                                     |
| GET    | /books/:id | Get specify book        | curl localhost:8080/books/1                                                                                   |
| POST   | /books     | Create new book         | curl localhost:8080/books --include --header "Content-Type: application/json" -d @body.json --request "POST"  |
| PATCH  | /checkout  | Decrement book quantity | curl localhost:8080/checkout                                                                                  |
| PATCH  | /return    | Increment book quantity | curl localhost:8080/return                                                                                    |


# Run project

```go
go run main.go
```
