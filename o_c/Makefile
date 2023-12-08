.PHONY: clean all

all:
	arduino-cli compile --fqbn teensy:avr:teensy31 --board-options opt=osstd,speed=120,usb=serialmidi --output-dir=./build

clean:
	rm -f build/*

upload:
	arduino-cli upload -b teensy:avr:teensy31 -p usb:1132000

