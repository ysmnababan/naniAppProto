# naniAppProto
shared proto for naniApp application

How to compile:
1. User Service
protoc --go_out=. --go-grpc_out=require_unimplemented_servers=false:. .\proto\user_service.proto