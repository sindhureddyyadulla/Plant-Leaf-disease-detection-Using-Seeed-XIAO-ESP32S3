# 🌿 Plant Leaf Disease Detection Using Seeed XIAO ESP32S3

This project integrates embedded systems and AI/ML to detect plant leaf diseases using sensors connected to the **Seeed XIAO ESP32S3** board. The results are processed using **Large Language Models (LLMs)** and visualized via a **React frontend**. The application not only detects diseases but also recommends appropriate remedies based on the diagnosis.

---

## 📸 Project Overview

- 🔌 **Hardware**: ESP32S3 board captures environmental and visual data from sensors/camera.
- 🧠 **AI/ML**: Trained LLM or lightweight model (e.g., TensorFlow Lite) classifies plant leaf diseases.
- 🌐 **Frontend**: React web app displays predictions and suggests remedies using API integration.
- 📶 **Connectivity**: Communication between ESP32 and frontend via Wi-Fi and RESTful APIs.

-----
## ✨ Features
- 📷 Capture leaf image and send to backend.
- 🤖 Classify leaf disease using ML model.
- 💬 Query LLM API for recommended remedies.
- 🧪 View results in real-time on React UI.
- 📶 Wi-Fi-based communication between frontend and ESP32.

---------
## 🧰 Tech Stack

### 🔧 Hardware
- Seeed Studio XIAO ESP32S3
- **Sensors**: Camera (for leaf images)
- **Power**: USB/Rechargeable Battery
- **Buzzer**: For Disease Detection
- **LED**: Green for NO Disease, Red for Disease.

### 💻 Software
- **Frontend**: React + Axios
- **Backend (ESP32)**: Arduino framework (ESP-IDF compatible)
- **ML Model**: TensorFlow / LLM (hosted or embedded)
- **Communication**: REST APIs over Wi-Fi

### Running the App 
- To start the development server
    **npm start**
### Runs the app in the development mode.
- Open http://localhost:3000 to view it in the browser.



  
