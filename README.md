# STM32F103C8T6 Microcontroller

The STM32F103C8T6 is a high-performance, 32-bit ARM Cortex-M3 microcontroller from STMicroelectronics.  
It is part of the STM32 family and is widely used in embedded systems, IoT devices, and various industrial applications due to its powerful features and flexibility.

## Key Features
- **Core**: ARM Cortex-M3 32-bit RISC core.
- **Clock Speed**: Up to 72 MHz.
- **Flash Memory**: 64 KB of flash memory for program storage.
- **SRAM**: 20 KB of static RAM.
- **GPIO Pins**: 37 general-purpose I/O pins.
- **Communication Interfaces**:
  - **USART**: Up to 3 universal synchronous/asynchronous receivers/transmitters.
  - **SPI**: Up to 2 Serial Peripheral Interfaces.
  - **I2C**: Up to 2 Inter-Integrated Circuit interfaces.
  - **USB**: Full-speed USB 2.0 interface.
- **Timers**:
  - **Advanced-control Timers**: 1 x 16-bit.
  - **General-purpose Timers**: 3 x 16-bit.
  - **SysTick Timer**: 24-bit down counter.
- **ADC**: 2 x 12-bit Analog-to-Digital Converters with up to 10 channels.
- **DAC**: 2 x 12-bit Digital-to-Analog Converters.
- **DMA**: 7-channel Direct Memory Access controller.
- **Operating Voltage**: 2.0V to 3.6V.
- **Power Consumption**: Low-power modes for energy-efficient applications.

## Capabilities
- **High Performance**: ARM Cortex-M3 core delivers high efficiency and performance.
- **Rich Peripherals**: Integrated peripherals like USB, ADC, DAC, and timers make it suitable for complex applications.
- **Flexibility**: Supports a wide range of applications, from simple control systems to advanced IoT devices.
- **Ease of Development**: Extensive support from STM32CubeMX, HAL libraries, and third-party tools like ST-Link.
- **Community Support**: Large community and extensive documentation available.

## Applications
- **Embedded Systems**: Used in various embedded applications due to its robustness and flexibility.
- **IoT Devices**: Ideal for IoT applications with its low power consumption and communication interfaces.
- **Industrial Automation**: Suitable for industrial control systems and automation.
- **Consumer Electronics**: Found in various consumer electronic devices.
- **Robotics**: Commonly used in robotics for motor control and sensor interfacing.

## Development Tools
- **IDEs**: Keil MDK.
- **Programmers**: STLINK-V3MINIE.
- **Debuggers**: STLINK-V3MINIE.
  
# 💻 How to Use Git and GitHub
To access the repository files and save them on your computer, there are two methods available:
1. **Using Git Bash and Cloning the Repository**
   - This method is more suitable for advanced users and those familiar with command-line tools.
   - By using this method, you can easily receive updates for the repository.

2. **Downloading the Repository as a ZIP file**
   - This method is simpler and suitable for users who are not comfortable with command-line tools.
   - Note that with this method, you will not automatically receive updates for the repository and will need to manually download any new updates.

## Clone using the URL.
First, open **Git Bash** :
-  Open the folder in **File Explorer** where you want the library to be stored.
-  **Right-click** inside the folder and select the option **"Open Git Bash here"** to open **Git Bash** in that directory.

![open Git Bash](Images/Step0.png)

> [!NOTE] 
> If you do not see the "Open Git Bash here" option, it means that Git is not installed on your system.  
> You can download and install Git from [this link](https://git-scm.com/downloads).  
> For a tutorial on how to install and use Git, check out [this video](https://youtu.be/BsykgHpmUt8).
  
-  Once **Git Bash** is open, run the following command to clone the repository:

 ```bash
git clone https://github.com/aKaReZa75/STM32
```
- You can copy the above command by either:
- Clicking on the **Copy** button on the right of the command.
- Or select the command text manually and press **Ctrl + C** to copy.
- To paste the command into your **Git Bash** terminal, use **Shift + Insert**.

![Clone the Repository](Images/Step1.png)

- Then, press Enter to start the cloning operation and wait for the success message to appear.

![Open the Library File](Images/Step2.png)

> [!IMPORTANT]
> Please keep in mind that the numbers displayed in the image might vary when you perform the same actions.  
> This is because repositories are continuously being updated and expanded. Nevertheless, the overall process remains unchanged.

> [!NOTE]
> Advantage of Cloning the Repository:  
> - **Receiving Updates:** By cloning the repository, you can easily and automatically receive new updates.  
> - **Version Control:** Using Git allows you to track changes and revert to previous versions.  
> - **Team Collaboration:** If you are working on a project with a team, you can easily sync changes from team members and collaborate more efficiently.  

## Download Zip
If you prefer not to use Git Bash or the command line, you can download the repository directly from GitHub as a ZIP file.  
Follow these steps:  
1. Navigate to the GitHub repository page and Locate the Code button:
   - On the main page of the repository, you will see a green Code button near the top right corner.

2. Download the repository:
   - Click the Code button to open a dropdown menu.
   - Select Download ZIP from the menu.

  ![Download Zip](Images/Step7.png)  

3. Save the ZIP file:
   - Choose a location on your computer to save the ZIP file and click Save.

4. Extract the ZIP file:
   - Navigate to the folder where you saved the ZIP file.
   - Right-click on the ZIP file and select Extract All... (Windows) or use your preferred extraction tool.
   - Choose a destination folder and extract the contents.

5. Access the repository:
   - Once extracted, you can access the repository files in the destination folder.

> [!IMPORTANT]
> - No Updates: Keep in mind that downloading the repository as a ZIP file does not allow you to receive updates.    
>   If the repository is updated, you will need to download it again manually.  
> - Ease of Use: This method is simpler and suitable for users who are not comfortable with Git or command-line tools.
# STM32 **Cube** Package
You can download the STM32Cube MCU Firmware Packages through the following links:

[![](https://img.shields.io/badge/Cube-C0_v100-blue)](https://www.mediafire.com/file/g50dhmr7ik9lgsj/stm32cube_fw_c0_v100.zip/file)
[![](https://img.shields.io/badge/Cube-C0_v101-blue)](https://www.mediafire.com/file/ylzs5c9v1owe3e2/stm32cube_fw_c0_v101.zip/file) 

[![](https://img.shields.io/badge/Cube-F0_v1110-blue)](https://www.mediafire.com/file/keam6ubr85eynjo/stm32cube_fw_f0_v1110.zip/file)
[![](https://img.shields.io/badge/Cube-F0_v1114-blue)](https://www.mediafire.com/file/37xceinyif8a06v/stm32cube_fw_f0_v1114.zip/file)
[![](https://img.shields.io/badge/Cube-F1_v180-blue)](https://www.mediafire.com/file/18rjp5zhjh3jamk/stm32cube_fw_f1_v180.zip/file)
[![](https://img.shields.io/badge/Cube-F1_v185-blue)](https://www.mediafire.com/file/upg6cdowe42urf7/stm32cube_fw_f1_v185.zip/file)
[![](https://img.shields.io/badge/Cube-F2_v190-blue)](https://www.mediafire.com/file/ajp6arei11f6trr/stm32cube_fw_f2_v190.zip/file)
[![](https://img.shields.io/badge/Cube-F2_v194-blue)](https://www.mediafire.com/file/7ap8mh9l2tdu3jr/stm32cube_fw_f2_v194.zip/file)
[![](https://img.shields.io/badge/Cube-F3_v1110-blue)](https://www.mediafire.com/file/74w0jq0kvliu6dy/stm32cube_fw_f3_v1110.zip/file)
[![](https://img.shields.io/badge/Cube-F4_v1270-blue)](https://www.mediafire.com/file/emtlenksppxzi5o/stm32cube_fw_f4_v1270.zip/file) 
[![](https://img.shields.io/badge/Cube-F7_v1170-blue)](https://www.mediafire.com/file/suwkita0op1xhbn/stm32cube_fw_f7_v1170.zip/file) 

[![](https://img.shields.io/badge/Cube-G0_v160-blue)](https://www.mediafire.com/file/j57obnwma8e4epo/stm32cube_fw_g0_v160.zip/file) 
[![](https://img.shields.io/badge/Cube-G0_v161-blue)](https://www.mediafire.com/file/fxzmhgajn52o9ko/stm32cube_fw_g0_v161.zip/file) 
[![](https://img.shields.io/badge/Cube-G4_v150-blue)](https://www.mediafire.com/file/e7wb3qhtmofdshd/stm32cube_fw_g4_v150.zip/file) 
[![](https://img.shields.io/badge/Cube-G4_v151-blue)](https://www.mediafire.com/file/mj7n6di3xku6tmh/stm32cube_fw_g4_v151.zip/file) 

[![](https://img.shields.io/badge/Cube-H5_v100-blue)](https://www.mediafire.com/file/mgcpx55g5wyibqc/stm32cube_fw_h5_v100.zip/file)
[![](https://img.shields.io/badge/Cube-H5_v101-blue)](https://www.mediafire.com/file/wasbwumm6vslnqv/stm32cube_fw_h5_v101.zip/file)
[![](https://img.shields.io/badge/Cube-H7_v1110-blue)](https://www.mediafire.com/file/d5rtwg4xbo7tiqe/stm32cube_fw_h7_v1110.zip/file)

[![](https://img.shields.io/badge/Cube-L0_v1120-blue)](https://www.mediafire.com/file/jua1sm61452m7jo/stm32cube_fw_l0_v1120.zip/file)
[![](https://img.shields.io/badge/Cube-L0_v1122-blue)](https://www.mediafire.com/file/s0vpqnwcsyl6l6x/stm32cube_fw_l0_v1122.zip/file)
[![](https://img.shields.io/badge/Cube-L1_v1100-blue)](https://www.mediafire.com/file/i7c2fq7a6xsfh3j/stm32cube_fw_l1_v1100.zip/file)
[![](https://img.shields.io/badge/Cube-L1_v1104-blue)](https://www.mediafire.com/file/2vyrtwe9namzn2j/stm32cube_fw_l1_v1104.zip/file)
[![](https://img.shields.io/badge/Cube-L4_v1170-blue)](https://www.mediafire.com/file/1s01c1fcqnkzhy5/stm32cube_fw_l4_v1170.zip/file)
[![](https://img.shields.io/badge/Cube-L4_v1172-blue)](https://www.mediafire.com/file/e4lal7yboww3er9/stm32cube_fw_l4_v1172.zip/file)
[![](https://img.shields.io/badge/Cube-L5_v150-blue)](https://www.mediafire.com/file/1a47tkf7zvo2vx7/stm32cube_fw_l5_v150.zip/file)

[![](https://img.shields.io/badge/Cube-W1_v130-blue)](https://www.mediafire.com/file/9c5re07vjfztkza/stm32cube_fw_wl_v130.zip/file)
[![](https://img.shields.io/badge/Cube-U5_v120-blue)](https://www.mediafire.com/file/o2moq3g3kzpe1po/stm32cube_fw_u5_v120.zip/file)
[![](https://img.shields.io/badge/Cube-MP1_v160-blue)](https://www.mediafire.com/file/kcakly7s4dj9d0p/stm32cube_fw_mp1_v160.zip/file)
[![](https://img.shields.io/badge/Cube-WBA_v100-blue)](https://www.mediafire.com/file/hv013vrkhz4e170/stm32cube_fw_wba_v100.zip/file)


# STM32 **Keil** Package
You can download the STM32 MCU DFU packages for Keil through the following links:

[![](https://img.shields.io/badge/Keil-C0_DFP.1.0.0-darkgreen)](https://www.mediafire.com/file/4pakp5geniqhl1q/Keil.STM32C0xx_DFP.1.0.0.zip/file) 

[![](https://img.shields.io/badge/Keil-F0_DFP.2.1.1-darkgreen)](https://www.mediafire.com/file/ceo5dil925sy4km/Keil.STM32F0xx_DFP.2.1.1.zip/file) 
[![](https://img.shields.io/badge/Keil-F1_DFP.2.4.1-darkgreen)](https://www.mediafire.com/file/up3lr3njkycsdp8/Keil.STM32F1xx_DFP.2.4.1.zip/file) 
[![](https://img.shields.io/badge/Keil-F2_DFP.2.10.0-darkgreen)](https://www.mediafire.com/file/rlmhjmerrmrmdtb/Keil.STM32F2xx_DFP.2.10.0.zip/file) 
[![](https://img.shields.io/badge/Keil-F3_DFP.2.2.2-darkgreen)](https://www.mediafire.com/file/rkdail9629me25o/Keil.STM32F3xx_DFP.2.2.2.zip/file) 
[![](https://img.shields.io/badge/Keil-F4_DFP.2.17.0-darkgreen)](https://www.mediafire.com/file/18oczefhh4mg31t/Keil.STM32F4xx_DFP.2.17.0.zip/file) 
[![](https://img.shields.io/badge/Keil-F7_DFP.2.15.1-darkgreen)](https://www.mediafire.com/file/naz1wjgi5k8wb3k/Keil.STM32F7xx_DFP.2.15.1.zip/file) 

[![](https://img.shields.io/badge/Keil-G0_DFP.1.4.0-darkgreen)](https://www.mediafire.com/file/y4mmg0effb18woh/Keil.STM32G0xx_DFP.1.4.0.zip/file) 
[![](https://img.shields.io/badge/Keil-G4_DFP.1.5.0-darkgreen)](https://www.mediafire.com/file/tivu3sjel2dwea5/Keil.STM32G4xx_DFP.1.5.0.zip/file) 

[![](https://img.shields.io/badge/Keil-H5_DFP.1.0.0-darkgreen)](https://www.mediafire.com/file/p5r36babs25fw7w/Keil.STM32H5xx_DFP.1.0.0.zip/file) 
[![](https://img.shields.io/badge/Keil-H7_DFP.3.1.0-darkgreen)](https://www.mediafire.com/file/i9v80bmeio46wtk/Keil.STM32H7xx_DFP.3.1.0.zip/file) 

[![](https://img.shields.io/badge/Keil-L0_DFP.2.2.0-darkgreen)](https://www.mediafire.com/file/k1jlr05jasmuxdg/Keil.STM32L0xx_DFP.2.2.0.zip/file) 
[![](https://img.shields.io/badge/Keil-L1_DFP.1.4.1-darkgreen)](https://www.mediafire.com/file/nqukbotfaxha29u/Keil.STM32L1xx_DFP.1.4.1.zip/file) 
[![](https://img.shields.io/badge/Keil-L4_DFP.2.6.2-darkgreen)](https://www.mediafire.com/file/w8tqh1ox6grkq27/Keil.STM32L4xx_DFP.2.6.2.zip/file) 
[![](https://img.shields.io/badge/Keil-L5_DFP.1.4.0-darkgreen)](https://www.mediafire.com/file/6gg99pshli5v9vs/Keil.STM32L5xx_DFP.1.4.0.zip/file) 

[![](https://img.shields.io/badge/Keil-MP1_DFP.1.3.0]-darkgreen)](https://www.mediafire.com/file/vz7b5f9agcn3pp1/Keil.STM32MP1xx_DFP.1.3.0.zip/file) 
[![](https://img.shields.io/badge/Keil-U5_DFP.2.1.0]-darkgreen)](https://www.mediafire.com/file/oyjqzd5tcfpqlc0/Keil.STM32U5xx_DFP.2.1.0.zip/file) 
[![](https://img.shields.io/badge/Keil-W1_DFP.1.0.0]-darkgreen)](https://www.mediafire.com/file/1494x3e869idyyw/Keil.STM32W1xx_DFP.1.0.0.zip/file) 
[![](https://img.shields.io/badge/Keil-WBA_DFP.1.2.0]-darkgreen)](https://www.mediafire.com/file/ypw2ax2c49kpf37/Keil.STM32WBAxx_DFP.1.2.0.zip/file) 
[![](https://img.shields.io/badge/Keil-WB_DFP.1.3.0]-darkgreen)](https://www.mediafire.com/file/5odp24davhcfv8n/Keil.STM32WBxx_DFP.1.3.0.zip/file) 
[![](https://img.shields.io/badge/Keil-WL_DFP.1.1.0]-darkgreen)](https://www.mediafire.com/file/3emcqc73urkj84i/Keil.STM32WLxx_DFP.1.1.0.zip/file) 
[![](https://img.shields.io/badge/Keil-NRG-1_DFP.1.2.0]-darkgreen)](https://www.mediafire.com/file/tlff1hizdtwcgfi/Keil.STBlueNRG-1_DFP.1.2.0.zip/file) 
[![](https://img.shields.io/badge/Keil-NRG-2_DFP.1.0.1]-darkgreen)](https://www.mediafire.com/file/sv4yk1heow36vaa/Keil.STBlueNRG-2_DFP.1.0.1.zip/file) 
[![](https://img.shields.io/badge/Keil-NRG-LP_DFP.3.0.0]-darkgreen)](https://www.mediafire.com/file/qabvcsn46kzunyk/Keil.STBlueNRG-LP_DFP.3.0.0.zip/file) 

# 📝 How to Ask Questions
If you have any questions or issues, you can raise them through the **"Issues"** section of this repository. Here's how you can do it:  

1. Navigate to the **"Issues"** tab at the top of the repository page.  

  ![Issues](Images/Step3.png)

2. Click on the **"New Issue"** button.  
   
  ![New Issue](Images/Step4.png)

3. In the **Title** field, write a short summary of your issue or question.  

4. In the "Description" field, detail your question or issue as thoroughly as possible. You can use text formatting, attach files, and assign the issue to someone if needed. You can also use text formatting (like bullet points or code snippets) for better readability.  

5. Optionally, you can add **labels**, **type**, **projects**, or **milestones** to your issue for better categorization.  

6. Click on the **"Submit new issue"** button to post your question or issue.
   
  ![Submeet New Issue](Images/Step5.png)

I will review and respond to your issue as soon as possible. Your participation helps improve the repository for everyone!  

> [!TIP]
> - Before creating a new issue, please check the **"Closed"** section to see if your question has already been answered.  
>   ![Closed section](Images/Step6.png)  
> - Write your question clearly and respectfully to ensure a faster and better response.  
> - While the examples provided above are in English, feel free to ask your questions in **Persian (فارسی)** as well.  
> - There is no difference in how they will be handled!  

> [!NOTE]
> Pages and interfaces may change over time, but the steps to create an issue generally remain the same.

# 🤝 Contributing to the Repository
To contribute to this repository, please follow these steps:
1. **Fork the Repository**  
2. **Clone the Forked Repository**  
3. **Create a New Branch**  
4. **Make Your Changes**  
5. **Commit Your Changes**  
6. **Push Your Changes to Your Forked Repository**  
7. **Submit a Pull Request (PR)**  

> [!NOTE]
> Please ensure your pull request includes a clear description of the changes you’ve made.
> Once submitted, I will review your contribution and provide feedback if necessary.

# 🌟 Support Me
If you found this repository useful:
- Subscribe to my [YouTube Channel](https://www.youtube.com/@aKaReZa75).
- Share this repository with others.
- Give this repository and my other repositories a star.
- Follow my [GitHub account](https://github.com/aKaReZa75).

# 📜 License
This project is licensed under the GPL-3.0 License. This license grants you the freedom to use, modify, and distribute the project as long as you:
- Credit the original authors: Give proper attribution to the original creators.
- Disclose source code: If you distribute a modified version, you must make the source code available under the same GPL license.
- Maintain the same license: When you distribute derivative works, they must be licensed under the GPL-3.0 too.
- Feel free to use it in your projects, but make sure to comply with the terms of this license.
  
# ✉️ Contact Me
Feel free to reach out to me through any of the following platforms:
- 📧 [Email: aKaReZa75@gmail.com](mailto:aKaReZa75@gmail.com)
- 🎥 [YouTube: @aKaReZa75](https://www.youtube.com/@aKaReZa75)
- 💼 [LinkedIn: @akareza75](https://www.linkedin.com/in/akareza75)
