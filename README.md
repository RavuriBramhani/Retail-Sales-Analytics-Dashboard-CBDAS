# 📊 Retail Sales Analytics Dashboard (Azure + Power BI)

## 🚀 Project Overview

This project presents a **cloud-based retail sales analytics system** built using Microsoft Azure and Power BI. It analyzes sales data to generate meaningful insights and provides intelligent recommendations on whether products should be sold **online, offline, or both**.

The system follows a complete data pipeline from preprocessing to visualization, enabling **data-driven decision-making**.

---

## 🧠 Key Features

* 📈 Sales trend analysis over time
* 🌍 Region-wise performance analysis
* 🛒 Product category insights
* 🔄 Online vs Offline sales comparison
* 🤖 AI-based recommendation system (DAX)
* 🎯 Interactive Power BI dashboard

---

## ☁️ Architecture

```
Google Colab (Data Cleaning & Preprocessing)
                ↓
Azure Data Lake Storage Gen2 (Cloud Storage)
                ↓
Power BI Desktop (Visualization & Analytics)
                ↓
Interactive Dashboard + Recommendations
```

---

## 🛠️ Tech Stack

| Category        | Tools Used                   |
| --------------- | ---------------------------- |
| Data Processing | Google Colab, Python         |
| Cloud Platform  | Azure Data Lake Storage Gen2 |
| Analytics       | Power BI                     |
| Languages       | Python, DAX                  |

---

## 📂 Project Structure

```
Retail-Sales-Analytics/
│
├── data/
│   └── sales_data.csv
│
├── dashboard/
│   └── RetailDashboard.pbix
│
├── notebook/
│   └── data_preprocessing.ipynb
│
├── report/
│   └── project_report.docx
│
├── azure-template/
│   ├── template.json
│   └── parameters.json
│
└── README.md
```

---

## 📊 Dashboard Insights

The dashboard provides:

* 📌 Sales performance across regions
* 📌 Top-performing product categories
* 📌 Revenue trends over time
* 📌 Channel-wise comparison

---

## 🤖 Recommendation System

A rule-based system built using DAX:

* If **Online Sales > Offline Sales → Sell Online**
* If **Offline Sales > Online Sales → Sell Offline**
* If both are similar → **Sell Both**

---

## 🔗 Data Source

The dataset is stored in **Azure Data Lake Storage Gen2** and accessed directly in Power BI.

---

## ⚙️ How to Run the Project

1. Clone this repository
2. Open `.pbix` file in Power BI Desktop
3. Load dataset (if required)
4. Explore dashboard and insights

---

## 🎯 Outcomes

* Improved understanding of sales trends
* Better decision-making using data insights
* Efficient cloud-based analytics pipeline
* Cost-effective implementation

---

## 📌 Future Enhancements

* Machine learning-based prediction models
* Real-time data streaming
* Advanced customer segmentation
* Automated reporting system

---



---

## ⭐ Acknowledgement

This project was developed as part of academic coursework to demonstrate the integration of **cloud computing and data analytics**.

---

## 📢 Note

Azure resources were used for development and later removed to avoid unnecessary costs. All project files are available in this repository.
