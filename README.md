# EdTech Customer Lead Conversion Prediction

Predicts which prospective students are most likely to convert to paying customers for an online education platform, enabling more targeted sales and marketing efforts.

## Overview

The EdTech industry has grown rapidly, with the online education market projected to exceed $286B. For platforms like ExtraaLearn, identifying high-intent leads from a large pool of prospects is critical to efficient growth. This project builds classification models to predict conversion likelihood and surfaces the features that most influence a lead's decision to enroll.

## Dataset

The ExtraaLearn dataset contains 4,612 leads across 15 features including demographic data, engagement signals (website visits, time on site, page views), marketing channel interactions, and lead status.

## Approach

- Exploratory data analysis and sanity checks
- Feature encoding and preprocessing
- Model training and comparison across Decision Tree and Random Forest classifiers
- Hyperparameter tuning for optimal precision/recall tradeoff
- Feature importance analysis to guide sales and marketing prioritization

## Results

Models evaluated on accuracy, precision, recall, and F1-score with a focus on maximizing conversion capture while minimizing wasted outreach.

## Tech Stack

Python, pandas, NumPy, scikit-learn, matplotlib, seaborn, Random Forest, Tuned Random Forest
