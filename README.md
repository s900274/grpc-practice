# grpc-practice

## Requirements

OS Version : MacOS

Go Version : 1.11 (with GoModule)

## Get started

```go
$ export GO111MODULE

$ ./bin/protoc --go_out=plugins=grpc:. *.proto

$ make

$ ./bin/grpc-server

$ ./bin/grpc-client
```