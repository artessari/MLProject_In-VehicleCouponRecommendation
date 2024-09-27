# In-Vehicle Coupon Recommendation 
### Machine Learning Project

This project explores the application of various machine learning models to predict whether a user will accept an in-vehicle coupon based on demographic, contextual, and coupon-specific factors. The project is based on a dataset from the UCI Machine Learning Repository (retrievable from https://archive.ics.uci.edu/dataset/603/in+vehicle+coupon+recommendation) and focuses on classification techniques.

This project was developed as part of the **Machine Learning course** at the **Free University of Bolzano**.

## Project Overview

The objective is to classify whether a customer will accept a coupon based on features like user demographics, the destination, and the specifics of the coupon. The key stages of the project are:

- Data Preprocessing
- Model Training & Evaluation
- Comparison of Model Performance

## Directory Structure

```
├── in-vehicle-coupon-recommendation.csv     # Dataset in CSV format
├── in-vehicle-coupon-recommendation.xlsx    # Dataset in XLSX format
├── MLProject_TessariArianna_19322.ipynb     # Main Jupyter notebook with code
├── MLProject_TessariArianna_19322.html      # Exported HTML version of the notebook
├── MLReport_TessariArianna_19322.pdf        # Final report in PDF format
├── requisites.txt                           # Dependencies for the project (use to recreate environment)
└── README.md                                # Project README file
```

## Key Files
- MLProject_TessariArianna_19322.ipynb: The main notebook that contains data preprocessing, exploratory data analysis (EDA), model training, and evaluation.
- in-vehicle-coupon-recommendation.csv: The dataset used for training and testing the models.
- MLReport_TessariArianna_19322.pdf: A detailed report that discusses the objectives, methodology, and conclusions.
- requisites.txt: The list of Python dependencies required to run the project.

## How to Run

**1. Clone the repository**
```
git clone https://github.com/artessari/MLProject_In-VehicleCouponRecommendation
cd MLProject_In-VehicleCouponRecommendation
```

**2. Install Dependencies**

To install the required Python libraries, run:
```
pip install -r requisites.txt
```

**3. Run Jupyter Notebook**

To explore the project interactively, launch the notebook.

## Models Implemented

The project explores the following machine learning models:

- Linear Classifiers: Logistic Regression and Support Vector Machine (SVM)
- Decision Tree
- K-Nearest Neighbors
- Non-Linear Support Vector Machine
- Naive Bayes
- Random Forest
- Neural Network

Each model was evaluated based on accuracy, precision, recall, F1 score, and ROC-AUC.

## Results

Neural networks and Random Forest demonstrate higher classification accuracy but require longer training and testing times, while simpler models like Logistic Regression and Decision Trees offer faster performance with slightly lower accuracy. A consistent trend shows better prediction for class 1 than class 0, highlighting the need to balance model effectiveness and efficiency based on application requirements.

**Model Performance Summary:**

| Model               | Accuracy | Precision | Recall  | F1 Score |
|---------------------|----------|-----------|---------|----------|
| Logistic Regression  | 66.03%   | 68.82%    | 73.88%  | 71.23%   |
| SVM                 | 65.35%   | 68.42%    | 72.87%  | 70.56%   |
| Decision Tree       | 65.83%   | 69.29%    | 72.02%  | 70.53%   |
| KNN                 | 66.07%   | 66.41%    | 82.06%  | 73.39%   |
| Non-Linear SVM       | 69.34%   | 71.67%    | 76.58%  | 74.00%   |
| Naive Bayes         | 58.19%   | 67.35%    | 51.57%  | 57.13%   |
| Random Forest       | 72.08%   | 73.11%    | 80.87%  | 76.74%   |
| Neural Network      | 72.22%   | 74.00%    | 79.11%  | 76.47%   |

## Conclusions

Both Neural Networks and Random Forests are highly effective for this classification problem, but simpler models like Logistic Regression also provide solid results with lower computational costs. The project demonstrates the use of machine learning techniques for real-world predictive tasks and provides insights into model selection based on performance and efficiency.

### References
In-Vehicle Coupon Recommendation. (2020). UCI Machine Learning Repository. https://doi.org/10.24432/C5GS4P.