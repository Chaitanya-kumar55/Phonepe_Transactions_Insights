# 📊 PhonePe Transaction Insights

## 🔍 Project Overview
This project provides data-driven insights into PhonePe’s transaction trends across India using data from the official [PhonePe Pulse GitHub Repository](https://github.com/PhonePe/pulse). It involves extracting data, storing it in a MySQL database, analyzing it using SQL and Python, and building a dynamic dashboard using Streamlit.

---

## 📌 Features

- 📥 Extract data from JSON files and insert into MySQL tables.
- 🧾 Perform SQL queries to understand transaction patterns.
- 📈 Visualize trends using bar, pie, and line charts.
- 🗺️ Map-level insights on state and district performance.
- 💻 Interactive dashboard using Streamlit.
- 🧠 Business insights for marketing, fraud detection, and user engagement.

---

## 🧰 Tech Stack

| Tool | Purpose |
|------|---------|
| `Python` | Data extraction, analysis, visualization |
| `MySQL` | Database for storing and querying transaction data |
| `Pandas, Plotly, Seaborn` | Data analysis and charting |
| `Streamlit` | Interactive data dashboard |
| `Git` | Version control |
| `VS Code` | IDE for development |

---

## 📊 EDA Highlights

- Top 10 states by transaction volume and count
- Registered users and app opens across quarters
- Popular payment methods
- Insurance transactions by region
- Quarterly transaction trends

---

## 💡 Business Use Cases

- 🎯 **Customer Segmentation** for better marketing
- 🕵️‍♂️ **Fraud Detection** via transaction patterns
- 🗺️ **Geographic Analysis** of app usage
- 🔄 **User Retention** strategies based on app opens
- 📈 **Product Growth** using transaction behavior

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/Chaitanya-kumar55/Phonepe_Transactions_Insights.git

2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Set up MySQL and import the schema:
   ```bash
   CREATE DATABASE phonepe;
   -- Then run all create table scripts

4. Load data into MySQL:
   ```bash
   python load_aggregated_transaction.py
   python load_map_user.py
   ...
   
6. Run the dashboard:
   ```bash
   streamlit run dashboard.py
   
   
