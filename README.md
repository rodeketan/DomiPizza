# DomiPizza App
- It is a Django based application in which users after login are able to browse the restaurant’s menu, add items to their cart, and submit their orders.
- In backend restaurant owners can add and update menu items, view orders that have been placed, and change the status of the order.
- Bootstrap4 is also included in order to make it more appealing. Program automatically creates superuser account at first start.
## Login Page
![alt text](https://github.com/rodeketan/pizza_app/blob/main/Images/Screenshot%20(286).png)
## Home Page
![alt text](https://github.com/rodeketan/pizza_app/blob/main/Images/Screenshot%20(288).png)
## Confirm Order
![alt text](https://github.com/rodeketan/pizza_app/blob/main/Images/Screenshot%20(290).png)



###### Additional Feature- 
I have added a feature of allowing the site administrator to mark orders as complete and as soon as the site administrator changes the status of the order the user can see it updated in their my orders tab.
## Admin Page
![alt text](https://github.com/rodeketan/pizza_app/blob/main/Images/Screenshot%20(292).png)

***


  1. **index.hmlt, login.html, signin.html, menu.html**- 
  
    These files are extending layout.html file.

  2. **my_orders.html**- 
      
    This file shows the items that the user has ordered.

  3. **orders_manager.html**- 
  
    This file is only rendered when the user logs in as superuser. This gives access to the superuser to change the status of the order.

  4. **models.py**- 
  
    This file defines all the tables of the database.

  5. **urls.py**- 
  
    This file defines all the routes to the functions.

  6. **views.py**- 
  
    This contains the main program and functions which render the html files.

  7. **Static folder** contains 3 .png files and a style.css file.
