# **GETTING_STARTED_WITH_SETUP_OF_STM32_CUBE_IDE**
The STM32 microcontroller series by STMicroelectronics is widely used in embedded systems and IoT projects due to its versatility and performance.
Whether you're a beginner or an experienced developer, getting started with STM32 development can be an exciting journey into the world of embedded systems.
In this guide, we'll walk through the essential steps to kickstart your STM32 development journey.


### **Here are step-by-step instructions for installing STM32Cube IDE:**

**1.Download STM32Cube IDE:**
Go to the official STMicroelectronics website.
Navigate to the STM32Cube IDE download page.
Choose the version suitable for your operating system (Windows, Linux, or macOS).
Click on the download link to start the download.

**2.Run the Installer:**
Once the download is complete, locate the installer file on your computer.
Double-click the installer executable file to launch the installation wizard.


**3.Accept License Agreement:**
Read through the license agreement presented by the installation wizard.
If you agree to the terms, select the option to accept the license agreement.

**4.Choose Installation Directory:**
Select the directory where you want to install STM32Cube IDE.
You can choose the default directory or specify a custom location.

**5.Select Components (Optional):**
The installation wizard may provide options to select additional components to install, such as device support packs or example projects.
Choose the components you want to install based on your requirements.

**6.Configure Start Menu Entries (Optional):**
The installation wizard may offer options to create shortcuts in the Start menu or desktop.
Configure these options according to your preferences.

**7.Wait for Installation to Complete:**
Once you have configured the installation settings, click on the "Install" or "Next" button to start the installation process.
The installation progress will be displayed by the wizard. Wait for the installation to complete.

**8.Launch STM32Cube IDE:**
Once the installation is finished, you can launch STM32Cube IDE.
You can do this by clicking on the desktop shortcut (if created), searching for STM32Cube IDE in the Start menu (Windows), or navigating to the installation directory and running the IDE executable file.

**9.Set up STM32CubeMX (Optional):**
STM32Cube IDE integrates with STM32CubeMX, a graphical tool for configuring STM32 microcontroller peripherals.
If you plan to use STM32CubeMX, you can download and install it separately from the STMicroelectronics website.

**10.Check for Updates (Optional):**
After launching STM32Cube IDE, you may want to check for updates by accessing the Help menu and selecting "Check for Updates."

**11.Start Using STM32Cube IDE:**
Congratulations! You're now ready to start using STM32Cube IDE for developing applications for STM32 microcontrollers.
You can create new projects, import existing projects, configure peripherals, write code, build, debug, and flash firmware to your STM32 microcontroller.

By following these steps, you should be able to successfully install STM32Cube IDE on your computer and begin your development journey with STM32 microcontrollers.


## **Start up guide for ON BOARD LED CONTROL** 

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
