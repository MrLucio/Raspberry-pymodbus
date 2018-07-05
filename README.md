# Raspberry_pymodbus
Raspberry_pymodbus is a simple repository that implements [pymodbus](https://github.com/riptideio/pymodbus) to create a basic Server-Client tcp connection with the modbus protocol.

## Description of the Modbus protocol
The Modbus tcp protocol communicates inside the tcp/ip stack. Inside the network we can find a Server and one or more Clients.
Data gathered from the sensors is usually stored on the Client side: it gets sent, trough the TCP/IP stack, to the Server register chosen by the Client, where it will be stored. This data will be available to both parties.

## Requirements
> - Python 2.7 version or newer (3.x versions included)
> - [pymodbus repository](https://github.com/riptideio/pymodbus)
##### Default Python libraries
> - Keyboard
> - Logging
---
**Made by Andrioaia Ovidiu and Mateias Luciano**
