# Springboard Data Science Mini Projects

### Data Wrangling

**[JSON Exercises](https://github.com/BradTombers/Springboard/blob/master/Mini%20Projects/JSON%20World%20Bank%20Project.ipynb):**
Using the World Bank projects dataset, I wrangle the data in order to find the 10 countries with the most projects, the top 10 project themes, and the column associated with the names of the major themes. I find that the category "Environment and natural resources management" is most prevalent. 

**[SQL Intermediate Tutorial](https://github.com/BradTombers/Springboard/blob/master/Mini%20Projects/sql_intermediate_tutorial):**
Using the website modeanalytics.com I generated a self-study worksheet to reference SQL queries.  



### Exploratory Data Analysis
**[Human Body Temperature](https://github.com/BradTombers/Springboard/blob/master/Mini%20Projects/human_temp_exercise.ipynb):**
I use the concepts of hypothesis testing, confidence intervals, and statistical significance to determine that what most people consider common knowledge about body temperature may be incorrect. 

**[Racial Discrimination](https://github.com/BradTombers/Springboard/blob/master/Mini%20Projects/sliderule_dsi_inferential_statistics_exercise_2.ipynb):**
Researchers examined the level of racial discrimination in the United States labor market by randomly assigning identical résumés to black-sounding or white-sounding names. In this notebook, I perform statistical analysis to establish whether race has a significant impact on the rate of callbacks for resumes.

**[Hospital Readmissions](https://github.com/BradTombers/Springboard/blob/master/Mini%20Projects/reduce_hospital_readmissions.ipynb):**
In October 2012, the US government's Center for Medicare and Medicaid Services (CMS) began reducing Medicare payments for Inpatient Prospective Payment System hospitals with excess readmissions. This report critiques a preliminary analysis of data and gives recommendations for reducing the readmissions rate.

### Machine Learning

**[Linear Regression - Predicting Boston Housing Prices](https://github.com/BradTombers/Springboard/blob/master/Mini%20Projects/Mini_Project_Linear_Regression.ipynb):**
Using the scikit-learn library, I perform exploratory data analysis and generate a model to predict home prices using the Boston Housing data set. To improve the model, I identify outliers and generate leverage plots.  My final model has 3 features: crime rate, number of rooms, and the pupil-teacher ratio.  

**[Logistic Regression - Predicting Gender from Height and Weight](https://github.com/BradTombers/Springboard/blob/master/Mini%20Projects/Mini_Project_Logistic_Regression.ipynb):**
In this project, I use cross-validation and grid search to tune my logistic regression model to predict gender from height and weight data.  Our goals are to find the best model in terms of model parameters, and maximize the models performance on unseen data.

**[Text Classification with Naive Bayes](https://github.com/BradTombers/Springboard/blob/master/Mini%20Projects/Naive_Bayes.ipynb):**
I learned the basics of text analysis using a subset of movie reviews from the rotten tomatoes database.  The goal is to be able to predict whether a movie will score "rotten" or "fresh" based on the text contained in the reviews.  In solving the problem I used CountVectorizer to model the text, and the MultinomialNB package from sklearn to generate the model. After fitting my inital model, I attempt to maximize the likelihood function to obtain the best possible model.  My favorite part of this project was finding the words that best indicated a "fresh" or "rotten" score.  Not suprisingly, the words were "entertaining" and "awful", respectively. 

**[Customer Segmentation using Clustering](https://github.com/BradTombers/Springboard/blob/master/Mini%20Projects/Mini_Project_Clustering.ipynb):**
Several datasets are provided containing data about wine offers and the customers that engaged with those offers.  Our goal is to cluster the customers to find what they have in common, in order to ultimately find more similar customers.  Throughout the notebook, I use KMeans, Affinity Propogation, Spectral, Agglomerative, and DBSCAN clustering in an attempt to find the optimal model. In order to choose the appropriate number of clusters, I use the silhoutte method, and generate plots to visualize each case. At the conclusion, I find the the greatest indicator of clustering is the customer's preference of varietal, as well as the minimum quantity required for purchase.  

### Take Home Challenges
**[Ultimate Inc. Take Home Challenge](https://github.com/BradTombers/Springboard/blob/master/Mini%20Projects/Ultimate_data_science_challenge.ipynb):**
Ultimate Technologies Inc. is an American worldwide online transportation network company headquartered in San Francisco, California. Founded by Jarvis Karolick in 2010, it has completely disrupted the taxi and logistics industry, and is one of the most prestigious companies to work for. This challenge has been adapted from an actual Ultimate Inc. data science challenge.

**[Relax Inc. Take Home Challenge](https://github.com/BradTombers/Springboard/blob/master/Mini%20Projects/relax_data_science_challenge.ipynb):**
Relax Inc. is a highly funded startup based in San Francisco that makes productivity and project management software that's extremely popular with both individuals and teams. Founded in 2008 by several ex-Facebook employees, it's considered one of the sexiest companies to work for.
