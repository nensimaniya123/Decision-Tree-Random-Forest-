# Decision-Tree-Random-Forest-

## Objective

This project focuses on learning and implementing tree-based models — **Decision Trees** and **Random Forests** — for classification tasks. The main goals are to:
- Train and visualize a decision tree
- Analyze overfitting and control model complexity
- Compare performance with a random forest model
- Interpret feature importance
- Evaluate models using cross-validation

---

##  Dataset Used

**Dataset:** [Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)  
**Source:** Kaggle  
**Description:** The dataset contains various medical attributes like age, cholesterol level, resting blood pressure, etc., to predict the presence of heart disease.

---

##  Tools & Libraries

- Python
- Scikit-learn
- Pandas
- Matplotlib
- Graphviz
- Seaborn (optional for visualization)

---

##  Steps Performed

1. **Data Loading & Preprocessing**
   - Loaded the dataset using Pandas
   - Handled missing values and categorical encoding (if necessary)
   - Performed train-test split

2. **Decision Tree Classifier**
   - Trained a Decision Tree model using Scikit-learn
   - Visualized the tree using `export_graphviz` + Graphviz
   - Controlled tree depth to prevent overfitting

3. **Model Evaluation**
   - Evaluated Decision Tree using training and test accuracy
   - Observed overfitting behavior at various depths

4. **Random Forest Classifier**
   - Trained a Random Forest with 100 estimators
   - Compared accuracy with Decision Tree

5. **Feature Importance**
   - Extracted and visualized feature importances using bar plots

6. **Cross-Validation**
   - Performed 5-fold cross-validation on Random Forest
   - Computed average performance score

---

## 📊 Results Summary

| Model             | Train Accuracy | Test Accuracy | Cross-Validation (Avg) |
|------------------|----------------|---------------|-------------------------|
| Decision Tree     | ~0.98          | ~0.79         | -                       |
| Random Forest     | ~0.99          | ~0.84         | ~0.85                   |

---

## Key Learnings

- Decision Trees are interpretable but prone to overfitting without pruning or depth control.
- Random Forests reduce variance through ensemble learning and generally outperform single trees.
- Feature importance scores help understand which variables drive predictions.
- Cross-validation provides a more reliable estimate of model performance.
  
Project Files
- decision_tree_random_forest.ipynb
- heart.csv
- decision_Tree_Report


Conclusion
This task provided a comprehensive understanding of decision tree-based models and ensemble techniques. By comparing single tree performance with that of a random forest, we observed the power of ensemble methods in reducing overfitting and improving accuracy.


