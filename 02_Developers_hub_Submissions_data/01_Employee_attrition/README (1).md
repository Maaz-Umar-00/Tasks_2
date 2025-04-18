<div align= "center">
    <h2> IBM-HR-Analytics-Employee-Attrition-and-Performance-Prediction </h2><br>
</div>

<div align= "center">
    <img src="https://media0.giphy.com/media/3o85xGdsSCHfTPBJok/giphy.gif?cid=ecf05e47l31i9etrpyq28fkfu8e6m1kpgrwngdx1ga4zx5n6&rid=giphy.gif&ct=g">
</div>

### ✍️ HR ANALYTICS

HR analytics is the process of collecting and analyzing Human Resource (HR) data in order to improve an organization’s workforce performance. The process can also be referred to as talent analytics, people analytics, or even workforce analytics. This method of data analysis takes data that is routinely collected by HR and correlates it to HR and organizational objectives. Doing so provides measured evidence of how HR initiatives are contributing to the organization’s goals and strategies.

### 📍 OBJECTIVE

Employee attrition is the rate at which employees leave a company. The goal of this analysis is to model employee attrition and determine the most dominant contributing factors that govern this turnover. Through this kind of analysis, we can understand how many employees are likely to leave, while also determining which employees are at the highest risk and for what reasons.

### 😇 MOTIVATION

The project stems from the potential to improve employee satisfaction, reduce costs, enhance organizational performance, and create a positive workplace culture. It's an opportunity to use data and analytics to make meaningful changes that benefit both employees and the organization as a whole.

#### The methodology for IBM-HR-Analytics-Employee-Attrition-and-Performance-Prediction is as follows:-

```
- Load the Dataset: The IBM HR Analytics Attrition Dataset is loaded using the pd.read_csv() function. The head() and info() methods are used to display the first few rows and get information about the dataset, respectively.
- Knowing the Dataset: Basic Information about the dataset is generated; numerical and categorical attributes are enlisted.
- Data Cleaning: Any missing values in the dataset are dropped using the dropna() method.
- Data Visualization: Matplotlib and Seaborn libraries are used to visualize the data. 
- Data Preprocessing: The target variable 'Attrition' is mapped to binary values (1 for 'Yes' and 0 for 'No'). Selected features are extracted from the dataset and one-hot encoded using the get_dummies() function.
- Splitting the Dataset: The dataset is split into training and testing sets using the train_test_split() method from scikit-learn.
- Implementing Machine Learning Algorithms: Logistic Regression, Random_forest.
- Model Evaluation: The accuracy score and confusion matrix are computed to evaluate the performance of each algorithm on the testing data.
- Results: The results, including the accuracy and confusion matrix, are printed for each algorithm.
```

### 📁 DATASET

This is a hypothetical dataset created by IBM data scientists. The dataset has (1470R X 35C) that contains numeric and categorical data types describing each employee’s background and characteristics, and labeled with whether they are still in the company or whether they have gone to work somewhere else.

#### Dataset Attributes

```
01] Age
02] Attrition
03] BusinessTravel
04] DailyRate
05] Department
06] DistanceFromHome
07] Education
08] EducationField
09] EmployeeCount
10] EmployeeNumber
11] EnvironmentSatisfaction
12] Gender
13] HourlyRate
14] JobInvolvement
15] JobLevel
16] JobRole
17] JobSatisfaction
18] MaritalStatus
19] MonthlyIncome
20] MonthlyRate
21] NumCompaniesWorked
22] Over18
23] OverTime
24] PercentSalaryHike
25] PerformanceRating
26] RelationshipSatisfaction
27] StandardHours
28] StockOptionLevel
29] TotalWorkingYears
30] TrainingTimesLastYear
31] WorkLifeBalance
32] YearsAtCompany
33] YearsInCurrentRole
34] YearsSinceLastPromotion
35] YearsWithCurrManager
```

Dataset Link:
https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset

### 📝 LIBRARIES USED:

```
- Pandas
- NumPy
- Matplotlib
- Seaborn
- HvPlot
- SciPy
- Sklearn
- XGBoost
- LightGBM
- CatBoost
- Warnings
```

### ⚠️ PREREQUISITES

```
- Python Programming
- Data Science
- Data Analysis
- Data Pre-processing
- Data Visualization
- Statistical Analysis
- Machine Learning Algorithms
- Performance Metrics.
```

### 🔑 CONCLUSION

In conclusion, we embarked on a comprehensive analysis of the IBM HR Analytics Attrition Dataset, from data loading to model evaluation. By implementing and evaluating various machine learning algorithms, we gained insights into which models are effective for predicting employee attrition. The results and visualizations generated throughout the process provide valuable information for decision-makers and HR professionals seeking to understand and mitigate employee attrition within the organization. This project showcases the power of data analysis and machine learning in addressing real-world business challenges.
