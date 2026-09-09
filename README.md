# Crypto Payment Transaction Analytics

An interactive Power BI dashboard analyzing crypto payment transactions, payment methods, cryptocurrencies, geographic performance, and transaction trends.

## 📊 Project Overview

This project explores a synthetic crypto-payment transaction dataset to demonstrate how business transaction data can be transformed into an interactive analytical dashboard.

The dashboard focuses on transaction performance, payment-method success rates, cryptocurrency activity, geographic distribution, and changes in transaction volume over time.

## 🎯 Business Objectives

The analysis was designed to answer questions such as:

- How much transaction volume is being processed?
- What is the overall transaction success rate?
- Which payment methods perform best?
- Which cryptocurrencies have the highest transaction activity?
- Which countries generate the most transaction volume?
- How does transaction volume change over time?
- Where are failures concentrated?
- What KPIs should management monitor?

## 📈 Dataset

The dataset contains:

| Metric | Value |
|---|---:|
| Transactions | 75,000 |
| Transaction Volume | €18.84M |
| Countries | 20 |
| Payment Methods | 10 |
| Cryptocurrencies | 10 |
| Success Rate | 91.5% |
| Average Transaction | €251.25 |
| Highest Monthly Volume | €1.62M |

> **Note:** The dataset is synthetic and does not contain proprietary or confidential customer data.

## 💡 Key Insights

The dashboard provides analysis of:

- Transaction success and failure performance
- Total and average transaction value
- Cryptocurrency transaction activity
- Payment-method performance
- Geographic transaction distribution
- Monthly and weekly transaction trends
- High-volume markets and transaction segments

## 🛠️ Tools & Technologies

- **Power BI**
- **DAX**
- **Data Modeling**
- **Data Visualization**
- **KPI Development**
- **Business Intelligence**

## 🧩 Data Model

The Power BI model uses a dimensional structure with a central transaction fact table and supporting dimensions.

Main tables include:

- `FactTransactions`
- `DimCountry`
- `DimCrypto`
- `DimCurrency`
- `DimCustomer`
- `DimDate`
- `DimPaymentMethod`
- `DimStatus`

This structure supports filtering and analysis across transactions, countries, cryptocurrencies, payment methods, customers, dates, and transaction status.

## 📐 DAX & KPI Analysis

Key measures developed for the dashboard include:

- Total Volume EUR
- Total Transactions
- Completed Transactions
- Failed Transactions
- Success Rate
- Failure Rate
- Average Transaction EUR
- Highest Monthly Volume
- Highest Volume Month

These measures are used throughout the dashboard to provide interactive KPI and trend analysis.

## 🖥️ Dashboard

The Power BI report contains four analytical pages:

### 1. Transaction Performance Overview

Provides a high-level overview of transaction volume, transaction count, success/failure performance, and key KPIs.

### 2. Crypto Currency Analysis

Analyzes transaction activity across different cryptocurrencies.

### 3. Country & Payment Analysis

Examines geographic performance and payment-method activity, including transaction volume and success rates.

### 4. Time & Trend Analysis

Analyzes transaction volume and status over time using monthly and weekly trends.

## 📷 Dashboard Screenshots

### Transaction Performance Overview

![Transaction Performance Overview](screenshots/Transaction%20Performance%20Overview.png)

### Crypto Currency Analysis

![Crypto Currency Analysis](screenshots/Crypto%20Currency%20Analysis.png)

### Country & Payment Analysis

![Country & Payment Analysis](screenshots/Country%20%26%20Payment%20Analysis.png)

### Time & Trend Analysis

![Time & Trend Analysis](screenshots/Time%20%26%20Trend%20Analysis.png)
## 🔗 Interactive Power BI Report

The interactive Power BI report is available through Power BI Service.

**Power BI Report:**  
[Open Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiM2YzYWMwN2QtM2RiOC00ZWE3LThjM2YtMWM4ZDg0NTY1YTlkIiwidCI6IjlhOWMwOTM4LWRjZWUtNGFlOS04ZmE1LTYyM2I0YWVkYTJkNyJ9)

## 🔍 Project Focus

This project demonstrates practical skills in:

- Business intelligence
- Data analysis
- Data modeling
- DAX calculations
- KPI design
- Interactive dashboard development
- Transaction analytics
- Cryptocurrency data analysis
- Business-oriented data storytelling

## ⚠️ Limitations

The dataset is synthetic and is intended for portfolio and analytical demonstration purposes.

Transaction values and cryptocurrency activity should therefore not be interpreted as real-world market or customer data.

## 👤 Author

**Raimondas Malinauskas**

Data & BI Analyst | Power BI | SQL | Python | Azure | Data Analytics
