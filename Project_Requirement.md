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

The goal of this project is to build a web application that will allow households to maintain a centralized shopping list based upon the aggregated, separate lists created by the individuals.
The motivation is the facilitation of household shopping by giving all users under a household a view of the entire prioritized household shopping list while sustaining the personal lists. It will aid both the household as a whole and the individual user in the overall process of shopping for necessities and for groceries when others might be busy. The stakeholders of this product are the households with a number of users greater than or equalled to two that utilize this application. All those involved in the development of the project, such as the engineers and project managers, are also stakeholders. For this particular project, the application domain will be strictly maintained to the scope of a household. Many people have extraordinarily busy schedules, where even finding time to shop is difficult. The question we posed was why not have a list where a family or group of co-inhabitants have the ability to shop for others when they are out. The benefits to the users will be the ability for the individual user to view and to purchase items on the master list for others when they may already be shopping. The traditional personal shopping list will also be maintained should the user just necessitate their own shopping list. 

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

&emsp;
# Functional Requirements
&nbsp;

###  *Descriptions*
The application target is each household as a unit. Each household can access the system by logging in with just one account. Each household may have multiple users as individuals. Each user can choose to access between personal list and master list. Each user has their own wanted shopping list of items. In the personal list, an user can add his/her wanted items into the shopping list. The user can also edit his/her items in their own shopping list (remove items/edit notes/edit name). In the master list, the user can see the total shopping items of everyone in the particular household in descending priority order. In the master list, the person who purchased the items can select and enter the price they bought the items for. The application will calculate the total price of the items bought (the selected items will be automatically removed from the list). User can log out of the system

###  *Functions*
- Creating an account
	- Each household only needs to sign up for one account
	- Completion of the sign up form is necessary to successfully create an account
- Creating users
	- In each household account, user can add their name if its non-existent within that account
- Create personal shopping list
	- Each user has their own wanted items shopping list automatically created together with their user creation
- Display personal shopping list
	- User can view all the items in their personal shopping list
	- Sorting will also be available according to item priority 
- Edit personal shopping list
	- User can edit item name, notes, quantity, priority, or even remove the item
- Display Master List view
	- Master list combines personal lists of all users in the household
	- Master list displays priority of items, items’ details and quantity as well as whom it belongs to
- Order Master List items by priority
	- Master list view of items are ordered according to priority
- Select items purchased and Enter items’ prices
	- In the Master List, user selects all items that are bought and enters the prices
	- The items selected as purchased will be deleted from database
- Calculate the total price + tax

  
&emsp;

# Non-functional Issues
###  *Graphical User Interface*
- We plan to use Adobe XD to design the website interface and Adobe Photoshop to create necessary graphics. The interface should be minimal and easy to navigate, with clear selections to perform tasks. Firstly, there should be a login page, then a user selection. The user could then choose between Master List and Personal Shopping List, and the rest of the functions should be accessible through those screens.


###  *Security*
- Each household will have an account of its own. For more enhanced security, we might implement a passcode system for the users within that account, to make sure there is no misuse among users.


###  *Access Control*
- Our website should be available 24/7 on any browser, as long as users have access to the internet, and have also made an account for their household. Users of different accounts should also be able to access our website simultaneously without any interruptions while the other users are online. Users are also only allowed to alter information within their own household/user account. 


