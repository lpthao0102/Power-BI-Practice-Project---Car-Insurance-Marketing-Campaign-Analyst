# REPORT: CAR INSURANCE MARKETING CAMPAIGN ANALYSIS

**INTRODUCTION**
-----------------------------------------------------------------------------------------------
This report provides information for individuals and teams interested in data to understand more about potential clients and the operation of car insurance marketing campaigns at a bank in the United States.

**DATASET**
-----------------------------------------------------------------------------------------------
This dataset consists of one table with 19 columns. It contains general information about customers (age, job, etc.) as well as specific details about the current car insurance marketing campaign (about contact information, contact dates, etc.) and previous campaigns.

**PROBLEM STATEMENT**
-----------------------------------------------------------------------------------------------
This report aims to analyze profiles of potential clients and details of car insurance marketing campaigns, thereby identifying the factors influencing the decision to subscribe to car insurance and providing recommendations to improve campaigns.

**PREPARING AND MODELING DATA**
-----------------------------------------------------------------------------------------------
Related to data shaping, blank rows in the table were removed to prevent errors. Next, data types in some columns were replaced for the convenience of writing DAX and visualizing data. In addition to setting up the table structure, the functionality forming a new group was also applied. Data Analysis Expression Language (DAX) was utilized to enhance the dataset. The Calculated table named "MonthOrder" and some Calculated columns were created to visualize the data more easily. Some Measures, such as Subscription_Rate or Total_Clients, were organized into a separate table titled 'Facts'.

**VISUALIZATION AND ANALYSIS**
-----------------------------------------------------------------------------------------------
Various cards, tables, charts and graphs were used to create 3 report pages. Some features such as Page Navigation and Bookmarks were employed to optimize the layout of the report page. Each report page provides a detailed analysis.

_Page 1: Client Demographic Overview_

- In general, this bank records a total of 4.000 potential clients and a service subscription rate of 40,10%.
- The average age of clients is 41.21 years old. Nearly a quarter of them are in management positions. The predominant educational level is at the secondary level, and the majority of customers are in a married status.
- Groups with the highest service subscription rate, segmented by demographic criteria: the over 70 age group (73,17%); the student group (66,41%); the tertiary education group (46,80%); and the single group (46,25%).

_Page 2: Client Financial Overview_

- The majority of clients have no credit default. Those with credit default account for only 1,45% of the client base, and they are less likely to subscribe to car insurance.
- The average balance of clients falls around $1.532. The group with very large balance (over $50.000) has the highest subscription rate (50%). However, there are very few clients in this group. The groups with average balance ($1.000 - $9.999) and large balance ($10.000 - $49.999) tend to have a high tendency to subscribe to the service.
- People with car loan are less likely to subscribe to the service than those without.
- People with household insurance are more likely to subscribe to the service than those without.

_Page 3: Campaign Details_

- The average call duration with clients who subscribe to car insurance is higher than with those who do not subscribe to the service.
- The group of clients aged over 70 has the lowest average number of contacts (2,16), but the highest subscription rate. Meanwhile, the age groups ‘30 – 49’ and ‘50 – 69’ have higher contact frequencies but lower subscription rates.
- Clients previously contacted have a higher subscription rate compared to those who have never been contacted before.
- Except for a few clients with days passed since the last contact exceeding 500 days, those with days passed below 100 days have the highest service subscription rate (77,78%).
- The campaign is active positively during the summer period. The most calls are made between May and August. The months of March, September, October, and December have a higher subscription rate.
- Clients are contacted a lot on certain days of the month, such as the 15th, 18th, 20th, 28th, and 29th days. The days with high service subscription rates usually fall on the first day, the 10th, 12th, and 25th days.
- Clients contacted via cellular or telephone have a high service subscription rates (about 46%).
- The success outcome of previous campaigns has the greatest impact on the subscription rate (89,26%). Clients who agreed with the previous campaign tend to continue their subscription in this campaign.

**RECOMMENDATION**
-----------------------------------------------------------------------------------------------
The profound insights gained from this report provide valuable information that can guide strategic decisions and marketing methods aimed at attracting new customers and enhancing the effectiveness of campaigns:
- Enhance advertising and care for the group of clients with high subscription rates. Simultaneously, customize strategies for the group with growth potential in the future.
- Prioritize clients with good credit history. Enhance services for them to attract their interest and increase enrollment opportunities.
- Develop specialized advertising to boost subscription likelihood among clients with large balances. Additionally, continue focusing on those holding small and average balances.
- Adjust product and service packages to attract interest from clients and minimize risks.
- Exploit further information about potential clients. Select appropriate communication methods and adjust call duration accordingly. 
- Depending on the specific context, choose suitable timing with a high subscription rate to increase service utilization likelihood.
- Continue advertising and caring for current clients to maintain and enhance satisfaction, while also creating opportunities for future subscription.





