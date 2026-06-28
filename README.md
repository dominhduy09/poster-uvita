# poster-uvita
poster-uvita

# Overview
UVITA is a real-time UV monitoring system developed for the NASA Space Apps Challenge 2024, designed to promote sun safety and public health. By leveraging NASA’s open climate data, UVITA provides accurate, accessible UV index readings to help users make informed decisions about sun exposure. This repository contains the source code, documentation, and resources for our smart UV monitoring solution.

# Features
Real-time UV index monitoring using NASA’s environmental datasets.
User-friendly interface for displaying UV levels and safety recommendations.
Data processing pipeline for integrating and analyzing UV-related climate data.
Alerts for high UV exposure risks to enhance public health awareness.

# Data Source
UVITA utilizes NASA’s open climate data, specifically UV radiation and environmental datasets, available through NASA Earth Data. Sample datasets and data-fetching scripts are included in the data/ directory.

# Team
Nguyen Le Manh Phi - Faculty of Physics and Engineering Physics, University of Science, VNUHCM
Tran Le Quoc Thong - Faculty of Physics and Engineering Physics, University of Science, VNUHCM
Pham Thanh Phong - Faculty of Physics and Engineering Physics, University of Science, VNUHCM
Nguyen Huynh Tam - Information Technology, International University, VNUHCM
Do Minh Duy - Information Technology, University of Science, VNUHCM
Tran Gia Hien - Faculty of Geology, University of Science, VNUHCM
Pham Thanh Thuy (Corresponding Author) - Faculty of Physics and Engineering Physics, University of Science, VNUHCM
Email: pththuy@hcmus.edu.vn


# Credits 💳
NASA Space Apps Challenge 2024: For providing an inspiring platform to innovate for global challenges.
NASA Earth Data: For open-access UV and climate datasets critical to UVITA’s functionality.
Beta Testers: For their invaluable feedback in refining the application.
University of Science, VNUHCM: For providing resources, mentorship, and facilities.
International University, VNUHCM: For supporting team members in the Information Technology department.
Acknowledgments
We sincerely thank the NASA Space Apps Challenge 2024 organizers for their inspiring platform, NASA for providing open climate data critical to our project’s validation, our beta testers for essential feedback, and the University of Science, VNUHCM, for providing resources and mentorship that enabled our participation.

# License
This project is licensed under the MIT License. See LICENSE for details.

# Contact
For inquiries, contact pththuy@hcmus.edu.vn or open an issue on GitHub.

# UVITA - A SMART UV MONITORING SOLUTION 
“Real-Time UV Monitoring for Sun Safety and Public Health”

Nguyen Le Manh Phi , Tran Le Quoc Thong , Pham Thanh Phong , Nguyen Huynh Tam , Do Minh Duy , Tran Gia Hien , Pham Thanh Thuy 
Faculty of Physics and Engineering Physics, University of Science, VNUHCM; Information technology, International University, VNUHCM;  Information technology, University of Science, VNUHCM; Faculty of Geology, University of Science, VNUHCM

Corresponding author: pththuy@hcmus.edu.vn 

![Screenshot 2025-05-25 115952](https://github.com/user-attachments/assets/883a06fe-ae5c-4e7f-883b-abc017f058ce)

Sources:
- https://www.spaceappschallenge.org/nasa-space-apps-2024/find-a-team/pho-broth/?tab=project
- https://github.com/flexity1210/UVita

# UVita - Solution for Health and Innovation

# UVita

## Project Summary
We developed an innovative application that displays the UV index in real time, utilizing data collected from UV-measuring phone cases equipped with integrated UV and light sensors. With the low awareness of the harmful effects of UV radiation on skin health, individuals often lack access to immediate and accurate information about UV exposure levels. Our project aims to bridge this gap by providing users with real-time UV index data directly on their smartphones, enabling informed decisions about sun protection. This application is crucial for promoting public health by helping users avoid excessive UV exposure, which can lead to skin damage and increased risk of skin cancer. By integrating IoT technology with a user-friendly app, we empower individuals to take proactive measures to safeguard their skin while enjoying outdoor activities.

## Project Demonstration
[Canva Presentation](https://www.canva.com/design/DAGSfRo2qZY/CM14lnt8c7Gg3A5XrXgr1g/edit?utm_content=DAGSfRo2qZY&amp;utm_campaign=designshare&amp;utm_medium=link2&amp;utm_source=sharebutton)

## Project
[GitHub Repository](https://github.com/Phong12HexDockwork/UVita/tree/main)

## Project Details
<img width="1024" height="393" alt="27702" src="https://github.com/user-attachments/assets/52824d73-7093-4363-b835-5e6aa3b086d8" />

- WHAT EXACTLY DOES IT DO?
  
UVita is an innovative application designed to provide real-time UV index data to users through their smartphones. By harnessing the capabilities of UV-measuring phone cases equipped with integrated UV and light sensors, the application addresses a significant gap in public awareness regarding the harmful effects of UV radiation on skin health. In an era where outdoor activities are increasingly common, many individuals remain unaware of the risks associated with UV exposure, including skin damage and heightened risk of skin cancer. Our project aims to empower users with immediate, accurate information, enabling them to make informed decisions about sun protection and promoting overall public health.

- HOW DOES IT WORK?

The UVita system operates through a seamless integration of various hardware components, ensuring reliable and accurate data transmission. The process begins when sunlight, containing UV radiation, approaches the integrated UV and light sensors located within the specially designed phone case. Here’s a detailed breakdown of how the system works:

<img width="1024" height="472" alt="image" src="https://github.com/user-attachments/assets/f70d34d0-7394-497b-8261-9af480830395" />

1. Data Collection: The UV and light sensors detect the intensity of UV radiation in real-time. This data is crucial for calculating the UV index, which indicates the potential risk of harm from unprotected sun exposure.

2. Processing the Data: The sensors transmit the collected data to an Arduino Pro Mini microcontroller. The Arduino serves as the central processing unit, interpreting the data received from the sensors and converting it into a usable format.

3. Bluetooth Transmission: Once the data is processed, the Arduino Pro Mini sends the UV index information to a Bluetooth module. This module, which is essential for wireless communication, allows the processed data to be transmitted to the user’s smartphone.

4. Power Supply Considerations: All components, including the UV and light sensors and the Arduino, operate on a stable 3.3V supply provided by a rechargeable battery. To ensure consistent performance, we employ a buck-boost voltage regulator, which maintains a steady voltage output regardless of battery charge levels. The Bluetooth module, however, requires a different voltage supply, and thus, it is powered separately to ensure reliability.

5. Battery Management: The battery powering the system is integrated with a charging module, allowing for convenient recharging. This ensures that users can rely on the UVita system without the worry of frequent battery replacements, making it ideal for regular outdoor use.

6. User Interface: Users receive real-time updates about the UV index directly on their smartphones through the UVita application. The app is designed to be user-friendly, offering notifications and recommendations for sun protection based on current UV levels.

- WHAT BENEFITS DOES IT HAVE?
<img width="1024" height="472" alt="50452" src="https://github.com/user-attachments/assets/715be018-2229-44e6-975b-4a7833defff8" />
<img width="1024" height="472" alt="36490" src="https://github.com/user-attachments/assets/6942db47-0a8c-4c60-b907-ae5c2ac7e183" />

The UVita application provides several key benefits:

+ Real-Time Awareness: Users gain immediate access to information about UV exposure, allowing them to make informed decisions regarding sun safety.

+ Enhanced Skin Protection: By providing timely alerts about high UV index levels, UVita helps users take proactive measures to protect their skin, reducing the risk of damage and long-term health issues like skin cancer.

+ Encouragement of Outdoor Activities: By empowering users with knowledge, UVita encourages safe outdoor experiences, promoting a healthier lifestyle while enjoying nature.

+ Educational Resource: The application raises awareness about UV radiation and its potential effects on skin health, fostering a more informed public.

- WHAT DO YOU HOPE TO ACHIEVE?

Our goal is to enhance public understanding of UV radiation and its associated risks through the UVita application. By providing users with accurate, real-time data, we aim to foster a culture of proactive sun safety, ultimately reducing the incidence of UV-related skin damage and skin cancer. We also hope to contribute to broader public health initiatives by encouraging responsible sun exposure habits and increasing awareness of the importance of skin health.

- TOOLS, LANGUAGES, HARDWARE

# LANGUAGES

+ C++: Used for programming the Arduino microcontroller.

+ Android Studio : For developing the mobile application.

+ HTML5, JavaScript, CSS3: Web development technologies. 

+ .NET: Software development framework. 

+ Flutter, React Native: Cross-platform mobile app development frameworks. 

# Libraries & UI Frameworks 

+ Bootstrap: CSS framework for responsive design. 

+ CytoscapeJS: For visualizing complex networks. 

# Cloud & Backend

+ Firebase: Backend as a Service (BaaS) for building mobile and web apps. 

# Version Control & Deployment 

+ Git: Version control. 

+ Github Pages: For hosting static websites.

# HARDWARE

+ ML8511 UV Sensor: For measuring UV radiation.

+ TSL2561 Light Sensor: For measuring ambient light conditions.

+ Arduino Pro Mini: Central processing unit for data interpretation.

+ Bluetooth Module (e.g., HC-05): For wireless communication with smartphones.

+ 3.3V Buck-Boost Voltage Regulator: Ensures stable voltage supply.

+ Rechargeable Battery: Powers the entire system.

# SOFTWARE

+ Arduino IDE: For programming the microcontroller.

+ Android Studio: For mobile application development.

+ Visual Studio Code: For any additional coding and debugging needs.

+ GitHub: For version control and project documentation.

+ Neovim: Code editor.

+ Powershell: Task automation and configuration management.

Through UVita, we aim to revolutionize the way individuals interact with sun safety information, transforming the landscape of skin health awareness in an engaging and innovative manner.

- One more thing
<img width="1024" height="472" alt="4213" src="https://github.com/user-attachments/assets/bd821735-0e27-470a-a6e2-58595572e269" />

NASA serves as a vital source of scientific data, providing information on space, climate, and natural disasters. Additionally, NASA collaborates with government agencies to disseminate public health knowledge and issue early warnings for impending natural disasters. This system plays a crucial role in delivering timely and accurate information, supporting disaster preparedness and response efforts, while also raising awareness about public health initiatives and the proactive approach helps enhancing their ability to respond to emergencies and make well-informed decisions.

Our process:

- Testing process: https://drive.google.com/drive/folders/1WsSk5XxNmezuu-OPdTZe5hIzjfwvgnR-
- Designing process: https://drive.google.com/drive/folders/13GcpQmWxGkk2z6cEiOxGMFCT5gkiB5U2

Use of Artificial Intelligence (AI):
- Blackbox Ai (www.blackbox.ai)
- ChatGPT
- Copilot
- Gemini (google.com)

NASA Data:
- The Sun: https://science.nasa.gov/gallery/the-sun/
- News Notification: https://science.data.nasa.gov/news/
- Ultraviolet Waves: https://science.nasa.gov/ems/10_ultravioletwaves/
- UV Index: https://neo.gsfc.nasa.gov/view.php?datasetId=AURA_UVI_CLIM_M

Space Agency Partner & Other Data: 
- ML8511 UV Sensor Manual: https://www.digikey.com/htmldatasheets/production/1342229/0/0/1/ml8511-datasheet.html?msockid=2ddb54504ade65d7064e40a34bcc643c
- ML8511 UV Sensor Library: https://github.com/RobTillaart/ML8511
- ML8511 UV Sensor UVI Formula Calculation: https://cdn.sparkfun.com/assets/learn_tutorials/2/0/6/ML8511_UV.pdf#:~:text=Calculation%20of%20the%20actual%20UV%20Index%20from%20Vout%20of%20ML8511
- SparkFun TSL2561 Light Sensor: https://github.com/sparkfun/SparkFun_TSL2561_Arduino_Library
- Joba Tsl2561 Usage: https://github.com/joba-1/Joba_Tsl2561
- Adafruit TSL2561 Driver: https://github.com/adafruit/Adafruit_TSL2561
- Adafruit TSL2561 Datasheet: https://cdn-shop.adafruit.com/datasheets/TSL2561.pdf#:~:text=The%20TSL2560%20and%20TSL2561%20are%20light-to-digital%20converters%20that%20transform%20light
- HC-05 -Bluetooth to Serial Port Module: https://components101.com/sites/default/files/component_datasheet/HC-05%20Datasheet.pdf
- nRF52832 Bluetooth Chipset: https://docs.nordicsemi.com/category/nRF52832-category
- E104-BT5032A/B Bluetooth Module Manual: https://www.bing.com/ck/a?!&amp;&amp;p=0fbac393fb639f3eJmltdHM9MTcyODA4NjQwMCZpZ3VpZD0yZGRiNTQ1MC00YWRlLTY1ZDctMDY0ZS00MGEzNGJjYzY0M2MmaW5zaWQ9NTE4NA&amp;ptn=3&amp;ver=2&amp;hsh=3&amp;fclid=2ddb5450-4ade-65d7-064e-40a34bcc643c&amp;psq=E104-BT5032A%2fB+User+Manua&amp;u=a1aHR0cHM6Ly93d3cubWFudWFsc2xpYi5jb20vbWFudWFsLzM0MzQ2MTUvRWJ5dGUtRTEwNC1CdDUwMzJhLUIuaHRtbCM6fjp0ZXh0PVZpZXcgYW5kIERvd25sb2FkIEVieXRlIEUxMDQtQlQ1MDMyQS9CIHVzZXIgbWFudWFsIG9ubGluZS4gblJGNTI4MzIgQkxFNS4w&amp;ntb=1
- Arduino Pro Mini Docs: https://docs.arduino.cc/retired/boards/arduino-pro-mini/
- Arduino Pro Mini Source Hardware: https://www.arduino.cc/en/uploads/Main/Arduino-Pro-Mini-schematic.pdf
- Arduino Pro Mini Tutorial: https://docs.arduino.cc/tutorials/
- Arduino Pro Mini Reference: https://www.arduino.cc/reference/en/
- ATmega328P: https://ww1.microchip.com/downloads/en/DeviceDoc/Atmel-7810-Automotive-Microcontrollers-ATmega328P_Datasheet.pdf#:~:text=ATmega328P%20[DATASHEET]%207810D%E2%80%93AVR%E2%80%9301/15%206%202.%20Overview%20The%20Atmel%C2%AE%20ATmega328P%20is
- USB IC - FTDI Datasheet: https://ftdichip.com/document/usb-ic-data-sheets/#:~:text=USB%20IC%20Data%20Sheets.%20The%20documents%20listed%20below%20are%20the
- USB IC - FTDI Products Reference: https://ftdichip.com/product-category/products/
- 3.3V Buck-Boost Switching Voltage Regulators Reference: https://www.mouser.vn/c/semiconductors/power-management-ics/voltage-regulators-voltage-controllers/switching-voltage-regulators/?output%20voltage=3.3%20V&amp;topology=Buck-Boost
- Battery Pho Broth Reference Collection: https://drive.google.com/drive/folders/1Op4Flf33sUin_Ei8tsdRmzzRxbZx5DL1?usp=sharing
- UV Index Scale: https://www.epa.gov/sunsafety/uv-index-scale-0

