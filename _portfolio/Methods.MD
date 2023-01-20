---
title: "Quantitative Methods"
excerpt: "A multi-predictor model to predict hyperinsulenima in patients"
header:
  image: /assets/img/Cyber-Scooter-Banner.jpg
  teaser: /assets/img/Cyber-Scooter-TH.jpg
gallery:
  - url: /assets/img/Cyber-Scooter-1.jpg
    image_path: assets/img/Cyber-Scooter-1.jpg
    alt: "placeholder image 1"
  - url: /assets/img/Cyber-Scooter-2.jpg
    image_path: assets/img/Cyber-Scooter-2.jpg
    alt: "placeholder image 2"
  - url: /assets/img/Cyber-Scooter-3.jpg
    image_path: assets/img/Cyber-Scooter-3.jpg
    alt: "placeholder image 3"
---

Objective: Previous research shows strong correlations between weight, alcohol use, race, and age. However, these relationships have not been leveraged to build multiple predictor linear models using NHANES datasets. In the present study, we aim to evaluate the efficacy of linear models based on weight, alcohol use, race, and age in predicting insulin concentrations.

Materials and Methods: Data on insulin concentration, weight, age, race, and alcohol consumption was imported from the NHANES website. Preliminary analysis of the data includes sorting and scrubbing techniques, ROC plots, and Cohens' f2 analysis to assess which of the independent variables show a significant effect on insulin concentration. MLR is used to create a model from our training set (n = 649) that predicts insulin concentration. An F-test of equal/unequal variance is used to analyze our model for differences in performance by race. An experiment is run 150 times with a replication set (n = 48 from a sample of 1402). The mean and variance in specificities are calculated and compared to the baseline specificity from the training set using a T-test.

Results: Our linear model classifies the majority of patients as negative for hyperinsulinemia. A T-test of mean specificities also indicates that the model does not offer equivalent performance for the 2015-2016 dataset compared to the 2017-2018 dataset. Our linear model for insulin prediction underestimates true insulin levels and does not accurately classify subjects.

Conclusions: Our linear model built via multiple linear regression using weight, alcohol use, race, and age is not a feasible alternative for predicting insulin concentrations. However, analysis of the predictors offers guidance for future research; weight and race, for example, are the strongest predictors of insulin concentrations. Moreover, future research should acknowledge bias in predictive insulin models based on race. Future insulin models may also leverage additional predictors like gender and dietary information.
{% include gallery caption="This is a sample gallery to go along with this case study." %}
