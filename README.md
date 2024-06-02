# Tech-Job-Salary-Prediction-Analysis


### Project Overview
The objective of this project was to analyze factors affecting salaries in the tech industry and build a predictive model to estimate salaries based on job-related features. The dataset used for this project was sourced from Glassdoor.com and is available on Kaggle.


### Dataset
* Source: [Glassdoor Job Salaries Dataset on Kaggle](https://www.kaggle.com/datasets/thedevastator/jobs-dataset-from-glassdoor)
* Description: The dataset contains information on 742 tech job positions, including 28 variables that capture various characteristics of the job positions and their corresponding salaries.


### Project Steps
1. <b>Data Collection</b>
* Collected job postings data from Glassdoor.com, covering the years 2017-2018
2. <b>Data Exploration and Analysis</b>
* Conducted initial data exploration to understand distributions and relationships using visualizations and correlation analysis
3. <b>Data Cleaning and Preparation</b>
* Removed missing values
* Converted categorical features to numerical ones using one-hot encoding
* Conducted feature engineering to create 14 new features and selected important features using correlation matrix and forward selection
4. <b>Model Building and Evaluation</b>
* Developed multiple machine learning models
* Identified Ridge regression as the best model with an alpha of 0.1, achieving a train R-squared of 78.9% and a test R-squared of 77.2%
5. <b>Final Inferences</b>
* Key factors affecting salaries were identified
* Ridge regression model demonstrated reliable performance on both seen and unseen data
* Geographical salary variations were analyzed and significant differences were confirmed through statistical tests


### Achievements and Results
- <b>Model Performance</b>: The Ridge regression model achieved a train R-squared of 78.9% and a test R-squared of 77.2%.
- <b>Feature Engineering</b>: Created 14 additional features, doubling the initial feature set and improving prediction accuracy.
- <b>Key Insights</b>: Identified key factors influencing job salaries and confirmed geographical variations in salary packages.


### Future Work
- Collect more data to improve model accuracy
- Ensure data quality by addressing missing or erroneous data points
- Experiment with other regression algorithms such as Support Vector Regression or Neural Networks
- Fine-tune model hyperparameters to enhance performance
- Deploy the model on a web page for user interaction and salary prediction


