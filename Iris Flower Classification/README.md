# Iris Flower Classification 🌸

A machine learning project that classifies Iris flowers into three species (setosa, versicolor, virginica) using their physical measurements. This project demonstrates fundamental concepts in supervised machine learning and classification.

## 📊 Dataset

The project uses the classic **Iris dataset**, which contains:
- **150 samples** of Iris flowers
- **4 features**: Sepal Length, Sepal Width, Petal Length, Petal Width (all in cm)
- **3 target classes**: Iris-setosa, Iris-versicolor, Iris-virginica
- **50 samples** per species

## 🎯 Project Objectives

- [x] Load and explore the Iris dataset
- [x] Perform basic data preprocessing
- [x] Train a machine learning model for classification
- [x] Evaluate model performance using multiple metrics
- [x] Visualize results with confusion matrix
- [x] Understand basic classification concepts

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization
- **Scikit-learn** - Machine learning library
- **Kagglehub** - Dataset access

## 📁 Project Structure

```
iris-classification/
├── iris.ipynb              # Main Jupyter notebook
├── README.md               # Project documentation
```

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.7+ installed on your system.

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/iris-classification.git
cd iris-classification
```

2. Install required packages:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn kagglehub
```

3. Run the Jupyter notebook:
```bash
jupyter notebook iris.ipynb
```

## 📈 Model Performance

The Logistic Regression model achieved **perfect accuracy** on the test set:

- **Accuracy**: 100%
- **Precision**: 1.00 (all classes)
- **Recall**: 1.00 (all classes)
- **F1-Score**: 1.00 (all classes)

### Confusion Matrix
```
Predicted    Setosa  Versicolor  Virginica
Actual
Setosa         10        0          0
Versicolor      0        9          0
Virginica       0        0         11
```

## 🔍 Key Features

### Data Preprocessing
- ✅ No missing values detected
- ✅ Removed unnecessary ID column
- ✅ Clean, well-structured dataset

### Model Training
- **Algorithm**: Logistic Regression
- **Train/Test Split**: 80/20 (120 training, 30 testing samples)
- **Random State**: 42 (for reproducibility)
- **Max Iterations**: 200

### Evaluation Metrics
- Accuracy Score
- Classification Report (Precision, Recall, F1-Score)
- Confusion Matrix with heatmap visualization

## 📚 What You'll Learn

1. **Data Loading**: Using kagglehub to access datasets
2. **Data Exploration**: Understanding dataset structure and characteristics
3. **Data Preprocessing**: Cleaning and preparing data for ML
4. **Train/Test Split**: Proper data splitting for model evaluation
5. **Model Training**: Using Scikit-learn's LogisticRegression
6. **Model Evaluation**: Multiple metrics for performance assessment
7. **Data Visualization**: Creating confusion matrix heatmaps

## 🎓 Educational Value

This project is perfect for:
- **Beginners** learning machine learning fundamentals
- **Students** studying classification algorithms
- **Anyone** wanting to understand the ML workflow
- **Data science enthusiasts** exploring practical applications

## 🔧 Possible Improvements

- [ ] Try different algorithms (SVM, Random Forest, Neural Networks)
- [ ] Implement cross-validation
- [ ] Add feature scaling/normalization
- [ ] Create feature importance analysis
- [ ] Add data visualization for feature relationships
- [ ] Implement hyperparameter tuning
- [ ] Create a web interface for predictions

## 📊 Sample Predictions

The model can predict Iris species based on flower measurements:
```python
# Example prediction
new_flower = [[5.1, 3.5, 1.4, 0.2]]  # [SepalLength, SepalWidth, PetalLength, PetalWidth]
prediction = model.predict(new_flower)
# Output: ['Iris-setosa']
```

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Ronald Fisher** - For introducing the Iris dataset (1936)
- **UC Irvine ML Repository** - For maintaining the dataset
- **Scikit-learn contributors** - For the excellent ML library
- **Kaggle community** - For dataset accessibility

