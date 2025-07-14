# 🌾 Agriculture Data Analysis Dashboard

An end-to-end data analytics pipeline that extracts agricultural datasets from AWS S3, processes them in Snowflake, and visualizes insights using Power BI.

---

## 📌 Project Overview

This project showcases a full data analytics workflow for agriculture-related parameters like:

- 🌧️ Rainfall  
- 💧 Humidity  
- 🌡️ Temperature  
- 🌱 Crop Yield  

---

## 🔄 Project Flow

```mermaid
graph TD
  A[AWS S3 Bucket<br>Raw Dataset] --> B[Snowflake<br>Data Warehousing]
  B --> C[Data Cleaning<br>& Transformation]
  C --> D[Data Modeling<br>with Views & Joins]
  D --> E[Power BI<br>Live Connection]
  E --> F[Interactive Reports<br>and Dashboards]
-----

## 🛠️ Tech Stack

| Component     | Tool Used          |
|---------------|--------------------|
| Cloud Storage | AWS S3             |
| Data Warehouse| Snowflake          |
| Visualization | Power BI           |
| Language      | SQL (Snowflake SQL) |

---

## 📌 Key Highlights

- ✅ Fully cloud-based end-to-end pipeline
- ✅ Live integration between Snowflake & Power BI
- ✅ Data grouped by ranges (e.g., rainfall levels, year buckets)
- ✅ Separate dashboards for each metric
- ✅ Clean, scalable architecture

---

## 📸 Dashboard Preview
<img width="1447" height="810" alt="image" src="https://github.com/user-attachments/assets/f51076c1-6cda-41df-90fc-a3bba28328db" />
<img width="1436" height="798" alt="image" src="https://github.com/user-attachments/assets/486bc0b0-e229-4a47-86cf-862d35705709" />
<img width="1426" height="799" alt="image" src="https://github.com/user-attachments/assets/49ee8815-eeea-49a6-960e-a069da6c7768" />



 
