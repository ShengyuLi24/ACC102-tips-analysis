# Superstore Sales Analysis – Which Products and Regions Drive Profit?

## 1. Problem & User
**Problem:** A large retail supermarket wants to know: Which product categories have the highest profits? Which regions have made the greatest contributions? Has the discount strategy really increased profits?
**User:** The regional manager and purchasing team of the supermarket.

## 2. Data Source
- **Source:** Superstore dataset from Kaggle (via local CSV file)
- **Access Date:** 2026-04-15
- **Key fields:** Category, Sub-Category, Sales, Profit, Discount, Region, Order Date

## 3. Methods (Python steps)
1. Load CSV using pandas
2. Clean and inspect data
3. Aggregate profit by Category, Region, and Discount level
4. Visualize with bar charts and scatter plots

## 4. Key Findings
- 📦 **Technology** category generates the highest profit, while **Furniture** loses money.
- 🗺️ **West** and **East** regions contribute most profit; **South** lags behind.
- 📉 Discounts above 30% almost always lead to negative profit.
- 🏆 Top 5 most profitable sub-categories: Phones, Copiers, Chairs, Bookcases, Tables.

## 5. How to Run
```bash
pip install -r requirements.txt
jupyter notebook analysis.ipynb

## 6. Product Link / Demo Video
- **GitHub Repo:** https://github.com/ShengyuLi24/ACC102-superstore-analysis.git
- **Demo Video:** https://youtu.be/你的视频ID

## 7. Limitations & Next Steps
-The data years are relatively old
-There is a lack of individual customer information
-The relationship between discounts and profits is only correlation rather than causation
- Next: Collect updated data, incorporate customer repurchase rate analysis, and use Streamlit to create interactive dashboards
