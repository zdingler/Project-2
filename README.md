# MIST4610-Project2-Group9

## Team Name:
61608 Group 9

## Team Members:
1. Zack Dingler - [@zdingler](https://www.github.com/zdingler)
2. Mingyang (Amanda) Li - [@MingyangLiAmanda](https://www.github.com/MingyangLiAmanda)
3. Andrew Toeppner - [@AToeppner](https://www.github.com/AToeppner)
4. Zuhair Baig - [@ZuhairBaig0](https://www.github.com/ZuhairBaig0)
5. Koty Hall - [@kah02358](https://www.github.com/kah02358)

## Dataset Introduction
The dataset “Nutrition, Physical Activity, and Obesity” comes from the Behavioral Risk Factor Surveillance System (BRFSS) and provides national and state-specific data focused on adult diet, physical activity, obesity, and breastfeeding. 
As for the credibility, the Behavioral Risk Factor Surveillance System (BRFSS), developed by the Centers for Disease Control and Prevention (CDC), is a credible and authoritative source for public health data in the United States. It collects information on health-related behaviors, chronic health conditions, and the use of preventive services among U.S. adults. The primary goal of BRFSS is to monitor public health trends and provide data that supports evidence-based policymaking and health interventions.

## Dimensions
The dataset includes data spanning from the years 2011 to 2023, with entries collected from 55 U.S. locations, including all 50 states, Washington D.C., and several U.S. territories. The dataset is structured with 33 columns, each representing a specific attribute related to public health monitoring. These columns include metadata (e.g., YearStart, YearEnd, LocationDesc), demographic variables (Age, Sex, Race/Ethnicity, Education, Income), survey-related identifiers (ClassID, TopicID, QuestionID), and health data such as Data_Value, Sample_Size, and confidence intervals. The data types vary and include strings, integers, and floating-point numbers. Together, this dataset provides a comprehensive view of chronic health conditions, health-related behaviors, and preventive service usage across diverse populations and time periods, making it a valuable resource for researchers and policymakers in public health.

## Question 1
Question 1: How does physical activity relate to obesity across different income levels and states?
This question is important because obesity is a major public health concern closely tied to physical inactivity. Exploring how income levels influence physical activity and obesity can help identify disparities across socioeconomic groups and geographic regions. Lower-income populations often face barriers to exercise, such as limited access to safe recreational spaces or lack of time due to multiple jobs, which may lead to higher obesity rates. This not only affects individual health but also increases public healthcare spending and reduces economic productivity. By using variables from the BRFSS dataset such as obesity rates, physical inactivity, income brackets, and state-level identifiers, this question enables public health agencies to design targeted, equitable interventions to support at-risk communities.


## Data Manipulation Question 1
To analyze how physical activity relates to obesity across income levels and states, the BRFSS dataset was filtered using the "Question" variable to isolate records related to both obesity rate and physical inactivity rate. These filtered measures were then aggregated by computing the average values for each income bracket. A dual-axis chart was created in Tableau, combining a bubble chart to display the average obesity rate and a line chart to represent the average physical inactivity rate. The income variable was used to differentiate the categories visually, enabling comparison across socioeconomic groups.
![image](https://github.com/user-attachments/assets/c49531cc-31b6-4180-8a11-e1e2b0732fad)
