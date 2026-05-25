# Climate-Impact-on-Agricultural-Productivity

## Project Overview
Climate change continues to influence agricultural productivity through rising temperatures, irregular rainfall patterns, climate risk exposure, and frequent extreme weather events. These environmental changes affect crop yield stability, farming efficiency, resource utilization, and economic sustainability across agricultural regions.  

This project analyzes the impact of climate variability on agricultural productivity between 1990 and 2024 using interactive Power BI dashboards. The analysis focuses on three major areas:  
i.	Climate Productivity  
ii.	Resource Efficiency  
iii.	Economic Vulnerability  

The project was designed to identify productivity trends, evaluate farming efficiency, assess climate-related risks, and measure the financial impact of climate change on agriculture across countries and crop categories.

## Problem Statement  
Agricultural systems are increasingly vulnerable to climate-related disruptions such as droughts, floods, rising temperatures, rainfall variability, and soil degradation. These environmental challenges reduce crop productivity, weaken farming efficiency, increase production costs, and contribute to significant economic losses.  
Despite advancements in agricultural technology and resource management, many farming regions continue to experience unstable agricultural performance due to poor climate resilience and inefficient resource utilization. Organizations and policymakers require a data-driven approach to understand how climate conditions affect agricultural productivity, resource efficiency, and financial sustainability.  
This project addresses the need for a comprehensive climate-agriculture analysis framework that evaluates productivity trends, climate severity exposure, farming efficiency, and economic vulnerability across countries and crop categories.  

## Data Source
The dataset used for this project contains historical agricultural, climate, and economic indicators from 1990 to 2024. 
[Here ](https://drive.google.com/file/d/1RJkkVuwN6doxLdD5W-Ur_-DiugqLEuo1/view?usp=drive_link)  

Data Categories
1.	Climate Variables  
o	Temperature  
o	Precipitation  
o	Climate Risk  
o	Extreme Weather Pressure  
o	Climate Severity

3.	Agricultural Variables  
o	Crop Yield
o	Irrigation Access
o	Fertilizer Usage
o	Pesticide Usage
o	Soil Health Index
o	Yield Efficiency

5.	Economic Variables
o	Economic Impact
o	Loss per Yield
o	Economic Vulnerability
o	High-Risk Economic Loss

Geographic Coverage
The analysis includes agricultural data across multiple countries including:
•	Nigeria
•	China
•	Argentina
•	India
•	USA
•	Australia
•	Brazil
•	Canada
•	France
•	Russia
Tools and Methodologies
1.	SQL
SQL was used for data transformation, preprocessing, and feature engineering.
New Columns Created in SQL
The following calculated columns were created to improve analysis and segmentation:
o	Country Group
o	Crop Category
o	Irrigation Resilience Ratio
o	Economic Vulnerability
o	Climate Risk Score
o	Yield Efficiency Index
o	Climate Severity
These transformations helped categorize countries, classify crop groups, evaluate climate exposure, and measure agricultural efficiency.
2.	Power BI
Power BI was used for data modeling, dashboard development, KPI tracking, and interactive visualization.
a.	Data Modeling
A star schema model was developed to improve dashboard performance and relationship management.
Calendar Table
A calendar table was created to support:
•	Time intelligence analysis
•	Rolling averages
•	Year-over-year calculations
•	Trend analysis
Dimension Tables Created
•	Dim_Crop
•	Dim_Country
•	Dim_Climate
•	Dim_Economic

b.	DAX Measures
DAX measures were created for KPI calculations and analytical insights.
Examples of DAX Calculations
•	Average Yield
•	Yield Volatility
•	Climate Risk Score
•	Fertilizer Efficiency
•	Irrigation Resilience
•	Economic Impact
•	Rolling Yield Average
•	Year-over-Year Percentage Change
•	High-Risk Economic Loss
Business Questions
1.	Climate Productivity
o	How do temperature and precipitation changes affect agricultural yield over time?
o	Which countries are most vulnerable to climate-related productivity decline?
o	What is the relationship between climate severity and crop productivity?
o	How do extreme weather events influence agricultural yield stability?
2.	Resource Efficiency
o	Does irrigation access improve agricultural productivity?
o	How does soil health influence farming efficiency?
o	Which crop categories demonstrate stronger resource efficiency?
o	What relationship exists between fertilizer usage and productivity?
3.	Economic Vulnerability
o	How does climate risk influence agricultural economic losses?
o	Which crop categories experience the highest financial exposure?
o	What climate severity levels contribute most to economic impact?
o	Which countries face the highest climate-related agricultural losses?
Exploratory Data Analysis (EDA)
Exploratory Data Analysis was conducted to identify trends, patterns, and relationships within the agricultural and climate dataset.
EDA Activities Performed
1.	Trend Analysis
o	Evaluated agricultural yield performance over time.
o	Analyzed rolling yield and rolling economic impact trends.
o	Compared current performance against historical averages.
2.	Comparative Analysis
o	Compared agricultural productivity across countries.
o	Evaluated crop efficiency across climate severity levels.
o	Assessed soil health performance by crop type.
3.	Relationship Analysis
o	Analyzed precipitation versus crop yield.
o	Evaluated temperature impact on agricultural productivity.
o	Measured the relationship between climate risk and economic losses.
4.	Geographic Analysis
o	Mapped climate risk exposure by country.
o	Visualized economic losses across agricultural regions.
o	Resource Utilization Analysis
o	Assessed fertilizer and pesticide usage patterns.
o	Evaluated irrigation access across countries.
o	Compared farming efficiency across crop categories.
