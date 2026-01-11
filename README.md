# Industrial Emissions Compliance Automator 🏭

### 📋 Overview
In the Pulp & Paper industry, failing to monitor daily SO2 (Sulfur Dioxide) emissions can lead to significant regulatory fines and operational shutdowns. 

This project automates the environmental auditing process. Instead of manually checking Excel sheets, this Python tool:
1. **Ingests** daily emission sensor data.
2. **Validates** against legal thresholds (e.g., 120 mg/Nm3).
3. **Visualizes** trends for the month.
4. **Auto-generates** a "Priority Alert" report containing only the dates requiring immediate engineering intervention.

### 🛠️ Technology Stack
* **Python** (Data Processing)
* **Pandas** (Data Cleaning & Logic)
* **Matplotlib** (Trend Visualization)

### 📊 Key Features
* **Automated Violation Detection:** Logic filters that instantly flag "unsafe" days.
* **Visual Reporting:** Generates a trend line comparing Actual vs. Legal Limits.
* **Actionable Output:** Exports a clean `.csv` file (`High_Priority_Alerts.csv`) ready for the Environmental Manager.

### 🚀 Usage
```python
# Run the analysis
python Report_automation.py
