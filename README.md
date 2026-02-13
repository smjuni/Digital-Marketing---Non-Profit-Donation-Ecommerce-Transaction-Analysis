# Digital-Marketing---Donation-Ecommerce-Transaction-Analysis
A fusion of transactional and digital marketing data used to identify and analyze marketing and purchasing trends to inform future marketing decisions. 

 [Tableau Dashboard Link](https://public.tableau.com/app/profile/stephanie.m.juniper/viz/DigitalMarketingTransactionAnalysis/CreativePerformanceDashboard)

<img width="1000" height="500" alt="Donation Trend Charts" src="https://github.com/user-attachments/assets/6981acfb-dcfa-4d22-96a2-1cb4e15d10c9" />

 ## Executive Summary
 A animal care charity is planning their next marketing campaign cycle and needs to know what campaign types and creatives perform the best overall to detemine where the advertising spend should be focused. 

Using Python and Tableau I extracted the data, deconstructed it into separate causes, joined it back to the marketing campaign data and visualized it in a dashboard.


<img width="1000" height="1000" alt="Donation Performance Dashboard" src="https://github.com/user-attachments/assets/11667f98-51d8-47f5-8ca1-8fb69eb11a0e" />
TOP 5 Campaigns & Causes By Total Donations<img width="468" height="167" alt="image" src="https://github.com/user-attachments/assets/6f198097-5fb1-4cf7-b5cb-7bbf33fa3ea4" />


After identifying the most purchased causes and the campaigns that drove them, I have the following recommendations:

 TOP 5 Campaigns & Causes By Donation Value
<img width="842" height="968" alt="image" src="https://github.com/user-attachments/assets/85c853fd-526d-444b-ab5c-8c8311bb070b" />


TOP 5 Campaigns & Causes By Total Donations
 <img width="838" height="994" alt="image" src="https://github.com/user-attachments/assets/5d1dfa2c-311d-4e83-9149-528232b7491d" />


## Business Problem
A animal care charity is planning their next marketing campaign and needs to know what types of donations perform the best and where advertising spend should be focused. How can we discern which donation types and campaigns have performed with certain audiences and causes?

The donation data is currently captured at the transaction level, which can include 1 or multiple donations within each transaction.  To measure the performance of each donation type, frequency (eg. Monthly, once etc) and targeted cause (eg. supplies or circumstance) I split out the causes and corresponding types, amounts and frequencies.

<img width="468" height="161" alt="image" src="https://github.com/user-attachments/assets/47471b56-5144-4192-a848-16607dc86823" />

Before:

 <img width="468" height="26" alt="image" src="https://github.com/user-attachments/assets/7f24e6d6-4445-41fb-b76b-dbc767dab861" />

After:
 
<img width="468" height="69" alt="image" src="https://github.com/user-attachments/assets/08a35284-4afc-4fdc-a0d1-c9ae8f8e1622" />


## Methodology

1.	I created 2 data sets with the help of ChatGPT: <br>

a.	Dataset for CleaningV2.xlsx <br>
A web transaction data set containing the donations in each purchase (and corresponding amount) and the order ID associated with that purchase. <br>
<br>
b.	Dataset for joiningV2.xlsx <br>
The second data set contains the digital marketing data to join back to the transaction, including the order ID. <br>
<br>
2.	A python algorithm to ensure that the transactions were split into their respective categories. A second algorithm to join the data back to the campaign data.<br>
<br>
3.	A Tableau dashboard to illustrate to the stakeholders the top performers and trends.<br>

## Skills
Microsoft Excel: functions, 'random' generators, data exploration.<br>
Python: Pandas, loops, functions <br>
Tableau: data visualization, data exploration, custom parameters, calculated fields <br>

## Results and Recommendations
Being able to split Transactions down into individual donations we are able to see the top performing product and campaign data.

Based on the split data, we can confirm that the FY25_Q3_Traffic_Display_TOF_Activists campaign was most effective by value for driving supply donations (Bowls, Cleaning, Grooming, Food and Toys).

<img width="842" height="968" alt="image" src="https://github.com/user-attachments/assets/043ccd32-058e-4f3f-8d8f-2706e34107c5" />

We can also see that Rosie's Litter drew the most most individual donations (45). This could indicate superior creative or marketing messaging and features, good website placement presence, better or different photography, something out of marketing control such as breed or visual appeal.

<img width="568" height="616" alt="image" src="https://github.com/user-attachments/assets/6d193f30-753e-4297-b9c8-4bc1b6c73ebb" />


## Next Steps
1. Meet with marketing strategy team to present results of the study.
2. Train strategy teams on how to use the dashboard to self-serve & make any requested UI tweaks.
3. Conduct A/B testing within different campaigns & audiences (high performing and low) for creative, campaign and audience performance.



## Limitations:
Because this is a 'home-made' data set there is some randomness to the field values (Eg. TOF Conversion campaign etc).
The date range includes April - July 2025.
