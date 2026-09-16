# Predicting Skincare Reaction Risk Using NLP & Machine Learning

## Overview
This project develops an end-to-end machine learning pipeline to
identify patterns associated with skincare reaction risk using
consumer reviews and product ingredient data.

The analysis combines NLP-based review classification with
ingredient-level machine learning to examine which product
characteristics are associated with different reaction-risk groups.

## Dataset
- 1M+ consumer reviews
- 2,400+ skincare products
- 6,000+ ingredient features

## Approach
1. Cleaned and processed large-scale consumer review data
2. Engineered NLP-based concern indicators with negation handling
3. Aggregated review signals to the product level
4. Used K-means clustering and PCA to identify product risk segments
5. Trained a multinomial logistic regression model using ingredient
   features to predict reaction-risk groups

## Results
- Identified distinct product segments based on reported reaction risk
- Built a model using 6,000+ ingredient features
- Achieved approximately 65% classification accuracy

## Technologies
Python • pandas • NumPy • scikit-learn • Jupyter Notebook
