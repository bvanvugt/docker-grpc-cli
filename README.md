# docker-grpc-cli
docker-grpc-cli

### Usage
```sh
docker run -it --rm \
    -v "$PWD"/proto:/usr/src \
    -w /usr/src \
    bvanvugt/grpc-cli \
    grpc_cli call IP:PORT call API.proto "name: 'test'"
```
