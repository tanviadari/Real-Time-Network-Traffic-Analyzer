# 🚀 Real-Time Network Traffic Analyzer

## 📌 Project Overview
This project captures real-time network packets using Scapy and detects anomalous traffic using the Isolation Forest machine learning algorithm.

It demonstrates real-time packet inspection, feature extraction, anomaly detection, and visualization of network behavior.


## 🛠️ Technologies Used
- Python
- Scapy (Packet Sniffing)
- Pandas
- NumPy
- Scikit-learn (Isolation Forest)
- Matplotlib



## ⚙️ Key Features
- Real-time packet capture
- Extraction of IP, TCP, UDP features
- Machine learning-based anomaly detection
- Traffic visualization
- Detection of suspicious network activity


## 🧠 Anomaly Detection Model
Isolation Forest algorithm is used to identify abnormal traffic behavior based on extracted packet features.



## ▶️ How to Run

1. Install dependencies:

pip install -r requirements.txt

2. Open the notebook:

network_traffic_analyzer.ipynb

3. Run all cells.

## 📷 Project Visualizations

### 🔹 Top Source IP Addresses
![Top Source IPs](images/top_source_ips.png)

---

### 🔹 Network Traffic Over Time with Anomalies
![Traffic Over Time](images/traffic_over_time.png)

---

### 🔹 System Architecture
![System Architecture](images/system_architecture.png)

---

### 🔹 Protocol & Packet Size Analysis
![Protocol Analysis](images/protocol_analysis.png)

## 💡 Technical Highlights

- Real-time packet capture using Scapy
- Feature engineering for network traffic analysis
- Unsupervised anomaly detection using Isolation Forest
- Data visualization using Matplotlib


## 📊 Future Improvements
- Add live dashboard (Streamlit / Flask)
- Integrate database logging
- Deploy as a monitoring tool
- Add more ML models for comparison



## 👩‍💻 Author
Tanvi Pentakota