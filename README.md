# docker-protoc
Docker image with Microsoft FXC shader compiler

Hub: https://hub.docker.com/r/gwihlidal/fxc/

## Usage
```
$ docker run --rm gwihlidal/fxc /help
```

```
$ docker run --rm -v $(pwd):$(pwd) -w $(pwd) gwihlidal/fxc /T <target> /E <entry-point-name> <input-hlsl-file>
```