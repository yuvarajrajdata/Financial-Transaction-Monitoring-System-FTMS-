# Financial Transaction Monitoring System (FTMS)

## 📌 Overview
The Financial Transaction Monitoring System (FTMS) is an end-to-end data engineering project designed to process and analyze large-scale financial transaction data for fraud detection and business insights. The system processes 6M+ records using a scalable lakehouse architecture and delivers curated insights for reporting and analytics.


## 🧰 Tech Stack

- Processing: Apache Spark  
- Orchestration: Apache Airflow  
- Storage: Apache Iceberg  
- Serving Layer: MySQL  
- Language: Python / PySpark  

---

## 📊 Dataset

- Size: 6 Million Records  
- Columns: 12  

### Key Fields:
- transaction_id  
- customer_id  
- transaction_amount  
- transaction_type  
- merchant_category  
- transaction_time  
- location  
- device_id  
- account_balance  
- is_fraud  
- payment_method  
- currency  

---

## ⚙️ Features

- Large-scale transaction data processing (6M+ records)
- Fraud detection using rule-based anomaly logic
- Feature engineering for behavioral analysis
- Partitioned storage for optimized querying
- Automated pipeline using Airflow DAGs
- Aggregated reporting in MySQL

---

## 🔄 Pipeline Workflow

1. Generate synthetic financial transaction data  
2. Process data using Apache Spark  
3. Perform data cleaning and feature engineering  
4. Store processed data in Apache Iceberg tables  
5. Orchestrate workflows using Apache Airflow  
6. Load aggregated insights into MySQL  

---

## 🧠 Fraud Detection Logic

- High-value transaction threshold detection  
- Multiple transactions within short time window  
- Unusual location/device activity  
- Customer spending pattern deviation  

---

## 📈 Output Tables (MySQL)

- Customer spending summary  
- Fraud transaction records  
- Daily transaction analytics  

---

## 🎯 Project Goals

- Simulate real-world banking transaction systems  
- Build scalable data pipeline architecture  
- Demonstrate big data processing capabilities  
- Implement lakehouse storage concepts  

---

## 📌 Future Enhancements

- Real-time streaming using Kafka  
- ML-based fraud detection model  
- Dashboard using Power BI / Tableau  
- API layer for serving analytics  

---

## 👨‍💻 Author

Yuvaraj (Data Engineer)

---

## 📜 License

This project is for learning and demonstration purposes.
