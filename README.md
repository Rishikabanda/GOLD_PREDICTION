<h1>Gold Price Prediction</h1> </br>
This project focuses on predicting gold prices using historical financial data. We leverage machine learning techniques to build a predictive model that learns patterns from various economic indicators to forecast future gold prices.</br>
<h2>📂 Project Structure</h2> </br>
GOLD_ML.project.ipynb   # Main notebook with EDA, preprocessing, and model training </br>
README.md               # Project overview and instructions </br>
gold_data.csv           # (Assumed) dataset with gold prices and features </br>
<h2>## 📌 Objective</h2> </br>
To build a machine learning model that can predict gold prices using relevant financial indicators such as: </br>
- SPX (S&P 500 index) </br>
- Oil prices </br>
- USD rates </br>
- Inflation-related metrics </br>

<h2> 🔍 Workflow </h2> </br.

<h4> 1. 📥 Data Collection </h4> </br>

Historical gold price data along with SPX, oil, USD, and other features are used. </br.
<h4> 2. 🧹 Data Preprocessing </h4> </br>

- Handling missing values </br>
- Feature selection</br>
- Scaling numerical features</br>
<h4> 3. 📊 Exploratory Data Analysis (EDA) </h4> </br>

Visualizations are used to understand correlation and trends in features. </br>

<h4> 4. 🤖 Model Building </h4> </br>

```python</br>
from sklearn.ensemble import RandomForestRegressor
model = RandomForestRegressor()
model.fit(x_train, y_train)
```
<h4> 5. 📈 Model Evaluation </h4> </br>

Metrics such as **R² Score** and **Mean Absolute Error** are used to evaluate model performance.</br>
<h2>✅ Results</h2> </br>

- The Random Forest model demonstrated strong predictive performance.</br>
- Key features like SPX and Oil prices showed high correlation with gold prices.</br>
- Visualization and residual analysis confirm the model's robustnes</br>
<h2>💡 Future Improvements</h2> </br>

- Hyperparameter tuning</br>
- Try other regression models </br>















