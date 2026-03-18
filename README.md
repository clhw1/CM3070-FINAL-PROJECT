# CM3070 Final Project  
## Predictive Modelling of Emerging Online Trends For GMMTV Artists using Google Trends Data

### 📖 Overview
This project develops a predictive modelling framework to identify emerging online trends related to GMMTV artists and events using Google Trends data.

Google Trends provides search interest data, which acts as a proxy for measuring public attention and online engagement. The project applies data collection, feature engineering, and machine learning techniques to predict potential trend emergence.

---

### ⚙️ Methodology
The project follows a structured pipeline:

1. **Data Collection**
   - Google Trends data retrieved using PyTrends
   - Time-series search interest values collected for selected topics

2. **Feature Engineering**
   - Rolling averages
   - Rate of change
   - Lag features
   - Statistical indicators

3. **Model Training**
   - Supervised learning approach
   - Random Forest classifier used for prediction

4. **Evaluation**
   - Metrics: Precision, Recall, F1-score
   - Baseline comparison included
   - Performance visualised through plots

---

### 📊 Results
The model is able to identify patterns associated with emerging trends and demonstrates improved performance over baseline approaches. Feature importance analysis highlights key indicators contributing to trend prediction.

---

### ▶️ How to Run
1. Open the Jupyter Notebook (`.ipynb` file)
2. Run all cells from top to bottom
3. Ensure required libraries are installed:
   - pandas
   - numpy
   - scikit-learn
   - pytrends
   - matplotlib

---

### 📁 Repository Structure
- `*.ipynb` — Main project notebook  
- (Optional) datasets / supporting files  

---

### 📌 Notes
- The notebook is designed to run sequentially from top to bottom
- Outputs are included for easier review and reproducibility

---

### 👤 Author
Charissa Leong  
SIM-UOL Computer Science (Year 3)

