# [PYTHON] RFM Analysis
## I. Introduction
### 1. About RFM Analysis
### Why RFM?
- RFM is a marketing analysis technique that stands for Recency, Frequency, and Monetary Value.
  - **Recency**: measures how recently a customer has made a purchase.
  - **Frequency**: measures how often a customer has made purchases.
  - **Monetary Value**: measures the total amount of money a customer has spent on purchases.
- RFM is used to identify and categorize customers based on their purchasing behavior and how recently and frequently they have made purchases, as well as the monetary value of those purchases.
### How?
- In RFM analysis, customers are scored based on three factors (Recency - how recently, Frequency - how often, Monetary - how much), then labeled based on the combination of RFM scores
### Reference
- [RFM Analysis For Successful Customer Segmentation](https://www.putler.com/rfm-analysis)

### 2. Business Questions
- The Marketing Department needs to classify the segments of each customer to deploy each marketing program suitable for each customer group.
- The Marketing Director also proposed a plan to use the RFM model in Python to segment customers, and then launch marketing campaigns to thank customers for supporting the company over the past time. As well as exploit potential customers to become loyal customers.
- Suggestions to the Marketing team with the company's retail model, which of the three indicators R, F, and M should be most interested in?

## II. Data Visualization with Python
- **Barchart of Number of Customers per Segment**

![image](https://github.com/user-attachments/assets/3787c6ab-e884-481d-ad20-441b80ecfa70)

- **Piechart of Percentage of Customers per Segment**

![image](https://github.com/user-attachments/assets/04a6cd8e-af23-4e9b-8b1f-fafada553ffe)

- **Percent of country buying**

![image](https://github.com/user-attachments/assets/d069c0a1-64a0-4e36-8490-ebf9f0453255)

- **Top 5 subcategory**

![image](https://github.com/user-attachments/assets/03ed559c-afca-4e6e-8b80-52b134521962)

## III. Insights
- 1.The most important index of the 3 indicators that the SuperStore company needs to pay attention to is F, then R: because the rate of customers buying once and twice is very high. Very few customers make long-term purchases like 8-9 times or more.
     -> That shows that the customer retention rate at the company is still low.
     
- 2.About Customer Segmentation: The company is mainly "Champions" >"Hibernating customers">"Lost customers".
    -> This again shows that we need to pay attention to the index F.
  
- 3.Revenue and profit from "Champions" is the highest.

- 4.The country that buys the most is the United States (90.7%).
  
- 5.The main subcategory are: WHITE HANGING HEART T-LIGHT HOLDER(24.4%), REGENCY CAKESTAND 3 TIER(22.5%), JUMBO BAG RED RETROSPOT(19.6%), ASSORTED COLOUR BIRD ORNAMENT & PARTY BUNTING (16.7%).
## IV. Recommendations
- The company needs to have policies to:
  - **Retaining Champion**:
    - As the highest-end customer group, it also accounts for the largest proportion of up to 19.8%.
    - This customer group meets all factors such as purchase time, purchase frequency as well as large order value.
    - This customer group can be considered the company's largest source of revenue
Should be maintained.
    - For customers who have made a high-value purchase, thank them for their business and offer a loyalty program that rewards them for their continued purchases.
    - For customers who have made multiple purchases in the past but have not made one recently, send personalized email campaigns that showcase new products or services that may be of interest to them
  - **Promoting hibernating customers**:
    - For hibernating customers who have not made a purchase in a while, send a win-back email or offer that encourages them to return to our business.
    - Offer a special discount or promotion that is personalized based on their past purchases.
    - For customers who have made multiple purchases in the past but have not made one recently, send personalized email campaigns that showcase new products or services that may be of interest to them.
    - For high-value customers who have not made a purchase in a while, send a personalized email or offer that highlights new products or services that may be of interest to them and offer a special discount or promotion that is tailored to their past purchase history.


