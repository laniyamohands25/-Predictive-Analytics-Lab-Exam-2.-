# -Predictive-Analytics-Lab-Exam-2.-
# Predictive Analytics Lab Exam-2

## Objective

The objective  is to build a machine learning classification model to predict the target class using the given dataset.

## Dataset

The dataset used in this project contains two input features and one target variable.

**Features**

* Feature1
* Feature2

**Target Variable**

* Yes
* No

## Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to understand the structure and distribution of the dataset. The following steps were carried out:

* Checked dataset structure and dimensions
* Checked for missing values
    found missing values in target 
* Visualized class distribution using a count plot
* <img width="514" height="444" alt="Screenshot 2026-03-17 at 12 35 39 PM" src="https://github.com/user-attachments/assets/4d5419a8-ab34-4e18-abf3-eb44be10f09f" />

* Visualized relationship between Feature1 and Feature2 using a scatter plot
* <img width="544" height="667" alt="Screenshot 2026-03-17 at 12 38 27 PM" src="https://github.com/user-attachments/assets/8b96ff97-047c-43bc-8b23-0e0913ee0599" />


## Data Preprocessing

Before building the model, the dataset was prepared using the following steps:

* Converted target variable from categorical values (Yes/No) to numerical values (1/0)
* Checked class distribution for imbalance
* 
* Split the dataset into training and testing sets

## Model Building

A Logistic Regression classification model was used to train the dataset and learn the relationship between the input features and the target variable.


## Decision Boundary Visualization

The decision boundary was plotted to visualize how the trained model separates the two classes based on Feature1 and Feature2.
<img width="492" height="405" alt="Screenshot 2026-03-17 at 12 40 54 PM" src="https://github.com/user-attachments/assets/121e1a3d-0086-4d4e-9ae2-0393e8f5bd65" />

## Model Evaluation

The performance of the classification model was evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report (Precision, Recall, and F1-score)
<img width="672" height="213" alt="Screenshot 2026-03-17 at 12 39 53 PM" src="https://github.com/user-attachments/assets/422cae74-5baf-48ca-b482-b701e8e4e79f" />

## Tools and Libraries Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
