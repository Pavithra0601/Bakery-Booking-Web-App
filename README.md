# Industrial-Canteen-Booking-Web-App
This is the Cafeteria Web Application i developed for Engine factory Avadi

**Login Page:
**
![image 1](https://github.com/Pavithra0601/Industrial-Canteen-Booking-Web-App/assets/174179024/7e1f1023-2258-41f6-acd7-31057df4047d)



This page is where the admin accesses the canteen management system through login Id and password. Passwords are only known to the admin of the canteen. When correct login Id and password is entered, the credentials are compared with the database table, if they are a match, then the user is admitted to enter the webpage. The webpage redirects to the menu page.

**Menu page:
**

![image 2](https://github.com/Pavithra0601/Industrial-Canteen-Booking-Web-App/assets/174179024/a5dff44f-738a-45be-82ab-0161142784a4)


●	This is the page where order creation takes place. It also has a navigation header bar on all webpages which helps in easier navigation to different modules on the canteen system. It also provides the option to change password whenever required. Logout can be done when exiting the application. 

●	Employee details is a select option where the options are all employees at EFA. the options are loaded dynamically every time the page refreshes, this makes the select option to be updated every time it is accessed. It is also provided with search option for easier finding of employees. The options are filled with permanent number, name and section name, this eliminates the confusion of employees with same names.

●	Other text fields are provided for other staff members who don't have a permanent number for their own.

●	The items are loaded from the products table under their respective category. Quantity column, is where the number items required for each order is entered. The buttons on either side of the text field is for adding or subtracting the quantity by 1. The amount column shows the total amount for the respective items in the row. The amount column is dynamically updated when the quantity is entered.

●	Total amount is summation of all items amount to a grand total.

●	Create order button saves the quantity entered for each item. Items with 0 quantity are ignored. It also collects the employee details entered along with the time when the order button is pressed. A dialog box appears asking for order confirmation with the summary of items and quantity with total amount. When pressed ‘OK’ the order is placed and the order id is displayed. If pressed ‘cancel’, the order is cancelled.

●	Clear button clears all fields and displays a fresh page.

 

**Order history:
**

![image 3](https://github.com/Pavithra0601/Industrial-Canteen-Booking-Web-App/assets/174179024/ac407dd5-bc8b-4b9b-bc13-f9f15a888c6a)


●	This module contains the details of all orders placed within a specified interval date period. The date option at the start of the page gives the user a filter option to display the orders between certain time interval. 

●	The data shown contains serial number, order number, Permanent number, items with their respective quantity, total amount to be paid, order date and time, status of the order - whether the order is been issued to the customer or not, delete option, and printing the bill.
 

**Manage categories:
**

![image 4](https://github.com/Pavithra0601/Industrial-Canteen-Booking-Web-App/assets/174179024/bbd9b66b-5321-422d-8dc3-13122500943a)


These are categories where items are added under each category. For example omm podi is added under snacks order, jangri will be added under sweets category. Each category name is given an unique Id. the name of the category can be edited as well. Deletion of categories can also be done.
 

**Add Category:
**

![image 5](https://github.com/Pavithra0601/Industrial-Canteen-Booking-Web-App/assets/174179024/050eff5b-3a4b-43ae-b301-81cafe6f6648)


New categories can also be added to the category list. A unique id will be allotted for the newly created category.
 

**Manage products:
**

![image 6](https://github.com/Pavithra0601/Industrial-Canteen-Booking-Web-App/assets/174179024/732d127f-8069-4134-b450-01e6faf911f6)


In this module, all the products are displayed along with their category name and weight in which each item is sold, the rate for each item for quantity of 1,edit product details, status is where the item is displayed on the menu only if they are confirmed, and hidden if they are not confirmed. This allows the admins to dynamically edit the sales information whenever they want. Raw materials is where the admin adds raw materials required to make the item. They specifythe basic amount of raw materials required for a specified weight, which then the web app calculates the amount of raw materials required for total orders received for the respective item.
 

**Add Item:
**

![image 7](https://github.com/Pavithra0601/Industrial-Canteen-Booking-Web-App/assets/174179024/1c274ee9-e1f2-4ea1-8699-5959b7a9ed14)


New items can be added, which will be displayed in the product list page and as well as menu page. Rate and weight specified here will be used to calculate summary in the summary webpage.

 


**Edit product:
**

![image 8](https://github.com/Pavithra0601/Industrial-Canteen-Booking-Web-App/assets/174179024/b944fbbe-b1a7-4337-a416-a3cb31a1d21a)


Products can be edited here, but the name of the item should not be changed to another item name, this leads to inconsistency while data retrieval and calculations.
 

**Order summary:
**

![image 9](https://github.com/Pavithra0601/Industrial-Canteen-Booking-Web-App/assets/174179024/104925e1-32bf-46a0-a0f2-a6a5de545185)


●	This is where the summary of all orders created within a specified date interval in displayed. Total number of orders is displayed for each and every item name. 

●	The respective total amount for item name is also calculated and displayed. 

●	Total orders weight for the item name is also calculated with the help of grams/packet with total orders.



**Print ticket:
**

![image 10](https://github.com/Pavithra0601/Industrial-Canteen-Booking-Web-App/assets/174179024/93e66c90-2d85-40d7-b833-f66ade0d51fc)


Ticket is printed when the print option is clicked on with all the necessary details required for the customer and admin.


**ADVANTAGES OF CANTEEN MANAGEMENT SYSTEM
**

●	Each and every order placed will be stored in the database tables for automatic calculation.

●	To increase efficiency of managing the Canteen, Sales. 

●	It also deals with monitoring the information and transactions of Items. 

●	It tracks all the information of Sales, Food, Items etc.
