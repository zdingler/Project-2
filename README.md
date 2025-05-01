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

## Question 1 Analysis and Results 
The visualization reveals a clear negative correlation between income and both obesity and physical inactivity rates. As income increases, the average obesity and inactivity rates steadily decrease. This trend is consistent and smooth, suggesting a systemic relationship between socioeconomic status and health behaviors. One likely explanation is that individuals with higher incomes often have greater flexibility in their schedules, allowing them more time to engage in physical activity. Financial stability reduces the need to work multiple jobs or long hours, which often limits opportunities for exercise in lower-income populations. Additionally, those with higher income levels tend to experience lower financial stress, making them more mentally and physically available to invest in health-related behaviors, such as going to the gym, buying healthier food, or participating in structured workout routines. These findings highlight the importance of addressing economic disparities in public health strategies. Interventions targeting low-income communities—such as subsidized gym memberships, workplace wellness programs, and safe, accessible public spaces for exercise—could help reduce both obesity and associated medical costs. The dual-axis bubble-line chart created in Tableau clearly illustrates the descending trend across income levels, visually reinforcing the socioeconomic link to health. No external citations were required, as all data originated from the BRFSS dataset provided by the CDC.

## Question 2
Question 2: Do states with higher muscle-strengthening activity rates also report lower obesity rates?
This question is critical for advancing public health education, as national health guidelines recommend adults engage in muscle-strengthening activities at least twice per week. Despite this, many individuals remain unaware of the connection between resistance training and healthier weight outcomes. If a strong inverse relationship between muscle-strengthening activity and obesity is confirmed, it would provide policymakers and healthcare professionals with a compelling case to promote these exercises as a cost-effective and accessible strategy to reduce obesity rates. From a social and economic perspective, encouraging regular strength training could lead to long-term improvements in population health, reduce the financial burden on healthcare systems, and enhance quality of life. This question ties directly into the BRFSS dataset, which includes state-level data on both muscle-strengthening activity and obesity rates, allowing for direct comparative analysis across U.S. states.

## Data Manipulation Question 2
To explore the relationship between muscle-strengthening activity and obesity rates across U.S. states, the BRFSS dataset was filtered using the “Question” field to isolate variables specifically measuring muscle activity and obesity rate. These were aggregated using the average function for each state to enable comparison. The "LocationDesc" variable was then used to group the data by state. Two choropleth maps were created in Tableau: one displaying average obesity rates per state and the other showing average muscle activity rates. These maps allowed for a side-by-side visual comparison of the two health indicators geographically.
![image](https://github.com/user-attachments/assets/2898da76-3761-47cc-a597-1b0b8d19a19f)
![image](https://github.com/user-attachments/assets/f316c439-8a70-4609-ad71-29200a6dc16f)

## Question 2 Analysis and Results
The results indicate a general inverse relationship between muscle-strengthening activity and obesity. States with higher average muscle activity rates tend to have lower obesity rates. For example, Colorado, which ranks among the highest in muscle activity, also has one of the lowest obesity rates. In contrast, West Virginia shows one of the lowest muscle activity rates and one of the highest obesity rates. Regional trends were also observed: southern states generally report lower muscle activity and higher obesity, while western and northeastern states show the opposite. However, some exceptions emerged—states with average muscle activity levels still exhibited high obesity rates, suggesting that additional factors such as diet, stress, mental health, and socioeconomic inequality may also play significant roles. It is important to note that all data from the BRFSS are self-reported, which introduces potential limitations such as response bias or inaccurate recall. For example, individuals may overreport healthy behaviors like exercise or underreport their weight. This limitation should be considered when interpreting the results. Despite this, the consistent patterns observed across states still provide valuable insights into public health trends. These findings support the idea that promoting muscle-strengthening activity at the state level may be an effective, low-cost strategy to combat obesity. All data used in this analysis were obtained from the CDC’s BRFSS dataset.

## Tableau Packaged Workbook
[Project2_Group9.zip](https://github.com/user-attachments/files/20001937/Project2_Group9.zip)
