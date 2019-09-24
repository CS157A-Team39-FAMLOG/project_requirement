&nbsp;
# -FAMLOG-
&nbsp;

&nbsp;

&nbsp;

CS157A - Section 01

Team 39

&nbsp;

&nbsp;

*Benjamin Wen Shen Lee*

*Grace To*

*Jeffrey Nguyen*

&nbsp;

&nbsp;

&nbsp;

# Project Overview
&nbsp;


&emsp;

# System Environment
&nbsp;

![3-tier diagram](https://github.com/CS157A-Team39-FAMLOG/project_requirement/blob/master/structured_diagram_update.png)

                                      Structured diagram of the 3-tier architecture
&emsp;
###  *Hardware and Software used*
- Windows 10
- Apache
- Sublime Text
- PHPStorm
###  *RDBMS*
- MySQL Community Server 8.0.17
###  *Application Languages*
- HTML, CSS, JavaScript, XML, PHP, SQL

# Functional Requirements
&nbsp;

###  *Descriptions*
The application target each household as a unit. Each household can access the system by logging in with just one account. Each household may have multiple users as individuals. Each user can choose to access between personal list and master list. Each user has their own wanted shopping list of items. In the personal list, user can add his/her wanted items into the shopping list. User can also edit his/her items in their own shopping list (remove items/edit notes/edit name). In the master list, user can see the total shopping items of everyone in the house in descending priority order. In the master list, the person who purchased the items can select and enter the price they bought the items for. The application will calculate the total price of the items bought (the selected items will be automatically removed from the list). User can log out of the system

###  *Functions*
- Creating an account
- Creating users
- Create personal shopping list
- Display personal shopping list
- Edit personal shopping list
- Display master list view
- Order master list by
- Select items purchased
- Enter items’ prices
- Calculate the total price + tax

  
&emsp;

# Non-functional Issues
###  *Graphical User Interface*
- We plan to use Adobe XD to design the website interface and Adobe Photoshop to create necessary graphics. The interface should be minimal and easy to navigate, with clear selections to perform tasks. Firstly, there should be a login page, then a user selection. The user could then choose between Master List and Personal Shopping List, and the rest of the functions should be accessible through those screens.


###  *Security*
- Each household will have an account of its own. For more enhanced security, we might implement a passcode system for the users within that account, to make sure there is no misuse among users.


###  *Access Control*
- Our website should be available 24/7 on any browser, as long as users have access to the internet, and have also made an account for their household. Users of different accounts should also be able to access our website simultaneously without any interruptions while the other users are online. Users are also only allowed to alter information within their own household/user account. 


