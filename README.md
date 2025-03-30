# Network Security: Real-Time Packet Sniffer & Threat Detection

## 📌 Project Overview

This project focuses on real-time network packet sniffing and cybersecurity threat detection through an AI model developed using advanced gradient boosting techniques. The model achieves an impressive accuracy of **99.88%**, ensuring robust protection against a wide range of network threats. The application features a user-friendly graphical interface for monitoring live network traffic and analyzing saved PCAP files, displaying packet summaries, threat predictions, and confidence levels.

## 🚀 Features

- **High Accuracy**: Achieves a 99.88% detection rate for cybersecurity threats.
- **Real-time Packet Sniffing**: Captures and processes network traffic on the fly.
- **AI-Based Threat Detection**: Utilizes a trained AI model to classify packets as benign or malicious.
- **Multi-Protocol Support**: Analyzes TCP, UDP, and other network protocols for anomalies.
- **Graphical User Interface**: Built with Tkinter to display live packet data, predictions, and dynamic confidence graphs.
- **PCAP Analysis**: Allows retrospective analysis of saved PCAP files.
- **Low Overhead**: Optimized for fast performance with minimal CPU and memory usage.

## 🔧 Installation & Setup

### Prerequisites

Ensure you have the following dependencies installed:

```bash
pip install numpy joblib scikit-learn scapy pandas matplotlib
```

### Clone the Repository

```bash
git clone https://github.com/your-repo/network-threat-detection.git
cd network-threat-detection
```

## 🏗 Usage

### 1️⃣ Run the Application

Execute the main script to launch the packet sniffer and threat detection GUI:

```bash
python main.py
```

### 2️⃣ Model Information

The trained AI model (developed using advanced gradient boosting techniques) is stored in `lightgbm_model.pkl`. This model is used to classify captured packets based on extracted features.

## 📊 Results & Performance

- **Accuracy**: 99.88%
- **Real-Time Detection**: Processes packets instantly for rapid threat identification.
- **Graphical Insights**: Displays dynamic prediction confidence in the GUI.
- **Retrospective Analysis**: Supports analysis of previously captured PCAP files.

## 📌 Future Improvements

- **Integrate with SIEM Tools**: Enhance monitoring with enterprise-grade security integrations.
- **Cloud Deployment**: Develop a cloud-based service with an API for broader accessibility.
- **Enhanced Feature Extraction**: Incorporate additional features and deep learning techniques for even better threat detection.

## 📜 License

This project is open-source and available under the **MIT License**.

---

Feel free to contribute and help make networks more secure!
```
