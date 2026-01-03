# Well Anomaly Detection Using Machine Learning

## Overview
This project applies machine learning techniques to detect anomalies in oil & gas well data.  
Early anomaly detection is critical in drilling and production operations to prevent equipment failure, reduce non-productive time (NPT), and improve operational safety.

The model analyzes historical well parameters and flags abnormal behavior that may indicate potential issues such as pressure instability, flow irregularities, or sensor faults.

---

## Problem Statement
Oil and gas wells generate large volumes of time-series data.  
Manual monitoring is inefficient and prone to human error.

This project aims to:
- Automatically identify abnormal patterns in well data
- Assist engineers in early decision-making
- Demonstrate the application of ML in petroleum engineering workflows

---

## Dataset
- Source: Synthetic but physically plausible well sensor data
- Size: 1000 hourly records
- Features may include:
  - Standpipe Pressure
  - Flow rate
  - Temperature
  - ROP (Rate Of Penetration)
  - Mud Weight

(Data has been anonymized and simplified for academic and portfolio purposes.)

---

## Anomalies
Artificial anomalies were injected to simulate:
- Pressure Spikes
- ROP Drops
- Torque Surges
This simulates events such as bit wear, blockages or abnormal downhole resistance.

---

## Methodology 
1. Data preprocessing and cleaning
2. Feature scaling and normalization
3. Unsupervised / semi-supervised anomaly detection model
4. Threshold-based anomaly flagging
5. Visualization of detected anomalies

---

## Machine Learning Model
- Model Type: (e.g., Isolation Forest / Autoencoder / One-Class SVM)
- Reason for choice:
  - Effective for unlabeled anomaly detection
  - Handles nonlinear relationships
  - Suitable for industrial sensor data

---

## Results
- Successfully identified abnormal data points
- Demonstrated the feasibility of ML-based monitoring for well operations
- Results can support predictive maintenance and operational optimization

---

## Limitations
- Dataset size and realism
- Model performance depends on data quality
- Further tuning required for real-field deployment

---

## Future Improvements
- Integration with real-time streaming data
- Model retraining with field-labeled anomalies
- Deployment as a monitoring dashboard
- Extension to drilling and completion datasets

---

## Tools & Technologies
- Python
- NumPy, Pandas
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

## Author
**Kachi Anugwom**  
Petroleum & Gas Engineering | Machine Learning  

---

## Disclaimer
This project is for educational and portfolio demonstration purposes and does not represent live field operations.
