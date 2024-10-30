# Bank
BankApp is a basic banking web application built using Spring Boot, 
with a focus on user authentication and account management. 
Users can register, log in, view their account balance, 
deposit and withdraw funds, transfer money to other users, 
and view transaction history.


Features

  User Registration and Login: Secure authentication using Spring Security.
  Account Management: Ability to deposit, withdraw, and transfer funds.
  Transaction History: View a complete history of transactions associated with each account.
  Secure Password Storage: Passwords are encrypted using BCrypt.
  Role-based Access: Only authenticated users can access account functionalities.



Tech Stack

  Java 17
  Spring Boot 3: Core framework for REST API and MVC.
  Spring Security: Provides authentication and authorization.
  Spring Data JPA: Simplifies data access and uses Hibernate for ORM.
  Thymeleaf: Template engine for rendering dynamic web pages.
  H2 Database (In-Memory): Used for development and testing.
  Getting Started
  Prerequisites
  Java Development Kit (JDK) 17 or higher
  Maven


  
Usage

  Register: Sign up for a new account by providing a username and password.
  Login: Log in using the credentials you provided during registration.
  Dashboard: View your balance and recent transactions.
  Deposit/Withdraw: Add or withdraw funds from your account.
  Transfer: Send funds to another registered user.
  Transaction History: View a complete history of deposits, withdrawals, and transfers.


  
Database Schema

  Account: Stores user details and account balance.
  Transaction: Stores transaction details linked to each account.


  
Endpoints

  /register: Register a new user account.
  /login: User login page.
  /dashboard: User dashboard with account balance.
  /transactions: Displays transaction history.
  /deposit: Endpoint for depositing funds.
  /withdraw: Endpoint for withdrawing funds.
  /transfer: Endpoint for transferring funds to another account.



Security

  Passwords are stored securely using BCrypt hashing.
  Access to the application is restricted to authenticated users.




Future Enhancements

  Add support for email notifications for transactions.
  Add support for two-factor authentication.
  Implement user roles for admin and regular users.
