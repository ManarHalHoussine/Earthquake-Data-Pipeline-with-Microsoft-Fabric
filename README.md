# 🌍 Earthquake Data Pipeline with Microsoft Fabric

End-to-end **data engineering pipeline** that ingests and processes worldwide earthquake data from the **USGS API** using **Microsoft Fabric, PySpark, and Power BI**, following a **Bronze–Silver–Gold (Medallion) architecture**.

---

#  Project Overview

This project demonstrates how to build an **end-to-end data engineering pipeline** using **Microsoft Fabric** to ingest, process, and analyze worldwide earthquake data from the **USGS Earthquake API**.

The pipeline follows the **Medallion Architecture (Bronze, Silver, Gold)** to progressively transform raw data into **analytics-ready datasets**.

The final processed data can be used for **data analysis and visualization in Power BI**.

---

# Architecture

This project implements a **modern data engineering architecture** using Microsoft Fabric components.


### Microsoft Fabric Components

- **Data Factory** → Data ingestion  
- **Data Engineering (Spark / PySpark)** → Data transformation  
- **Lakehouse / Delta Tables** → Data storage  
- **Power BI** → Data visualization  

---

# Technologies Used

- **Python**
- **PySpark**
- **Microsoft Fabric**
  - Data Factory
  - Data Engineering
  - Lakehouse
- **Power BI**
- **USGS Earthquake API**

---

# Bronze Layer — Raw Data Ingestion

This layer ingests **raw earthquake event data** directly from the **USGS API**.

### Key Characteristics

- Raw data ingestion
- Minimal transformations
- Data stored in its original format
- Serves as the **source of truth**

### Tasks Performed

- Extract data from the USGS API  
- Ingest schema and raw dataset  
- Store raw data in the **Fabric Lakehouse**

---

# Silver Layer — Data Cleaning & Transformation

The **Silver Layer** processes the raw data from the Bronze layer and converts it into **clean and structured datasets**.

### Key Operations

- Data cleaning
- Data normalization
- Handling missing values
- Schema transformation
- Data consolidation

This layer prepares the data for **analytical workloads**.

---

# Gold Layer — Analytics Ready Data

The **Gold Layer** produces **business-ready datasets** optimized for **reporting and analytics**.

### Transformations Include

- Data aggregations
- Feature preparation
- Analytical dataset creation
- Optimized tables for **Power BI dashboards**

This layer powers the **final analytics and insights**.

---

# Data Source

The earthquake data is retrieved from the **USGS Earthquake API**, which provides real-time information about earthquake events worldwide.

Data includes:

- Earthquake magnitude
- Location coordinates
- Event timestamps
- Significance scores
- Geological metadata
---

# 👤 Author

**Manar HAL-HOUSSINE**
