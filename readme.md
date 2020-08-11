# Data Wrangling

### Introduction
This repo is a part of Data Wrangling course in [udacity](https://udacity.com) Data Analysis Professional Nanodegree

### Dataset
The dataset we used here is [Armenian Online Job Postings](https://www.kaggle.com/udacity/armenian-online-job-postings) from [kaggle](https://www.kaggle.com)
19,000 online job postings from 2004 to 2015 from Armenia's CareerCenter.

### Lesson one (Introduction to data wrangling)
1- Gathering Data
* downloading a file from the internet, which in this case was a zip file from Kaggle,
* opening a Jupyter Notebook,
* unzipping the zip file using Python,
* then importing the extracted CSV file into a pandas DataFrame in the Jupyter Notebook.

2- Assessing Data</br>
So far we identified the following issues in the data:
* Nondescriptive column headers
* Missing values (i.e. NaNs)
* Inconsistent representations of values, specifically "As soon as possible" and other similar values to "ASAP" in the StartDate column for this dataset
* A messy (i.e. untidy) dataset

3- Cleaning Data
* Define
  * Select all nondescriptive and misspelled column headers (ApplicationP, AboutC, RequiredQual, JobRequirment) and replace them with full words (ApplicationProcedure, AboutCompany, RequiredQualifications, JobRequirement)
  * Select all records in the StartDate column that have "As soon as possible", "Immediately", etc. and replace the text in those cells with "ASAP"
  
* Code

* Test

4- Storing Data (Optional)
* After reassessing your data and revisiting any steps of the data wrangling process deemed necessary, storing your cleaned data can be the next logical step. Storing data is important if you need to use your cleaned data in the future.

![](Images/party.gif)
