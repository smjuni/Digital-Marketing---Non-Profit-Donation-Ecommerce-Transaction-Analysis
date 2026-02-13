# Digital-Marketing---Donation-Ecommerce-Transaction-Analysis
A fusion of transactional and digital marketing data used to identify and analyze marketing and purchasing trends to inform future marketing decisions. 

 [Tableau Dashboard Link](https://public.tableau.com/app/profile/stephanie.m.juniper/viz/DigitalMarketingTransactionAnalysis/CreativePerformanceDashboard)


 ## Executive Summary
A animal care charity is planning their next marketing campaign and needs to know what types of donations perform the best and where advertising spend should be focused. How can we discern which donation types and campaigns have performed with certain audiences and causes?

Using Python and Tableau I extracted the data, deconstructed it into separate causes, joined it back to the marketing campaign data and visualized it in a dashboard.


<img width="1272" height="757" alt="image" src="https://github.com/user-attachments/assets/d8c1223b-7b44-4848-b0ee-7815d02fa2c3" />


After identifying the most purchased causes and the campaigns that drove them, I have the following recommendations:

1. "Supplies" donations are the biggest contributor to donation revenue ($135.6K) and the most frequent donation group (351/666). "Supplies" cause group is very important to the shelter to generate donation revenue. I would recommend keeping this cause as an 'always' on marketing tactic as a complement to specific drive campaigns (eg. Family Spotlight, Emergency messaging).

2. The average donation is highest for yearly donations, demonstrating a great relationship with their donors. One time donors provide the greatest Donation Value ($), demonstrating that donors are more generous with non-recurring gifts.
Depending on the shelter's needs at the time, One-time donation marketing campaigns can be utilized to boost instant revenue, for emergencies or an influx of animals in care.

3. Cart-Abandon Audiences brought in $33,655 revenue and 83 donations indicating strong messaging performance to those 'stuck' in the conversion process.


## Business Problem


The donation data is currently captured at the transaction level, which can include 1 or multiple donations within each transaction.  To measure the performance of each donation type, frequency (eg. Monthly, once etc) and targeted cause (eg. supplies or circumstance) I split out the causes and corresponding types, amounts and frequencies.

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

1. Based on the split donation data, we can confirm that the FY25_Q3_Traffic_Display_TOF_Activists campaign was most effective by value for driving supply donations (Bowls, Cleaning, Grooming, Food and Toys).

<img width="568" height="616" alt="image" src="https://github.com/user-attachments/assets/043ccd32-058e-4f3f-8d8f-2706e34107c5" />

2. We can also see that Rosie's Litter drew the most most individual donations (45). This could indicate superior creative or marketing messaging and features, good website placement presence, better or different photography, something out of marketing control such as breed or visual appeal.

<img width="568" height="616" alt="image" src="https://github.com/user-attachments/assets/6d193f30-753e-4297-b9c8-4bc1b6c73ebb" />


 3. "Supplies" donations gained the most revenue, particularly with Loyalty and Conversion campaign types. This indicates that "Supplies" appeal to many donors in these campaign groups and also that these donors have interacted with the shelter or their marketing efforts previously. I would recommend keeping Loyalty campaign types for the next campaign cycle, and perhaps experiment with expanding the creative range. Conversion campaigns are always in-market, but in order to drive more "Supplies" revenue (or different cause revenue), I would recommend testing different landing pages/Call to Actions to see if the marketing influences the donors, or if it is a characteristic of the targeted audience.
 
<img width="1152" height="720" alt="image" src="https://github.com/user-attachments/assets/7359788b-085c-4be8-ae01-40bb3ac04ef0" />


4. Overall, the cart-abandoners audience are the biggest donors both in revenue and quantity of donations, showing strong engagement with the current cart-abandon retargeting methods. I recommend reusing and monitoring campaigns targeting this segment in the next cycle to ensure repeat success.


## Next Steps
1. Meet with marketing strategy team to present results of the study.
2. Train strategy teams on how to use the dashboard to self-serve & make any requested UI tweaks.
3. Conduct A/B testing within different campaigns & audiences (high performing and low) for creative, campaign and audience performance.



## Limitations:
Because this is a 'home-made' data set there is some randomness to the field values (Eg. TOF Conversion campaign etc). The data is also split more normally than 'real life' would suggest.
The date range includes April - July 2025.
