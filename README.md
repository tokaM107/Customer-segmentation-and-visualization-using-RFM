# Customer-segmentation-and-visualization-using-RFM
### About dataset
##### this is a data analysis and RFM model for online shopping dataset
# Dataset: Online Shopping Dataset

| Column Name          | Description                                               | Data Type   |
|----------------------|-----------------------------------------------------------|-------------|
| CustomerID           | Unique identifier for each customer.                      | Numeric     |
| Gender               | Gender of the customer (e.g., Male, Female).              | Categorical |
| Location             | Location or address information of the customer.          | Text        |
| Tenure_Months        | Number of months the customer has been associated with the platform. | Numeric |
| Transaction_ID       | Unique identifier for each transaction.                   | Numeric     |
| Transaction_Date     | Date of the transaction.                                  | Date        |
| Product_SKU          | Stock Keeping Unit (SKU) identifier for the product.      | Text        |
| Product_Description  | Description of the product.                               | Text        |
| Product_Category     | Category to which the product belongs.                    | Categorical |
| Quantity             | Quantity of the product purchased in the transaction.     | Numeric     |
| Avg_Price            | Average price of the product.                             | Numeric     |
| Delivery_Charges     | Charges associated with the delivery of the product.      | Numeric     |
| Coupon_Status        | Status of the coupon associated with the transaction.     | Categorical |
| GST                  | Goods and Services Tax associated with the transaction.   | Numeric     |
| Date                 | Date of the transaction (potentially redundant with Transaction_Date). | Date |
| Offline_Spend        | Amount spent offline by the customer.                     | Numeric     |
| Online_Spend         | Amount spent online by the customer.                      | Numeric     |
| Month                | Month of the transaction.                                 | Categorical |
| Coupon_Code          | Code associated with a coupon, if applicable.             | Text        |
| Discount_pct         | Percentage of discount applied to the transaction.        | Numeric     |

### Findings:
#### Females buy more that males almost twicely 
#### Max number of months the customer has been associated with the platform is 30
#### Most frequent product category is apparel
#### Total Price and GST are negatively correlated
#### Other all features have less correlation with each other
#### Most frequent copuon state is clicked 
#### Customers who have rfm score 111 are 120 among 52524 customers 
