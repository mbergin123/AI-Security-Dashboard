# 🛡️ AI Security Dashboard (SOC-Style Monitoring System)

An AI-powered security monitoring platform that collects endpoint telemetry, detects anomalies, scores risk, and generates concise, actionable security insights using a local AI model.

---

## 🔒 Note

This repository showcases the architecture and functionality of an AI-assisted security monitoring system.  
Core implementation details have been intentionally abstracted.

---

## 🎯 Overview

This project simulates a real-world SOC workflow:

- Endpoint telemetry collection  
- Threat detection engine  
- Risk scoring system  
- AI-assisted alert explanations  
- Real-time dashboard visualization  

---

## 🚨 Why This Matters

Modern SOC teams are overwhelmed with alerts and noise. This project demonstrates how AI can assist in triaging security events, prioritizing risks, and reducing analyst fatigue by automating parts of the detection and response workflow.

## 🧠 Architecture

Client Agent → FastAPI → Detection Engine → Risk Scoring → AI Model → Dashboard


---

# ⚙️ 1. Backend Server Setup

### Server Setup
![Server Setup](images/server1.png)

### Dependencies Installed
![Dependencies](images/server2.png)

### API Creation
![API](images/server3.png)

### Server Running
![Server Running](images/server4.png)

---

# 🖥️ 2. Client Agent

### Agent Setup
![Agent Setup](images/step1.png)

### Telemetry Collection
![Telemetry Code](images/step2.png)

### Initial Output
![Agent Output](images/step3.png)

### Fixing Issues
![Improved Output](images/step4fixip.png)

---

# 🔗 3. Communication

### Client Sending Data
![Client Sending](images/clientsent.png)

### Server Receiving Data
![Server Telemetry](images/telemetry.png)

---

# 🔍 4. Detection Engine

### Detection Rules
![Detection Rules](images/server1a.png)

### Client Validation
![Client Detection](images/client1b.png)

### Server Output
![Server Detection](images/server3b.png)

---

# 🧠 5. Risk Scoring

### Risk Output
![Risk Output](images/client3e.png)

---

# 🔧 6. Telemetry Enhancements

### Client Enhancements
![Client Enhancement](images/updateprocess_user_cl.png)

### Server Enhancements
![Server Enhancement](images/updateprocess_user_server.png)

### Validation
![Server Enhanced](images/server_process_update.png)

![Client Enhanced](images/client_process_test.png)

---

# 🌐 7. Port Parsing Improvement

![Port Parsing](images/updateports.png)

---

# 🧪 8. Security Simulation

### Simulated Open Port
![Fake Port](images/fakeport.png)

### Detection Triggered
![Detected](images/server_output.png)

### Server Response
![Response](images/server_response.png)

---

# 🗃️ 9. Data Storage

![Dataset](images/dataset1.png)

---

# 📊 10. Dashboard

### Setup
![Dashboard Setup](images/dashboard1.png)

### Code
![Dashboard Code](images/dashboard4.png)

### Output
![Dashboard](images/dashboard5.png)

---

# 🤖 11. AI Integration

### Install Model
![Ollama](images/ollama (2).png)

### Test Model
![Test](images/ollamatest.png)

---

### ⚠️ Initial Problem
![Bad AI](images/AI_Int_Test.png)

---

### ✅ Final AI Output
![Clean AI](images/ai-test2.png)

---

# 📊 12. Final Dashboard

![Final Dashboard](images/finalAIDashboard.png)

---

## 🧠 Skills Demonstrated

- FastAPI backend development  
- Streamlit dashboard design  
- Client-server architecture  
- Detection engineering  
- Risk scoring  
- AI model integration  
- Output filtering + guardrails  
- Security simulation  

---

## 🚀 Future Improvements

- Multi-agent support  
- Database integration  
- Authentication system  
- Real-time streaming  
- Automated response (SOAR)  

---

## 🏁 Summary

This project demonstrates a full pipeline:

Collect → Detect → Score → Explain → Visualize


---

## 📌 Status

✔ Functional  
✔ Tested  
✔ AI-integrated  
✔ Dashboard-ready  
✔ Portfolio-ready  

---

This repository is intended as a portfolio case study; source code and proprietary implementation details are not publicly included.
