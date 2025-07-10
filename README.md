# Flipkart CSAT Prediction 📦🤖

This project uses machine learning and NLP to predict customer satisfaction (CSAT) based on Flipkart's customer support interaction data.

## 🔍 Project Features
- Sentiment analysis using TextBlob
- ML model training (XGBoost, Random Forest, Logistic Regression)
- CSAT class prediction (High/Medium/Low)
- Feature importance visualization
- Hypothesis testing for business insights

## 📁 Files
- `Flipkart_CSAT_Advanced.ipynb` – Main project notebook
- `best_model.pkl` – Trained XGBoost model
- `README.md` – Project description
- `requirements.txt` – Dependencies

## 📊 Sample Visualizations

### 🔹 Model Performance
![Model Performance](Model_Performance.png)

### 🔹 Feature Importance
![Feature Importance](Feature_Importance.png)

### 🔹 CSAT Score Distribution
![CSAT Distribution](Distribution_of_CSAT_scores.png)

### 🔹 CSAT Score vs Agent Shift
![CSAT Score vs Agent Shift](CSAT_scores_vs_Agent_Shift.png)

### 🔹 Response Time vs CSAT Score
![Response Time vs CSAT Score](Response_Time_vs_CSAT_score.png)

### 🔹 Average CSAT Score by Category
![Average CSAT Score by Category](Average_CSAT_score_by_category.png)

## 🔹 Average CSAT Score by Sub Category
![Average CSAT Score by Sub Category](Average_CSAT_score_by_sub-category.png)

### 🔹 Sentiment Score vs CSAT
![Sentiment Score vs CSAT](Sentiment_Score_VS_CSAT.png)

### 🔹 CSAT Score vs Agent Tenure
![CSAT Score vs Agent Tenure](CSAT_score_VS_agent_tenure.png)

### 🔹 CSAT Score by Channel
![CSAT Score by Channel](CSAT_score_by_channel.png)


## 🚀 How to Run
```bash
pip install -r requirements.txt
streamlit run csat_app.py



