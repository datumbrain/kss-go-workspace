# go-workspace

**golang-1.18** _multi-module workspaces_

Make sure that you’ve installed `Go` at `Go 1.18` or later using the links at [go.dev/dl.](https://go.dev/dl/)

```shell
$ go version
go version go1.18 darwin/arm64
```

## Project structure

```
.
├── README.md
├── worspace
    ├── app1
    │   ├── go.mod
    │   └── main.go
    └── app2
        ├── go.mod
        └── main.go
    ├── go.work
```

## Reference

For understanding of `go workspace` read the below mentioned blog.

[Go Workspace](https://blog.datumbrain.com/2022/05/25/go-workspace.html)
