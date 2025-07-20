# 📊 Sales Data Analysis with Pandas

This project is a beginner-friendly **Data Analysis** exercise using **Pandas** in Python.  
We analyze sales data to extract insights using GroupBy, Aggregations, and Visualization.

---

## 🔍 Dataset Information

- 📁 File Name: `Sales_Data_Pandas_Practice.csv`
- 💾 Contains: Region, Country, Order Date, Item Type, Sales Channel, Revenue, Profit, etc.
- 📈 Size: 1000+ records

---

## 🧪 Skills Used

- ✅ Data Cleaning
- ✅ Pandas GroupBy and Aggregation
- ✅ Sorting, Filtering, Multi-indexing
- ✅ Matplotlib (for optional visualizations)

---

## 📌 Key Tasks Performed

- Find **Top 3 Item Types** based on Profit
- Count **Number of Orders per Order Priority**
- Group Data by `Region` and `Order_Priority` to calculate:
  - Mean, Sum, Median of `Unit Cost` and `Total Revenue`
- Sort based on `Unit Cost` and analyze results

---

## 📁 Files in This Repo

| File Name                     | Description                          |
|------------------------------|--------------------------------------|
| `sales_data_analysis.ipynb`  | Jupyter Notebook with full analysis  |
| `Sales_Data_Pandas_Practice.csv` | Dataset used in the project       |

---

## ✨ Output Sample

```python
df.groupby(["Region", "Order_Priority"])[["Unit_Cost", "Total_Revenue"]].agg(["mean", "sum", "median"])
```

---

## 💼 Author

**Mayur Prajapati**  
🔗 [LinkedIn Profile](www.linkedin.com/in/mayur-data-analyst)  
🔗 GitHub: [@mayur-prajapati](https://github.com/mayur-prajapati)

---

## 📢 License

This project is for educational & portfolio purposes only.

