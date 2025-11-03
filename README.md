# 🏏 IPL Score Predictive Model

## 📘 Overview
This project predicts the **final IPL team score** during an ongoing match using a **Linear Regression model**.  
It analyzes live match data such as overs, runs, wickets, and recent performance to forecast the expected final total.

---

## 🎯 Objective
To develop a machine learning model that estimates a team’s **final score** based on current match progress.

---

## 📊 Dataset  
- **Features Used:**
  - Batting team  
  - Bowling team  
  - Overs completed  
  - Runs scored  
  - Wickets fallen  
  - Runs in the last 5 overs  
  - Wickets in the last 5 overs  
  - Final match total (target)

---

## ⚙️ Project Workflow
1. **Data Cleaning:** Removed incomplete and invalid records.  
2. **Encoding:** Applied One-Hot Encoding to team names for model understanding.  
3. **Data Split:**
   - Training data → IPL Seasons 2008–2016  
   - Testing data → IPL Seasons 2017–2019  
4. **Model Training:** Used Linear Regression to learn scoring patterns.  
5. **Model Evaluation:** Assessed performance using MAE and RMSE metrics.  
6. **Prediction:** Estimated final scores based on in-progress match data.

---

## 📈 Model Performance
| Metric | Value (approx.) |
|--------|------------------|
| **Mean Absolute Error (MAE)** | 12.11 |
| **Root Mean Square Error (RMSE)** | 15.84 |

✅ The model predicts within ±15 runs of the actual final score for most matches.

---

## 🧠 Key Insights
- Linear Regression effectively models scoring trends in IPL data.  
- Accuracy improves with overs and runs as features.  
- Simple yet interpretable approach suitable for early-stage sports analytics.

---

## 🛠️ Tools & Technologies
- **Language:** Python  
- **Libraries:** pandas, numpy, scikit-learn, matplotlib  
- **Technique:** Linear Regression  

---

## 🚀 Future Enhancements
- Add advanced models (Random Forest, XGBoost) for non-linear behavior.  
- Include player stats, venue, and pitch conditions.  
- Deploy as a **Streamlit dashboard** for live match predictions.

---

## 🏁 Conclusion
This project demonstrates how **machine learning** can be used to predict sports outcomes in real time.  
Using simple statistical modeling, it offers interpretable and accurate score predictions for IPL matches.

---

👨‍💻 *Built by [Amisha Jain]*  
