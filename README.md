# **Retail Store Sales Analysis**

## **Project Overview**

This project is focused on cleaning and visualizing data from a retail store sales dataset using only Microsoft Excel. The objective is to ensure data integrity, handle missing values effectively, and generate insightful visualizations for better business understanding. By addressing inconsistencies in sales data, this analysis helps in making data-driven decisions for retail operations. Information about the dataset used can be seen [here](https://www.kaggle.com/datasets/ahmedmohamed2003/retail-store-sales-dirty-for-data-cleaning)

## **Objectives**

-  Ensure data accuracy and consistency by handling missing values, correcting inconsistencies, and standardizing formats.
-  Identify key trends and insights by summarizing sales performance, customer behavior, and product demand using Pivot Tables.
-  Develop a visual dashboard to effectively present findings and facilitate data-driven decision-making.

## **Data Cleaning Process**

- **Item Column**: Missing values were imputed by matching the corresponding Category column.
- **Price Per Unit, Quantity, and Total Spent Columns**: Missing values were corrected using the fundamental sales formula :

  $$
  **Price Per Unit \times Quantity = Total Spent**
  $$
  
  This ensured that any inconsistencies in price or quantity were addressed accurately.
- **Discount Applied Column**: Missing values were estimated based on transaction details and logical assumptions, ensuring accurate discount representation.

## **Data Visualization**

1. **Frequently Used Payment Methods**

    ![image](https://github.com/user-attachments/assets/58563397-ba5a-47fc-b97e-da1979e22fee)
    
    Objective: To understand customer payment preferences and how they impact total revenue.
    
    Insights:
      - The analysis compares different payment methods, such as cash, credit card, and digital wallets.
      - Businesses can use this insight to optimize payment processing options, offer discounts for specific payment methods, or introduce new payment solutions.
      - If digital payment adoption is increasing, retailers can invest in improving their online transaction experience.

   
2. **Total Sales Per Category**

    ![image](https://github.com/user-attachments/assets/c17f6e22-14d2-4988-9f01-e45796e795eb)
    
    Objective: To identify which product categories generate the highest revenue.
    
    Insights :
      - This visualization highlights the total revenue contribution of each product category.
      - Categories with consistently high sales can indicate customer preference, while low-performing categories may require promotional strategies or stock adjustments.
      - This analysis is essential for inventory planning and demand forecasting.
   
3. **Monthly Revenue Performance**

    ![image](https://github.com/user-attachments/assets/197c6898-4da4-480d-ad7d-5e425b2df24b)
    
    Objective: To track sales performance across different months and identify seasonal trends.
    
    Insights :
      - The trend line showcases fluctuations in total revenue across months, helping to identify peak sales periods.
      - Spikes in revenue could correspond to seasonal events, holiday sales, or promotional campaigns.
      - This visualization supports business decisions regarding marketing strategies, inventory stocking, and resource allocation.

4. **In-Store vs Online Sales Performance**

    ![image](https://github.com/user-attachments/assets/9369ea84-9282-4f7d-b876-91c944125b38)
    
    Objective: To evaluate the difference in sales performance between physical stores and online transactions.
    
    Insights:
      - This visualization provides a side-by-side comparison of revenue generated from online and in-store sales.
      - If online sales outperform in-store sales, it suggests a shift towards digital purchasing behavior, encouraging businesses to enhance their e-commerce platforms.
      - If in-store purchases dominate, it may indicate a preference for physical shopping experiences or limited online availability of certain products.
      - Understanding this split helps in tailoring marketing efforts, improving customer experience, and optimizing sales channels.

## **Conclusion**

This project successfully addressed key challenges in retail sales data by implementing a comprehensive data cleaning and visualization process. The analysis provided valuable insights into sales performance, customer purchasing behavior, and business trends that can help optimize retail operations.

By leveraging the insights derived from this analysis, retail businesses can drive growth, customer satisfaction, and operational efficiency while adapting to evolving market trends.


