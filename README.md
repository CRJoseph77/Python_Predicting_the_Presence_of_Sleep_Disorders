![](Python_sleep_coverphoto.PNG)
# Predicting the Presence of Sleep Disorders using Python
Using sleep, lifestyle, and health data to predict the presence of sleep disorders with Python.

## Project Overview
This project uses sleep, lifestyle, and health data combined with supervised machine-learning techniques to predict the presence of sleep disorders. The dataset contains health data, such as heart rate and blood pressure, as well as lifestyle data, such as activity level and BMI category. It also contains information about sleep patterns, such as sleep duration, quality of sleep, and whether or not a sleep disorder is present.

Exploratory data analysis was performed, including visualization, cleaning, structuring, and validation. Data was then prepared for modeling. Three classification models were created and evaluated. A logistic regression model was fit to the data and evaluated, followed by a random forest model and finally a gradient boosting model. Models were tuned and evaluated, and the most predictive features from the data were identified. 

## Installation and Setup
### Code and Resources Used
Editor Used: This project was completed in an online Jupyter Notebook.

Python Version: Python version 3. 

### Python Packages Used
Data manipulation: pandas, numpy.

Data visualization: matplotlib, seaborn.

Machine learning: scikit-learn, xgboost.

## Data
Source data: The data used for this project was a dataset containing sleep, lifestyle, and health data downloaded from Kaggle: https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset.

Preprocessing: No preprocessing was performed prior to uploading the dataset to the Jupyter Notebook. 

## Code Structure
1. Importing packages and data - Relevant packages and the dataset were loaded into the Jupyter Notebook.

2. Exploratory data analysis - The general structure and format of the data were explored, as well as descriptive statistics. Inconsistencies and issues with the data were examined. Visualizations were created to inspect the distribution of the data.

3. Cleaning and structuring - The data was cleaned and structured. The data was checked for missing values and duplicates, and those values were addressed. Columns were cleaned and formatted properly. Data was encoded to prepare it for modeling. Outliers were identified and examined. Cleaning and structuring were validated and visualizations were created to examine data relationships. 

4. Modeling - Data was prepared for modeling and separated into feature and target datasets. A logistic regression model was fit to the data and evaluated. Next, a random forest model was fit to the data and evaluated. The model was then tuned and a second random forest model was created and evaluated. Finally, a gradient-boosting model was created, tuned, and evaluated. Important predictive features from all three models were explored. 

## Results and Evaluation
Data was successfully cleaned and structured, and the three models were successfully created and evaluated. The model with the best performance was the logistic regression model, with an F1 score of 0.82. The tuned random forest model did not perform as well as the logistic regression model, with an F1 score of 0.77. The gradient boosting model performed the worst, with an F1 score of 0.69. The most predictive features that were identified as being predictive by all three models were blood pressure and heart rate. This suggests that examining an individual's health metrics can be useful in determining and predicting the presence of a sleep disorder. 

It should be noted that there are a few limitations to these conclusions, namely the limited size of the dataset used to train these models. 

## Future Work
The primary goal of future work would be to use a dataset that is more comprehensive and has more data. This would ensure that the models would be generalizable and not overfit the model to the available data. Other factors that influence sleep and health could be explored, such as diet or sleep routine. The relationship between blood pressure, heart rate, and sleep could be further examined to improve outcomes for individuals with sleep disorders and to improve the ability to predict and treat those disorders. 

## References
Kaggle Data: https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset.

## License
The license associated with the data used for this project is CC0: Public Domain.

