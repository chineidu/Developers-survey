# Developer's Salary Prediction App

## Summary

This web app was created using [streamlit](https://https://streamlit.io). It uses the Stack Overflow Annual Developer Survey data to  predict and explore the salary of developers from various countries.

### Dataset

The 2020 version of the survey [data](https://insights.stackoverflow.com/survey/) was obtained from Stack Overflow. The dataset contains about 64461 respondents (rows) who participated in the survey with 61 data points (columns) on the respondents. The target feature **'ConvertedComp'** which is the salary in US Dollars was predicted using some of the features in the dataset.

### Data Cleaning

Important features (data points) in the dataset were selected and further preprocessing was carried out. Outliers and aberrant values were also properly handled before statistical modelling could be carried out.

### Data Exploration

* The data contains a lot of outliers which is to be expected since it's a survey from various regions in the world. 
* On average, most developers earn about USD 60,000 with some earning as high as USD 2,000,000. 
* Most of respondents (20%) are from the United States followed by India (13%). Nigeria (~1%) has the highest number of respondents from Africa
* After the data cleaning, it can be seen that most developers have a Barchelor's degree.
![EdLevel](https://drive.google.com/file/d/1-Ou6ci-UMGi1f8nbcEnSQdeP2jFk6bEE/view?usp=sharing)

### Model Building and Performance

Several regression models were built but after the models were evaluated, Random Forest regressor gave the best performance. It was further improved by hyperparameter tuning.

### Model Deployment

Further information will be provided.
