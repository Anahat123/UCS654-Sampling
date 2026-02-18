# Sampling Techniques on Imbalanced Credit Card Dataset

## Objective

The objective of this assignment is to understand the importance of sampling techniques in handling imbalanced datasets and to analyze how different sampling strategies affect the performance of various machine learning models.

---

## Dataset

The Credit Card Fraud Detection dataset used in this assignment was highly imbalanced, with a large difference between the number of fraudulent and non-fraudulent transactions.

---

## Methodology

The following steps were performed:

1. Loaded the dataset.
2. Preprocessed the data and separated features and target variable.
3. Applied five different sampling techniques:
   - Sampling1
   - Sampling2
   - Sampling3
   - Sampling4
   - Sampling5
4. Trained five machine learning models:
   - M1 – Logistic Regression
   - M2 – Decision Tree
   - M3 – Random Forest
   - M4 – Support Vector Machine
   - M5 – K-Nearest Neighbors
5. Evaluated model performance using Accuracy Score.

---

## Accuracy Table

| Model | Sampling1 | Sampling2 | Sampling3 | Sampling4 | Sampling5 |
|--------|------------|------------|------------|------------|------------|
| M1 | 91.70 | 33.33 | 91.92 | 91.92 | 98.28 |
| M2 | 98.69 | 66.67 | 97.16 | 97.38 | 97.84 |
| M3 | 99.78 | 16.67 | 99.34 | 99.13 | 98.71 |
| M4 | 96.51 | 16.67 | 97.38 | 97.38 | 98.71 |
| M5 | 96.94 | 33.33 | 95.41 | 95.41 | 98.71 |

---

## Results and Discussion

After applying different sampling techniques to multiple machine learning models, the following observations were made:

- For M1, Sampling5 achieved the highest accuracy of 98.28%.
- For M2, Sampling1 performed best with 98.69% accuracy.
- For M3, Sampling1 achieved the highest overall accuracy of 99.78%, which is the best performance among all model–sampling combinations.
- For M4 and M5, Sampling5 produced the highest accuracy of 98.71%.

Sampling1 and Sampling5 consistently performed better across most models. Sampling2 significantly reduced accuracy in multiple cases, indicating possible loss of important information due to undersampling.

Overall, Random Forest (M3) combined with Sampling1 gave the best performance.

---

## Conclusion

Balancing an imbalanced dataset significantly improves model performance.

Among all combinations tested, Random Forest with Sampling1 achieved the highest accuracy of 99.78%, making it the most effective model-sampling pair for this dataset.

This experiment demonstrates that selecting an appropriate sampling technique plays a crucial role in improving classification performance on imbalanced datasets.
