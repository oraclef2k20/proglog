```
mkdir proglog
cd !$
go mod init github.com/hacker65536/$(basename $(pwd))
```


```
brew install protobuf
brew install protoc-gen-go
```

```console
$ protoc --version                                                              
libprotoc 3.21.6
```

```console
$ protoc-gen-go --version
protoc-gen-go v1.28.1
```
