# Climate-Impact-on-Agricultural-Productivity

## Table of Contents
- [Project Overview](https://github.com/Emjay-19/Climate-Impact-on-Agricultural-Productivity/blob/main/README.md#project-overview)
2. [Problem Statement](https://github.com/Emjay-19/Climate-Impact-on-Agricultural-Productivity/blob/main/README.md#problem-statement)
3. [Data Source](https://github.com/Emjay-19/Climate-Impact-on-Agricultural-Productivity/blob/main/README.md#data-source)
4. [Tools and Methodologies](https://github.com/Emjay-19/Climate-Impact-on-Agricultural-Productivity/blob/main/README.md#tools-and-methodologies)
5. [Business Questions](https://github.com/Emjay-19/Climate-Impact-on-Agricultural-Productivity/blob/main/README.md#business-questions)
6. [Exploratory Data Analysis (EDA)](https://github.com/Emjay-19/Climate-Impact-on-Agricultural-Productivity/blob/main/README.md#exploratory-data-analysis-eda)
7. [Key Insights](https://github.com/Emjay-19/Climate-Impact-on-Agricultural-Productivity/blob/main/README.md#key-insights)
8. [Summary of Findings](https://github.com/Emjay-19/Climate-Impact-on-Agricultural-Productivity/blob/main/README.md#summary-of-findings)
9. [Recommendations](https://github.com/Emjay-19/Climate-Impact-on-Agricultural-Productivity/blob/main/README.md#recommendations)
10. [Limitations](https://github.com/Emjay-19/Climate-Impact-on-Agricultural-Productivity/blob/main/README.md#limitations)
11. [Conclusion](https://github.com/Emjay-19/Climate-Impact-on-Agricultural-Productivity/blob/main/README.md#conclusion)




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

### Data Categories
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

### Geographic Coverage  
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

## Tools and Methodologies  
### 1.	SQL  
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

### 3.	Power BI  
Power BI was used for data modeling, dashboard development, KPI tracking, and interactive visualization.  
**a.	Data Modeling**  
A star schema model was developed to improve dashboard performance and relationship management.  
Calendar Table: A calendar table was created to support:  
•	Time intelligence analysis  
•	Rolling averages  
•	Year-over-year calculations  
•	Trend analysis  
Dimension Tables: Dimension tables created:  
•	Dim_Crop  
•	Dim_Country  
•	Dim_Climate  
•	Dim_Economic  

**b.	DAX Measures**  
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

## Business Questions  
1.	Climate Productivity  
o	How do temperature and precipitation changes affect agricultural yield over time?  
o	Which countries are most vulnerable to climate-related productivity decline?  
o	What is the relationship between climate severity and crop productivity?  
o	How do extreme weather events influence agricultural yield stability?
  
3.	Resource Efficiency  
o	Does irrigation access improve agricultural productivity?  
o	How does soil health influence farming efficiency?  
o	Which crop categories demonstrate stronger resource efficiency?  
o	What relationship exists between fertilizer usage and productivity?

5.	Economic Vulnerability  
o	How does climate risk influence agricultural economic losses?  
o	Which crop categories experience the highest financial exposure?  
o	What climate severity levels contribute most to economic impact?  
o	Which countries face the highest climate-related agricultural losses?

## Exploratory Data Analysis (EDA)  
Exploratory Data Analysis was conducted to identify trends, patterns, and relationships within the agricultural and climate dataset.  
EDA Activities Performed  
1.	Trend Analysis  
o	Evaluated agricultural yield performance over time.
o	Analyzed rolling yield and rolling economic impact trends.
o	Compared current performance against historical averages.

3.	Comparative Analysis  
o	Compared agricultural productivity across countries.  
o	Evaluated crop efficiency across climate severity levels.  
o	Assessed soil health performance by crop type.

5.	Relationship Analysis  
o	Analyzed precipitation versus crop yield.  
o	Evaluated temperature impact on agricultural productivity.  
o	Measured the relationship between climate risk and economic losses.

7.	Geographic Analysis  
o	Mapped climate risk exposure by country.  
o	Visualized economic losses across agricultural regions.  
o	Resource Utilization Analysis  
o	Assessed fertilizer and pesticide usage patterns.  
o	Evaluated irrigation access across countries.  
o	Compared farming efficiency across crop categories.


<img width="526" height="336" alt="Screenshot 2026-05-25 074057" src="https://github.com/user-attachments/assets/ba406440-1962-42b2-aed9-9f5875f11faf" />


<img width="561" height="333" alt="Screenshot 2026-05-25 074635" src="https://github.com/user-attachments/assets/a7e1e18f-f2d6-480c-bc70-e1d2f2954b22" />


<img width="553" height="335" alt="Screenshot 2026-05-25 075339" src="https://github.com/user-attachments/assets/ab9c8e59-860f-49b3-b2ba-b93e2e1729d1" />


## Key Insights  
**1.	Climate Productivity Insights**
The data shows that the stable and predictable weather patterns farmers relied on for generations are disappearing. Global agricultural yield dropped to 2.24 MT/HA, representing a 2.9% decline compared to last year, proving that climate instability is already shrinking the total amount of food being produced worldwide. 

Extreme weather pressure slightly declined by 10.9% year-over-year, suggesting there were fewer severe weather events over the past year. However, despite this temporary relief, crop production remained highly unstable and yield volatility stayed unchanged. This proves that agricultural systems have become structurally weakened, where even short periods of manageable weather are no longer enough for crops to recover properly.  

Countries such as Nigeria performed slightly above the global average in crop productivity, while countries like Russia experienced lower harvest performance. However, the most concerning trend appears in the long-term yield trendline, which shows a noticeable downward decline heading into 2024. The data confirms that no country is fully escaping the effects of changing climate conditions on food production.   

Temperature increases and unstable rainfall patterns continue to weaken agricultural productivity across severe climate zones. Stable and moderate climate conditions still support stronger crop performance, but regions experiencing climate extremes are seeing increasing production instability.   

**3.	Resource Efficiency Insights**  
The most alarming finding in the analysis is the collapse in irrigation resilience. Irrigation resilience dropped by 41.8% in a single year, showing that water systems and backup irrigation supplies are failing to keep up with hotter and drier climate conditions. This sharp decline signals a growing water security crisis that threatens the future sustainability of traditional farming systems.    

Farmers are increasingly responding to climate pressure by relying heavily on fertilizers and pesticides to maintain crop output. Fertilizer efficiency improved slightly by 3.4%, showing that chemical inputs are temporarily helping sustain production levels despite worsening environmental conditions. However, this short-term survival strategy is creating long-term damage.  

Soil health index declined by over 2% year-over-year, proving that excessive dependence on agricultural chemicals is gradually degrading the health of farming soils. This creates what can be described as a “chemical trap,” where farmers sacrifice long-term soil sustainability in order to protect short-term harvest volumes.  

Countries with stronger irrigation systems such as Australia and Canada demonstrated greater agricultural resilience and productivity stability compared to countries with weaker water infrastructure. The data highlights that access to reliable irrigation is becoming one of the most important factors determining future agricultural survival.   

**4.	Economic Vulnerability Insights**  
Climate-related agricultural damage reached a total economic impact of $6.74M, showing that climate variability is no longer a distant environmental concern but an immediate financial crisis affecting food systems globally. In addition, every failed harvest resulted in an average loss of approximately $300 per unit of agricultural yield lost.   

Nearly 32% of all agricultural financial losses were classified as high-risk losses, representing approximately $3.78M in damage that could not be recovered through standard insurance protection or financial safety measures. This indicates that severe weather events are no longer simply reducing profits but are completely wiping out farming operations and livelihoods.   

Wheat and sugarcane recorded the largest high-risk financial losses, followed closely by coffee, fruits, and vegetables. These are critical food and commercial crops relied upon globally, meaning severe weather disruptions in these sectors could directly contribute to rising food prices, supply shortages, and economic instability.   

The relationship between climate risk and economic loss remains extremely strong across countries and crop categories. As climate severity increases, economic losses rise sharply, proving that climate conditions are changing faster than traditional agricultural systems can adapt.   


## Summary of Findings  
1.	The analysis reveals that climate change is no longer a future environmental concern but an active global agricultural crisis already reducing food productivity, weakening farming resilience, and increasing economic instability.  
2.	The dashboards show that global agricultural yield declined by nearly 3% year-over-year despite a temporary reduction in severe weather events. This indicates that farming systems have become structurally weakened and can no longer recover easily from climate disruptions.  
3.	Water security emerged as one of the most critical risks within the agricultural system. Irrigation resilience collapsed by almost 42% in a single year, showing that water infrastructure and groundwater reserves are failing to support farming activities under hotter and drier climate conditions.  
4.	Farmers are increasingly depending on fertilizers and pesticides to artificially maintain production levels. While fertilizer efficiency improved slightly, soil health continued to decline, proving that excessive chemical dependence is damaging long-term agricultural sustainability.  
5.	The project also identified major financial risks associated with climate variability. Climate-related agricultural losses reached $6.74M, with nearly one-third of these losses categorized as high-risk and unrecoverable damages. Critical crops such as wheat, sugarcane, coffee, fruits, and vegetables experienced the highest financial exposure.  
6.	Overall, the findings confirm that climate conditions are changing faster than traditional agricultural systems can adapt, creating growing threats to food security, farmer livelihoods, and global economic stability.

## Recommendations
1.	Climate Adaptation Strategies  
o	Invest heavily in climate-smart agricultural systems capable of adapting to changing weather conditions.  
o	Promote drought-resistant and heat-tolerant crop varieties across vulnerable agricultural regions.  
o	Strengthen weather forecasting systems and early warning mechanisms for farmers.  
o	Encourage sustainable farming practices that improve long-term agricultural resilience.  

2.	Water and Irrigation Management  
o	Expand irrigation infrastructure and modern water conservation systems.  
o	Improve groundwater management policies to reduce water depletion.  
o	Encourage efficient irrigation technologies such as drip irrigation and smart water monitoring.  
o	Prioritize water security programs in climate-vulnerable farming regions.

4.	Soil and Resource Sustainability  
o	Reduce excessive dependence on chemical fertilizers and pesticides.  
o	Promote organic farming practices and soil restoration programs.  
o	Encourage balanced fertilizer application to protect long-term soil health.  
o	Increase farmer education on sustainable resource management practices.

6.	Economic Protection Measures  
o	Develop stronger agricultural insurance and climate recovery programs.  
o	Increase government support for climate-vulnerable farmers and farming communities.  
o	Create emergency financial protection systems for high-risk agricultural regions.  
o	Prioritize funding and protection for highly vulnerable crops such as wheat, sugarcane, coffee, fruits, and vegetables.

8.	Data and Technology Recommendations  
o	Improve agricultural and climate data collection systems.  
o	Encourage the use of data analytics and business intelligence tools in agricultural planning.  
o	Continuously monitor climate-productivity trends to support evidence-based policy decisions.  
o	Expand digital agriculture initiatives for predictive climate risk management.

## Limitations  
•	The dataset used in this project did not fully capture all real-time climate events and agricultural disruptions occurring globally.  
•	Some agricultural indicators were aggregated at country level, limiting deeper farm-level analysis.  
•	External factors such as government policy, geopolitical instability, and market price fluctuations were not included in the analysis.  
•	Historical trends were used to evaluate agricultural performance, which may not completely predict future climate scenarios.  
•	Certain regional climate impacts may vary beyond the scope of the available dataset.  

## Conclusion
•	This project provides a comprehensive analysis of how climate variability is affecting agricultural productivity, farming efficiency, resource sustainability, and economic vulnerability between 1990 and 2024.  
•	Using SQL for data transformation and feature engineering, and Power BI for data modeling, visualization, and KPI analysis, the project successfully identified key patterns linking climate conditions to agricultural performance.  
•	The analysis demonstrates that changing weather patterns are reducing crop productivity, weakening irrigation resilience, degrading soil health, and increasing financial losses across agricultural systems. The findings also reveal that traditional farming methods are struggling to adapt quickly enough to long-term climate changes.  
•	The dashboards highlight the urgent need for climate adaptation strategies, sustainable resource management, improved irrigation systems, and stronger financial protection mechanisms for vulnerable agricultural sectors.  
•	Ultimately, the project emphasizes that food security, agricultural sustainability, and economic resilience now depend on how effectively governments, organizations, and farming systems respond to accelerating climate challenges.  
