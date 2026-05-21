NeoGuardAI: AI-powered Neonatal Monitoring using VSD Squadron Pro
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
<img width="1600" height="660" alt="image" src="https://github.com/user-attachments/assets/915da640-9275-497c-9a69-7ee76c9df2ab" />







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


## 🛠 Technologies Used

### Embedded
- Embedded C
- UART
- SPI

### Software
- Python
- NumPy
- Pandas
- Matplotlib
- PySerial

### AI
- TensorFlow
- CNN + LSTM

## 📂 Project Structure

firmware/      → Embedded C source code  
python/        → Data logging, AI models, visualization  
docs/          → Setup guide and documentation  
pcb/           → PCB schematics and hardware design  
datasets/      → Sample CSV outputs and dataset references  
images/        → Output screenshots and result visuals  

## 👨‍💻 Author
Lokash Sri — Embedded Systems, AI & Healthcare Monitoring Developer

## 👥 Team Project
Developed collaboratively as part of a neonatal healthcare monitoring system.

## 🚀 Future Improvements
- Cloud-based monitoring dashboard
- Mobile alert system
- Edge AI deployment
- Real-time hospital integration
- Advanced predictive analytics
