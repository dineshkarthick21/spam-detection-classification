# Spam SMS Detection System

## Overview

Spam SMS Detection System is a Machine Learning project that classifies SMS messages as **Spam** or **Ham (Not Spam)**. The project uses Natural Language Processing (NLP) techniques and a Random Forest Classifier to analyze message content and predict whether a message is spam.

---

## Features

* SMS message classification
* Text preprocessing using TF-IDF Vectorization
* Random Forest Classification
* High prediction accuracy
* Model saving using Joblib
* Real-time message prediction
* Easy integration with Flask and React applications

---

## Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Scikit-learn
* Joblib

### Machine Learning

* Random Forest Classifier

### NLP Techniques

* TF-IDF Vectorization

### Development Environment

* Jupyter Notebook
* VS Code

---

## Dataset

The project uses the Spam SMS Dataset.

Dataset Columns:

| Column | Description      |
| ------ | ---------------- |
| v1     | Label (ham/spam) |
| v2     | SMS Message      |

Target Classes:

* Ham = 0
* Spam = 1

---

## Project Workflow

```text
Dataset
   ↓
Data Cleaning
   ↓
Label Encoding
   ↓
TF-IDF Vectorization
   ↓
Train-Test Split
   ↓
Random Forest Classifier
   ↓
Model Evaluation
   ↓
Prediction
   ↓
Save Model
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/spam-sms-detection.git
```

Move into the project folder:

```bash
cd spam-sms-detection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Required Packages

```bash
pip install pandas
pip install numpy
pip install scikit-learn
pip install joblib
```

---

## Running the Project

Open Jupyter Notebook:

```bash
jupyter notebook
```

Run the notebook cells step by step.

---

## Model Training

The model is trained using:

```python
RandomForestClassifier(
    n_estimators=100,
    random_state=42
)
```

---

## Example Prediction

Input:

```text
Congratulations! You won a cash prize.
Click here to claim your reward.
```

Output:

```text
Spam
```

Input:

```text
Hi, are you coming to class today?
```

Output:

```text
Ham
```

---

## Model Evaluation

Metrics Used:

* Accuracy Score
* Classification Report
* Confusion Matrix

Example Result:

```text
Accuracy: 96%
```

---

## Saving the Model

```python
joblib.dump(model, "spam_classifier.pkl")
joblib.dump(vectorizer, "vectorizer.pkl")
```

Saved Files:

```text
spam_classifier.pkl
vectorizer.pkl
```

---

## Future Enhancements

* Flask REST API Integration
* React Frontend Interface
* Docker Deployment
* Email Spam Detection
* Deep Learning Models
* Real-time Prediction Dashboard

---

## Learning Outcomes

Through this project, the following concepts were implemented:

* Supervised Learning
* Classification Algorithms
* Natural Language Processing
* TF-IDF Vectorization
* Random Forest Classifier
* Model Evaluation
* Model Persistence

---

## Author

Dineshkarthick


