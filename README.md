&nbsp;&nbsp;&nbsp;This project presents the ***design and implementation of a microsystem based on the Intel 8086 microprocessor*** . The system integrates EPROM and SRAM memory modules, programmable peripheral interfaces, and multiple input/output devices.
 
&nbsp;&nbsp;&nbsp;The microsystem uses:

* **Memory Storage:** 62512 SRAM circuits for data memory
* **Serial Communication:** 8251 USART for serial communication
* **Peripheral Control:** Peripheral control systems
* **User Input:** A 4x3 keypad for user input
* **Visual Output:** LEDs and 7-segment displays for visual output

&nbsp;&nbsp;&nbsp;Address, data, and control buses are used to connect all components to the 8086 microprocessor. Memory and I/O selection are performed using 74LS138 address decoders, while synchronization is achieved using a 15 MHz quartz crystal and the 8284A clock generator.

&nbsp;&nbsp;&nbsp;The project also includes assembly language routines for:

initializing the 8251 and 8255 interfaces;
serial transmission and reception;
parallel data output;
keypad scanning;
LED control;
hexadecimal character display on 7-segment displays.

&nbsp;&nbsp;&nbsp;The purpose of the project is to demonstrate the operation and interfacing capabilities of a complete 8086-based microsystem using both memory and peripheral devices.
