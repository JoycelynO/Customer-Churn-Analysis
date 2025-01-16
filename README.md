# Customer-Churn-Analysis
This project analyses customer data to track customer attrition rate and assist a telecom company devise new customer retention  strategies.

## Project Background
The telecom company provides communication services to individuals and organizations. The services they provide include: Telephone and Internet Services, Television Broadcasting and Wireless Communication Services. For subscription-based businesses, reducing customer churn is a top priority. This project analyses customer data to uncover critical insights that will ensure customer retention at the company.

Insights and Recommendations are provided on the following key areas:
1. Churn Reasons: Analyses of attrition rate by broader churn categories and specific churn reasons.
2. Customer Demographics: Analyses of churn rate by customer demographics, age groups and grouped consumption of vertex mobile services.
3. Contract Types: Analyses of churn rate based on account length and contract types.
4. State Comparison: Analyses of churn rate by states.

An interactive Power BI report can be accessed [here](https://app.powerbi.com/view?r=eyJrIjoiMjUwNGYyZDQtMDk1NC00OTFhLThhYTgtMmFiYTQ0ZjcwY2NhIiwidCI6Ijk0MWJiZjVmLWYyYzAtNDg3NS1hMjRjLTY5MDc4NjVkMjUxYSIsImMiOjh9)


## Data Structure
The dataset consists of a single customer data table with 6,687 records. 

![Screenshot 2024-11-26 232248](https://github.com/user-attachments/assets/3ab94c52-bf1b-49a8-97af-a721bacb0c1e)
![Screenshot 2024-11-26 232223](https://github.com/user-attachments/assets/6a369eeb-54bc-4c55-b90f-28e58c429df7)
![Screenshot 2024-11-26 232215](https://github.com/user-attachments/assets/1b2563a7-b1ca-4d51-b6b4-26ccdbb72ed2)
![Screenshot 2024-11-26 232204](https://github.com/user-attachments/assets/ae1945ed-1aaa-4c1e-81e4-a662dc77aa81)
![Screenshot 2024-11-26 232259](https://github.com/user-attachments/assets/d0281bd7-ebe9-4ea8-89e4-0feda266909e)

Prior to the beginning of the analysis, some columns were transformed using DAX to create calculated columns and measures for easy insight generation.


## Executive Summary

### Overview of Findings
The overall churn rate for Vertex Mobile stands at 26.86%, indicating a significant portion of the customer base is leaving the company. Seniors exhibit the highest churn rate at 38.46%, which is 11.6% above the average. Customers with monthly contracts show a higher propensity to churn, In contrast, two-year contracts have the lowest churn rate, at just 2.11%. There's also a noticeable downward trajectory in the churn rate as the customers' account length increases. Customers on unlimited plans who use less than 5 GB of data have a high churn rate of 34.71%. State churn analysis revealed a high churn rate in California, particularly among customers who frequently make international calls but do not subscribe to an international plan. Below are the snapshots from the dashboard:

![Screenshot 2024-11-26 234646](https://github.com/user-attachments/assets/303e20e9-e4cf-4ca3-9386-7600d224fe2e)
![Screenshot 2025-01-10 125618](https://github.com/user-attachments/assets/c58a0d76-b56e-46db-aebd-923c4b26b23a)
![Screenshot 2025-01-10 125821](https://github.com/user-attachments/assets/d1442228-aba3-4922-acf2-ec3364e1f8ab)
![Screenshot 2024-11-26 235043](https://github.com/user-attachments/assets/4414aaa3-2325-458b-b314-32776af7aeeb)
![Screenshot 2024-11-26 234935](https://github.com/user-attachments/assets/60d8f074-9065-4902-bae1-edde850dc489)


## Deep Dive

### Overall Churn Rate and Primary Reasons for Churn
The overall churn rate is 26.86%. Further analysis revealed that customers churned mainly due to competitors and attitude of service agents. 16.9% of customers left because they got better deals from competitors, 16.5% of customers switched to competitors because they offered better devices and 11.3% of customers left due to poor attitudes from support persons. Furthermore, dissatisfaction as a general sentiment was responsible for 15.92% of the total churn, underscoring the need for consistent and high-quality service.

![Screenshot 2024-11-27 001154](https://github.com/user-attachments/assets/4e2b50c5-11e9-4f25-9e39-e4644ef0a101)
![Screenshot 2025-01-10 125926](https://github.com/user-attachments/assets/5bdb7130-a4f1-42e2-a582-9abbf4c8a1d1)



### Churn by Age Group and Demographics
An analysis of churn rates by age group revealed distinct patterns. Seniors had the highest churn rate at 38.46%, which is 11.6% above the average. This could suggest that as customers age, they might find telecommunication services less useful, prompting them to cancel their subscriptions. The Mid-Age group follows with a churn rate of 24.53%. For customers under 30 who are not part of any group plan, the churn rate is relatively high at 29.44%. An unusual insight uncovered is that customers who were subscribed to month-to-month contracts and preferred to not disclose their genders have a high churn rate of 40%. Further investigations should be made on this customer segment.
Data usage patterns and plan types also influenced churn rates. Customers on unlimited plans who used less than 5 GB of data have a high churn rate of 34.71%. This could suggest that these customers may not perceive sufficient value in their unlimited plans, leading them to seek better-suited alternatives. Seniors who weren't subscribed to a group contract have the highest average monthly charge of $38.49 and this could probably be one of the reasons why the highest churn is observed among Seniors. 


![Screenshot 2025-01-10 125821](https://github.com/user-attachments/assets/d111633f-58ae-4dae-a5b2-d8429d2c9917)
![Screenshot 2025-01-10 130126](https://github.com/user-attachments/assets/7189c926-4df9-461b-b7a0-6093056a6168)
![Screenshot 2025-01-10 130158](https://github.com/user-attachments/assets/56a1e473-2d07-46e5-bfe7-a69aafc68197)
![Screenshot 2025-01-10 130334](https://github.com/user-attachments/assets/b3c3f345-4bd5-4555-9684-8c99ebe437c4)




### Contract Type and Churn Tendency
Customers with monthly contracts show a higher propensity to churn, possibly due to the flexibility these contracts offer, making it easier for them to switch providers. In contrast, two-year contracts have the lowest churn rate, at just 2.11%. This indicates that longer-term commitments are effective in retaining customers, suggesting that incentives for longer contracts could be beneficial. 


### State Analysis
State wide analysis revealed a high churn rate in California-CA (63.24%), particularly among customers who frequently make international calls but do not subscribe to an international plan. Specifically, 72% of these customers churned, indicating a potential gap in service offerings that meet their needs.

A peculiar trend observed across various states is that churned customers tend to have a higher average number of customer service calls. However, California defies this trend; despite having the highest churn rate, it has the lowest number of customer service calls. This anomaly suggests that other factors, perhaps related to the specific needs or preferences of Californian customers, are driving churn and should be investigated further.
 
![Screenshot 2025-01-16 201959](https://github.com/user-attachments/assets/5d21e48a-0126-4946-8df4-d072c2cd443b)



## Recommendations
1. Addressing competitive offers and device options could help ensure customer retention. Conducting Market research and a detailed SWOT analysis would help gain a clear understanding of strengths, weaknesses, opportunities, and threats in comparison to competitors. Valuable cues can be taken from opportunities and threats. Armed with this knowledge, more competitive pricing strategies and attractive bundles could be implemented. The company could also partner with top device manufacturers to provide the latest devices at discounted rates as well as introducing easy upgrade options for devices. Additionally, loyalty programs rewarding long-term customers with special discounts and exclusive offers could be introduced to make yearly contract types more attractive. Monthly charges should also be reviewed.
2. Investing in training support staff to ensure an excellent customer experience is important. Feedback systems could be set up so customers can share their experiences and suggestions. Performance evaluation and a determined percentage of salary could be tied to support persons' performance. For instance, a system could be introduced where customers rate support persons who attend to their issues. This would keep support persons on their toes as their salaries could be at stake. Customer service calls should also be recorded for quality assurance purposes.
3. Age-specific retention strategies should be implemented to address the unique needs and preferences of different age groups. For seniors, simple plans with essential features and emergency support could be introduced. Educational sessions or materials should be offered to help seniors make better use of telecommunication services. Discounts can be offered for young customers who sign up with friends or join group plans. Flexible, no-commitment plans that appeal to the lifestyle of younger customers who prefer month-to-month arrangements could also be created.
4. Further analysis should be conducted on persons who prefer to not disclose their genders as well as customers in California. This would mean investigating why California has the highest churn rate despite low customer service call numbers and address underlying issues, possibly through targeted surveys and focus groups.
