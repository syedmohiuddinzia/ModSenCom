# ModSenCom
This repository is added to provide simple code for Arduino Modbus communication.

## Instructions
1. Clone the repository.
2. Extract ![LIB/ModbusRTUSlave.zip](https://github.com/syedmohiuddinzia/ModSenCom/blob/main/LIB/ModbusRTUSlave.zip} in Arduino Library folder.
3. Connect Arduino hardware using serial port and dpload ![ModbusSlaveRTU.ino](https://github.com/syedmohiuddinzia/ModSenCom/blob/main/ModbusSlaveRTU.ino).
4. Extract ![ModbusClientX.zip](https://github.com/syedmohiuddinzia/ModSenCom/blob/main/ModbusClientX.zip) and run ***ModbusClientX.exe*** in release directory.
5. Connect RS485 Sensor using RS485 to UART module as shown in the image below such that A -> A, B -> B, RX -> 3, TX -> 4, VCC -> 5V and GND -> GND.
6. Connect Modbus RTU with the RS485 Port and Sensor Baudrate *i.e. 9600*.
7. On next window of Modbus Client, change # of addresses to *4*, click on *Read from 0 to 3* and keep in mind that Slave Address *1* is slected.
8. Now data on specific holding registers can be read.
9. To write data on specific holding registers, double click and write a new value and then press enter.
