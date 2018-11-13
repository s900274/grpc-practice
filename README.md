# grpc-practice

## Requirements

Use Go 1.11 with Gomodule

## Get started

```go
$ export GO111MODULE

$ ./bin/protoc --go_out=plugins=grpc:. *.proto

$ make

$ ./bin/grpc-server

$ ./bin/grpc-client
```