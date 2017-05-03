# Arduino_MCP23S17_utils

Wrapper to access to most common ardunio sensors connecting them direclty to the arduino boards or using a MCP23S17


## Available sensors
- [x] DHT11 (**not working through the MCP23S17**, this sensor needs high frequency and it is recommended to connect it directly to the board)


## Base libaries
This arduinio library includes some changes to already existing libraries in order to work both through the MCP23S17 or direclty to the arduino board. Above are listed the original libraries repositories:
* [DHT11](https://github.com/winlinvip/SimpleDHT/)


## Developing
This library includes a CMakeLists just to import the library to a c++ supported IDE. You will not be able to compile the library using this file. 
