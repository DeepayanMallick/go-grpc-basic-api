# go grpc basic api

### In this project I build a basic API using gRPC and protobufs in Go

# Generate proto file
-----------------------
```
protoc --go_out=. --go_opt=paths=source_relative \
    --go-grpc_out=. --go-grpc_opt=paths=source_relative \
    proto/service.proto
```