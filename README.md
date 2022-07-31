# React_Buyer-app-v.1

The application contains a defined list of products in the src / common / consts / products.js file.
The left column (of available products) displays a list of products from the products.js file as an unnumbered list (we only display the name).
Left-clicking on one of the products adds it to the 'shopping list'.
The right column displays the current shopping list.
After clicking on any product from the list of available products, it will appear on the shopping list 
(the selected element does not disappear from the list of available products).
It is possible to choose the same product multiple times.
Left-clicking on any item from the shopping list removes it from the list 
(this simulates a situation in which someone threw the product into the shopping cart and removed it from the shopping list).
The list on the left can be filtered to find the product you are interested in in a short time. 

The filter section has 2 types of dynamic filters:
 - after the name (or its part)
 - by category, it is possible to select any category from among the existing ones (dropdown, categories downloaded dynamically)
 - "Only food" filter, which is an input of the "checkbox" type

The user can add additional products to the list on the left. Data should be complete.
The newly added products are fully interactive, i.e. work in line with the previous tasks. (e.g. new categories are shown in the drop-down list).
Right-clicking on an item from the shopping list causes it to be crossed out. 
Right-clicking on a crossed-out element again causes it to go back as non-crossed.

-------------------------------------------------------------------------------------------------------------------------------------------------

**Clone/copy project**

**npm init -y**

**npm install**

**npm start**

http://localhost:3000

https://github.com/TomaszJaniszta/React_Buyer-app-v.1/blob/main/Buyer-app1.PNG

https://github.com/TomaszJaniszta/React_Buyer-app-v.1/blob/main/Buyer-app1eng.mkv
