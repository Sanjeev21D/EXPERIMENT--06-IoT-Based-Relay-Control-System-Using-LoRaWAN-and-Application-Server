# EXPERIMENT--06-IoT-Based-Relay-Control-System-Using-LoRaWAN-and-Application-Server
## Aim
To configure a LoRaWAN end device and monitor IR sensor data using a network server and dashboard visualization.

## Components Required
- LoRaWAN End Device-STM32
- LoRaWAN Gateway
- Application Server Dashboard
- Serial Port Utility
- Development Tools (STM32CubeIDE, STM32CubeProgrammer)

## Procedure
1. Open STM32CubeIDE and import the project from the realy-control project directory.
2. Select the LoRaWAN End Node project for the NUCLEO-WLE5JC board.
3. Clean all previous build files using the Clean Project option in the build configuration.
4. Build the project to generate the firmware files.
5. Flash the compiled firmware into the STM32 board using STM32CubeProgrammer with baud rate set to 9600.
6. Open the network server console and login using your registered email ID and password.
7. Register the device by selecting Device Types and adding the LoRaWAN device in the network server.
8. Open the Serial Port Utility  give the AT commands and verify device connection through the serial port utility
9. Create a dashboard on the application server by clicking the Add Dashboard option.
10. Add widgets and commands to visualize the relay status data.
11. Send control commands from the dashboard to control the relay.

## Output
### 1. Serial Port Utility – Network Server Connection
## AT+FDR
<img width="1600" height="900" alt="Image" src="https://github.com/user-attachments/assets/5edc3e10-6a4a-47a8-be3f-1e6534b33090" />

## AT+NJM
<img width="1600" height="900" alt="Image" src="https://github.com/user-attachments/assets/155f0ca7-e3be-461c-88f6-2ee8c9f15e99" />

## AT+ADR
<img width="1600" height="900" alt="Image" src="https://github.com/user-attachments/assets/832cd86c-0cd9-4d18-a2dd-f1b014ab9806" />

## AT+TDC
<img width="1600" height="900" alt="Image" src="https://github.com/user-attachments/assets/7bd9a99b-de39-41c8-8a98-59a315c8b20d" />

## AT+CLASS
<img width="1600" height="900" alt="Image" src="https://github.com/user-attachments/assets/eee7ebf7-7306-4a1b-8b03-d235a64c6906" />

## AT+DEUI
<img width="1600" height="900" alt="Image" src="https://github.com/user-attachments/assets/c39e3abc-4274-4ccf-89f1-d923e288c0d5" />

## AT+APPEUI
<img width="1600" height="900" alt="Image" src="https://github.com/user-attachments/assets/c30c607c-a242-451b-9a99-87e14901471a" />

## ATZ
<img width="1600" height="900" alt="Image" src="https://github.com/user-attachments/assets/49360c2c-f287-463b-8e2e-f804010f73a5" />

### 2. Network Server – Recent Events
<img width="1920" height="1080" alt="Screenshot 2026-03-19 160359" src="https://github.com/user-attachments/assets/556e05db-3f42-4c44-937e-e5f6ea89e8c6" />

### 3. Dashboard Command Sending
<img width="1920" height="1080" alt="Screenshot 2026-03-19 210109" src="https://github.com/user-attachments/assets/975f94f1-4f39-401b-b6e4-59a671c5fd27" />

### 4. Relay Status Dashboard Output

### Bulb ON → Relay ON  
<img width="1920" height="1080" alt="Screenshot 2026-03-19 160303" src="https://github.com/user-attachments/assets/d53c1d39-839b-4f63-9e29-5e845dd99543" />

![on board off](https://github.com/user-attachments/assets/ad654aa6-10fb-42f2-a646-e6ea2695d743)

### Bulb OFF → Relay OFF
<img width="1920" height="1080" alt="Screenshot 2026-03-19 160343" src="https://github.com/user-attachments/assets/8e12163e-56be-44aa-8baa-f94deb141305" />

![on board on](https://github.com/user-attachments/assets/f9e82e07-686b-47f7-a625-a3fe477dddc5)

## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
