# 📧 Spam Email Detection Using Logistic Regression

## 📌 Project Overview

This project builds a **Spam Email Detection Machine Learning model** using **Logistic Regression**.

The model analyzes features extracted from emails and predicts whether an email is:

* 🟢 **Not Spam (0)**
* 🔴 **Spam (1)**

The project also evaluates the model using **Accuracy, Precision, Recall, and F1 Score**, and visualizes the results using a **Confusion Matrix**.

## 🎯 Project Objective

The main objective of this project is to develop a binary classification model that can automatically identify spam emails.

This project demonstrates the use of:

* Data preprocessing
* Train-test splitting
* Logistic Regression
* Binary classification
* Model evaluation
* Confusion matrix visualization

## 📊 Dataset

The project uses the **Spambase dataset**, which contains numerical features extracted from emails.

The target column is:

```text
spam
```

Where:

```text
0 = Not Spam
1 = Spam
```

The remaining columns are used as input features for the machine learning model.

## 🛠️ Technologies Used

* Python
* Pandas
* Scikit-learn
* Seaborn
* Matplotlib

## 🤖 Machine Learning Model

### Logistic Regression

Logistic Regression is a supervised machine learning algorithm commonly used for **binary classification**.

In this project, it learns the relationship between email features and the target variable `spam`.

The model then predicts whether an unseen email belongs to the spam or non-spam class.

## 🔄 Project Workflow

```text
Load Dataset
     ↓
Separate Features and Target
     ↓
Split Data into Training and Testing Sets
     ↓
Train Logistic Regression Model
     ↓
Make Predictions
     ↓
Evaluate Model
     ↓
Visualize Confusion Matrix
```

## 📈 Model Evaluation

The model is evaluated using four important classification metrics:

### Accuracy

Measures the percentage of predictions that were correct.

### Precision

Measures how many emails predicted as spam were actually spam.

### Recall

Measures how many of the actual spam emails were correctly detected.

### F1 Score

Provides a balance between precision and recall.

The project prints:

```text
Accuracy
Precision
Recall
F1 Score
```

## 📉 Confusion Matrix

A confusion matrix is used to visualize the model's classification results.

It contains:

* **True Positive (TP):** Spam correctly identified as spam
* **True Negative (TN):** Non-spam correctly identified as non-spam
* **False Positive (FP):** Non-spam incorrectly classified as spam
* **False Negative (FN):** Spam incorrectly classified as non-spam

## 📁 Project Structure

```text
Email-detector/
│
├── spam/
│   └── spambase.csv
│
├── main.py
│
└── README.md
```

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Vedline2547/Spam-email-detector.git
```

### 2. Navigate into the project

```bash
cd Email-detector
```

### 3. Create a virtual environment

```bash
python -m venv .venv
```

### 4. Activate the virtual environment

Windows PowerShell:

```bash
.venv\Scripts\Activate.ps1
```

### 5. Install the required libraries

```bash
pip install pandas scikit-learn seaborn matplotlib
```

### 6. Run the project

```bash
python main.py
```

## 💡 What I Learned

Through this project, I practiced:

* Building a binary classification model
* Using Logistic Regression with Scikit-learn
* Preparing data for machine learning
* Splitting data into training and testing sets
* Evaluating classification models
* Understanding precision, recall, and F1 score
* Interpreting a confusion matrix
* Visualizing machine learning results

## 🚀 Future Improvements

Possible improvements include:

* Feature scaling
* Hyperparameter tuning
* Comparing Logistic Regression with Random Forest and SVM
* Testing additional classification algorithms
* Improving model performance
* Building a simple web interface for real-time spam detection

## 👨‍💻 Author

**Vedline Ochieng**

Civil Engineering Student | Machine Learning & AI Enthusiast | Python Developer

---

⭐ If you find this project useful, feel free to star the repository!
