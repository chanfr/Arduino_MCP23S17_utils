 cmake_minimum_required(VERSION 2.8)


 include_directories(/home/frivas/devel/arduino/arduino-1.8.2/hardware/arduino/avr/cores/arduino/
         /home/frivas/devel/arduino/arduino-1.8.2/hardware/arduino/avr/libraries/SPI/src
         /home/frivas/devel/arduino/arduino-1.8.2/hardware/tools/avr/avr/include/
         /home/frivas/devel/arduino/arduino-1.8.2/hardware/arduino/avr/variants/micro/
         )

add_library( test
	MCP23S17
        SimpleDHT
)
