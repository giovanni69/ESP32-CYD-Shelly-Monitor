# ESP32-CYD-Shelly-Monitor
Power monitor with ESP32 Cheap Yellow Display 2432S028R and Shelly EM

Shelly EM is an IoT device that connects to the home WiFi network and allows for real-time monitoring of power through two current clamps. The collected data is sent to the Shelly cloud, where it can be accessed via a dedicated app. Additionally, this device also provides a local API interface that can be accessed directly. Therefore, I decided to implement a project using an Arduino board with ESP32 Cheap Yellow Display (ESP32-2432S028R), a TFT Touchscreen display LCD with an ESP32 development board included. 

This board will periodically query Shelly EM to retrieve power measurements from both the photovoltaic system and the meter, displaying them on LCD screen.


<img src="https://github.com/user-attachments/assets/23b1ce46-f3b6-439a-ad1f-dfba56192962" width=60% height=60%>
<img src="https://github.com/user-attachments/assets/5e3eedcb-6735-46ae-8a34-f188073be404" width=65% height=65%>

# .
<img src="https://github.com/user-attachments/assets/302a1624-cace-4747-adf0-6aba08cff229" width=40% height=40%>
<img src="https://github.com/user-attachments/assets/7734bf8d-cc7c-4c63-8425-c71b451d5f29" width=40% height=40%>


# Acknowledgement


