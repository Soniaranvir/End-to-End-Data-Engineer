# 📰 **Bing News Analytics Platform Using Microsoft Fabric**

✨ **Overview**

This project demonstrates an **end-to-end data engineering pipeline** built with **Microsoft Fabric**, designed to process and analyze news data sourced from the **Bing API**. By utilizing tools like **Apache Spark**, **Pyspark**, **Delta Lake**, and **Power BI**, the pipeline ingests, transforms, performs sentiment analysis, and visualizes insights from news articles.

🔍 **Problem Statement**

News organizations and media platforms often face challenges in:

- Analyzing and categorizing large volumes of news data efficiently.
- Extracting meaningful insights from news content and provider data.
- Understanding sentiment trends in news articles.
- Building scalable, automated data pipelines for real-time insights.

This project addresses these challenges by processing Bing news data and extracting actionable insights using a fully automated pipeline.

⚙️ **Tools and Technologies Used**

- **Data Ingestion & Transformation**: Apache Spark, Pyspark
- **Data Storage**: Delta Lake (Azure Data Lake)
- **Data Orchestration**: Microsoft Fabric, Azure Data Factory
- **Sentiment Analysis**: Machine Learning models
- **Visualization**: Power BI

🔑 **Key Insights**

- **Sentiment Distribution**: Categorization of news articles by sentiment (positive, negative, neutral).
- **News Categories**: Popular categories such as Sports, Politics, and Business dominate the news feed.
- **Top News Providers**: Insights into leading news agencies and their article contributions.
- **Trending Topics**: Extracted key trends and topics based on article frequency.

🔢 **Data Cleaning and Transformation**

- **Flattened JSON**: Transformed nested JSON data from the Bing API into structured tables.
- **Data Extraction**: Extracted key fields like title, description, category, and publisher.
- **Incremental Loading**: Implemented incremental loading to keep the dataset up-to-date with the latest news articles.

🌄 **Power BI Visualizations**

Key Visualizations:
- **News Article Sentiment**: Pie chart showcasing the sentiment distribution across articles.
- **Top Categories by Article Count**: Bar chart visualizing the most frequent news categories.
- **Provider Analysis**: Table showing the contribution of top news providers.
- **Trending Topics**: Line chart highlighting the evolution of trending news topics.

🌐 **Lessons Learned**

- **Apache Spark** enables handling large datasets efficiently in a distributed environment.
- **Power BI** is effective for transforming raw data into insightful, interactive reports.
- **Microsoft Fabric** simplifies orchestration of complex data pipelines across various tools.

🚀 **Future Scope**

- **Real-Time Data Processing**: Implementing real-time data ingestion and processing for live news updates.
- **Advanced Sentiment Analysis**: Utilizing more sophisticated machine learning models to improve sentiment accuracy.
- **Interactive Dashboards**: Enhancing Power BI dashboards for more in-depth user interaction.

⚡ **Quick Links**

- **Dataset**: Bing News Dataset
- **SQL Queries**: Data Ingestion and Transformation Queries
- **Python Code**: Sentiment Analysis & Data Transformation Scripts
- **Power BI Visualizations**: Interactive Dashboard

---

\
