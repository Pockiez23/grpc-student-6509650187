Run the following command to generate the Go code from the proto file:
```bash
protoc --go_out=. --go-grpc_out=. proto/student.proto
```
Run server terminal1:
```bash
go mod tidy // to update go.mod
go run server/server.go // to run server
```
Server will run on:
`localhost:50051`

Run client terminal2:
```bash
go run client/client.go
```
