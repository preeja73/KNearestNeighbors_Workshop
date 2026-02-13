# 🧑‍💻 K-Nearest Neighbors (KNN) Workshop

## 📘 Workshop Summary
This repository contains the materials and student solutions for the **K-Nearest Neighbors (KNN) Workshop**.  
The workshop introduces students to data analysis, machine learning design patterns, and active learning practices through the implementation of the KNN algorithm.

Students will explore multiple types of datasets (CSV files, APIs, relational databases), implement KNN classifiers, and design their code using the **Machine Learning Pipeline Pattern**. The workshop emphasizes collaboration through **peer programming** and reflection on algorithm performance.

---

## 🎯 Learning Objectives
By completing this workshop, you will be able to:
1. Understand the intuition behind the K-Nearest Neighbors algorithm.  
2. Acquire, clean, and preprocess data from different sources.  
3. Apply KNN for classification and evaluate its performance.  
4. Architect code using the **Machine Learning Pipeline Pattern**.  
5. Collaborate with peers through active learning and peer programming.  
6. Reflect on the strengths, limitations, and real-world applications of KNN.  

---

## 🤖 About the KNN Algorithm
The **K-Nearest Neighbors algorithm** is a simple, non-parametric machine learning method used for classification and regression.  
- A new data point is classified based on the **majority label of its *k* closest neighbors** in the training set.  
- The choice of *k* and the method of measuring distance (e.g., Euclidean, Manhattan) heavily influence performance.  
- KNN is **instance-based** (lazy learning): it stores the training data and makes predictions only at query time.  

---

## 🏗️ Implementation with ML Architecture and Design Patterns
This workshop emphasizes implementing KNN using the **Machine Learning Pipeline Pattern**:
- **Data Acquisition** (from CSV, API, or relational database)  
- **Data Cleaning & Preprocessing** (scaling, encoding, handling missing values)  
- **Feature Engineering**  
- **Model Training** (KNN classifier)  
- **Evaluation** (accuracy, confusion matrix, other metrics)  
- **Reflection & Peer Comparison**  

By structuring code into **modular components**, students will learn how to build reproducible and extensible ML workflows, aligning with professional MLOps practices.

---

## 📂 High-Level View of the Workshop
The workshop is split across two sessions (two hours total), with homework in between:

- **Session 1**  
  - Introduction to KNN (theory and Iris dataset demo)  
  - Hands-on: load and preprocess a dataset from a CSV, API, or relational DB  

- **Homework**  
  - Finalize preprocessing and prepare dataset for KNN  

- **Session 2**  
  - Implement KNN using the Pipeline Pattern  
  - Train, evaluate, and visualize results  
  - Reflect on algorithm performance  
  - Compare results with peers and discuss strengths/weaknesses of KNN  

---

## 👤 Student Information
1. Truong Minh Thuan 8730956
2. Anthony Izevbokun 9016626
3. Preeja Anilal 8791796

---

## 📋 Summary of Work
This submission completes the K-Nearest Neighbors (KNN) workshop with the following:

- **Part 1 – Iris dataset:** Loaded the Iris dataset, split into train/test, trained a KNN classifier, evaluated accuracy, and visualized predictions (including a test-point plot).
- **Part 2 – Data sources:** Implemented KNN pipelines for three data sources: (A) Open-Meteo API (temperature data), (B) Titanic CSV (load, clean, preprocess, and full pipeline with ColumnTransformer), and (C) SQLite database (write/read Titanic data, then run the same pipeline on DB-loaded data). Explored different values of *k* for the Titanic dataset.
- **Part 3 – ML Pipeline Pattern:** Built modular, reusable functions: `load_data_api_open_meteo`, `preprocess_api_temperature`, `build_knn_numeric_pipeline`, and `evaluate_classifier`; ran the full flow (load → preprocess → split → train → evaluate) on the API dataset.

The notebook includes markdown explanations before each code block and inline comments throughout the code.

---

## 📝 Deliverables
- `KNN_Workshop_Solution.ipynb`: Our notebook implementation with code and explanations.  
- `README.md`: This file, including your name, student ID, and a brief summary of your work.  
- A PDF file with our name, student ID, and the URL to your remote repository.  

---

## ✍️ Instructor Information
- **Name:** *David Espinosa*  
- **Release:** *October 2025*  
