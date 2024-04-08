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

**Results:**  
After flashing the program onto the STM32 microcontroller, the on-board LED began blinking at the specified interval. The blinking pattern demonstrated the successful control of GPIO pins through software.

**Conclusion:**  
The development of a simple LED blinking program on an STM32 microcontroller provides a foundational understanding of GPIO control and basic software development for embedded systems. This project serves as an excellent starting point for beginners entering the world of STM32 development. Further exploration can involve more complex applications and interactions with additional peripherals and communication interfaces.
