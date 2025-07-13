# Azure Data Engineering Project

## 📌 Project Overview
This project demonstrates an **end-to-end data engineering solution** built using Microsoft Azure services. It covers data ingestion, storage, transformation, loading, and reporting for a simulated on-premise SQL Server dataset.  
Developed as part of a Hands-On to strengthen practical data engineering skills.

---

## 🏗️ Architecture Diagram

![Architecture Diagram](images/architecture.png)

---

## 💻 Tools & Technologies Used

- Azure Data Factory (ADF)
- Azure Data Lake Storage Gen2
- Azure Databricks (PySpark)
- Azure Synapse Analytics
- Microsoft Power BI
- Azure Key Vault
- Microsoft Entra ID

---

## 🔨 Implementation Steps

### 1. Data Ingestion
- Created linked services in **ADF** to connect to on-premise SQL Server.
- Built data pipelines to ingest multiple tables into **Azure Data Lake Storage Gen2**.

### 2. Data Storage
- Organized raw data in a **RAW container** in ADLS Gen2 with structured folders by table name.

### 3. Data Transformation
- Used **Azure Databricks** with PySpark notebooks to clean and transform raw data into curated datasets.
- Saved cleaned data in a **CURATED container** in ADLS Gen2.

### 4. Data Loading
- Loaded transformed data into **Azure Synapse Analytics** tables for optimized querying.

### 5. Reporting
- Built interactive dashboards in **Power BI** connected to Synapse Analytics for insights.

### 6. Governance & Security
- Managed secrets and connection strings securely using **Azure Key Vault**.
- Configured access control with **Microsoft Entra ID** for monitoring and governance.

### 7. End-to-End Testing
- Validated pipelines to ensure seamless data flow from ingestion to reporting.

---

## 📁 Repository Structure

```
azure-data-engineering-project/
│
├── images/
│   └── architecture.png
│
├── notebooks/
│   └── databricks_transformation.ipynb
│
├── pipeline_json/
│   └── adf_pipeline_export.json
│
└── README.md
```



---

## 📂 Sample Files Included

- `notebooks/databricks_transformation.ipynb` – PySpark data transformation notebook.
- `pipeline_json/adf_pipeline_export.json` – Exported ADF pipeline JSON definition.
- `images/architecture.png` – Project architecture diagram.


---

## 🎯 Learning Outcomes

✔️ Built scalable pipelines using Azure Data Factory  
✔️ Transformed data efficiently with PySpark in Databricks  
✔️ Designed data warehousing solutions in Synapse Analytics  
✔️ Created impactful Power BI dashboards  
✔️ Applied governance with Key Vault and Entra ID  
✔️ Strengthened practical cloud data engineering skills

---

## 📌 Author

**Sudhanshu Pukale**

## 🚀 Next Steps

- Automate deployment using ARM templates or Terraform  
- Integrate CI/CD for pipeline deployment  
- Enhance security with Managed Identities and Private Endpoints


