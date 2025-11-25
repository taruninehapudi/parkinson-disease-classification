# parkinson-disease-classification
Project Overview

• Machine learning project to classify Parkinson’s disease based on biomedical voice measurements
• Includes exploratory data analysis, visualization, and predictive modeling
• Supports early diagnosis using quantifiable voice features

Objectives

• Explore key voice-based biomedical features
• Compare Parkinson vs healthy samples
• Build ML classification models
• Evaluate performance using accuracy and classification metrics
• Identify most influential predictors

Tools Used

• Python
• Pandas
• NumPy
• Matplotlib
• Seaborn
• Scikit-learn
• Jupyter Notebook

Files in This Repository

• parkinson_classification.ipynb — Main notebook
• sample_parkinson.csv — Sample dataset
• README.md — Documentation

Dataset Source

• UCI ML Repository — Parkinson’s Biomedical Voice Dataset

Important Note (Path Adjustment Required)

• The notebook currently loads the dataset using a local machine path
• Users must update this to their own path or use the sample dataset
• This ensures proper execution on any system

Key Insights

• Parkinson’s patients show distinctive vocal feature patterns
• Strong differences observed in jitter, shimmer, and HNR measures
• Correlation analysis reveals clusters of related voice metrics
• Model feature importance highlights top predictive biomarkers

Modeling Summary

• Logistic Regression, Random Forest, and SVM models tested
• Strong classification accuracy achieved
• Random Forest/SVM typically provide the best performance
• Confusion matrix shows reliable prediction results

Clinical Recommendations

• Use model output to support early-stage clinical screening
• Prioritize individuals showing high-risk feature combinations
• Combine ML predictions with clinical evaluations for accuracy
• Encourage further data collection for enhanced model reliability

How to Run

• Download the repository
• Place the sample dataset in the same folder as the notebook
• Open the notebook in Jupyter
• Adjust the dataset path if required
• Run all cells in order
