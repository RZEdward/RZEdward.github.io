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

Overview: Develop a predictive model that forecasts the likelihood of a loan default based on historical loan performance data and borrower's financial attributes.
Skills Demonstrated: Risk analysis, handling time-series data, dealing with censored data (loans that have not yet defaulted), and model calibration for risk prediction.
Why It's Good: This project emphasizes risk management—a crucial aspect of financial services—and showcases your ability to predict and manage financial risk.

'What are the chances / binary classification that someone fails to pay back their loan'

Logistic Regression or Decision Tree / Random Forest?

Thumbnails: Logistic Regression Plot, Table of example customer info + risk prediction, Dalle of money burning up

<div style="display: flex;">
  <img src="/images/Graveler.png" alt="Image 2" style="width: 40%; border: 2px solid white; margin-right: 2px;">
  <img src="/images/CNN_Analytics.png" alt="Image 1" style="width: 60%; border: 2px solid white;">
</div>

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