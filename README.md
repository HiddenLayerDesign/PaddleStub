# Paddle-of-Theseus
This Repository holds the "stub-client" submodule for the [Paddle-of-Theseus](), which allows a developer to work on the [PaddleClient](https://github.com/HiddenLayerDesign/PaddleClient)
Please take a look at [the Wiki](https://github.com/HiddenLayerDesign/Paddle-of-Theseus/wiki) for in-depth information.

**For now only development on Windows is supported via this repository. Development work on other platforms will require a properly programmed Teensy board to be connected over Serial.**

## Author
[Chase E Stewart](https://chasestewart.co) for [Hidden Layer Design](https://hiddenlayerdesign.com)

## Features
This program allows for development of the more-complex PaddleClient application without needing to keep the hardware connected.
This is done by emulating the EEPROM configuration and serial messaging of the physical Teensy Board that is connected to the Client application over Serial port.

### Software Requirements
You will need the following:
- Python 3.x
- A Null-modem Emulator, such as [com0com Null-modem emulator](https://com0com.sourceforge.net/) on Windows

## Getting Started
- Download a null-modem emulator and set it up to run as a background service
- Run this application

## Links
- Personal Website: https://chasestewart.co/
- Hidden Layer Design Website: https://HiddenLayerDesign.com
- Repository: https://github.com/ChaseStewart/Paddle-of-Theseus/

## License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
