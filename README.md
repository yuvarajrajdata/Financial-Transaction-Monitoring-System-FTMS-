# Financial Transaction Monitoring System (FTMS)

## 📌 Overview
The Financial Transaction Monitoring System (FTMS) is an end-to-end data engineering project designed to process and analyze large-scale financial transaction data for fraud detection and business insights. The system processes records using a scalable lakehouse architecture and delivers curated insights for reporting and analytics.

The system is designed like a real banking data pipeline used for monitoring customer transactions and identifying suspicious activities.

---

## 💼 Business Use Case
In real banking and fintech systems, millions of transactions happen every day. This project simulates how companies:

- Detect fraudulent transactions in real time or batch mode  
- Identify unusual spending behavior of customers  
- Monitor high-value or suspicious transactions  
- Generate reports for risk and compliance teams  

This helps banks reduce fraud losses and improve customer security.

---

## ⚙️ Tech Stack

- Processing: Apache Spark  
- Orchestration: Apache Airflow  
- Storage: Apache Iceberg  
- Serving Layer: MySQL  
- Language: Python (PySpark)

---

## 📊 Dataset
- 12 columns including:
  - transaction details
  - customer info
  - device & location
  - payment method
  - fraud label

---

## 🔄 Pipeline Flow

1. Generate financial transaction dataset  
2. Process data using Apache Spark  
3. Clean and transform data  
4. Create fraud detection features  
5. Store processed data in Iceberg tables  
6. Load final summaries into MySQL  

---

## 🚨 Fraud Detection Logic

The system identifies suspicious transactions based on:

- High transaction amount  
- Unusual transaction time (late night activity)  
- New or unknown device usage  
- Rapid or repeated transactions  

A simple risk scoring method is used to mark potential fraud cases.

---

## 📈 Output

- Fraud transaction dataset  
- Customer spending summary  
- Location-wise transaction analysis  
- Daily financial insights  

---
## 📌 Future Enhancements

- Real-time streaming using Kafka  
- ML-based fraud detection model   
- API layer for serving analytics  

## 🎯 Goal of the Project

To simulate an industry-level financial monitoring system that demonstrates how large-scale data pipelines are built and used for fraud detection and analytics.

---

## 👨‍💻 Author
Yuvaraj – Data Engineer
