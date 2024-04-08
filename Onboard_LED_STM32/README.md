## **Start up guide for ON BOARD LED CONTROL**  
[Main Code](https://github.com/kartik2340/STM_32/blob/main/Onboard_LED_STM32/main.c)

**Configuration:**  
Using STM32CubeMX, we configured one of the GPIO pins connected to an on-board LED (e.g., Pin PC13 on Nucleo-F446RE) as an output.
We set up the clock configuration and other necessary peripherals.

**Code Generation:**  
STM32CubeMX generated initialization code based on our configuration, including system initialization and GPIO initialization.
The generated code was imported into STM32CubeIDE for further development.

**Application Code:**  
We wrote the main application code to toggle the LED at a specific interval.
The code initializes the GPIO pin, sets it to output mode, and toggles its state periodically using delay functions.
Compilation:

The code was compiled using the GNU Arm Embedded Toolchain within STM32CubeIDE.

**Flashing:**  
The compiled binary was flashed onto the STM32 microcontroller using STM32CubeIDE or other programming tools like ST-Link or J-Link.
