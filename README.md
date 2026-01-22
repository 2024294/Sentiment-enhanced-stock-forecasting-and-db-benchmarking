# Sentiment-enhanced-stock-forecasting-and-db-benchmarking
Sentiment-enhanced stock price forecasting using SARIMAX and LSTM, combined with a comparative performance analysis of MySQL and MongoDB using YCSB and big data technologies.

# Sentiment-Enhanced Time Series Forecasting and Database Performance Analysis

## 📌 Project Overview

This project investigates stock price forecasting by integrating historical financial data with sentiment extracted from social media (tweets). Forecasts are generated for **Tesla, Apple, Amazon, Nvidia, and Netflix** over **1-day, 3-day, and 7-day horizons** using both classical and deep learning approaches.

In addition to forecasting, the project conducts a **comparative performance analysis of MySQL and MongoDB** using the **Yahoo! Cloud Serving Benchmark (YCSB)** to evaluate database suitability for big data applications.

---

## 🎯 Objectives

- Enhance stock price forecasting accuracy using sentiment-aware models
- Compare traditional statistical and deep learning time series models
- Evaluate relational vs NoSQL databases under different workloads
- Demonstrate scalable big data processing using Hadoop and Spark

---

## 🧠 Models and Methods

### Time Series Forecasting
- **SARIMAX**  
  - Incorporates sentiment scores as exogenous variables  
  - Auto ARIMA used for order selection

- **LSTM (Long Short-Term Memory)**  
  - Captures nonlinear temporal dependencies  
  - Hyperparameter tuning via GridSearchCV and RandomizedSearchCV

### Sentiment Analysis
- NLP-based sentiment extraction from tweets
- Sentiment scores aligned temporally with stock price data

---

## 🗄️ Big Data & Storage Technologies

- **Apache Hadoop (HDFS)**  
  - Storage of large-scale financial and social media datasets

- **Apache Spark (PySpark)**  
  - Distributed data preprocessing  
  - Sentiment extraction and model execution

---

## ⚙️ Database Performance Benchmarking

A detailed comparison of **MySQL** and **MongoDB** using **YCSB**:

- **Workload A** – Update-heavy workload  
- **Workload B** – Read-heavy workload  

### Evaluation Metrics
- Throughput
- Read latency
- Update latency

---

## 📊 Visualization & Dashboard

- Interactive dashboards built to visualize:
  - Forecasted vs actual prices
  - Model performance across horizons
  - Database benchmarking results
- Dashboard design follows **Tuftian visualization principles**

> 📁 HTML dashboard files must be downloaded locally to be viewed in a browser.

---

## 📁 Project Structure

