# Employee-Sentiment-Analysis# Employee Sentiment Analysis - README

## 🔍 Summary

This project analyzes internal employee messages to assess sentiment and engagement patterns using NLP and statistical modeling techniques.

---

## 🏆 Top 3 Positive Employees (Most Positive Monthly Scores)

| Month     | Employee                      | Score |
|-----------|-------------------------------|-------|
| 2001-06   | lydia.delgado@enron.com       | +12   |
| 2001-06   | john.doe@enron.com            | +10   |
| 2001-06   | jane.smith@enron.com          | +9    |

*(Note: Update values with actual data from `top_positive` DataFrame)*

---

## 🚩 Top 3 Negative Employees (Most Negative Monthly Scores)

| Month     | Employee                      | Score |
|-----------|-------------------------------|-------|
| 2001-06   | mark.james@enron.com          | -11   |
| 2001-06   | tanya.lee@enron.com           | -10   |
| 2001-06   | james.chen@enron.com          | -8    |

*(Note: Update values with actual data from `top_negative` DataFrame)*

---

## ⚠️ Flight Risk Employees

Employees flagged as **flight risks** (≥4 negative messages in a rolling 30-day period):

- lydia.delgado@enron.com  
- mark.james@enron.com  
- tanya.lee@enron.com  

*(Note: Replace with actual names from `flight_risk_list`)*

---

## 📊 Key Insights & Recommendations

- **Balanced Sentiment**: Most communication is neutral, though some employees show consistently positive or negative trends.
- **Engagement Signals**: Frequent positive contributors may be internal influencers or high performers.
- **Risk Identification**: Repeated negative communication in short time windows signals disengagement; proactive HR outreach is recommended.
- **Predictive Trends**: Message volume and structure (word/character count) are predictive of sentiment trends and can support future employee wellness tools.

---

## 📁 Files Included

- `notebook.ipynb` — Main analysis notebook
- `labeled_test.csv` — Labeled dataset with sentiment
- `visualizations/` — Folder containing all graphs and charts
- `Final_Report.docx` — Comprehensive documentation
- `README.md` — This summary file
