# 🍦 Ice Cream Sales Prediction using Simple Linear Regression

## 📌 Project Overview

This project uses **Simple Linear Regression**, a Machine Learning algorithm, to predict ice cream revenue based on temperature.

The main objective is to understand the relationship between temperature and ice cream sales and build a model that can predict revenue for a given temperature.

As temperature increases, the demand for ice cream generally increases. This project uses historical data to learn this relationship and make predictions.

## 🎯 Objectives

- Understand Simple Linear Regression.
- Load and explore the ice cream sales dataset.
- Visualize the relationship between temperature and revenue.
- Train a Linear Regression model.
- Predict ice cream revenue based on temperature.
- Evaluate model performance using different evaluation metrics.
- Visualize actual and predicted values.

## 📂 Dataset Information

**Dataset:** Ice Cream Sales Dataset

**Source:** YBI Foundation

**Dataset Link:** https://github.com/ybifoundation/Dataset/blob/main/Ice%20Cream.csv

The dataset contains 500 records and 2 columns.

| Column | Description |
|---|---|
| Temperature | Temperature in Celsius (°C) |
| Revenue | Ice cream sales revenue |

**Dataset Shape:** 500 rows × 2 columns

**Missing Values:** No missing values found.

## 🛠️ Technologies Used

- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## ⚙️ Project Workflow

The project follows these steps:

1. **Import Libraries:** Import the required Python libraries.
2. **Load Dataset:** Load the ice cream sales dataset using Pandas.
3. **Data Exploration:** Check the first and last five records, dataset shape, column information, statistical summary, and missing values.
4. **Data Visualization:** Create a scatter plot to understand the relationship between temperature and revenue.
5. **Train-Test Split:** Divide the dataset into 80% training data and 20% testing data.
6. **Model Building:** Create a Simple Linear Regression model using Scikit-learn.
7. **Model Training:** Train the model using the training dataset.
8. **Prediction:** Predict revenue using the testing dataset.
9. **Model Evaluation:** Evaluate the model using MAE, MSE, RMSE, and R² Score.
10. **Visualization:** Display the regression line and Actual vs Predicted graph.
11. **New Prediction:** Predict ice cream revenue for a temperature of 27°C.

## 📐 Linear Regression Equation

Simple Linear Regression uses the following equation:

**Y = mX + C**

Where:

- Y = Predicted Revenue
- X = Temperature
- m = Slope
- C = Intercept

The trained model produced the following values:

- **Slope:** 21.3840
- **Intercept:** 46.1783

Therefore, the regression equation is:

**Revenue = 21.384 × Temperature + 46.178**

## 📊 Model Evaluation

The model was evaluated using the following metrics:

| Evaluation Metric | Result |
|---|---:|
| Mean Absolute Error (MAE) | 19.20 |
| Mean Squared Error (MSE) | 652.49 |
| Root Mean Squared Error (RMSE) | 25.54 |
| R² Score | 0.9772 |
| R² Score (%) | 97.72% |

**Interpretation:**

The model achieved an R² score of approximately 97.72%, indicating that it explains a large proportion of the variation in ice cream revenue in the test dataset.

## 🔮 Sample Prediction

The model was tested with a new temperature value.

**Input:**
- Temperature = 27°C

**Predicted Output:**
- Ice Cream Revenue ≈ 623.55

This means that when the temperature is 27°C, the model predicts an ice cream revenue of approximately 623.55 units.

## 📈 Visualizations

The project includes the following visualizations:

1. **Temperature vs Ice Cream Revenue:** Shows the relationship between temperature and revenue.
2. **Regression Line:** Displays the actual data points and the fitted regression line.
3. **Actual vs Predicted Revenue:** Compares actual revenue values with predicted revenue values.

## 📁 Project Structure

```text
Ice-Cream-Sales-Prediction/
│
├── Ice_Cream_Sales_Prediction.ipynb
│
└── README.md
```

## 🚀 How to Run This Project

**Step 1:** Clone this repository.

```bash
git clone https://github.com/your-username/Ice-Cream-Sales-Prediction.git
```

**Step 2:** Open the project folder.

```bash
cd Ice-Cream-Sales-Prediction
```

**Step 3:** Install the required libraries.

```bash
pip install pandas numpy matplotlib scikit-learn
```

**Step 4:** Open the Jupyter Notebook.

```bash
jupyter notebook
```

**Step 5:** Open `Ice_Cream_Sales_Prediction.ipynb` and run all the cells.

You can also upload the notebook directly to Google Colab.

## 💡 Future Improvements

- Use multiple regression with additional features.
- Try other machine learning algorithms.
- Build a simple web application for predictions.
- Allow users to enter temperature and get predicted revenue.
- Improve model performance using additional relevant features.

## 📚 Learning Outcomes

Through this project, I learned:

- Basics of Machine Learning.
- Working with datasets using Pandas.
- Data visualization using Matplotlib.
- Training and testing a Machine Learning model.
- Understanding Simple Linear Regression.
- Making predictions using a trained model.
- Evaluating model performance using regression metrics.

Faculty GitHub ID:https://github.com/complexiota
Student GitHub Repository:https://github.com/dikshalande98/SLR_model_AD3227
