# ESP32 Brushless Motor Telemetry and Thrust Measurement System

A custom embedded hardware system built around the ESP32 for real-time measurement, display, and logging of brushless motor performance parameters. This board integrates thrust sensing, current monitoring, voltage measurement, RPM sensing, temperature monitoring, onboard display, and SD card logging on a single PCB.

The project includes complete schematic design, PCB layout, and manufacturing-ready files.

---

## Features

- ESP32-based control and data acquisition  
- Load cell interface using HX711 for thrust measurement  
- Hall-effect current sensing  
- Battery voltage monitoring via ADC  
- Optical RPM sensing using IR photodiode  
- Temperature sensing capability  
- SSD1306 OLED display interface (I2C)  
- SD card logging support (SPI)  
- Integrated 3.3V power regulation  
- ESC interface connector  
- Fully custom PCB design  

---

## Hardware Overview

The ESP32 serves as the central controller and interfaces with multiple sensors and peripherals.

### Interfaces Used

| Peripheral | Interface |
|----------|-----------|
| HX711 Load Cell Amplifier | GPIO |
| Current Sensor | ADC |
| Voltage Measurement | ADC |
| Temperature Sensor | ADC |
| RPM Sensor | Digital Input |
| OLED Display | I2C |
| SD Card Module | SPI |
| ESC Interface | GPIO |

---


### Design Tools

- EasyEDA

---

## Repository Structure

```
.
├── Altium_PCB.pcbdoc        # Altium PCB design file
├── DXF_PCB.dxf              # Board outline file
├── Easy_EDA_PCB.json        # EasyEDA PCB source file
├── Gerber_Harsh_PCB.zip     # Manufacturing Gerber files
├── OBJ_PCB_Harsh_.zip       # 3D PCB model files
├── Schematic.pdf            # Circuit schematic
└── README.md
```

---

## Capabilities

The system measures and logs:

- Thrust  
- Voltage  
- Current  
- RPM  
- Temperature  

Data can be displayed on OLED and logged to SD card.

---

## Manufacturing

The repository includes complete fabrication files:

- Gerber files  
- PCB source files  
- Schematic  
- 3D model  


---

## Applications

- Brushless motor testing  
- Drone propulsion testing  
- Embedded telemetry systems  
- Motor performance analysis  



**Harsh Aditya**  
Embedded Systems and Hardware Design
