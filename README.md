# Armago

Arma Golang Extension 64 bits

The minimal requirement to build a good & nice GOLANG .dll or .so extension with ARMA3 :)

This template extension complete those jobs:
- receive ARMA input
- write it into a file into ARMA directory
- return a result to ARMA

## Requirements & Build

1- install the 64bits TDD gcc compiler on your machine
https://sourceforge.net/projects/tdm-gcc/

2- use armago_x64 as your entrie point template to develop your own extension :)

3- build your extension with this command line :
go build -o armago_x64.dll -buildmode=c-shared armago_x64.go