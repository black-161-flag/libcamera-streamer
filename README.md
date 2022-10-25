# libcamera-streamer
simple streaming server 

## prerequisites
Because the version delivered by apt is to old, please follow the instructions for [installing picamera2 via pip](https://github.com/raspberrypi/picamera2#installation-using-pip) from the [official repository](https://github.com/raspberrypi/picamera2).

## usage
python3 streamer.py

```
optional arguments:
  -h, --help         show this help message and exit
  --hflip HFLIP      rotate hflip (default: 0)
  --vflip VFLIP      rotate vflip (default: 0)
  --width WIDTH      width of the video (default: 1280)
  --height HEIGHT    height of the video (default: 720)
  --address ADDRESS  bind address (default: localhost)
  --port PORT        bind port (default: 8000)
```
