---
#layout: archive
title: "Portfolio"
permalink: /project_portfolio/
author_profile: true
---

{% include base_path %}
<br>
Welcome! See my projects below. <!-- or contributions or competitions -->

<h2> Predictive Analysis for Loan Default Risk </h2>

Overview: This project contains a set of predictive machine learning models that return a binary classification forecast for loan defaults based on the profiles and repayment status of past borrowers. The models used include random forest, decision tree, and logistic regression provided by Sci-Kit Learn, as well as another logistic regression model built from scratch which serves as a comparison to pre-existing frameworks. The code may be viewed [HERE](https://github.com/RZEdward/Loan_Default_Risk) on my GitHub page. The images below display the field correlation heatmap (and includes key columns from the dataset) and a metrics table to compare the performance of each model.

<div style="display: flex;">
  <img src="/images/correlation_heatmap.png" alt="Image 2" style="width: 50%; border: 2px solid white; margin-right: 2px;">
  <img src="/images/model_performance.png" alt="Image 1" style="width: 50%; border: 2px solid white;">
</div>

<br>
Method: The first step was to retrieve a borrower history dataset from [Kaggle](https://www.kaggle.com/datasets/hemanthsai7/loandefault/data) and clean the data thoroughly. This involved renaming columns to enhance readability and accessibility, removing duplicates and invalid entries, rounding values, eliminating unnecessary fields, and more. After producing some preliminary visualisations to ensure the data aligns with expectations, a correlation heatmap was generated to identify any redundancy, and finally log scaling and boxcox techniques were applied to fields that lacked a natural Gaussian form. Next, we had to encode any categorical variables into numeric form, then employ SMOTE to generate more 'default' cases (as they were under-represented in the dataset), and, in our final stage of pre-processing, the data was scaled to ensure that variation in absolute value differences across fields was evenly weighted. Having completed data cleaning, EDA, feature engineering, and pre-processing, the models could then be imported and fit to the training data. 

As can be seen in the metrics table above, the built-in logistic regression and random forest models performed best among the set, and, as expected, the logistic regression model built from scratch performed relatively poorly due to a lack of complexity around convergence techniques, regularization, and hyperparameter tuning. Note that, in this context, we greatly value a high recall score as 'default' instances are rare, and it is of vital importance that we correctly predict each case in which a loan will/is highly likely to default.
<br>

<h2> Convolutional Neural Network: Gen-1 Pokémon Classifier </h2>

Here, I constructed a convolutional neural network (CNN) using Keras from TensorFlow and applied it to a dataset of first generation pokemon (downloaded from [Kaggle](https://www.kaggle.com/datasets/lantian773030/pokemonclassification/data)), with the aim of producing an accurate image recognition algorithm and correctly classifying pokemon when tested on unseen data.

Following some intensive efforts in preprocessing, hidden layer selections, and hyperparameter optimization, the model returns a training accuracy of around 80% after 20 epochs, having resized images to 256x256. However, the testing accuracy was considerably lower, and so I will soon introduce anti-overfitting techniques into the algorithm in order to enhance generalisation to unseen data. The report and code will be made available upon completion.

<div style="display: flex;">
  <img src="/images/Graveler.png" alt="Image 2" style="width: 40%; border: 2px solid white; margin-right: 2px;">
  <img src="/images/CNN_Analytics.png" alt="Image 1" style="width: 60%; border: 2px solid white;">
</div>

<!-- Need to professionalize images, nice font, white text, clean boundaries  test -->

<br>

<h2> An Insight Into London's Boroughs: Rental Market and Lifestyle </h2>

In this project I conducted extensive research into various key stats that one might consider before moving to London, and presented my results on a Tableau dashboard. Rental data was scraped from SpareRoom using Python's BeautifulSoup library, and much of the other information was sourced via downloadable CSVs (later processed using Pandas) or simply by manual copy and paste. Although a dataset of this size could have been managed in Excel, I chose to transfer it to PostgreSQL (after some data cleaning in Excel) in order to reinforce skills I had learnt during past work experience and online courses. Visit my Tableau Public [profile](https://public.tableau.com/app/profile/ross.edwards/vizzes) if you wish to interact with the dashboard and reveal tooltips.

<div style="display: flex;">
  <img src="/images/London_Dashboard.png" alt="Image 1" style="width: 100%; border: 2px solid white;">
</div>

<br>


<!--


<h2> Data Engineering Project </h2>

SQL / Python / Hadoop / Spark / AWS / Azure - Project to display competence in data engineering

![image](rzedward.github.io/images/500x300.png)

<br>

<h2> Project 4: Logistic Regression </h2>

Using built-in vs custom built logistic regression to identify neural tube defects. We are taking quantifiable features of the neural tubes rather than images here.

![image](rzedward.github.io/images/500x300.png)

<br>

<h2> Project 5: Time Series Forecasting </h2>

Let's build a time series forecast.

![image](rzedward.github.io/images/500x300.png)

<br>

Ideas:

END GOAL: END-TO-END DATA ENGINEERING PROJECT USING CLOUD (Python/SQL), END-TO-END MACHINE LEARNING PROJECT (C++), END-TO-END DATA SCIENCE PROJECT (R)

* Cobblestone Research Project
* Kaggle competitions
* Hackathon
* Excel Competition
* Open Source Contribution
* Teaching (YouTube?)

* Trading Bot
* Logistic Regression Project - disease classification
* NLP Sentiment Analysis
* Time Series Forecast for Sales Predictions (or in R for stock market forecasting)
* Ideally deploy these things using AWS/Docker/K8s

* Data Science / ML - ML Projects
* Data Analysis - Tableau Dashboard
* Data Engineering - Need a full End-to-end project - see projectpro website

-->