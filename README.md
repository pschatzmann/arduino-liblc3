# arduino-liblc3

LC3 (Low Complexity Communication Codec) is an audio codec specified by the Bluetooth Special Interest Group (SIG) for the LE Audio audio protocol introduced in Bluetooth 5.2. It's developed by Fraunhofer IIS and Ericsson as the successor of the SBC codec.

I cloned the orignal https://github.com/zephyrproject-rtos/liblc3codec and converted it to an Arduino Library

## Installation

For Arduino, you can download the library as zip and call include Library -> zip library. Or you can git clone this project into the Arduino libraries folder e.g. with

```
cd  ~/Documents/Arduino/libraries
git clone pschatzmann/arduino-liblc3.git
```
This has the advantage that you can easily get the latest code updates by just executing the command ```git pull```

## Documentation

I recommend to use this library together with my [Arduino Audio Tools](https://github.com/pschatzmann/arduino-audio-tools). 
This is just one of many __codecs__ that I have collected so far: Further details can be found in the [Encoding and Decoding Wiki](https://github.com/pschatzmann/arduino-audio-tools/wiki/Encoding-and-Decoding-of-Audio) of the Audio Tools.


