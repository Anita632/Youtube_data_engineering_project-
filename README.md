# YouTube Data Analysis Project

## 📌 Overview
This project aims to securely manage, process, and analyse structured and semi-structured YouTube video data based on video categories and trending metrics. The solution is designed using a cloud-based architecture on AWS to ensure scalability, efficiency, and performance.

---

## 🎯 Project Goals
- **Data Ingestion** – Build a mechanism to ingest data from multiple sources  
- **ETL System** – Transform raw data into a clean and analytics-ready format  
- **Data Lake** – Store data centrally for easy access and management  
- **Scalability** – Ensure the system scales as data volume increases  
- **Cloud Integration** – Use AWS services to handle large-scale data processing  
- **Reporting** – Build dashboards to generate meaningful insights  

---

## ☁️ AWS Services Used

- **Amazon S3**  
  Object storage service used to store raw and processed datasets securely and at scale.

- **AWS IAM (Identity and Access Management)**  
  Manages access control and permissions for AWS services.

- **AWS Glue**  
  Serverless ETL service used for data discovery, transformation, and preparation.

- **AWS Lambda**  
  Used to run code without managing servers for automation and event-based processing.

- **AWS Athena**  
  Query service that allows SQL-based analysis directly on data stored in S3.

- **Amazon QuickSight**  
  BI tool used for building interactive dashboards and visual reports.

---

## 📂 Dataset Used
The dataset is sourced from Kaggle and contains statistics on daily trending YouTube videos across multiple countries.

**Dataset Features Include:**
- Video title  
- Channel title  
- Publish time  
- Tags  
- Views, likes, dislikes  
- Description  
- Comment count  
- Category ID (mapped using JSON files)  

🔗 Dataset Link:  
https://www.kaggle.com/datasets/datasnaek/youtube-new

---

## 📊 Key Use Cases
- Analyse trending content patterns  
- Identify high-performing categories  
- Understand engagement metrics (likes, views, comments)  
- Build dashboards for content insights  
- Perform scalable cloud-based analytics  

---

## 🛠 Tools & Technologies
- Python  
- SQL  
- AWS (S3, IAM, Glue, Lambda, Athena, QuickSight)  
- Jupyter Notebook  
- Kaggle Dataset  

---

