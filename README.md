# libcamera-streamer
simple streaming server using picamera2

## prerequisites
Because the version delivered by apt is to old, please follow the instructions for [installing picamera2 via pip](https://github.com/raspberrypi/picamera2#installation-using-pip) from the [official repository](https://github.com/raspberrypi/picamera2).

## usage
streamer.py [-h] [--hflip HFLIP] [--vflip VFLIP] [--width WIDTH] [--height HEIGHT] [--address ADDRESS] [--port PORT]

Simple video streamer.

optional arguments:
  -h, --help         show this help message and exit
  --hflip HFLIP      rotate hflip
  --vflip VFLIP      rotate vflip
  --width WIDTH      width of the video
  --height HEIGHT    height of the video
  --address ADDRESS  bind address
  --port PORT        bind port
