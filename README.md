# Customer Churn Prediction using ML and DL

## Summary
In this study, we performed customer churn analysis. The process steps are summarized as follows:

### 1. Data Exploration and Cleaning
- The dataset was loaded and inspected.
- Missing values were filled with the median for numerical data.
- Categorical variables were encoded using Label Encoding.
- Features (X) and the target (y) were defined.
- Data was scaled using StandardScaler.

### 2. Data Visualization
- A correlation matrix was plotted to observe relationships between variables.
- Customer churn distribution was visualized using a bar chart.

### 3. Machine Learning Prediction
- Data split into training and testing sets.
- A Random Forest model was trained to predict churn.
- Accuracy and classification report were used for evaluation.
- Confusion matrix plotted for model predictions.

### 4. Deep Learning Prediction
- A neural network (Sequential) was built.
- Model includes hidden layers with 64 and 32 neurons, with Dropout layers.
- Trained and evaluated using accuracy/loss plots and test predictions.

## Dataset
The dataset is loaded directly from GitHub:
```
https://github.com/Mosaad2010-star/customer-churn-prediction-ml-dl/blob/main/customer_churn.csv?raw=true
```

## Project Structure
- `predicting-customer-churn-using-ml-and-dl-models.ipynb`: Main notebook
- `README.md`: Project overview and summary
- `requirements.txt`: Python dependencies

---

© 2025 Mosaad Hendam
