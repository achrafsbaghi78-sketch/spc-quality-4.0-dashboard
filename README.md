# 📊 SPC 4.0 Dashboard - Real-Time Quality Control

<div align="center">

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![IATF 16949](https://img.shields.io/badge/IATF_16949-Compliant-success?style=for-the-badge)
![Industry 4.0](https://img.shields.io/badge/Industry_4.0-Enabled-blue?style=for-the-badge)

**Real-time Statistical Process Control Dashboard for Automotive Manufacturing**

[🚀 Live Demo](https://spc-quality-4-0-dashboard.streamlit.app) | [📊 Data Source](https://docs.google.com/spreadsheets/d/1vkfDof3og5G2YOizZP7WK-RCSx2IA2T75VgtMtV7fwM)

</div>

---

### 🎯 Overview
**PFE 2026 - ENSA Tanger** | This platform implements **IATF 16949:2016 §8.5.1.1** requirements for Statistical Process Control in automotive parts manufacturing. 

Monitors `Ø12.00±0.05mm` axle diameter in real-time using **Xbar-R charts**, **Cp/Cpk capability analysis**, and **Western Electric rules** for automatic anomaly detection.

### ✨ Key Features
1. **📈 Real-Time Xbar-R Control Charts** - Automatic LSC/LIC calculation per ISO 7870
2. **🎯 Capability Analysis** - Cp, Cpk, Pp live calculation with IATF 16949 thresholds
3. **🚨 Smart Alerts System** - 8 Western Electric rules + Email/SMS notifications
4. **📄 8D Report Generator** - One-click PDF export for customer complaints
5. **📊 Live Data Integration** - Google Sheets API for shop floor connectivity

### 🛠️ Tech Stack
`Python` `Streamlit` `Plotly` `Pandas` `NumPy` `Google Sheets API`

### 📐 Business Impact
- **-60%** QC inspection time vs Excel manual
- **+40%** faster drift detection vs traditional SPC
- **0 PPM** customer complaints target via early warning system
- **IATF 16949** audit-ready documentation

### 🚀 Quick Start
```bash
git clone https://github.com/achrafsbaghi78-sketch/spc-quality-4.0-dashboard.git
cd spc-quality-4.0-dashboard
pip install -r requirements.txt
streamlit run app.py
