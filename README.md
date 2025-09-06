# Digital-Marketing---Donation-Ecommerce-Transaction-Analysis
A fusion of transactional and digital marketing data to identify and analyze marketing and purchasing trends. 

<img width="1000" height="500" alt="Donation Trend Charts" src="https://github.com/user-attachments/assets/6981acfb-dcfa-4d22-96a2-1cb4e15d10c9" />

 ## Executive Summary
 A animal care charity is planning their next marketing campaign and needs to know what campaign types and creatives perform the best overall to detemine where the advertising spend should be focused. Using Python and Tableau I extracted the data, deconstructed it into separate causes, joined it back to the marketing campaign data and visualized it in a dashboard.

After identifying the most purchased causes and the campaigns that drove them, I have the following recommendations:

1. "Supplies" donations gained the most revenue, particularly with Loyalty and Conversion campaign types. This indicates that many donors in this category have interacted with the shelter or their marketing efforts previously. I would recommend to keep Loyalty campaign types in the mix for this cause group, perhaps expanding the creatives in these campaigns.
2.  Overall, cart-abandoners are the biggest donors both in revenue and quantity of donations, showing strong engagement with the current cart-abandon retargeting methods.
3.  Display creatives are outperforming video creatives accross the board overall, with 475 conversions and $184k in revenue (vs $77K and 191 donations for video). I would recommend re-evaluating the video creatives and examining where they were served (eg. on non-clickable sites), to see if this difference is expected and if not, are the videos fatigued, not functioning or just not resonating as expected?

<img width="1000" height="1000" alt="Donation Performance Dashboard" src="https://github.com/user-attachments/assets/11667f98-51d8-47f5-8ca1-8fb69eb11a0e" />

   
## Business Problem
 How can we discern which donation types and campaigns have performed best with certain audiences and causes? 

The donation purchase data is currently captured for each web transaction, which can include 1 or multiple types of donations/causes within each transaction.  The campaign performance data table can be linked to the donation purchase data using the transaction (Order) ID. To measure the performance of each donation type (Source), frequency (eg. Monthly, once etc) and targeted cause (eg. supplies or circumstance) I split out the causes and corresponding types, amounts and frequencies.


## Methodology
1.	I created 2 data sets: <br>

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
Microsoft Excel: functions, 'random' generators.<br>
Python: Pandas, loops, functions <br>
Tableau: data visualization, data exploration, custom parameters, calculated fields <br>

## Results and Recommendations

1. "Supplies" donations are the biggest contributor to donation revenue ($135.6K) and the most frequent donation group (351/666). Supplies are very important to the shelter to generate donation revenue. I would recommend keeping this cause as an 'always' on marketing tactic as a complement to specific drive campaigns (eg. Family Spotlight, Emergency messaging).

2. The average donation is highest for one-time donations, demonstrating that donors are more generous with non-recurring gifts. Depending on the shelter's needs at the time, One-time donation marketing campaigns can be utilized to boost instant revenue, for emergencies or an influx of animals in care.

3. Cart-Abandon Audiences brought in $33,655 revenue and 83 donations indicating strong messaging performance to those 'stuck' in the conversion process.

4. Surprisingly, the recurring creatives outperformed the new in market creatives, and mid-funnel (MOF) campaigns were the top revenue drivers, this could mean that customers are interacting best with the consideration campaigns. "Kitty" and "Smile" creatives were most successful in donation quantity and revenue. As recurring creatives seem to resonate better with the donors, reinstating the existing "Kitty" and "Smile" creatives could have benefits. Consider A/B testing some new images/messaging for "Litter" and "Puppy" to increase engagement.
<img width="1269" height="758" alt="Creative Performance Tableau Dashboard" src="https://github.com/user-attachments/assets/c7f72d96-2dd4-47bb-b9aa-cf11ac434a32" />

5.The Display channel outperformed Social and Search in both revenue and donation quantity. This is unusual in marketing campaigns and digging deeper, I found that the Retargeting Display ads are bringing in the most donation quantity and revenue for cart-abandons, Shelter visits in the last 3M and charitables audience groups, together bringing in about 35K$ of donation revenue.

<img width="1269" height="751" alt="Campaign Performance Dashboard" src="https://github.com/user-attachments/assets/4cf875b3-01c7-439b-a542-290faaf17bc0" />

The most successful campaign in terms of donations was the Q2 Always-on, mid-funnel display campaign directed to the cart abandon audience with 20 donations. 
<img width="854" height="116" alt="Top Campaign by Donations Quantity" src="https://github.com/user-attachments/assets/bedf7d9f-34fc-4641-89c7-6ff27cb93967" />

The biggest revenue campaign was a display traffic, top funnel (TOF) campaign during Q3, bringing in $7725.
<img width="722" height="160" alt="image" src="https://github.com/user-attachments/assets/85e2fd70-d777-4220-8228-1e039a9dd68b" />

## Next Steps
1. Meet with marketing strategy team to present results of the study.
2. Train strategy teams on how to use the dashboard to self-serve & make any requested UI tweaks.
3. Conduct A/B testing within different campaigns & audiences (high performing and low) for creative, campaign and audience performance.









## Limitations:
Because this is a 'home-made' data set there is some randomness to the field values (Eg. TOF Conversion campaign etc).
The date range includes April - July 2025.
