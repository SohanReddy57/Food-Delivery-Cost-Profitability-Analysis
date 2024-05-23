# Food_Delivery_Cost & Profitability_Analysis
Food Delivery Cost and Profitability Analysis involves examining all the costs associated with delivering food orders, from direct expenses like delivery fees and packaging to indirect expenses like discounts offered to customers and commission fees paid by restaurants. By juxtaposing these costs against the revenue generated (primarily through order values and commission fees), the analysis aims to provide insights into how profitable the food delivery service is on a per-order basis.

Below is the process I followed for the task of Food Delivery Cost and Profitability Analysis:

1. Started by gathering data related to all aspects of food delivery operations.
2. Cleaned the dataset for inconsistencies, missing values, or irrelevant information.
3. Extracted relevant features that could impact cost and profitability.
4. Broke down the costs associated with each order, including fixed costs (like packaging) and variable costs (like delivery fees and discounts).
5. Determined the revenue generated from each order, focusing on commission fees and the order value before discounts.
6. Calculated the profit by subtracting the total costs from the revenue. Analyzed the distribution of profitability across all orders to identify trends.
7. Based on the cost and profitability analysis, developed strategic recommendations aimed at enhancing profitability.
8. Used the data to simulate the financial impact of proposed changes, such as adjusting discount or commission rates.

# Cost and Profitability Analysis
For the cost analysis, I considered the following costs associated with each order:

**Delivery Fee**: The fee charged for delivering the order.  
**Payment Processing Fee**: The fee for processing the payment.  
**Discount Amount**: The discount provided on the order.  

* We should calculate the total cost for the platform per order and then aggregate this data to understand the overall cost structure.
* The revenue for the platform is mainly derived from the Commission Fee. We should calculate the net profit by subtracting the total costs (including discounts) from the revenue generated through commission fees.

# A New Strategy for Profits
From the analysis I understood that the discounts on food orders are resulting in huge losses. Now, we need to find a new strategy for profitability. We need to find a sweet spot for offering discounts and charging commissions. To find a sweet spot for commission and discount percentages, I analyzed the characteristics of profitable orders more deeply. Specifically for these:

* A **new average commission** percentage based on profitable orders.
* A **new average discount** percentage for profitable orders, that could serve as a guideline for what level of discount still allows for profitability.

From these new averages, 
* The average commission percentage for profitable orders is significantly higher than the overall average across all orders which suggests that a higher commission rate on orders might be a key factor in achieving profitability.
* The average discount percentage for profitable orders is notably lower than the overall average, indicating that lower discounts might contribute to profitability without significantly deterring order volume.

