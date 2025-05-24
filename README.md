# 🏥 Patient Satisfaction Analysis

This project analyzes a hospital patient satisfaction survey to identify which factors are most associated with high or low satisfaction levels.

## Objective

- Analyze the key factors influencing **overall patient satisfaction**.
- Understand the distribution of ratings across different variables.
- Identify patterns of dissatisfaction and satisfaction.
- Prepare the data for predictive modeling (classification and regression).

## Dataset

The dataset contains responses from a hospital satisfaction survey, including:

- **Target variable**: Overall satisfaction level (`satisfaction_in_rm`)
- **Independent variables**: Ratings of aspects like `time_waiting`, `hygiene`, `communication_with_dr`, etc., on a scale from 1 to 5.

## Project Structure

patient_satisfaction_analysis/  
├── data/                  # Raw and processed datasets  
│   ├── raw/               # Original raw data files  
│   ├── processed/         # Cleaned and transformed datasets  
├── notebooks/             # Jupyter notebooks with EDA, cleaning, and modeling  
├── scripts/               # Python scripts for data processing and modeling  
├── reports/               # Visualizations and analysis reports  
├── requirements.txt       # Project dependencies  
└── README.md              # Project overview and documentation  

## Process

1. **Data cleaning**
   - Renamed columns for clarity
   - Handled missing values and checked data ranges

2. **Value mapping**
   - Converted numeric ratings (1–5) to readable labels (`Satisfied`, `Unsatisfied`, etc.)

3. **Exploratory data analysis**
   - Distribution plots of the target and independent variables
   - Correlation heatmap to find relationships between variables
   - Average ratings grouped by satisfaction levels
   - Visualizations comparing satisfaction categories

4. **Predictive modeling**
   - Classification and regression models built to predict satisfaction
   - Model evaluation and feature importance analysis completed

## Conclusions

- Most variables show varied correlation with overall satisfaction, generally low to moderate.
- Certain aspects like appointment time and communication with doctors are more closely linked to dissatisfaction.
- The dataset offers useful insights for improving patient experience.

## Next Steps

- Extend analysis integrating patient reviews with NLP and sentiment analysis.
- Deploy models into a pipeline for real-time patient feedback prediction.

---

If you have any questions or want to collaborate, feel free to reach out!


