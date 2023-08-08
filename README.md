The "Smart Room" project is a comprehensive Arduino-based solution designed to enhance the comfort, security, and efficiency of any living space. By integrating temperature monitoring, intelligent fan control, lighting management, motion detection, and real-time data display on an LCD screen, this project transforms a regular room into a smart environment. The system utilizes the DHT11 sensor to continuously assess ambient temperature and automatically triggers the fan to maintain an optimal climate. Users can take charge of their room's ambiance by sending serial commands to control LEDs and lamps. The inclusion of an infrared motion sensor adds an extra layer of security by detecting any movement in the room. With the LCD screen providing instant temperature updates and user feedback, the "Smart Room" project offers a seamless blend of technology and convenience, making it an ideal solution for modern living spaces seeking to achieve a higher level of comfort, security, and energy efficiency.

## Pin Diagram

### DHT11 Sensor

- VCC: Connect to 5V
- GND: Connect to GND
- DATA: Connect to A0

### Liquid Crystal Display (LCD)

- RS: Connect to Arduino pin 12
- EN: Connect to Arduino pin 11
- D4: Connect to Arduino pin 5
- D5: Connect to Arduino pin 4
- D6: Connect to Arduino pin 3
- D7: Connect to Arduino pin 2
- Vo: GND
- VCC: Connect to 5V
- GND: Connect to GND

### Buzzer

- Connect to Arduino pin 9
- Connect the other end to GND

### LED

- Connect to Arduino pin 7
- Connect the other end to GND

### Fan

- Connect to Arduino pin 10
- Connect the other end to GND

### Infrared (IR) Sensor

- Signal: Connect to Arduino pin 8
- VCC: Connect to 5V
- GND: Connect to GND

### Lamp

- Connect to Arduino pin 13
- Connect the other end to GND

### Bluetooth

- Rx: Connect to Arduino Tx
- Tx: Connect to Arduino Rx
- GND: Connect to GND
- VCC: Connect to 5V

## Remote Control

The system can also be controlled remotely using a dedicated app provided by us.
