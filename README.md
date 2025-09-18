predicting Breast cancer of persons-Decision Tree vs Logistic Regression:
this project is compares Decision Tree and Logistic regression models to predict Breast cancer of 
a person(yes(or)no).the goal is to evaluate which model performs better on the dataset and demostrate
preprocessing,training,and eveluation steps

**Dataset:**
     breast-cancer dataset
     the number of rows and columns=(272,10)
     it contains data  age,mefalse,tumorsize,breast,breastquad,irradiat,etc
(https://drive.usercontent.google.com/download?id=18ugGAHpNYyryg0ZWfONCCNoem0E0L8XN&export=download&authuser=0)
**Requirements:**
 -Python 3.8+
 -numpy,pandas,scikit-learn,matplotlib,seaborn,jupyter
**Project structure**
-'data/'-raw &processed datasets 
-'notebook/'-exploratory analysis and plots(Jupyter notebooks)
-'Decision_tree.ipynb'-main script to run models
-'README.md'-this file 
-'results/'-evaluation metrics,plots
**How to run:**
Clone this repository:
'''bash
-git clone 
https://github.com/krishna4444-dell/Decision_tree_project.git
-open the project folder:
-cd Decision_tree-project
-Install dependencies:
pip install -r requirements.txt
-open the Jupyter Notebook:
jupyter notebook Decision_tree.ipynb
-Run all cells in order to reproduce the results
**workflow**
-Data cleaning and preprocessing 
-Handling missing values and encoding categorical data
-splitting dataset into training and testing sets
-Training Decision Tree and Logistic Regression models
-Evaluating models using accuracy
-Comparing results to understand which model performs better
**Results**
-**Decision Tree**: Accuracy=77.27%,
-**Logistic Regression**:Accuracy=69.811%
**comparison**
-Decision Tree performed better than Logistic Regression on this dataset
-Logistic Regression gave lower accuracy but is simpler and less prone to overfitting.
**Conclusion**
-Decision Tree achieved higher accuracy(77.27%) compared to Logistic Regression (69.81%)
on this dataset
-This shows Decision Trees can capture complex patterns in the data,while Logistic Regression 
is better for simpler linear relationships
**Future work**
-perform hyperparameter tuning (e.g.,GridSearchCV) to improve Decision Tree performance.
-Try other algorithms like Random Forest,Gradient Boosting, or SVM for comparison.
-Add cross-validation to get more reliable performance estimates.
-Deploy the best model as a simple web or desktop application for demonstration
