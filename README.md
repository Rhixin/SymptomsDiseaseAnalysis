# **Symptom-Based Disease Prediction System**

---

## 📌 **Overview**

This project implements a **symptom-disease prediction system** using association rule mining (Apriori Algorithm) and machine learning approaches like **Naive Bayes**. The system identifies frequent symptom patterns from data and predicts the most likely disease based on provided symptoms.

---

## 🛠️ **Technologies & Methods**

1. **Apriori Algorithm**:  
   - Applied to extract frequent itemsets and generate association rules.
   - **Support** threshold = **0.10**  
   - **Confidence** threshold = **0.80**  
   - **Lift** used = **4**  
   - **Leverage** threshold = **0.05**  

2. **Bayesian Methods**:  
   - **Naive Bayes Classifier** to predict diseases based on a given list of symptoms.  
   - Using Bayes' Theorem to determine the probability of disease presence given symptoms.

---

## 💡 **How It Works**

1. **Apriori Rules**:  
   - Extract frequent symptom-disease pairs using predefined thresholds.  
   - Example:
     - Symptoms like *"fever" + "cough"* may lead to another symptom like *"itching."*

2. **Bayesian Prediction**:  
   - Given a list of symptoms as input, predict the most likely disease using a probabilistic approach based on **Bayes' Theorem**.

---

## ✅ **Goals**

- [x] Extract and filter association rules using **Apriori** with:
  - 0.10 support  
  - 0.80 confidence  
  - Lift factor = 4  
  - Leverage = 0.05  

- [ ] **Bayesian Methods**:
  - Create a system that predicts the likelihood of a disease based on a given list of symptoms.
  - Research & implement **Naive Bayes Classifier**.
  - Investigate if this is similar to Bayesian inference.
