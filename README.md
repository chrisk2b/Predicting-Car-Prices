
# Purpose of the Repository

This repository contains the results of the Data Science Nanodegree "Write a Data Science Blog Post" Project. Its’s purpose is to give the reviewers access to the code. 

# Overview 
This repository contains the technical aspects of Data Science Nanodegree "Write a Data Science Blog Post" Project. A non-technical summary can be found in a [blog post](https://medium.com/@christophberns/using-crisp-dm-to-predict-car-prices-f15eb5b14025).
The project applies the CRISP-DM process to the problem of predicting car prices based on certain attributes of cars.

# Files in the Repository
The repository contains the following files/folders:

 - *requirements.txt*:  This file contains the necessary libraries, see the section "How to Use iI" in this README.
 - *data*: The data folder contains the file [imports-85.data](https://github.com/chrisk2b/Predicting-Car-Prices/tree/master/data) which contains the data in csv-format. Each row in that file contains the features of a car and its price. The column names are not included in that file. The name of the columns and an explanation of each column can be found [here](https://archive.ics.uci.edu/ml/datasets/automobile).
 - *notebooks*: This folder contains the the Jupyter Notebook [*Predicting_Car_Prices.ipynb*](https://github.com/chrisk2b/Predicting-Car-Prices/blob/master/notebooks/Predicting_Car_Prices.ipynb) which contains the main analysis. The analysis in this notebook is structured according to the CRISP-DM process. Furter, the *notebook* folder contains a html-version of *Predicting_Car_Prices.ipynb*.
 - *README*: This README.
 
# Packages
The following packages are necessary to run the cells in  [*Predicting_Car_Prices.ipynb*](https://github.com/chrisk2b/Predicting-Car-Prices/blob/master/notebooks/Predicting_Car_Prices.ipynb):
 - pandas
 - numpy
 - sklearn
 - matplotlib

 # How To Use It
 All code is in the Notebook [*Predicting_Car_Prices.ipynb*](https://github.com/chrisk2b/Predicting-Car-Prices/blob/master/notebooks/Predicting_Car_Prices.ipynb).  Please assure that all dependencies which are mentioned in the section Packages have been installed. There is a requirements.txt file in the Repository which contains all relevant dependencies. You can install all dependencies from that file using pip via the command: _pip install -r requirements.txt_
 Further, the business questions as well as their answers are contained in *Predicting_Car_Prices.ipynb* in markdown cells. 
 

