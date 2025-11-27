# Global Sales Data Analytics Project

This project is an end-to-end analysis of multi-year global sales data from both online and offline channels.  
The goal was to clean, merge, analyze, and visualize the dataset to extract valuable business insights about product performance, geographic trends, shipping efficiency, and weekly sales patterns.

---

## 📁 1. Project Structure

```text
📦 data-analytics-sales-project
├── Module_Task.ipynb
├── README.md
└── data/
    ├── events.csv
    ├── products.csv
    └── countries.csv
```


---

## 🧹 2. Data Cleaning

- Converted date columns into proper datetime format  
- Cleaned missing values (~6% missing country codes)  
- Fixed inconsistent types (strings, floats, ints)  
- Removed anomalies & duplicates  
- Merged all datasets into a unified analytical table  

---

## 📈 3. Key Business Metrics

- **Total orders:** ~1,250  
- **Countries covered:** ~200  
- **Product categories:** 12  
- Overall, the company generates **high revenue** and **strong positive profit**

---

## 🛍️ 4. Product Performance Insights

### ⭐ Top Revenue Categories  
- Office Supplies  
- Household  
- Cosmetics  
- Meat  

### ⭐ Top Profit Categories  
- Cosmetics  
- Office Supplies  
- Household  

### 🔻 Lowest-Performing Categories  
- Beverages  
- Fruits  

**Insight:** Profitability is concentrated in office, household, and cosmetics products.

---

## 🌍 5. Geographic Insights

### Regions
- **Europe** is the dominant market in revenue and profit  
- **Asia** performs significantly weaker  

### Countries
Top-performing examples:  
- Czech Republic  
- Ukraine  
- Bosnia and Herzegovina  
- San Marino  

**Insight:** Europe remains the most valuable strategic market.

---

## 🚚 6. Shipping Efficiency

- Average shipping times range between **20–28 days**  
- Fastest: Croatia, UK, Denmark, Estonia, Serbia  
- Shipping time varies by product type as well  

**Insight:** Improving logistics could increase sales and customer satisfaction.

---

## 📅 7. Weekly Sales Patterns

- Highest sales occur on **Monday** and **Wednesday**  
- Weekends show lower purchasing activity  

**Insight:** Marketing campaigns should target early-week peaks.

---

## 🧰 8. Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Google Colab  

---

## ▶️ 9. How to Run

1. Download all files from the `/data` folder  
2. Open `Module_Task.ipynb` in Google Colab or Jupyter Notebook  
3. Run all cells to reproduce the analysis  

---

## 👤 10. Author

**Mykyta Poliakov**  
Data Analytics student | Python | SQL | Visualization  
GitHub: https://github.com/XoTTa6bl4
