
# 🌌 Cosmic Classifier

A machine learning project that classifies different types of cosmic objects based on their features. This project demonstrates data preprocessing, model training, evaluation, and prediction using Python and Jupyter Notebook.

## 🚀 Overview

The **Cosmic Classifier** analyzes a dataset of celestial objects and builds a machine learning model to classify them accurately. The project focuses on:
- Data exploration and visualization
- Preprocessing (handling missing values, feature scaling, encoding)
- KNN mean imputation for missing numerical data
- KNN mode imputation for missing categorical data.
- One hot encoding for categorical data.
- Model building and evaluation (classification models like Random Forest, etc.)
- Making predictions on new/unseen data

## 🗂️ Project Structure

```
📁 Cosmic-Classifier/
   ├── datasets/
   │   ├── cosmicclassifierTraining.csv     # Training dataset
   │   ├── cosmicclassifierTest.csv         # Test dataset
   │
   ├── cosmic_classifier.ipynb              # Main Jupyter Notebook for model training and evaluation
   ├── submission.csv                       # Output predictions or submission results
   ├── requirements.txt                     # Python dependencies
   └── README.md                            # Project overview and instructions

```

## 📚 Dataset

The dataset used in this project contains features representing different cosmic objects, such as stars, galaxies, and quasars. You'll find it in the `datasets/` folder.
## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Cosmic-Classifier.git
   cd Cosmic-Classifier
   ```

2. **Install Python packages**
   Make sure you have Python 3.x installed.

   Install required libraries:
   ```bash
   pip install -r requirements.txt

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. Open `cosmic_classifier.ipynb` and follow along!

## 🔎 Features

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Multiple machine learning models
- Model evaluation (accuracy, confusion matrix, etc.)
- Predictive analysis

## 📈 Results

The best performing model in this project was the Support Vector Classifier (SVC), which achieved an accuracy of 92% on the test dataset.
This demonstrates the effectiveness of SVC in classifying cosmic data based on the provided features.

## ✨ Future Work

- Hyperparameter tuning for improved accuracy
- Deploy the model as an API or web app
- Explore deep learning models for classification


### 🚀 Author
**MIMAT SINGH**
