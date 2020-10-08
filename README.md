# docker_grpc_chat_tutorial
Docker Build Command used :- docker build --tag=docker_example .
Run Command := docker run -it -p 8080:8080 docker_example
Protocol Buffer Command :- protoc --proto_path=proto --proto_path=third_party --go_out=plugins=grpc:proto service.proto