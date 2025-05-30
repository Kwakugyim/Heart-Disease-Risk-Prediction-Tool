# How to Use the Tool

The Heart Disease Risk Prediction Tool outputs a probability score between 0 and 1 that estimates the likelihood of developing heart disease. Follow the steps below to use the tool effectively.

---

## Step-by-Step Guide

### 1. Gather Data

Collect the following information about the individual you want to assess:

- Smoking status (1 = smoker, 0 = non-smoker)
- Age (in years)
- Body Mass Index (BMI × 100)
- Diabetes diagnosis (1 = yes, 0 = no)
- Sex (1 = male, 0 = female)
- Alcohol consumption (1 = yes, 0 = no)
- COPD diagnosis (1 = yes, 0 = no)
- Kidney disease diagnosis (1 = yes, 0 = no)
- Depression diagnosis (1 = yes, 0 = no)
- Arthritis diagnosis (1 = yes, 0 = no)

---

### 2. Input the Data into the Model

Use the Python code provided in the [Appendix](../appendix/explanation_notes.md) to enter the data. Make sure that all inputs follow the specified format (e.g., BMI multiplied by 100).

---

### 3. Run the Model

Execute the Python script. It will calculate a **logit** score internally and return the **probability** of heart disease.

---

### 4. Interpret the Results

The model returns a probability value between 0 and 1.  
- A score close to **0** means low risk.  
- A score close to **1** means high risk.

Use this score to make informed decisions about health interventions or lifestyle changes.
