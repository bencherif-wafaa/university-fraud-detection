# 🎓 University Fraud Detection System

Real-time fraud detection using Apache Kafka and PySpark.

## What it does
Detects 3 types of fraud:
- Multiple location logins
- Exam cheating (same IP, multiple students)
- Account sharing (multiple devices)

## How to run
1. Install dependencies: pip install -r requirements.txt
2. Run setup: bash setup.sh
3. Start the system: bash start_kafka_system.sh

## Requirements
- Python 3.8+
- Java 11
- Apache Kafka
