# 🕵️ Splunk Fraud Detection Dashboard

## 📄 Description
This project simulates a **Fraud Detection System** using **Splunk
The Splunk Fraud Detection Dashboard project demonstrates how data analytics and SIEM (Security Information and Event Management) capabilities can be leveraged to identify and visualize fraudulent activities within a simulated financial transaction dataset. The project was developed using Splunk Enterprise, focusing on designing an automated detection and visualization system that mimics real-world fraud monitoring in banking or e-commerce environments.

The dataset used in this project consisted of transaction logs containing attributes such as user ID, transaction time, amount, IP address, and geographical location. These logs were ingested into Splunk, where data cleaning, normalization, and indexing processes were applied. Using Splunk’s Search Processing Language (SPL), several correlation rules and detection queries were created to flag suspicious patterns — such as multiple failed login attempts, high-value transactions from new locations, and rapid repeat transactions within short time intervals.

A key objective of this project was to visualize these anomalies effectively. For this purpose, I built a Fraud Detection Dashboard featuring real-time panels that track user activity, transaction trends, alert frequency, and geographic heat maps. This enabled the identification of potential fraud indicators at a glance. In addition, I implemented automated alerts that trigger when certain thresholds are breached (e.g., multiple failed authentications or unusually high transaction volume), which helps simulate the workflow of a real SOC (Security Operations Center).

The dashboard also incorporates a risk scoring model, where each transaction is assigned a score based on its deviation from normal user behavior. High-risk transactions are automatically categorized and highlighted on the dashboard for further investigation.

Through this project, I developed hands-on experience in Splunk administration, data ingestion, SPL query writing, security event correlation, and dashboard design. The result is a functional and insightful fraud monitoring system that demonstrates how SIEM tools like Splunk can be applied to detect, analyze, and respond to financial fraud.
