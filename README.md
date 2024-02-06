# Stock Market Management System

Stock Market Management System is a Python application that allows users to manage their stock portfolios, buy and sell shares of different companies, and track their wallet balances. This project is built using the CustomTkinter library for the graphical user interface and interacts with a MySQL database for user registration and data storage.


## Table of Contents

> [Features](#features)

> [Installation](#installation)

>[Usage](#usage)

> [Database Setup](#database-setup)

> [ER Diagram](#erd)

> [Screenshots](#screenshots)

> [Process Flow Diagram](#process-flow-diagram)


## Features

- User registration with details like full name, PAN card, Aadhar number, phone number, and initial balance.
- User login with phone number and password authentication.
- Display of the user's wallet balance.
- Buying and selling shares of different companies, with stock prices fetched from a database.
- Managing the user's portfolio, displaying the number of shares owned for each company.
- Option to add money to the wallet.
- User-friendly graphical user interface with a dark and light theme.

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Prem07a/Stock_Mangement_app.git
   ```

2. Install the required Python libraries:

   ```bash
   pip install -r ./requirements.txt
   ```

3. Database Setup:
   - Create a MySQL database.
   - Import the SQL script `stock_market_db.sql` provided in the repository to set up the database schema.
   - Update the database credentials in the `database_credentials.txt` file with the appropriate information, including the host, user, and password.

4. Run the application:

   ```bash
   python app.py
   ```

## Usage

- Upon launching the application, you can choose to either log in or sign up.
- If you are a new user, click on "Sign-Up" to register with your personal details and an initial balance.
- If you are an existing user, click on "Login" and enter your phone number and password to access your account.
- After logging in, you can view your wallet balance and your stock portfolio.
- You can also buy and sell shares of different companies from the available list.

## Database Setup

To set up the database, follow these steps:

1. Create a MySQL database.

2. Run the SQL script `Create.sql` provided in the repository on your MySQL workbench. This script will create the necessary tables and schema for the application.

3. Update the `database_credentials.txt` file with the correct database credentials, including the host, user, and password. This file is used by the application to connect to the database.

## ERD

![ERD](./images/erd.png)

## Screenshots

### Home Page
#### Dark Theme
![Homepage](./images/Homepage.png)
#### Light Theme
![Homepage](./images/Homepage_l.png)

### Login Page
#### Dark Theme
![Login](./images/login.png)
#### Light Theme
![Login](./images/login_l.png)

### Sign-Up Page
#### Dark Theme
![Sign-Up](./images/sign_up.png)
#### Light Theme
![Sign-Up](./images/sign_up_l.png)

### Dashboard
#### Dark Theme
![Dashboard](./images/dashboard.png)
#### Light Theme
![Dashboard](./images/dashboard_l.png)

### Orders
#### Dark Theme <br>
![Order](./images/order.png)
#### Light Theme <br>
![Order](./images/order_l.png)

## Process Flow Diagram

### Login/Sign-up Workflow
![homepage work flow](./images/lswork.png)

### Order Workflow
![Order flow](./images/orderflow.png)

