# **Twitter Data Pipeline – Extract, Transform, and Load (ETL) with Airflow & AWS S3**

## **Overview**
This project automates the extraction, transformation, and storage of **Elon Musk's tweets** using **Apache Airflow**. The pipeline fetches tweets via the Twitter API, applies transformations (such as filtering, cleaning, and sentiment analysis), and stores the processed data in an **AWS S3 bucket** for further analysis.

## **Tech Stack**
- **Apache Airflow** – Orchestrates the ETL workflow  
- **Twitter API / Tweepy** – Extracts tweets  
- **Pandas & NLTK** – Data transformation (cleaning, sentiment analysis)  
- **AWS S3** – Cloud storage for processed data  
