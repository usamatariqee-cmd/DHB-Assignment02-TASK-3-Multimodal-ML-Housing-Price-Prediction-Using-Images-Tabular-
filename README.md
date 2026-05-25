# DHB-Assignment02-TASK-3-Multimodal-ML-Housing-Price-Prediction-Using-Images-Tabular-
# House Price Prediction using CNN

This project demonstrates a deep learning approach for predicting house prices using a Convolutional Neural Network (CNN). The notebook walks through the complete workflow including data preprocessing, model creation, training, evaluation, and prediction.

---

# Project Overview

The objective of this project is to build a neural network model capable of predicting house prices based on housing-related features.

The notebook includes:

* Data loading and preprocessing
* Exploratory Data Analysis (EDA)
* Feature scaling and transformation
* CNN model creation using TensorFlow/Keras
* Model training and validation
* Performance evaluation
* Prediction visualization

---

# Dataset

The dataset used contains housing-related features such as:

* Number of rooms
* Area size
* Location-related information
* House condition
* Other property features

Target variable:

* House Price

---

# Technologies Used

## Python Libraries

* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* TensorFlow
* Keras

---

# Workflow

## 1. Data Loading

The dataset is loaded using Pandas:

```python
pd.read_csv()
```

Initial inspection includes:

* Viewing dataset shape
* Checking missing values
* Understanding feature types

---

## 2. Exploratory Data Analysis (EDA)

The notebook performs data visualization and analysis to understand:

* Feature distributions
* Correlation between variables
* Price trends
* Outliers and anomalies

Visualizations may include:

* Histograms
* Scatter plots
* Heatmaps
* Correlation matrices
* Box plots

---

## 3. Data Preprocessing

The preprocessing stage includes:

* Handling missing values
* Feature selection
* Encoding categorical variables
* Normalization/Standardization

Data is prepared before training the CNN model.

---

## 4. Train-Test Split

The dataset is divided into:

* Training set
* Testing set

Using:

```python
train_test_split()
```

---

## 5. CNN Model Architecture

The project uses a Convolutional Neural Network (CNN) built with TensorFlow/Keras.

Typical layers include:

* Convolutional layers
* Activation functions
* Dense layers
* Dropout layers

Example:

```python
Sequential()
```

The model is compiled using:

```python
model.compile()
```

---

## 6. Model Training

The model is trained using:

```python
model.fit()
```

Training includes:

* Epochs
* Batch size
* Validation split

---

## 7. Model Evaluation

The notebook evaluates model performance using:

* Loss metrics
* Mean Squared Error (MSE)
* Mean Absolute Error (MAE)
* Prediction accuracy visualization

---

## 8. Predictions

The trained model is used to:

* Predict house prices
* Compare actual vs predicted values
* Visualize prediction performance

---

# Project Structure

```text
├── TASK_3(Hosue_price_prediction_CNN).ipynb
├── dataset.csv
└── README.md
```

---

# How to Run the Project

## 1. Clone the Repository

```bash
git clone <repository-url>
cd <repository-folder>
```

## 2. Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow keras
```

## 3. Run the Notebook

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook:

```text
TASK_3(Hosue_price_prediction_CNN).ipynb
```

---

# Deep Learning Concepts Covered

* Convolutional Neural Networks (CNN)
* Neural Network Training
* Feature Scaling
* Regression using Deep Learning
* TensorFlow/Keras Workflow
* Model Evaluation
* Prediction Analysis

---

# Future Improvements

Possible enhancements:

* Hyperparameter tuning
* Use advanced architectures
* Add early stopping
* Improve feature engineering
* Deploy model using Flask or FastAPI
* Save trained model for production

---

# Learning Outcomes

This project helps understand:

* Building regression models using CNNs
* Deep learning workflow for structured data
* TensorFlow/Keras model development
* Data preprocessing for neural networks
* Performance evaluation techniques

---

# Author

Created as part of a deep learning and house price prediction practice project using TensorFlow and Keras.
