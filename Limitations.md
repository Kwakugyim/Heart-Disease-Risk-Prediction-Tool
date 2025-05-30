# Limitations

While the Heart Disease Risk Prediction Tool offers valuable insights, it has several limitations that users should consider when interpreting its output.

---

## 1. Data Source Limitations

- The model is built using **BRFSS data**, which is nationally representative but may not match the characteristics of smaller, specific populations.
- Certain subgroups (e.g., rural communities, non-English speakers) may be underrepresented.

---

## 2. Self-Reported Bias

- BRFSS relies on **self-reported data**, which can be prone to inaccuracies.
  - Example: Underreporting of smoking or overreporting of exercise.

---

## 3. Statistical Assumptions

- Logistic regression assumes a **linear relationship** between predictors and the log odds of the outcome.
- This assumption may not hold true for all variables, especially when complex interactions are involved.

---

## 4. Model Complexity

- The inclusion of **interaction terms** improves performance but also increases complexity.
- This can make the model more **sensitive to input variability** and harder to interpret.

---

## 5. Missing Variables

- The model does **not include** some important risk factors:
  - Genetic predisposition
  - Diet quality
  - Chronic stress
  - Medication history

---

## 6. Lack of Local Validation

- The model has only been validated on BRFSS data.
- **Community-specific validation** is needed to ensure reliability for other populations.

> Users should treat the model as an educational or screening tool and consult medical professionals for personalized risk assessments.
