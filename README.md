# 🛒 Retail Data Pipeline (Databricks CE)

This is a simple project that moves and processes retail data using **Databricks Community Edition**.

---

## 💡 What it does

- Loads a CSV file with retail orders
- Cleans the data
- Saves it in 3 layers:
  - Bronze (raw data)
  - Silver (cleaned data)
  - Gold (KPIs and summary)

---

## 🔧 Tools used

- Databricks Community Edition (free)
- Spark
- Delta Lake

---

## 📊 KPIs calculated

- Sales by region
- Top 10 products
- Monthly sales
- Average shipping cost
- Total number of orders

---

## ▶️ How to run

1. Upload `data.csv` to `/FileStore/tables/` in Databricks
2. Run the notebooks:
   - Bronze: load raw data
   - Silver: clean the data
   - Gold: compute KPIs
3. Tables will be saved automatically

---

## 📁 Files

- `data.csv` — input data
- `bronze_ingest` — first notebook
- `silver_transform` — second notebook
- `gold_analytics` — third notebook

---

## ✅ Done

All data is processed and saved in Delta tables inside Databricks.
