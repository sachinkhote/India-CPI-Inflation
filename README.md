# Inflation Analysis in India: Problem Statement Overview

## Introduction
This document provides a structured analysis of key economic trends affecting India's inflation rates. The problems focus on investigating CPI inflation trends, food price contributions, pandemic-driven changes, and the correlation between global events like crude oil price fluctuations and inflation.

## Problem Statements

### 1. CPI Inflation Trend Analysis
- Analyze month-on-month changes in India's retail inflation over a 12-month period.
- Identify months with the highest and lowest inflation.
- Categorize contributions from different CPI basket components to understand key drivers.
#### Approach
1. **Category Consolidation**  
   - Combined individual columns into five major categories:  
     **Food, Clothing & Footwear, Housing, Fuel & Light, Miscellaneous**  
   
2. **Percentage Distribution Calculation**  
   - Summed up the total CPI value to determine the percentage distribution of each category.

3. **Average Percentage Distribution Analysis**  
   - Calculated the overall average of percentage distribution for all categories.  
   - Computed the specific average percentage distribution for **May 2023**.



### 2. Contribution of Food Price to Inflation
- Examine how food prices have influenced inflation trends.
- Identify the biggest contributor within the broader food category.
- Investigate absolute changes in inflation over a 12-month period.
#### Approach
1. **Data Filtering**  
   - Selected records covering both **rural and urban** sectors.
   - Filtered dataset for years **2017 to 2023**.
   - Extracted records corresponding to **January and December** to compare seasonal trends.

2. **Inflation Analysis**  
   - Calculated **year-wise inflation rates** starting from **2017 to 2022**.
   - Identified trends in food price contribution to overall inflation.

3. **Visualization**  
   - Plotted a **line chart** representing inflation trends over the selected years.
   - Highlighted the year with **highest inflation** for better insight.



### 3. Food Inflation Dynamics (Nov'23)
- With India's inflation reaching a 3-month high of 5.55% in Nov'23 due to food price spikes, assess price trends for the broader food category.
- Evaluate month-on-month variations and highlight peak and lowest food inflation periods.
- Identify the top contributing subcategory driving food inflation.
#### Approach
1. **Pivot Table for Food Category**  
   - Created a **Pivot Table** to compute the **average inflation of food** from **May 2022 to May 2023**.

2. **Visualization using Pivot Chart**  
   - Generated a **Pivot Chart** representing the inflation trend across the food category.  
   - Observed a **stable inflation trend** with no major fluctuations.

3. **Subcategory Analysis via Pivot Table**  
   - Constructed another **Pivot Table** to compute the **average inflation** for individual subcategories within food:  
     **Cereals and products, Meat and fish, Egg, Milk and products, Oils and fats, Fruits, Vegetables, Pulses and products, Sugar and Confectionery, Spices, Non-alcoholic beverages, Prepared meals, snacks, sweets etc., Food and beverages, Pan, tobacco and intoxicants**  

4. **Key Findings**  
   - Identified that **Meat and Fish** showed the **highest contribution to food inflation** among all subcategories.  
   - This trend was **clearly visible in the line chart**, highlighting its dominant impact.



### 4. Impact of COVID-19 on Inflation
- Examine how the onset and progression of the pandemic affected inflation rates.
- Compare inflation trends before and after March 2020 (first lockdown).
- Focus on healthcare, food, and essential services to assess pandemic-related inflation changes.
#### Approach
1. **Pivot Table Analysis**  
   - Created a **Pivot Table** to compute the **average inflation** for key sectors:  
     **Health, Personal Care & Effects, Food, Education**  

2. **Timeframe Selection**  
   - Evaluated averages for **2019, 2020, and 2021** to compare **pre-pandemic and post-pandemic** trends.

3. **Comparison of Inflation Trends**  
   - Assessed variations in **inflation rates** across these categories.  
   - Determined how the pandemic influenced price changes in essential sectors.

4. **Base Month Analysis**  
   - Considered **March 2020** as the base month for comparison.  
   - Calculated the **percentage difference** in inflation for months before and after March 2020.  
   - Found that **Health, Personal Care & Effects, and Food showed inflation spikes of 10-15%**, while **Education remained stable**.

5. **Visualization using Pivot Charts**  
   - Inserted **Pivot Charts** to illustrate inflation changes post-March 2020.  
   - Clearly highlighted the impact of COVID-19 on price fluctuations.


### 5. Global Economic Events & Inflation Correlation
- Investigate how imported crude oil price fluctuations influenced India's inflation.
- Analyze oil price trends from 2021-2023 on a month-on-month basis.
- Identify CPI categories most correlated with oil price changes using statistical functions such as `=CORREL()` in Excel.
#### Approach
1. **Correlation Analysis**  
   - Selected various **CPI categories** for correlation with **Fuel and Light**:  
     - **Cereals and products, Meat and fish, Egg, Milk and products, Oils and fats, Fruits, Vegetables, Pulses and products, Sugar and Confectionery, Spices, Non-alcoholic beverages, Prepared meals, snacks, sweets etc., Food and beverages, Pan, tobacco and intoxicants, Clothing, Footwear, Clothing and footwear, Housing, Household goods and services, Health, Transport and communication, Recreation and amusement, Education, Personal care and effects, Miscellaneous, General index**.

2. **Identification of Strong Correlations**  
   - Computed correlation coefficients to determine **strongly related categories**.  
   - Identified the categories with **high correlation** to **Fuel and Light**.

3. **Visualization using Statistical Charts**  
   - Created **graphs and tables** to highlight **CPI components most affected by fuel price fluctuations**.



## Methodology
- Data extraction from CPI inflation records.
- Statistical analysis using Excel (Pivot Tables, `=CORREL()` function) for trend identification.
- Visualization of inflation trends for better interpretability.

## Expected Outcome
- A well-structured inflation analysis identifying key trends and correlations.
- Insights into macroeconomic drivers impacting India's retail inflation.
- Actionable conclusions based on statistical analysis.