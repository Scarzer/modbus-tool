# Modbus Tools

A small collection of tools to work with the modbus protocol from the command line.

## Installation

A simple `npm -g modbus-tool` should do the trick.

## General usage

Type `modbus-tool --help` for the help message.

## Examples

Poll coils with `modbus-tool -h someHost -p somePort readcoils 0 10`. This way you poll the first 10 bool values.

Poll word register with `modbus-tool -h someHost -p somePort readregisters 0 10`. This way you poll the first 10 word values.

Write a single coil with `modbus-tool -h someHost -p somePort writesinglecoil 10 true`. This way you write true to register 10.

Write a single register with `modbus-tool -h someHost -p somePort writesingleregister 20 1234`. This way you write value 1234 to register 20.

## License

Copyright (C) 2012 Stefan Poeter (Stefan.Poeter[at]cloud-automation.de)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
