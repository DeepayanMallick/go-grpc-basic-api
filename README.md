# go grpc basic api

### In this project I build a basic API using gRPC and protobufs in Go

-----------------------
## Run this command to generate proto file
```
protoc --go_out=. --go_opt=paths=source_relative \
    --go-grpc_out=. --go-grpc_opt=paths=source_relative \
    proto/service.proto
```