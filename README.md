# Used Car Price Prediction (Excel Data Analysis Project)

<img width="551" height="310" alt="Image" src="https://github.com/user-attachments/assets/6cdb5032-9942-4bbb-be54-fd6a354a5e31" />

## 📘 Project Overview

This project focuses on analyzing and predicting the selling prices of used cars using Microsoft Excel.
The goal is to understand how various factors—such as mileage, engine capacity, power, number of seats, and kilometers driven—affect the price of used cars.

By performing exploratory data analysis, visualizations, and building a simple predictive model (via trendlines or regression), we gain insights into the most influential features that drive car prices.

## 🧾 Dataset Information

The dataset used contains several features describing each car:

Column Name	Description
Kilometers_Driven	Total distance (in km) the car has been driven
Mileage	Fuel efficiency (km/litre)
Engine	Engine displacement in cubic centimeters (cc)
Power	Engine power in brake horsepower (bhp)
Seats	Number of seats in the car
Price	Selling price of the car (in lakhs)
### ⚙️ Steps Performed
#### 1. Data Cleaning

Removed missing or zero values from key columns like Power and Mileage.

Standardized numerical columns (converted text entries to numbers).

Checked for outliers and corrected anomalies.

#### 2. Exploratory Data Analysis (EDA)

Used Excel charts (Scatter plots, Histograms, Column charts) to explore relationships.

Created Pivot Tables to summarize average price by engine size, power, and number of seats.

Used Conditional Formatting to highlight high and low prices.

#### 3. Correlation Analysis

Used Excel’s CORREL function to identify relationships between variables.

Found that Power and Engine had strong positive correlations with Price.

Kilometers Driven showed a negative correlation — higher usage reduced price.

### 📈 Regression Analysis Results

After cleaning the dataset, a Multiple Linear Regression was run using Price as the dependent variable, and the following independent variables:
Kilometers_Driven, Mileage, Engine, Power, and Seats.

### 🔢 Regression Output Summary
Metric	Value
R² (Model Accuracy)	0.578
Mean Squared Error (MSE)	44.28
Intercept	-14.76
### 📊 Coefficients and Interpretation
Variable	Coefficient	Effect on Price
Kilometers_Driven	-0.000002	Each additional kilometer slightly reduces the price.
Mileage	+0.2728	Higher mileage increases car value.
Engine	+0.000833	Larger engine capacity increases price.
Power	+0.1667	Strongest positive influence on car price.
Seats	-0.1312	Minor negative impact; not statistically significant.
### 🧠 Interpretation

The R² = 0.578 means the model explains about 57.8% of price variability.

Power and Engine size are the most important predictors.

Kilometers Driven reduces resale value (older cars depreciate).

Mileage positively influences price due to fuel efficiency.

Seats have minimal predictive power.

### 🎯 Conclusion

This project demonstrates how Microsoft Excel and basic statistical tools can help understand key pricing factors for used cars.
Regression analysis shows that Power, Engine, and Mileage are the main contributors to price variation, while usage (Kilometers Driven) negatively affects value.

### 🧰 Tools & Skills Used
#### 🪟 Microsoft Excel

Data Cleaning & Validation

Pivot Tables

Charts & Dashboards

Correlation Analysis

Regression (Data Analysis ToolPak)

#### 🧠 Analytical Skills

Data Interpretation

Insight Generation

Visualization & Reporting
## 📁 Project Deliverables

Excel dataset (raw and cleaned)

Excel dashboard/report

Regression output summary

README documentation (this file)

## 🧩 How to Recreate This Project in Excel

Follow these steps to perform the analysis from scratch:

Import Your Dataset

Load your dataset into a new Excel sheet.

Clean the Data

Remove blank rows or irrelevant columns.

Ensure all numeric values (Mileage, Power, Engine, Price) are formatted as numbers.

Replace missing values (if any) with averages or remove affected rows.

Create Pivot Tables

Insert → PivotTable → Analyze Price by Mileage, Engine, Power, and Seats.

Summarize averages or counts to identify patterns.

Visualize the Data

Insert → Charts → Scatter Plot or Column Chart.

Use trendlines to observe relationships between features and price.

Perform Correlation Analysis

Run Regression Analysis

Enable Data Analysis ToolPak:

Go to File → Options → Add-ins → Excel Add-ins → Check “Analysis ToolPak” → OK.

Then go to Data → Data Analysis → Regression.

Set Input Y Range to Price, and Input X Range to all predictor variables.

Interpret the results:

R Square (R²) shows model accuracy.

Coefficients show how each variable affects Price.
