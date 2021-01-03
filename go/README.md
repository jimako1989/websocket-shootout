# Go
As this mentioned [this post](https://www.reddit.com/r/golang/comments/gjjb9e/are_there_any_benchmark_results_available_for/), there are some websocket libraries for Go as of Jan. 2021.

 1. [x/net/websocket](golang.org/x/net/websocket)
 1. [Gorilla Websocket](https://github.com/gorilla/websocket/)
 1. [Gobwas Websocket](https://github.com/gobwas/ws)
 1. [go-socket-io](https://github.com/googollee/go-socket.io)
 1. [nhooyr/websocket](https://github.com/nhooyr/websocket)

## Dependencies

* Go 1.15

~~All other dependencies are vendored in the project GOPATH with git submodules.~~
To apply Go Modules adopted after Go 1.11, vendored directories were discarded.

## Building the server

From the top-level project directory:

```
make
```

## Websocket Server

The websocket server is located in `./bin/go-websocket-server`.

To run the go Server

```
bin/go-websocket-server -address REPLACEME -port 3334
```
