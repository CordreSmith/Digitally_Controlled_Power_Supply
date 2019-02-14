My Final Year Project was the development of a Digitally Controlled Bench Top Variable Power Supply.

I had to design the Power Supply circuit, do the prototype and testing, layout the PCB, assemble the PCB, design and develop the User Interface, design and develop the controlling software and assemble the final product. 

I developed the User Interface on a 4.3-inch TFT LCD Touchscreen, by implementing TouchGFX and Visual Studios. To interface the LCD with the power supply circuit I used an STM32F7 Developer board. I developed startup and configuration code manually due to compatibility issues between TouchGFX and CubeMX, Keil UVision and Visual Studios to develop the software and MingW to flash the software to the Developer Board.  

The software boasts a Real-Time Operating System, implemented with freeRTOS. The implementation of an RTOS improved the responsiveness of the GUI and accuracy of measurements. 

The final software and report are available in this repository.
