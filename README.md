# BorrowerDefault
Udemy Python for Data Science and Machine Learning Bootcamp - Final Project

## Abstract / Introduction
LendingClub is a US peer-to-peer lending company, headquartered in San Francisco, California. It was the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission (SEC), and to offer loan trading on a secondary market. LendingClub is the world's largest peer-to-peer lending platform.

Using historical data on loans that has information on whether or not a borrower defaulted (charge-off), we built a model to predict wether or not a borrower will pay back their loan. This will allow the company to have an ability to predict if a new potential customer is likely to pay back the loan.

The best "f1_score" for "class 0" of 66% was acheieved using an "Artifical Neural Network" (ANN) with random oversampling of the dataset, to mitigate against the clear imbalances in the dataset. But by focusing the predictive power of the model on the "f1_score" for "class 0" there has been compromises in the performance of the model in other areas. However as the objective of this project was focused on predicting borrower defaults, such compromises are considered acceptable.

## Files in the repository
**lending_club_info.csv** - This .csv file that contains the core data that is analysed in this project.

**Keras-Project_BorrowerDefaultPrediction.ipynb** - The main jupyter notebook file for this project that contains all the python and r markdown code that is displayed in the final .pdf report.

**Keras-Project_BorrowerDefaultPrediction.pdf** - Simply .pdf print of the main jupyter notebook.


