#  Smart Elevator Surveillance System  

![Arduino](https://img.shields.io/badge/Arduino-IDE-blue)  
![ESP32](https://img.shields.io/badge/ESP32-Microcontroller-orange)  
![IoT](https://img.shields.io/badge/IoT-Smart%20System-green)  
  

---

##  Project Overview  
The Smart Elevator Surveillance System is an IoT-enabled real-time monitoring solution for elevator safety.  
It detects cable faults, abnormal vibrations, current/voltage anomalies, and immediately notifies building management through Email/SMS alerts.  

This system enhances safety, reduces downtime, lowers maintenance costs, and enables predictive maintenance – making it ideal for smart buildings and Industry 4.0 adoption.  

---

##  Features  
-  Real-time monitoring of vibration, voltage, and current  
- Abnormal fault detection (open/short circuits, insulation breakdown, mechanical imbalance)  
- IoT-enabled alerts via Blynk, Email, and SMS  
- Compact & low-cost design (ESP32 + sensors)  
- Easy integration into existing elevator control systems  
- Future-ready: AI/ML-based predictive maintenance support  

---

## System Architecture  

<img width="1438" height="786" alt="image" src="https://github.com/user-attachments/assets/7b8d5a63-cdf5-49dc-b21b-53e52a272db7" />

---

## Hardware Components  
| Component | Description |  
|-----------|-------------|  
| *ESP32* | Microcontroller with Wi-Fi |  
| *ADXL345* | 3-axis accelerometer for vibration detection |  
| *ACS712* | Current sensor (motor current monitoring) |  
| *ZMPT101B* | Voltage sensor (AC voltage fluctuations) |  
| *GSM Module (SIM800L/SIM900A)* | SMS notification support |  
| *Buzzer/LED* | Local fault alerts |  

---

##  Software & Tools  
- Arduino IDE  
- Blynk IoT Platform  
- SMTP (for Email alerts)  
- GSM AT Commands / APIs (Twilio, Fast2SMS)  
- Python/Excel (for test data analysis)  

---

## ⚙️ Installation & Setup

Follow these steps to set up and run the Smart Elevator Surveillance System on your ESP32:

### 1️⃣ Clone Repository
```bash
git clone https://github.com/Shreeya146/smart-elevator-surveillance.git
```bash
#2️⃣ Open Code

Open Arduino IDE

Go to File → Open

Select the .ino file from the /code folde
