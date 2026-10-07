# 🎧 Customer Support Performance & Ticket Analytics

![Python](https://img.shields.io/badge/Python-3873A9?style=for-the-badge&logo=python&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![Looker Studio](https://img.shields.io/badge/Looker_Studio-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

An end-to-end data analytics pipeline that cleans, models, and visualizes customer support ticket data to evaluate operational efficiency, SLA compliance, and customer satisfaction (CSAT).

---

## 📌 Business Overview & Problem Statement

Customer support operations face challenges in managing ticket resolution times and maintaining high CSAT across multiple channels. This project analyzes **8,469 customer support tickets** to identify support bottlenecks, evaluate resolution rates across product lines, and deliver actionable operational insights.

---

## 🛠️ Tech Stack & Architecture

- **Data Processing & Cleaning:** Python (Pandas, NumPy) via Google Colab / Jupyter Notebook.
- **Database & Data Modeling:** MySQL (XAMPP / phpMyAdmin) for aggregation and SQL Views creation.
- **Business Intelligence & Visualization:** Looker Studio (Executive Dark-Themed Dashboard).

---

## 🚀 Key Insights & Business Recommendations

1. **Balanced Omnichannel Distribution:** Support ticket volume is evenly distributed across all 4 channels (~25% each for Email, Phone, Chat, and Social Media), indicating a stable cross-channel support demand.
2. **SLA & Resolution Bottlenecks:** The overall Resolution Rate stands at **32.70%** with an average CSAT of **2.99 / 5.00**. SLA optimizations are required particularly for *Refund Requests* and *Technical Issues*.
3. **High-Issue Products:** Hardware products such as **Canon EOS**, **Nest Thermostat**, and **GoPro Hero** record the highest ticket volumes. Updating product FAQs and self-service troubleshooting guides is highly recommended.

---

## 📊 Dashboard Preview

*(Insert your dashboard screenshot image here)*

- **Interactive Dashboard:** [View Live Looker Studio Report](YOUR_LOOKER_STUDIO_LINK_HERE)

---

## 📁 Repository Structure

```text
├── dataset/
│   └── customer_support_tickets_clean.csv
├── notebooks/
│   └── customer_support_data_cleaning.ipynb
├── sql/
│   ├── schema_and_ingestion.sql
│   └── analytical_queries.sql
├── assets/
│   └── dashboard_preview.png
└── README.md