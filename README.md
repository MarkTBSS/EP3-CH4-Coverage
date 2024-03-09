```
go test .
go test ./...
go test -v .
go test -run TestName .

go test -cover
go test -cover -coverprofile=c.out
go tool cover -html=c.out -o coverage.html
```