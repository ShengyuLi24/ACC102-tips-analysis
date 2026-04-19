# Restaurant Tips Analysis – What Affects Tipping Behavior?

## 1. Problem & User
**Problem:** Restaurant operators want to know: Do dining hours, customers' smoking habits,the number of diners and gender affect the tip ratio? How to optimize service strategies?
**User:** Restaurant manager and waiter training department.

## 2. Data Source
- **Source:** Seaborn built-in 'tips' dataset (originally from a restaurant server's records)
- **Access Date:** 2026-04-15
- **Key fields:** total_bill, tip, sex, smoker, day, time, size

## 3. Methods (Python steps)
1. Load dataset using `sns.load_dataset('tips')`
2. Calculate tip percentage = tip / total_bill * 100
3. Group by time, smoker, sex to compare average tip percentage
4. Visualize with bar charts and scatter plots

## 4. Key Findings
- 🍽️ **Dinner** gets higher tip percentage (16.5%) than lunch (14.7%).
- 🚬 Non-smokers tip slightly more (15.8%) than smokers (15.1%).
- 👥 Larger parties (5-6 people) tend to tip higher absolute amount, but percentage is similar.
- 👫 Gender difference is minimal.

## 5. How to Run
```bash
pip install -r requirements.txt
jupyter notebook analysis.ipynb

## 6. Limitations & Next Steps
Data only from one restaurant in the US (1990s?).
No information on service quality or customer income.
Next: collect more recent data from multiple locations, add weather or day-of-week analysis.
