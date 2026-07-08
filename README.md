# 3bitcounter
3 bit binary/decimal counter PCB project

This is a simple through-hole soldering project, perfect for
- soldering practice
- teaching electronics
- introductory computer concepts for home or classroom
- learning binary counting
- building a fun, DIY, desk gadget

Please see the [Bill of Materials](https://github.com/nickthenlec/3bitcounter/blob/main/3bitcounter_1_2_bom.html) for components needed to assemple the project.  The project requires a 5V power source.
Optionally, sockets may be used when installing IC.

How it works:
- the 555 timer IC controls the rate of adding the bits
- the 74HC393 is a binary adder, in this project it will cycle back to 0 after the number 111 (Binary), it displays the bit values on the 3 LEDs
- the CD4511 chip takes the 3 bit binary number and displays it as a decimal number on the 7-segment LED
- when running, the display will cycle continuously from 0-7 in Binary and Decimal

The PCB can be created using the [zip file](https://github.com/nickthenlec/3bitcounter/blob/main/3bitcounter_1_2_.zip).  We recommend using the link at PCBWay if you would like to support the project.
