# 📊 Employee Sentiment Analysis

## 📌 Project Overview
This project analyzes employee email communication data to evaluate sentiment and engagement within an organization.  
Using **NLP techniques**, **EDA**, and **predictive modeling**, we transform raw communication data into actionable insights such as sentiment distribution, employee rankings, flight risk identification, and sentiment forecasting.

---

## 🛠️ Tech Stack
- **Language**: Python  
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn, transformers (Hugging Face)  
- **Modeling**: DistilBERT for sentiment classification, Linear Regression for prediction  

---

## 🎯 Objectives
1. **Sentiment Labeling** – Classify each email as **Positive, Negative, or Neutral**.  
2. **EDA** – Explore sentiment distribution, trends over time, and employee activity.  
3. **Scoring** – Calculate monthly sentiment scores for employees.  
4. **Ranking** – Identify **Top 3 Positive** and **Top 3 Negative** employees each month.  
5. **Flight Risk** – Detect employees sending ≥ 4 negative emails in any rolling 30-day period.  
6. **Predictive Modeling** – Use regression to forecast sentiment scores from behavioral features.  

---

## 📊 Key Results

- **Sentiment Distribution**: Majority of emails were Positive, with fewer Neutral communications.  
- **Trends**: Negative sentiment spiked during specific periods, possibly linked to organizational stress.  
- **Top Employees**: Rankings highlighted consistently positive contributors and recurring negative senders.  
- **Flight Risks**: Several employees flagged for repeated negativity in short windows.  
- **Regression Insights**: Behavioral features (email count, average length) correlated with sentiment scores.  

---

## ✅ Conclusion

This project demonstrates how NLP and predictive analytics can be applied to workplace communication data to:

 - Monitor employee engagement.

 - Detect potential attrition risks.

 - Recognize high-performing employees.

 - Provide actionable insights for HR and management.
