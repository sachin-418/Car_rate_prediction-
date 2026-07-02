# Car Price Prediction using Linear Regression

##  Project Overview

This project builds a **Linear Regression** model to predict the selling price of used cars based on various features such as company, car name, manufacturing year, fuel type, and kilometers driven.

The project includes complete data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and model serialization for future use.

---

##  Objective

Develop a machine learning model capable of accurately estimating the price of a used car using historical vehicle data.

---

##  Dataset

* **Dataset:** Quikr Used Car Dataset
* **Original File:** `quikr_car.csv`
* **Cleaned Dataset:** `cleaned_car.csv`
* **Target Variable:** `Price`

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* YData Profiling
* Pickle

---

##  Project Workflow

1. Import required libraries
2. Load the dataset
3. Perform Exploratory Data Analysis (EDA)
4. Generate an automated profiling report using YData Profiling
5. Clean inconsistent and invalid data
6. Handle missing values
7. Perform feature engineering
8. Build preprocessing pipelines
9. Split the dataset into training and testing sets
10. Train a Linear Regression model
11. Evaluate the model using R² Score
12. Save the trained model using Pickle

---

##  Data Cleaning

The following preprocessing steps were performed:

* Removed records with **"Ask For Price"**
* Converted `Price` to integer
* Converted `year` to integer
* Converted `kms_driven` to numeric values
* Removed unwanted text and commas from numerical columns
* Filled missing values in `fuel_type`
* Simplified car names by retaining the first three words
* Removed invalid and inconsistent records

---

##  Machine Learning Algorithm

**Algorithm Used:** Linear Regression

Linear Regression is a supervised machine learning algorithm used for predicting continuous numerical values by finding the best-fit line that minimizes the prediction error.

---

##  Model Evaluation

The model was evaluated using:

* R² Score (Coefficient of Determination)
* Train-Test Split
* Multiple Random State Evaluation for selecting the best model

The final model was trained using the random state that achieved the highest R² score.

---

##  Project Structure

```text
├── Untitled29(1).ipynb
├── quikr_car.csv
├── cleaned_car.csv
├── LinearRegressionModel.pkl
└── README.md
```

---

##  How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repository.git
```

### 2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn ydata-profiling
```

### 3. Open the notebook

```bash
jupyter notebook Untitled29(1).ipynb
```

or run the notebook in **Google Colab**.

---

##  Learning Outcomes

Through this project, I learned:

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Automated profiling using YData Profiling
* Feature engineering
* Building preprocessing pipelines with Scikit-learn
* Training and evaluating a Linear Regression model
* Understanding the R² evaluation metric
* Saving trained machine learning models using Pickle

---

##  Future Improvements

* Hyperparameter tuning
* Feature selection
* Compare Linear Regression with Ridge, Lasso, Decision Tree, and Random Forest Regression
* Deploy the model using Flask or FastAPI
* Build a web application for real-time car price prediction

---

##  Author

Developed as part of my Machine Learning learning journey to understand data preprocessing, regression analysis, and end-to-end machine learning model development using Python and Scikit-learn.
