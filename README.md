# KJ Marketing Customer Segmentation Project

## Overview
This repository contains the code, data, and documentation for the KJ Marketing customer segmentation project. The project aims to classify new customers into relevant segments based on their purchasing behavior using historical sales data.

## Project Context
KJ Marketing, a leading retail supermarket chain in Sri Lanka, has identified the ineffectiveness of traditional marketing strategies for its current customer base. To enhance its marketing efforts, the company seeks to adopt a personalized marketing strategy tailored to individual customer preferences.

## Objectives
- Develop an analytical solution to classify new customers into predefined customer segments.
- Address key questions related to data preprocessing, feature selection, model training, and evaluation.
- Enhance the effectiveness of KJ Marketing's marketing strategies based on the classified clusters.

## Data
The project utilizes historical sales data provided by KJ Marketing, including average monthly sales per customer across different product categories:
- **Dry Goods**
- **Fresh Produce**
- **Luxury Items**

### Datasets
- **train.csv**: Used for model training and testing.
  - **Variables**: customer_id, outlet_city, luxury_sales, fresh_sales, dry_sales, cluster_category.
- **test.csv**: Used for model evaluation.
  - **Variables**: customer_id, outlet_city, luxury_sales, fresh_sales, dry_sales.

## Methodology
### Data Preprocessing
- Address missing values, duplicates, and outliers.
- Convert categorical variables to numeric format using label encoding.
- Apply feature scaling using robust scaling techniques.

### Exploratory Data Analysis (EDA)
- Univariate and multivariate analysis to understand data structure and quality.
- Visualizations such as histograms, scatter plots, box plots, and correlation matrices.

### Model Selection
Five machine learning models were considered:
1. **Logistic Regression**
2. **K-Nearest Neighbors (KNN)**
3. **Decision Tree**
4. **Random Forest**
5. **Gradient Boosting**

### Model Evaluation
- Accuracy, MSE, R², precision, recall, confusion matrix, and overfitting checks.
- Final model selected: **Random Forest** due to its high performance, ability to handle complex datasets, and interpretability.

## Results
The Random Forest model achieved high accuracy and recall, making it suitable for classifying customer segments effectively. The model's feature importance analysis provides valuable business insights for strategic decision-making.

## Repository Structure
- **Models/**: Contains files for model building and evaluation.
- **Exploration and Cleaning.ipynb**: Jupyter notebook for data exploration and cleaning.
- **README.md**: Project overview and instructions.



## Contributors
- **Iffath Saleem**
- **Govindu Sathruwan**
- **Shahik Shiyam**
- **Abdullah Sheriffdeen**

## Acknowledgements
We express our sincere gratitude to our lecturers and project supervisors, Mr. Fouzul Hassan and Ms. Sapna Dissanayaka, for their mentorship and guidance. We also thank the team at Octave for collaborating with this module and providing valuable industry insights.
