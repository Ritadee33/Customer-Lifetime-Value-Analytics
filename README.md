# Customer-Lifetime-Value-Analytics

### INTRODUCTION
This project is a full power bi data analysis project of a growing digital wallet called vertex fintech. A digital wallet and payment application providers across the United
Kingdom. This project aims to analyse and derive insight by answering business question that will in turn help the business make better data driven decisions.

### PROJECT OVERVIEW
Vertex FinTech is one of the rapidly growing digital wallet and payment application providers across the United Kingdom. With thousands of daily active users, the platform generates a massive volume of transactional, user behaviour, and customer service data. 
This raw historical and operational data will be transformed into a high-leverage strategic asset that enables the Board of Directors to make data-driven decisions. This analysis will evaluate Customer Lifetime Value (LTV), segment users, and optimize support desk operations to maximize long-term portfolio profitability.

### OBJECTIVES
The aim of this data analysis is to consolidate my power bi skills in helping business like this solve business problems, gain insights in order to make data driven decisions. For this project my goal is to make a comprehensive and interactive dashboard that provide actionable insights into customer lifetime value, customer inactivity & retention risk.

### ABOUT DATASET
The dataset used in this project was a single data structure that contains 7,000 records and 20 fields. Understanding the contents of the dataset is key and knowing what each field represent gave me a holistic view of what I am working with.

<img width="940" height="341" alt="image" src="https://github.com/user-attachments/assets/dd950d9c-2153-4895-873f-c223798de993" />

### PROBLEM STATEMENT
Vertex FinTech currently lacks an integrated, multi-dimensional view of customer health and platform activity.
To build robust operational safeguards and retain premium users, they need to ask the following questions:
- What is the gross portfolio LTV managed by the platform, and how does it distribute across different user
income tiers and locations?
- Which demographic and behaviour combination constitutes the platform's "Golden Segment" (highest net
lifetime contribution)?
- How do specific payment mechanisms influence the historical lifetime value across the engineered age
groups?
- Which payment mechanism shows the highest velocity of transactions, and does app open frequency
amplify this velocity?

### CONCEPTS/SKILLS DEMOSTRATED
The following data analysis skills and power bi were incorporated during the run down of this project.
- Data Cleaning/ Data Transformation using power query
- Data Analysis Expression (DAX)
- Power BI interactive dashboard design for analysis 

### DATA CLEANING/TRANSFORMATION
The dataset that was used for this project was already cleaned with fewer or no issues. But as a data analyst the idea of data cleaning is to ensure that the data is clean enough for analysis in order to maintain data integrity and accuracy. As I checked the dataset for any form of dirtiness, I found out the following:
   - No missing values 
   - No duplicates 
   - No issue of incorrect data types

### DATA ANALYSIS AND VISUALS
Given the problem statement above and the business, there are a couple of analytical approach to be made on the dataset that will help in answering and analysing both the business question and problems.

- Firstly, I added a new column called Age band using the IFS Function

<img width="602" height="362" alt="image" src="https://github.com/user-attachments/assets/bee76a8a-aed2-46e3-a21f-0e90b70c1f43" />

- Secondly, I added a new column called Engagement Status which was extracted from the Last_Transaction_Days column

<img width="940" height="573" alt="image" src="https://github.com/user-attachments/assets/7740638b-e995-4221-8019-075f14727f76" />

Now it is ready for the actual analysis while answering business question and problems.

#### DATA ANALYSIS INSIGHTS
1. Customer Value by location showed that Suburban location is bringing in more revenue than the other location although they are still performing well.
See image below: 
<img width="803" height="510" alt="image" src="https://github.com/user-attachments/assets/3080d7d3-d729-4814-a1b8-af516e7bcab2" />

2. App Usage by Age Group showed that age group 25-44, 45-64 uses the App more and this in turn affects the LTV by Age Group.

<img width="940" height="478" alt="image" src="https://github.com/user-attachments/assets/67a8fbfc-7dc2-4600-9a12-66034a7ef30c" />

3. Transactions by Income Level revealed that middle income earners mostly carry out more transactions followed by low income earners before the high income earners

<img width="653" height="464" alt="image" src="https://github.com/user-attachments/assets/dbf1b1c8-535f-489a-867d-b05179bda32e" />

### DYNAMIC DASHBOARD VISUALS
The image below is the snapshot of the interactive dashboard design
<img width="940" height="526" alt="image" src="https://github.com/user-attachments/assets/8b2a4e0d-373f-4a01-a90c-5553ab066019" />


#### RECOMMENDATION
1. Reorient acquisition strategy toward Middle-income customers.
The data clearly shows Middle income outperforms High income by £1. The company may be over-investing in premium customer acquisition while undervaluing its most structurally profitable segment. Marketing spend and product development should reflect this reality.
2. Prioritise the Golden Segment for retention programmes.
Middle · Suburban · Monthly-app · customers. These customers should be in a dedicated retention tier with personalised engagement, early access to features, and proactive relationship management before they drift toward inactiveness.
3. Build a Credit Card + Monthly-usage growth pathway.
Credit Card users show the highest transaction velocity (515.5 avg txns), amplified further by Monthly app engagement (522 txns). The company should design product nudges that encourage Credit Card adoption and move Daily-app users toward richer Monthly engagement patterns counterintuitively, Monthly users transact more meaningfully than Daily users.
4. Don't write off Rural customers.
Low · Rural · Weekly customers ranked #2 in the Golden Segment at $671K avg LTV. Rural is often overlooked in FinTech strategy but this dataset shows they punch above their weight. Localised product features and payment accessibility in rural markets could unlock significant untapped value.









