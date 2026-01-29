# 🏥 Breast Cancer Diagnostic Classification
**Machine Learning | Healthcare | Supervised Learning**

## 📌 The Challenge
Using cell nuclei features to classify tumors as Malignant or Benign. In medical AI, the cost of a "False Negative" is extremely high, so the model must be highly reliable.

## 🛠️ Technical Approach
* **Preprocessing:** Applied **StandardScaler** to normalize feature scales (radius, texture, smoothness).
* **Algorithm:** Implemented a **Random Forest Classifier** to handle the high dimensionality of the feature set.
* **Validation:** Used a 80/20 train-test split with Cross-Validation.

## 📊 Key Results
* **Accuracy:** [e.g., 96%]
* **Insight:** Identified 'concave points' and 'radius' as the most significant predictors.
