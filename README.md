# NSW-Accommodation-web-portal
The aim of our project is to implement an Airbnb-like, local accommodation recommendation web portal, which contains a series of functions to help users to complete the property business transactions online, especially for those short-term renting properties in NSW territory, fast but effectively.
## Design of the functionalities
### 1. Accommodation search module
Both users and visitors could search the accommodation according to their requirements. The requirements include check in date, check out date, area selection and specific services, such as daytrip, translation, barrier free elevator, guide dog etc. Only the user could add the accommodation into their favorites, leave comments and add into order after login, these functions are permission denied for visitors.
### 2. User account management module
In the main page the visitors could choose either register or login. In the register part, visitor could create a new account by their email address, which is unique to their accommodation account. The existing user could login based on their email address and password.
### 3.User information review module
Publish a review about user’s information, order history and their available properties (only the properties owners have the properties review), all these must in the login status.
### 4.Profile modification module
Users could edit their basic information, which includes username, phone number, password and self-introduction.
### 5.Accommodation advertising module
Only the properties owners could publish/ edit the accommodation, the accommodation address is unique, which means the landlord is updating the existing properties if he fills in the address that already exists in the properties database, otherwise it is a new published accommodation. When in advertising page, users need to fill in the property title, address, capacity, price, suburb and the services they provide.
### 6.Favorites review module
Publish the review about their favourite accommodation. The accommodation could not be reviewed if it has been deleted by the owner.
### 7.Payment module
After the customer has chosen the house they like, they could click the “Pay Now” button on the single property page to pay for it. In the payment page, the top half of the page shows basic information about the selected house which includes house title, address, capacity and price. In the bottom half of the page, customers need to fill out a form which need them to provide the check-in date, check-out date, number of people, card details and contact information.

The information input would be checked whether they are in correct format. For example, the check-out date cannot be earlier than check-in date, the capacity must be integer. If the customer provided all the correct information, it would check the database whether the house could be rent during this period of time, because it might have been booked by another customer. If that happens, the payment would be fail, otherwise it would show payment successful and jump to personal information interface where the user could check its transaction record.
