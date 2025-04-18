
# Employee Attrition Prediction

This project implements a machine learning model to predict whether an employee is likely to leave a company based on various factors like job satisfaction, hourly rate, environment satisfaction, and years at the company. It uses the **Random Forest Classifier** and **KMeans clustering** for prediction and segmentation, respectively.

### Features:
- **Interactive User Input**: The user can input attributes such as job satisfaction, hourly rate, environment satisfaction, and years at the company.
- **Prediction**: The model predicts whether the employee will stay or leave the company based on the input features.
- **Model Evaluation**: The model is evaluated using metrics like **accuracy**, **precision**, and **recall**. It also displays a **confusion matrix** heatmap.
- **Clustering (Segmentation)**: The code performs **KMeans clustering** to segment employees based on job satisfaction, hourly rate, and years at the company.

### Libraries Used:
- `pandas`: For data manipulation.
- `matplotlib` & `seaborn`: For data visualization.
- `sklearn`: For machine learning model and evaluation metrics.
- `ipywidgets`: For creating interactive widgets for user input in **Google Colab**.




## Example:

### Interactive User Input:
- **Job Satisfaction**: 3
- **Hourly Rate**: 45
- **Environment Satisfaction**: 3
- **Years at Company**: 5

### Output:
The model will predict whether the employee is likely to stay or leave the company.


## Code Details

1. **Data Preprocessing**:
   - Irrelevant columns are removed from the dataset.
   - Categorical variables are encoded into numeric values using `LabelEncoder`.

2. **Training the Model**:
   - A **Random Forest Classifier** is used to train the model on employee data.
   - The dataset is split into training and testing sets (80% train, 20% test).

3. **Evaluation Metrics**:
   - The model is evaluated using **accuracy**, **precision**, and **recall**.
   - A **confusion matrix** heatmap is plotted to visualize the performance.

4. **Clustering**:
   - **KMeans clustering** is performed to segment employees based on job satisfaction and years at the company.
   - The clusters are visualized using a scatter plot.



## Conclusion

This project demonstrates how machine learning can be used to predict employee attrition and segment employees into clusters. By leveraging **Random Forest** and **KMeans clustering**, this solution provides insights into employee behavior and helps identify at-risk employees.

---

### Author:
- Nilesh Singh Yadav
---
