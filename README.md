# 🏥 Patient Satisfaction in Healthcare

A data-driven analysis of hospital service ratings and patient satisfaction.  
The goal of this project is to uncover which factors most strongly influence how patients evaluate their experience, and to predict satisfaction levels using machine learning.

---

## 📊 Project Summary

Using a structured survey dataset, this project explores how various aspects of hospital services—such as appointment scheduling, cleanliness, wait time, and communication—relate to overall patient satisfaction.

We apply exploratory data analysis, correlation analysis, and a Random Forest classification model to identify patterns and key drivers of satisfaction and dissatisfaction.

---

## 🎯 Objectives

- Analyze the distribution of satisfaction levels among patients.
- Explore which hospital service variables most impact satisfaction.
- Build a predictive model to classify satisfaction level using survey ratings.
- Identify key service areas for improvement through feature importance.
- Provide actionable recommendations to improve healthcare experiences.

---

## 🔧 Technologies Used

- **Python**: pandas, numpy, matplotlib, seaborn, scikit-learn
- **Jupyter Notebook** for development and documentation
- **RandomForestClassifier** for multiclass prediction

---

## 📁 Project Structure

```bash
patient_satisfaction_analysis/
├── data_raw/          # Original dataset
├── notebooks/         # Jupyter notebooks with analysis and modeling
├── requirements.txt   # Python dependencies
└── README.md          # Project documentation
```

---

## ✅ Results Summary
Most patients in the dataset reported being Unsatisfied, with very few Satisfied.

Features like waiting_rooms, appointment_time, and hospital_rooms_quality were most correlated with low satisfaction.

A Random Forest model achieved 66% accuracy, with good predictive performance for the dominant class.

Feature importance confirmed that environmental and administrative aspects heavily influence patient perception.

---

## 💡 Recommendations
Improve hospital infrastructure (especially waiting areas and rooms).

Reduce appointment delays and administrative inefficiencies.

Focus on doctor-patient communication to build trust and clarity.

---

## 🔮 Future Work
Integrate analysis of open-ended patient reviews using NLP and LLMs.

Explore class balancing techniques or model tuning to improve predictive performance.

Deploy a satisfaction prediction tool for hospitals to monitor in real time.
