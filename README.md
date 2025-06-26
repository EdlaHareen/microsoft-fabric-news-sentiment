# microsoft-fabric-news-sentiment
End-to-end news sentiment analysis using Microsoft Fabric, Synapse, Power BI, and Data Activator


# 📊 News Sentiment Analysis with Microsoft Fabric

This project is an end-to-end sentiment analysis platform built entirely on **Microsoft Fabric**. It automates the ingestion, transformation, enrichment, analysis, and visualization of real-time news data.

---

## 📌 Architecture Overview

![Architecture](assets/architecture.png)

**Tools Used:**
- 💡 Bing News API (Source)
- 🏗️ Data Factory (Ingestion + Scheduling)
- 💾 OneLake / Lakehouse (Delta storage)
- 🧹 Synapse Data Engineering (Data cleaning & transformation)
- 🤖 Synapse Data Science (Sentiment analysis using pre-trained model)
- 📈 Power BI (Interactive reporting)
- ⚡ Data Activator (Real-time alerts to Teams)

---

## 🛠️ Features

- Fully orchestrated daily data pipeline
- Delta table transformations
- Real-time sentiment analysis from news descriptions
- Dynamic Power BI dashboard:
  - KPI Cards
  - Sentiment distribution
  - Category/provider filters
  - Timeline trends
- Alerts sent to **Microsoft Teams** for key thresholds

---

## 📷 Sample Screenshots

### Dashboard
![Dashboard](assets/dashboard.png)

### Pipeline
![Pipeline](assets/pipeline.png)

---

## ⏱️ Automation

The pipeline is scheduled to run daily at **6:00 AM**, ingesting the latest articles and updating both the model and reports.

---

## 📁 Files

- `reports/News_Sentiment_Analysis.pbix` – Power BI report file
- `notebooks/` – Transformation and ML logic
- `assets/` – Visuals for architecture, dashboard, and pipeline

---

## 💬 Instructor Note (Transcript Excerpt)
> “We covered all the components in this architecture... starting from Data Factory, through Synapse, and finally building alerts with Data Activator integrated into Microsoft Teams…”

---

## 👨‍💻 Author
**Hareen Edla**

---

## 📎 License
[MIT](LICENSE)

