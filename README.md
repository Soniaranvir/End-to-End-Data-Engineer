# Bing News Data Analytics Platform

## 🚀 Project Overview
This repository showcases an **end-to-end data engineering pipeline** built entirely using **Microsoft Fabric**. The project focuses on ingesting, processing, and visualizing Bing News data, while also incorporating **sentiment analysis** and **real-time alerts**. The result is a robust news analytics platform that provides actionable insights into the latest news.

---

## 📂 Project Structure

```
├── DataFactory (Data ingestion pipelines)
├── SynapseDataEngineering (Transformation Notebooks)
├── SynapseDataScience (Sentiment Analysis Scripts)
├── PowerBI (Dashboard Reports)
├── DataActivator (Alert Configurations)
└── Documentation
```

---

## 🛠 Tools and Technologies
- **Microsoft Fabric**: Unified platform for data engineering and data science
- **Data Factory**: Data ingestion pipelines
- **OneLake**: Centralized storage for raw and processed data
- **Synapse Data Engineering**: Data transformation with Spark Notebooks
- **Synapse Data Science**: Pre-trained machine learning models for sentiment analysis
- **Power BI**: Data visualization
- **Data Activator**: Real-time alert configurations

---

## 🌟 Key Features

### 1. **Data Ingestion**
- Used **Data Factory** to connect to the Bing API.
- Extracted news articles in **JSON** format.
- Stored raw data in **OneLake’s Lake Database**.

### 2. **Data Transformation**
- Processed raw JSON files into structured **Delta tables**.
- Utilized **Spark Notebooks** in Synapse Data Engineering.
- Applied a predefined schema for better usability.

### 3. **Sentiment Analysis**
- Leveraged **Synapse Data Science** to analyze news descriptions.
- Used a pre-trained text analysis model to classify sentiment as:
  - Positive
  - Negative
  - Neutral
- Stored sentiment-enriched data as Delta tables in the Lake Database.

### 4. **Visualization with Power BI**
- Created a **dynamic dashboard** to display:
  - Latest news articles (published within the last 24 hours).
  - Sentiment distribution across news articles.
- Explored Copilot Feature: Leveraged the Copilot tool in Microsoft Fabric to auto-generate a dashboard. This feature provided a strong starting point, which was then customized to meet project requirements.
- Configured to update automatically with each pipeline run.

### 5. **Real-Time Alerts with Data Activator**
- Set up alerts for critical events (e.g., negative sentiment articles).
- Notifications delivered via **Microsoft Teams**.

---

## 🖼 Dashboard Highlights
- **Real-Time Updates**: Automatically fetches the latest news.
- **Sentiment Analysis Visuals**: Displays sentiment breakdowns.
- **Filterable Views**: Dynamic date filters for customized insights.
  
---

## 🏗️ Workflow

### Step-by-Step Process:
1. **Data Ingestion**: Fetch news data via Bing API and store it in JSON format.
2. **Data Transformation**: Convert raw JSON to structured Delta tables.
3. **Sentiment Analysis**: Classify news sentiment using pre-trained models.
4. **Visualization**: Create a Power BI dashboard for real-time insights.
5. **Alerting**: Configure alerts for significant updates using Data Activator.

---

## 📅 Automation
- **Pipeline Scheduling**: Orchestrated the entire workflow in Data Factory.
- **Daily Updates**: Scheduled pipeline to run at **6 a.m.** every day.

---

## ⚠️ Challenges
1. **Dynamic Filtering**:
   - Displaying news from the last 24 hours was initially challenging.
   - Resolved using calculated fields and advanced Power BI filters.

2. **Alert Configuration**:
   - Setting up real-time alerts in Data Activator required rigorous testing.
   - Successfully implemented Microsoft Teams notifications.

---

## 📈 Results
- **End-to-End Pipeline**: Fully automated and scalable.
- **Dynamic Insights**: Real-time dashboard to monitor news.
- **Actionable Alerts**: Instant notifications for critical events.

---

## 📋 Key Files
- **DataFactory**: Bing API pipeline configurations.
- **Synapse Notebooks**: Data transformation and sentiment analysis scripts.
- **Power BI Dashboard**: Visualizations and filters.
- **Alert Configuration**: Data Activator setup for real-time notifications.

---

## 🖇️ How to Run
1. **Setup Bing API**:
   - Configure API key in Azure.
   - Update credentials in Data Factory pipeline.
2. **Run Data Pipeline**:
   - Execute Data Factory pipeline for data ingestion.
3. **Execute Spark Notebooks**:
   - Transform JSON to Delta tables using Synapse Data Engineering.
4. **Perform Sentiment Analysis**:
   - Run Synapse Data Science scripts for sentiment classification.
5. **Visualize in Power BI**:
   - Open Power BI report and refresh to view the latest data.
6. **Test Alerts**:
   - Trigger alerts by adding negative sentiment articles.

---

### 🔗 ## Live Dashboard

Check out the live version of the dashboard [here](https://app.fabric.microsoft.com/reportEmbed?reportId=472bea21-396b-4596-b0b7-a52f94b9f782&autoAuth=true&ctid=eb34f74a-58e7-4a8b-9e59-433e4c412757).

You can access the live Co-Pilot feature dashboard [here](https://app.fabric.microsoft.com/reportEmbed?reportId=472bea21-396b-4596-b0b7-a52f94b9f782&autoAuth=true&ctid=eb34f74a-58e7-4a8b-9e59-433e4c412757).

> **Note:** Access to the dashboard may require appropriate permissions and login credentials.


