# MeriSkill-intern Project

A comprehensive report that encapsulates the essence of the three intriguing projects offered by MeriSKILL. 
These projects, centered within the realm of data analytics, are meticulously designed to unravel patterns and insights concealed within intricate datasets. The focus of these projects includes:

1. Sales Analysis: A deep dive into sales data, aimed at extracting valuable insights to enhance strategic decision-making.
   
2. Diabetic Patients: Exploring the intricacies of diabetic patient data to identify trends and patterns that can aid in improving healthcare outcomes.
   
3. HR Analytics: Delving into the world of human resources, with a keen eye on data analysis to optimize talent management and organizational performance.

## Table of Contents
- [Sales Analysis](#Sales-Data-Analysis-MeriSkill)
- [Diabetic Patients](#Diabetic-Patients-MeriSkill)
- [HR Analytics](#HR-Analytics-MeriSkill)


# Sales-Data-Analysis-MeriSkill

### PURPOSE:
Analyze sales data to identify trends, top-selling products, and revenue metrics for business decision-making.

### DESCRIPTION:
In this project, we will dive into a large sales dataset to extract valuable insights. I will explore sales trends over time, identify the best-selling products, calculate revenue metrics such as total sales and profit margins, and create visualizations to present your findings effectively. This project showcases your ability to manipulate and derive insights from large datasets, enabling me to make data-driven recommendations for optimizing sales strategies.

### COLUMN DESCRIPTION FOR SALES DATA ANALYSIS:
• ORDER ID • PRODUCT • QUANTITY ORDERED • PRICE EACH • ORDER DATE 
• PURCHASE ADDRESS • MONTH • SALES • CITY • HOUR

### Project Structure:
The tool used is Power Bi. The project description includes the following steps:
1. Importing and preprocessing the Sale dataset i.e
• The column headers are identified in the first row and should be kept as headers by following the steps below.
• After promoting the headers, navigate to the 'Transform' tab and select 'Detect Data Type.' This action will automatically identify the data type of each column and convert them as needed.
• Split the datetime into date and time stamp
• The aforementioned process starts with selecting the desired column. Following the selection, the option to split the column becomes visible.
• Choose the 'Split Column' option and select the space as the delimiter.
• Upon completing the data transformation, click on 'Close & Apply' located at the top left.

2. Visualization of Data. 
- Sales trend over time using the line chart
- Best selling products using tree map
- Top 5 best selling product using stacked bar chart
- Weekly sales distribution by weekday using column chart
- Slicer is used to make this kind of visual

#### Insights Generated:
1. Total Sales generated was $34.49M from a total of 209,000 products sold in 9 cities
2. The bulk of the Total revenue was generated from the Macbook Pro with a total of $8m however, the iPhone sold the most with about 6800 sold.
3. San Francisco generated the highest revenue of $8.26m
4. Sales Trends: It is observed that within the year in consideration, sales peaked in December with a total of $4.61m followed by October with $3.74m and April with $3.39m, 72% of the generated revenue was during the week as compared to the weekends
5. Most certainly, the top-selling product was

# 2. Diabetic-Patients-MeriSkill

### About Dataset:
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether a patient has diabetes based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

### Objectives:
Upon examination, I discovered that the dataset contains data suitable for predictive analysis.
Predictive analysis is a type of analysis where this means understanding the probable future trends and behavior
To derive predictions from the given dataset, I partitioned the data into independent and dependent variables. Upon analysis, I observed that all seven variables i.e. Pregnancies, Glucose, Blood pressure, skin thickness, Insulin, BMI, Diabetes, Age are independent, while 'Outcome' serves as the dependent variable.

### Data Description:
- Pregnancies: To express the Number of pregnancies
- Glucose: To express the Glucose level in blood
- BloodPressure: To express the Blood pressure measurement
- SkinThickness: To express the thickness of the skin
- Insulin: To express the Insulin level in blood
- BMI: To express the Body mass index
- DiabetesPedigreeFunction: To express the Diabetes percentage
- Age: To express the age
- Outcome: To express the final result 1 is Yes and 0 is No

### Project Structure:
Diabetic Patientss Analysis that analyzes Diabetic data using Python libraries such as NumPy, Pandas, Matplotlib, Seaborn, and Scikit-learn. The project description includes the following steps:
1. Importing and preprocessing the Diabetic data, including renaming columns, converting data types, and checking for null values and duplicates.
2. Exploratory data analysis, including generating summary statistics, creating visualizations such as line plots, histograms, and heatmaps, and calculating correlations between numerical columns.
3. Performed Train Test Split, Visualizing Correlation, Logistic Regression, Support vector machine (svm)
4.Arrived at conclusion.

# HR-Analytics-MeriSkill

### About Dataset
HR analytics, also referred to as people analytics, workforce analytics, or talent analytics, involves gathering together, analyzing, and reporting HR data. It is the collection and application of talent data to improve critical talent and business outcomes. It enables your organization to measure the impact of a range of HR metrics on overall business performance and make decisions based on data. They are primarily responsible for interpreting and analyzing vast datasets.

### Objective & Structure:
In this Power BI Dashboard, we used data from HR analytics to help an organization improve employee performance and retention (reduce attrition) by creating an HR Analytics Dashboard.
Complete the Power BI project through this data set. Topics covered in this Power BI Project. This dashboard includes topics;
• Dashboard Overview
• Raw HR Analytics Data
• Dashboard Setup
• Data Cleaning and processing in Power BI
• Import Data in Power BI
• Power Bi Dashboard- KPIs
• Power Bi Dashboard- Charts & Table
• Export or share Power Bi Dashboard
• Insights from Dashboard
• Measures and Calculations in Power BI

#### Insights:
- The dashboard emphasizes important insights that were used to draw conclusions from the presented data.
With a total of 1470 employees recorded.
- The attrition Count was 237 which amounts to 16.12% of the total workforce.
- Based on the Job role, it is observed that Research directors experienced the lowest personnel attrition rates, while Laboratory Personnel experienced the highest levels of personnel loss.
- Also observed that the staff between the ages of 26 - 35 had the highest attrition rate across the board
Based on Marital status, Single employees have the highest attrition rate, with 120 departures, then married employees with 84 departures, and divorced employees with 33 departures.
- With insights drawn from the analysis, it is imperative that the organization make timely and informed decisions about workplace administration and boost employee performance.

### Basic Recommendations:
Develop and implement more Retention Strategies
Ensure Gender Equality
Work on creating Job Satisfaction for Single Employees
