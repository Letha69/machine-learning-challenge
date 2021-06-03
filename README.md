# Machine Learning Homework - Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)

## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data, two machine learning models are created which are capable of classifying candidate exoplanets from the raw dataset.

Steps to Creating the Models:

1. Preprocessed the raw data

- Preprocess the dataset prior to fitting the model.
- Perform feature selection and remove unnecessary features.
- Use `MinMaxScaler` to scale the numerical data.
- Separate the data into training and testing data.

2. Tuned the models

- Used `GridSearch` to tune model parameters.

3. Quantified the models
   Found the best score from the trained GridSearch model.

### Findings

The SVM had a slightly higher accuracy, (0.87). The scores of the hypertuned GridSearch models slightly increased when compared to the test scores of the regular SVM and Logistic Regression models.

---

## Resources

- [Exoplanet Data Source](https://www.kaggle.com/nasa/kepler-exoplanet-search-results)

- [Scikit-Learn Tutorial Part 1](https://www.youtube.com/watch?v=4PXAztQtoTg)

- [Scikit-Learn Tutorial Part 2](https://www.youtube.com/watch?v=gK43gtGh49o&t=5858s)

- [Grid Search](https://scikit-learn.org/stable/modules/grid_search.html)

---

---

© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
