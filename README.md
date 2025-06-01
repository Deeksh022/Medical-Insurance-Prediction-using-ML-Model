# Medical-Insurance-Prediction-using-ML-Model

This project focuses on predicting medical insurance costs for patients using machine learning techniques. The prediction is based on several factors like age, BMI, smoking status, number of children, region, and gender. The project includes extensive exploratory data analysis (EDA) with insightful visualizations to understand the trends and relationships in the dataset before model training.

## 📊 Exploratory Data Analysis (EDA)

Several visualizations were created to gain insights from the data:

* ### **Age vs Charges**

  * **Graph Type**: Scatter Plot
  * **Purpose**: To examine how medical charges increase with age. The relationship appears more complex than linear.

* ### **BMI vs Charges**

  * **Graph Type**: Scatter Plot
  * **Purpose**: To analyze if a higher BMI correlates with higher medical costs. Outliers were visible among patients with very high BMI.

* ### **Smoker vs Charges**

  * **Graph Type**: Box Plot / Count Plot
  * **Purpose**: To visualize the stark contrast in medical costs between smokers and non-smokers. Smokers tend to incur significantly higher medical costs.

* ### **Children vs Charges**

  * **Graph Type**: Bar Chart
  * **Purpose**: To analyze whether the number of children affects medical costs. No clear linear trend was found.

* ### **Gender vs Charges**

  * **Graph Type**: Bar Chart
  * **Purpose**: To explore if gender has an impact on charges. The differences between male and female charges were minimal.

* ### **Region Distribution**

  * **Graph Type**: Pie Chart / Bar Chart
  * **Purpose**: To see the distribution of patients across different regions.

## 🧠 Machine Learning Model

* The dataset was preprocessed and split into training and testing sets.
* **Feature Encoding** was performed for categorical variables (e.g., gender, smoker, region).
* **Model Used**: Linear Regression (or the model used in the final cell of your notebook).
* The model was trained on the features to predict the `charges` column (i.e., the medical insurance cost).

## ✅ Final Prediction

The trained model was used to predict the medical charges for patients based on their personal attributes. Evaluation metrics (like Mean Squared Error or R² Score) were used to assess model performance, showing that the model reasonably predicts charges, especially highlighting the impact of smoking, age, and BMI on costs.

## 📁 Files

* `Predicting Medical Insurance Cost with Machine Learning.ipynb`: Jupyter Notebook containing the full workflow.
* `README.md`: Project overview and documentation.

## 🔧 Requirements

* Python 3.x
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

Install dependencies using:

```bash
pip install -r requirements.txt
```
