# 📧 Spam Detector

Welcome to this project!

In this project, I am building a machine learning spam classifier from raw email data. The goal is to create a model capable of distinguishing between legitimate emails (ham) and spam emails with high precision and recall.

This project is part of my AI & Machine Learning learning journey, where I focus on implementing concepts from scratch, understanding the complete ML pipeline, and documenting my progress along the way.

---

## 🎯 Project Objectives

The main goals of this project are to:

- Download and work with real-world email datasets
- Perform data preprocessing and feature engineering
- Build a complete machine learning pipeline
- Convert emails into numerical feature vectors
- Train and compare multiple classification algorithms
- Evaluate model performance using appropriate metrics
- Improve precision and recall through experimentation

---

## 📂 Dataset

This project uses the public datasets provided by:

- Apache SpamAssassin Public Corpus

The dataset contains:

- 📧 Ham Emails (legitimate emails)
- 🚫 Spam Emails (unwanted or malicious emails)

---

## 🛠 Project Workflow

### 1. Data Collection

- Download spam and ham datasets
- Extract and organize email files
- Explore dataset structure

### 2. Data Exploration

- Inspect email content
- Understand email formatting
- Analyze class distribution

### 3. Data Preparation

The email preprocessing pipeline may include:

- Removing email headers
- Converting text to lowercase
- Removing punctuation
- Replacing URLs with `URL`
- Replacing numbers with `NUMBER`
- Tokenization
- Stopword removal
- Word stemming
- Feature extraction

---

### 4. Feature Engineering

Emails will be transformed into sparse vectors representing word occurrences that machine learning models can understand.

#### Example

Email:

```text
Hello you Hello Hello you
```

Vocabulary:

```text
["Hello", "how", "are", "you"]
```

Binary Representation (Word Present or Not):

```text
[1, 0, 0, 1]
```

Count Representation (Word Frequency):

```text
[3, 0, 0, 2]
```

#### Vectorization Techniques

- Bag of Words (BoW)
- Count Vectorization
- TF-IDF Vectorization

### 5. Model Training

Several machine learning models will be tested and compared, including:

- Naive Bayes
- Logistic Regression
- Support Vector Machines (SVM)
- Random Forest
- Gradient Boosting

#### Future Experiments

- Deep Learning models
- Transformer-based text classification
- LLM-assisted email filtering