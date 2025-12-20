# Loan Default Risk Analysis

An end-to-end data analytics project focused on analyzing loan default risk using Excel, Python, and Power BI. The project prioritizes insight discovery and pattern analysis, followed by training a basic machine learning model to validate findings.

This project demonstrates a practical analytics workflow from raw data to insights and prediction.

## Project Overview

Loan defaults pose significant financial risks for lending institutions. Understanding borrower behavior and risk factors is essential for improving lending decisions and minimizing losses.

This project aims to answer questions such as:

• What factors are most associated with loan default?  
• How do income, loan amount, and credit history influence default risk?  
• Can basic machine learning help validate analytical insights?

The approach is **insight-first**, where exploratory analysis and visualization are completed before applying prediction models.

## Dataset Description

The dataset used in this project is sourced from Kaggle and contains anonymized loan and borrower information.

🔗 **Dataset Link (Kaggle):**  
https://www.kaggle.com/datasets/nikhil1e9/loan-default

### Dataset includes:

• Applicant income and employment details  
• Loan amount and loan term  
• Credit history indicators  
• Loan purpose and demographic attributes  
• Loan status (Default or Non-Default)

> Note: The dataset is not included in this repository due to size and licensing considerations. Please download it directly from Kaggle.

## Tools and Technologies

• Microsoft Excel for initial data exploration and cleaning  
• Python (Pandas, NumPy, Matplotlib, Scikit-learn) for analysis and modeling  
• Power BI for interactive dashboards and visualization  
• Jupyter Notebook for documenting the analysis workflow  

## Key Analysis Focus

• Data cleaning and preparation  
• Identifying patterns and trends related to loan default risk  
• Visualizing high-risk borrower segments  
• Training a simple and interpretable machine learning model  
• Evaluating model performance using standard classification metrics  

Machine learning is used as a **supporting step**, not the main objective.

## Machine Learning Component

After discovering key insights, a basic classification model was trained to predict loan default outcomes.

• Focused on simplicity and interpretability  
• Used standard machine learning algorithms  
• Evaluated using accuracy, confusion matrix, and classification report  

This step helps validate insights obtained during exploratory analysis.

## Repository Structure

<pre>
Loan-Default-Risk-Analysis
├── README.md
│
├── Analysis
│   └── Loan_Default_Analysis.ipynb
│
├── Model
│   └── Loan_Default_Model.ipynb
│
├── Visualization
│   └── Loan_Default_Dashboard.pbix
│
└── Presentation
    └── Loan_Default_Project_Presentation.pptx
</pre>

## How to Use

1. Clone the repository:
git clone https://github.com/aliraza-data/Loan-Default-Risk-Analysis.git
2. Download the dataset directly from Kaggle using the provided link.
3. Open the Jupyter notebooks to review analysis and modeling steps.
4. Open the Power BI dashboard to explore interactive insights.

## Project Outcome

This project highlights an insight-driven data analytics workflow and demonstrates how analytical findings can be supported using basic machine learning. It reflects practical skills relevant to entry-level data analyst roles.

## Contributions

Suggestions and improvements are welcome. Feel free to fork the repository or open an issue for discussion.

## Reference

Loan Default Dataset  
Source: Kaggle  
https://www.kaggle.com/datasets/nikhil1e9/loan-default
