# Fast MODBUS CRC 16-bit Algorithm implementation
## Requirements:
Golang 1.19

References to install Golang: [here](https://go.dev/dl/)

## Compilation from source code:
```
go build <project directory>/src/modbusCRC16.go
```
modbusCRC16 binary file is created

## Running the application:
```
./modbusCRC16 <hex sequence> <number of iterations>
```

## Example workflow:
```
PS C:..\MODBUS-CRC16-Golang> go build .\src\modbusCRC16.go
PS C:..\MODBUS-CRC16-Golang> .\modbusCRC16.exe 011000110003061AC4BAD0 1000000
Obliczona suma kontrolna CRC: 0x677F
Łączny czas realizacji: 21ms
```
