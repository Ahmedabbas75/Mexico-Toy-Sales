## 1- Dashboard :

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

    - The total profits across the entire set of product categories ranged from **$505,718** to **$1,079,527**. *This indicates a considerable variation in profitability across the different product categories.*
    
    - 
  
