 Project 4: Breast Cancer Classification via Logistic Regression

  Overview
In this project, a binary class model is developed via Logistic Regression to classify whether a tumor is malignant or benign given medical diagnostic measurements. The model is trained against the Breast Cancer Wisconsin dataset and tested on standard classification metrics.

  Dataset
- Source: [Breast Cancer Wisconsin Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- File: `data.csv`

  Objective
- Train logistic regression model to predict tumors as benign (0) or malignant (1).
- Test the model based on accuracy, precision, recall, and ROC-AUC.
- Describe sigmoid function and discuss the impact of threshold tuning. 

 ️ Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

  Workflow Summary
1. Data Preprocessing
   - Dropped unnecessary features such as `id` and `Unnamed: 32`.
- Transformed target `diagnosis` column into binary.
   - Normalized numerical features with `StandardScaler`.

2. Training
   - Split the data into training and testing sets.
   - Trained a logistic regression model with `sklearn`.

3. Model Evaluation
   - Created confusion matrix and classification report.
   - Complicated ROC-AUC and plotted ROC curve.
- Visualized sigmoid function to illustrate logistic regression behavior.

4. Threshold Tuning
   - Tested the model performance at various classification thresholds (0.3, 0.5, 0.7).

  Evaluation Metrics
| Metric| Description |
|--------|-------------|
| Accuracy| Overall correctness of predictions |
| Precision| Number of predicted positives that are correct |
| Recall| Number of actual positives that are captured
| ROC-AUC| Area under the ROC curve (towards 1 is better) |
 Conclusion
Logistic regression model successfully classified breast cancer instances with excellent accuracy and AUC. Threshold tuning and sigmoid comprehension improved model interpretability for clinical decisions.

  Files Included
- `project_4.ipynb` – Jupyter Notebook containing full code and output
- `data.csv` – Dataset file used for training and testing
- `README.md` – Project documentation

