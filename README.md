# Stroke-Risk-Prediction-Using-Machine-Learning

## Overview
This project analyzes and compares **three machine learning models**—Support Vector Machine (SVM), Random Forest, and K-Nearest Neighbors (KNN)—for stroke risk prediction using a healthcare dataset. The study evaluates these models based on their classification performance and interpretability.

## Methodology
### Data Preprocessing
- **Dataset:** 5110 records with 12 attributes (demographic, medical, and lifestyle features)
- **Missing Values:** BMI values imputed using the mean
- **Encoding:** One-hot encoding and label encoding applied to categorical variables
- **Feature Scaling:** Min-Max scaling applied to continuous variables
- **Train-Test Split:** 80% training, 20% testing

### Model Implementation
- **Random Forest:** An ensemble learning method using multiple decision trees
- **Support Vector Machine (SVM):** Utilized RBF kernel for optimal separation
- **K-Nearest Neighbors (KNN):** Selected optimal `k` value using cross-validation

### Model Evaluation
- **Accuracy**: Measures overall classification correctness
- **Precision**: Reflects the proportion of correctly identified stroke cases
- **Recall**: Evaluates the model’s ability to detect stroke cases
- **F1-Score**: Balances precision and recall

### Results
| Model         | Accuracy | Precision | Recall | F1-Score |
|--------------|----------|-----------|--------|----------|
| **SVM**       | 94%      | 88%       | 94%    | 91%      |
| **Random Forest** | 93%      | 88%       | 93%    | 91%      |
| **KNN**       | 94%      | 88%       | 94%    | 91%      |

SVM and KNN achieved the highest accuracy (94%), making them effective for precise stroke prediction. Random Forest, while slightly lower in accuracy (93%), offers better feature interpretability.


## Future Work
- Implement **ensemble learning** to improve prediction accuracy
- Explore **feature selection** methods for reducing dataset complexity
- Address **class imbalance** to enhance model reliability in real-world applications

### References
- [Performance Comparison of Random Forest, SVM, and Neural Networks in Stroke Prediction](https://www.researchgate.net/publication/379990719_Performance_Comparison_of_Random_Forest_Support_Vector_Machine_and_Neural_Network_in_Health_Classification_of_Stroke_Patients)
- [SVM for Stroke Risk Prediction](https://www.researchgate.net/publication/369456872_Support_Vector_Machine_for_Stroke_Risk_Prediction)

