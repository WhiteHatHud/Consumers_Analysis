# Welcome to Consumers_Analysis

## About

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) that answers the question:
How can we maximize the frequency of online shopping purchases of consumers respective to males and females?
Note: Bi-weekly,Fortnightly and weekly are considered frequent.
from this dataset: [Behavior and shopping habits dataset](https://www.kaggle.com/datasets/zeesolver/consumer-behavior-and-shopping-habits-dataset "Named link title")

Detailed walkthrough:
1) Explonatory Data Anlysis
2) Data Preparation
3) Analytic visualisation
4) Random Forest
5) Outcomes and Insights


## Contributors 
- Adrian : Random forest, Outcomes and Insights
- Hudzaifah : EDA, Analytic Visualisation
- Jun Hern: Data Preparation, Outcomes and Insights

## Problem Defination
Is there a relationship between gender and their purchasing behavior evident in the Consumer Behavior and Shopping Habits Dataset? Do certain age groups or genders show preferences for specific product categories or shopping channels? Do females have a certain preference in their shopping habits compare to males?

Mainly categorical predictors and categorical response. Hence, we neede to explore our options of ML Techniques.

## Models used

i) Random Forest
ii) Classification Tree

## Conclusions

- None of the numeric variables had correlation with each other. Their values were all below 0.1 . Hence we needed to focus on categorical variables
- From domain knowledge and EDA, we identified important variables
- Since gender was overly imbalanced, we up-sampled the dataset
- Accuracy was a huge problem in Random Forest Classification
- However after dropping irrelavent categorical values, Accuracy is about 65%
- For the males, accuracy was higher // ask ad to explain . i forgot

## What did we learn 
- Random Forest Classification to predict categorical with another categorical variable.
- Working with mainly categorical variables
- Sampling techniques
- Github platform
- One-hot encoding to seperate sub cateogries in a category
  
## References
- https://www.kaggle.com/datasets/zeesolver/consumer-behavior-and-shopping-habits-dataset
- https://www.analyticsvidhya.com/blog/2021/06/understanding-random-forest/
- https://www.microsoft.com/en-sg/
- https://jupyter.org



