# Awesome AVR Microcontrollers
A curated list of awesome AVR tools, libraries, resources, and shiny things. Inspired by awesome-... stuff.

- [Awesome AVR](#awesome-avr)
	- [Boot Loader](#boot-loader)
	- [Driver](#driver)
	- [EEPROM](#eeprom)
	- [I2C](#i2c)
	- [ISP](#isp)
	- [JTAG](#jtag)
	- [Keyboard](#keyboard)
	- [LCD](#lcd)
	- [PWM](#pwm)
	- [SPI](#spi)
	- [TWI](#twi)
	- [USART](#usart)
	- [USB](#usb)
	- [Wireless](#wireless)
		- [nRF24L01](#nrf24l01)
		- [ZigBee](#zigbee)
	- [Xmega](#xmega)
	- [Miscellaneous](#miscellaneous)
- [Hardware](#hardware)
	- [Programmers](#programmers)
- [Software](#software)
	- [Compilers](#compilers)
	- [Integrated Development Environments](#integrated-development-environments)
	- [Simulators](#simulators)
- [Resources](#resources)
	- [Articles](#articles)
	- [Books](#books)
	- [Videos](#videos)
	- [Websites](#websites)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

## EEPROM
* [i2ceeprom](https://github.com/w0qs1/i2ceeprom) - A simple C library for interfacing with 24CXX series I2C EEPROMs.

## I2C

* [i2cdevlib](https://github.com/jrowberg/i2cdevlib) - I2C device library collection for AVR/Arduino or other C++-based MCUs.
* [I2C-master-lib](https://github.com/g4lvanix/I2C-master-lib) - Lightweight I2C library for 8-bit AVRs. 

## Keyboard

* [tmk_keyboard](https://github.com/tmk/tmk_keyboard) - A keyboard controller firmware for Atmel AVR USB family.
* [AVR-Keyboard](https://github.com/BathroomEpiphanies/AVR-Keyboard) - USB Keyboard firmware for Atmel AVR microcontrollers.

## SPI

* [AVRLib/SPI](http://www.tinkerer.eu/AVRLib/SPI/) - Serial Peripheral Interface.

## USB

* [v-usb](https://github.com/obdev/v-usb) - A Firmware-Only USB implementation for Atmel's AVR Microcontrollers.
* [LUFA](https://github.com/abcminiuser/lufa) - A lightweight USB Framework for AVRs.
* [libusbx](https://github.com/libusbx/libusbx) - A cross-platform user library providing access to USB devices.

## Wireless

* [rf24boot](https://github.com/nekromant/rf24boot) - nRF24L01+ bootloader for avr and other mcus.
* [libnrf24l01p](https://github.com/omriiluz/libnrf24l01p) - NRF24L01+ Transceiver library.
* [RF24Network](https://github.com/maniacbug/RF24Network) - Network Layer for nRF24L01(+) Radios.
* [nrf24L01_plus](https://github.com/kehribar/nrf24L01_plus) - Portable nrf24L01+ library with auto acknowledgement and auto retransmission support.
* [arduino-nrf24l01](https://github.com/aaronds/arduino-nrf24l01) - An Arduino port of the [nRF24L01](http://www.tinkerer.eu/AVRLib/nRF24L01) library.
* [NRF24-BTLE-Decoder](https://github.com/omriiluz/NRF24-BTLE-Decoder) - Sniff and decode NRF24L01+ and Bluetooth Low Energy using RTL-SDR.
* [AVRLib/nRF24L01](http://www.tinkerer.eu/AVRLib/nRF24L01/) - Nordic Semiconductor nRF24L01.

## Miscellaneous
*Useful libraries or tools that don't fit in the categories above or maybe just not categorised yet*

* [AVR Libc](http://www.nongnu.org/avr-libc/) - A high quality C library for use with GCC on Atmel AVR microcontrollers.
* [light_ws2812](https://github.com/cpldcpu/light_ws2812) - A lightweight library to control WS2811/WS2812 based LEDS and LED Strings for 8-Bit AVR microcontrollers.
* [avr-os](https://github.com/chrismoos/avr-os) - A multitasking OS for Arduino and AVR platforms.
* [AVR-Crypto-Lib](http://avrcryptolib.das-labor.org/) - A library providing implementations of cryptographic algorithms for the AVR 8-bit microcontroller family.
* [libemb](https://github.com/wendlers/libemb) - A collection of libraries which try to make things needed in many MCU based projects more convinient.
* [Pocket AVR Programmer](https://github.com/sparkfun/Pocket_AVR_Programmer) - Example firmware and board files for the Pocket AVR Programmer.
* [avr-tutorials](https://github.com/abcminiuser/avr-tutorials) - LaTeX typeset versions of my popular AVR Tutorials.
* [AVRliberty](https://github.com/dreamiurg/avr-liberty) - Library of routines for AVR microcontollers.
* [AVR-EAX-AES-bootloader](https://github.com/sirgal/AVR-EAX-AES-bootloader) - Bootloader for AVR microcontrollers featuring EAX mode encryption in 1024 bytes.
* [ArduinoAES256](https://github.com/qistoph/ArduinoAES256) - Ilya's byte-oriented AES-256 implementation implemented for Arduino.
* [Arduino AESLib](https://github.com/DavyLandman/AESLib) - Arduino Library for AES Encryption (source based on avr-crypto-lib).
* [avr-libs](https://github.com/supermucca/avr-libs) - Some other libraries and code examples for interfacing AVR microcontrollers with external devices

# Software
*Software for creating a development environment.*

## Compilers
*List of AVR compilers*

* [avr-gcc](https://gcc.gnu.org/wiki/avr-gcc)

## Integrated Development Environments
*List of AVR nominal IDEs.*

* [Atmel® Studio](http://www.atmel.com/tools/atmelstudio.aspx)
* [CodeVisionAVR]()

## Simulators
*List of AVR Simulators*

* [simavr](https://github.com/buserror/simavr) - A lean, mean and hackable AVR simulator for linux & OSX.

# Resources
*Various resources, such as books, websites, and articles for improving your AVR development skills and knowledge.*

## Articles
*Fantastic AVR related articles.*

## Books
*Fantastic AVR related books.*

* [Make: AVR Programming](http://littlehacks.org/AVR-Programming) - Learning to Write Software for Hardware.

## Videos
*Fantastic AVR related videos.*

## Websites
*Useful AVR related websites.*

* [AVR Freaks](http://www.avrfreaks.net/) - AVR Freaks Forum.
* [AVR Projects](http://www.avrprojects.net/) - Free projects for 8-bit atmel avr microcontrollers.
* [Arduino for Projects](http://duino4projects.com/)
* [ATmega32 AVR](http://atmega32-avr.com/)
* [PIC-Microcontroller](http://pic-microcontroller.com/)

## Persian Websites

* [avr92](http://avr92.ir/)

## Other Awesome Projects
*Collection of useful codes, snippets, ...*

* [AVR-Programming](https://github.com/hexagon5un/AVR-Programming) - Code examples for the book "Make: AVR Programming".
* [AvrProjects](https://github.com/KonstantinChizhov/AvrProjects) - Different projects and drafts for Atmel's avr controllers.
* [Tinkerer's AVRLib](http://www.tinkerer.eu/AVRLib/) - A small collection of code snippets which are often needed programming Atmel AVR-Controllers.

# Other Awesome Lists
*Other amazingly awesome lists*

* [lists](https://github.com/jnv/lists) - List of (awesome) lists curated on GitHub
* [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) - A curated list of awesome awesomeness.
* [awesome](https://github.com/sindresorhus/awesome) - A curated list of awesome lists.
* [awesome-cpp](https://github.com/fffaraz/awesome-cpp) - Awesome C/C++ frameworks, libraries, resources, and shiny things.
* [free-programming-books](https://github.com/vhf/free-programming-books) - List of Freely Available Programming Books
* [papers-we-love](https://github.com/papers-we-love/papers-we-love) - Papers from the computer science community to read and discuss.

# Contributing
Please see [CONTRIBUTING](https://github.com/fffaraz/awesome-avr/blob/master/CONTRIBUTING.md) for details.
