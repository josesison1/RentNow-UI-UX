# "RentNow" Marketing Application 
 
<p align="center">
  <img width="800" height="350" src="https://github.com/josesison1/RentNow-UI-UX/blob/master/project%20pic.PNG"> </p>
  
  ---
            
## Table of Contents <a name="back-to-top"></a>

  1. [Application Description](#Application-Description)
  2. [Wireframe Design](#Wireframe-Design)
  3. [Entity Relationship Diagram (ERD)](#Entity-Relationship-Diagram)
  4. [Database Diagram](#Database-Diagram)
  5. [User Stories](#User-Stories)
  6. [Use Cases](#Use-Cases)
  7. [Use Case Diagram](#Use-Case-Diagram)
  8. [Requirements](#Requirements)
  9. [Requirements Table](#Requirements-Table)
  10. [Test Table](#Test-Table)
  
  ---
[back to top](#back-to-top)

  
  <p align="center">  
  
 ## Application Description   <a name="Application-Description"></a>
 
 </p> 
 
 
  
  This is a marketing application for users who are interested in renting items from others in their sorrounding area.
It will have features that can be easily be navigated through by users.

---
[back to top](#back-to-top)
## Wireframe Design <a name="Wireframe-Design"></a>

1. This is the main page of the website with a selection of "__LOGIN__" and "__SIGN UP__". 
![Main Page](https://github.com/josesison1/Project-Step-6-UI-UX/blob/master/1.png)
2. This is the __login__ page. Email and password are the required fields to log in.
![Login](https://github.com/josesison1/Project-Step-6-UI-UX/blob/master/2.png)
3. This is the __registration__ page with the required fields to create an account.
![Registration](https://github.com/josesison1/Project-Step-6-UI-UX/blob/master/3.png)
4. This is the __main page__ once user is logged in. It will have a "search bar" feature, next to it is the location feature where users can input their zip code or city. Top right corner is the users profile page. It also have the different category options.
![Logged In](https://github.com/josesison1/RentNow-UI-UX/blob/master/4.PNG)
5. Once the user browsing the website selects a category, in this example "__Games__". It will populate all item under games category within that area.
![Games category](https://github.com/josesison1/Project-Step-6-UI-UX/blob/master/5.png)
6. Once the user selects an item, this will be the next screen which displays the item description, pictures, length of rental, and it will show the other user who listed the item along with a message button for further questions.
![Nintendo Switch](https://github.com/josesison1/Project-Step-6-UI-UX/blob/master/6.png)
7. Once the user decides on the rental length and clicks on "Rent" it will automatically generate an automated message to the listed user. They will get a notification and discuss further action i.e transaction & meet up. The users will be responsible for the transaction and payments.

![Rent](https://github.com/josesison1/Project-Step-6-UI-UX/blob/master/7.png)


---
[back to top](#back-to-top)
## Entity Relationship Diagram (ERD) <a name="Entity-Relationship-Diagram"></a>

![ERD](https://github.com/josesison1/Project-Step-6-UI-UX/blob/master/NEW%20ERD%20PROJECT.png)

---
[back to top](#back-to-top)
 ## Database Diagram   <a name="Database-Diagram"></a>
 
![DatabaseDiagram](https://github.com/josesison1/RentNow-UI-UX/blob/master/Project%20ERD%20SQL.PNG)

---
[back to top](#back-to-top)
 ## User Stories   <a name="User-Stories"></a>
 
__As a__ homeowner with 30 acres of land in the middle of no where,
__I want__ a system where I could purchase or rent items from my neighbors nearby instead of driving 1 hour to the nearest shopping center. 
__So that__ it is more convenient for myself and will save me a lot of time.


__As a__ do it yourself (DIY) person, I always find myself crafting something new for my home,
__I need__ a system where I could borrow supplies and tools needed for my projects.
__So that__ I don't have to buy expensive tools or items that I would only use for 1 day.

---
[back to top](#back-to-top)
 ## Use Case(s) <a name="Use-Cases"></a>
 
 #### Scenario 1:
 
__Given__ the user to register for an account
and has filled out the registration form.

__When__ its the users first time using the application,

__Then__ user will be able to utilize the application once they create an account.


#### Scenario 2:

__Given__ the user logs in to the application
and request additional information on a specific listing.

__When__ they reach out and message the listing user,

__Then__ the listing user will get a notification message.


#### Scenario 3:

__Given__ the user post a listing up for rent
and picks the category the item is in.

__When__ the user completes all required fields for listing,

__Then__ the listing will be posted for others to view.


#### Scenario 4:

__Given__ the user is interested in renting an item
and decides the rental length.

__When__ the user clicks the "rent" button,

__Then__ the application will send an automated message to the listing user to let them know.


#### Scenario 5:

__Given__ the user is looking to expand outside his local area 
and is looking to network more than 30miles radius.

__When__ the user changes his location and radius miles,

__Then__ the application populate new searches that is within those set settings.
 
---
[back to top](#back-to-top)
 ## Use Case Diagram  <a name="Use-Case-Diagram"></a>
![ERD](https://github.com/josesison1/RentMeUp-SRS/blob/master/use%20case%20diagram.PNG)

---
[back to top](#back-to-top)
 ## Requirements  <a name="Requirements"></a>
1.0 Create new user account

    1.1 Verify all information input are correct format
    
    1.2 Verify both password entries match
    
    1.3 Verify registering user is 18 years old or over
    
2.0 User login

    2.1 Invalid error if user enters wrong username or password
    
    2.2 Lock out user after 3 failed login attempts
    
3.0 Rental Length

    3.1 Calculate rental cost per users rental length entry
    
4.0 Automated Message to listing user

    4.1 Generate automated message to the listing user once the other user selects "Rent Now" button
    

---
[back to top](#back-to-top)
 ## Requirements Table  <a name="Requirements-Table"></a>
|No.| Description|Test Method|Test ID|
|---|------------|-----------|-------|
|1.0|Create new user account|
|1.1|Verify all information input are correct format|
|1.2|Verify both password entries match|
|1.3|Verify registering user is 18 years old or over|
|2.0|User login|
|2.1|Invalid error if user enters wrong username or password|
|2.2|Lock out user after 3 failed login attempts|
|3.0|Rental Length|
|3.1|Calculate rental cost per users rental length entry|
|4.0|Automated Message to listing user|
|4.1|Generate automated message to the listing user once the other user selects "Rent Now" button|

