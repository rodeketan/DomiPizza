# Project 3

This is the pizza ordering application which I made for this project. A user after login can order anything from the complete menu of "Pinnochio's Pizza and Subs". He can add and remove items from his cart. I have used Django in this project. Bootstrap4 is also included in order to make it more appealing. Program automatically creates superuser account at first start.

Personal Touch:
I have added a feature of allowing the site administrator to mark orders as complete and as soon as the site administrator changes the status of the order the user can see it updated in their my orders tab.



  1. index.hmlt, login.html, signin.html, menu.html:
       These files are extending layout.html file.

  2. my_orders.html
       This file shows the items that the user has ordered.

  3. orders_manager.html
       This file is only rendered when the user logs in as superuser. This gives access to the superuser to change the status of the order.

  4. models.py
       This file defines all the tables of the database.

  5. urls.py
       This file defines all the routes to the functions.

  6. views.py
       This contains the main program and functions which render the html files.

  7. Static folder contains 3 .png files and a style.css file.
