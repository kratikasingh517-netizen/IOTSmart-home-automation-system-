#  IoT-Based Smart Home Automation System

##  Description

The IoT-Based Smart Home Automation System is designed to automate household appliances and improve home security using Arduino Uno and various sensors. The system monitors environmental conditions such as motion, temperature, gas leakage, and object distance, and automatically controls connected appliances through relay modules.

The project demonstrates how embedded systems and IoT concepts can be used to create an intelligent, energy-efficient, and secure smart home environment.

---

##  Objectives

- Automate home appliances using sensors.
- Improve home security through motion and gas detection.
- Reduce electricity consumption using automatic control.
- Monitor environmental conditions in real time.
- Learn the fundamentals of IoT and embedded systems.

---

##  Features

- Motion-activated lighting
- Automatic fan control based on temperature
- Gas leakage detection with buzzer alert
- Distance detection using ultrasonic sensor
- Relay-based appliance control
- Energy-efficient automation
- Real-time sensor monitoring

---

##  Hardware Components

- Arduino Uno
- PIR Motion Sensor
- HC-SR04 Ultrasonic Sensor
- MQ Gas Sensor
- TMP36/LM35 Temperature Sensor
- Relay Module
- DC Motor/Fan
- Bulb
- Piezo Buzzer
- Breadboard
- Jumper Wires
- 9V Battery

---

##  Software Requirements

- Arduino IDE
- Tinkercad
- C++ Programming Language

---

##  Technologies Used

- Internet of Things (IoT)
- Arduino
- Embedded Systems
- Sensor Interfacing
- Automation

---

##  Working Principle

1. Arduino continuously reads data from all connected sensors.
2. The PIR sensor detects motion and switches ON the room light automatically.
3. The ultrasonic sensor detects nearby objects by measuring distance.
4. The temperature sensor monitors room temperature and turns ON the fan when the temperature exceeds a predefined limit.
5. The gas sensor detects gas leakage and activates the buzzer as a warning.
6. Relay modules control electrical appliances safely.
7. The system continuously monitors the environment and performs automatic actions.

---

##  Components and Their Functions

| Component | Function |
|-----------|----------|
| Arduino Uno | Main controller |
| PIR Sensor | Detects human motion |
| Ultrasonic Sensor | Measures distance |
| Gas Sensor | Detects gas leakage |
| Temperature Sensor | Measures room temperature |
| Relay Module | Controls electrical appliances |
| Bulb | Represents room lighting |
| Motor/Fan | Cooling appliance |
| Buzzer | Warning indicator |

---

##  Installation

1. Install Arduino IDE.
2. Connect Arduino Uno to your computer.
3. Open the project (.ino) file.
4. Select **Arduino Uno** as the board.
5. Select the correct COM port.
6. Upload the code.
7. Assemble the circuit according to the circuit diagram.
8. Power the circuit and test the system.

---

##  Project Structure

```
IoT-Smart-Home-Automation/
│
├── Arduino_Code/
│   └── SmartHomeAutomation.ino
│
├── Circuit_Diagram/
│   └── circuit.png
│
├── Images/
│   ├── output.png
│   └── simulation.png
│
├── Documentation/
│   └── Project_Report.pdf
│
└── README.md
```

---

## 📸 Circuit Diagram

Add your circuit diagram here.

<p align="center">
  <img src="Images/Smart Home Automation System.png" width="700">
</p>


---

##  Output

Add screenshots of the simulation or hardware output.

<h2>Circuit Diagram</h2>


---

##  Applications

- Smart Home Automation
- Smart Offices
- Home Security Systems
- Smart Buildings
- Energy Management
- Industrial Automation

---

##  Advantages

- Low cost
- Easy to build
- Energy efficient
- Improves home safety
- Automatic appliance control
- Scalable and customizable

---

## ⚠ Limitations

- Requires continuous power supply.
- Sensor accuracy depends on environmental conditions.
- Limited functionality without Wi-Fi connectivity.

---

## 🔮 Future Enhancements

- ESP8266/ESP32 Wi-Fi integration
- Mobile application control
- Voice control using Google Assistant or Alexa
- Cloud data logging
- AI-based automation
- Real-time notifications

---

##  Learning Outcomes

- Arduino Programming
- Sensor Interfacing
- Relay Control
- Embedded Systems
- IoT Fundamentals
- Home Automation Design

---

##  Author

**Kratika Singh Rathour**

B.Tech Computer Science & Engineering

Hindustan College of Science and Technology, Farah, Mathura

---

## License

This project is developed for educational purposes only. It is free to use, modify, and distribute for learning and research.
