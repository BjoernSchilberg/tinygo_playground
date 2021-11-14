# TinyGo playground for the Circuit Playground Express

## Getting started 

- https://tinygo.org/getting-started/linux/
- https://play.tinygo.org/
- TinyGo + Vim + gopls https://dev.to/sago35/tinygo-vim-gopls-48h1
- https://github.com/sago35/tinygo-workshop


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
- https://www.adafruit.com/product/3333
- https://learn.adafruit.com/adafruit-circuit-playground-express/guided-tour
- https://godoc.org/github.com/tinygo-org/tinygo
- https://godoc.org/tinygo.org/x/drivers/ws2812
- https://godoc.org/tinygo.org/x/drivers/lis3dh
- https://godoc.org/tinygo.org/x/drivers/thermistor
- https://tinygo.org/microcontrollers/drivers/ (Link list to datasheets)

## Circuit Playground Express


- 10 x Mini NeoPixel LEDs, each one can display any rainbow color
- 1 x Motion Sensor (LIS3DH 3-Axis XYZ Accelerometer), with Tap and Free-Fall Detection)
- 1 x Temperature Sensor (MMBT2222)
- 1 x Light Sensor (ALSPT1931), can also act as a Color or Pulse Sensor)
- 1 x Sound sensor (MEMS Microphone)
- Infrared Transmitter and Receiver (DSOP38338), can transmit and receive remote control codes, send messages between Circuit Playground Expresses, or act as a Proximity Sensor.
- 1 x Mini speaker with class D amplifier (7.5mm magnetic speaker/buzzer)
- 2 x Push buttons, left and right
- 1 x Slide switch
- 8 x Alligator-clip friendly input/output pins (Includes I2C, UART, 8 pins that can do analog inputs/multiple PWM output
- 7 pads can act as Capacitive Touch inputs, remaining pad is a true analog output
- Green "ON" LED 
- Red "#13" LED for basic blinking
- Reset button

Source: https://www.mouser.de/new/adafruit/adafruit-circuit-playground-express/
