## Hi, I'm Mohamed Amine BELKACEM 👋

Master 2 student in **Communicating Electronic Systems Design (CSEC)** at the **University of Lorraine** (Metz, France). Before that I did a first Master's in **Embedded Systems Electronics** at USTHB, Algiers.

I like working where hardware meets software: digital design on FPGA in VHDL, firmware on microcontrollers, and the PC tools that talk to the board. Lately I've been looking at **AI** and hardware for **AI inference**, which is where my FP8 project comes from.

🎯 **Looking for a 4 to 6-month end-of-studies internship starting early 2027**, in FPGA / digital design, embedded systems or embedded AI, anywhere in France.

### 🔧 Projects

| Project | What it is | Stack |
|---|---|---|
| [**FP8 MAC unit**](https://github.com/amine-belkacem/fp8-mac-vhdl) | Multiply-accumulate operator in FP8 (E4M3) for AI inference, synthesized on Cyclone IV (≈ 6 % of the FPGA) and verified with testbenches | VHDL · Quartus · Questa · GHDL |
| [**Qt6 UART API (PC ↔ FPGA)**](https://github.com/amine-belkacem/qt6-uart-fpga-api) | C++ class that handles the serial link between a PC and a Basys3 board, tested on the real board, with QTest tests running in CI on virtual serial ports | C++17 · Qt 6 · QSerialPort · CMake · GitHub Actions |
| [**Smart House solar supply**](https://github.com/amine-belkacem/smart-house-solar-energy) | Solar power chain for an Arduino house model (my part of a licence group project): PV sizing redone in Python, tested in CI and compared with multimeter measurements on the prototype | Arduino · TP4056 · XL6009 · Python · pytest · GitHub Actions |
| [**Face recognition attendance on Raspberry Pi**](https://github.com/amine-belkacem/face-attendance-raspberry-pi) | Time clock that recognises people with a webcam (Haar cascade + KNN) and logs arrivals in a daily CSV, with a Flask page to enrol users. I fixed the bugs from my report version and added 16 pytest tests running in CI | Python · OpenCV · scikit-learn · Flask · Raspberry Pi · pytest · GitHub Actions |
| [**Connected weather station (Home Assistant)**](https://github.com/amine-belkacem/home-assistant-weather-station) | Web dashboard I wrote for a 10-student IoT lab: it reads the ESP32 sensors through the Home Assistant REST API and compares them with Open-Meteo. I also helped integrate the sensors. 13 tests on the unchanged code run in CI and caught one real bug | JavaScript · HTML/CSS · REST API · Home Assistant · ESP32 · node:test · GitHub Actions |
| **FPGA accelerator for molecular dynamics** *(in progress)* | Hardware/software co-design: Python host + VHDL pipelines for force computation | VHDL · Python |
| **Low-power LoRaWAN metering node** | ESP32 firmware for voltage/current measurement, deep-sleep state machine, LoRa-E5 module (internship, CREDEG – Sonelgaz) | C/C++ · ESP32 · LoRaWAN · MQTT |
| **Connected health monitoring system** | ECG, SpO2 and temperature acquisition on ESP32, Flask server on Raspberry Pi 5 with real-time dashboard and alerts | ESP32 · Python · Flask · SQLite |

*The projects without a link aren't published yet.*

### 🛠️ Tech stack

- **Digital design / FPGA:** VHDL, Verilog, RTL design, testbenches, Intel Quartus Prime, Questa, Cyclone IV, Artix-7 (Basys 3)
- **Embedded systems:** C, C++, STM32, ESP32, Arduino, Raspberry Pi, FreeRTOS, UART, SPI, I2C, CAN, LoRaWAN
- **Software & tools:** Python, pytest, Qt 6, CMake, Git, GitHub Actions, Linux, MATLAB/Simulink, Flask, MQTT
- **Web / IoT:** JavaScript, HTML/CSS, REST APIs, Home Assistant
- **AI / computer vision:** OpenCV (Haar cascade face detection), scikit-learn (KNN), neural network fundamentals, reduced-precision arithmetic (FP8) for inference, TensorFlow / PyTorch

### 🌍 Languages
English · French · Spanish · Arabic · Kabyle

### 📫 Contact
[LinkedIn](https://www.linkedin.com/in/mohamed-amine-belkacem-262582391/) · mohamed-amine.belkacem8@etu.univ-lorraine.fr
