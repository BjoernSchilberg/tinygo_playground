# TinyGo playground

## Getting started 

- https://tinygo.org/getting-started/linux/


## Build your first TinyGo program 

```shell
source set-gopath.sh
go get -d github.com/tinygo-org/tinygo
tinygo build -o=flash.uf2 -target=circuitplay-express main.go
```

## Build your TinyGo program

```shell
source set-gopath.sh
tinygo build -o=flash.uf2 -target=circuitplay-express main.go
```

### Examples

- https://github.com/tinygo-org/drivers/tree/master/examples/ws2812
- https://github.com/tinygo-org/drivers/tree/master/examples/lis3dh
- https://github.com/tinygo-org/drivers/tree/master/examples/thermistor

## Links

- https://tinygo.org/microcontrollers/circuit-playground-express/
- https://godoc.org/github.com/tinygo-org/tinygo
- https://godoc.org/tinygo.org/x/drivers/ws2812
- https://godoc.org/tinygo.org/x/drivers/lis3dh
- https://godoc.org/tinygo.org/x/drivers/thermistor
