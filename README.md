# Custom-measuring-water-temperature-in-storage-tanks
-> Custom measuring water temperature in storage tanks in the house build on ESP32 board from 2023.
-> The customer wanted a private solution for measuring the temperature in the storage tanks in his house. The project was built on the Arduino cloud platform due to its mobile phone application to communicate with the user for easier control over the water temperature.

-> due to personal reasons of the customer, the code is on request <-

![image](https://github.com/user-attachments/assets/90ce9847-44e6-480e-b22d-71863d29d3f0)

-> The task was to monitor the water temperature in the storage tanks, so that the user could monitor the drop in the water temperature in the tank and go to add it to the boiler or re-heat it in the solid fuel boiler.
-> The measuring system therefore contains 9 DS18B20 sensors for measuring the temperature in the tanks and the outdoor temperature. Then one Ktype sensor with MAX6675 for measuring the smoke temperature in the chimney. The last sensor is for measuring air quality MQ135. All peripherals are connected to esp32 and communicate with Arduino Cloud via Wi-Fi.

-> The user interface is implemented via an OLED I2C display and three LEDs. The display shows the current temperature from each sensor. The three LEDs are a Green LED for power supply, a Red LED for error, and a Yellow LED for Wifi connection.

![image](https://github.com/user-attachments/assets/3929f8d2-cf26-46c6-8218-9d2bc4266c45)
-> PCB was designed in eagle program but I lost the files and yes I created the PCB by the old way with etching technique. ,, if I will recreating this device again, I gonna crate PCB at factory."
-> Here are some pictures form a testing and assembling the device. 
![image](https://github.com/user-attachments/assets/f65f2751-a2d7-4108-830d-30e759786d55)

![image](https://github.com/user-attachments/assets/6e741364-c00a-4ab1-8167-7f9ee4790537)

-> As I said, the client chose the Arduino cloud solution because the IoT Remote mobile application is also available for this Cloud, which sends the user a notification on their mobile phone when the temperature in the tanks changes or in the event of air pollution, and they can then use graphs to view the temperatures on all sensors. Here are some pictures from the online web editor and mobile aplication. 

shown in the online editor: 

![image](https://github.com/user-attachments/assets/6a0b3d77-814e-40a7-b551-4bb90e511839)


shown in the mobile aplication: 

<p align="center">
  <img src="https://github.com/user-attachments/assets/901df88d-5d80-449d-9640-93b31961c1aa" alt="Obrázek 1" width="200">
  <img src="https://github.com/user-attachments/assets/cff87e34-fc09-47bb-be22-d769ceb1dd29" alt="Obrázek 2" width="200">
  <img src="https://github.com/user-attachments/assets/c76efc06-836e-4dff-af33-bca86258bf60" alt="Obrázek 3" width="200">
  <img src="https://github.com/user-attachments/assets/de46d7a8-5016-4f61-a65a-a84b8d2a3cda" alt="Obrázek 4" width="200">
</p>


-> due to personal reasons of the customer, the code is on request <-

