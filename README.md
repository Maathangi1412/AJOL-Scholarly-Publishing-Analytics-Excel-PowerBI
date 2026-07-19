# 📊 AJOL Journal Analytics Dashboard

### Publication Trends, Open Access Distribution, and Journal Performance Analysis (2020 – March 2024)

---

## 📌 Project Overview

This project analyzes scholarly publication data from **African Journals Online (AJOL)** between **2020 and March 2024**. The dataset was cleaned and transformed using **Microsoft Excel** and **Power Query**, followed by data modelling and interactive dashboard development in **Power BI**.

The dashboard provides insights into publication trends, journal performance, Open Access distribution, geographical coverage, and journal quality based on the **Journal Publishing Practices and Standards (JPPS)** classification, supporting data-driven decision-making in scholarly publishing.

---

## 🎯 Project Objectives

- Analyze annual publication trends (2020–March 2024).
- Identify journals with the highest publication output.
- Compare Diamond and Non-Diamond Open Access journals.
- Analyze country-wise publication performance.
- Evaluate journal quality using JPPS classification.
- Build an interactive dashboard for publication analytics.

---

## 📂 Dataset Information

**Dataset:** AJOL (African Journals Online) Metadata Dataset

**Source:** Zenodo

**DOI:** https://doi.org/10.5281/zenodo.15383374

**Domain:** Scholarly Publishing | Research Analytics | Bibliometrics

**Analysis Period:** 2020 – March 2024

### Dataset Files

- ajol_pub.csv
- ajol_journals.csv
- ajol_pub_author.csv
- ajol_pub_keyword.csv

---

## 🛠 Tools & Technologies

- Microsoft Excel
- Power Query
- Power BI Desktop
- DAX
- Data Modelling

---

## 🔄 Data Preprocessing

The following preprocessing tasks were performed before visualization:

- Removed duplicate records
- Handled missing values
- Converted appropriate data types
- Filtered records (2020–March 2024)
- Standardized country and journal names
- Created Open Access classification
- Prepared Fact and Dimension tables
- Established relationships using a Star Schema

---

# 🗂 Data Model

The project follows a **Star Schema** consisting of one Fact table and multiple Dimension tables to improve data modelling efficiency and analytical performance.

<img width="1453" height="620" alt="image" src="https://github.com/user-attachments/assets/7b3a9eb0-2f31-4039-91c4-1823bad41fd4" />

---

# 📊 Dashboard Preview

<img width="1182" height="661" alt="image" src="https://github.com/user-attachments/assets/6a520a1e-4e27-4a54-9e5c-2f1184136a8a" />

---

## 📈 Dashboard Features

### KPI Cards

- Total Articles
- Total Journals
- Total Authors
- Total Keywords
- Countries Covered
- Diamond Journals

### Visualizations

- Annual Publication Trend
- Top 10 Journals by Article Count
- Open Access Distribution
- Top 10 Countries by Article Count
- Geographical Distribution of Journals
- JPPS Status by Open Access

### Interactive Features

- Publication Year Slicer
- Country Slicer
- Open Access Slicer
- Clear Filters Button
- Dynamic Cross-filtering

---

## 💡 Key Insights

- Analyzed **50,000+ research articles** from **739 journals** across **39 African countries**.
- Publication output increased steadily from **2020 to 2023**.
- **Pan African Medical Journal** recorded the highest publication output.
- **65.49%** of journals follow the **Diamond Open Access** publishing model.
- **Nigeria, South Africa, and Uganda** are the leading contributors to research publications.
- Most journals are classified as **1 Star** under the JPPS framework, indicating opportunities for quality improvement.

---

## 📌 Business Recommendations

- Improve editorial quality to achieve higher JPPS ratings.
- Encourage research participation from lower-contributing countries.
- Continue supporting the Diamond Open Access publishing model.
- Promote collaboration between established and emerging journals.

---

## 📁 Repository Structure

```
AJOL-Journal-Analytics-Excel-PowerBI
│
├── Dataset
│   ├── ajol_pub.csv
│   ├── ajol_journals.csv
│   ├── ajol_pub_author.csv
│   └── ajol_pub_keyword.csv
│
├── Power BI Dashboard
│   └── AJOL_Journal_Analytics.pbix
│
├── Documentation
│   └── AJOL_Journal_Analytics_Report.pdf
│
├── Images
│   ├── Dashboard.png
│   └── Data_Model.png
│
└── README.md

```

---

## 📚 Reference

Alonso-Álvarez, P. (2025). *AJOL Dataset: Structured Metadata of Articles and Journals Indexed in African Journals Online* (Version 2). Zenodo.

https://doi.org/10.5281/zenodo.15383374

---

## 👩‍💻 Author

**Maathangi**

Aspiring Data Analyst | Microsoft Excel | SQL | Power BI | Python

🔗 **GitHub:** https://github.com/Maathangi1412

🔗 **LinkedIn:** www.linkedin.com/in/maathangi-p-560266333


