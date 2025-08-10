# Sales Prediction 📈💰

A machine learning project that predicts future sales based on factors such as advertising spend, target segment, and platform. This project demonstrates the application of regression and time series models to real-world business marketing strategies.

## 📊 Dataset

The project uses a **Sales dataset** containing:

* **Multiple sales records** with historical business data
* **Features**: advertising spend, target segment, platform, etc.
* **Target**: sales amount

## 🎯 Project Objectives

* [x] Prepare and clean the dataset for analysis
* [x] Perform feature engineering and selection
* [x] Train regression or time series models to forecast sales
* [x] Evaluate model performance using appropriate metrics
* [x] Analyze the effect of advertising changes on sales
* [x] Deliver actionable insights for marketing strategies

## 🛠️ Technologies Used

* **Python 3.x**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical computing
* **Matplotlib** / **Seaborn** – Data visualization
* **Scikit-learn** – Machine learning library

## 📁 Project Structure

```
sales-prediction/
├── Sales_Prediction.ipynb   # Main Jupyter notebook
├── README.md                # Project documentation
```

## 🚀 Getting Started

### Prerequisites

Ensure you have Python 3.7+ installed.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/ZoZ641e/CodeAlpha_intern_task.git
cd sales-prediction
```

2. Install required packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Run the Jupyter notebook:

```bash
jupyter notebook Sales_Prediction.ipynb
```

## 📈 Model Performance

### Linear Regression:

* **R² Score**: 98%
* **Coefficients**: [0.04405928, 0.1992875, 0.00688245]
* **Intercept**: 2.7089490925159065
* **Mean Squared Error (MSE)**: 3.7968


## 🔍 Key Features

### Data Preprocessing

* ✅ Handle missing values
* ✅ Transform categorical variables
* ✅ Normalize/scale numerical features

### Model Training

* Algorithm: Linear Regression
* Train/Test Split for evaluation
* Reproducibility with fixed random state

### Evaluation Metrics

* R² Score
* Mean Squared Error (MSE)
* Intercept
* Coefficients
* Visualization of predicted vs actual sales

## 📚 What You'll Learn

1. Data cleaning, transformation, and feature selection for forecasting
2. Building regression and time series models
3. Evaluating sales prediction models
4. Understanding how advertising factors affect outcomes
5. Creating insights to improve marketing strategies

## 🔧 Possible Improvements

* [ ] Experiment with more regression models (Ridge, Lasso, Random Forest)
* [ ] Perform hyperparameter tuning
* [ ] Add cross-validation for better generalization
* [ ] Deploy the model as a web application

## 📊 Sample Prediction

```python
# Example input
new_data = [[ad_spend, target_segment_encoded, platform_encoded]]
prediction = model.predict(new_data)
# Output: [predicted_sales]
```

## 📝 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.


