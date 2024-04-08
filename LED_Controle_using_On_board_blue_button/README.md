## **Getting started for on board LED on/off using PUSH button**

**Step 1: Setup Project in STM32CubeIDE**  
Launch STM32CubeIDE and create a new project targeting your STM32 microcontroller model.
Configure project settings including device selection, toolchain, and project location.

**Step 2: Configure Pinout in STM32CubeMX** 
Open STM32CubeMX and select your STM32 microcontroller model.
Assign GPIO pins for the on-board LED and push button.
Ensure proper pin configurations for input (push button) and output (on-board LED).

**Step 3: Generate Code** 
After configuring pinout in STM32CubeMX, click on "Project" tab and select your IDE (e.g., STM32CubeIDE).
Click "Generate Code" to generate initialization code based on your configurations.

**Step 4: Write Initialization Code**  
Open the generated project in STM32CubeIDE.
Navigate to the initialization file (e.g., main.c).
Initialize GPIO pins for the on-board LED and push button as input and output, respectively.

**Step 5: Implement Toggle Functionality**  
Write code within the main loop to continuously monitor the state of the push button.
When the push button is pressed (or released, depending on configuration), toggle the state of the on-board LED.
Use GPIO read and write operations to achieve this functionality.

**Step 6: Build and Flash the Project**  
Build the project in STM32CubeIDE to ensure there are no compilation errors.
Connect the STM32 development board to your computer via USB.
Flash the compiled code onto the microcontroller using appropriate flashing tools (e.g., ST-Link).

**Step 7: Test the Application**  
Disconnect the development board from the computer and power it using an external power source if necessary.
Press the push button and observe the behavior of the on-board LED. It should toggle on and off with each press of the button.

**Conclusion:**  
This guide provides a systematic approach to toggle the on-board LED of an STM32 microcontroller using a push button. By following these steps, developers can gain practical experience in configuring GPIO pins, handling interrupts, and implementing basic input/output operations on STM32 microcontrollers. This foundational knowledge can be further expanded upon to create more sophisticated embedded systems and applications.
