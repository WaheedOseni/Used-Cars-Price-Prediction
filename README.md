# Used Car Price Prediction (Excel Data Analysis Project)
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

#### 4. Regression Analysis (Prediction Model)

Used Excel’s Data Analysis ToolPak → Regression.

Set Price as the dependent variable (Y).

Set Kilometers_Driven, Mileage, Engine, Power, and Seats as independent variables (X).

Interpreted the coefficients and R² value to measure prediction accuracy.

## 📊 Key Insights

Power (bhp) has the strongest positive influence on car price.

Kilometers Driven negatively affects price — older, high-mileage cars sell for less.

Engine size and number of seats have moderate influence.

Mileage has minimal or inconsistent impact across different brands or models.

## 🎯 Conclusion

This analysis successfully demonstrates how Excel can be used for data-driven decision-making in the automobile market.
By applying regression analysis, we can estimate car prices with reasonable accuracy and identify the most important pricing factors.

## 🧰 Tools & Skills Used

Microsoft Excel

Data Cleaning

Pivot Tables

Charts & Visualizations

Correlation Analysis

Regression (Data Analysis ToolPak)

Analytical Skills

Data interpretation

Business insight generation

Report creation

📁 Project Deliverables

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
