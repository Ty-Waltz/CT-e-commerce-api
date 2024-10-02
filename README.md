# Welcome to the E-Commerce-API   
## Here I will explain how all the functions work  
At the beginning, you will see a few "Schema" classes. These are simply for translating information to and from any API youre using  

### Customer management:  
Here there are 2 classes for customer management.  
1. Customer: Which is used for all the customer info (id, name, email, phone number, and orders)  
   There is a couple routes associated with Customer:  
   - (GET): used to retrieve a customer's info  
   - (POST): used add a customer to the database  
   - (PUT): used to update a customer's info  
   - (DELETE): used to delete a customer form the database  
2. CustomerAccount: This class is similar but is used to store and keep track of one customer's log in information
   There is a couple routes associated with CustomerAccount:  
   - (GET): used to retrieve a customer account  
   - (POST): used add a customer account to the database  
   - (PUT): used to update a customer's account  
   - (DELETE): used to delete a customer's account form the database  

   ### Product Management:    
   There is only one class for procts management.  
   1. Product: Used for all product info (id, name, price, stock, orders)  
      There is a couple routes associated with Product:  
        - (GET): used to retrive a product's info (or multiple products info if you need more than one)   
        - (POST): used to add a product to the database  
        - (PUT): used to update a product  
        - (DELETE): used to delete a product  
 
  ### Stock/Orders:  
  Stock/Orders uses both the 'Procuct' and 'Order' class  
  1. Order: takes the date, id of the order, and customer id a keeps them together  
   There is 2 routes associates with Order:  
   - (GET): used to retrieve am orders info  
   - (POST): used to add an order  
  2. Product: uses the stock part of the class to keep track of how much of an item is left  
     There is a couple routes associated with Product  
     - (GET): used to retrieve a product's stock  
     - (PUT): used to update a product's stock  
     - (POST): used to restock a product  
  
  
   

