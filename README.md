# Early_Warning_System

This repository contains three AI/ML projects completed as part of an internship with **Oakland Natives Give Back**. These projects apply advanced machine learning techniques, including deep learning, sentiment analysis with BERT, and predictive modeling for chronic absenteeism.

## Projects Overview

### 1. Advanced AI & ML Techniques & Model Fine-Tuning
- **Objective**: Implement and optimize advanced machine learning techniques to predict chronic absenteeism beyond school days missed.
- **Key Approaches**:
  - Deep learning models using TensorFlow.
  - Reinforcement learning for decision-making in absenteeism prediction.
  - Ensemble methods such as Random Forests and Gradient Boosting.
  - Hyperparameter optimization through Grid Search and Bayesian Optimization.
- **Deliverables**:
  - Jupyter Notebook containing all implementations.
  - Model performance visualizations.
  - Executive report summarizing results and key insights.

**Project Folder**: `advanced_ml_absenteeism/`

### 2. Sentiment Analysis with BERT
- **Objective**: Fine-tune a BERT model to classify tweet sentiment (positive/negative) across five categories.
- **Key Approaches**:
  - Data collection of 500 tweets across business, politics, fashion, entertainment, and technology.
  - Data cleaning, including removal of retweets, hashtags, mentions, and URLs.
  - Fine-tuning a pre-trained BERT model for binary sentiment classification.
  - Evaluation using accuracy, precision, recall, F1-score, and confusion matrix.
- **Deliverables**:
  - Preprocessed dataset in CSV format.
  - Fine-tuned BERT model.
  - Performance metrics and confusion matrix visualization.
  - Report analyzing model performance and improvements.

**Project Folder**: `sentiment_analysis_bert/`

### 3. Predicting Chronic Absenteeism for 2023-2024
- **Objective**: Develop predictive models for chronic absenteeism using historical data from seven schools over seven academic years.
- **Key Approaches**:
  - Data preparation by splitting datasets into two groups: below Grade 6 (excluding GPA) and Grade 6 and above (including GPA).
  - Feature engineering incorporating attendance trends, ethnicity, fluency, and GPA.
  - Model training and validation using Confusion Matrix, AUC Score, Precision, Recall, and F1-score.
  - Future predictions for students in the 2024-2025 academic year.
- **Deliverables**:
  - Jupyter Notebook with data preprocessing and model training.
  - Evaluation metrics report summarizing model performance.
  - CSV file containing absenteeism predictions for the 2024-2025 academic year.

**Project Folder**: `chronic_absenteeism_prediction/`

## Installation Instructions

To set up the environment and run the projects, install the required dependencies:

```bash
pip install -r requirements.txt
