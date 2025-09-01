# Digital-Marketing---Donation-Ecommerce-Transaction-Analysis
A fusion of transactional and digital marketing data to identify and analyze marketing and purchasing trends. 

(WIP)

 ## Executive Summary
 A animal care charity is planning their next marketing campaign and needs to know what campaign types and creatives perform the best overall and especially with Family Spotlight cause to detemine where the advertising spend should be focused. Using Python and Tableau I extracted the data, deconstructed it into separate causes, joined it back to the marketing campaign data and visualized it in a dashboard.

After identifying the most purchased causes and the campaigns that drove them, I have the following recommendations.
#### Overall:
1. "Supplies" donations gained the most revenue, particularly with Loyalty and Conversion campaign types. This indicates that many donors in this category have interacted with the shelter or their marketing efforts previously. I would recommend to keep Loyalty campaign types in the mix for this cause group, perhaps expanding the creatives in these campaigns.
2.  Overall, cart-abandoners are the biggest donors both in revenue and quantity of donations, showing strong engagement with the current cart-abandon retargeting methods.
4.  Display creatives are outperforming video creatives accross the board overall, with 475 conversions and $184k in revenue (vs $77K and 191 donations for video). I would recommend re-evaluating the video creatives and examining where they were served (eg. on non-clickable sites), to see if this difference is expected and if not, are the videos fatigued, not functioning or just not resonating as expected?
   
### Family Spotlight:

1. Family Spotlight donations have not gained as much traction with Loyalty campaign types, and considering the focus on this cause group, I would recommend testing new creatives/messaging within the loyalty campaign to appeal to the family spotlight donors. Alternatively, advertising spend on this campaign could be diverted to Retargeting, Conversion and Engagement campaigns, which attracted more Family Spotlight donations. Because the highest average donations come from people who have visited the shelter within the last 3 months, I would recommend a campaign geared towards increasing shelter visits.
2. The creatives that drove the most donation revenue for Family spotlight causes were the "Kitty" Display ads (15K), "Smile" Display and "Cuddles" display.
3. Kitty and Smile creatives were most successful overall both bringing in over $19K of revenue and 50+ donations for Family Spotlight. 
 
## Business Problem
 How can we discern which donation types and campaigns have performed best with certain audiences and causes? The shelter is anticipating an influx of litters/families of animals and will need to focuse their marketing efforts to drive donations to support them.

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
Microsoft Excel: functions, 'random' generators.
Python: Pandas, loops, functions
Tableau: data visualization, parameters, calculated fields 

## Results and Recommendations

### Overall:
"Supplies" donations are the biggest contributor to donation revenue ($135.6K) and the most frequent donation group (351/666).
The family spotlight, which is the shelter's most sought after donation group, drove the second highest donation revenue $83K, and 209 donations. The audiences that the family spotlight cause group most resonated with is cart-abandons, Pet owners and vet-students by donation count and cart-abandons, Pet-owners and Philathropists for revenue volume.

The donation frequency of Family Spotlight donations is closely dispersed, with yearly subscriptions bringing in the most revenue, $28.1K * 12mths ($338.3K over the year - the revenue only accounts for the first payments), and 73 donations.

The average donation is highest for one-time donations, demonstrating that donors are more generous with non-recurring gifts.

#### Recommendations:
Supplies are very important to the shelter to generate donation revenue. I would recommend keeping this cause as an 'always' on marketing tactic which can complement the drive for family spotlight and emergency messaging.


<img width="1000" height="1000" alt="Donation Tableau Dashboard Screenshot" src="https://github.com/user-attachments/assets/406cd93c-d515-4f5b-b9bf-879187d25f4d" />

### Family Spotlight
  In general, the population responded to the family spotlight cause group best for LeadGen campaign types, with the highest average donation ($503). Retargeting, LeadGen and Engagement Campaign Types performed best for donation revenue. The campaign that resonated least with the family spotlight cause group was loyalty campaign type, with only 7% of the total donations and lowest donation revenue ($5.8K) for the April to July time period. 

The audiences who have the highest average donations to family spotlight causes are people who have visited the Shelter within the last 3 months and the philanthropist audience comprised of regular, high-income donors. 

#### Recommendations:
Revisit loyalty campaign parameters, perhaps the messaging or targeting can be adjusted to appeal more to Family spotlight donors.
For upcoming campaigns, boost ad spend into Retargeting, LeadGen and Engagement campaign types, building lookalike audiences from these campaigns. Test linking Supply cause groups with family spotlight cause groups to measure crossover.
To increase the Shelter-visit-3mths audience, I would recommend running a concurrent campaign to entice shelter visits.


### Creative Performance

<img width="1269" height="758" alt="Creative Performance Tableau Dashboard" src="https://github.com/user-attachments/assets/c7f72d96-2dd4-47bb-b9aa-cf11ac434a32" />



## Next Steps
1. Meet with marketing strategy team to present results of the study.
2. Train strategy teams on how to use the dashboard to self-serve & make any requested tweaks.
3. Conduct A/B testing within different campaigns & audiences (high performing and low) for creative, campaign and audience performance.



Donation Performance
<img width="1274" height="753" alt="image" src="https://github.com/user-attachments/assets/b52944a7-8ac4-493f-bb40-3ec6eba1830f" />

Trend Analysis
<img width="1275" height="756" alt="image" src="https://github.com/user-attachments/assets/424c1395-86bb-43f2-9fc0-8452b9f389d7" />


Campaign Performance
<img width="1269" height="751" alt="image" src="https://github.com/user-attachments/assets/4cf875b3-01c7-439b-a542-290faaf17bc0" />





## Limitations:
Because this is a home made data set 
