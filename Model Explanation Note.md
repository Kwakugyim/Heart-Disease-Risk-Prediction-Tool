# Appendix – Model Explanation Notes

This section provides supporting context for the Python code used in the Heart Disease Risk Prediction Tool.

---

## Model Type

The model is a **logistic regression**, trained on BRFSS survey data. It calculates the **log odds** of heart disease based on individual health and demographic variables.

---

## Input Variables

The model uses 10 primary predictors:

- Smoking status
- Age
- BMI (multiplied by 100)
- Diabetes diagnosis
- Sex
- Alcohol consumption
- COPD status
- Kidney disease
- Depression
- Arthritis

Each is encoded as either a numerical or binary value.

---

## Interaction Terms

To improve predictive accuracy, the model includes several **interaction terms**, which capture how the effect of one variable may change depending on the value of another (e.g., Smoking × Age).

---

## Output

- The final output is a **probability** between 0 and 1.
- Higher values indicate greater estimated risk.

---

## Important Note

- This tool is **not diagnostic**.
- It is designed for educational, wellness, or research purposes and should be interpreted in consultation with a healthcare provider.
