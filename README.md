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
