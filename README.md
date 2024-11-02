# Online Pizza Delivery Web Application

## Overview
The Online Pizza Delivery Web Application provides a seamless platform for users to order pizza online. This application features a diverse user interface and stores various user-related data in a database. The process includes pizza selection, simulated payment, and real-time delivery status updates.

## Technologies Used
- **Frontend**: Angular 15
- **Backend**: Node.js 14
- **Database**: MongoDB
  
## Installation Instructions
For detailed installation instructions, check out the [Installation Guide](InstallationsDoc.txt)
```
$ git https://github.com/Swathi-Reddy1408/PizzaTime.git
$ cd OnlinePizzaOrderingSystemAngular
$ npm install
$ ng serve 
```

## Purpose of Database
The purpose of a database in the context of our online pizza ordering web application is to efficiently and securely manage and store various types of data associated with users, orders, and the overall system. This includes customer details, order information, transaction history, and delivery status. The database serves as a central repository for data, facilitating seamless interactions, order tracking, and ensuring a smooth user experience. It is essential for data integrity, accessibility, and effective management of information, contributing to the overall functionality and success of an application.

## User Profiles
There are two types of Users in this application.
Users
Admin

## Information and Functionalities of Users

### Admin
- **Registration**: 
  - Admin can register by entering:
    - Name
    - Email ID
    - Password
- **Login**: 
  - Admin can log in using:
    - Registered User ID
    - Password
- **Functionalities**:
  - Edit user information
  - Add items to the inventory
  - Update existing items
  - View orders
  - View feedback
  - Accept or reject orders

### User
- **Registration**: 
  - User can register by entering:
    - Name
    - Email ID
    - Password
- **Login**: 
  - User can log in using:
    - Registered User ID
    - Password
- **Functionalities**:
  - View user information
  - View items available for order
  - Add items to the cart
  - View cart
  - Checkout for payment
  - Place orders
  - Check the status of orders
  - Choose between delivery or pickup options
  - Write feedback

## Information Stored in Database

### Admin Information
- **Fields**:
  - `Id`
  - `Name`
  - `Email`
  - `Contact`
  - `Password`
  - `Role`

### Item Information
- **Fields**:
  - `Id`
  - `Item Name`
  - `Item Size`
  - `Item Price`
  - `Item Image`

### User Information
- **Fields**:
  - `Id`
  - `Name`
  - `Email`
  - `Contact`
  - `Password`
  - `Address`
  - `City`
  - `Pincode`
  - `State`

### Customizations Information
- **Fields**:
  - `Id`
  - `Items`
  - `Item Name`
  - `Item Size`
  - `Item Price`
  - `Item Image`
  - `Toppings`
  - `Style`
  - `Qty`
  - `Total Price`

### Orders Information
- **Fields**:
  - `Id`
  - `Item Name`
  - `Item Size`
  - `Item Price`
  - `Item Image`
  - `Toppings`
  - `Style`
  - `Qty`
  - `whichUser`
  - `delivery_type`
  - `delivery_status`
  - `delivery_address`

### Feedback Information
- **Fields**:
  - `Id`
  - `whichUser`
  - `Name`
  - `Message`
  - `CreatedAt`

### Payment Information
- **Fields**:
  - `whichUser`
  - `Payment Type`





