To start, make sure you have Go installed and set up. Then install libp2p and some other deps we need with:
```shell
go get -u github.com/libp2p/go-libp2p
go get -u github.com/libp2p/go-floodsub
go get -u github.com/libp2p/go-libp2p-kad-dht
```

And with that, you have a simple chat app! Build it with:
```shell
go build -o libp2p-demo main.go
```

And then run it:
```shell
./libp2p-demo
```
