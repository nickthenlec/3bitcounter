# 3bitcounter
3 bit binary/decimal counter PCB project

This is a simple through-hole soldering project, perfect for
- soldering practice
- teaching electronics
- introductory computer concepts for home or classroom
- learning binary counting
- building a fun, DIY, desk gadget

Please see the [Bill of Materials](https://github.com/nickthenlec/3bitcounter/blob/main/3bitcounter_1_2_bom.html) for components needed to assemble the project.  The project requires a 5V power source.
Optionally, sockets may be used when installing ICs.

How it works:
- the 555 timer IC controls the rate of adding the bits
- the 74HC393 is a binary adder, in this project it will cycle back to 0 after the number 111 (Binary), it displays the bit values on the 3 LEDs
- the CD4511 chip takes the 3 bit binary number and displays it as a decimal number on the 7-segment LED
- when running, the display will cycle continuously from 0-7 in Binary and Decimal

The PCB can be created using the [zip file](https://github.com/nickthenlec/3bitcounter/blob/main/3bitcounter_1_2_.zip).  We recommend using PCBWay if you would like to support the project.
<a href="https://www.pcbway.com/project/shareproject/3_bit_Binary_Decimal_Counter_dd6c4679.html"><img src="https://www.pcbway.com/project/img/images/frompcbway-1220.png" alt="PCB from PCBWay" /></a>

PCB and components
https://github.com/nickthenlec/3bitcounter/blob/main/3bitcounter_1_2_pcb_and_components.jpg

Working project after assembly
https://github.com/nickthenlec/3bitcounter/blob/main/3bitcounter_1_2.mp4

[NE555 Data Sheet](https://www.ti.com/lit/ds/symlink/ne555.pdf?ts=1783609782901&ref_url=https%253A%252F%252Fwww.ti.com%252Fproduct%252FNE555)

[74HC393 Data Sheet](https://www.ti.com/lit/ds/symlink/sn74hc393.pdf?ts=1783559986246)

[CD4511 Data Sheet](https://www.ti.com/lit/ds/symlink/cd4511b.pdf)
