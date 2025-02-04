# Power-BI-Dashboards-PwC-Project

This project consists of 3 tasks:
* **Task 1**: Create Call Centre Dashboard - visualizing customer and agent behaviour.
* **Task 2**: Create Customer Retention and predict churn customers - visualizing customer demographics and insights.
* **Task 3**: Create Diversity and Inclusion in HR - visualizing gender balance in the executive suite.

## Task 1

### Background
* **Problem**: The manager at PhoneNow (a big telecom company) is seeking transparency and insight into the Call Center dataset to gain an accurate overview of long-term customer and agent behavior trends.
* **Objective**: The purpose of this analysis is to create a dashboard in Power BI for Call Center Manager that reflects all relevant Key Performance Indicators (KPIs) and metrics.
* **Data Source**: Call center datasets
### KPIs
* Overall customer satisfaction
* Overall calls answered/abandoned
* Calls by time
* Average speed of answer
* Agent’s performance quadrant -> average handle time (talk duration) vs calls answered

### Call Center Dashboard

<img width="903" alt="image" src="https://github.com/user-attachments/assets/96f004ca-8c30-4c06-af2c-4b193dc78df3" />

**Findings:**
* The total number of calls received is 5,000, with 4,000 answered and 946 abandoned, resulting in an abandonment rate of 18.92%.
* The average answer speed is 67.52 seconds, and the average talk duration is 3.75 minutes, while the resolved rate stands at 72.92%.
* Customer satisfaction is moderate at 3.40 out of 5, with Martha (3.47) and Dan (3.45) scoring highest, while Joe (3.33) has the lowest satisfaction rating.
* Call volume remains consistent across months, with January having the highest number of calls (1,772), while February (1,616) and March (1,612) show similar trends.
* Throughout the day, calls peak at 11 AM-1 PM and 4-5 PM, suggesting the need for optimized staffing during these hours.
* In terms of agent performance, Dan and Jim handled the most calls (~530–540) with a longer-than-average talk duration (~3.85–3.9 mins), suggesting they balance efficiency and thorough support. Stewart and Greg had fewer calls (~475–495) but longer talk durations (~3.8–3.9 mins), indicating potential inefficiencies, while Martha and Becky managed high call volumes (~510) with shorter durations (~3.7–3.75 mins), showing efficiency but possibly at the cost of call quality.

To improve performance, reducing call abandonment should be a priority, possibly by optimizing staffing during peak hours and improving queue management. Additionally, enhancing agent training, particularly for those with lower satisfaction ratings, may help improve customer experience. Monitoring answer speed and resolution rates closely will ensure continuous improvement in service quality.

## Task 2 

### Background
* Customers in the telecom industry are hard-earned: we don’t want to lose them
* The retention department is here to get customers back in case of termination
* Currently, we get in touch after they have terminated the contract, but this is reactionary: it would be better to know in advance who is at risk
* We  have done customer analysis with Excel: it has always ended in a dead-end
* We would like to know more about our customers: visualised clearly so that it’s self-explanatory for our management

### 1) Customer Risk Analysis
<img width="902" alt="image" src="https://github.com/user-attachments/assets/352a9395-3d7f-4692-8346-1fb8a94ffa11" />

**Findings:**
* **Important KPIs**:
  * The total number of customers is 7,043, with a churn rate of about 26.5%. This means that over a quarter of customers are leaving.
  * The volume of tech and admin tickets is 2,955 and 3,632, respectively. The total monthly and yearly charges are 0.5M and 16.1M. 
* **Internet Service**:
  * The highest churn (around 42%) is among Fiber‐optic customers, whereas DSL churn is only about 19%, and customers without Internet service are at about 7%.
  * Fiber‐optic accounts for the largest share of Monthly Charges (>60%), so losses in this segment have a major revenue impact.
* **Contract Types & Churn**:
  * Month‐to‐month plans have a significantly higher churn rate (~40%), whereas one‐year and two‐year plans have markedly lower churn (~20% or below).
  * This suggests that longer contracts help retain customers.
* **Year of Contract**:
  * Churn is highest among new customers for under one-year subscription. After the first year, churn steadily decreases over years 2–5.
  * The Monthly Charges are quite high for first‐year subscribers, then decreases through the middle‐contract years (2–4), and rises again at the 5+ or 6+ years.
* **Payment Methods & Churn**: Customers paying by electronic check shows the highest churn(about 40%). In contrast, churn with other payment methods (credit card, bank transfer, and mailed checks) is lower, often below 25%.

Overall, the data suggests that Fiber‐optic, month‐to‐month customers paying by electronic check are at highest risk of canceling. Longer‐term contracts and other payment methods are associated with lower churn.

### 2) Churn Dashboard

<img width="903" alt="image" src="https://github.com/user-attachments/assets/2613f3c2-090b-43ca-aabb-a7d687070d69" />

**Findings:**
* The Churn Dashboard highlights key factors driving customer churn. Churn is highest among new customers (29.38%) and remains significant even for long-term subscribers (21.06%). Senior citizens (25.5%) and partners (35.8%) also have notable churn rates.
* Month-to-month contracts show the highest churn (55.02%), while longer contracts reduce attrition. Electronic check users (33.58%) experience the highest churn among payment methods. Fiber optic customers have the highest churn rate (41.9%), suggesting possible service issues or competition.
* Retention efforts should focus on new customers, fiber optic users, and month-to-month subscribers. Encouraging longer contracts, improving early customer engagement, and promoting underutilized services like tech support and online security could help reduce churn.

**Key Insights & Recommendations:**
  * Reduce churn among new customers by improving onboarding and early engagement.
  * Encourage longer contracts, as churn is significantly lower in 1-year and 2-year contracts.
  * Monitor electronic check users as they have the highest churn rate—potentially.
  * Investigate Fiber Optic churn to understand if it’s driven by service issues or competitive offers.
  * Promote underutilized services like Tech Support & Online Security, which could improve retention.

## Task 3 

### Background
* Problem: Human Resources at our telecom client is highly into diversity and inclusion. They’ve been working hard to improve gender balance at the executive management level, but they’re not seeing any progress. 
* Create visualizations to represent HR data, particularly focusing on gender-related KPIs.
* Identify and discuss potential root causes for the slow progress in achieving gender balance at the executive management level.

### KPIs
* Number of men
* Number of women
* Number of leavers
* % employees promoted (FY21)
* % of women promoted
* % of hires men
* % of hires women
* % turnover
* Average performance rating: men
* Average Performance rating: women

### Diversity & Inclusion Dashboard

<img width="1047" alt="image" src="https://github.com/user-attachments/assets/9d03c7d2-6f52-4678-ac88-a44534985ef8" />
<img width="1047" alt="image" src="https://github.com/user-attachments/assets/59aab4a6-feab-4b47-8334-f7abcc16a7c2" />


**Findings:**
* Gender Imbalance in Leadership: The proportion of female executives remains low, with only 15.79% in FY21. Despite hiring efforts (41% female hires), promotions to executive roles are still dominated by men.
* Promotion Rates: Women have higher promotion rates in lower job levels (e.g., Junior Officers at 52.1%), but fewer women advance to senior leadership.
* Turnover & Performance: Female turnover is slightly higher (11% vs. 9% for men), but performance ratings for men and women are nearly identical (2.42 vs. 2.41).
* Age Distribution: Younger employees (20-29) make up the majority, indicating future potential for improving gender balance at leadership levels.
* Potential Root Causes: Limited female promotions to executive levels, higher turnover for women, and a predominantly male leadership pipeline contribute to the slow progress in achieving gender balance.


