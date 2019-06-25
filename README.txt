go get -d github.com/tinygo-org/tinygo
#dep ensure
tinygo build -o=flash.uf2 -target=circuitplay-express main.go
