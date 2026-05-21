
# NeoGuardAI: Vital Monitoring using VSD Squadron Pro 🚀

AI-powered neonatal monitoring system using VSD Squadron Pro.

## 👩‍💻 My Contribution
- Embedded system integration
- Sensor interfacing
- UART communication
- Testing and debugging
- Documentation support

## 🧩 Problem
Newborns are highly vulnerable to:
- Hypothermia
- Apnea
- Hypoxia
- Cardiac abnormalities

Continuous monitoring systems are often expensive and inaccessible in low-resource settings.

## 💡 Solution
NeoGuardAI provides a low-cost real-time monitoring pipeline:

Sensors → Embedded System → UART → Python → AI Models → Risk Detection → Visualization

Block Diagram
<img width="1238" height="762" alt="image" src="https://github.com/user-attachments/assets/40e4acb5-6089-46d4-b023-b1727ef16b85" />

## ⚙️ Hardware Components
| Component        | Purpose                       |
| ---------------- | ----------------------------- |
| LM35DZ           | Body temperature sensing      |
| FSR402           | Respiration / apnea detection |
| MAX30102         | Heart rate & SpO₂ monitoring  |
| MCP3008          | ADC (SPI interface)           |
| VSD Squadron Pro | Embedded processing unit      |


## 🧠 Features
| Feature                            | Purpose                                                                    |
| ---------------------------------- | -------------------------------------------------------------------------- |
| Real-time physiological monitoring | Continuous monitoring of neonatal vital parameters                         |
| UART-based data streaming          | Serial transmission of sensor data for display and analysis                |
| Apnea detection                    | Identification of abnormal breathing interruption                          |
| Hypothermia detection              | Detection of low body temperature conditions                               |
| Hypoxia detection                  | Detection of low oxygen saturation levels                                  |
| AI-based ECG & EEG analysis        | Intelligent analysis of physiological signals for prediction and diagnosis |
| Live visualization dashboard       | Real-time graphical display of monitored parameters                        |


## 🛡 Detection Capabilities
- Hypothermia Detection
- Apnea Detection
- Hypoxia Detection
- Bradycardia Detection
- Seizure Prediction
- Arrhythmia Prediction

## 🔄 Data Flow

1. Sensors capture neonatal physiological signals  
2. Embedded firmware processes sensor data  
3. UART transmits data at 115200 baud  
4. Python logs data into CSV format  
5. AI models analyze ECG & EEG signals  
6. Risk score is generated  
7. Dashboard updates in real time  

---

## 🛠 Technologies Used

### Embedded
- Embedded C
- UART Communication
- SPI Interface
- MCP3008 ADC

### Software
- Python
- NumPy
- Pandas
- Matplotlib
- PySerial

### AI
- TensorFlow
- Keras
- CNN + LSTM

---

## 📊 AI Models

| Model            | Function               |
| ---------------- | ---------------------- |
| EEG CNN + LSTM   | Seizure Detection      |
| ECG CNN + LSTM   | Arrhythmia Detection   |


<img width="854" height="433" alt="image" src="https://github.com/user-attachments/assets/15cadc4b-7b9b-4f13-b86e-86d2dbb27819" />


Datasets:

- MIT-BIH Arrhythmia Dataset
- EEG Seizure Dataset (Kaggle)

---

## ▶️ How to Run

### 1️⃣ Firmware Setup
- Build and flash the firmware using **Freedom Studio**
- Ensure UART is configured at **115200 baud**

---

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt

````


### 3️⃣ Run Serial Logger

```bash
python python/data_logger/serial_logger.py


```
### 4️⃣ Run AI + Visualization Dashboard

```bash
python python/visualization/realtime_plot.py
```

---

## 📘 Setup Guide

Full setup instructions are available in:

```text
docs/setup_guide/README.md
```

---

## 📷 Results

### 📊 Vital Signs Dashboard

<img width="796" height="421" alt="image" src="https://github.com/user-attachments/assets/f78ecda4-6437-44d9-9bc9-b2bd21692c66" />

---

### 🧠 ECG & EEG Analysis

<img width="836" height="451" alt="image" src="https://github.com/user-attachments/assets/3ecddaff-b4ec-4c42-b374-90e6ad2cabe0" />

---

### 💻 Terminal Output

<img width="870" height="414" alt="image" src="https://github.com/user-attachments/assets/9c72b446-665b-450d-939b-21b61acc658a" />

---

### 📁 Data Logging

<img width="851" height="492" alt="image" src="https://github.com/user-attachments/assets/59dec022-3112-4955-80ff-8e7ad5714727" />

---

## 📂 Project Structure

- firmware/      → Embedded C source code
- python/        → Data logging, AI models, visualization
- docs/          → Setup guide and documentation
- pcb/           → PCB schematics and hardware design
- datasets/      → Sample CSV outputs and dataset references
- images/        → Output screenshots and result visuals

---

## ⭐ Why This Project Stands Out

* End-to-end embedded + AI system
* Real-time healthcare monitoring
* Multi-sensor fusion
* AI-assisted neonatal risk prediction
* Practical low-cost healthcare solution
* Embedded-to-cloud scalable architecture

---

## 👨‍💻 Author

Lokashsri — Embedded Systems, AI & Healthcare Monitoring Developer

---

## 👥 Team Project

Developed collaboratively as part of a neonatal healthcare monitoring system.

---

## 🚀 Future Improvements

* Cloud-based monitoring dashboard
* Mobile alert system
* Edge AI deployment
* Real-time hospital integration
* Advanced predictive analytics
* Wearable neonatal monitoring support

---


