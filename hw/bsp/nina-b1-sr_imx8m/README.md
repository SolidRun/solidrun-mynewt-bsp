### SolidRun BSP for NINA-B1 module on iMX8MQ SOM 

This is the BSP you need in order to build and debug mynewt bootloader and applications for the NINA-B1 module integrated onto SolidRun iMX8MQ based SOM.  It uses OpenOCD as the debugger connecting over the SWD pins of the NINA-B1 module.  *note that the SWD and SWCLK pins are brought out to the carrier board so it is up to the board designer to connect these pins to SOC GPIOs.  The pin definitions in this BSP default to those configured for the HummingBoard Pulse*

### Requirements

* Newt - This will need to be installed from source on the device. https://mynewt.apache.org/latest/newt/install/newt_linux.html  
* OpenOCD - For now you will need to install our patched version of OpenOCD following the instructions here.  https://developer.solid-run.com/knowledge-base/building-openocd-for-i-mx-platforms/ 
* arm-none-eabi - This is detailed in the mynewt linux setup, but I wanted to make it clear that both the compiler and gdb need to be installed.

### Setup

Todo

### Build
### Debug
