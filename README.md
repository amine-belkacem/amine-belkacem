## Hi, I'm Mohamed Amine BELKACEM 👋

Master 2 student in **Communicating Electronic Systems Design (CSEC)** at the **University of Lorraine** (Metz, France). Before that I did a first Master's in **Embedded Systems Electronics** at USTHB, Algiers.

I like working where hardware meets software: digital design on FPGA in VHDL, firmware on microcontrollers, and the PC tools that talk to the board. Lately I've been spending more time on **AI**: hardware for **AI inference** (my FP8 project), and how to evaluate a model honestly when the data is hard (my fraud detection project).

🎯 **Looking for a 4 to 6-month end-of-studies internship starting early 2027**, in FPGA / digital design, embedded systems or embedded AI, anywhere in France.

### 🔧 Projects

| Project | What it is | Stack |
|---|---|---|
| [**FP8 MAC unit**](https://github.com/amine-belkacem/fp8-mac-vhdl) | Multiply-accumulate operator in FP8 (E4M3) for AI inference, synthesized on Cyclone IV (≈ 6 % of the FPGA) and verified with testbenches | VHDL · Quartus · Questa · GHDL |
| [**Fraud detection under an alert budget**](https://github.com/amine-belkacem/fraud-detection-alert-budget) | Credit card fraud models (0.17 % fraud) evaluated the way a fraud team would use them: temporal split, alert budget, simulated cost in euros and bootstrap intervals. XGBoost catches 80 % of the frauds at a 0.1 % false positive rate; SMOTE brought no measurable gain, and a random split would have overstated PR-AUC by 0.07. 70 tests run in CI | Python · scikit-learn · XGBoost · imbalanced-learn · pytest · GitHub Actions |
| [**Qt6 UART API (PC ↔ FPGA)**](https://github.com/amine-belkacem/qt6-uart-fpga-api) | C++ class that handles the serial link between a PC and a Basys3 board, tested on the real board, with QTest tests running in CI on virtual serial ports | C++17 · Qt 6 · QSerialPort · CMake · GitHub Actions |
| [**Smart House solar supply**](https://github.com/amine-belkacem/smart-house-solar-energy) | Solar power chain for an Arduino house model (my part of a licence group project): PV sizing redone in Python, tested in CI and compared with multimeter measurements on the prototype | Arduino · TP4056 · XL6009 · Python · pytest · GitHub Actions |
| [**Face recognition attendance on Raspberry Pi**](https://github.com/amine-belkacem/face-attendance-raspberry-pi) | Time clock that recognises people with a webcam (Haar cascade + KNN) and logs arrivals in a daily CSV, with a Flask page to enrol users. I fixed the bugs from my report version and added 16 pytest tests running in CI | Python · OpenCV · scikit-learn · Flask · Raspberry Pi · pytest · GitHub Actions |
| [**Connected weather station (Home Assistant)**](https://github.com/amine-belkacem/home-assistant-weather-station) | Web dashboard I wrote for a 10-student IoT lab: it reads the ESP32 sensors through the Home Assistant REST API and compares them with Open-Meteo. I also helped integrate the sensors. 13 tests on the unchanged code run in CI and caught one real bug | JavaScript · HTML/CSS · REST API · Home Assistant · ESP32 · node:test · GitHub Actions |
| [**Connected health monitor (ESP32 + Raspberry Pi 5)**](https://github.com/amine-belkacem/health-monitor-iot) | My first Master's thesis: ECG, SpO2, temperature and air quality read by an ESP32 and sent over Wi-Fi to a Flask/SQLite server on a Pi 5, with a web dashboard and a Flutter app. Going back through the code, I found and fixed a bug that truncated the ECG to whole volts. Server tests, the firmware build and Flutter tests run in CI | ESP32 · Arduino C++ · Python · Flask · SQLite · Flutter · pytest · GitHub Actions |
| **FPGA accelerator for molecular dynamics** *(in progress)* | Hardware/software co-design: Python host + VHDL pipelines for force computation | VHDL · Python |
| **Low-power LoRaWAN metering node** | ESP32 firmware for voltage/current measurement, deep-sleep state machine, LoRa-E5 module (internship, CREDEG – Sonelgaz) | C/C++ · ESP32 · LoRaWAN · MQTT |

*The projects without a link aren't published yet.*

### 🛠️ Tech stack

- **Digital design / FPGA:** VHDL, Verilog, RTL design, testbenches, Intel Quartus Prime, Questa, Cyclone IV, Artix-7 (Basys 3)
- **Embedded systems:** C, C++, STM32, ESP32, Arduino, Raspberry Pi, FreeRTOS, UART, SPI, I2C, CAN, LoRaWAN
- **Software & tools:** Python, pytest, Qt 6, CMake, Git, GitHub Actions, Linux, MATLAB/Simulink, Flask, MQTT
- **Web / IoT / mobile:** JavaScript, HTML/CSS, Chart.js, REST APIs, Home Assistant, Flutter (Android)
- **AI / computer vision:** OpenCV (Haar cascade face detection), scikit-learn (KNN, logistic regression), XGBoost, imbalanced-learn, model evaluation on imbalanced data (PR-AUC, bootstrap intervals, threshold choice), neural network fundamentals, reduced-precision arithmetic (FP8) for inference, TensorFlow / PyTorch

### 🌍 Languages
English · French · Spanish · Arabic · Kabyle

### 📫 Contact
[LinkedIn](https://www.linkedin.com/in/mohamed-amine-belkacem-262582391/) · mohamed-amine.belkacem8@etu.univ-lorraine.fr
