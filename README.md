# Digital-Marketing---Non-Profit-Donation-Ecommerce-Transaction-Analysis
A fusion of transactional and digital marketing data to identify and analyze marketing and purchasing trends. 

(WIP)

 ## Executive Summary
 A animal care charity is planning their next marketing campaign and needs to know what types of donations perform the best and where advertising spend should be focused. Using Python and Tableau I extracted the data, deconstructed it into separate causes, joined it back to the marketing campaign data and visualized it in a dashboard.

After identifying the most purchased causes and the campaigns that drove them, I have the following recommendations.

 Recommendations:

 
## Business Problem: 
 How can we discern which donation types and campaigns have performed best with certain audiences and causes? The shelter is anticipating an influx of litters/families of animals and will need to focuse their marketing efforts to drive donations to support them.

The donation purchase data is currently captured for each web transaction, which can include 1 or multiple types of donations/causes within each transaction.  The campaign performance data table can be linked to the donation purchase data using the transaction (Order) ID. To measure the performance of each donation type (Source), frequency (eg. Monthly, once etc) and targeted cause (eg. supplies or circumstance) I split out the causes and corresponding types, amounts and frequencies.


## Methodology: 
1.	I created 2 data sets:
a.	Dataset for CleaningV2.xlsx
A web transaction data set containing the donations in each purchase (and corresponding amount) and the order ID associated with that purchase.

b.	Dataset for joiningV2.xlsx
The second data set contains the digital marketing data to join back to the transaction, including the order ID.

1.	A python algorithm to ensure that the transactions were split into their respective categories. A second algorithm to join the data back to the campaign data.
2.	A Tableau dashboard to illustrate to the stakeholders the top performers and trends.

## Skills
Microsoft Excel:
Python:
Tableau:

## Results and Recommendations:
Supplies is the biggest contributor to donation revenue ($135.6K) and the most frequent donation group (351/666).
The family spotlight, which is the shelter's most sought after donation group, drove the second highest donation revenue $83K, and 209 donations. The audiences that the family spotlight cause group most resonated with is cart-abandons, Pet owners and vet-students by donation count and cart-abandons, Pet-owners and Philathropists for revenue volume.

The frequency of Family Spotlight donations is closely dispersed for Donation frequency, with Yearly subscriptions bringing in the most revenue of $28.1K * 12mths ($338.3K over the year - the revenue only accounts for the first payments), One time donations of $28.1K



## Next Steps



### Creative Performance
<img width="1269" height="758" alt="image" src="https://github.com/user-attachments/assets/c7f72d96-2dd4-47bb-b9aa-cf11ac434a32" />

### Donation Performance
<img width="1274" height="753" alt="image" src="https://github.com/user-attachments/assets/b52944a7-8ac4-493f-bb40-3ec6eba1830f" />

### Trend Analysis
<img width="1275" height="756" alt="image" src="https://github.com/user-attachments/assets/424c1395-86bb-43f2-9fc0-8452b9f389d7" />


### Campaign Performance
<img width="1269" height="751" alt="image" src="https://github.com/user-attachments/assets/4cf875b3-01c7-439b-a542-290faaf17bc0" />





## Limitations:
Because this is a home made data set 
