### Install dependeice

```
$ glide install
```

### Running

Buld and run the server.

```
$ go build -o server && ./server
```

Open client/index.html in your browser.



### Port

Modify 'err := http.ListenAndServe(":8000", nil)' in main.go to change the port of the server.


The index.html use 'let socket = new WebSocket("ws://localhost:8000/ws");' to access the websocket.

