# ❤️ Heart Smart Tech  
## IoT-Enhanced Smart Healthcare Monitoring with Energy Efficient Data Compression

![GitHub Repo stars](https://img.shields.io/github/stars/ArpanPramanick/Finay-Yr-Project-Btech?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/ArpanPramanick/Finay-Yr-Project-Btech?style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/ArpanPramanick/Finay-Yr-Project-Btech?style=for-the-badge)

---

## 📌 Overview

Heart Smart Tech is an IoT-based smart healthcare monitoring system designed for continuous health parameter monitoring using ESP32 microcontrollers and multiple biomedical sensors.

The project focuses on:

- Real-time patient monitoring
- Energy-efficient sensor communication
- Data compression techniques
- Smart alert routing to nearest hospitals
- Reduced bandwidth consumption
- IoT-enabled healthcare automation

This system integrates biomedical sensors with ESP32 and optimized data transmission algorithms to improve healthcare response efficiency.

---

# 🧠 Key Features

✅ Real-time health monitoring  
✅ ESP32-based wireless communication  
✅ Pulse & ECG monitoring  
✅ Temperature & humidity sensing  
✅ Smart anomaly detection  
✅ SOS emergency alert system  
✅ Energy-efficient data transmission  
✅ Data compression using deviation-based encoding  
✅ Routing to nearest hospital  
✅ IoT + Healthcare integration

---

# 🏗️ System Architecture

![Architecture](images/architecture.png)

---

# 🔌 Sensors Used

| Sensor | Purpose |
|---|---|
| MAX30100/MAX30102 | Pulse & Oxygen Monitoring |
| AD8232 | ECG Monitoring |
| DS18B20 | Body Temperature |
| DHT11 | Temperature & Humidity |
| HC-SR04 | Height Measurement |
| Weight Sensor | Weight Monitoring |
| ESP32 | Central Controller |

---

# 📡 Sensor Connectivity

![Connectivity](images/sensor_connectivity.png)

---

# 🧍 Human Body Sensor Placement

![Body Sensors](images/body_sensor.png)

---

# 🔄 Data Transmission Workflow

![Data Flow](images/data_flow.png)

---

# ⚡ Energy Consumption Analysis

The proposed compression algorithm significantly reduces transmission energy consumption compared to traditional sensor transmission methods.

![Energy Graph](images/energy_graph.png)

---

# 🧪 Proposed Compression Logic

The project uses:

- Boolean flag arrays
- Deviation arrays
- Threshold-based transmission
- Reduced bit transmission model
- Smart anomaly filtering

Instead of transmitting complete sensor values continuously, only abnormal deviations are transmitted.

This dramatically reduces:

- Power consumption
- Bandwidth usage
- Sensor communication overhead

---

# 🚨 Emergency Alert Mechanism

If abnormal sensor readings persist:

1. ESP32 validates anomaly
2. Local data centre receives alert
3. SOS packet generated
4. Modified reverse Dijkstra routing applied
5. Alert forwarded to nearest hospital

---

# 🛠️ Technologies Used

- ESP32
- Arduino IDE
- IoT
- Wireless Sensor Networks
- Embedded C++
- Biomedical Sensors
- Data Compression
- GSM Communication
- IFTTT
- Cloud Database

---

# 📂 Project Structure

```bash
├── code/
├── docs/
├── hardware/
├── images/
├── results/
└── research/
```

---

# 📄 Research Paper / Report

Full project report available here:

📘 [Project Report](docs/Project_Report.pdf)

---

# 🚀 Future Improvements

- AI-based disease prediction
- Cloud analytics dashboard
- Mobile application
- MQTT integration
- Edge AI processing
- Deep learning for ECG analysis

---

# 👨‍💻 Team Members


- Arpan Pramanick
- Arpan Nandi
- Ayan Sarkar
- Ayush Kumar

---

# 🎓 Institution

Haldia Institute of Technology  
Department of Information Technology

---

# 📜 License

This project is developed for academic and research purposes.

---

# ⭐ If you like this project

Give this repository a ⭐ on GitHub.