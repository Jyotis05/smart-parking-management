# smart-parking-management
An IoT-based intelligent parking system using ESP32 and IR sensors for real-time vehicle detection, automatic slot allocation, and web-based management to efficiently monitor and control parking spaces.

## Features
- Real-time vehicle detection using IR sensors  
- Automatic parking slot allocation and booking  
- Web-based interface to monitor parking slots  
- Servo-controlled gate operation  
- LCD display showing slot status
- Buzzer alert for vehicle entry, exit, or wrong parking 

---

## Hardware Required
- ESP32 Development Board  
- IR Sensors (for vehicle detection)  
- Servo Motor (for gate control)  
- LCD Display (LiquidCrystal_I2C)
- Buzzer (audio alert for slot booking / vehicle detection
- Jumper wires and breadboard  

---

## Software / Libraries
- Arduino IDE  
- ESP32Servo library  
- LiquidCrystal_I2C library  
- WiFi library  
- WebServer library  

---

## Circuit Diagram
![Circuit Diagram](images/circuit_diagram.png)  

---

## Installation / Setup
1. Install **Arduino IDE** and required libraries.  
2. Connect the ESP32 and components according to the circuit diagram.  
3. Open the `smart_parking.ino` file in Arduino IDE.  
4. Update WiFi credentials in the code.  
5. Upload the code to ESP32.  
6. Open the serial monitor or web interface to control the parking system.  

---

## Usage
- Access the web interface via ESP32 IP address.  
- Check available parking slots.  
- Book a slot; the gate will open automatically.  
- Monitor slot status in real-time via LCD or web page.  

---

## Project Images / Web Interface
![Web Interface](images/web_interface.png)  

---

## Future Enhancements
- Integration with mobile app for remote booking  
- Predictive slot availability using machine learning  
- Cloud-based data logging and analytics  
- Integration with smart city infrastructure  




