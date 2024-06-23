# Supermarket Segmentation Analysis

![Local Image](85098ba509022672227799346e094c5b.jpg)

### Dataset Overview

#### Background: Supermarket X

This dataset includes information about customers from Supermarket X, including demographic data, product purchases, promotions that have been run and customer responses to them, as well as details about purchasing behavior and customer visit activities on the supermarket's website in 2014.

**People:**

- **ID:** Unique customer identifier
- **Year_Birth:** Year of birth of the customer
- **Education:** Education level of the customer
- **Marital_Status:** Marital status of the customer
- **Income:** Annual household income of the customer
- **Kidhome:** Number of children in the customer's household
- **Teenhome:** Number of teenagers in the customer's household
- **Dt_Customer:** Date the customer registered with the company
- **Recency:** Number of days since the customer's last purchase
- **Complain:** 1 if the customer has complained in the last 2 years, 0 if not

**Product:**

- **MntWines:** Amount spent on wine in the last 2 years
- **MntFruits:** Amount spent on fruits in the last 2 years
- **MntMeatProducts:** Amount spent on meat products in the last 2 years
- **MntFishProducts:** Amount spent on fish products in the last 2 years
- **MntSweetProducts:** Amount spent on sweets in the last 2 years
- **MntGoldProds:** Amount spent on gold products in the last 2 years

**Promotion:**

- **NumDealsPurchases:** Number of purchases with a discount
- **AcceptedCmp1:** 1 if the customer accepted the offer in the first campaign, 0 if not
- **AcceptedCmp2:** 1 if the customer accepted the offer in the second campaign, 0 if not
- **AcceptedCmp3:** 1 if the customer accepted the offer in the third campaign, 0 if not
- **AcceptedCmp4:** 1 if the customer accepted the offer in the fourth campaign, 0 if not
- **AcceptedCmp5:** 1 if the customer accepted the offer in the fifth campaign, 0 if not
- **Response:** 1 if the customer accepted the offer in the last campaign, 0 if not

**Place:**

- **NumWebPurchases:** Number of purchases made through the company's website
- **NumCatalogPurchases:** Number of purchases made using the catalog
- **NumStorePurchases:** Number of direct purchases in the store
- **NumWebVisitsMonth:** Number of visits to the company's website in the last month

#### Background Problem

Supermarket X has faced issues with marketing campaigns that are not engaging to its members. This may be due to lack of campaign appeal, lack of personalization in offers, or misunderstanding of member preferences. However, the last campaign succeeded in attracting more customers. Despite this, management recognizes the need to continuously develop effective campaign strategies to maintain the interest of existing members. They also observe a decline in interest in membership that needs to be addressed with a better understanding of their various customer segments. Through market segmentation analysis, Supermarket X can identify groups of customers with similar characteristics, helping them develop more effective campaign strategies. This will enable them to better address the decline in customer interest in the future.

#### Business Task

**Main Problem**

Management wants to find ways to improve their campaign program to prevent a decline in customer interest in joining the membership program while also making the campaign program more effective and relevant based on customer preferences. This will ensure existing members remain active and profitable, and encourage non-members to join the membership program.

**Problem Formulation**

Steps to perform the analysis:

1. Identify various market segments based on relevant categories.
2. Is there a relationship between Customer Recency and Shopping Interest?
3. How does income affect supermarket customer shopping patterns?
4. Do differences in educational background affect shopping preferences and interest?
5. Is there a correlation between age and shopping preferences and interest?
6. Do married customers tend to shop more than unmarried customers?
7. Does having children affect shopping patterns?
8. Evaluate the most efficient marketing channels.
9. Provide conclusions and marketing strategy recommendations.
