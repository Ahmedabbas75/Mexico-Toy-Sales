## 1- Dashboard :
</p>
  <p float="left">
  <img src='resources/Mexico Toy Sales page one.jpg'/>
  <img src='resources/Mexico Toy Sales page 2.jpg'/>
</p>
__________________________________________________________________________________________________________________________

## 2- About the Dataset :
Sales & inventory data for a fictitious chain of toy stores in Mexico called Maven Toys, including information about products, stores, daily transactions, and current inventory levels at each location.
__________________________________________________________________________________________________________________________

## 3- Tables Description :

## Products Table:
|Field	| Description |
|-----|----------------|
| Product_ID |	Product ID |
| Product_Name |	Product name |
| Product_Category |	Product Category |
| Product_Cost |	Product cost ($USD) |
| Product_Price |	Product retail price ($USD) |

## Inventory Table:
|Field	| Description |
|-----|----------------|
|	Store_ID |	Store ID |
|	Product_ID |	Product ID |
| Stock_On_Hand |	Stock quantity of the product in the store (inventory) |

## Stores Table:
|Field	| Description |
|-----|----------------|
|	Store_ID|	Store ID|
|	Store_Name|	Store name|
|	Store_City|	City in Mexico where the store is located|
|	Store_Location|	Location in the city where the store is located|
| Store_Open_Date|	Date when the store was opened|

## Sales Table:
|Field	| Description |
|-----|----------------|
|	Sale_ID|	Sale ID|
|	Date|	Date of the transaction|
|	Store_ID|	Store ID|
|	Product_ID|	Product ID|
|	Units|	Units sold|

## Calendar Table:
|Field	| Description |
|-----|----------------|
| Calendar |	Date|	Calendar date|
__________________________________________________________________________________________________________________________

## 4- Database Digrams

</p>
  <p float="left">
  <img src='resources/Mexico Toy Sales.png'/>
</p>
__________________________________________________________________________________________________________________________

## 5- In Mind Questions :

- ## Project Objective :
  - Connect to SQL Server and Check Tables. 
  - Create a relational model.
  - Add calculated measures & fields
  - Build an interactive report

- ## Business Questions :
  ### 📌1️⃣ Which product categories drive the biggest profits? Is this the same across store locations?
    - Total profit among the five product categories was observed in `Toys`, *reaching $1,079,527*. This figure was **113.46%** higher than the lowest total profit, which was in the `Sports & Outdoors` category at *$505,718.*

    - `Toys` accounted for a significant portion of the total profit, *contributing to 26.89% of the overall profits across all five product categories.*

    - Total profits across the entire set of product categories ranged from **$505,718** to **$1,079,527**. *This indicates a considerable variation in profitability across the different product categories.*
    
    - 🛑 profit percentage varies from one location to another:
        - ➡️ In **`Residential`**
          - `Toys` recorded the highest total profit at *$136,214*, demonstrating a **125.68%** increase compared to the lowest total profit in `Sports & Outdoors`, which was *$60,358.*

          - `Toys` contributed significantly to the overall profitability, *representing 29.59% of the total profit across all five product categories.*

          - Total profit across the five product categories varied, ranging from **$60,358** to **$136,214**, *showcasing distinct levels of profitability within the product portfolio.*
        
        - ➡️ In **`Downtown`**
          - `Toys` led with the highest total profit at *$630,029*, marking a **114.68%** increase compared to the lowest total profit in `Sports & Outdoors`, which amounted to *$293,468.*

          - `Toys` significantly contributed to the overall profitability, *accounting for 28.02% of the total profit across all five product categories.*

          - Total profit across the five product categories showed variation, ranging from **$293,468** to **$630,029**, *illustrating diverse levels of profitability within the product portfolio.*

        - ➡️ In **`Commercial`**
          - `Electronics` led with the highest total profit at *$287,574*, demonstrating a **155.62%** increase compared to the lowest total profit in `Sports & Outdoors`, which amounted to *$112,499.*

          - `Electronics` made a substantial contribution to the overall profitability, *representing 31.03% of the total profit across all five product categories.*

          - Total profit across the five product categories displayed variation, ranging from **$112,499** to **$287,574**, *highlighting diverse levels of profitability within the product portfolio.*
         
        - ➡️ In **`Airport`**
          - `Electronics` led with the highest total profit at *$108,197*, showing a substantial **174.66%** increase compared to the lowest total profit in Sports & Outdoors, which amounted to *$39,393.*

          - `Electronics` contributed significantly to the overall profitability, *representing 28.62% of the total profit across all five product categories.*

          - Total profit across the five product categories varied, ranging from **$39,393** to **$108,197**, *indicating diverse levels of profitability within the product portfolio.*
            
  ### 📌2️⃣ Can you find any seasonal trends or patterns in the sales data?
    - ➡️ In **`Sprint`**
      
      - Total orders for `Toys` reached **58,806**, *making it the product category with the highest demand.*
      - This was **93.35%** higher than `Electronics`, *which had the lowest total orders at 30,414.*
      - `Toys` accounted for a significant portion, representing **26.46%** of the total orders.
      - Across all five product categories, the total orders varied, ranging from **30,414** to **58,806.**
        
    - ➡️ In **`Summer`**

      - `Toys` had the highest total orders, reaching **72,085.**
      - This total was **162.58%** higher than `Electronics`, *which had the lowest total orders at 27,453*
      - `Toys` accounted for **28.48%** of the total orders, indicating a significant share of overall demand.
      - Across all five product categories, the total orders ranged from **27,453** to **72,085**, highlighting the variability in demand across different product types.
     
     - ➡️ In **`Autumn`**

       - `Art & Crafts` had the highest total orders, **reaching 64,157.**
       - This total was **138.05%** higher than `Electronics`, which had the lowest total orders of **26,951.**
       - `Art & Crafts` accounted for **27.88%** of the total orders, indicating a substantial share of overall demand.
       - Across all five product categories, the total orders ranged from **26,951** to **64,157**, showcasing the variability in demand across different product types.
      
     - ➡️ In **`Winter`**
       - 


