# RS485Thermostat
**Replace that awful thermostat with something cool** THIS HAS ONLY BEEN TESTED TO WORK WITH COLEMAN/AIRXCEL 

**What this will do**
Room Temp: Read from DS18B20  
Dual Setpoints: Heat + Cool separately adjustable  
Deadband: 3°F buffer to prevent cycling  
Mode Auto: Automatically heats/cools based on temp  
Zone 1 & 2 RS485 Control every 5 sec  

**Parts Needed:**  
DS18B20  
ESP32-S3-Touch-LCD-4.3  
TTL to RS485 485 to Serial UART Adapter  
4.7kΩ Pull-Up Resistor this goes between the red and yellow wires

**Home Assistant**  
Just MQTT  

**Code Adjustment**  
Replace YOUR_WIFI_SSID, YOUR_WIFI_PASSWORD, YOUR_MQTT_BROKER_IP, YOUR_MQTT_USERNAME, YOUR_MQTT_PASSWORD with your real values

![61R8InXl6RL _SL1010_](https://github.com/user-attachments/assets/fd422baf-c65f-47a9-9630-ac7fad290ecd)
![image](https://github.com/user-attachments/assets/9ca14c3d-79ea-415f-9ce3-022ea4fd6c72)
![61jsYiEs7xL _SL1010_](https://github.com/user-attachments/assets/84b8aca3-b364-4f2f-ba14-870bb277a020)
![51xQ4eeMY3L _SL1300_](https://github.com/user-attachments/assets/87f30c57-ef5c-4391-a161-2fc17da305bd)

![cd4d54ab-e845-420c-8136-d07e6aabc43c](https://github.com/user-attachments/assets/02b4a027-5e2a-4326-87ac-50a7b1624304)
