# Group-32---new

# Welcome to our project in GitHub. 

In this project we try to predict house prices in Copenhagen, using the LASSO and RIDGE regression models. Our research question is: What impact do macroeconomics factors have on predicting apartment prices in Copenhagen?

## The data
We partly webscraped our data from Boliga.dk. We provide you with the code of the webscraping. This code is stored in the 'Web_scraping.ipynb' file. Please make sure to download Jupyter on your local computer (in combination with the Anaconda terminal). However, be aware that the practice of web scraping comes with ethical issues. If you want to run our code, please ask Boliga.dk for permission first. Also, always identify yourself.

## The code
In order to help you understand this project, we will briefly explain how our project works. Follow the following steps to get up and running:
1) Download the output.csv file and store it on your local computer. Remember the URL, as you will need it later on.
2) Open the CodeForML_final.ipynb file.
3) Follow the steps in the CodeForML.ipynb file.

## Overview of the files
These are the most important files in our GitHub repository:
- Newest version of the notebook is Cleaning_data.ipynb
- output.csv is the cleaned data set 
- combined.csv is the data set uploading in the notebook
- Web_scraping.ipynb is the code for the web scraping
- CodeForML_final.ipynb is the code for the machine learning models

## Conclusion of our project
Through machine learning, we optimized hyperparameters and weights to predict house prices. Initial models were trained on Boliga.dk's web-scraped data (rooms, kr/m2, m2, postal code) merged with macroeconomic factors (loan interest rate, inflation, salary, GDP). Data details, scraping, cleaning, and statistics were documented. Feature selection, influenced by correlations and literature, guided our choice of variables. Employing LASSO and RIDGE regression models with polynomial features, we aimed to capture data intricacies and balance bias-variance trade-offs using time-series cross-validation.

Our findings highlighted a dominant LASSO regression model with two polynomial degrees as the strongest predictor of unseen data. The mean squared error, with an optimized λ of 1873.82, stood at 9,700,939,201.857. Despite this, evaluation of learning and validation curves raised concerns of overfitting. Subsequent research may explore increasing training data, refining hyperparameters, or alternative models to enhance generalization.

In conclusion, the postal code emerged as the most influential feature for Copenhagen house price prediction, evidenced by the LASSO model attributing the highest weight (9446.227) to it. Acknowledging our research's limited feature scope, future research should consider additional variables to ascertain the model's broader generalization potential.

# Any suggestions for further improvement
Please contact us if you have any suggestions for further improvement. We're always happy to review suggestions and improving our code. We're aware of certain limitations of our model, as we didn't have unlimited time for this project (i.e., about three weeks). You could read our initial thought off limitations in the final project. Please commit your changes and we will try to review it. Kind regards, David (@dave010339), Katrine, and Sofie.

# Last comments
Nevertheless, we are happy that we've learned a **lot** during the course of this project. We all started with no to limited knowledge of Python, Jupyter, webscraping and machine learning in general. We've come such a far way and managed to deliver a quite complicated paper in just three weeks. We also want to thank the supporting staff of the Copenhagen University which made this project possible.
