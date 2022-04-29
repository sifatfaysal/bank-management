![](https://img.shields.io/badge/Project-bankmanagement-blue.svg)
![](https://img.shields.io/badge/Programming_Language-c-blue.svg)
![](https://img.shields.io/badge/ProjectType-ConsoleApp-red.svg)

This project in C you can create a new account, update information of an existing account, view and manage transactions, check the details of an existing account, remove existing account and view customers’ list. Overall, with this project, you can perform banking activities like in a REAL bank. Bank management mini project in C is a console application without graphics.

  
## Functions:

#The function for Customer Account Bank Management System is relatively short and easy to understand. I have divided this C mini project into many functions, most of which are related to different banking activities. Listed below are some of the more important functions which may help you understand the project better.

1. [menu():](#AddContact)      
This function displays the menu or welcome screen to perform different banking activities mentioned below.* 

2. [new_acc():](#SearchContact)   
This function creates a new customer account. It asks for some  personal and banking details of the customer such as name, date of birth, citizenship number, address and phone number. You can enter the amount to deposit and choose one type of deposit account – saving, current, fixed for 1 year, fixed for 2 years or fixed for 3 years.*

3. [view list():](#ModifyContact)  
With this function, you can view the customer’s banking information such as account number, name, address and phone number provided while creating the account.*

4. [edit():](#Display)        
This function has been used for changing the address and phone number of a particular customer account.*

5. [transact():](#DirectoryInfo)    
With this function, you can deposit and withdraw money to and from a particular customer account.*

6. [erase():](#DeleteContact)   <br/>
This function is for deleting a customer account.*

7. [see() :](#DeleteContact)   <br/>
This function shows account number, name, date of birth, citizenship number, age, address, phone number, type of account, amount deposited and date of deposit. It also displays the amount of interest corresponding to a particular account type.*

</br>
#In this bank management system project in C, file handling has been used for almost all functions. File has been used to store data related to new account, transaction, editing of account information and viewing of account information. I haven’t used file handling for the menu, interest calculation and password.
