# ART-Status-Prediction-Analysis

- Access the exploratory data analysis and data cleaning notebook [here](https://github.com/ChristianAliyuda/ART-Status-Prediction-Analysis/blob/main/ART%20prediction-Data%20Exploration.ipynb).
- Access the notebook on model fitting, prediction, accuracy and interpretation [here](https://github.com/ChristianAliyuda/ART-Status-Prediction-Analysis/blob/main/ART%20prediction%20-%20Model%20Building.ipynb).

#### Relationship Between Variables
![image](https://github.com/ChristianAliyuda/ART-Status-Prediction-Analysis/assets/91130565/51580496-85d5-418b-9d3f-d7ebb57ba374)

#### Understanding Distribution of Target Variable
![image](https://github.com/ChristianAliyuda/ART-Status-Prediction-Analysis/assets/91130565/ef1af810-92d8-4852-841d-76c767661470)

#### Understanding Feature Importance
![image](https://github.com/ChristianAliyuda/ART-Status-Prediction-Analysis/assets/91130565/c205d2c1-0ee2-4c05-991c-eb8ad3cb1e18)

### Best Model Prediction Accuracy and Confusion Matrix
![image](https://github.com/ChristianAliyuda/ART-Status-Prediction-Analysis/assets/91130565/90133765-74a4-40a7-b171-e744f3e4ca5e)

### Interpretation for the Best Performing Model

**Class 0 (Majority Class) - Active**

- True Positives (14779): The model correctly predicted 14779 instances as class 0.
- False Negatives (5): There are 5 instances that belong to class 0 but were predicted as other classes.
- Precision (0.99): Indicates high accuracy in predicting class 0.
- Recall (1.00): The model captured nearly all instances of class 0.

**Class 1 - LTFU**

- True Positives (4495): The model correctly predicted 4495 instances as class 1.
- False Positives (289): Instances that were incorrectly predicted as class 1.
- False Negatives (290): Instances that belong to class 1 but were predicted as other classes.
- Precision (0.88): Indicates high accuracy but slightly lower than class 0.
- Recall (0.94): The model captured most instances of class 1.

**Class 2 - Discontinued Care**

- True Positives (124): The model correctly predicted 124 instances as class 2.
- False Positives (366): Instances that were incorrectly predicted as class 2.
- False Negatives (366): Instances that belong to class 2 but were predicted as other classes.
- Precision (0.39): Indicates moderate accuracy in predicting class 2.
- Recall (0.25): The model captured only a quarter of the instances of class 2.

**Class 3 - Transferred Out**

- True Positives (194): The model correctly predicted 194 instances as class 3.
- False Positives (419): Instances that were incorrectly predicted as class 3.
- False Negatives (419): Instances that belong to class 3 but were predicted as other classes.
- Precision (0.41): Indicates moderate accuracy in predicting class 3.
- Recall (0.32): The model captured nearly a third of the instances of class 3.

**Class 4 - Death**

- True Positives (972): The model correctly predicted 972 instances as class 4.
- False Positives (535): Instances that were incorrectly predicted as class 4.
- False Negatives (453): Instances that belong to class 4 but were predicted as other classes.
- Precision (0.72): Indicates high accuracy in predicting class 4.
- Recall (0.68): The model captured more than two-thirds of the instances of class 4.

